[![Build Status](https://travis-ci.org/gdg-southafrica/hoverboard.svg?branch=master)](https://travis-ci.org/gdg-southafrica/hoverboard)

This README is specific to the DevFest South Africa fork. Find the upstream _hoverboard_ README.md [here](https://github.com/gdg-x/hoverboard/blob/master/README.md)

# Blog posts, team
We are maintaining blog posts and team members purely in Cloud Firestore. See collections `blog` and `team`. 

# The other stuff? 
Most of the other important things are configured and deployed from `data/resources.json`. 

# Disable apply to speak
Once the Call For Papers is concluded we should disable the apply to speak button. See https://github.com/gdg-southafrica/hoverboard/commit/3f4be12045e6c256e5d68bee134d4f7e475fdf43

# Dev environment and branches 
Please dev in your own fork and file a PR. If you're fairly confident, gladly merge to `master` and let Travis deploy to Firebase. But gladly assign a team member for code review while filing your pull request. 

We're not maintaining a dev environment as a team. Test locally or in a personal Firebase project. 

# Travis integration
Travis will deploy every change in master. See status image at the top of the README. 

# Manual Deploy
The easiest will most likely using Docker, see [docs/tutorials/05-docker.md](docs/tutorials/05-docker.md). Otherwise [README.md here](https://github.com/gdg-x/hoverboard/blob/master/README.md)
