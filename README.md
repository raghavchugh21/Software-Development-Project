# Software Development Project

This project was created by me as the customer interface manager of ISDL07 Lab Group to help the team understand how github issues and pull requests work.
Each member had to handle the issue created by me for their ID, by following the steps mentioned below :

1. Go to https://github.com/raghavchugh21/ISDL-Practice-Project
2. Go to Issues
3. Find the issue to fix your roll number
4. Leave a comment "I'll work on this issue"
5. Go back to the repository and fork it, and select your account
6. Go to your own github page, open the forked repository and click on Clone or Download, select clone with HTTPS and copy the code
7. Create a new folder on your desktop named "open-source-contributions"
8. Open the terminal or CMD and type `cd desktop/open-source-contributions`
9. Then Type `git clone {The Link You Copied}`
10. Now type `cd ISDL-Practice-Project`
11. Type git branch, you should see *master* because that is the branch you are working on
12. Type `git checkout -b {Issue Number You're Working On}` - You can find the issue number next to '#' in your issue in the issues tab on the main repo; they will be in the range 1-8
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
