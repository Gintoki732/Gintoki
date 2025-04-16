## For Termux/Ubuntu/SSH User

```bash
pkg update && pkg upgrade
pkg install git -y
pkg install nodejs-lts
pkg install ffmpeg -y
git clone https://github.com/xziyyy/clairity.git
cd clairity
npm install
```

[RECOMMENDED INSTALL ON TERMUX]
```bash
pkg install yarn
yarn
```

Run
```bash
npm start
```
Editing on Termux
```bash
npm install mc -y
mc
```

edit file in ./media/settings/config.js
```bash
global.botname = "Gintoki bot" // bot name
global.ownerNumber = [`${966553357953}`,'no2','no3'] // no owner can access all features
global.email = 'abdullah712767@gmail.com' // leave blank if you don't have one
global.web = '' // leave blank if you don't have one
global.location = 'Edo' // fill in your area or place of residence if you don't want to leave it blank
global.packname = '𖤐 G I N T O K I 𖤐' // wm on the sticker
global.author = 'جينتوكي عمك' // wm on the sticker
```

License: [MIT](https://choosealicense.com/licenses/mit/)
