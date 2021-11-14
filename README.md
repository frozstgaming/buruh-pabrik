## How to Clone ?

Open the save location directory with commandline / terminal / git cli / etc.

Then run this command
```bash
> git config --global user.email "Pemuda@tersesat.com"
> git config --global user.name "Pemuda Tersesat"
> git clone https://github.com/frozstgaming/buruh-pabrik.git
```

## How to Sync to the latest saved games ?

```bash
> git fetch --all
> git pull origin master
```

## How to Update to the latest saved games ?
1. You need to make sure your branch already sync *refer to How to sync above
2. Then run this command
```bash
> git status #to see the changes
> git add .
> git commit -m "Update #1"
> git push origin
```

Happy Industrying