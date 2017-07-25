# Evrey's Stronghold Crusader Campaign

A custom skirmish campaign for this classic game.

## What is it and how to install it?

This is basically a set of custom maps and modded AI castles, together with instructions on how to set up skirmish matches and in which order. Everything you'll need can be found right in this repository.

- The sub-folder `Maps` contains all maps related to this campaign. They all follow the naming scheme `EVY M?? *******`, where `EVY` is just a short nickname for `Evrey`, `M??` is the mission number and where `*******` is the mission's German title. E.g. the first mission is called `EVY M01 Die Ankunft`.
- These maps have to be copied to *Stronghold Crusader's* custom maps folder. On a default Windows installation, this folder is located at: `C:\Users\<Your Name>\Documents\Stronghold Crusader\Maps`. If, for whichever reason, you cannot find this folder, you can copy the maps to the game's internal maps folder instead. That folder is: `<Path to Stronghold Crusader's .exe>\maps`. Note, however, that maps within the internal map folder cannot be modified using the map editor.

The modded AI castles are all taken from [Evrey's modded SHC AI castles](https://github.com/Evrey/SHC_AIV).

## How do I play a campaign mission?

Let's say that you want to start playing `M01 Die Ankunft`. First, you'll have to remove all AI castles from the game. The AI castles are 128 files with the extension `.aiv`, located at `<Path to Stronghold Crusader's .exe>\aiv`. Then, you have to copy all the files from `<This Campaign>\M01 Die Ankunft\aiv` to `<Path to Stronghold Crusader's .exe>\aiv`. This ensures, that all AI lords - in this case the Sultan - build very specific castles. The campaign's maps have been optimised for them, and building other castles might break the AI due to e.g. unplacable buildings. Then, you follow the instructions provided in `<This Campaign>\M01 Die Ankunft\README.md` to properly set up the skirmish game - e.g. where to put the AI lords in which color and with which amount of start resources - and go play it. You might also want to read the mission's description, which is provided in German and English.

So, to wrap this all up:

- Remove all `.aiv` files from the game.
- Copy the mission-specific `.aiv` files to the game's `aiv` folder.
- Go to the mission's folder of this repository, read the contained `README.md`, and follow its instructions.
- Start the skirmish game after you have set up everything correctly and have fun!
- Do not forget to copy the `.aiv` files you previously used back to the game's `aiv` folder, if you are done playing a mission. In case you forgot to do a backup, you'll find Firefly's original `.aiv` files, as well as Evrey's modded and fixed ones, in the [AI mod repository](https://github.com/Evrey/SHC_AIV).

## License

Keep in mind that this is just a custom campaign for *Firefly Studio's* game *Stronghold Crusader (Extreme) HD*. Without this game, this repository is worth nothing.

Anyways, the campaign itself is published under the MIT license:

- Understandable description on [tl;dr legal](https://tldrlegal.com/license/mit-license)
- [Full license text](./LICENSE-MIT.md)
