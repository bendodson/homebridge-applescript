homebridge-applescript-file
===========================

Supports triggering AppleScript commands on the HomeBridge platform via Applescript files.

## Installation

1. Install homebridge using: `npm install -g homebridge`
2. Install this plugin using: `npm install -g homebridge-applescript-file`
3. Update your configuration file. See `sample-config.json` in this repository for a sample.

## Configuration

Configuration sample:

```
"accessories": [
	{
		"accessory": "ApplescriptFile",
		"name": "Security Camera",
		"on": "/Users/bendodson/Documents/Scripts/cameraOn.applescript",
		"off": "/Users/bendodson/Documents/Scripts/cameraOff.applescript"
	}
]
```

Note that you must use absolute paths for your AppleScript file.