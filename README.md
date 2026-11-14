# ApnoAI Internship Task 2 — React Profile Card

A modern, responsive, 2026-style Glassmorphism Profile Card built using **React 18**, **Tailwind CSS**, and **Lucide Icons** in a single standalone HTML file (no complex build tools or npm dependencies required).

---

## 🌟 Live Demo
- **Live Vercel URL:** [Deploy on Vercel](https://vercel.com)
- **GitHub Repository:** [apnoai-task-2-dnyaneshwari](https://github.com)

---

## ✨ Features

- 💎 **Modern Glassmorphism UI:** Frosted glass effect with `backdrop-blur`, soft translucent borders, and ambient neon background orbs.
- 🌓 **Dark & Light Mode:** Seamless full-page theme toggling powered by React `useState`.
- 🧩 **Component Architecture:** Clean separation of concerns with `App` and `ProfileCard` components.
- 📥 **Props (Inputs):** Dynamic personal data passed into the component (Name, Role, Bio, Skills badges, Avatar, Social Links).
- 🧠 **State (Memory):**
  - Theme state (`isDark`, `setIsDark`)
  - **Bonus Feature (+10 XP):** Interactive Like / Endorse counter (`likes`, `setLikes`, `isLiked`)
  - Copy profile link with feedback (`copied`, `setCopied`)
- 📱 **Fully Responsive:** Looks gorgeous on mobile, tablet, and desktop screens.

---

## 💡 React Concepts Explained

### 1. Props (Inputs passed IN)
Props are read-only properties passed from the parent component down to the child component:
```jsx
function ProfileCard({ name, role, bio, skills, avatar, socialLinks }) {
  // Renders profile information dynamically
}
```

### 2. State (Dynamic Memory)
State holds data that can change over time based on user interactions:
```jsx
// Theme toggle state
const [isDark, setIsDark] = useState(true);

// Bonus interactive counter (+10 XP)
const [likes, setLikes] = useState(42);
```

---

## 🛠️ Tech Stack

- **React 18** (via CDN)
- **Babel Standalone** (in-browser JSX compilation)
- **Tailwind CSS** (via CDN)
- **Lucide Icons**

---

## 🚀 How to Run Locally

1. Clone or download this repository.
2. Open `index.html` directly in any web browser (Chrome, Edge, Firefox, Brave).
3. No `npm install` or build step required!

---

*Created for ApnoAI Internship - Task 2 by Dnyaneshwari.*

