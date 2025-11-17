# **Git & Environment Setup — Structured Notes (Markdown)**

---

## **Python & Environment Setup Commands**

```bash
ipykernel (pip install ipykernel)
conda create -p venv python==3.12
pip install numpy
git clone git@github.com:Shivacode-37/Study__23.git
```

---

## **Git Daily Workflow Commands**

```bash
git add .
git commit -m "update"
git push
```

# **Markdown Formatting Quick Reference**

## **Headings**

* `# Heading` → Big title
* `## Heading` → Medium subtitle
* `### Heading` → Section title

## **Text Styles**
* **Bold** → `**text**`
* *Italic* → `*text*`
* ***Bold + Italic*** → `***text***`

## **Blockquote (For Notes)**
* `> text`

## **Lists**
* Bullet → `- item`
* Numbered → `1. item`

## **Inline Code**
* `` `code` ``
## **Code Block**
````
```bash
commands
```
````

## **Horizontal Divider**
* `---`

## **Checkboxes**
* `[ ]` → `- [ ] task`
* `[x]` → `- [x] done`

## **Links**
* `[name](url)`

## **Tables**
* `| col1 | col2 |`
[
# ------------------------------

# **PART 1 — FIRST TIME SETUP FOR ANY NEW PROJECT**
# ------------------------------
## **Go inside your project folder**
```bash
cd "path/to/your/folder"
```
## **Initialize Git**
```bash
git init
```

## **Add all files**
```bash
git add .
```
## **Commit files**
```bash
git commit -m "initial"
```
## **Add GitHub remote**
*(replace with your username and repo name)*
```bash
git remote add origin git@github.com:YOUR_USERNAME/REPO_NAME.git
```
## **Set branch name to main**
```bash
git branch -M main
```
## **Push everything to GitHub**
```bash
git push -u origin main
```
---
# ------------------------------
# **PART 2 — DAILY UPDATES (AFTER YOU CHANGE FILES)**
# ------------------------------
```bash
git add .
git commit -m "update"
git push
```
---
# ------------------------------
# **PART 3 — CLONE YOUR REPO ON ANY OTHER LAPTOP**
# ------------------------------
```bash
git clone git@github.com:YOUR_USERNAME/REPO_NAME.git
```
---
# ------------------------------
# **PART 4 — CHECK STATUS & LOG (OPTIONAL)**
# ------------------------------
```bash
git status
git log --oneline
```
]