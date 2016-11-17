Create dotfiles project

   - mkdir dotfiles
   - fork prezto from github
   - create README.markdown file in dotfiles directory
   - copy your initial vimrc file
   - git init
   - git add
   - git commit -m"Initial commit"
   - git push -u origin master
   - git submodule add https://github.com/piquesel/prezto.git
 
   - Then do the changes in the submodule
   - add, commit and push normally

   - Go back to the main project
   - git add path/to/submodule
   - git commit -m "Updated my submodule"
   - git push

   - When cloning the main project again, you will need to
     git checkout master in order to get your own changes in the submodule
 
Installation

    git clone git://github.com/piquesel/dotfiles.git

References
    - Fork a repository: https://help.github.com/articles/fork-a-repo/
    - Edit a git submodule:
      http://stackoverflow.com/questions/5427414/editing-a-git-submodule
    - Commit changes in a submodule:
      http://stackoverflow.com/questions/5542910/how-do-i-commit-changes-in-a-git-submodule
    - Powerline:
      http://www.tecmint.com/powerline-adds-powerful-statuslines-and-prompts-to-vim-and-bash/
