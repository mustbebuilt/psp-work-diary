# Guide to Recording Your Contribution to the Teams

To monitor you contribution to your team you will require to maintain a GitHub repo dedicated to the task.  You should make weekly updates during the week upto and between Sprints and daily updates durng the Sprint Weeks themselves.

Updates will take the form of a pull request and should be written as a markdown file [see guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

## **Step 1: Fork this Repository**
1. Click the **Fork** button at the top-right corner to create your copy of the repository.

---

## **Step 2: Clone the Repository**
1. Open your terminal.
2. Run the following command to clone your forked repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   ```
3. Navigate to the repository directory:
   ```bash
   cd repository-name
   ```

---

## **Step 3: Create a New Branch**
It is important to create a new branch for your changes rather than making changes on the `main` branch.
1. Create a new branch:
   ```bash
   git checkout -b your-branch-name
   ```
2. Use a descriptive branch name, e.g., `week1`, `week2` or `sprint1-day1`.

---

## **Step 4: Make Your Changes**
1. Open the project in Visual Studio Code or a similar GitHub friendly editor.
2. Create a markdown file matching the name of branch.
3. Save your changes.

---

## **Step 5: Commit Your Changes**
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
   - **What changes you made.**
   - **Why you made the changes.**
   - **How to test the changes.**
6. Add any relevant labels and assign reviewers if required.
7. Click **Create pull request**.

---

## **Step 9: Review Feedback**
Once your academic consultant has reviewed your PR, they may request changes:
1. Review their comments.
2. Make the requested changes locally.
3. Commit and push the updates to the same branch:
   ```bash
   git add .
   git commit -m "Chore: Address reviewer comments"
   git push origin your-branch-name
   ```
4. The pull request will automatically update with your new commits.

---

## **Step 9: Follow Best Practices for a Successful PR**
To improve your chances of getting your PR accepted:
1. **Follow the project’s contribution guidelines.**
   - Look for a `CONTRIBUTING.md` file in the repository.
2. **Write clean and readable code.**
   - Follow the coding style used in the project.
3. **Add tests if required.**
   - Ensure your changes do not break existing functionality.
4. **Provide a clear PR description.**
   - Use bullet points or a checklist if your changes are extensive.
5. **Be respectful and patient.**
   - Remember that maintainers may be busy. Respond politely to feedback.

---


## **Common Mistakes to Avoid**
- Not creating a new branch for your changes.
- Writing vague or unclear commit messages.
- Ignoring the project’s coding style.
- Failing to provide a detailed PR description.
- Not addressing reviewer comments.

---





