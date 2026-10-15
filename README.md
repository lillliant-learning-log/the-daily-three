# Daily 3 ✦

> A minimalist, distraction-free daily focus tool built on the **Rule of 3** productivity principle.

Daily 3 helps you cut through task paralysis and prioritize what genuinely matters each day. Instead of managing endless, overwhelming to-do lists, Daily 3 limits you to **three active tasks at a time**—encouraging intentionality, deep focus, and completion.

---

## ✨ Features

- **Strict Focus Limiting (Rule of 3)**: You can only have up to 3 active tasks simultaneously. Adding another task requires finishing or clearing an existing one.
- **End-of-Day Review & Celebration**:
  - Conclude your day to view your completion rate and task breakdown.
  - Custom canvas confetti celebration when you crush your goals.
  - Daily rotating mindset and focus reflections.
- **Zero Dependencies & Single-File Architecture**:
  - Built entirely with vanilla HTML, modern CSS, and plain JavaScript in a single `index.html`.
  - No build tools, bundlers, or `node_modules` required.
- **Local Persistence (`localStorage`)**:
  - Tasks, theme preference, and day state persist across browser sessions automatically.
  - 100% private: no tracking, no backend, and no sign-up needed.
- **Refined Monospace Aesthetic**:
  - Minimalist terminal-inspired typography and micro-interactions.
  - Light and Dark modes with smooth transitions.
  - Live tabular digital clock and date counter.
- **Accessible & Responsive**:
  - Keyboard-navigable controls and semantic ARIA labeling.
  - Respects user accessibility preferences (`prefers-reduced-motion`).
  - Mobile-responsive layout.

---

## 🚀 Quick Start

No servers, runtimes, or installations needed. It is a completely static, single-file web app:

1. Clone or download this repository:
   ```bash
   git clone https://github.com/lillliant-learning-log/the-daily-three.git
   cd the-daily-three
   ```
2. Open [index.html](file:///Users/christinewong/GitHub/Daily%20Three%20Focus%20Website/index.html) directly in any browser:
   ```bash
   # On macOS
   open index.html

   # On Linux
   xdg-open index.html

   # On Windows
   start index.html
   ```
   *(Or simply double-click `index.html` in your file explorer.)*

---

## 🛠️ Deploying to the Web

Deploying Daily 3 takes seconds because it requires no build pipeline:

### GitHub Pages
1. Go to your repository settings on GitHub.
2. Under **Pages** (in the sidebar), select **Deploy from a branch**.
3. Choose the `main` branch and `/ (root)` folder, then click **Save**.
4. Your site will be live at `https://<username>.github.io/<repo-name>/`.

### Vercel / Netlify / Cloudflare Pages
- Drop the folder directly into [Netlify Drop](https://app.netlify.com/drop) or link the repository to [Vercel](https://vercel.com) / [Cloudflare Pages](https://pages.cloudflare.com) using default static hosting settings.

---

## ⌨️ How It Works

1. **Add Focus Items**: Enter up to 3 tasks you intend to accomplish today.
2. **Execute & Check Off**: Click `[ ]` to mark a task as completed `[x]`. Completing an item frees up space if you need to add another focus target.
3. **End the Day**: When you are finished working, click **End Day** to inspect your day's summary, celebrate your wins with confetti, and reset your mind for tomorrow.
4. **Start Fresh**: Use **Start New Day** to clear the slate and prepare for tomorrow's priorities.

---

## 📂 Project Structure

```
.
├── index.html       # Complete application (markup, styling, animations, logic)
└── README.md        # Project documentation
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
