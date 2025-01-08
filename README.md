> original Repo [here](https://github.com/lynxbinz/CS-Beacon-Notifier).

# Cobalt Strike Beacon Notifier
A Cobalt Strike Beacon Notifier Via Telegram.

## Setup
```console
git clone https://github.com/vasco0x4/CS-Beacon-Notifier.git
cd CS-Beacon-Notifier
pip3 install requests
```

* Open the pyScript.py and replace with your Telegram Bot Token and Chat ID 
```python
def telegram_bot_msgSender(msg):
    teleBot_token = "xxxxxxxxx:xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
    teleBot_chatID = "xxxxxxxxxxxx"
```

> [Telegram Bot](https://telegram.me/BotFather).


* Now Load the script via Cobalt Strike Script Manager as show below
<p align="center">
    <img src="https://github.com/lynxbinz/CS-Beacon-Notifier/blob/main/images/load-cna-script.png" alt="Image" width="600" />
</p>



## Tested On
* Cobalt Strike 4.9.1


