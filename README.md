
×
Congrats on completing activity 'Linting Our Lunch'!
Git, Markdown, and the Dev Workflow
Walkthrough
35 minutes
 Status
Incomplete
We will create a new Git repository, learn the basics of Markdown, and create a README file with our newly learned Markdown skills.

When starting and maintaining a new project, there are a number of common steps a developer follows.

To practice these steps, our new project directory will be a repository of content (not code) as it will be used to hold all of our class notes throughout the course. Bla bla bla

Initializing A New Project
Create a directory in your /vagrant folder called lighthouse-web-notes.

cd /vagrant
mkdir lighthouse-web-notes
This will serve as the project directory.

Switch into your newly created directory.

cd lighthouse-web-notes
Initialize a new git repo in this directory.

git init
Create a README file (called README.md) using the Terminal.

touch README.md
Add the README.md file to the repository

git add README.md
Commit your changes

git commit -m  "Blank README.md added"
Pushing to Github
We can now push this new repository along with its single commit to a new repository on GitHub.

Create a new and completely empty repository with the same name on GitHub.

There is no need to initialize with a README on Github, as we will be creating our own.



Add the URL of the new repo as a remote on your local repo.

git remote add origin <URL>
(Replace <URL> with the URL of your repo)

Push your changes to GitHub.

git push -u origin master
Single Projects Per Editor Window
Working with our new project in the editor, it's important to avoid just opening the files we want to edit. Instead, we should open the entire project folder in a new editor window.

Open the lighthouse-web-notes folder in VSCode.

Formatting the README with Markdown
Our README file has the .md extension, which tells us that the contents of the file contains markdown.

Markdown is a simple markup language that allows a developer to easily format text. Markdown can also be parsed into HTML, allowing Markdown to be used in webpages.

Headings
Most GitHub repositories have a README.md file in the root directory that provides useful information about the project.

Today we will be using our README file to describe our repository, and provide convenient links to the repository folders.

Add a Title

Let's start by adding a title to our README. Insert the following Markdown code as the first line of your README file.

# Farid Asadpour's Notes

## Summary 

This repository contains all of the notes taken by [Your Name] for the Lighthouse Labs Web Development Bootcamp.

....taken by [Farid Asadpour](https://github.com/yani5752000) for the [Lighthouse Labs](https://www.lighthouselabs.ca/)