
# Homebridge Counter

## This plugin is a fork of the plugin developed by https://github.com/shamanskyh, with contributions from https://github.com/nano9g.

The change arises from my need to reset index values at a specific time of the day.

Example config.json:

```
    "accessories": [
        {
            "accessory": "IndexCounter",
            "name": "My Counter",
            "max": 6,
            "randomizeAfterDelay": true,
            "resetAfterDelay": true,
            "delay": 300000,
            "resetAtTime": true,
            "time": "18:00",
        }
    ]

```

With this plugin, you can keep track of an index and increment or randomize it at will. This is useful in HomeKit since it provides a simple variable that can be used with automations.


