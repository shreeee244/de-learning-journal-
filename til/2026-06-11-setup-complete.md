# til - june 11 , 2026
## what i did today
-created 3 repo with proper folder structure 
-started with python course from udemy completed 2 day's task and made small python project called band name genrater 
- started a course on sql from mode.sql 
## how to make a folder and files than how to push in github
STEP 1

Go to GitHub.
Click New Repository.
Name it de-learning-journal.
Make it Public.
Add a README.
Create repository.

STEP 2
* clone it first 
git clone https://github.com/shreeee244/de-learning-journal.git
* check the foler 
ls
* You should see something like:
de-learning-journal-
de-sql-practice
...
* create a folder 
cd de-learning-journal-
* create the structure
mkdir weekly-goals, til, resources
* create files
echo "# Weekly Goals" > weekly-goals\README.md
echo "# Today I Learned" > til\README.md
echo "# Resources" > resources\README.md
* verify 
tree /F

STEP 3
* push to git hub
git add .
git commit -m "initialize learning journal structure"
git push origin main