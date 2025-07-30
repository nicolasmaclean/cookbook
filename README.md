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
- treat links as shortest path

### Get content from obsidian sync
1. open obsidian 
2. setup 'Cookbook' vault from obsidian sync
3. close obsidian
4. move the everything from inside this to cookbook/content (overwrite existing files)
(next time you open obsidian, open from cookbook/content)

### Preview website
```
npx quartz build --serve
```

### Publish website (THIS DOES NOT WORK YET)
```
npx quartz sync
```
- if you see unable to access 'github.com/nicolasmaclean.git' when trying to push changes, just manually run git push or use some kind of git gui

---

🔗 Read the documentation and get started: https://quartz.jzhao.xyz/
