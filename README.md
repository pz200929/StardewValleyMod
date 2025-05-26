# Reflection:

Working on this Stardew Valley mod taught us a lot about C# and game modding. We used Content Patcher to change Lewis' dialogue and appearance by first unpacking the content folder and editing the JSON files to add new sprites. We made mistakes like trying to use FromFile the wrong way or having the wrong folder structure, but after running the game, the SMAPI messages helped us fix them. We also used some softwares like GIMP to edit pixelated art and a Stardew Valley portrait maker (https://jazzybee.itch.io/sdvcharactercreator) to create our character's portrait. We learned C# features like some "load" actions, target expressions, and simple file paths, with the help of Content Patcher. The Stardew Valley Wiki page and modding guides were really helpful when we got stuck. In our collaboration, Philip handled all the art editing (GIMP and portrait maker) and manifest code while Matthew edited all the dialogue lines as well as the content code. At the end, seeing our work showing up in the game was exciting, and the most important thing we learned was that testing small changes first saves a lot of time, as we can easily find errors and fix them. Overall, our project replaced all Lewis' dialogue with modern Gen Z slang and changed the character's appearance into Lebron James. 


# Lebonbon's Lewis Replacement Mod

<img width="1440" alt="Screenshot 2025-05-22 at 09 29 22" src="https://github.com/user-attachments/assets/e4bda267-eedf-4dd5-a084-a1f81b3a041a" />
<img width="1440" alt="Screenshot 2025-05-22 at 09 29 30" src="https://github.com/user-attachments/assets/bbff9930-de51-4446-9fbe-ea14cdaa940a" />


## Features
Replaces Mayor Lewis with a custom character (Lebonbon) including:
- **Complete dialogue overhaul** - All new conversations and responses
- **Custom character sprite** - New appearance for Lewis
- **Unique portrait** - Matching portrait for dialogue boxes

## Installation
1. Install SMAPI
2. Download the mod folder
3. Place the entire `Lebonbon` folder in your `Stardew Valley/Mods` directory
4. Launch the game via SMAPI

## How It Works
This mod uses Content Patcher to:
- `Load` new dialogue from JSON
- `Load` replacement sprite and portrait PNGs
- Completely overwrites Lewis's original assets

## Compatibility
- Works with Stardew Valley 1.5+
- Requires Content Patcher (included in SMAPI)
- Compatible with most other mods like NPC locations
- <img width="1440" alt="Screenshot 2025-05-22 at 09 29 10" src="https://github.com/user-attachments/assets/86336072-28f1-48b5-9cef-3e65de91e885" />

## TODO
- Add seasonal dialogue variations
- Include custom gift preferences
- Create unique heart events
- Change the name below the portrait from Lewis to Lebonbon

## Credits
- Dialogue writing: Matthew Wu
- Art assets: Philip Zheng
