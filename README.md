# SkyHack Toolkit: Ethical Security for BlueSky 🌐🔒
![SkyHack Logo](https://github.com/user-attachments/assets/1b40d32f-1f5e-45d6-810e-eb704adb3c7b)

SkyHack is a powerful, Python-based brute force tool designed for educational purposes only. It offers a range of features to demonstrate the vulnerabilities of weak passwords and the importance of strong security measures. Built with modularity in mind, it allows for easy customization and extension.

> ⚠️ **Disclaimer**: This tool is intended solely for ethical and legal purposes. Unauthorized use may lead to severe consequences.

## ✨ Features
SkyHack is designed with user accessibility in mind, making it easy for beginners to navigate its functionalities. Users can retrieve valuable information by extracting data from search results, followers, and followings lists. Upcoming features will also allow data extraction from hashtags and explore pages. 🔍

In addition to data retrieval, SkyHack offers robust hacking functionalities. Users can initiate hacking processes with pre-set configurations for quick and efficient actions. The tool provides logs of successful hacking attempts and checkpoint results, enhancing users' understanding of effective tool usage. 🔑

SkyHack also features customizable settings, allowing users to personalize their experience by modifying the Useragent.json file. They can switch between `Single` or `Random` user-agent settings for advanced usage. 🛠️ These features collectively aim to enhance understanding of password vulnerabilities while promoting ethical usage.

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

## 📜 License
This project is licensed under the MIT License. See the `LICENSE` file for more information.
