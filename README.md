# GitPush V11 — Use Karne Ki Guide

## 🔗 App Link
**https://tecno2p.github.io/gitpush-app/**

---

## Step 1 — GitHub Token Banana

1. GitHub.com pe jao → apni profile photo pe click karo
2. **Settings** → **Developer settings** (sabse neeche)
3. **Personal access tokens** → **Tokens (classic)**
4. **Generate new token (classic)** click karo
5. Yeh permissions select karo:
   - ✅ `repo` (full repo access)
   - ✅ `workflow` (GitHub Actions)
   - ✅ `delete_repo` (repo delete karne ke liye)
   - ✅ `notifications`
6. **Generate token** click karo
7. Token copy karo — ek baar hi dikhta hai!

---

## Step 2 — App Mein Login

1. App open karo: https://tecno2p.github.io/gitpush-app/
2. Token paste karo input box mein
3. **Sign In** click karo
4. Tera GitHub account load ho jayega

---

## Features Aur Use Karna

### 📤 Files Upload Karna
1. Left sidebar mein **Upload** click karo
2. **Repository** select karo (ya "All Repos" sab mein ek saath)
3. **Branch** select karo (default: main)
4. Files drag-drop karo ya click karke select karo
   - Single files, multiple files, folders, ZIP — sab kaam karta hai
5. **Commit message** likho
6. **Upload to GitHub** click karo
7. Live progress bar aur file-by-file status dikhega

### 📡 All Repos Pe Ek Saath Push
1. Upload page pe Repository dropdown mein **"All Repositories"** select karo
2. Files select karo
3. **Push to All Repos** click karo — har repo mein automatically jayega

### 📁 File Manager
1. Sidebar mein **Files** click karo
2. Repo aur branch select karo
3. Files browse, download, delete, rename kar sakte ho
4. **New File / New Folder** bana sakte ho directly

### ✏️ Online Editor
1. Sidebar mein **Editor** click karo
2. Repo select karo → file path likho → **Load** karo
3. Code edit karo
4. **Commit Changes** click karo — seedha GitHub pe save ho jayega

### 🗑️ Multiple Repos Delete Karna
1. **Repositories** page pe jao
2. Top-right **"☑ Select"** button click karo
3. Jo repos delete karni hain unhe click karo (red border aayega)
4. **"Select All"** se sab select kar sakte ho
5. **"🗑 Delete Selected"** click karo
6. `delete all` type karo confirm karne ke liye
7. Progress bar se dekho kitni delete huin

### 📊 Dashboard
- Tera GitHub activity, stars, repos ka overview
- Recent commits aur notifications

### 🔔 Notifications
- Sidebar mein bell icon — saari GitHub notifications
- Click karke directly issue/PR pe jao
- **✓** se mark as read

### ⚙️ Actions / Workflows
- Repo ke GitHub Actions dekho
- Workflow manually trigger karo
- Build status live dekho (queued/running/done/failed)

### 🔒 Secrets Manager
- Repo ke GitHub Secrets add/delete karo
- Encrypted store hote hain

### 📄 Commits History
- Repo ke commits dekho
- Kisi commit pe click karo — changed files aur diff dikhega

---

## 💡 Tips

| Tip | Kaise |
|-----|-------|
| Multiple accounts | Header mein **+ Add Account** — multiple GitHub accounts switch karo |
| Pin repos | Repo card pe **📌 Pin** — sidebar mein shortcut aa jayega |
| Dark/Light mode | Header mein **🌙/☀️** button |
| Dry Run | Upload karne se pehle **Dry Run** toggle on karo — actually upload nahi hoga, sirf simulate karega |
| Cancel upload | Upload ke dauran **⏹ Cancel** button aata hai |
| Export repo list | Repositories page → **⬇️ Export CSV** |

---

## ❓ Common Issues

**Token invalid error**
→ Token mein `repo` permission check karo

**Delete nahi ho raha**
→ Token mein `delete_repo` permission add karo

**Upload fail ho raha hai**
→ File size 50MB se kam honi chahiye per file

**Branch nahi dikh raha**
→ Repo mein pehle koi commit hona chahiye (empty repo mein branch nahi hoti)

---

## 🔐 Security

- Tera token sirf tere browser mein save hota hai (localStorage)
- Koi server nahi hai — sab kuch directly GitHub API se hota hai
- App ka code open source hai: https://github.com/Tecno2P/gitpush-app

