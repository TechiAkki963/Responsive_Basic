# Responsive_Basic

Responsive Web with Git , HTML and CSS

<h1> Git and Github</h1>
<p> to write inside a .Readme file always use HTML for better formatting</p>
Author - TechiAkki963
</br>
Setting up GIT
<ul>
  <li> VS studio Code</li>
   <li> Git Bash - Windows</li>
  <li> Terminal - Mac</li>
</ul>

<h3>git --version</h3>
<p> to check whether the git is installed in your machine or not ? we use git --version</p>
<p> for windows type : git --version (in gitbash)</p>
<p> for mac type : git --version (in Terminal)</p>
<p> if it is not install go to this link <a href="https://git-scm.com/downloads">git- offlcial website</a> and download according to your system</p>

<h3> Configuring the Git</h3>
<p> if we see  '~'  tild symbol that means we are in our root directory </p>
<p> for e.g. - Admin@JARVIS MINGW64 ~ (master)</p>
<ul>
  <li>
    git config --global user.name "User Account Name"
  </li>
    <li>
    git config --global user.email "github's email id"
  </li>
    <li>
    git config --list  (to show the list of items in git config)
  </li>
</ul>

<h4> The Best way to keep your project sync with the Github repo is via VS Code editor</h4>
<p> Stages to Config VS code Editor with Github</p>
<ol>
  <li>
     we create a folder with any project name on the desktop 
  </li>
  <li>
    we acess the folder via Vscode editor
  </li>
  <li>
    once we acess the folder , on VS code editor we will open terminal and check whether git in installed or not using : git --version
  </li>
  <li> Clone 
  <ul>
    <li> for git Clone : in ther terminal we use : ' git clone <url from github repo>' (here we get the url from github HTTP any simply we copy )</li>
    <li> to check the list of file/folder inside the repository we use 'ls' command or we can use 'ls -a' to get the list of hidden folder</li>
    <li> then we enter the git repository via terminal using : cd gitfoldername</li>
    <li> to clear terminal we use ; clear</li>
   
  </ul>
      
  </li>
    <li> Status
  <ul>
    <li> for git status : in ther terminal we use : git status , for the first time if there nothing to change it will show On branch main
Your branch is up to date with 'origin/main'.</li>
    <li> Suppose we if make changes to a file in Vs code , and again run the command : ' git status' for e.g. if i make changes in my README.md file in VS code and run git status in the VS-terminal it will show me ---- modified:   README.md</li>
    <li> Suppose if we create a new  file in the VS code , for .eg. we create a file name 'index.html' and we run the command 'git status' in VS-terminal , Now it will show Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html. 
    <ol> Generally we have 4 type of status 
    <li> untracker </li>
    <li> modified </li>
    <li> staged </li>
    <li> unmodified </li>
    </ol>
  </li>
  </ul>
  </li>
</ol>
