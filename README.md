# FUT Web App - TamperMonkey scripts

This is based off the super duper and awesome scripts originall created by [Mardaneus86](https://github.com/Mardaneus86/futwebapp-tampermonkey)!

FIFA 20's companion app for FIFA Ultimate Team, the FUT 20 Web App, is a website that let's you trade and manage your team on the go.

This TamperMonkey script is meant to enhance the FUT 20 Web App experience. You can install the script following the instructions below. Afterwards you will get a settings button on the bottom right of the web app, where you can enable every feature by itself. The script provides a certain degree of customization possibilities.

:warning: Using this script is at your own risk. EA might (temp-)ban you for altering parts of their Web App.
  - I do see alot of Auth errors come up and so far, its just a reauthenticate to esnure your not a robot
  - FUTBIn might error, thats because of the request to the site.  I found a quick proxy does a temp fix until it sorts itself out again

I contiuned on this project for the love of FIFA FUT but also lear more about Javascriptm jQuery and Webpack.

## Features
- [x] Futbin integration
  - [x] Show Futbin prices on all player cards throughout the app
  - [x] Show link to player on Futbin
  - [x] Mark bargains (BIN price lower then Futbin value)
- [x] Find minimum BIN value of players
  - [x] Price will Include 5% EA tax to ensure its cheaper
  - [x] Also a MIN Bid is added so you know how to place the MIN bid Safely
- [x] Refresh transfer list
- [x] Increase transfer list size
- [x] Extra card information (contracts, fitness)
- [x] Total coin value for cards on the transfer list

## Installation
Make sure you have user scripts enabled in your browser (these instructions refer to the latest versions of the browser):

* Firefox - install [Tampermonkey](https://tampermonkey.net/?ext=dhdg&browser=firefox). :warning: Has issues loading properly (see issue #115)
* Chrome - install [Tampermonkey](https://tampermonkey.net/?ext=dhdg&browser=chrome).
* Opera - install [Tampermonkey](https://tampermonkey.net/?ext=dhdg&browser=opera).
* Safari - install [Tampermonkey](https://tampermonkey.net/?ext=dhdg&browser=safari).
* Dolphin - install [Tampermonkey](https://tampermonkey.net/?ext=dhdg&browser=dolphin).
* UC Browser - install [Tampermonkey](https://tampermonkey.net/?ext=dhdg&browser=ucweb).

### Install scripts
Once Installed, Install the scripts via the latest version and release notes at the [releases page](https://github.com/darthvader666uk/futwebapp-tampermonkey/releases).  By Clicking the JS link, this shouldm auto add to Tampermonkey.

## Feature requests
If you feel there are missing features, feel free to add a request to the [issue list][issue-list]. Make sure to provide the necessary details, or even a mockup of what the feature would look like.

## Issues
File a bug report in the [issue list][issue-list].

## Developing
Clone this repository and execute:
```
npm install
```

To start the bundling process and linting process, execute:
```
npm run build
```

The output will be in the `dist` folder called `fut-enhancer.user.js`

<a href="https://www.buymeacoffee.com/darthvader666uk" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" ></a>
