# 🌟 CamPhish 🌟
*Capture cam shots from a target's device just by sending a link!*

## 🎥 What is CamPhish?
**CamPhish** is a powerful tool designed to capture camera shots from a target's phone front camera or PC webcam. It hosts a fake website on a built-in PHP server and uses **ngrok** or **serveo** to generate a link. When the target clicks the link and grants camera permission, CamPhish captures the shots seamlessly.

## ✨ Features
CamPhish offers two engaging webpage templates to entice targets into granting camera access:
1. **Festival Wishing** 🎉
2. **Live YouTube TV** 📺
3. **Online Meeting [Beta]** 💻

Simply input the festival name or YouTube video ID to use these templates!

## 🚀 Tested On:
- **Kali Linux**
- **Termux**
- **macOS**
- **Ubuntu**
- **Parrot Sec OS**

## ⚙️ Installation & Requirements
CamPhish requires PHP for the webserver and either SSH or serveo for link generation. Begin by installing the necessary packages:

```bash
apt-get -y install php openssh git wget
```

### 📥 Installation (Debian/Termux):
```bash
git clone https://github.com/thebugbounter/CamPhish
cd CamPhish
chmod +x camphish.sh
bash camphish.sh
```





