# Guide to Recording Your Contribution to the Teams

To monitor your contribution to your team you will require to maintain a GitHub repo dedicated to the task.

This should be a private repo with your academic consultant as the only contributor.

You should make weekly updates during the week upto and between Sprints and daily updates durng the Sprint Weeks themselves.

Updates will take the form of a pull request and should be written as a markdown file [see guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

[Tips on using Github in Visual Studio Code](https://code.visualstudio.com/docs/sourcecontrol/overview)


> [!TIP]
> The repo will allow the academic team to see that you have contributed consistently throughout the project via timestamped pull requests.  You should ensure you complete these regularly in order to evidence your contribution to the team.  This will contribute to your mark in both the tasks that make up the assignment.



## **Step 1: Create a New Repository**
1. In your GitHub account create a new repository.
2. Make your repository `private` and add your academic consultant as a collaborator.  
3. These can both be done via `Settings` in GitHub.  Setting the repo `private` is found under the `Danger Settings`.

---

## **Step 2: Clone the Repository**

Clone the repository either with a GitHub friendly editor like Visual Studio Code or via the command line.

The command instructions are as follows:

1. Open your terminal.
3. Run the following command to clone your forked repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   ```
4. Navigate to the repository directory:
   ```bash
   cd repository-name
   ```

---

## **Step 3: Create a New Branch**
Create a new branch for your changes rather than making changes on the `main` branch.

This can be done through your Visual Studio Code editor or via the command-line.

The command-line instructions are as follows:

1. Create a new branch:
   ```bash
   git checkout -b your-branch-name
   ```
2. Use a descriptive branch name, e.g., `week1`, `week2` or `sprint1day1`.

---

## **Step 4: Make Your Changes**

1. Open the project in Visual Studio Code or a similar GitHub friendly editor.
2. Create a markdown file matching the name of branch.
3. You should briefly address the following areas:
   - **What you did during this duration of the session.**
   - **What you intend to do before the next session.**
   - **Any issues arising and how you intend to resolve them.**
4. You may choose to include evidence such project specifications, user stories, wireframe etc and save these in an appropriate folder.

> [!TIP]
> To familiarize yourself with the process create a `profle.md` file that includes your name and student id.  Remember to ensure that you keep this GitHub `private`.

---

## **Step 5: Commit Your Changes**

This can be done through your Visual Studio Code editor or via the command-line.

The command-line instructions are as follows:

1. Stage your changes:
   ```bash
   git add .
   ```
2. Commit your changes with a meaningful message:
   ```bash
   git commit -m "docs: Week One"
   ```

---

## **Step 6: Push Your Changes to GitHub**

This can be done through your Visual Studio Code editor as a `Sync` operation.

The command-line instructions are as follows:

1. Push your changes to your repository:
   ```bash
   git push origin your-branch-name
   ```

---

## **Step 7: Create a Pull Request**

1. Go to your repository on GitHub.
2. Open the **Pull Requests** from the top menu.
3. You will see a **Compare & pull request** button. Click it.
4. Ensure that the base repository is the original repository and the base branch is `main` (or the relevant branch).
5. Provide a descriptive title for your pull request such as `Week One Evidence`.
8. Click **Create pull request**.

---

## **Step 8: Review Feedback**
Once your academic consultant has reviewed your Pull Request, they may make comments:
1. Review their comments.
2. Respond to comments where appropriate.
3. Your academic consultant will then commit your changes to the `main` branch to provide a record of your contribution.


---





