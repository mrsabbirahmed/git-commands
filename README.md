# 🚀 Git & GitHub Commands

# 👤 Git Global Setup — FIRST

### Set Username

```bash
git config --global user.name "mrsabbirahmed"
```

### Set Email

```bash
git config --global user.email "mdsabbirahmed0a@gmail.com"
```

### Check Username

```bash
git config --global user.name
```

### Check Email

```bash
git config --global user.email
```

---

# ⭐ Quick Reminder

## প্রতিদিন Code করার পর

```bash
git status
git add .
git commit -m "Update code"
git push
```

---

# 🚀 নতুন Project GitHub-এ প্রথমবার Upload

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/USERNAME/REPOSITORY.git
git push -u origin main
```

---

# 📥 Clone Repository

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
```

---

# ⬇️ Get Latest Code

```bash
git pull
```

Or:

```bash
git pull origin main
```

---

# 📊 Status & Changes

### Check Status

```bash
git status
```

### See Changes

```bash
git diff
```

---

# ➕ Add Files

### Add All Files

```bash
git add .
```

### Add Specific File

```bash
git add filename
```

---

# 💾 Commit

### Commit Changes

```bash
git commit -m "Update code"
```

### Initial Commit

```bash
git commit -m "Initial commit"
```

### See Commit History

```bash
git log
```

### Short Commit History

```bash
git log --oneline
```

---

# ⬆️ Push

### Normal Push

```bash
git push
```

### First Push

```bash
git push -u origin main
```

### Push Specific Branch

```bash
git push -u origin branch-name
```

---

# 🔗 Remote Repository

### Check Remote

```bash
git remote -v
```

### Add Remote

```bash
git remote add origin https://github.com/USERNAME/REPOSITORY.git
```

### Change Remote

```bash
git remote set-url origin https://github.com/USERNAME/REPOSITORY.git
```

### Remove Remote

```bash
git remote remove origin
```

---

# 🌿 Branch

### See Branches

```bash
git branch
```

### Create New Branch

```bash
git branch feature-name
```

### Create & Switch to New Branch

```bash
git switch -c feature-name
```

### Switch Branch

```bash
git switch main
```

### Delete Branch

```bash
git branch -d feature-name
```

### Push New Branch

```bash
git push -u origin feature-name
```

---

# 🔄 Merge Branch

```bash
git switch main
git pull origin main
git merge feature-name
git push origin main
```

---

# ↩️ Undo Changes

### Unstage File

```bash
git restore --staged filename
```

### Discard Changes in a File

```bash
git restore filename
```

### Undo Last Commit — Keep Changes

```bash
git reset --soft HEAD~1
```

### Undo Last Commit — Delete Changes

```bash
git reset --hard HEAD~1
```

⚠️ `git reset --hard` ব্যবহারে সাবধান। এতে uncommitted changes হারাতে পারে।

---

# 🗑️ Remove File from Git

```bash
git rm filename
```

Then:

```bash
git commit -m "Remove file"
git push
```

---

# 🔐 .gitignore

Project-এর root folder-এ `.gitignore` file রাখতে পারো:

```gitignore
node_modules/
.env
.env.local
dist/
build/
.next/
.DS_Store
coverage/
npm-debug.log*
```

⚠️ Password, API key, token বা `.env` file GitHub-এ upload করবে না।

---

# ⚙️ Git Version

```bash
git --version
```

---

# 📌 My Git Information

**GitHub Username:** `mrsabbirahmed`

**Git Email:** `mdsabbirahmed0a@gmail.com`
