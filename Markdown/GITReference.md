## Git Reference Guide
 - **git init** 
   - Use it on the current working directory to **Initialize** a new Git repository.

 - **git clone [repository_url]**
   - Creates a copy of a remote repository on your local machine.

 - **git add [file]**
   - Adds changes in the working directory to the staging area.

 - **git commit -m "[commit_message]**
   - Commits the changes in the staging area with a descriptive message.

 - **git status**
   - Displays the status of changes as untracked, modified, or staged.

 - **git log**
   - Shows a log of all commits, with commit hashes, author, date, and commit messages.

 - **git pull**
   - Fetches changes from a remote repository and merges them into the current branch.

 - **git push [remote] [branch]**
   - Pushes the committed changes to a remote repository.

 - **git branch**
   - Lists all local branches and indicates the current branch.

 - **git branch [branch_name]**
   - Creates a new branch with the specified name.

 - **git checkout [branch_name]**
   - Switches to the specified branch.

 - **git merge [branch_name]**
   - Merges changes from the specified branch into the current branch.

 - **git fetch [remote]**
   - Fetches changes from a remote repository but does not merge them.

 - **git diff**
   - Shows the differences between the working directory and the last commit.

 - **git reset [file]**
   - Unstages the specified file or resets the entire staging area.

 - **git tag [tag_name]**
   - Adds a lightweight tag to the latest commit.

 - **git remote add [remote_name] [remote_url]**
   - Adds a new remote repository.

 - **git remote -v**
   - Lists all remote repositories associated with the current repository.

## Configuration

 - **git config** 
   - Used to set or get configuration options for Git. It can be used to configure various aspects of Git, including user information, aliases, colors, and more.

 - **git config --global user.name "Your Name"**
   - Sets your globally configured Git username.

 - **git config --global user.email "your.email@example.com"**
   - Sets your globally configured Git email.

 - **git config --global color.ui auto**
   - Enables colored output in the terminal for better readability.

 - **git config --global core.editor "editor_name"**
   - Sets the default text editor for commit messages.

 - **git config --global alias.[alias_name] "[git_command]"**
   - Creates a shortcut (alias) for a Git command.
      * Example: `git config --global alias.co checkout` creates the alias `co` for the `checkout` command.

 - **git config --global core.autocrlf true/false/input**
   - Configures line ending conversions. `true` converts line endings to CRLF, `false` keeps them as-is, and `input` converts to LF on input.

 - **git config --global credential.helper cache**
   - Caches credentials in memory for a specified period, reducing the need to enter credentials repeatedly.

 - **git config --global credential.helper store**
   - Stores credentials in a plain text file. Not recommended for security reasons.

 - **git config --global core.ignorecase true**
   - Makes Git commands case-insensitive.

 - **git config --global diff.tool [tool_name]**
    - Configures the default diff tool.

 - **git config --global merge.tool [tool_name]**
    - Configures the default merge tool.

 - **git config --global http.proxy [proxy_url]**
    - Configures a proxy for Git to use when making HTTP requests.

 - **git config --global --unset [config_key]**
    - Unsets a global configuration option.