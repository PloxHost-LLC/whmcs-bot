# whmcs-bot

Deprecated!! If anyone wants to take the attempt to update this- feel free too.

This bot was used for my hosting company https://plox.host/ and has since been recoded. 
I'll eventually open source the new bot whenever the code looks half decent. 

## State of code
The bot is buggy, but works. I started to integrate a system to lookup clients by their email. 
Here's what needs to be updated
- Update to D.JS 12
- Finish the upgrade for email lookup
- Change GetTickets to search by the email/CID instead of scanning through the whole output
- Fix bugs

## How to use it
Well firstly you need to own a WHMCS license, the bot needs permissions to:
- GetClientsDetails
- getclientsProducts
- GetTickets

If you want to use the linking system you need to setup a system on your WHMCS which sends a request to the webhook. I will eventully release the code for the webhook.

Please contact me on discord if you have any questions. markd#0001 markd@plox.host

