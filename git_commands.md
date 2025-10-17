Git commands: 

1. Initialize git in folder: 
```
git init 
```

2. Add all existing files: 
```
git add . 
``` 

3. Commit your current version: 
```
git commit -m "Intial commit - existing local prep folder" 
```

4. Link Github repository
```
git remote set-url origin https://<YOUR_USERNAME>@github.com/MBharathiMozhian/ML_preparation.git
```
(or) 
``` 
git remote add origin https://github.com/<your-username>/<repo-name>.git
``` 

Check if it's added: 
```
git remote -v
```

5. Merge remote changes before pushing
Use this if you don't want to lose any commits that exist on GitHub
```
git pull --rebase origin main
```

6. Push Changes to repo: 
```
git push -u origin main
``` 
