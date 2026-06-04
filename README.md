# URL Shortener — Project Plan

This branch hosts the **live project plan and progress tracker** for the URL Shortener pair programming project.

## 🌐 Live Page

Access the project plan at: **[https://khaldzer.github.io/url-shortner/](https://khaldzer.github.io/url-shortner/)**

Both developers can open this link anytime to:
- Review the 13-phase roadmap
- Check checkpoints and requirements
- Track personal progress with interactive checkboxes

## 📝 What's in this branch

- `index.html` — The complete project plan with all 13 phases, concepts, checkpoints, and pair programming exercises
- `favicon.svg` — Browser tab icon (blue link icon)
- `README.md` — This file

The HTML is **self-contained** — all CSS and JavaScript are inline, no external dependencies needed.

## ✅ Progress Tracking

Each phase has interactive checkboxes. Your progress is saved in your browser's **localStorage**:
- Check boxes as you complete tasks
- Progress persists even after closing the tab
- Click "Reset" at the top to clear all progress
- The sticky progress bar shows overall completion percentage

**Note:** Progress is stored locally in each browser. To share updates, discuss what you've completed in your next sync or issue check-in.

## 🔄 Making Changes

To update the project plan:

1. Switch to this branch:
   ```bash
   git switch docs/github-pages
   ```

2. Edit `index.html` in your editor

3. Commit and push:
   ```bash
   git add index.html
   git commit -m "docs: update phase X"
   git push
   ```

4. Changes will be live on GitHub Pages within 1-2 minutes

## 📖 How to Use the Plan

**Phase Structure:**
- Each phase has a goal, big picture explanation, and key concepts
- Color-coded callouts (CONCEPT, HINT, GIT, PAIR, GOTCHA, STRETCH) guide you
- Ownership is split between Dev A and Dev B for both backend and frontend
- Checkpoints at the end confirm understanding and completion

**Before You Start:**
1. Read Phase 0 (Foundations) and Phase 1 (Read the Map) together as a pair
2. Don't skip the concepts — confusion is the work, breaking it down is the skill
3. Open GitHub Issues for blockers instead of grinding alone
4. Commit small, review code, keep PRs under control

## 🛠 Customization

Want to modify the plan? The HTML includes:
- Color variables for different roles and callout types
- Flexible phase sections that can be copied for new phases
- Responsive design that works on mobile and desktop

## Questions?

- Open a GitHub Issue in the main repo
- Check the links to resources in each phase
- Sync with your pair partner regularly

---

**Happy shipping!** 🚀
