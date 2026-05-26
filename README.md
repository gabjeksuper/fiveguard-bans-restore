# Fiveguard Bans Restore Bot
A free, self-hosted utility bot to easily extract, segment, and restore Fiveguard ban databases for your FiveM server.


# What it does

- Scrapes Discord text channels to collect historical ban data sent via Fiveguard webhooks.
- **Intelligent Segmentation**: Automatically detects when the anticheat database is wiped or reset based on logs (e.g. the ban file is deleted and another set of bans is recorded) and splits data into separate `bans.json` files categorized by date (`Since DD-MM-YYYY to DD-MM-YYYY`).
- **Interactive Paging**: Delivers generated files through a clean, multi-page interactive embed with button controls, displaying the most recent database instantly.


# How to use

Invite the bot to your Discord server logs by clicking [here](https://discord.com/oauth2/authorize?client_id=1508724912649408542
) and ensure it has the **View Channel**, **Read Message History**, and **Application Commands** permissions.

### Commands

- Use the `/create-bans-file [channel-id]` command to analyze a specific channel.
- *(Optional)* Provide a `from-message-id` to start scraping from a specific point in time.
- *(Optional)* Provide a `to-message-id` to cap the scraper at a specific historical message.

*Note: For performance reasons, the interactive pagination buttons will remain active for 10 minutes after execution.*


# Documentation

To best set up your anticheat configuration and avoid false bans, follow our documentation.

🌐 Website Doc: https://gabjeksuper.gitbook.io/fiveguard-configuration


# Want More?

Discord: **gabjeksuper**

Want a custom bot tailored to your server, community, or gaming needs? 100% functional, highly optimized, and robust? Send me a private message on Discord (setup + hosting + future changes included).


# Credits

This free utility tool has been brought to you by a community member, **gabjeksuper**, to help server owners maintain seamless backup logs for their [fiveguard.net](https://fiveguard.net/) anticheat. 

Join the official [Fiveguard Discord](https://www.discord.gg/fiveguard) community. 
*Please note: This tool is an independent community project and is not officially affiliated with or developed by the Fiveguard team.*
