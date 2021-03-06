## BuildSubmission

Build management plugin for Minecraft. Ranks with customized commands for each promotion.

#### Download

You can find all releases [here](https://github.com/freddedotme/BuildSubmission/releases).

#### Commands

    /bs submit - Submit a build for review
    /bs cancel - Cancel a submitted build
    /bs list - List all pending reviews
    /bs review <player> - Teleports to a pending submission
    /bs rank <player> - Show the player's rank
    /bs approve <player> - Approve a build
    /bs deny <player> - Deny a build
    /bs reset <player> - Reset a player's rank

#### Permissions

    bs.user - submit, cancel
    bs.admin - list, review, rank, approve, deny, reset
    bs.rankN - where N = number >= 0, will apply on restart/login

#### chat.yml

    SUBMITTED: '&eBuild submitted.'
    APPROVED: '&aCongrats, your build was approved!'
    DENIED: '&cSorry, your build got denied.'
    INVALID: '&cInvalid argument or command.'
    CANCEL: '&eYour submission has been cancelled.'
    
#### commands.yml

    ONLINE:
    - '{rank1} tell {player} YAY'
    - '{rank2} tell {player} WOO'
    OFFLINE:
    - '{rank1} promote {player}'
    - '{rank2} promote {player}'
    
**{player}** will use the player's username.  
**{rankN}** where N = number >= 0. Needs to be written as the examples above. Avoid using "/" before the command.

#### Bugs and errors

Please use the [issue tracker](https://github.com/freddedotme/BuildSubmission/issues) if you need help.
