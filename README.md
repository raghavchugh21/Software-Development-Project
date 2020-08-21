# ISDL-Practice-Project

This is a project created by the customer interface manager to help the team understand how github issues work.

1. Go to https://github.com/raghavchugh21/ISDL-Practice-Project
2. Go to Issues
3. Find the issue to fix your name
4. Leave a comment "I'll work on this issue"
5. Go back to the repository and fork it, and select your account
6. Go to your own github page, open the forked repository and click on Clone or Download, select clone with HTTPS and cope the code
7. Create a new folder on your desktop named "open-source-contributions"
8. Open the terminal or CMD and type `cd desktop/open-source-contributions`
9. Then Type `git clone {The Link You Copied from CLone HTTPS}`
10. Now type `cd ISDL-Practice-Project`
11. Type git branch, you should see *master* because that is the branch you are working on
12. Type `git checkout -b {Issue Number You're Working On}`
13. Type `git branch` and you should see *{Issue Number} in the green color, that means this is a new branch you created to fix the issue
14. Type `code .` to open in vscode, change your roll number and save the file
15. Type `git diff` and you should see the changes you made to your roll number
16. Type `git pull`
17. Type `git branch --set-upstream-to=origin/master {Issue Number}`
18. Type `git add .`
19. Type `git commit -m "This fixes #{Issue Number}"` 
20. Type `git push origin HEAD`
21. Now go to your Github page and click on the notification you get "Compare and Pull request"
22. Click on 'Create Pull Request'
23. Congrats, You're done!
