# Slack Emojis Essentials
Upload about 1500 emojis to your slack channel relatively painlessly.

(To be used in conjunction with https://github.com/lambtron/emojipacks/)

The all.yaml file here uploads all 29 packs listed on https://github.com/lambtron/emojipacks/tree/master/packs to your slack channel and also uploads about 100 extra emojis that my friends & I have made.

## One .yaml file for all the slack emojis and then some?
I always use https://github.com/lambtron/emojipacks/ when i start a new slack channel but uploading each pack individually is a real pain in the tuchus.  So I use this all.yaml file here to just upload them all at once.  "At once" is optimistic - it takes about an hour on decent internet (60 mbps).  Using this one file eliminates the need to reenter your slack subdomain, email, password and yaml path every few minutes, 30 times in a row.

## Instructions
```
git clone https://github.com/mcdermottsolutions/slack-emojis-essentials.git
git clone https://github.com/lambtron/emojipacks.git
cp slack-emojis-essentials/all.yaml emojipacks/packs
cd emojipacks
sudo make
```
(you may be able to just do `make` instead of `sudo make`)

then type
```
emojipacks
```
It'll ask you a few questions (enter your own info for subdomain, email & password):
```
Slack subdomain: ninjaslackhideout
Email address login: mrninja@gmail.com
Password: *********
Path or URL of Emoji yaml file: ./packs/all.yaml
```
This will take *forever* - about an hour on decent internet (60 mbps)

Enjoy!
Let me know if it gives you any problems or anything! 😎
