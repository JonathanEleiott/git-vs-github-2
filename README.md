# Git vs GitHub

- Git -> version control system using git commands that keeps track of the history of files and folders
- GitHub -> place to store your projects (repository)

- git commands
  - git init -> allows a project to use git commands
  - git status -> shows what has been added/changed/deleted since our last commit
  - git add [file names] -> moves changes from the working directory to the staging area
  - git commit -> takes everything from the staging area and makes it permanent
    - -m "message" -> shortcut for writing a message on your commit
  - git remote -> a connection to another location
    - add -> add connection
      - nickname -> name of the connection (most commonly origin)
      - location -> where is the actual location
  - git push -> send your code somwhere
    - nickname -> nickname of the place you want to send your code to
    - branch name -> which branch do you want to push

- 3 stages
  - working directory (red)
  - staging area (green)
  - project