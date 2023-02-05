# Quick Deploy Options!
[<img src="https://www.netlify.com/img/deploy/button.svg">](https://app.netlify.com/start/deploy?repository=https://github.com/math-study/gba-host)
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/math-study/gba-host)
[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/math-study/gba-host)
[![amplifybutton](https://oneclick.amplifyapp.com/button.svg)](https://console.aws.amazon.com/amplify/home#/deploy?repo=https://github.com/math-study/gba-host)


# GBA-Host!
This is a repository that is a backup of all of the Roms on the main GBA project. This currently includes: NES, SNES, GBA, and Sega Genesis (Mega Drive). 
This is a Backup Repo
# Creating a Fork!
If you are coming from our main GBA emulator page, this is a great way to link to the roms if you don't want to do much work. Assuming you just want to host from here, make sure you deploy this Repo with Github Pages. It should do this automatically, but check the `Actions` tab in the repository to check and see if it has ran or is running. You can also ensure it is going to be built by going to Settings --> Pages --> GitHub Pages. From here make sure the "Source" is set to `Deploy from a branch` and that you select `main` under "Branch" (or the branch you want). The folder should say `/ (root)`. If it looks good, ensure you press save.

## Once Deployed!
Once deployed, make sure the site is live by visiting index.html. In this case, our link is https://math-study.github.io/gba-host/index.html, but replace `math-study` with your username, and `gba-host` with the repo name, if changed. 

## Link to the roms!
If you saw a page load, good job! Everything is successful so far. Now you can start linking. Following instructions from [here](https://github.com/math-study/gba/blob/gh-pages/docs/UltimateGuide.md) link the games. Make sure to link properly, links from here are Case Sensitive! For example: https://math-study.github.io/gba-host/nes-alt/Mega_Man_2.nes.zip is the proper way to link Mega Man 2. Notice how the `M`'s are capitalized, and the file extension is also included (`.nes` is NOT the file extension in this case. It is `.zip` Remember to look at the entire file name and path.). 

# Notes!
Please note that this may take a long time to deploy. Like a really long time. GBA games alone make deployment 25 mins, and this include more consoles. 
If you choose to clone this repository locally for any reason, please note that the roms will take up about 7-8GBs of local storage. 
 
# Contributions! 
If you wish to help contribute, feel free to make a pull request! Try not to modify the folders included, as we may reject any additions not organized into a folder. As long as you create a new folder on the root, or create a folder inside the existing ones, we will happily take contributions!
