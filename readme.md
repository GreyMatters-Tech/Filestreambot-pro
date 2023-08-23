<h1 align="center"></h1>
<p align="center"> 
  <img src="https://socialify.git.ci/adarsh-goel/filestreambot-pro/image?description=1&descriptionEditable=A%20very%20fast%20file%20streaming%20bot%20used%20for%20streaming%20and%20downloading%20movies&font=Source%20Code%20Pro&forks=1&issues=1&language=1&logo=https%3A%2F%2Fuser-images.githubusercontent.com%2F88939380%2F137127129-a86fc939-2931-4c66-b6f6-b57711a9eab7.png&owner=1&pattern=Circuit%20Board&pulls=1&stargazers=1&theme=Dark" alt="Cover Image" width="650">
  </a>
  
 <p align="center">
    A Telegram bot to turn all media and documents files to instant direct download and stream link .
    <br />
   </strong></a>
    <br />
    <a href="https://github.com/adarsh-goel/pro/issues">Report a Bug</a>
    |
    <a href="https://github.com/adarsh-goel/filestreambot-pro/issues">Request Feature</a>
  </p>


<hr>

## Please Follow me so you know whenever I release a new Project!❤️‍🔥
## [Tutorial Video](https://youtu.be/u773hq1tGiA)
## 🍁 About This Bot :

![streamingfilestreambot-professional-live_1](https://user-images.githubusercontent.com/88939380/137127129-a86fc939-2931-4c66-b6f6-b57711a9eab7.png)

</p>
<p align='center'>
    This bot will give you stream links for Telegram files without the need of waiting till the download completes
</p>


## ♢ How to make your own :


#### ♢ Click on This Drop-down and get more details
<br>
<details>
  <summary><b>Deploy on Heroku:</b></summary>


1. Fork This Repo
2. Click on the button to Deploy and follow steps

<h4> So Follow Above Steps 👆 and then deploy other wise bot won't work</h4>

Press the below button to Fast deploy on Heroku/Raiwlay
Either you could locally host or deploy on [Heroku](https://heroku.com)
### 💜 Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy/)

<br>


then goto the <a href="#mandatory-vars">variables tab</a> for more info on setting up environmental variables. </details>

<details>
  <summary><b>Features:</b></summary>
  
<p>

🚀Features<p>
💥Superfast⚡️ download and stream links.<br>
💥No ads in generated links.<br>
💥Superfast interface.<br>
💥Along with the links you also get file information like name,size ,etc.<br>
💥Updates channel Support.<br>
💥Mongodb database support for broadcasting.<br>
💥Password Protection.<br>
💥User Freindly Interface.<br>
💥Ping check.<br>
💥User DC Check.<br>
💥Real time CPU , RAM , Internet usage. <br>
💥Custom Domain support. <br>
💥All unwanted code removed. <br>
💥A lot more tired of writing check out by deploying it. 
</details>
<details>
  <summary><b>Host it on VPS Locally :</b></summary>


```py
apt install git
apt install python3-pip
git clone https://github.com/Filmyrohesh/Filestreambot-pro/tree/main-3/Filestreambot-pro
cd Filestreambot-pro
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
nohup python3 -m Adarsh &
```

and to stop the whole bot,
 do <kbd>CTRL</kbd>+<kbd>C</kbd>

Setting up things

If you're on Heroku, just add these in the Environmental Variables
or if you're Locally hosting, create a file named `config.env` in the root directory and add all the variables there.
An example of `config.env` file:

```py
API_ID=12345
API_HASH=esx576f8738x883f3sfzx83
BOT_TOKEN=55838383:yourtbottokenhere
BIN_CHANNEL=-100
PORT=8080
FQDN=your_server_ip
OWNER_ID=your_user_id
DATABASE_URL=mongodb_uri
```
  </details>

<details>
  <summary><b>Vars and Details :</b></summary>

`API_ID` : Goto [my.telegram.org](https://my.telegram.org) to obtain this.

`API_HASH` : Goto [my.telegram.org](https://my.telegram.org) to obtain this.
  
`MY_PASS` : Bot PASSWORD

`BOT_TOKEN` : Get the bot token from [@BotFather](https://telegram.dog/BotFather)

`BIN_CHANNEL` : Create a new channel (private/public), add [@missrose_bot](https://telegram.dog/MissRose_bot) as admin to the channel and type /id. Now copy paste the ID into this field.
  
`OWNER_USERNAME` : U should be knowing it afterall it's your username dont remember it? just go to settings!

`OWNER_ID` : Your Telegram User ID

`DATABASE_URL` : MongoDB URI for saving User IDs when they first Start the Bot. We will use that for Broadcasting to them. I will try to add more features related with Database. If you need help to get the URI you can click on logo below!

[![mongo](https://telegra.ph/file/fd68906852c71fdd68bef.jpg)](https://www.youtube.com/watch?v=HhHzCfrqsoE)

 Option Vars

`UPDATES_CHANNEL` : Put a Public Channel Username, so every user have to Join that channel to use the bot. Must add bot to channel as Admin to work properly.

`BANNED_CHANNELS` : Put IDs of Banned Channels where bot will not work. You can add multiple IDs & separate with <kbd>Space</kbd>.

`SLEEP_THRESHOLD` : Set a sleep threshold for flood wait exceptions happening globally in this telegram bot instance, below which any request that raises a flood wait will be automatically invoked again after sleeping for the required amount of time. Flood wait exceptions requiring higher waiting times will be raised. Defaults to 60 seconds.

`WORKERS` : Number of maximum concurrent workers for handling incoming updates. Defaults to `3`

`PORT` : The port that you want your webapp to be listened to. Defaults to `8080`

`WEB_SERVER_BIND_ADDRESS` : Your server bind adress. Defauls to `0.0.0.0`

`NO_PORT` : If you don't want your port to be displayed. You should point your `PORT` to `80` (http) or `443` (https) for the links to work. Ignore this if you're on Heroku.

`FQDN` :  A Fully Qualified Domain Name if present. Defaults to `WEB_SERVER_BIND_ADDRESS` </details>

<details>
  <summary><b>How to Use :</b></summary>

:warning: **Before using the  bot, don't forget to add the bot to the `BIN_CHANNEL` as an Admin**
 
`/start` : To check if the bot is alive or not.

To get an instant stream link, just forward any media to the bot and boom, its fast af.
  
![image](https://user-images.githubusercontent.com/88939380/145798095-3cdad108-96b0-4391-a540-cad144d6b864.png)


### Channel Support
Bot also Supported with Channels. Just add bot Channel as Admin. If any new file comes in Channel it will edit it with **Get Download Link** Button. </details>

### Credits : 

- [Me](https://github.com/adarsh-goel)
- Everyone In This Journey !
