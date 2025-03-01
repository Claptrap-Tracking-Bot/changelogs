## Saturday 01 March 2025

* Fixed Minecraft Update Icons not Showing
* Fixed ATLauncher API routes leading to invalid requests
* Fixed Database tables not being deleted when the bot is kicked from a server
* Fixed CurseForge /linkout spamming changelogs
* Fixed CurseForge changelogs showing urls as encoded urls
* Added Ping Role support to Forge, NeoForge, Fabric, Quilt, Minecraft and Curse Launcher Notifications
* Added support for changing the changelog length
* Added support for changing between code blocks, or raw markdown for changelogs

***

## Tuesday 28 January 2025

* Fixed Dashboard being limited to 200 servers and not showing for new servers

***

## Sunday 18 August 2024

* Fixed some update trackers failing to run completely when they encounter any errors

***

## Friday 05 July 2024

* Fixed bot not being able to be added to new servers after discord verification
* Fixed dashboard displaying "Not a member of this guild"
* Added Health Check Command

***

## Thursday 23 May 2024

* Fixed other games from CurseForge not being supported anymore

***

## Satuday 06 April 2024

* Fixed wrong channel type in slash commands
* Fixed modrinth updates spamming logs with errors, that aren't errors
* Fixed Tracking commands not allowing announcement channels to be used

***

## Friday 29 March 2024

* Fixed ATLauncher and GitHub commands not allowing you to untrack projects
* Added the ability to change notification styles when tracking new projects
* Fixed NeoForge and Curseforge Spelling on Embeds
* Updated CurseForge Logos on Embeds
* Fixed FTB updates not being posted
* Added better monitoring to discover outages and errors
  

***

## Wednesday 29 November 2023

* Added Curselauncher ModLoader notification support for NeoForge
* Added Quilt to Curselauncher Filtering Options
* Improved the overall Curselauncher Filtering
* Updated Discord JDA

***

## Monday 7 August 2023

* Added support for NeoForge notifications

***

## Wednesday 31 May 2023

* Fixed an issue with Curseforge Alpha/Beta files not being detected as updates

***

## Sunday 14 May 2023

* Switched from using SQLite to Postgres. Also cleaned up the database
* You can now track/untrack projects from a different channel, instead of only the one the command was executed in. All tracking commands take this in as an optional parameter
* You can choose to ping a role (or roles through the dashboard) when a project updates
* Fixed some MAJOR issues with the FTB Tracking commands
* We now have a public API that developers can use to build their own solutions for managing the bot, instead of relying on our dashboard alone
* Compact notifications. This setting is per server, and not per project/channel

***

## Sunday 05 February 2023

* Added support for Curseforge Launcher version tracking. This allows modpack makers to see when new Forge, Fabric, Quilt, and Minecraft versions are added to the Curseforge Launcher.
* Removed the requirement for Claptrap Manager role
* Removed the Welcome message when Claptrap joins a server
* Updated to Latest Discord JDA
* Fixed Minecraft Updates spamming "Snapshot" version notifications


## Monday 21 November 2022

* Added FTB Support
