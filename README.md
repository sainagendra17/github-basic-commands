*	$ git init   //Initialize local git Repository
*	$ git add <file> //Add  fles(s) To index
*	$ git status //Check Status of Working Tree
*	$ git commit //Commit Changes in index
*	$ git pull    //Pull latest from remote repository
*	$ git clone  //clone repository into a new directory
*	$ git config –-global user.name ‘Nagendra’
*	$ git config –-global user.email ‘gbrgnagendra@gmial.com’
*	$ git add index.html
*	$ git status 
*	$ git rm  --cached index.html
*	$ git add *.html – adds all html files
*	$ git add . – add all files
*	I for giving comment
*	:wq to come back
*	$ git commit -m ‘changed adpp.js’
*	$ git branch login
*	$ git checkout login
*	$ git merge login
*	$ git config –list //shows all details like usename email
*	$ git config –-local  user.name ‘Nagendra’
*	$ git config –-local user.email ‘gbrgnagendra@gmial.com’
*	$ git log // show our commit log
*	$ git diff // show difference in files in working area and staging area
*	$ git diff –staged // show diff in our staging area and recent  commit
*	$ git checkout –s1 //revert changes working tree changes
*	$ git reset Head s1 //restores to staging area from commit
*	$ git  log and $ git checkout 900 -s2 //restore  to working and staggin tree
*	$ git log –all  --decorate –online  --graph
*	$ alias graph=”$ git log –all  --decorate –online  --graph”
*	$ graph
*	$ git branch branchname  //creates branches
*	$ git branch // will so all branches
*	$ git checkout –brnachname
*	$ git diff master..SDN  //master branch and SDN branch
*	$ git branch –merged
*	$ git branch -d SDN
*	$ git checkout -d dev //creates new branch and checkout create branch
*	$ git stash
*	$ git stash -p
