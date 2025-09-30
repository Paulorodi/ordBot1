
# ordBot1 – WhatsApp MD User Bot

**ordBot1** is a simple and powerful WhatsApp MD User Bot created and maintained by **Paul Orodi**.  
It helps automate tasks, run commands, and enhance your WhatsApp experience.

---

## 🚀 Features
- Fast and lightweight
- Multi-deployment support (Heroku, Koyeb, VPS, Render, Replit)
- Easy configuration with `config.env`
- Auto-start with `pm2` on VPS
- Extendable with plugins

---

## 🔧 Deployment Options

- **Heroku** → [Deploy Now](https://qr-hazel-alpha.vercel.app/heroku)  
- **Koyeb** → [Deploy Now](https://qr-hazel-alpha.vercel.app/koyeb)  
- **Render** → [Deploy Now](https://qr-hazel-alpha.vercel.app/render)  
- **Replit** → [Run on Replit](https://replit.com/@Paulorodi/ordBot1)  
- **VPS/PC** → Clone the repo and run with Node.js & pm2  

```sh
git clone https://github.com/Paulorodi/ordBot1
cd ordBot1
yarn install
pm2 start . --name ordBot1 --attach --time
````

---

## ⚙️ Environment Variables

Set these in `config.env` before running:

```
SESSION_ID = your_session_id_here
PREFIX = .
STICKER_PACKNAME = ordBot1
LANGUAG = en
SUDO = 25479283897
TZ = Africa/Nairobi
```

---

## 📌 Requirements

* Node.js 20+
* Yarn
* pm2 (for VPS/PC runs)

---

## 🙏 Credits

* Built on top of open-source WhatsApp bot frameworks
* Customized and maintained by **Paul Orodi**

---

## 🌐 Repository

[GitHub Repo – ordBot1](https://github.com/Paulorodi/ordBot1)


