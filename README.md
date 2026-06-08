# 🚀 Women in Tech Hackathon — Version Control Practice

Welcome! This exercise will walk you through the basics of **Git and version control** by adding your own file to this shared repository. By the end, you'll have cloned a repo, created a file, and pushed your first commit. 

---

## 📋 What You'll Be Doing

1. Clone this repository to your local machine
2. Create a personal `.md` or `.txt` file
3. Answer a few short reflection questions inside it
4. Commit and push your changes back to the repo

---

## 🛠️ Step 1 — Clone the Repository

Open your terminal and run:

```bash
git clone https://github.com/fuzzylabs/hackathon-introductions.git
```

Then move into the project folder:

```bash
cd hackathon-introductions
```

> **Don't have Git installed?** Download it at [git-scm.com](https://git-scm.com) and follow the setup guide for your OS.

---

## 📝 Step 2 — Create Your File

Inside the repository, there is a folder called `participants/`. Navigate into it:

```bash
cd participants
```

Create a new file named after yourself — use your first name or a handle, no spaces (either a txt file OR a md):

```bash
# Markdown option
touch yourname.md

# Plain text option
touch yourname.txt
```

Open it in any text editor (VS Code, Notepad, etc.) and answer the questions in the section below.

---

## 💬 Step 3 — Answer the Reflection Questions

Copy the prompts below into your file and write your answers underneath each one. There are no right or wrong answers — this is about you! 

```
## About Me

**Name (or handle):**

**Where I'm joining from:**


## Reflections

1. What does being part of a women's tech community mean to you?

2. What is it about AI agents that interests you, and what do you hope to learn?

3. If you could build an AI agent to solve any problem, what would it do and why?

4. What's one skill you're bringing to the hackathon, and one you're hoping to pick up?

5. What would a successful hackathon look like for you personally?
```

Feel free to write as much or as little as you like, you don't have to answer all five questions. 

---

## 💾 Step 4 — Commit Your Changes

Once you've saved your file, head back to the root of the repository:

```bash
cd ..
```

Check that Git can see your new file:

```bash
git status
```

You should see your file listed under *Untracked files*. Now stage it:

```bash
git add participants/yourname.md
```

Commit it with a message:

```bash
git commit -m "Add yourname participant file"
```

---

## 🚀 Step 5 — Push to the Repository

Send your commit up to GitHub:

```bash
git push origin main
```

That's it — you've made your first contribution! 🎉

---


## 🆘 Common Issues

| Problem | Fix |
|---|---|
| `Permission denied` when pushing | Check you've been added as a collaborator, or fork the repo first |
| `fatal: not a git repository` | Make sure you `cd` into the cloned folder before running git commands |
| Merge conflict | Let a facilitator know — we'll work through it together! |
| Unsure of your branch name | Run `git branch` to see all local branches |

---

## 📚 Resources

- [Git Cheat Sheet (GitHub)](https://education.github.com/git-cheat-sheet-education.pdf)
- [Introduction to GitHub (free course)](https://github.com/skills/introduction-to-github)
- [Markdown Guide](https://www.markdownguide.org/basic-syntax/)

---

*Questions? Grab a facilitator or drop a message in the hackathon Slack channel. Happy committing!* 💻✨
