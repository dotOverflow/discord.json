# discord.json
Discord.json | Make your own discordbot with json !
# Example
```javascript
{
    "general": {
        "token": "ENTER YOUR TOKEN HERE"
    },
    "welcome": {
        "enabled": true,
        "type": "channel",
        "channel_id": "508588496856940546",
        "message": "Welcome {user} to the server !"
    },
    "commands": [
        {
           "command": "!command1",
           "action": "send_message",
           "message": "MESSAGE TO SEND IN CHANNEL"
        },
        {
            "command": "!command2",
            "action": "send_dm",
            "message": "MESSAGE TO SEND IN PRIVATE"
        },
        {
            "command": "!command3",
            "action": "add_role",
            "role_id": "ROLE ID"
        },
        {
            "command": "!command4",
            "action": "remove_role",
            "role_id": "ROLE ID"
        },
        {
            "command": "!command5",
            "action": "switch_role",
            "role_id": "ROLE ID"
        }
    ],
    "reaction_messages": [
        {
            "channel_id": "ENTER CHANNEL ID HERE",
            "message_id": "ENTER MESSAGE ID HERE",
            "action": "role",
            "role_id": "ID OF THE ROLE",
            "reaction": "🌠 REACTION AS AN EMOJI"
        }
    ]
}
```
