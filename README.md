
image GitHub GitHub release (with filter) GitHub Repo stars

A lightweight server picker for CS2. Previously developed for CS:GO but now for CS2! All regions available are included for freedom of selection. Still showing passion for the game since I started playing way back in 2013 despite the fact that my laptop cannot handle the game anymore with the new visual upgrades 😃.

⬇️ Download
Releases
📷 Screenshot
CS2ServerPicker Demo.gif

⚙️ Requirements
Windows 10 or above
Works on Windows 8.1 but requires .NET Framework 4.7.2 to be installed separately.
❔FAQ
1. How it works, will I get banned?!

The app does not modify any game or system files, I can assure you are safe from being banned when using the app as long as you do not download from untrusted sources. It will add necessary firewall policies to block game server relay ip addresses from being accessed by your network thus skipping them in-game when finding a match.
2. Not being routed to lowest ping server or not working on your location?

Due to the fact that we can only access and block IP relay addresses from valve's network points around the world rather than the game's actual server IP addresses directly, which are not exposed publicly, either your connection got relayed to the nearest available server due to how Steam Datagram relay works or your location might be a factor.
Re-routing can also happen anytime, even mid-game. One of the best ways to test it out is to block low-ping servers and leave out high-ping servers that are far from your current region. If your ping is high in-game, then you are being routed properly, and the blocked IP relays are not able to re-route you to a nearby server. I was able to test this out properly way back.
Some solutions that might help out but are not guaranteed: turning off any vpn, uninstalling third-party antivirus and let windefender manage the firewall.
ISP-related issues, such as bad routing or high ping, are out of scope and control since the app only adds firewall entries. Please contact your ISP instead.
3. Why it requires admin permission on execution?

This is due to how Windows requires elevated execution when adding the necessary firewall policies. If the app is running in normal mode, it will not be able to do its operations and will throw errors.
4. Windows smartscreen detected unrecognized app/publisher

The app requires a registered publisher which costs a lot of money. Rest assured the app is safe and has been tested already with more than 10k downloads.
image

5. I'm receiving frequent timeouts when a match is being confirmed

You may have blocked many servers, for optimal searching and relaying block only the necessary server relays.
6. Why windows only

The app is written using VB.NET, and Windows platform still dominates the gaming scene due to better compatibility. Steam Charts has great statistics on this.
📔 To Do
TBD
💡 Contributors
@Mohamad82Bz (for testing out the app on EU Servers and providing necessary details)
people from the issue tracker and pr section
🔽 Disclaimer
This project or its author are not affiliated, associated, authorized, endorsed by valve, its affiliates or subsidiaries. Images, names and other form of trademark are registered to their respective owners.
💖 Support the Project/Dev
I develop stuff for free with dedication and hard work. Sharing this project with fellow gamers or giving it a star is a huge sign of appreciation!
Donate with PayPal
