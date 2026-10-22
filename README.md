# 🚀 Top 1% Android, KMP & Mobile AI Roadmap Tracker (ChatGPT UI)

[![Live Website](https://img.shields.io/badge/Live_Site-Visit_Roadmap-10a37f?style=for-the-badge&logo=openai&logoColor=white)](https://harik90.github.io/TUDO_DEV_TOP1/)
[![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-22c55e?style=for-the-badge&logo=github&logoColor=white)](https://harik90.github.io/TUDO_DEV_TOP1/)

### 🌐 Live Hosted URL:
👉 **[https://harik90.github.io/TUDO_DEV_TOP1/](https://harik90.github.io/TUDO_DEV_TOP1/)**

---

A senior mobile engineering roadmap tracker built in the authentic **ChatGPT App Design**, featuring:
- **Custom Engineer Profile**: Change your name, goal/role (e.g. "Staff Mobile AI Engineer"), and initials with real-time sync.
- **Skill Notes & Doubts**: Attach personal doubts, cheat-sheet points, code snippets, or reference links to any skill card.
- **Notes Filter**: Quickly filter your entire roadmap to view only topics where you have active notes or open doubts.
- **Dark & Light Mode**: Authentic ChatGPT dark (`#212121`) and light (`#ffffff`) theme toggling with smooth transition.
- **Hierarchical Structure**: 106 Parent Capabilities and 424 Granular Sub-concepts (530 total trackable checkpoints).
- **Progressive Disclosure**: Multi-view navigation (Overview Dashboard + Dedicated Category Tracks) so everything is clean and not crowded onto a single screen.
- **Firebase Realtime Database (RTDB)**: Dynamic, zero-hardcoding Firebase connection. On first launch, paste your Firebase Web Config JSON or Android `google-services.json` and it automatically connects and syncs checks, notes, and profile in real time!
- **Local Fallback**: Works 100% offline via `localStorage` even if you choose not to connect Firebase.
- **Realtime Search**: Filter across all 106 parent skills, 424 sub-concepts, and personal notes from the ChatGPT prompt composer bar at the bottom.
- **Export / Import**: Complete JSON backup and restore capabilities (includes checks, notes, and profile).
- **Copy for ChatGPT**: Export your entire checklist along with your notes/doubts as a Markdown prompt for personalized mock interviews or study plans.

---

## 🗂 Architecture & Tracks

1. **Languages & Compilers** (17 Parent Skills • 68 Sub-concepts)
2. **KMP Stack** (24 Parent Skills • 96 Sub-concepts)
3. **Mobile AI & Edge** (26 Parent Skills • 104 Sub-concepts)
4. **Backend & Infra** (16 Parent Skills • 64 Sub-concepts)
5. **APIs & Protocols** (6 Parent Skills • 24 Sub-concepts)
6. **Mobile System Design** (10 Parent Skills • 40 Sub-concepts)
7. **Career Leverage** (7 Parent Skills • 28 Sub-concepts)

---

## 🔥 Firebase Realtime Database Setup

1. Open **[https://harik90.github.io/TUDO_DEV_TOP1/](https://harik90.github.io/TUDO_DEV_TOP1/)**.
2. A setup modal will pop up asking for your Firebase configuration.
3. Paste either:
   - **Firebase Web Config JSON** from Firebase Console (Project Settings > Web App)
   - Or **google-services.json** from your Android project.
4. Click **Connect & Sync Database**.
5. The site automatically parses the `databaseURL`, `apiKey`, and `projectId`, initializes Firebase, and syncs your checked state, personal notes, and profile in real time!
6. To update your database URL or disconnect, click the database pill in the top header or the status button at the bottom of the sidebar.

---

## 💻 Tech Stack

- **UI Framework**: Vanilla JavaScript + ChatGPT authentic UI tokens
- **Styling**: Responsive CSS with Dark/Light mode theme system
- **Icons**: Bootstrap Icons
- **Database**: Firebase Realtime Database (Compat SDK) + `localStorage` fallback
- **Hosting**: GitHub Pages
