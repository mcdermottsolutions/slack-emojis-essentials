# slack-emojis-essentials
To be used in conjunction with https://github.com/lambtron/emojipacks/

The all.yaml file here uploads all 29 packs listed on https://github.com/lambtron/emojipacks/tree/master/packs to your slack channel and also uploads about 100 extra emojis that my friends & I have made.

## One file for all the slack emojis and then some?
I always use https://github.com/lambtron/emojipacks/ when i start a new slack channel but uploading each pack individually is a real pain in the tuchus.  So I use this all.yaml file here to just upload them all at once.  "At once" is optimistic - this takes maybe 20 or 40 minutes on decent internet (60 mbps).

## Instructions
```
git clone https://github.com/mcdermottsolutions/slack-emojis-essentials.git
git clone https://github.com/lambtron/emojipacks.git
cp slack-emojis-essentials/all.yaml emojipacks/packs
cp slack-emojis-essentials/essentials.yaml emojipacks/packs
cd emojipacks
sudo make
```
(you may be able to just do `make` instead of `sudo make`)

then type
```
emojipacks
```
It'll ask you a few questions:
```
Slack subdomain: ninjaslackhideout
Email address login: mrninja@gmail.com
Password: *********
Path or URL of Emoji yaml file: ./packs/all.yaml
```
This will take *forever* - maybe 20 or 40 minutes on decent internet (60 mbps)

Enjoy!
Let me know if it gives you any problems or anything! 😎
