# Introduction to Git

### Version Control

- Version control system - program(s) used to track changes to a collection of files
- Software Configuration Management (SCM)
- Features
  - Track changes and who made them
  - Include messages with each change
  - Retrieve past versions of project or files
  - create branches
- Distributed version control: history is stored on both the client and the server

### Git terminology

- Working tree: the set of nested directories and files being worked on
- Repository: the directory where all history and metadata is stored
- Hash: number produced by a hash function that represents the contents of the file or object as a fixed number of digits
- Object: blob (file), tree (directory), commit (specific version), tag (name for commit)
- Commit: saving the changes to the repo
- Branch: named series of linked commits
- Remote: named reference to another Git repo

### Basic Git commands

- > git status

    - Displays the state of the working tree

- > git add

    - Stage changes to prepare for a commit
- > git commit

    - Save changes to the repository
- > git log
  - Show the commit history
- > git help
    - shows help info