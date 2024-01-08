# Sell item with delivery
You can sell at a location obtained through an informant.
In order to receive the coordinates, the informant NPC performs checks. Do you have the quantity intended for sale and a ticket? 
Everything can be easily changed in the config.lua file.

* Easy configuration
* Checking items
* 10 preset addresses
* Discord Webhook

# Preview
https://www.youtube.com/watch?v=F562Z0a0KX8

# Install
- Clone or Download the [repository](https://github.com/AzakitHU/azakit_delivery).
- Add the **azakit_delivery** to your resources folder.
- Add `ensure azakit_delivery` to your **server.cfg**.

# OX Inventory Items
	['weed'] = {
		label = 'weed',
		weight = 1,
		stack = true,
		close = true,
		description = nil
	},

	['sellticket'] = {
		label = 'Ticket',
		weight = 1,
		stack = true,
		close = true,
		description = nil
	},

# Requirements
- ESX
- ox_lib
- ox_target

# UPDATE
- Added two more NPCs
- Everything is easily configured in config.lua

# UPDATE
- Added additional required item check.
(Thus, up to three elements can be checked before issuing the address.)
- Everything is easily configured in config.lua

# Documentation
You can find [Discord](https://discord.gg/DmsF6DbCJ9).
