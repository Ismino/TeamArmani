![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome Ismino,

This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. It's perfectly ok to use this template as the basis for your project submissions.

You can safely delete this README.md file, or change it for your own project. Please do read it at least once, though! It contains some important information about Gitpod and the extensions we use. Some of this information has been updated since the video content was created. The last update to this file was: **September 1, 2021**

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!

## Features 
The Team Petra & Armani webpage is a page for professional use who need a therapy dog. The user's can be school's and hospital's, even retirement home's. The website provides a contact to a service dog and he's owner/leader. The user can also read a little bit about what a social service dog is and what his working with.
### Existing Features

- __Navigation bar__

  - The navigation bar makes the site easy to go throught. 
  - The navigation bar is also simple and elegant styled so that the user easy can read.

![Navigation](style/image/navbar.png)

- __The landing page image__

  - A picture of the social service dog that the team provides.

![Landing Page](style/image/shortone.png)
- __Short intro section__

  - This section helps the user get a clue of what's comming.
  
![Shortone](style/image/.png)

- __What is a social service dog section__

  - This section helps the user understand what's an social service dog is and about the history of it.
  
![What](style/image/what.png)

- __The Footer__ 

  - This section contains a link to the instagram acount of Team Petra & Armani.
![Footer](.png)

- __About us page__

  - About us is a page where the user's read all about the Team Petra & Armani.
  

![]()

- __Contact Page__

  - The side contains a contact fill in where the user can leave a message to the team leader.

![]()

## Testing 

- I tested the site with lighthouse both for mobile phones and for desktops and the result got very great. It works really great one both smartphones and desktops.
- I also tested to use the site on a smartphone and a desktop and a bigger screen desktop.I found it easy to use on all direrent screens.

### Validator tesing 

- There where to small things that came up in the validator testing on w3c html testing. Thhe first is that the img dont have an alt atribute and the secound is that the image dont have an heading. [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fismino.github.io%2FTeamArmani%2F)
- Testing trought the jigsaw css validator testing the program did'nt found any errors.[jigsaw validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fismino.github.io%2FTeamArmani%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv)

### Unfixed bugs
- the only bug that I have is that the hero picture is bigger than it's sized and it's makes the picture a little bit compressed.

## Deployment 
- To deploy my project I want to github and to the teamArmani repositry, from there i went to settings and to pages. 
- From pages I deployed my site to main branches and it went online.

https://ismino.github.io/TeamArmani/

## Credits
I've got stuck with the hero picture where i got help from student tutoring, they helped me understand how to put the picture but at the and I changed it all anyway. I also had an issue with the padding that my mentor helped me out with. The pictures are from my mother Petra Cigel and it's her dog. To the media section i googled how to make it and then i tested different things.

## Content
- The text for the pages where written by my mother who has a certificate in ocial service's dog's.
- The pictures was taken by my sister and sent to me from my mother.
- The icons was taken from font awsome. [font awsome](https://fontawesome.com/)
- For making my contact fill in i looked at basic form functions on w3cschool.


