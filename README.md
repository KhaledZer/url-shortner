# url-shortner


A high-performance URL shortening service that converts long URLs into compact, shareable short links. Built with a focus on low-latency redirects and scalability, the system routes every request through an API gateway for authentication and rate limiting before hitting the application server. Short link mappings are persisted in a relational database and written to a cache simultaneously, ensuring that the most common lookups never touch the database at all. On redirect, a cache-first strategy means users are sent to their destination in milliseconds, with a database fallback on cold misses that repopulates the cache automatically. Every click is recorded asynchronously to a NoSQL analytics store, keeping the critical redirect path clean and fast while still capturing full engagement data.

**Key design decisions:**
- Cache write-through on creation eliminates cold-start misses
- Async click tracking decouples analytics from redirect latency
- API gateway centralizes auth and rate limiting across both read and write flows
- Relational DB for link mappings, NoSQL for high-volume event logging