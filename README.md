# Steps on how to create and commit file in Git
### Step 1:
- Create a new folder on your local machine and name it "PLPBasicGitAssignment".
- Open a terminal or command prompt and navigate to the created folder.

### Step 2
Git Initialization:
- Initialize a new Git repository in your local folder.

### Step 3
Connecting to GitHub:
- Link your local repository to the GitHub repository you created

```
git remote add origin <repository-url>
```

 Replace `<repository-url>` with the actual URL of your GitHub repository.

 ### Step 4
 Create a File:

  - Inside your local folder, create a new text file (e.g., `hello.txt`).

  - Add a simple text message (e.g., "Hello, Git!").

### Step 5
Committing Changes:

- Stage the changes.

```
git add hello.txt
```

- Commit the changes.

```
git commit -m "Add hello.txt with a greeting"
```

### Step 6
Pushing to GitHub:

- Push the committed changes to your GitHub repository.

```
git push -u origin main
```

### Step 7

Verify on GitHub:

  - Visit your GitHub repository in a web browser and confirm that the `hello.txt` file and commit message are visible.


