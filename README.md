# slack-emojis-essentials
To be used in conjunction with https://github.com/lambtron/emojipacks/
The all.yaml file here uploads all the packs listed on https://github.com/lambtron/emojipacks/tree/master/packs
The essentials.yaml file here uploads about 100 extra emojis of my own devising.

## Two files for all the slack emojis and then some?
I always use https://github.com/lambtron/emojipacks/ when i start a new slack channel but uploading each pack individually is a real pain in the tuchus.  So I use this all.yaml file here to just upload them all at once.  "At once" is optimistic - this takes maybe 20 or 40 minutes on decent internet (60 mbps).  After that i essentials.yaml file to add extra emojis that I absolutely cannot do without.  Actually last time i tried i had trouble using the essentials file and uploaded them individually.  But i shall include that here for now untested to try again soon.

## Instructions
```
git clone https://github.com/mcdermottsolutions/slack-emojis-essentials.git
git clone https://github.com/lambtron/emojipacks.git
cp slack-emojis-essentials/all.yaml emojipacks/packs
cp slack-emojis-essentials/essentials.yaml emojipacks/packs
cd emojipacks
```
`sudo make` or you may be able to just do `make`
```
emojipacks
```
It'll ask you a few questions:
```
Slack subdomain: 20percentclub
Email address login: andyjiang@gmail.com
Password: *********
Path or URL of Emoji yaml file: ./packs/all.yaml
```
This will take *forever* - maybe 20 or 40 minutes on decent internet (60 mbps)
```
emojipacks
```
It'll once again ask you the above questions.
This time for the yaml file use essentials.yaml
```
Path or URL of Emoji yaml file: ./packs/essentials.yaml
```

Enjoy!
Let me know if it gives you any problems or anything! 😎
