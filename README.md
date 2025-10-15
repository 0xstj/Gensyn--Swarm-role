# How to claim "Swarm role" in <img width="30" height="-30" alt="image" src="https://github.com/user-attachments/assets/682a583a-63a3-4ddf-a840-aab7e94441e0"/> Gensyn discord server‼️- Github guide
👉We are going to claim this role without VPS with help of github codespace🤔

➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖

## Gensyn Documentation <img width="30" height="-30" alt="image" src="https://github.com/user-attachments/assets/682a583a-63a3-4ddf-a840-aab7e94441e0"/> - https://github.com/Deep-Commit/gswarm

A step-by-step guide to set up your <b>GSwarm Node</b>, receive live Telegram updates, and verify your account to claim your <b>Swarm Role</b> on Discord.
</p>

---

## ⚙️ Prerequisites
Before starting, make sure you have:
- A VPS or local system (Linux recommended)
- Installed `git` and `curl`
- A working **Telegram** and **Discord** account
- Access to [Gensyn Dashboard](https://dashboard.gensyn.ai)
- Basic terminal knowledge

---
## Step 1: 🖥️Go to your Github Codespace - https://github.com/codespaces

## Step 2: 🧠 Install Gswarm CLI with Go

```bash
go install github.com/Deep-Commit/gswarm/cmd/gswarm@latest

```

✅ Check version:

```bash
gswarm --version

```
🛠️ Step 3: Configure GSwarm Node
Run this command in your codespace and follow steps:

```bash
gswarm

```
👉It will ask for:

● Bot Token-

● Chat ID-

● Your EOA Address (from Gensyn Dashboard)-https://dashboard.gensyn.ai/

💠Note if you have id on gensyn then sign in otherwise sign up first with your email & always use same email

● After setup, GSwarm will start monitoring and sending live node updates to your Telegram chat.


🤖 Step 4: Create Your Telegram Bot

Click on this Link - https://t.me/BotFather

Run /newbot and follow the steps

Copy your Bot Token (keep it safe — don’t share!)

🧾 Example Bot Token format:

```bash
8314754474 : AAHj3HQqKyA9BBj8oaSfwLmDwWsAmQNklZo

```

💬 Step 5: Get Your Telegram Chat ID

● Message your bot once like - hi or hello , then copy this link below & open in new tab in your chrome brownser.

```bash
https://api.telegram.org/botYOUR_BOT_TOKEN/getUpdates

```
● <YOUR_BOT_TOKEN> 👈cut this your bot token and paste you own that you saved earlier

● Wen open above link after putting your own bot token than you see like this - {"id":123456789}
this id is your chat id copy and save it somewhere

📡 Step 6: Link Telegram with Discord

Join the Official Discord Server - https://discord.gg/gensyn

Go to channel : # link-for-access

Run the slash command:

```bash
/link-telegram

```
The bot will send you a unique verification code

Now open your Telegram bot and type:

```bash
/verify <your-code-here>

```
✅ If everything is correct, you’ll receive a confirmation and get your Swarm Role automatically.




























