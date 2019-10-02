<!DOCTYPE html>
<html>
<body>
  <h1>How to Use Git, Github, and Webstorm</h1>
  <h2>What are Git, Github, and Webstorm?</h2>
  <p>All three of these entities address the processes of coding computer programs.<p>
  <h3>Git</h3>
  <p>Git is a distributed version control system - it records the changes made to a computer program, allowing the user change the computer program (committing), see the differences between each change (diffing), create separate changes to the same code (branching), and bring those separate changes together into one (merging). The user would use Git to track changes in programs that were written in an editor or an IDE (a software suite that provides basic tools required to write and run code). Git integrates with some popular IDEs to facilitate this.<p>
  <h3>Github</h3>
  <p>Github is a website that hosts Git repositories, allowing users to collaborate on open source projects (where the public can see the code), or closed source projects (where the public cannot see the code, but select users can).<p>
  <h3>Webstorm</h3>
  <p>Webstorm is an IDE that provides coding assistance for JavaScript, HTML and CSS and a wide range of modern web technologies. Webstorm can be integrated with Git.<p>
  <h2>How to Use Git and Github</h2>
  <h3>Getting Started</h3>
  <ol>
  <li>Install Git at https://git-scm.com/book/en/v2/Getting-Started-Installing-Git</li>
  <li>Make a Github account at https://github.com/join</li>
  </ol>
  <h3>Using Git</h3>
  <ol>
  <li>To create a new project using Git, create a repository (a directory or storage space that keeps code files, text files, image files, etc.) in a computer folder</li>
  <ul>
  <li>Open the terminal (an application that directly interacts with the computer through typed commands) to save the project to the desired place on the computer through the cd (change directory) command</li>
  <li>Create the repository by running the git init command</li>
  </ul>
  <li>Add a new file to the repository</li>
  <ul>
  <li>Use any text editor or run a touch command</li>
  <li>Use the git status command to see which files Git considers to exist </li>
  </ul>
  <li>Add the file to the staging environment (where the program is tested in private)</li>
  <ul>
  <li>Use the git add command</li>
  <li>Rerun the git status command to see that Git has added the file to the staging environment</li>
  </ul>
  <li>Create a commit</li>
  <ul>
  <li>Run the git commit command</li>
  <li>Make a message at the end of the commit that relates to what the commit is</li>
  </ul>
  <li>Create a branch (separate "states" of a program) to add features to the program without making permanent changes to the main version</li>
  <ul>
  <li>Run "git checkout -b < my branch name >" (remove spaces between "my branch name" and its external arrows)</li>
  <li>Run the git branch command to confirm that the branch was created</li>
  <li>Note that the branch name with the asterisk next to it indicates which branch is pointed to at a given time</li> 
  </ul>
  <li>Merge the branches (optional)</li>
  <ul>
  <li>"Check out" the branch by running "git checkout master"</li>
  <li>Run "git merge (branch name)"</li>
  </ul>
  </ol>
  <h3>Using Github</h3>
  <p>On Github, the user can make a new repository and create commits directly on the repository, or they can push (sending committed changes to a remote repository) import an existing repository from the command line.<p>
  <h4>Create a New Repository or Push (Import) an Existing Repository from the Command Line</h4>
  <h5>Creating a New Repository from Scratch</h5>
  <ol>
  <li>Click on the button that says "New" and displays a book icon</li>
  <li>Customize the new repository</li>
  <li>Code on the new repository using HTML</li>
  </ol>
  <h4>Pushing (or Importing) an Existing Repository from the Command Line</h4>
  <ol>
  <li>Enter the clone URL of the existing repository into the URL field</li>
  </ol>
  
  <h2>Media</h2>
</body>
<html>
