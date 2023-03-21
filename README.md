⚑ This mod adds a party system to Minecraft! 

Track your party member's health, experience, or even dimension! Currently, there are 15 different elements with more being made! You can choose from several presets or create your own... almost everything is configurable! Special support for other mods will be added over time.

⭐ Current Elements

✔ Player Head/Model: Renders the player's head icon on the UI. Has an option to render the model instead in the advanced settings. Also has a tooltip that shows the player's name when hovered.

✔ Player Name: Renders the player's name on the UI. Has an option to limit the amount of letters to display.

✔ Leader Indicator: Displays an icon on the party leader's frame. Shows who is the party leader in the party. Only the party leader can invite/kick other members. Also has a tooltip!

✔ Dimension Indicator: Displays an icon on the UI indicating which dimension the player is in. Also has an animation for when the player changes dimensions (can be turned off). Has support for custom dimensions, along with the custom dimensions from RFTools Dimensions! (Must use rftoolsdim:dim as the dimension name in the custom dimension json). Supports RFTools Dimensions, Twilight Forest, and Vanilla as default. Also has a tooltip!

✔ Potion Effects: Three different types of potion effect bars are implemented: Debuffs only, buffs only, or a combined bar. The amount of buffs, the amount of buffs per row, the color - almost everything is configurable!

✔ Armor Indicator: Displays an icon on the UI indicating the armor level of the party member. Has a tooltip and can be text-only or icon-only.

✔ Hunger Indicator: Displays an icon on the UI indicating the hunger level of the party member. Has a tooltip and can be text-only or icon-only.

✔ Experience Bar: Has support for a custom-sized experience bar. Can also be text only or bar only, and has tooltip support!

✔ Health Bar: Displays a health bar (not hearts) that also shows any absorption the player currently has. Also has animations (can be disabled), and tooltip support!.

✔ Offline Indicator: Displays an icon along with text when the player is offline. Can be text only or icon only as well.

✔ Dead Indicator: Displays an icon when the player is dead.

✔ Transparent Box: A background box to aid with text visibility for elements that have it (like hunger text, armor text, and name). Can be resized/moved.

⌛Clickable Box Area: A box that currently has little use (the party settings icons snaps to this box). In the future, it will support clicking frames - and this box defines the area/outline of the party frame. Almost like a tab target rpg! (Support for Ars Noveau).

⌛Mana Bar: This, although not implemented yet, will represent another bar that shows the player's current mana levels, similar to the Health Bar! (Support for Ars Noveau).

⌛Pet Frame: Although not implemented yet, will represent a pet that the player has tamed and will display basic elements like health, name, and armor.
 
Almost every single element has extra configurability like scale, position, and even a toggle to enable or disable the element.

⭐ Getting Started

‣ To create a party, you invite another player through the command '/party invite PlayerName'. They will get a chat notification and will be able to click Accept or Decline (by recalling the mouse) or use the following commands: '/party accept' or '/party decline'. You can only invite someone that doesn't have a party.

‣ The inviter will become the party leader. They can transfer leadership by using the following command: '/party leader PlayerName'. Please note that only the party leader can kick/invite other players to the party. Also note that the party size limit is default of 5 and can be configured on the server.

‣ Players can leave their party by using the command '/party leave'. You can only join another party when you're not currently in one.

‣ There is an extra keybind under Game Interface called 'Show Mouse (Party UI). It defaults to Left Alt. Using this keybind recalls the mouse which allows you to hover over the chat screen (and click on links, including accept/decline invites). This also allows you to hover over elements that have tooltips like the hunger, health, and dimension indicators, for example. Pressing this keybind also makes two buttons visible: Party Settings, and a Preset Loader. The Party Settings displays more buttons that allows you to manipulate the party frame's position, the player order, or open the advanced party settings. The preset loader button allows you to load presets (either default or custom ones in the folder config/sedparties/presets). 

‣ The advanced party settings may be a bit complicated at first, but will get easier once you get the hang of it. The first button on the top-left allows you to load other presets. Note that this overwrites your current one! The several buttons on the right of the load button allows you to configure every element available in the mod. This ranges from position, scale, visibility, to even disabling specific animations. Note that this updates the UI in real-time, but doesn't save the preset to a file. You can save a preset by filling the name and description boxes on the bottom of this screen and clicking the save button.

‣ The extra buttons on the right of the UI are also useful:

Toggle RGB Mode: toggles all Hex Code color entries to their RGB counterparts.

Turn All Other Elements Off: Turns off all other mod elements. Helps with visibility.

Turn All Other Elements On: Turns on all other mod elements. In case you don't want to individually turn them all back on.

Reset Current Element to Default: Resets the current selected element to its default position. Note that it also depends on the main frame's width/height.

Reset Everything to Default: It's similar to loading the default preset. Note that it overwrites your current preset, and there's no going back!

Copy Preset to Clipboard: Copies your current preset to clipboard. This can be shared with other people as well! Just note that it only works within specific versions.

Load Preset from Clipboard: Attempts to load a preset from your clipboard. Valid presets are only ones that originated from the copy button.

Link Preset to Chat: Links your current preset to the chat. Players can click on the preset link to copy your preset to their clipboard and load it from the Load Preset from Clipboard button.

Note that you don't need to use the advanced settings. This is only for people that want to create their own presets or are unsatisfied with the default presets provided.

⭐ Other Information

You can add custom dimension support by providing the dimension registry name, the item registry name, and the text color in a json file under /config/sedparties/dims. To support RFToolsDimensions, you must use the dimension registry name 'rftoolsdim:dim'. You can view examples in the folder under the file default.json. To reload dimension files you can type the command /party reload. Note that this also re-writes all default presets under the defaultconfigs folder, so can be used in case those were deleted somehow as well.

The advanced party settings window automatically closes when you take damage. This is to prevent needless death in case you're no longer safe. The advanced party settings window can also be dragged by clicking from outside the party settings window and dragging. Useful in case the window's default position covers your party frame.
