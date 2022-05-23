# TmuxVimGit
Programmers efficient workspace environment using

- Tmux
- vim
- Git


## Good to have features
1. vim in multiple monitors:
    - certain buffer or files is open in 2<sup>nd</sup> or even 3<sup>rd</sup> monitors.
      - for example, search buffer is on 2<sup>nd</sup>  monitor
    - possible solution
      - create 2<sup>nd</sup> tmux session (with -t) and open a temprary file
      - highlignting text would be chalenging

2. Update vim project and tag
    - possible solution
      - This should be run in background
      - git hook creates the file list and tag when
        - branch is changed
        - commit
        - add new file
        - remove file
      - vim updates the tag files when a file is saved

3. multiple project rules
   1. All files (pattern) in the directory and subdirectory.
   2. Files are by a script
    - dependent files from .d files
    - dependent files from bazel query

