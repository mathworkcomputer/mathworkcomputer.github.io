# mathworkcomputer

A 3D open-world riding game that runs in your browser. Deliver packages around a city on scooters and e-bikes, then take your money to the ski hill, the stunt park and the mountain bike park to land big jumps and do tricks.

The whole game is a single file (`index.html`). There is nothing to install or build.

## Running it

1. Download `index.html`.
2. Open it in a modern browser (Chrome, Edge, Firefox or Safari).
3. Tap or click the start card.

The game loads the 3D engine (three.js r128) from a CDN, so you need an internet connection the first time you open it. If the engine can't be loaded, the game shows an error message on screen.

To host it, drop `index.html` on any static host, such as GitHub Pages.

## Features

- **Open city** with traffic, delivery jobs and an optional police chase mode.
- **Vehicles:** a range of scooters and electric dirt bikes. Earn money, buy faster ones and upgrade them in the Garage (speed, braking, handling, and paint).
- **Maps** (buy them from the Maps menu):
  - **Private Road:** a long straight road for testing top speed.
  - **Stunt Park:** huge jumps. Air time pays $400 per second if you land it, plus bonuses for tricks.
  - **Ski Resort:** a 25 degree terrain park with kickers and rails. Choose skis or snowboards from 10 real-world models each.
  - **Mountain Bike Park:** a 25 degree dirt downhill with big dirt jumps. Air time pays $500 per second. Choose from 10 mountain bikes.
- **Tricks:** flip and spin in the air. Land them cleanly to get paid. On the ski and bike maps you only fall when going faster than 10 mph.
- **Pop button:** hop over obstacles, land on rails, or pop off a jump for more air.
- **Rider customization:** change your helmet, shirt, pants and backpack (or take the backpack off), and buy Fitness and Balance upgrades.
- **First person mode** (Settings, on bike and scooter maps): ride from the rider's eyes with a speed display on the handlebars.
- **Progress is saved** automatically in your browser's local storage. Settings has a restart button that wipes it.

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Go / gas | `W` or Up arrow | GAS / GO button |
| Brake / stop | `S` or Down arrow | BRAKE / STOP button |
| Steer left / right | `A` `D` or Left / Right arrows | Steering controls |
| Pop (ski and bike maps) | `Space` | POP button |
| Boost (city and road maps) | `B` | BOOST button |
| Look behind | `C` | Look-back button |
| In the air: spin | `A` `D` | Steering controls |
| In the air: flip | `W` `S` | Gas / brake |

Let go of everything in the air to line up your landing.

## Tips

- Pop right at the end of a kicker for extra air.
- On the Ski Resort, pop about 2 to 18 metres before a rail to land on it. Hitting a rail without popping at speed makes you fall.
- Better skis, boards and bikes in the shop glide faster. Wax and Edges upgrades in the Gear garage add speed and sharper turns.

## Project layout

```
index.html   the entire game (HTML, CSS and JavaScript)
README.md    this file
```

## Credits

Built with [three.js](https://threejs.org/).
