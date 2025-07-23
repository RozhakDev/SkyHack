# SkyHacks - Nightmare BlueSky Account Annihilator 😈💀
![SkyHack Logo](https://github.com/user-attachments/assets/8aa55ed2-3f3a-4bb6-9cee-d2afeb44fcbc)

**SkyHack** is a terrifyingly potent, Python-based brute force tool ⚙️🕸️ crafted for educational purposes only. It showcases the catastrophic risks of weak passwords through relentless AI-driven attacks 🤖💥. Designed with modularity, it allows easy customization for ethical hacking experiments.

> ⚠️ **Disclaimer:** This tool is strictly for ethical and legal use. Unauthorized access or misuse will unleash dire consequences. 🚨🔒

## ✨ Features
SkyHacks delivers a sinister user-friendly interface for beginners, extracting data from BlueSky search results, followers, and followings with ruthless precision 🔍. Upcoming updates will rip data from hashtags and explore pages. It unleashes brutal hacking with pre-set configs, logging successful attacks and checkpoints for chilling insights 🔑. Customize the horror with Useragent.json, toggling between `Single` or `Random` user-agent settings for advanced terror 🛠️. All features scream ethical use to expose password vulnerabilities.

## 🛠️ Installation
- **Linux - [Termux](https://drive.google.com/file/d/1dHqQe_WNWVp0qXTRPqYId_J3YVJ6taHr/view?usp=sharing)**

  ```
  $ pkg update -y && pkg upgrade -y
  $ pkg install git python-pip
  $ git clone https://github.com/RozhakXD/SkyHack
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
- If you experience issues with login or token validation, try changing the BlueSky token and ensure that the token is correct! 🔑
- If you encounter any errors while hacking, you can simply ignore them; we found that enabling airplane mode allows the hack to run smoothly! ✈️
- If you don't get results, it may be because the target is not suitable or has a difficult-to-guess password. You might have chosen the wrong password list! ❌
- If you encounter issues with dumping IDs, ensure that the target has a substantial number of followers/following and that the username is correct! 📊

## 🚨 Disclaimer
This tool is for educational and research purposes only. Misuse of this tool is illegal and unethical. The developers are not responsible for any harm caused by its use. Use responsibly and within the law.

📜 License
This project is not open source. Access and usage rights are strictly reserved for authorized users only. Unauthorized distribution or modification is prohibited. See the `LICENSE` file for more details.
