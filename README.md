# GitExperiment
<p>
<h3>
Initialize or clone a repo</h3>
git init OR git clone https://github.com/ekansh/GitExperiment.git
</p>
<p>
<h3>
Adding a remote repository </h3>
git remote add origin https://github.com/try-git/try_git.git
</p>
<p>
<h3>
Add file to staging </h3>
git add file1.txt file2.txt
git add .  
add all files under the current directory to the project WARNING: including untracked files.
</p>
<p>
<h4>
UNDO</h4>
git reset filename
</p>
<p>
<h3>
Committing a file </h3>
git commit -m "commit message"
</p>
<p>
<h4>
UNDO</h4>
1) git reset HEAD~1
this way you want lose the work you did
OR
2) git reset --hard HEAD~1 { however you will lose the files that were created or modified as part of previous commit}
</p>
<p>
<h4>Reference</h4>
https://stackoverflow.com/questions/927358/how-to-undo-the-last-commits-in-git
</p>
<p>
<h3>Pushing to remote repository</h3>
git push -u origin master
</p>

