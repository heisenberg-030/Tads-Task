# Tads-Task
Your task for the Git Workshop.

## Resources

- [Interactive Git Learning Platform](https://learngitbranching.js.org) (No need to do advanced topics in both remote/main)
- [Git Cheatsheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet/)

---

## Task 1: Add Your Name to a New File

1. **Fork the repository and create a new branch (`Task1`).**
2. Create a new file named `<your-github-username>.txt`.
3. Add your name inside the file using the format:
   - `Your Name [GitHub Username](http://github.com/username)`
4. Commit the changes.
5. Merge `Task1` into the `main` branch.

---

## Task 2: Create and Merge Branches with Conflicts

1. **Switch back to main branch.**
2. Create a file with same name you created in Task 1.
3. Add some other text in the file (maybe your friend's name ;) ).
4. Commit the changes.
5. Merge `Task1` into `main` (this should result in a merge conflict).
6. Resolve the conflict manually and commit the merge resolution.

---

## Task 3: Revert a Commit (Without Removing History)

1. Create a new branch `Task3` from `main` in your fork.
2. Add a dummy piece of code and commit it.
3. Realizing it was incorrect, **push another commit that reverts the changes**.

### Why not remove the commit?

Keeping the history ensures integrity and improves collaboration.

---

## Task 4: Remove a Commit Entirely

1. Create a new branch `Task4` from `Task3` in your fork.
2. Use `git reset` to **remove the previous commit permanently**.
3. Push the changes to a new branch `Task4-verify` so that it can be verified.

---

## Task 5: Rebase and Remove Intermediate Commits

1. Create a new branch `Task5` from `main` in your fork.
2. Add a dummy piece of code and commit it.
3. Repeat this process **five more times**.
4. Rebase `main` branch into this.
