# SkyHack
![SkyHack Image](https://github.com/user-attachments/assets/67d69af9-3060-41e1-8c8f-804047775a23)


## Description
BlueSky is an advanced Python-based brute force program specifically designed for educational purposes only. This powerful tool allows users to perform various actions on the BlueSky platform.

The BlueSky brute force tool is built using a combination of Python scripts and JSON files to store and manage data. The tool's architecture is designed to be modular, allowing users to easily modify and extend its functionality. 

By using the BlueSky brute force tool, users can gain a deeper understanding of the importance of security and the potential consequences of weak passwords. However, it is essential to use this tool responsibly and within the bounds of the law.

## Installation
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

## Customizing User Agent Settings
By default, the BlueSky brute force tool uses a default user agent string to interact with the BlueSky API. However, users can customize this setting by modifying the Useragent.json file. To do so, follow these steps:
1. Open the `Useragent.json` file in a text editor, such as `nano` or `vim`, in the Termux terminal.
2. Locate the `"COMMENT"` section and modify the `"TYPE"` field to choose between `SINGLE` or `RANDOM` user agent settings.

```json
{
    "TYPE": "RANDOM",
}
```
By customizing the user agent, users can change the behavior of the tool and potentially avoid detection by the BlueSky API. However, it is important to use this feature responsibly and within legal limits.

## Error Handling
- If you experience issues with login or token validation, you can try to change the BlueSky token and make sure the token is correct!
- If you encounter any errors while hacking, you can just ignore them, we found that if you still need airplane mode then the hack runs smoothly!
- If you don't get results, this is because the target is not good enough or has a password that is difficult to guess. Maybe you chose the wrong password list!
- If you encounter issues with dumping IDs, you can make sure the target has a lot of followers/following and make sure the username is correct!

## Screenshot
![BlueSky](https://github.com/user-attachments/assets/6c5a92a0-6e58-4dea-8876-2052496d8747)

## Disclaimer
This tool is for educational purposes only and should not be used to harm or exploit others. Using this tool to brute force or hack into someone's account without their consent is illegal and unethical. Be cautious when using this tool, as it may cause harm to your own account or others. The author of this tool is not responsible for any misuse or harm caused by this tool. Use at your own risk.

I hope this description provides more detail about the BlueSky brute force tool! Let me know if you have any further requests.
