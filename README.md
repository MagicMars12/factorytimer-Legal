# Factory Timer

Hello everyone! Thank you for choosing **Factory Timer**!

## About the mod

Factory Timer gives you detailed information about your factories' health and the exact time at which they will stop. Hit a factory, give it a name, and the mod keeps counting down for you, even while you are away. Share your factories with friends through groups, and show them as live cards in a Discord channel.

## Requirements

- Minecraft **1.21.11**
- [Fabric Loader](https://fabricmc.net/use/installer/) 0.18.0 or newer
- [Fabric API](https://modrinth.com/mod/fabric-api)


## Quick start

1. Type **`.f`** to open the menu.
2. Make a group with **Create**, or join your **friends** group with an invite code.
3. Open your group and click **Make default group**.
4. Go to a factory and hit it to check its health, the way you normally do.
5. Name the new factory when the mod asks (see below).
6. Type `.f list` any time to see every factory with its health and time left.

## Commands

1. **`.f`**: opens the UI menu.
2. **`.f help`**: shows you all commands.
3. **`.f list`**: shows a list of all your factories.
4. **`.f set <#> <label>`**: renames a factory. `#` is its number from `.f list`.
5. **`.f name <label>`**: names the factory you last touched.
6. **`.f discord <groupname>`**: gives you the Discord bot link along with a link code, so you can connect your Discord server and a specific channel to your group.
   - **`.f discord <groupname> new`**: creates a new Discord link code.
7. **`.f remove [#]`**: deletes the factory you last touched, or number `#`.
8. **`.f yes <name>`**: saves a newly found factory under that name. **`.f no`** keeps the default name and **`.f cancel`** discards it.

## The menu

Type `.f` to open it. From the menu you can:

- see all your groups, and hover over one for your rank, its members and its factories,
- create a group or join one with an invite code,
- see members and factories with their health and time left,
- show an invite code, or make a new one,
- show a Discord link code, or make a new one,
- kick a member or hand the group over to someone else with **Make owner** (group owners only),
- leave or delete a group.

## Connect a group to Discord

You need to be the group owner, and have **Manage Server** on the Discord server.

1. In game, type `.f discord <groupname>`. It shows the bot link and your link code.
2. Open the bot link and add the bot to your **server**.
3. Pick a channel for the cards and let the bot **View Channel**, **Send Messages** and **Embed Links** there.
4. In that channel, type `/link code:XXXX-XXXX` with your code. A code works only once.
5. Your factories appear as cards within a few minutes, and they refresh by themselves.

Discord commands: `/list` shows all factories, `/rename` renames one, `/remove` deletes one, `/unlink` disconnects the channel and `/settings` controls who can use each command.

## Note

- Each group has one owner. A group can hold up to 25 members and 100 factories.
  


