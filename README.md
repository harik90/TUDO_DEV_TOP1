# 🚀 Top 1% Android, KMP & Mobile AI Roadmap Tracker (ChatGPT UI)

A senior mobile engineering roadmap tracker built in the authentic **ChatGPT App Design**, featuring:
- **Hierarchical Structure**: 106 Parent Capabilities and 424 Granular Sub-concepts (530 total trackable checkpoints).
- **Progressive Disclosure**: Multi-view navigation (Overview Dashboard + Dedicated Category Tracks) so everything is clean and not crowded onto a single screen.
- **Firebase Realtime Database (RTDB)**: Dynamic, zero-hardcoding Firebase connection. On first launch, paste your Firebase Web Config JSON or Android `google-services.json` and it automatically connects and syncs in real time!
- **Local Fallback**: Works 100% offline via `localStorage` even if you choose not to connect Firebase.
- **Realtime Search**: Filter across all 106 parent skills and 424 sub-concepts from the ChatGPT prompt composer bar at the bottom.
- **Export / Import**: JSON backup and restore capabilities.
- **Copy for ChatGPT**: Export your entire checklist as a Markdown prompt for personalized mock interviews or study plans.

---

## 🗂 Architecture

1. **Languages & Compilers** (17 Parent Skills • 68 Sub-concepts)
2. **KMP Stack** (24 Parent Skills • 96 Sub-concepts)
3. **Mobile AI & Edge** (26 Parent Skills • 104 Sub-concepts)
4. **Backend & Infra** (16 Parent Skills • 64 Sub-concepts)
5. **APIs & Protocols** (6 Parent Skills • 24 Sub-concepts)
6. **Mobile System Design** (10 Parent Skills • 40 Sub-concepts)
7. **Career Leverage** (7 Parent Skills • 28 Sub-concepts)

---

## 🔥 How Firebase Realtime Database Works

1. Open `index.html`.
2. A setup modal will pop up asking for your Firebase configuration.
3. Paste either:
   - **Firebase Web Config JSON** from Firebase Console (Project Settings > Web App)
   - Or **google-services.json** from your Android project.
4. Click **Connect & Sync Database**.
5. The site automatically parses the `databaseURL`, `apiKey`, and `projectId`, initializes Firebase, and syncs your checked state in real time across any device or browser tab!
6. To update your database URL or disconnect, click the database pill in the top header or the status button at the bottom of the sidebar.

---

## 🌐 Deploy to GitHub Pages (When Ready to Push)

```bash
git push -u origin main
```
Then enable GitHub Pages under **Settings > Pages** (`main` branch, `/ (root)` folder).
