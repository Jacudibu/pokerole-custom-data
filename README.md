# pokerole-custom-data
Custom data and overrides for https://github.com/Jacudibu/pokerole-discord-bot

Default data for all servers can be found in `/base_data/`

In order to add custom data for your own server:
1. Add your server data to [data_mapping.json](/custom_server_data/data_mapping.json)
2. Create a folder in `/custom_server_data/` which follows the general folder and file structure of our `base_data`. In case of doubt, look at how it's done for other servers.

This process is also recommended in case you want to host your own bot instance and fork this repository, as it allows you to pull in updated base data from the main repository without worrying about merge conflicts... Unless you want to play vanilla Pokerole, right now in that case you'd need to delete all `base_data`.