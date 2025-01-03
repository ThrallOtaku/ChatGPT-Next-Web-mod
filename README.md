<h1 align="center">ChatGPT-Next-Web-mod    based   on ChatGPT-Next-Web</h1>

##To deploy the mod

```shell
git clone https://github.com/ThrallOtaku/ChatGPT-Next-Web-mod.git 
cd ChatGPT-Next-Web-mod
yarn install 
yarn build 
PORT=8080 pm2 start npm --name "chatgpt-next-web" -- start
```

enjoy  chatting
