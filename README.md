<div align="center">

# 🏆 GitHub Achievement Badges Guide

### A comprehensive guide to unlocking all GitHub profile achievement badges

[![GitHub Stars](https://img.shields.io/github/stars/tamerawedan-ctrl/badges?style=for-the-badge&logo=github&color=gold)](https://github.com/tamerawedan-ctrl/badges/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/tamerawedan-ctrl/badges?style=for-the-badge&logo=github&color=blue)](https://github.com/tamerawedan-ctrl/badges/network)
[![GitHub License](https://img.shields.io/github/license/tamerawedan-ctrl/badges?style=for-the-badge&color=green)](LICENSE)

---

*⭐ Star this repo to help others discover it — and to help me unlock the **Starstruck** badge!*

</div>

---

## 📋 Table of Contents

- [What Are GitHub Achievements?](#-what-are-github-achievements)
- [Achievement Badges](#-achievement-badges)
  - [🫛 Pair Extraordinaire](#-pair-extraordinaire)
  - [🟡 YOLO](#-yolo)
  - [🌟 Starstruck](#-starstruck)
  - [🦈 Pull Shark](#-pull-shark)
- [How to Earn Each Badge](#-how-to-earn-each-badge)
- [Badge Tiers](#-badge-tiers)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🎯 What Are GitHub Achievements?

GitHub Achievements are special badges that appear on your GitHub profile when you complete certain actions on the platform. They showcase your contributions and activity to the developer community. Each achievement can have multiple tiers (Bronze → Silver → Gold) based on the number of times you've completed the action.

---

## 🏅 Achievement Badges

### 🫛 Pair Extraordinaire

| Property | Details |
|----------|---------|
| **Icon** | 🫛 (Pea Pod) |
| **Description** | Co-authored a commit with another developer |
| **How to Unlock** | Add a `Co-authored-by` trailer to your commit message |
| **Tiers** | x1 (1 PR), x2 (10 PRs), x3 (24 PRs), x4 (48 PRs) |

**How it works:**

When creating a commit, add the following line at the end of your commit message (after a blank line):

```
Your commit message here

Co-authored-by: Partner Name <partner@example.com>
```

**Example:**

```bash
git commit -m "feat: add new login feature

Co-authored-by: John Doe <john@example.com>"
```

> **💡 Tip:** The co-author must have a valid GitHub account with the email address used in the trailer. The commit must be part of a merged Pull Request.

---

### 🟡 YOLO

| Property | Details |
|----------|---------|
| **Icon** | 🟡 (Colorful YOLO badge) |
| **Description** | Merged a Pull Request without any code review |
| **How to Unlock** | Merge a PR that has zero reviews |
| **Tiers** | Single tier (no progression) |

**How it works:**

1. Create a repository (or use an existing one you own)
2. Create a new branch
3. Make changes and push the branch
4. Open a Pull Request
5. Merge the PR **without requesting or receiving any reviews**

```bash
# Create and switch to a new branch
git checkout -b feature/yolo-badge

# Make some changes
echo "YOLO - You Only Live Once!" > yolo.txt

# Commit and push
git add .
git commit -m "feat: YOLO badge unlock"
git push origin feature/yolo-badge

# Then go to GitHub and merge the PR without any reviews
```

> **⚠️ Note:** "You Only Live Once" — this badge celebrates the bold move of shipping without review. Best done on personal repos, not production code! 😄

---

### 🌟 Starstruck

| Property | Details |
|----------|---------|
| **Icon** | 😻 (Cat with star eyes) |
| **Description** | Your repository received a significant number of stars |
| **How to Unlock** | Have a repository you own reach 16+ stars |
| **Tiers** | x1 (16 ⭐), x2 (128 ⭐), x3 (512 ⭐), x4 (4096 ⭐) |

**How it works:**

1. Create a useful open-source project or tool
2. Share it with the developer community
3. When your repo reaches 16 stars, you unlock the first tier!

**Tips to get more stars:**

- 📦 Build useful developer tools (CLI tools, libraries, frameworks)
- 📝 Write excellent documentation with clear README files
- 🎨 Add badges, screenshots, and demos to your repo
- 📢 Share your project on social media, Reddit, Dev.to, etc.
- 🤝 Contribute to communities and share your work
- 🏷️ Use relevant topics/tags on your repository

> **🌟 Pro Tip:** Projects like Python PDF management tools, diagnostic utilities (Mini Diag), or developer productivity tools tend to attract stars naturally when they solve real problems!

---

### 🦈 Pull Shark

| Property | Details |
|----------|---------|
| **Icon** | 🦈 (Shark) |
| **Description** | Opened Pull Requests that were merged |
| **How to Unlock** | Have your Pull Requests accepted and merged |
| **Tiers** | x1 (2 PRs), x2 (16 PRs), x3 (128 PRs), x4 (1024 PRs) |

**How it works:**

1. Fork a repository or work on your own
2. Create a branch and make meaningful changes
3. Open a Pull Request
4. Get the PR reviewed (optional) and merged

```bash
# Fork and clone a repo
git clone https://github.com/your-username/some-repo.git

# Create a feature branch
git checkout -b fix/improve-docs

# Make changes, commit, and push
git add .
git commit -m "docs: improve installation instructions"
git push origin fix/improve-docs

# Open a PR on GitHub and get it merged!
```

> **💡 Tip:** Contributing to open-source projects is a great way to earn this badge while helping the community! Look for "good first issue" labels.

---

## 📊 Badge Tiers

All tiered badges follow this progression:

| Tier | Visual | Meaning |
|------|--------|---------|
| 🥉 Default | Base badge | First unlock |
| 🥈 Bronze (x2) | Badge + x2 marker | Intermediate milestone |
| 🥇 Silver (x3) | Badge + x3 marker | Advanced milestone |
| 💎 Gold (x4) | Badge + x4 marker | Expert milestone |

---

## 🎮 Quick Reference

| Badge | Action Required | Minimum to Unlock |
|-------|----------------|-------------------|
| 🫛 Pair Extraordinaire | Co-author commits via merged PR | 1 merged PR with co-author |
| 🟡 YOLO | Merge PR without review | 1 unreviewed merge |
| 🌟 Starstruck | Get stars on your repo | 16 stars |
| 🦈 Pull Shark | Get PRs merged | 2 merged PRs |

---

## 🤝 Contributing

Contributions are welcome! If you know of additional achievement badges or have tips to share:

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/new-badge-info`)
3. Commit your changes (`git commit -m 'Add info about new badge'`)
4. Push to the branch (`git push origin feature/new-badge-info`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

### 🌟 If you found this guide helpful, please give it a star! 🌟

*Every star helps me unlock the **Starstruck** badge and makes this guide more visible to other developers.*

**Made with ❤️ by [tamerawedan-ctrl](https://github.com/tamerawedan-ctrl)**

</div>
