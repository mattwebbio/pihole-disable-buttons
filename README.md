# PiHole Disable Buttons
A micro, stupid simple PiHole "control" panel - designed to allow your users to disable PiHole for a limited amount of time. Host locally (requires PHP), direct an old device's browser to the page, and mount the device wherever you want.

## Installation
Assuming you already have a web server with PHP installed, installation takes 2 steps:

1. Create the directory where you want to host the panel and clone the repository into it:
`git clone https://github.com/mattwebbio/pihole-disable-buttons.git .`
2. Copy `config.example.php` to `config.php` and edit it with your PiHole address and API key.

Done!