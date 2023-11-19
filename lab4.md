### 4)
# Logging into ssh account

<img width="604" alt="lab4-step4" src="https://github.com/shinaegyo/lab-report-4/assets/137027086/7558094b-da77-4bc3-9f5e-21702e7335e3">

Accompanying the screenshot,
Keys Pressed: ssh cs15lfa23ml@ieng6.ucsd.edu <Enter>


### 5)
# Git Cloning

<img width="637" alt="lab4-step5" src="https://github.com/shinaegyo/lab-report-4/assets/137027086/fc8fbe1c-ebe2-445d-b897-0779240070be">

Accompanying the screenshot,
Keys Pressed: git clone git@github.com:shinaegyo/lab7.git <Enter>

### 6)
# Showing failed test

<img width="547" alt="lab4-step6" src="https://github.com/shinaegyo/lab-report-4/assets/137027086/b44a45cd-1e5c-4047-bf7b-e44054c13faf">

Accompanying the screenshot,
Keys Pressed: cd lab <Enter> , bash test.sh <Enter>

### 7)
# Fixing the code in Vim

<img width="552" alt="lab4-step7" src="https://github.com/shinaegyo/lab-report-4/assets/137027086/7a5e3c37-b63d-4ac0-bc50-246bcb67b011">

Accompanying the screenshot,
Keys Pressed: vim ListExamples.java <Enter> , <j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><j><l><l><l><l><l><l><l><l><l><l><l><r><2><esc><:wq> 

`j` moves the cursor down one line and `l` moves the cursor right one space. `r` replaces whatever character is at the current area of the highlight and `2` replaces the 1 in index 1 to index2. The `esc` moves from insert mode to command mode and `:wq` command saves the changes and exits vim.

### 8)
# Showing Passed Test

<img width="290" alt="lab4-step8" src="https://github.com/shinaegyo/lab-report-4/assets/137027086/76e07a4f-7316-4b81-ab80-0687334230a9">

Accompanying the screenshot,
Keys Pressed: vim ListExamples.java <Enter> , bash test.sh

### 9)
# Commit and Push to Github Account

<img width="591" alt="lab4-step9" src="https://github.com/shinaegyo/lab-report-4/assets/137027086/94faa497-fe62-41e3-8e2b-535d5038fd3f">

Accompanying the screenshot,
Keys Pressed: git add ListExamples.java <Enter> , git commit -m "Changed index1 to index2 in the merge method" <Enter> , git push <Enter>

`git add command` adds a change in the working directory, in this case, ListExamples.java. `git commit -m "Changed index1 to index2 in the merge method"` takes all the changes made locally and pushes them to a remote repository. Finally, `git push` uploads the local repository content to a remote repository.
