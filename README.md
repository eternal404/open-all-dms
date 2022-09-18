<div align="center">
  <h3>DM Opener</h3>
  <a href="https://www.codefactor.io/repository/github/localip/dm-opener">
    <img src="https://www.codefactor.io/repository/github/localip/dm-opener/badge" />
  </a>
  <a href="https://github.com/localip/dm-opener/issues">
    <img src="https://img.shields.io/github/issues/localip/dm-opener?style=flat" />
  </a>
  <a href="https://github.com/localip/dm-opener/stargazers">
    <img src="https://img.shields.io/github/stars/localip/dm-opener?style=flat" />
  </a>
</div>

---

<div align="center">
  Small script to extract private message channels from a discord data package & open them on a certain account.
</div>

---

### How do i use it?

First, you'll need your data package. You can get this by going to Settings > Privacy & Safety and clicking the Request Data button at the bottom.
<br /><br />![image](github/images/picture.png)

### I have my data package, now what?

- Make sure you have [NodeJS](https://nodejs.org/) installed
- Once you have your data package, extract it and make sure you have the messages folder inside.
- Open a Command Prompt/Terminal in this projects directory.
- Run `npm install` and wait for it to finish.
- Edit the `config.json` file with your token and User ID.
- Run `node . "C:\Users\USERNAME\Downloads\package\messages"`. (Replace the path with the path of your messages folder inside your package)
- Wait for all your DMs to open.
