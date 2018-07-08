# PiHole Disable Buttons
<img src="https://user-images.githubusercontent.com/420820/42415692-b69a6f7c-820b-11e8-9748-68d5714d8d65.JPG" height="300" /> <img src="https://user-images.githubusercontent.com/420820/42415694-b6b6d784-820b-11e8-8c74-32da4ccaab72.png" height="300" /> <img src="https://user-images.githubusercontent.com/420820/42415719-b14a5090-820c-11e8-82ee-fc3bf0e987e4.png" height="300" />

A micro, stupid simple PiHole "control" panel - designed to allow your users to disable PiHole 
for a limited amount of time (without giving them the admin password). Host locally (requires PHP), 
direct an old device's browser to the page, and mount the device wherever you want.

## Installation
Assuming you already have a web server with PHP installed, installation takes 2 steps:

1. Create the directory where you want to host the panel and clone the repository into it:

`git clone https://github.com/mattwebbio/pihole-disable-buttons.git .`

2. Copy `config.example.php` to `config.php` and edit it with your PiHole address and API key.

## Extra Information
Built with just HTML/CSS, jQuery and PHP. The UI checks the status of the PiHole server every 
10 seconds. If you want more/different time options, just adjust index.html and do.php. 

Theoretically, this app doesn't need PHP - I'm merely using it to hide the API key. If you don't use HTTPS
on your PiHole server (the API URL you entered in the `config.php`) and you're not hosting this panel on the
same server as PiHole (your API URL isn't 127.0.0.1), then this kind of defeats the purpose and you're likely
broadcasting your API key across the network.

## FAQ
* `API Error` - check the API entered key in config.php
* `Connection Error` - make sure the web server can ping the PiHole server (and make sure PiHole is online!)