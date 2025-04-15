# Configuration

> **The CORE Retail Lite Configuration file contains all the settings that make your game different to the rest.**

You can change any of these settings and make the tables empty, but do not delete any configuration as this may break the system.

Below is the current Configuration settings:

```lua
local Configuration = {
	
	General = {
		MaxProductsTaken = 3,
		Currency = "£",

		EnableBillBoardUI = true,
		TemplateBillBoardUI = "",

		BasketObjects = {
			"Basket"
		},
		
		RestockTools = {
			"Box",
			"Crate",
			"Lagoon"
		}
	},
	
	ProximityPrompt = {
		TemplateLocation = nil -- if you are using a proximity prompt with custom settings
	},
	
	RestockWhitelist = { -- who is able to restock
		
		GroupLock = {
			["PutGroupIDHere"] = {
				MinimumRank = 32
			}
		},
		
		TeamWhitelist = {
			"Staff",
			"Developer"
		},
		
		PlayerWhitelist = {
			"sirnolag"
		},
	}
}

return Configuration
```

