# github-workflow assignment

## Instructions:
***NOTE:***This assignment has a dual purpose. 1. To test the Git workflow procedures for completing assignments this semester and 2. To refresh your knowledge of basic Java principles. I have included a simple Java "HelloWorld" project for you to edit, commit, and push from your local computer. NOTE: These steps are for using git via the command line. Extra credit for anyone that forks this repository and adds workflow steps for any gui (Windows, Mac, or Linux) program they use.

### TODO:
1. Git workflow: Complete the [Git Workflow steps](#workflow) below. You must have at least two commits/pushes (steps 8-11)
2. Java refresh: Refactor the mini-Java project. 
 * Add to the provided project a simple pet store. Limit what the store sells to just pets. Each pet type should be its own class as well as the actual pet store. The pet store should have methods of selling and buying pets. There should also be a way to see what pets are available for purchase, so some sort of simple inventory should be kept. You should make at least three different animals types. You MUST have at least one superclass. Main.java should be the entry point and should print out the inital contents of the pet store. Also include a printout of your methods in action, such as buying a cat and showing the inventory with the new cat quantity. Feel free to make the program interactive with a user, but there are no extra points for this. There are, HOWEVER, extra points for working jUnit tests that exercise your methods in the pet store.
 
 The steps for this project should go like this:
  * Complete Workflow steps 1-6.
  * Import your project into an IDE such as Eclipse.
  * Complete your Pet Store Java project in your IDE.
  * Perform Workflow steps 7-12.
  * Edit your Pet Store project in your IDE some more.
  * Perform Workflow steps 7-12.
 
 ***Note:*** Any issues you have with either the GitHub steps or Java questions should be asked publically in Piazza. If you have a question, chances are someone else does also. If you see someone has posted a question on Piazza and you know the answer, please chime in and answer. 

## Workflow (Command Line):
1. Click on project invitation
  * This will create a custom repository for you inside the classroom organization account [CSCI-490-MobileAppDevelopment](https://github.com/CSCI-490-MobileAppDevelopment)
2. Find your custom repository (either by going to the [organization account](https://github.com/CSCI-490-MobileAppDevelopment) or clicking on link that was emailed to you)
3. Click button that is labeled "Clone or download"
  * Copy either the https or ssh link (I recommend you set up ssh)
4. On the command line, navigate to where you want the project to be located
  * eg. Type: `cd cofc/csci490/projects/`
5. Type: `git clone \<paste your repository link here \>`
6. This will put your project on your local computer. You are ready to start editing/adding files. For practice, any text editor will do. Once you have completed your files:
7. On the command line, navigate to the top level of your project. This will be where the README is located.
8. Type: `git status` and ensure you see you have something to add to a commit set.
9. Type: `git add .` to add all files (NOTE you can add each file individually if you desire)
10. Type: `git commit -m "initial commit"`
11. Type: `git push origin master`
12. Check your repository in GitHub to ensure that your push was sucessfull. You can make further edits and repeat steps 8-11 as many times as you want/need. I will be able to grade based on these pushes. I will be able to see your progression easier if you commit and push often. This will also allow me to see how much you got done by the deadline and after should you keep pushing after the deadline.
