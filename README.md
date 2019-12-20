# free-agario-bots
Free open source agar.io facebook bots, normal and proxy version!

## Change Log
New version - v2.0.0
* Bypass recaptcha v3
* Updated FB files
* New vanila userscript - potion hack

## Discord
1. [EcoBits](https://discord.gg/AYF2pjY)
2. [EcoBits Web](http://ecobits.rf.gd/)

## Usage
1. [How to get Facebook Token](https://www.youtube.com/watch?v=Sjtb_OHP2tE)

1. VPS TUTORIAL
2. Run `sudo apt install git` command
3. Run `git clone https://github.com/EcoBits-max/EcoBits.git` command
4. Run `cd EcoBits` command
5. Run `sudo chmod +x install.sh` command
6. Run `sudo ./install.sh` command
7. Run `node server` command and leave the process running
8. Follow the same steps explained on `Windows` section for installing userscript in Tampermonkey and put your VPS IP on SERVER HOST input in the OPTIONS panel
9. Go to [agar.io](https://agar.io) and click "Connect" button
10. On top right of your browser you will see a shield with a red mark, click there and then click "Load unsafe scripts"
11. After agar.io loads click "Connect" button again, the status should say "Connected" in green
12. Create party and make sure that you are logged in on your account agar.io account then click "Start Bots" button, if the VPS IP doesn't has captcha the button should turn red and say "Stop Bots" if you get an alert saying the IP has captcha you will need to change the VPS IP somehow to one without captcha
13. To stop bots click the "Stop Bots" button and wait 30 seconds for process to close you will see a countdown there
14. To run the bots again just run `node server`, make sure you "Load unsafe scripts", click "Connect" button and then click "Start Bots" button if you did everything right bots should start again
15. Always make sure you wait the 30 seconds for process to close or you are gonna get captcha on the VPS ip
16. If you wanna run it 24/7 on the VPS run `sudo npm i -g pm2` command and then run `sudo pm2 start process.js` command


## Captcha (only for Windows)
If you get captcha alert you need to change your IP or get rid of captcha by playing with your IP. You can do so by:
- Restarting your router (only if you have a dynamic IP)
- Connecting to a VPN server like one from [ProtonVPN](https://protonvpn.com) which you make sure that doesn't has captcha
- Playing logged out of your agar.io account until captcha goes away
