# Maclean Cookbook

### Get the repo

```
git clone https://github.com/nicolasmaclean/cookbook.git
cd cookbook
```

### Initialize repo

```
npm i
npx quartz create 
```

- if this doesn't work because content/index.md is missing, manually created an empty text file here and rerun
- select "treat links as shortest path"

### Get content from obsidian sync

1. open Obsidian 
2. "Open vault from Obsidian Sync"
3. Connect "Cookbook"
5. Set location to the root of the repo
6. Create!
7. Give Obsidian a minute to download all the files

### Preview website

```
npm run preview
```

### Publish website

In bash
```
npm run sync
```

For windows
```
cp -r Cookbook/* content; npx quartz sync
```

For unix (?)
```
cp -r Cookbook/* content && npx quartz sync
```

- if you see unable to access 'github.com/nicolasmaclean.git', it probably indicates you lack access to the repo from where you are running this command. You can manually git push from a different terminal or gui.

---

🔗 Read the documentation and get started: https://quartz.jzhao.xyz/
