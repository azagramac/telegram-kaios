<p align="center">
  <img src="https://github.com/AzagraMac/telegram-kaios/assets/571796/c40fca05-2b05-47ca-90e9-240940321d66" width="350" height="120" title="kaios"/>
  <img src="https://github.com/AzagraMac/telegram-kaios/assets/571796/b270abf1-1fbe-48db-aead-06c15ae25a10" width="100" height="100" title="telegram"/>
</p>

### Screenshots
![Captura desde 2024-04-19 17-21-15](https://github.com/AzagraMac/telegram-kaios/assets/571796/c4afe3d7-8c3d-479e-9d93-c97fb2984df7) ![Captura desde 2024-04-19 17-26-28](https://github.com/AzagraMac/telegram-kaios/assets/571796/bae216fb-f3a8-481b-b030-a55f2dcc1f15)



### Config 

Log in to your Telegram account via web from the following link (don't delete your Telegram account)
https://my.telegram.org/auth
![Captura desde 2024-04-19 17-46-39](https://github.com/AzagraMac/telegram-kaios/assets/571796/9b069194-bfe3-47a9-853e-73453428ce4c)

and select **API development tools**

![Captura desde 2024-04-19 17-45-56](https://github.com/AzagraMac/telegram-kaios/assets/571796/be12b31d-db33-496d-915e-5733ee2fc71a)

We need **YOUR_APP_ID** and **YOUR_APP_HASH** of our Telegram account, which we must put in the following files:

```
build/authenticationWebWorker.js
build/authorizedWebWorker.js
build/bundle.js
```

### Requirements

We need access to the development mode, if you don't have it press this code on the phone to enable it. 

```
*#*#33284#*#*
```

Or click on this [link](https://w2d.bananahackers.net/) from your KaiOS phone

### Download Kaiosrt, emulator
- https://developer.kaiostech.com/docs/getting-started/env-setup/simulator (Only for Linux)

### Install and run App
- https://developer.kaiostech.com/docs/getting-started/env-setup/simulator#install-and-run-the-app

### If it works
- Notifications push
- emojis in the conversation
- you can receive photos and audios, you have to download them beforehand.

### Known errors
- Attach photo to be able to send it does not work.
- The settings menu does not work either

