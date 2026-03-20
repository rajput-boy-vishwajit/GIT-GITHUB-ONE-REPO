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
</pre>