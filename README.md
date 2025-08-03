# Learning-Github
## step by step guide to create a repo
 
1. create a local repository

``` bash
mkdir my_github_repo
cd my_github_repo
git init
```
2. create a **README**.md file

create a file named README.md and add markdown content:
```markdown
# my github repository
## how to create a github repo and upload your project
1. create a folder:
  ```bash
  mkdir my_github_repo
  cd my_github_repo
```

3. create your project files (e.g., README.md, code files)

4. stage and commit:

```bash
git add .
git commit -m 'initial commit with README'
```

5. create a github repository (on [github.com](http://github.com))

   - go to [github.com](http://github.com)
   - click on **New Repository**
   - don't initialize it with a **README** (since you already have one)
7. link your local repo to github:

```bash
git remote add origin
https://github.com/your-username/your-repo-name.git
```

7. push your code:

```bash
git branch -M main
git push -u origin main
```
Done!
