
# Hyperbolic Node Run Guide by YourFirstCrypto

- For PC you have to Download WSL ( check out any video of Installing WSL )
- For Mobile You have to Downlaod a New App
- Download this App: https://play.google.com/store/apps/details?id=tech.ula&pli=1

# Create your Hyperbolic Dashboard
https://app.hyperbolic.xyz/

- Sign up using Gmail and verify Your Number
- You will get 1$ to use in Hyperbolic


- Follow these Steps to Run Your Node
  
# Download Dependencies 
```
sudo apt update && sudo apt upgrade -y
```
```
sudo apt install git screen python3
```
```
sudo apt install python3.10-venv
```
```
sudo apt install nano
```
---

# Download Node Files
```
git clone https://github.com/0xmoei/chatbot-app.git
```
```
cd chatbot-app
```
---

# Python
```
python3 -m venv venv
```
```
source venv/bin/activate
```
---

## Install Configuration Files
```
pip install requests
```
---

# Connect Node With Your Hyperbolic dashboard using API

```
nano chatbot.py
```
- Open Hyperbolic dashboard & Go to setting and Copy Your API key
- PASTE YOUR API KEY here "YOUR_API_KEY_HERE" 
- Then Click CTRL button + X to Save Then Press Y
- Then Hit Enter

# Now Run your Node
```
python3 chatbot.py
```
---

# Next Day to Start Your Node Paste These Commands 👇
```
cd chatbot-app
```
```
python3 -m venv venv
```
```
source venv/bin/activate
```
```
python3 chatbot.py
```

