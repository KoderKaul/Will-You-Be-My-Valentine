# 💘 Will You Be My Valentine? 

A cute, interactive web page to ask your special someone to be your Valentine. 

The "No" button runs away when they try to click it, ensuring a 100% success rate. 😉

## ✨ Features
* **Mobile & Desktop Friendly:** Works with mouse hover (desktop) and touch (mobile).
* **The "Unclickable" Button:** The "No" button dodges the cursor/finger using random viewport coordinates.
* **Instant Success State:** Clicking "Yes" swaps the GIF and text immediately without reloading.
* **Single File:** Zero dependencies. Just one `hehe.html` file.

## 🚀 How to Run Locally

### Prerequisites
* A web browser
* Python (optional, for local hosting)

### Method 1: The "Double Click" (Simplest)
Just double-click `hehe.html` to open it in your browser.

### Method 2: Local Network (For testing on Phone)
If you want to test it on your phone over Wi-Fi, run a simple Python server in the project directory:

```bash
# Python 3
python3 -m http.server 8000
```
Then access it via your local IP: `http://<YOUR_LOCAL_IP>:8000/hehe.html`

Use `ifconfig | grep "inet " | grep -v 127.0.0.1` on Mac for finding the local IP(it will be left to "netmask")

### 🌐 Hosting for your Partner
Since you probably want to send this as a link, here are the best ways to host it:

#### Option A: GitHub Pages (Permanent & Free)
- Upload `hehe.html` to a public GitHub repository.
- Go to `Settings > Pages`.
- Select the main branch as the source.
- Send the generated link to your partner!

#### Option B: Ngrok (Temporary & Secure)
- Great for a surprise "right now" link without deploying.
- Start your local Python server (python3 -m http.server 8000).

Run Ngrok:

```Bash
ngrok http 8000
Send the https://....ngrok-free.app link.
```

### 📄 License
MIT License. Feel free to use, modify, and spread the love!
