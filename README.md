# CLI first git test

Before using the CLI: 
1. surf github.com and create a new repository
2. generate a classic TOKEN with no expiration date from: 
> profile settings > developer settings > Personal access tokens


using CLI:

```
$ git init
$ git branch -M main 
$ git commit -m "message"
$ git remote add origin https://github.com/<profilename>/<repo_name.git>
$ git push -u origin main  # the push will ask you for a password, use the TOKEN
```


