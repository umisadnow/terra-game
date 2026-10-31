# Crypt of the Iron Dice

Ten floors to go. Only a chipped broadsword, ancient buckler and three dice that probably dislike you.

A web based tactical dice roguelike written completely in Vanilla JavaScript and HTML5 Canvas. All of your equipment is powered by dice rolls. Roll your dice pool and drag them into your weapons and shields to attack enemies, increase your armour, create poisons or cheat destiny.

## Play Online

[https://umisadnow.github.io/terra-game/]

## Local

Download `index.html` file and double click to play.

## Gameplay

### Specific Requirements

All weapons/shields have requirements. Siege Maul only accepts dice rolls of `4` or higher, Oak Buckler requires even dice rolls and Headsman Axe needs an exact roll of `6`.

### Predictable Combat

The enemy will always show what their next move is. This can be anything from a Bog Ooze throwing acid to an Abysmal Executioner preparing to strike with a 14 damage cleaver.

### Poor Rolls

If you get three 1s on a key turn you can use your Reroll. Or simply design your deck to contain poor rolling items such as Gutter Shiv (Max 3), Loaded Flip (Exact 1 - Spawns 2 new dice).

### Ten Floor Dungeon

After each room you can choose a path. You can fight Elite enemies for double gold, heal at Smoldering Braziers, barter with the Blind Peddler for Relics or risk your HP at cursed shrines. Finally fight Malakor, the Die King on Floor 10.

## Controls

| Action | Key |

|:--- |:--- |

| Drag & Drop | Drag dice from bottom tray to equipment slots. |

| Left Click | Select dungeon rooms, Shop items, Reroll & End Turn. |

| Spacebar | End Turn (Combat). |

| R | Restart Run |

| M | Mute/Unmute retro synth. |

## Technical Info

I wanted this game to be fully contained.

### No External Assets

All characters (Knights, Rats & Slimes), dice faces and particles are drawn procedurally using HTML5 ``. Using a custom CRT Scanline effect.

### Synth Sounds

All sounds (Dice, Sword, Shield, Coin & Fanfare) are created using the Web Audio API. Using oscillators (AudioContext) instead of `.mp3` / `.wav` files.

### High Scores

Using `localStorage` to keep track of your highest score.

## License

Play, fork and have fun! If you can beat Floor 10 using poison I salute you.
