# CLI first git test

**Before** using the CLI: 
1. surf [github.com](https://github.com) and create a new repository
2. generate a classic TOKEN with no expiration date from: 
> profile settings > developer settings > Personal access tokens


Using **CLI**:

```
git init
git branch -M main 
git commit -m "message"
git remote add origin https://github.com/<profilename>/<repo_name.git>
git push -u origin main  # the push will ask you for a password, use the TOKEN
```

After modifying files
```
git add README.md
git commit -m "message"
git push -u origin main 
```

**Clone** a repository from CLI:
```
cd destination_dir
git clone https://github.com/<profile>/<repo_name.git>
```
