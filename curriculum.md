#Curriculum

##Command line

###Notes
  - The language you use in the linux or mac command line is call Bash. The terminals of both OS's are based off of Unix. Windows uses a totally different command line language which sucks. It is a big reason why a lot of windows programming sucks
  ### command cheat sheat
  1. cd: change directory 
  2. pwd: list path of current directory
  3. ls: list contents of current directory
  4. . : reference for current directory
  5. .. : reference for parent of current directory (ie "cd .." will move you back one directory)
  6. ~ : reference for home directory (ie "cd ~" will move you to your home directory)
  7. / : reference for root directory
  8. sudo [command]: putting this in front of a command will cause that command to be administered with root (admin) priveleges. 
  9. sudo apt-get install [program] : the way you download programs through the command line in ubuntu
  10. sudo homebrew [program]: the way you download programs
  
###References 
  - https://www.youtube.com/watch?v=xtS2NiABf54 (series on bash)
  - https://www.youtube.com/playlist?list=PLtK75qxsQaMLZSo7KL-PmiRarU7hrpnwK

##Git

Git is a revision control system. This means you cna use it to save and review very detailed changes in the life of a document or file. Git is essential to modern software development.

Try it out and learn more 
- https://www.codeschool.com/courses/try-git

You should be able to clone a git repo from the internet to your machine. Pull down changes from that repo. Push changes up to that repo. Make commits. View commit logs. View the difference between two pieces of code.

###Git command line cheatsheat
  1. git init : make the current directory a git repo
  2. git clone [url] : clone a remote repository to your current directory
  3. git status : show the changes on your current branch
  4. git add [args] : add changes to be commited
    - git add . : will add all files
    - git add -u will add all currently tracked files
  5. git commit -m ["commit message"]: creates a new commit from the code you have added with the message you specify
  
  6. git push [remote] [branch] : pushes your current state to the branch and remote specifies
  7. git pull : gets all new code from the default remote and updates your current branch with that code if possible
  
  8. git checkout [ref] : updates your current codebase to be exactly the same as the state of the ref
  9. git checkout -b [branch name]: create a new branch off of the current state and check it out.
  
### Git terminology
  - remotes : a remote (ie: on the internet) source of code which you can reference as the source of a git repo
  - HEAD : is equal to the ref of the top commit of your current branch. Essentially it is equal to the latest commit on a given branch.
  ie (git checkout HEAD) will take you to the most recent commit on your current brach
  - origin : an alias (alternate name) for a remote of your current branch
 ie: if I do git clone "http:some-repo/repo". Inside that directory the term "origin" will equal "http:some-repo/repo"
 - ref : a reference to a specific point of history on a branch. refs are referenced via strings of numbers and letters called hashes that would look something like "b3a459a0a55ed7ce5046420fce43c2c8def920b7"
  You can checkout a hash directly (ie git checkout b3a459a0a55ed7ce5046420fce43c2c8def920b7) will take you to the exact state when b3a459a0a55ed7ce5046420fce43c2c8def920b7 was commited.

##How the web works

  - http
  - tcp/ip
  - networking
  - servers
  - "the cloud"
##HTML/CSS
  Do the codecadmy course
 - http://www.codecademy.com/en/tracks/web
##Ruby
  Do the codecademy course
  http://www.codecademy.com/en/tracks/ruby
##Rails
  Do this extensive tutorial. It will combine all things you have learned so far into a project where you make a fully functioning website with ruby and ruby on rails.
  https://www.railstutorial.org/book
##Javascript
Do the codecademy course
http://www.codecademy.com/en/tracks/javascript
 and the jquery codecademy course. Jquery is a javascipt library which allows you to change html, css and data, easily in the browser
http://www.codecademy.com/en/tracks/jquery
