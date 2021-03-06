# Guardian

Guardian, a purpose built anti-nuke Discord bot.

---

#### How Guardian Works

Guardian allows server owners to set strict limits on administration actions. These actions include: bans, kicks, channel creations/deletions, and role creations/deletions. Once these limits are met, their Discord permissions are automatically revoked via removing all of their roles.

---

#### Setup

_Requires Node v12 for discord.js_

**1.** Add `BOT_TOKEN` property to a .env file

**2.** Configure `config.js` to your personal preferences

**3.** Run `npm start` to start the bot

**4.** Ensure the highest role the bot has is higher than others so it can remove their roles

---

#### Commands

_You can mention the bot instead of using a prefix_

**`g!prefix [prefix]`** Displays the current prefix, changes the prefix if specified

**`g!limits [index] [value]`** Displays the limits, changes an index's value if specified

**`g!reset [type]`** Resets the specified data or collection

**`g!recent [ID]`** Displays recent moderation actions that can trigger the bot's limits

---

#### Example Images

*The prefix shown in the images are different due to the ability to change the prefix using `g!prefix newPrefix`*

_g!limits command_ <br>
![](https://i.plexidev.org/w05p)

_Image of a limit reached notification_ <br>
![](https://i.plexidev.org/gVYq)

_g!recent command_ <br>
![](https://i.plexidev.org/nfMD)
