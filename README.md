# Git Assignment: Fork, Clone, Branch, and Merge Workflow

This assignment is designed to help you practice essential Git commands and workflows commonly used in collaborative development. By the end of this exercise, you will have experience forking repositories, creating branches, committing changes, and merging them back into the main branch.

---

## Objectives

1. **Fork and Clone**: Gain experience working with repositories you don't own by forking and cloning.
2. **Branch Management**: Learn how to create and switch between branches to isolate your changes.
3. **Commit and Merge**: Practice adding files, committing changes, and merging them with the main branch.
4. **Push Changes**: Update the remote repository with your changes.

---

## Instructions

1. **Fork the Repository**  
   Use the GitHub web interface to fork the repository provided by your instructor.

2. **Clone Your Forked Repository**  
   Run the following command to clone your forked repository:
   ```bash
   git clone <forked-repo-url>

3. **Create and switch to a new branch**
   Create a new branch named feature or any name of your choice and switch to it
   ```bash
   git checkout -b feature
   
4. **Add your files(Stage)**
   ```bash
   git add .
   
5. **Commit your changes**
   ```bash
   git commit -m "added features/files
   
6. **Merge the new branch with the main branch**
   ```bash
   git checkout main 
   git merge feature
   
7. **Push to GitHub**
   ```bash
   git push origin main
   
### Deliverables
1. **A forked repo on you github profile**
2. **All changes commited and merged to the main branch**
3. **The updated repo pushed to github**

### Notes
1. **Use meaningful commit messages to describe the changes you make**
2. **If you encounter any merge conflicts, resolve them before completing the merge**

## Good Luck.