# 🦅 PTERODACTYL ADMIN DISCORD BOT

Enterprise-grade **Pterodactyl Panel management directly from Discord**.  
Built with **discord.py 2.x** using modern **Slash Commands**.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 📦 Versions

**V1 — Stable Release** ✅  
• Initial production release  
• Core panel management system

**V1.0.1 — Update**  
• Added `/manage` command  
• Server start/stop buttons  
• Real-time resource usage monitoring

**V2 — Big Upgrade (Coming Soon)** 🚀

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 🚀 What Is This?

A **complete Application API management system** for **Pterodactyl Panel** that allows administrators to manage everything directly from **Discord**.

### Manage Directly From Discord

• Nodes  
• Servers  
• Eggs  
• Nests  
• Mounts  
• Database Hosts  
• Users  
• Roles  
• Suspend / Unsuspend Servers  
• Server Creation Wizard (Auto Egg Configuration)  
• Real-Time Server Resource Monitoring  

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## ⚡ Quick Setup

### 1️⃣ Install Requirements
```bash
pip install -r requirements.txt
```

### 2️⃣ Configure Environment
```bash
cp .env.example .env
nano .env
```

### 3️⃣ Run the Bot
```bash
python main.py
```

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 🔐 Environment Configuration

```env
DISCORD_TOKEN=YOUR_DISCORD_BOT_TOKEN
OWNER_ID=YOUR_DISCORD_USER_ID
PTERODACTYL_URL=https://panel.example.com
PTERODACTYL_API_KEY=YOUR_APPLICATION_API_KEY
```

⚠ **Important:**  
Use the **Application API Key**, **NOT** the Client API Key.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 🧠 Core Features (V1)

✔ Slash command system  
✔ Owner-only security  
✔ Ephemeral responses  
✔ Clean embed UI  
✔ Async API client (aiohttp)  
✔ Auto pagination system  
✔ Suspend / Unsuspend servers  
✔ Smart server creation wizard  
✔ Crash-safe architecture  

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 🛠 Command System

### `/help`
Displays the admin command overview.

### `/nodes`
Manage panel nodes

• overview  
• list  
• create  
• edit  
• delete  
• allocations  
• servers  
• create-allocations  
• delete-allocations  

### `/servers`
Manage servers

• overview  
• list  
• create  
• edit-details  
• edit-build  
• edit-startup  
• delete  
• databases  
• suspend  
• unsuspend  
• reinstall  

### `/users`
Manage panel users

• overview  
• list  
• create  
• edit  
• delete  
• roles  
• servers  

### `/roles`
Manage roles

• overview  
• list  
• create  
• edit  
• delete  

### `/manage`
Interactive server management

• Start / Stop server buttons  
• Real-time resource usage  
• Live server status monitoring  

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 📂 Project Structure

```
ptero-bot/
├── main.py
├── api_client.py
├── config.py
├── requirements.txt
├── .env.example
└── cogs/
    ├── utils.py
    ├── help.py
    ├── nodes.py
    ├── eggs.py
    ├── nests.py
    ├── mounts.py
    ├── database_hosts.py
    ├── users.py
    ├── servers.py
    ├── roles.py
    ├── server_suspend.py
    └── manage.py
```

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 🛡 Security

• Never expose the `.env` file  
• Regenerate API key if leaked  
• Restrict panel IP access  
• Limit Discord bot permissions  
• Use owner-only command access  

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 🔄 Version History

### V1
• Full admin management system  
• Suspend / Unsuspend servers  
• Auto egg configuration  
• Production ready  

### V1.0.1
• Added `/manage` command  
• Server start / stop buttons  
• Real-time resource monitoring  

### V2 (Coming Soon 🚀)

• Interactive help UI  
• Advanced logging system  
• Rate-limit auto retry  
• Audit logging  
• Multi-owner support  
• Permission system  
• Performance optimizations  

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# 👑 Owner

Made with ❤️ by **Zerioak**
