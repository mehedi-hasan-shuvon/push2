//to see which directory we are in
pwd

//setting name and mail
git config --global user.name "mehedi"
git config --global user.email "mehedi.hasan.shuvon@gmail.com"
git --list

//to show name nad email
git config user.name 
git config user.name 

// to chcek a git status
git status

//to make a git repository
git init

// to send all file into statging phrase
git add --a

//to commit
git commit -m "initial status"

//to send perticular file to stating pharse
git add filename.txt

//then to commit
git commit -m "string"

// to delete all the file in the repository
rm -rf .git

//to clone a github repository
git clone  {url}


// to make a file ignore first make a file name .gitignore
touch .gitignore
//then add the file name what should be ignored inside the .gitignore 

//to compare between working area and staging area
git diff
git diff --staged

// to do direct commit without staging
git commit -a -m "direct commit"

// to see all the past commit 
git log
q <..... to exit

// to delete any thing in the repository
git rm filename.txt

// to reaname a file
git mv filename.txt newfilename.txt