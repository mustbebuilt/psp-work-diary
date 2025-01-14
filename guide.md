# Guide to Recording Your Contribution to the Teams

To monitor your contribution to your team you will require to maintain a GitHub repo dedicated to the task.

This should be a private repo with your academic consultant as the only contributor.

You should make weekly updates during the week upto and between Sprints and daily updates durng the Sprint Weeks themselves.

Updates will take the form of a pull request and should be written as a markdown file [see guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

> [!TIP]
> The repo will allow the academic team to see that you have contributed consistently through out the project via timestamped pull requests.  You should ensure you complete these regularly in order to evidence your contribution to the team.  This will contribute to your mark in both the tasks that make up the assignment.



## **Step 1: Fork this Repository**
1. Click the **Fork** button at the top-right corner to create your copy of this repository.
2. Make your Fork `private` and add your academic consultant as a collaborator.  
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

This can be done through your Visual Studio Code editor.

The command instructions are as follows:

1. Create a new branch:
   ```bash
   git checkout -b your-branch-name
   ```
2. Use a descriptive branch name, e.g., `week1`, `week2` or `sprint1day1`.

---

## **Step 4: Make Your Changes**

1. Open the project in Visual Studio Code or a similar GitHub friendly editor.
2. Create a markdown file matching the name of branch.
3. Save your changes.

---

## **Step 5: Commit Your Changes**

This can be done through your Visual Studio Code editor.

The command instructions are as follows:

1. Stage your changes:
   ```bash
   git add .
   ```
2. Commit your changes with a meaningful message:
   ```bash
   git commit -m "Work Summary"
   ```

---

## **Step 6: Push Your Changes to GitHub**

This can be done through your Visual Studio Code editor as a `Sync` operation.

The command instructions are as follows:

1. Push your changes to your repository:
   ```bash
   git push origin your-branch-name
   ```

---

## **Step 7: Create a Pull Request**

1. Go to your repository on GitHub.
2. You will see a **Compare & pull request** button. Click it.
3. Ensure that the base repository is the original repository and the base branch is `main` (or the relevant branch).
4. Provide a descriptive title for your pull request.
5. In the description, include the following details:
   - **What you did during this duration of the session.**
   - **What you intend to do before the next session.**
   - **Any issues arising and how you intend to resolve them.**
6. Your can choose to create a folder which matches the branch name to add additional evidence such as project specifications, user stories, wireframe etc.
7. Click **Create pull request**.

---

## **Step 9: Review Feedback**
Once your academic consultant has reviewed your Pull Request, they may make comments:
1. Review their comments.
2. Respond to comments where appropriate.
3. Commit and push the updates to the same branch:
   ```bash
   git add .
   git commit -m "Chore: Address reviewer comments"
   git push origin your-branch-name
   ```
4. The pull request will automatically update with your new commits.


---





