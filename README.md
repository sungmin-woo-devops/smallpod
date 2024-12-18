## Smallpod Tech Blog

Cloud Computing Journey

---
### Prerequisites
```bash
git clone https://github.com/sungmin-woo-devops/smallpod.git
cd smallpod
npm install
npx quartz create
```

### How to use
1. ./content : Write *.md files for main contents
2. 

https://quartz.jzhao.xyz/authoring-content
https://quartz.jzhao.xyz/configuration
https://quartz.jzhao.xyz/layout


### How to run
```bash
npx quartz build --serve

# listen at 32999
npx quartz build --serve --port 32999

---
npx quartz build --help

Most of these have sensible defaults but you can override them if you have a custom setup:

    -d or --directory: the content folder. This is normally just content
    -v or --verbose: print out extra logging information
    -o or --output: the output folder. This is normally just public
    --serve: run a local hot-reloading server to preview your Quartz
    --port: what port to run the local preview server on
    --concurrency: how many threads to use to parse notes

```
### How to host
```bash
https://quartz.jzhao.xyz/setting-up-your-GitHub-repository
https://quartz.jzhao.xyz/hosting

```

---
Powerd by Quartz v4 (Digital-garden)
Edited in Obsidian
