# **Node JS Rest-API**

<img src="#" width="500">

Simple Rest-API With Login System, Built using MongoDB, Express.js, and Node.js

Demo App:
Full App:

# Installation

Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [VS Code](https://code.visualstudio.com/download) or Any Text Editor

## Cloning this repo
```cmd
> git clone https://github.com/DrkBotBase/dylan-rest.git
> cd dylan-rest
```
Use `code .` to open file in VS Code
```cmd
> code .
```

## Editing the file
Edit the required value in folder `lib` file `settings.js`.

```js
module.exports = {
    port: '5000',
    limitCount: 0,
    recaptcha_key_1: '',
    recaptcha_key_2: '',
    // ex Mongodb Atlas : mongodb+srv:/xxx
    dbURI: ''
};
```

`port`: PORT localhost.

`recaptcha_key_1`: reCaptcha Key.

`recaptcha_key_2`: reCaptcha Key.

`dbURI`: Connection String MongoDb. 

## How to Get recaptcha_key

Contact Me ([WhatsApp](https://api.whatsapp.com/send/?phone=573508770421&text&app_absent=0)) How to get Recaptcha Key

## How to Get Mongodb URI
1. Sign In [Mongodb](https://www.mongodb.com/)
2. Create a Database.
<img src="https://i.postimg.cc/R0D16X3C/1.png" width="300">

3. Create Free Cluster.
4. Choose Cloud Provider & Region, Create Cluster.
5. Select `Connect`.
6. Add a Connection IP Address.
<img src="https://i.postimg.cc/gk1H2MZY/5-1.png" width="500">

7. Create a Database User
<img src="https://i.postimg.cc/T1zCLGPc/5-2.png" width="500">

8. Connect Your Application
9. Change `<password>` with Your Password Database User `step 7`
<img src="https://i.postimg.cc/6pW4wgW2/db.png" width="500">
10. Copy and Paste in `settings.js`

Contact Me ([WhatsApp](https://api.whatsapp.com/send/?phone=573508770421&text&app_absent=0)) if You Have Problem with mongodb

## Installing the dependencies
```cmd
> npm install
```

## Running App
```cmd
> npm start
```

Then Browse http://localhost:5000 . You will see the Homepage.

<img src="#" width="500">

# Features

|     API              |  EndPoint       |  Query           |
| :--------------:     | :------------:  | :------------:   |
| Youtube MP3          |  /ytmp3?url=    |  url & apikey    |
| Youtube MP4          |  /ytmp4?url=    |  url & apikey    |
| Youtube Play         |  /ytplay?query= |  query & apikey  |
| Random Quotes        |  /quotes        |  apikey          |
| Random Fakta         |  /fakta         |  apikey          |
| Random Kata Bijak    |  /bijak         |  apikey          |
| Random Kata Motivasi |  /motivasi      |  apikey          |
| Random Ptl           |  /ptl           |  apikey          |
| Cak Lontong          |  /caklontong    |  apikey          |

If you want to unlock Premium Feature, please contact me ([WhatsApp](https://api.whatsapp.com/send/?phone=573508770421&text&app_absent=0))

|     Premium               |  Availability  |
| :--------------:          | :------------: |
| Premium User              |   ✔️           |
| Added Premium Apikey      |   ✔️           |
| Delete Premium Apikey     |   ✔️           |
| Limit Apikey              |   ✔️           |
| Custom Limit Apikey       |   ✔️           |
| Custom Apikey             |   ✔️           |
| Expired Premium User      |   ✔️           |
| Reset All Limit every day 8am |   ✔️           |
| Reset One Limit           |   ✔️           |

# Deploy Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/DrkBotBase/dylan-rest)