# GiveawayBot™
[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)

## Repository Statics
<p align="center"><a href="https://github.com/GarudaProjects/Giveaways"><img src="https://github-readme-stats.vercel.app/api/pin?username=GarudaProjects&show_icons=true&theme=dracula&hide_border=true&repo=Giveaways"></a></p>
<p align="center">
### A Discord Giveaway bot written in Discord.js to create & enjoy Feature rich and Seamless Giveaways within your very own Discord guild!

# Contributions

All contributions are welcomed, it is recommended to create an issue or reply in a comment of an existing issue to let us know what you are working on first, that way we do not overwrite each other.

- Please read [contributing guide](.github/CONTRIBUTING.md) for details on this project.
- Please respect the [pull request template](.github/PULL_REQUEST_TEMPLATE/pull_request_template.md) while submiting a pull request.

### Step 1: Install the Dependencies:
Linux 
```sh
apt install nodejs npm -y
curl -sL https://deb.nodesource.com/setup_16.x -o nodesource_setup.sh
chmod 777 nodesource_setup.sh
./nodesource_setup.sh
apt install nodejs -y
npm install

```
Windows 
```sh
# https://nodejs.org/en/blog/release/v16.0.0/ get node.js
npm install 
```

### Step 2: Obtain a Bot Token From [Here](https://discord.com/developers) <br> <br>
<kbd>
</kbd>
<b>
  

### Step 3 : Replace the Token in [config.json](https://github.com/GarudaProjects/Giveaways) <br>
#### That's all! We Are Done! Now Simply host the Bot!

### Run with node
```sh
node index.js
```
### Run with pm2
```sh
npm install -g pm2@latest
pm2 start --name "Giveaway" index.js --watch
```

# Features
## Featuring | Slash Commands 
<kbd>
  <img src="https://raw.githubusercontent.com/GarudaProjects/Giveaways/main/.image/IMG_20211227_185024.jpg">
</kbd>
<b>
  
### Interactive Giveaway Creation
  
  <kbd>
  <img src="https://zerosnap.000webhostapp.com/mig6cvt0.gif">
</kbd>
<b>
  
### Featured ✨ Bonus Entries 
<kbd>
  <img src="https://zerosnap.000webhostapp.com/8eblx4sc.gif">
</kbd>
<b>

  
### And Lots More!
- Direct message when the server mentioned for joining is not joined
- Direct message when the server mentioned for joining is joined 
- Direct Message When User Reacts on an ended giveaway
- Direct Message User On Removing Reaction
- Direct Message Winner On Winning
