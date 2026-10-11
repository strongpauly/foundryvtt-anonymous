# 1.6.7

-   add a GitHub Actions workflow that builds the module, attaches `module.zip` and `module.json` to releases, and publishes to the Foundry package site when a token is configured
-   `module.json` version and URLs are now generated from the release tag and repository
-   `scripts/` is now built in CI and no longer committed

# 1.6.6

-   use `data-tooltip` for the GM's original-name tooltip on renamed chat text
-   fix the replaced-name highlight colors in chat for light and dark themes

# 1.6.5

-   declare Foundry v14 compatibility
-   change the combat tracker name toggle from an anchor to a button

# 1.6.4

-   fix the token HUD name toggle on v13
-   hide a combat tracker group's name from players when one or more of its members' names are hidden

# 1.6.3

-   basic Foundry v13 support (combat tracker updated for the new markup)
-   minimum compatibility is now v13

# 1.6.2

-   fix chat renaming issue introduced in `1.6.1`
-   fix names composed names not properly being encompassed

# 1.6.1

-   add support for more languages (thanks to [Elfrey](https://github.com/Elfrey))

# 1.6.0

-   updated the module to be compatible with foundry v12

# 1.5.1

-   fixed issue brought by the added compatibility for d&d 3.0

# 1.5.0

-   updated to be compatible with `Dungeons & Dragons Fifth Edition` version `3.0`
-   fixed issue with nameplates not always swapping to the desired state when creating a new token

# 1.4.4

-   fixed API bug introduced in the `1.4.3`

# 1.4.3

-   fixed rename regex catching partials

# 1.4.2

-   removed the fix that was added in `1.4.1` (foundry `11.307` fixed the issue)

# 1.4.1

-   fixed token nameplates not automatically refreshing when toggling anonymity

# 1.4.0

-   just a manifest update for v11, no work was actually done for it

# 1.3.0

the module now dissociates names and others settings when it comes to anonymity: up till now, if an actor's anonymity was removed, all the features of the module were disabled for said actor. with this version, while the actor's name will still be revealed, the other features will remain (hiding chat rolls, etc..)

-   now displays `Target: Unknown` instead of removing the line from the chat card in `pf2e` system

# 1.2.3

-   fix issue with `pf2e` critical roll result color still showing

# 1.2.2

-   the API function `playersSeeName` now also check if the actor is owned by a player, if so, it will always return true

# 1.2.1

-   fix a bug with `pf2e` lootable combatant permission

# 1.2.0

-   holding `shift` while toggling a name from the combat tracker will toggle the names of all the combatants with the same actor

# 1.1.3

-   added tooltips for the combat tracker and token HUD

# 1.1.2

-   fixed escaping bug that prevented the anonymity of actors with different names in token and alias

# 1.1.1

-   now also make saving throws anonymous in chat when using `Whistler's Item Rolls Extended`.

# 1.1.0

-   should now be compatible with the module `Whistler's Item Rolls Extended`.

# 1.0.7

-   fixed special characters when renaming chat messages

# 1.0.6

-   fixed bug with `PF2e Dorako UI` using a different element tree structure for chat cards.

# 1.0.5

-   fixed a bug with not fully provided speaker data on chat message create.

# 1.0.4

-   name parsing in chat messages is now case insensitive

# 1.0.3

-   fixed settings localization

# 1.0.2

-   cleaned debug stuff

# 1.0.1

-   fixed pf2e success degree showing

# 1.0.0

-   original release
