# quick deploy guide

## 1. create repo on github
- go to github.com → click **+** → **New repository**
- name it (e.g. `fable-landing`)
- make it **Public**
- click **Create repository**

## 2. copy these commands

replace `YOUR-USERNAME` and `REPO-NAME` with your info:

```bash
cd "/Users/codylejang/Downloads/lg stuff"
git init
git add .
git commit -m "initial commit"
git remote add origin https://github.com/YOUR-USERNAME/REPO-NAME.git
git branch -M main
git push -u origin main
```

## 3. enable pages
- repo → **Settings** → **Pages**
- source: `main` branch, `/ (root)` folder
- click **Save**

## 4. visit your site
`https://YOUR-USERNAME.github.io/REPO-NAME/`

(takes 1-2 minutes to go live)

