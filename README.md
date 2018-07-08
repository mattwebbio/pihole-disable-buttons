# PiHole Disable Buttons
<img src="https://user-images.githubusercontent.com/420820/42415692-b69a6f7c-820b-11e8-9748-68d5714d8d65.JPG" height="300" /> <img src="https://user-images.githubusercontent.com/420820/42415694-b6b6d784-820b-11e8-8c74-32da4ccaab72.png" height="300" /> <img src="https://user-images.githubusercontent.com/420820/42415695-b6d2883a-820b-11e8-9215-6f94557023a7.png" height="300" />

A micro, stupid simple PiHole "control" panel - designed to allow your users to disable PiHole for a limited amount of time. Host locally (requires PHP), direct an old device's browser to the page, and mount the device wherever you want.

## Installation
Assuming you already have a web server with PHP installed, installation takes 2 steps:

1. Create the directory where you want to host the panel and clone the repository into it:

`git clone https://github.com/mattwebbio/pihole-disable-buttons.git .`

2. Copy `config.example.php` to `config.php` and edit it with your PiHole address and API key.

Done!
