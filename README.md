  # Prework Study Guide Webpage

## Descriptions

Provide a short description explaining the what, why, and how of your project. Use the following questions as a guide:

- What was your motivation?
My moltivation for this first project is to learn and understand what is JS, HTML, CSS.
- Why did you build this project? (Note: the answer is not "Because it was a homework assignment.")
I build this project as a study to comeback and review my code
- What problem does it solve?
it a reset point and cheat sheet for me to review if need to solve a difficult problem
- What did you learn?
how to pull/push to git hub, Git Bash command, HTML structure + js Logic statement and looping.


## Installation

"N/A"

## Usage

Provide instructions and examples for use. Include screenshots as needed.

I can use this studied as a rerfence to review how to use Git bash command to navigate in terminal and push and pull files from my local computer to git hub. 

Also I can use this studied guide to review JS IF statement structure and loop structure

It also a good reference point to review before writing the code for a new HTML webpage
*******************************************************************************************
CLI:
PWD: Print Window Directory

CLI:
LS: Show list of file that you are working on in the folder directory

CLI:
CD: Change Directory. For example : CD Downloads. ( This move to the download folder)

CD .. ( To move backward 1 Level)

mkdir "text" : Make directory. can use to create a folder

touch "File Name".txt : use this command to create a text line. 

if on window use: start "file name".txt

If on Mac use: Open "File name".txt

Pull/ Comit note:
git add -A ( to state change)

Git commit -m " added code to HTML file" ( use this when commit)

git pull origin main ( Pull in to branch)

git push origin feature/add-html (push all of our change)

--------
git status
show modified files in working directory, staged for your next commit
git add [file]
add a file as it looks now to your next commit (stage)
git reset [file]
unstage a file while retaining the changes in working directory
git diff
diff of what is changed but not staged
git diff --staged
diff of what is staged but not yet commited
git commit -m “[descriptive message]”
commit your staged content as a new commit snapshot

--------
git branch
list your branches. a * will appear next to the currently active branch
git branch [branch-name]
create a new branch at the current commit
git checkout
switch to another branch and check it out into your working directory
git merge [branch]
merge the specified branch’s history into the current one
git log
show all commits in the current branch

_________

Git Status give you what have changes

Git Checkout -B " Text" to create a new branch

Git chechout "branch name" to switch to that branch

Git add-A or git add. is to add modification in the current working branch to staging are.\

Git Commit -m "text description" to commit to the change ( must enter description)

git push origin "branch name"

Java Script Iff statement: 
if (condition) {
 // block of code to be executed if condition is truthy
}

*****************************************
var topic = "HTML";

if (topic === 'HTML') {
  console.log("Let's study HTML!");
} else if (topic === 'CSS') {
  console.log("Let's study CSS!");
} else if (topic === 'Git') {
  console.log("Let's study Git!");
} else if (topic === 'JavaScript') {
  console.log("Let's study JavaScript!");
} else {
  console.log('Please try again!');
}

******************************************
Loop Method:

function helloWorld() {
 // code block
}
**********************
Loop Example:
var topics = ['HTML', 'CSS', 'Git', 'JavaScript'];

for (var x = 0; x < topics.length; x++) {
 console.log(topics[x]);
}
***************************************

to call the function:
"Function name"()


## Credits

N/A

## License
MIT LICENSE