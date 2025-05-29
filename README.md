# Angular app sample

---

- [🚀 Init](#-init)
- [✨ Prettier setup](#-prettier-setup)
- [✨ ESLint setup](#-eslint-setup)
- [✨ Stylelint setup](#-stylelint-setup)

---

### 🚀 Init

- run `npm run init <project name> <prefix>`
- run `npm install`
- remove `init` command from `package.json`
- remove `tools/init-project.js`
- create GitHub repo and set remote
  ```
  git remote set-url origin https://github.com/<username>/<reponame>.git
  git push -u origin master (or main)
  ```
- confirm that git remote is set up correctly
  ```
  git remote -v
  ```
- setup Prettier, ESLint and Stylelint according to steps below
- replace README.md content with your own
- remove `images` folder

---

### ✨ Prettier setup

- `cmd + ,`
- search `Prettier`
- enable `Automatic Prettier configuration`
- insert `**/*.{ts,js,html,css,scss,json,yml,md}`
- enable `Run on save`
- `Apply` / `OK`

<details>
  <summary>🎆 Screenshot</summary>
    
  <img src="images/prettier.png" width="500" alt="img" />
</details>

---

### ✨ ESLint setup

- `cmd + ,`
- search `ESLint`
- enable `Automatic ESLint configuration`
- insert `**/*.{ts,js,html,json,yml,md}`
- enable `Run eslint --fix on save`
- `Apply` / `OK`

<details>
  <summary>🎆 Screenshot</summary>

  <img src="images/eslint.png" width="500" alt="img" />
</details>

---

### ✨ Stylelint setup

- `cmd + ,`
- search `Stylelint`
- enable `Enable`
- insert `**/*.{css,scss}`
- enable `Run stylelint --fix on save`
- `Apply` / `OK`

<details>
  <summary>🎆 Screenshot</summary>

  <img src="images/stylelint.png" width="500" alt="img" />
</details>

---
