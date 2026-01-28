# Guide to Recording Your Contribution to the Team

To monitor your individual contribution to the team project, you are required to maintain a GitHub repository that records your activity throughout the module.

You will do this by **forking the base repository provided** and making **regular diary-style commits** that document your contribution over time.

Your academic team will review the **timestamped commit history** to ensure consistent engagement across the project lifecycle.

You should:

* Make **weekly updates** during the weeks leading up to the Sprint Weeks
* Make **daily updates** during the Sprint Weeks themselves

All updates must be written as **Markdown files**
[GitHub Markdown guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

It is recommended that you use **Visual Studio Code** to manage this process.
[Tips on using GitHub in Visual Studio Code](https://code.visualstudio.com/docs/sourcecontrol/overview)

> [!TIP]
> This repository allows the academic team to see evidence of consistent contribution via timestamped commits.
> You must keep this up to date, as this evidence will be reviewed during the marking of both assignment tasks.

---
Sure thing — here’s a **cleanly updated version** that explicitly ensures the fork is **private**, while keeping the tone and structure consistent (＾▽＾)

---

## **Step 1: Fork the Base Repository (Private Fork Required)**

1. Navigate to the base repository provided by the module team.
2. Click the **Fork** button (top-right of GitHub).
3. When prompted, **set the fork to `Private`**.
4. Fork the repository into **your own GitHub account**.
5. Do **not** create a new repository manually.

This forked repository will be your **private personal contribution diary** and should only be accessible to you and the academic team.

---

## **Step 2: Update the `README.md` File**

In your forked repository, edit the existing `README.md` file to include:

* Your name
* Your student ID
* Your team name / number

This allows markers to clearly identify whose work they are reviewing.

> [!TIP]
> A [sample README](sample-readme.md) structure is included in the base repository.

---

## **Step 3: Clone Your Forked Repository**

Clone **your fork**, not the original base repository.

Using the command line:

```bash
git clone https://github.com/your-username/repository-name.git
cd repository-name
```

Or clone directly using Visual Studio Code.

---

## **Step 4: Structure Your Diary**

The repo has a clear folder structure to record your activity.

* Each **week folder** should contain one markdown diary entry
* Each **sprint folder** may contain daily entries if required

> There is **no need to create branches**.
> All work should be committed directly to the `main` branch.

---

## **Step 5: Write Your Diary Entries**

For each week (or sprint day), create a Markdown file such as:

* `week-01.md`
* `week-02.md`
* `day-01.md`

Each entry should briefly address:

* **What you worked on during this period**
* **What you plan to do next**
* **Any issues, blockers, or reflections**
* **How these issues were resolved or will be addressed**

You may include supporting evidence such as:

* user stories
* screenshots
* wireframes
* meeting notes
* links to relevant work

Store these in appropriate folders if needed.

---

## **Step 6: Commit Your Changes**

Commit **regularly** with clear, meaningful messages.

Using the command line:

```bash
git add .
git commit -m "docs: Week 3 contribution diary"
```

Or use the Source Control panel in Visual Studio Code.

---

## **Step 7: Push Your Changes to GitHub**

Push your commits directly to your forked repository:

```bash
git push origin main
```

There is:

* ❌ **No need for branches**
* ❌ **No pull requests**
* ✅ **Direct commits to `main` only**

---

## **Important Notes**

* Your forked repository should remain **private** if instructed by the module team
* Ensure commits are made **consistently across the project**
* Large gaps in commit history may negatively impact assessment
* Commit messages and diary content should be **professional and reflective**

