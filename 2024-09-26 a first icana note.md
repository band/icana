# 2024-09-26 a first icana note

- a trial run at a MassiveWiki in a iCloud vault
	- expect to be able to access on the desktop, and with iAWriter on the iPad
	- also expect to have as a GitHub repo
-
- adding text using iAWriter; so, yay!  
  (also corrected typo using Obsidian)

- set up the vault as a GitHub repository; here are the steps:  
	- first copied an existing `.gitignore` from another vault, and created a simple `README.md` file, and then:  
```shell
git init
git add .
git commit -m "initial commit"
gh repo create icana --public
git remote add origin https://github.com/band/icana.git
git remote -v
git push -u origin main
```

