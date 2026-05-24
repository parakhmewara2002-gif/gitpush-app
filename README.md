# GitPush V11 — GitHub Manager

> Apna personal GitHub manager — browser mein, koi installation nahi

## 🔗 Live App
**👉 [https://parakhmewara2002-gif.github.io/gitpush-app/](https://parakhmewara2002-gif.github.io/gitpush-app/)**

---

## 🚀 Quick Start

### Step 1 — GitHub Token Banana
1. GitHub.com → Profile photo → **Settings**
2. **Developer settings** → **Personal access tokens** → **Tokens (classic)**
3. **Generate new token (classic)** click karo
4. Yeh permissions select karo:

| Permission | Kisliye |
|-----------|---------|
| ✅ `repo` | Repos read/write |
| ✅ `workflow` | GitHub Actions |
| ✅ `delete_repo` | Repos delete karna |
| ✅ `notifications` | Notifications dekhna |

5. **Generate token** → Copy karo (ek baar hi dikhta hai!)

### Step 2 — Login
1. App open karo → Token paste karo → **Sign In**
2. Bas! Tera GitHub account load ho jayega

---

## ✨ Features

### 📤 File Upload
- Single file, multiple files, folder, ZIP — sab support
- **All Repos** option — ek saath saare repos mein push
- Live progress bar — file-by-file status (queued → uploading → done)
- Dry run mode — pehle simulate karo, phir upload
- Conflict handling — overwrite / rename / skip

### 📁 File Manager
- Repo ke files browse karo
- Files download, delete, rename karo
- Naya file ya folder banao directly

### ✏️ Online Editor
- Browser mein code edit karo
- Seedha GitHub pe commit ho jata hai
- Syntax highlighting support

### 🗑️ Bulk Repo Delete
- Multiple repos ek saath select karo
- Ek click mein sab delete — progress bar ke saath

### 📊 Dashboard
- GitHub activity overview
- Recent commits, stars, repo stats

### 🔔 Notifications
- Saari GitHub notifications ek jagah
- Click karke directly issue/PR pe jao

### ⚙️ GitHub Actions
- Workflows dekho aur manually trigger karo
- Build status live — queued / running / done / failed

### 🔒 Secrets Manager
- Repo secrets add/delete karo

### 🌿 Branch Manager
- Branches create/delete karo

### 📝 Commits History
- Commits dekho with diff view

### 👥 Multi Account
- Multiple GitHub accounts ek saath manage karo

---

## 💡 Tips

| Tip | Kaise |
|-----|-------|
| Repos pin karo | Repo card → **📌 Pin** → sidebar shortcut |
| Dark/Light mode | Header mein **🌙 / ☀️** button |
| Upload cancel | Upload ke dauran **⏹ Cancel** button |
| Dry Run | Upload se pehle toggle on karo |
| CSV export | Repositories → **⬇️ Export CSV** |
| All repos push | Upload → Repository → **📡 All Repositories** |

---

## ❓ Common Issues

**Token invalid error**
→ Token mein `repo` permission check karo

**Delete nahi ho raha (403)**
→ Token mein `delete_repo` permission add karo

**Upload fail**
→ File 50MB se kam honi chahiye

**Branch nahi dikh raha**
→ Repo mein pehle ek commit hona chahiye

**Actions trigger nahi ho raha**
→ Token mein `workflow` permission check karo

---

## 🔐 Security

- Token sirf **tere browser** mein save hota hai (localStorage)
- Koi server nahi — sab directly **GitHub API** se
- App completely **client-side** hai

---

## 📦 Tech Stack

- Pure HTML + CSS + JavaScript — koi framework nahi
- GitHub REST API v3
- PWA support (install as app)
- highlight.js, marked.js, Chart.js, DOMPurify, JSZip

---

*GitPush V11 — Made with ❤️*
