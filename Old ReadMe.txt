**************************************************
WoW Texas Holdem v2.0 - Forked from Anzac Holdem
**************************************************
WoW Texas Holdem is a fully functional Texas Holdem Poker Mod that allows World of Warcraft players to play texas holdem with each other while in World of Warcraft.  This mod provides users something to do while waiting for spawns, raiding, and while looking for a group.

We do not suggest playing for real money, or world of warcraft gold.

This version is only made possible from the help of Wet, developer of Questie.


**************************************************
Installation
**************************************************
1) Unzip folder into your World of Warcraft\Interface\AddOns directory.
2) WoW Texas Holdem Files should now be in worldofwarcraft\interface\addons\WoWTexasHoldem


**************************************************
How to play WoW Texas Holdem
**************************************************
1) Login to world of warcraft
2) To start a game type /holdem
3) To join someone elses started game type /holdem 'playername' (remove the quotes and replace playername with the character's name)

**************************************************
v2.1 Changes
**************************************************
- Updated the addon communication to use proper addon channels, this prevents triggering serverside spam filter
- Changed communication protocol to use base89streamlib, which has a smaller data size and the possibility for better error checking / hack prevention

**************************************************
v2.0 Changes
**************************************************
- Updated to get it to work with World of Warcraft Version 2.0.

**************************************************
v1.21 Changes
**************************************************
- Merged Forks of Anzac Holdem v1.02 and WoW Texas Holdem 1.20 so that you get the following features:
- Added minimize support via the "minimap" button
- Minimap button will flash when its your turn
- Minimap button can be used to start a dealer

- Fixed a known crash bug where you could show cards after you'd lost all your chips.
- Added Window Resizing Support, offered at 50%, 75% and 100% 

**************************************************
v1.20 Changes
**************************************************
- Blinks on player we're all waiting for -- then sits them out after 30 seconds 
- Added a dealer button that moves around the table for the "current dealer"
- Added the ability for a player to sit out -- you gotta raid sometimes
- Added a timer of 30 seconds for the current player -- they get folded and sit out if they don't act in time

- Fixed All in button was appearing when the player still had chips -- premature button text 



**************************************************
Features we plan to add in future versions
**************************************************

- Add avatar of all other players characters to the screen. (Currently you see your own but no one elses).
- Add Change "raise" to "bet" unless the player is actually raising
- Add Blink the cards or the status text of the player who wins the pot
- Add allow player to "fold" or "check" if they're in the blind
- Add Show cards on players who haven't folded
- Add Adjustable blinds
- Add ability for dealer to set the time out time.

- Fix if board plays then pot should be split
