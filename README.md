# Git

A set of snapshots of a miniature filesystem
Every time you commit, or save the state of your project in Git, it basically takes a picture of what all your files look like at that moment and stores.

#### What is version control?
Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

#### What are the types of version control systems?

##### Local
- RCS
##### Centralized
- CVS
- Subversion
- Perforce
##### Distributed
- Git
- Mercurial
- Bazaar
- Darcs

#### Git States
- modified 
- staged/indexed
- committed

#### Recording Changes to the Repository
each file in your working directory can be in one of two states
- tracked
  - unmodified
  - modified
  - staged
- untracked

#### Remotes
origin - default name Git gives to the server you cloned from.

#### Branching
- Branching means you diverge from the main line of development and continue to do work without messing with that main line
- A branch in Git is simply a lightweight movable pointer to one of the commits. A simple file that contains the 40 character SHA-1 checksum of the commit it points to.

#### First time Git setup
- Configuration file
  - /etc/gitconfig: git config --system
  - ~/.gitconfig or ~/.config/git/config: git config --global
  - .git/config
- Identity
  - $ git config --global user.name "John Doe"
  - $ git config --global user.email johndoe@example.com
- Editor
  - $ git config --global core.editor emacs
- How to check my settings?
  - $ git config --list
  - $ git config user.name
  
  #### Day-to-day Commands
  
  #### Pulling and Pushing
  
  #### Stashing (Not Squashing)
  
  #### FAQ - Branch
  
  #### FAQ - Remote
  
  #### FAQ - General
  
  #### Git Rebase/Squash
  
  #### How to generate, take email patches and push?
