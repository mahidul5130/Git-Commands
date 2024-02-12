# Merge changes from dev to Mahidul
1. **Switch to the "dev" branch:**
   ```bash
   git checkout dev
   ```

2. **Pull the latest changes from the remote repository:**
   ```bash
   git pull origin dev
   ```

3. **Switch to the "mahidul" branch:**
   ```bash
   git checkout mahidul
   ```

4. **Merge the changes from "dev" into "mahidul":**
   ```bash
   git merge dev
   ```

   This will bring the changes from the "dev" branch into your "mahidul" branch.

5. **Resolve any merge conflicts (if any):**
   If Git encounters conflicts during the merge, you'll need to resolve them manually. Git will mark the conflicted files, and you'll need to edit them to resolve the conflicts.

6. **Commit the changes:**
   After resolving conflicts, if any, commit the changes:
   ```bash
   git commit -m "Merge changes from dev into mahidul"
   ```

7. **Push the changes to the remote repository:**
   ```bash
   git push origin mahidul
   ```

# Merge changes from Mahidul to Dev and Stating Branch

1. **Ensure you have committed your changes:**
   ```bash
   git add .
   git commit -m "Updated"
   ```

2. **Push changes to the remote "mahidul" branch:**
   ```bash
   git push origin mahidul
   ```

3. **Switch to the "dev" branch:**
   ```bash
   git checkout dev
   ```

4. **Merge changes from "mahidul" to "dev":**
   ```bash
   git merge mahidul
   ```

5. **Push changes to the remote "dev" branch:**
   ```bash
   git push origin dev
   ```

6. **Back to "mahidul" branch:**
   ```bash
   git checkout mahidul
   ```

7. **Switch to the "staging" branch:**
   ```bash
   git checkout staging
   ```

8. **Merge changes from "mahidul" to "staging":**
   ```bash
   git merge mahidul
   ```

9. **Push changes to the remote "staging" branch:**
   ```bash
   git push origin staging
   ```

10. **Back to "mahidul" branch:**
   ```bash
   git checkout mahidul
   ```
