# Mygoodnes
This is my first Git Repository
<br>
Author: Ujjwal pandey
<br>
<h1>🔹 Steps to Create a New GitHub Repository via CMD </h1>
<h2>
  <p>
    1. Open CMD (Windows) / Terminal (Linux/Mac)
  </p>
</h2>
<p>
  mkdir myproject       # Create new folder (name: myproject)
  cd myproject          # Go inside the folder
</p>
<br>
<h2>
  <p>
    2. Initialize Git
  </p>
</h2>
<p>
<b> git init </b> 
  <p>
    👉 Creates a new empty Git repository in the current folder.
  </p>
</p>
<br>
<h2>
  <p>3. Create a File</p>
</h2>
<p>
  <b>echo "# My First Repo" >> README.md </b>
  <p>
    👉 Creates a README.md file with text inside.
  </p>
</p>
<br>
<h2>
  <p>
    4. Check Repository Status
  </p>
</h2>
<p>
  <b>git status
</b>
  <p>👉 Shows which files are new/modified/untracked.</p>
</p>
<br>
<h2>
  <p>
  5. Add Files to Staging Area  
  </p>
</h2>
<p>
  <b>git add .
</b>
  <pre>👉 Adds all files to staging (ready to commit).
       (You can also use git add filename for one file.)</pre>
</p>
<br>
<h2>
  <p>
    6. Commit Changes
  </p>
</h2>
<p>
  <b>git commit -m "First commit"
</b>
  <p>👉 Saves your changes with a message inside Git history.</p>
</p>
<br>
<h2>
  <p>
    7. Create a New Repository on GitHub Website
  </p>
</h2>
<p>
  <b>Go to GitHub → click New Repository → give it a name → Create Repository.</b>
  <p>Copy the HTTPS or SSH link:</p>
  <a href = https://github.com/Ujjwal-333/Myfirstrepo.git alt="myrepo" /a>
</p>
<br>
<br>
<h2>
  <p>
    8. Link Local Repo with GitHub
  </p>
</h2>
<p>
  <b>git remote add origin https://github.com/Ujjwal-333/Myfirstrepo.git
</b>
  <pre>👉 Connects your local repo to GitHub repo.
     (origin = name of remote repo).</pre>
</p>
<br>
<br>
<h2>
  <p>
    9. Push Code to GitHub
  </p>
</h2>
<p>
  <b>git branch -M main
     git push -u origin main
</b>
  <pre>
    👉 Sends your code to GitHub under the main branch.
      (If branch is master, replace with master.)
  </pre>
</p>
<br>
<br>
<h2>
  <p>
   🔹 Summary of Commands & Uses 
  </p>
</h2>
 <h3>   
<pre>
<b>COMMAND</b>                        <b>USE</b>
  </pre>
 </h3> 
    <h4>
      <pre>
        
mkdir foldername	                   Create new folder
cd foldername	                       Enter folder
git init	                           Initialize Git repository
git status	                         Show changes (tracked/untracked)
git add .	                           Stage all files
git commit -m "msg"                	 Save staged changes
git remote add origin <url>	         Connect to GitHub repo
git branch -M main	                 Rename branch to main
git push -u origin main	             Upload files to GitHub
      </pre>
    </h4>
<br>


