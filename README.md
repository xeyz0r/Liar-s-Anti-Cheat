# Liar's Anti-Cheat

Welcome to the **Liar's Bar Anti-Cheat Mod**! This is an **anti-cheat** mod 
designed to enhance the integrity and fairness of the 
[Liar's Bar](https://store.steampowered.com/app/3097560/Liars_Bar/) game by 
preventing and mitigating the most common cheats.

As a fresh, brand-new game that has just recently been released, Liar's Bar is 
still in the process of refining its security measures. The game developers are 
working diligently to address these issues and enhance the overall gameplay 
experience.

However, with the game's current P2P setup, it is unfortunately easy for 
players to cheat. This mod aims to address these issues by providing robust 
anti-cheat mechanisms.

<img alt="Liars Anti-Cheat Mod Banner" src="Liars Anti-Cheat Mod Banner.png"/>


# Features

### Current Features

- **Players' Cards Obfuscation:** 
Prevent cheaters from seeing other players' cards by obfuscating everyone's 
cards to 5 jokers.

- **Thrown Cards Obfuscation:** 
Prevent cheaters from seeing the cards that got played onto the table by 
obfuscating the played cards into all joker cards.

- **Bullet Position Obfuscation:** 
Prevent cheaters from seeing your (host) bullet position by obfuscating your 
bullet position to the last chamber and only revealing your real bullet 
position when you are about to die.

- **Auto-Kick for Cheating:** 
  - Auto-kick cheaters attempting to play cards that they don't have in their hand.
  - Auto-kick cheaters attempting to change their bullet positions mid-game.
  - Auto-kick cheaters trying to place their bullet into an invalid revolver chamber.
  - Auto-kick cheaters that illegally modify their revolver shot counter (e.g., decrease the shot counter).
  - Auto-kick cheaters (or modders) that modify the chat messages in an illegal way (e.g., impersonating someone else, hiding their player name, changing the name color, etc.).

### Work-In-Progress Features

- **Bullet Position Obfuscation for All Players:** 
Prevent cheaters from seeing other players' bullet positions by obfuscating 
everyone's bullet position to the last chamber and only revealing the real 
bullet position when the player is supposed to die.

- **Bullet Rigging Prevention:** 
Prevent cheaters from rigging their bullet at the start of the game (currently, 
the bullet position is dictated on the client side and relayed to the server).

### Planned Features

- **Movement Mod Prevention:** 
Prevent modders from using harmless but disruptive mods such as illegal head 
movements or player body movement.

- **Compatibility Support:** 
Ensure compatibility with other mods that will (hopefully) start to appear.


# Installation

1. Install **BepInEx** (see [BepInEx Installation Guide](https://docs.bepinex.dev/articles/user_guide/installation/index.html)) or download [here](https://github.com/BepInEx/BepInEx/releases)

2. Launch **Liar's Bar** _once_ with **BepInEx** installed to generate necessary mod folders and files

3. Navigate to your **Liar's Bar** game directory and go to `./BepInEx/plugins`
    - The `BepInEx` and `plugins` folder should have been generated in the previous step
    - **Example:** `C:\Program Files\Steam\steamapps\common\Liar's Bar\BepInEx\plugins`

4. Download the Anti-Cheat mod from the [Github Releases](https://github.com/xeyz0r/Liar-s-Anti-Cheat/releases/latest)

5. Copy the downloaded **DLL file** (ex. `LiarsAntiCheat.dll`) to the `plugins` folder

6. Launch the **Liar's Bar** game and enjoy your new Anti-Cheat mod :)


# Host-Only

Please note that this anti-cheat mod works only if you are the host of the 
lobby and hosting the game. If you join someone else's lobby, none of the 
anti-cheat features will work, as it all depends on having server authority.

However, you can still join other players' lobbies just fine, and it won't have 
any impact on your ability to play the game.
