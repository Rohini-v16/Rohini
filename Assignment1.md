Tasks To Be Performed:
 1. Based on what you have learnt in the class, do the following steps:

 a. Create a new folder

mkdir XYZProject
cd XYZProject

 b. Put the following files in the folder 

● Code.txt 
● Log.txt 
● Output.txt 

touch Code.txt Log.txt Output.txt
echo "Sample code" > Code.txt
echo "Log entry" > Log.txt
echo "Output result" > Output.txt

c. Stage the Code.txt and Output.txt files 
Initialise GIT Repository
git init
git add Code.txt Output.txt


d. Commit them
git commit -m "Initial commit with Code and Output files"
 	e. And finally push them to GitHub 
git remote add origin https://github.com/Rohini-v16/Rohini.git
git branch -M main
git push -u origin main


2. Please share the commands for the above points

mkdir XYZProject
cd XYZProject
touch Code.txt Log.txt Output.txt
git init
git add Code.txt Output.txt
git commit -m "Initial commit with Code and Output files"
git remote add origin https://github.com/Rohini-v16/Rohini.git
git branch -M main
git push -u origin main
