# ASSIGNMENT #4 (COMPLETE)

## Objective
This week you will:  
- Work with branches and a basic Git Flow

## PREREQUISITES  
You have a working remote repository. 

## ACTIVITY 1: 

### Background
- This week you will practice working with branches.  Often you will see a main branch, a dev branch, 
and several other branches that are used for new features, releases, or bug fixes.  
- The main branch is very carefully controlled and all of the developers will integrate their code into the dev branch, which will eventually be merged 
with the main branch after the code is known to work.   
- Several developers will work at the same time on different features and merge those into the dev branch.   

### What to do
1. Make your own feature branch and use that to make changes that will be merged into your main branch.   Optionally, you can also create a dev branch as described above.  The branch can be created at the command line, but try making your feature branch via Visusal Studio Code.  

- Click on the little branch icoon.
- In the popup window, click + Add new Branch

![alt text](files/screenshots/image-1.png)

- You will see the branch at the bottom of the window, but you can also use the CLI, to see
the local and remote branches.   Is there a remote branch create yet?

![alt text](files/screenshots/image-2.png)

- Commit your changes to the local repo branch and then publish it to the remote repo.  

![alt text](files/screenshots/image-3.png)

- What is different when you run git branch and git branch -r?  

- When you are done making your changes, go to Git Hub (the URL), and issue a pull request to merge your feature branch on the remote repo.  This will also delete your remote feature branch.  Will the local feature branch still exist?  

![alt text](files/screenshots/image-4.png)

- Since your feature is complete, then delete the remote repo.  First, run the following command 
to update the local metadata.  

```
git fetch -p
```



### A Typical Git Flow
![A typical Git Flow](./files/diagrams/git-flow-1.excalidraw.png)


# ADVANCED EXERCISES
### For those who did this project in a previous class

### Read the following articles
[AI Emotional Awareness](./files/articles/emotional-awareness.pdf)

[Games are Rigged](./files/articles/guardian-rigged.pdf)


### Discuss 
- What are some of the AI Assisted Coding tools, e.g. Cursor?   Will they replace coding as a skill?
- If learning to code will become less important, what new skills will software engineers need to have.
- Many think that software engineers will need to develop people skills more than ever.  Will AI out perform people in that area as well?

# WHAT TO TURN IN

- Your assignment will be completed in a markdown file. 
- Name the markdown file:

```
Assignment4<Lastname>
```
- Follow the directions above to ensure that your markdown file contains everything required for the assignment.
- Ensure that your markdown file for the assignment includes appropriate screen shots. 
- In the Slack channel #github-project, post the link to your GitHub repo that you created above when you are done.

### NOTE: 
- Ensure in the root directory of your repository, you have a markdown file called "README.md."  In that file, include a link to the assignment this week. 
- Example: 

```
[Assignment #X](./Assignment#<Lastname>.md)
```

### For advanced users (those who did the project before)
- Follow the directions for "ADVANCED EXERCISES" and include your work in the markdown assignment for the week.  
- Ensure that the "ADVANCED EXERCISES" section is clearly labeled with appropriate "header markdown." 

