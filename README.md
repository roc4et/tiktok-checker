# TikTok Checker
<img src="https://img.shields.io/github/issues/7z-henry/tiktok-checker" alt="open_errors"></a> 
<img src="https://img.shields.io/github/watchers/7z-henry/tiktok-checker?style=social" alt="watchers"></a> 
<img src="https://img.shields.io/github/stars/7z-henry?style=social" alt="stars"></a> 
<img src="https://img.shields.io/github/forks/7z-henry/tiktok-checker?style=social" alt="open_errors"></a> 

A Tool that checks if TikTok 4l or 4c are still available.\
It will send all available usernames to a Webhook on your Discord Server.
##

![App Screenshot](https://cdn.upload.systems/uploads/qBaV3WVY.png)


## Installation
You need Python 3.8 or higher.\
Download Python from <a href="https://www.python.org/downloads/">here</a>.
```bash
pip install -r req.txt
```
    
## Usage
Open a new terminal in the folder and run:
```javascript
py main.py
```
## Known error
```
Traceback (most recent call last):
  File "C:\path\to\file\main.py", line 113, in <module>
    threading.Thread(target=Check()).start
  File "C:\path\to\file\main.py", line 58, in Check
    r = requests.get(f'https://www.tiktok.com/@{username}', proxies={"http": 'http://' + random.choice(proxies)})
  File "C:\Users\henry\AppData\Local\Programs\Python\Python310\lib\random.py", line 378, in choice
    return seq[self._randbelow(len(seq))]
IndexError: list index out of range
```
Just rerun the file.
## Support

Please give me a 🌟 and follow me to miss nothing :)\
Join my Discord at https://discord.gg/JepCwnawUj


## License
I am not responsible for your actions using this script.
