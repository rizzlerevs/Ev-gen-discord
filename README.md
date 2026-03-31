# 🚀 DISCORD TOKEN GENERATION TOOL (EVS-GEN)

A high-speed, secure Discord token generation tool with automated browser control and premium aesthetic.

---

## 🛠️ PREREQUISITES

Before running the tool, ensure you have the following installed on your Windows system:

### 1. 🌍 Brave Browser (CRITICAL)
This tool is optimized specifically for **Brave Browser**. 
- **Download:** [Brave Website](https://brave.com/)
- **Installation:** Install to the default directory (usually `C:\Program Files\BraveSoftware\Brave-Browser\Application\brave.exe`). 
- **Note:** The tool will automatically look for Brave in standard locations.
- Install [Python 3.10+](https://www.python.org/)
- Run: `pip install -r requirements.txt` (including `nodriver`, `tls_client`, `cryptography`, `pystyle`, `colorama`, `bs4`, `psutil`).

---

## 🔑 AUTHENTICATION & LICENSE KEYS

The tool requires a valid **Worker License Key** to authenticate with the backend before it starts generating tokens.

### How to get a Key:
1. Join the **Official Workers Server**.
2. Navigate to any general channel or the bot interaction channel.
3. Use the following slash command:
   ```bash
   /generate_key
   ```
4. The bot will respond with your unique license key (Format: `WORKER-XXXX-XXXX`).
5. **Copy the key** exactly as it appears.

---

## 🚀 HOW TO USE

1. **Launch the tool:**
   - Double-click `evs.exe`.
2. **Authentication:**
   - When prompted, paste your **License Key**.
   - The tool will verify the key with the Supabase backend.
   - Once verified, the key will be saved to `worker_key.txt` so you don't have to enter it again.
3. **Configuration:**
   - **Target Count:** Enter the number of accounts you want to generate (Enter `0` for unlimited).
   - **Proxy:** (Optional) Enter your proxy (Format: `ip:port:user:pass`). Leave blank for direct connection.
4. **Generation:**
   - The tool will launch a private Brave instance for each account.
   - It handles form filling, account creation, and **automatic token extraction**.
   - **Email Verification:** If Discord sends a verification email, the tool fetches the link automatically and opens it for you.
   - **Auto-Cleanup:** The browser window will automatically close after the account is secured.

---

## ⚠️ IMPORTANT NOTES


- **Cooldown:** There is a built-in **120s cooldown** between account generations to keep your IP/Proxy safe from Discord's rate limits.


