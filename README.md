# AoC-AI-Aggression-Reducer
This mod lowers the AI's aggression. The way vanilla works is that if the AI has nothing better to do (aka is bored), it goes to war. With this mod before the AI even considers whether it wants to go to war or not, it has to go through an RNG check. If it fails then the AI does nothing for that turn. AI doing nothing can happen in vanilla anyway if the boredom war can't find a suitable target, so the game can handle an inactive AI for a turn. The intensities are as follows:

Vanilla: 100% chance of considering going to war if nothing better to do.

Low: 25% chance of not going through with war considerations if bored.

Medium: 50% -

High: 75% -

In my testing, high has resulted in a way calmer world. If you glance at the BepInEx logs you'll see all the times a warmongerer got bonked in the head.

## Requirements
- BepInEx 5 x64 (Mono). Download from the official BepInEx releases. https://github.com/bepinex/bepinex/releases

## Install
1. Extract the BepInEx zip into the game folder (next to the exe). Run the game once.
2. Extract **this mod’s zip** into the plugins location so that:
   - BepInEx\plugins\AI Aggression Reducer.dll exists
3. Run the game. Check `BepInEx/LogOutput.log` for "AI Aggression Reducer loaded".

## Configure
After the first launch with the plugin installed you can find the created config in BepInEx/config/AIAggressionReducer.cfg. Config includes directions.
