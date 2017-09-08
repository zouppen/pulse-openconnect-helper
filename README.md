<!-- -*- mode: markdown; -*- -->
# Pulse-openconnect-helper

Browser script for connecting to Juniper Pulse Connect Secure VPN
using OpenConnect. Works even with the most hostile
two-factor-authentication schemes.

## How it works?

It's a user script installed to a browser which steals the session
cookie and shows the user a oneliner for connecting to that VPN using
open-source OpenConnect. No more shady Java applets.

![Screenshot](screenshot.png)

## Installation

1. Install OpenConnect 7.08 or newer. Run `sudo apt install
   openconnect` if you are using Debian or Ubuntu.
1. Install
   [Greasemonkey](https://addons.mozilla.org/fi/firefox/addon/greasemonkey/)
   for Firefox or
   [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   for Chrome/Chromium.
2. Click [pulse-openconnect.user.js](pulse-openconnect.user.js)
3. Click *Raw*
4. Click *Install*

## Usage

Remember to use a browser which has the script installed.

1. Login to the VPN provider page using your browser as usual
2. Press *Copy* on the Openconnect line
3. Paste to terminal.

## License

[MIT License](LICENSE)
