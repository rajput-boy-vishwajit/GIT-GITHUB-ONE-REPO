<h2>Git/GitHub In One Shot</h2>
<h3>Quick Setup</h3>

<p>
...or create a new repository on the command line
</P>
<pre>
echo "# Add changes in File" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin <https://github.com/[USERNAME]/[REPONAME].git>
git push -u origin main
</pre>

<p>
...or push an existing repository from the command line
</p>
<pre>
git remote add origin <https://github.com/[USERNAME]/[REPONAME].git>
git branch -M main
git push -u origin main
</pre>

<p>
...configure new folder local repository on the command line
</P>
<pre>
git init
git config --global user.name "[USERNAME]
git config --global user.email "[USEREMAIL]
git congig --list
</pre>


<p>
...creating and working on new branch from the command line
</p>
<pre>
git branch
git branch -M main
git checkout
git checkout -b
git checkout -d
</pre>


<p>
...merge code with feature branch from the command line
</p>
<pre>
git branch
git diff
git merge
git diff main
git branch -d [BRANCHNAME]
</pre>


<p>
...merge code with feature branch from the command line
</p>
<pre>
git status
</pre>

<p>
...--- from the command line
</p>
<pre>
git 
</pre>

<p>
...I have Changed the UserName to "RajputVishwajit"
</p>
<pre>
git 
</pre>




<h1>🚀 Git Commands Cheat Sheet</h1>

<h2>✅ MUST-KNOW GIT COMMANDS</h2>
<pre>
git status        # check changes / repo state
git branch        # check current branch
git remote -v     # check connected GitHub repo
git pull          # download latest changes

git add .         # select all files
git commit -m ""  # save changes
git push          # upload to GitHub
</pre>

<hr>

<h2>🔰 SETUP COMMANDS (Only once per repo)</h2>
<pre>
git init                          # start repo
git remote add origin &lt;url&gt;       # connect to GitHub
git branch -M main                # set branch to main
git push -u origin main           # first push
</pre>

<hr>

<h2>🔄 FIX / PROBLEM COMMANDS</h2>
<pre>
git pull --allow-unrelated-histories   # fix repo mismatch
git restore file.txt                   # undo changes
git reset --soft HEAD~1                # undo last commit
</pre>

<hr>

<h2>🌿 BRANCH COMMANDS</h2>
<pre>
git checkout -b new-branch   # create + switch branch
git checkout main            # switch back
</pre>

<hr>

<h2>⚡ DAILY WORKFLOW</h2>
<pre>
git pull
git add .
git commit -m "message"
git push
</pre>

<hr>

<h2>🧠 SIMPLE MEMORY</h2>
<pre>
status → check
add    → select
commit → save
push   → upload
pull   → download
</pre>

<hr>

<h2>🔥 PRO TIP</h2>
<p><b>Always start with:</b></p>
<pre>
git pull
</pre>

<p>This avoids:</p>
<ul>
  <li>❌ rejected push</li>
  <li>❌ merge errors</li>
  <li>❌ conflicts</li>
</ul>