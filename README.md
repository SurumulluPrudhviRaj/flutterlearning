# flutter_concepts

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.



You're absolutely right! Here's a clean step-by-step breakdown for using `git remote add` and pushing code using a custom remote name:

---

## ✅ Step-by-Step Git Commands:

### 1. **Add a remote with a custom name**
```bash
git remote add myremote https://github.com/yourusername/your-repo.git
```
- `myremote` → this is the **custom name** you're giving to the remote
- You can use any name instead of `origin` (default)

---

### 2. **Verify it was added**
```bash
git remote -v
```

Output should show:
```
myremote  https://github.com/yourusername/your-repo.git (fetch)
myremote  https://github.com/yourusername/your-repo.git (push)
```

---

### 3. **Push code to that remote**
```bash
git push myremote master
```

> Replace `master` with `main` if your branch is named `main`:
```bash
git push myremote main
```

---

✅ That’s it! You’ve pushed your code using a **custom remote name** instead of the default `origin`.

Let me know if you want to rename, remove, or change a remote too!