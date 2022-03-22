# ⭕ Captcha Bypassing Lab ⭕

If you want to try Captcha Bypassing, you can practice it with my [auto-captcha](https://github.com/D3Ext/PentestDictionary/blob/main/Captcha-Bypassing/auto-captcha.sh) script, it generates automatically 
an http-server (apache2) with a simple but efective captcha. 

You can bypass the captcha with just 2 requirements:

- [python3](https://www.python.org/) **(for sending the requests and using tesseract)**
- [tesseract](https://github.com/tesseract-ocr/tesseract) **(a python3 module for converting an image to text)**

## ⭕ Installation:
Execute the script as root or with sudo for installing automatically the captcha:

    wget "https://github.com/D3Ext/PentestDictionary/blob/main/Captcha-Bypassing/auto-captcha.sh" ; chmod +x auto-captcha.sh ; ./auto-captcha.sh
    
## ⭕ Demo:

<img src="">

You can learn more about captchas [here](https://www.anura.io/blog/captcha-and-recaptcha-how-fraudsters-bypass-it) and [here](https://book.hacktricks.xyz/pentesting-web/captcha-bypass)

⚪ *Created by ***D3Ext****
