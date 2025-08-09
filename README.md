# SkyHacks - Nightmare BlueSky Account Annihilator 😈💀

![SkyHack Logo](https://github.com/user-attachments/assets/8aa55ed2-3f3a-4bb6-9cee-d2afeb44fcbc)

**SkyHack** is a Python-forged cyber phantom, designed to relentlessly probe BlueSky account vulnerabilities with ruthless precision for ethical hacking purposes. Unleashed in 2024, it wields AI-driven brute force attacks and advanced data extraction, harvesting critical user data like usernames and follower lists for meticulous analysis. Trusted by thousands worldwide, SkyHack evolves ceaselessly, sharpening its edge against weak passwords. Built for modularity, it empowers ethical hackers to customize tests, exposing digital frailties. Only the bold and responsible may wield this tool, as its power demands strict adherence to legal boundaries.

> **Disclaimer:** SkyHack is exclusively for lawful, ethical security testing. Unauthorized use invites severe consequences. Wield it wisely to fortify digital defenses.

## ✨ Features

SkyHack offers a sleek interface for novices, slicing BlueSky’s search results, followers, and followings to extract data for export. Its brute force engine logs breaches with pre-set configs, while `Useragent.json` toggles Single or Random settings for stealth. Future updates will target hashtags and explore pages. All features are crafted for ethical use to expose password weaknesses.

## 🛠️ Installation

- **Linux - [Termux](https://drive.google.com/file/d/1dHqQe_WNWVp0qXTRPqYId_J3YVJ6taHr/view?usp=sharing)**
  
  ```
  $ pkg update -y && pkg upgrade -y
  $ pkg install git python-pip
  $ git clone --depth 1 https://github.com/RozhakDev/SkyHack.git
  $ cd "SkyHack"
  $ python -m pip install -r requirements.txt
  $ chmod +x Run
  $ ./Run
  ```

- **Running on Termux**
  
  ```
  $ cd "$HOME/SkyHack"
  $ ./Run
  ```

## ⚙️ Customizing User-Agent Settings

You can modify the user-agent behavior by editing the `Useragent.json` file.

1. Open the file with a text editor (e.g., `nano` or `vim`):
   
   ```
   nano Useragent.json
   ```

2. Change the `TYPE` value to:
   
   - `RANDOM`: Rotate between multiple user-agents.
   - `SINGLE`: Use a single user-agent.

Example:

```json
{
    "TYPE": "RANDOM"
}
```

## 📸 Screenshots

![FunPic_20250107](https://github.com/user-attachments/assets/6df2676b-1d2e-4b92-adcd-2339526e32a8)

## 🛡️ Error Handling & Tips

SkyHack demands precision. Invalid tokens trigger login failures—verify or replace your BlueSky token. Airplane mode can bypass errors during attacks. Poor results may stem from unsuitable targets or weak wordlists. For ID dumping issues, ensure the target has ample followers and a correct username.

## 🚨 Disclaimer

SkyHack exists solely for educational and ethical research. Any misuse is a betrayal of its purpose and a violation of law. The creators renounce all liability for harm caused by reckless or illegal use. Wield this tool with honor, or face the consequences.

## 📜 License

SkyHack is not open source. Access is restricted to authorized users for ethical testing only. Unauthorized modification or distribution is forbidden, and violators will face the full weight of the law. Consult the [LICENSE](LICENSE) file for details.
