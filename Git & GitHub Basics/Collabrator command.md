| **Git Command**            | **Purpose**                                                               |
| -------------------------- | ------------------------------------------------------------------------- |
| `git clone`                | Copies a remote Git repository to your local system.                      |
| `cd`                       | Changes the current working directory (move into project folder).         |
| `git switch -C hello`      | Creates a new branch named `hello` and switches to it.                    |
| `git add .`                | Stages all modified and new files for commit.                             |
| `git commit -m "python"`   | Saves staged changes with a message describing what was changed.          |
| `git push -u origin hello` | Uploads the `hello` branch to GitHub and sets tracking.                   |
| `git fetch`                | Downloads latest branches and updates from the remote (no merge).         |
| `git branch`               | Lists all branches and highlights the current active branch.              |
| `git switch hello`         | Switches to the `hello` branch.                                           |
| `git switch main`          | Switches to the `main` branch.                                            |
| `git merge hello`          | Merges the `hello` branch into the current branch (usually `main`).       |
| `git push origin main`     | Uploads changes from the `main` branch to the GitHub repository.          |
| `git fetch` (again)        | Refreshes the list of branches and updates from remote (without merging). |
| `git pull`                 | Downloads and **merges** the latest changes from remote to your branch.   |
