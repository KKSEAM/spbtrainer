# Hypixel Speed Builders Trainer
View, practice, and grind time on all of Hypixel's 350+ builds in your own singleplayer world.

**Compatible with Fabric 1.21.x**. More versions to come as released.

Not affiliated with the Hypixel Network.

### Features
- **Practice all 350+ Hypixel builds** - All builds as of `August 3rd, 2025` are included
- **Realistic Functionality** - Mimics & supports Hypixel's "features" such as buttons on floor and **90-degree stair rotation placement**
- **Advanced Automatic World Setup** - Instantly setup your world with `/spb setup`
- **Different Modes**:
  - **Build Mode** - Creative powers with limited blocks, also restricts breaking and placing blocks outside of the platform
  - **Grind Mode** - Skips the build preview and enables replenishing blocks in order to keep practicing your time
- **Time Recording** - Your times are viewable and recorded locally in `spbtrainer.json` within your config folder
- **Customizble Preview Time** - Run `/spb config` to set preview time. Default is 5 seconds
- **Customizble Keybinds**. Defaults:
  - `Grave Key` - Clear build area
  - `F6` - Restart
- **Custom Builds Support** - Create and practice your own custom builds
- **Randomized Layout** - Builds with set hotbars will be added soon, e.g., `colors` or `painting vertical`
- **Builds Spreadsheet** - All Hypixel builds listed, as well as extra information. It can be found [here](https://docs.google.com/spreadsheets/d/1fSd1hopLb59BqAY-T0gyVs8ceevx1QD36Xqu-oSHJBA/edit?usp=sharing)
## Usage
### Dependencies
Before installing this mod, make sure you have the following mods installed:
- [WorldEdit](https://modrinth.com/plugin/worldedit)
- [Fabric API](https://modrinth.com/mod/fabric-api)

<details>
  <summary>Dependencies download table for convenience!</summary><br>
  
  *Note: All links take you straight to Modrinth downloads. It's easier to right click &rarr; `Open Link in New Tab`*
  
  <table>
    <thead>
      <tr>
        <th>Fabric API version</th>
        <th>WorldEdit version</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><a href="https://modrinth.com/mod/fabric-api?version=1.21#download">1.21</a></td>
        <td><a href="https://modrinth.com/plugin/worldedit/versions?loader=fabric&version=1.21#download">1.21</a></td>
      </tr>
      <tr>
        <td><a href="https://modrinth.com/mod/fabric-api?version=1.21.1#download">1.21.1</a></td>
        <td><a href="https://modrinth.com/plugin/worldedit/versions?loader=fabric&version=1.21.1#download">1.21.1</a></td>
      </tr>
      <tr>
        <td><a href="https://modrinth.com/mod/fabric-api?version=1.21.2#download">1.21.2</a></td>
        <td><a href="https://modrinth.com/plugin/worldedit/versions?loader=fabric&version=1.21.2#download">1.21.2</a></td>
      </tr>
      <tr>
        <td><a href="https://modrinth.com/mod/fabric-api?version=1.21.3#download">1.21.3</a></td>
        <td><a href="https://modrinth.com/plugin/worldedit/versions?loader=fabric&version=1.21.3#download">1.21.3</a></td>
      </tr>
      <tr>
        <td><a href="https://modrinth.com/mod/fabric-api?version=1.21.4#download">1.21.4</a></td>
        <td><a href="https://modrinth.com/plugin/worldedit/versions?loader=fabric&version=1.21.4#download">1.21.4</a></td>
      </tr>
      <tr>
        <td><a href="https://modrinth.com/mod/fabric-api?version=1.21.5#download">1.21.5</a></td>
        <td><a href="https://modrinth.com/plugin/worldedit/versions?loader=fabric&version=1.21.5#download">1.21.5</a></td>
      </tr>
      <tr>
        <td><a href="https://modrinth.com/mod/fabric-api?version=1.21.6#download">1.21.6</a></td>
        <td><a href="https://modrinth.com/plugin/worldedit/versions?loader=fabric&version=1.21.6#download">1.21.6</a></td>
      </tr>
      <tr>
        <td><a href="https://modrinth.com/mod/fabric-api?version=1.21.7#download">1.21.7</a></td>
        <td><a href="https://modrinth.com/plugin/worldedit/versions?loader=fabric&version=1.21.7#download">1.21.7</a></td>
      </tr>
      <tr>
        <td><a href="https://modrinth.com/mod/fabric-api?version=1.21.8#download">1.21.8</a></td>
        <td><a href="https://modrinth.com/plugin/worldedit/versions?loader=fabric&version=1.21.8#download">1.21.8</a></td>
      </tr>
    </tbody>
  </table>
</details>

### World Setup
1. `Singleplayer` &rarr; `Create New World`
2. Set `Game Mode` to **Creative**
3. Set `Allow Commands` to **ON**
4. In the `World` tab, set `World Type` to **Superflat**
5. `Customize` &rarr; `Presets` &rarr; `The Void` (it will work without this, but you may have mob spawns, and it won't look as pretty)
6. `Create New World`
7. Once you're in the world, run `/spb setup`

### Commands
*Important: Build names are formatted with no spaces and no capitals, e.g., `castleonahill`*
- `/spb config` - Shows configuration in chat with interactable buttons
- `/spb <build>` - Loads a build with a preview, then allows for building. Essentially a round of SPB
- `/spb grind <build>` - Enables grind mode, which skips the previews, and automatically replenishes blocks in order to practice
- `/spb stop` - Stops all previews and clears build region and inventory
- `/spb reset` - Resets/clears the build area
  - **Default keybind: `Grave Key`**
- `/spb restart` - Resets/clears the build, area, replenishes blocks, and begins a countdown to try again
  - **Default keybind: `F6`**
- `/spb setup` - Sets up the world for the mod. Make sure you're in a superflat world with the void preset, with commands enabled!
- `/spb create <build>` - Creates a custom build for whatever is on the platform
- `/spb delete <build>` - Deletes your custom build
- `/spb list` - Shows your custom builds
- `/spb area` - Displays a message containing the build area
- `/spb time <build>` - Displays your best recorded time for the build
- `/spb time reset <build>` - Resets the recorded time for a build
- `/spb view <build>` - Places the complete build for learning
- `/spb buildmode <on/off>` - Toggles buildmode
- `/spb help` - Shows this!

## Known Issues
*Note: If any issues occur, which are not mentioned here, DM `ilovelifethankyou` on Discord for any questions, issues, or concerns. spbtrainer 1.21.4 is the **best** version.*
- Signs don't leave inventory on `bus` build
- Some builds don't have set hot bars yet 
  - Please DM me builds with set hotbars
- Some builds use wrong blocks - very minor issue that's being fixed as they appear
  - Please DM me builds with wrong blocks

## FAQ
*Note: `ilovelifethankyou` on Discord for any questions, issues, or concerns not mentioned here.*
### Q: Can I use this mod on the Hypixel server?
A: While it doesn't have multiplayer functionallity, you can log into servers with it safely.
### Q: Can I use this alongside other SPB mods?
A: Yes. It doesn't interfere with [Boxeth's SpeedBuildersHelper](https://modrinth.com/project/aUJs6CKs).
### Q: Is there a 1.8.9 version?
A: Due to complexity, previous verisions such as 1.8.9 will most likely not be available, but I'll check it out.
### Q: Is there a list of builds I can see?
A: Click [here](https://docs.google.com/spreadsheets/d/1fSd1hopLb59BqAY-T0gyVs8ceevx1QD36Xqu-oSHJBA/edit?usp=sharing) for the Hypixel Builds Spreadsheet.
### Q: A build is missing! Where can I report it?
A: Please DM `ilovelifethankyou` on Discord builds with set hotbars that aren't already added!

## Coming Soon
- `/spb game` - Mimics a game of SPB, 2 simple, 2 easy, medium, hard, insane
- More set hotbars for builds that have them

## Testers and Thanks
- Thank you `DIX0` on Hypixel for providing many of the builds!
- Thank you `HanaHippo` on Hypixel
- Thank you `aembr` on Discord | `aembur` on GitHub for proofreading and restructuring README
  - And their amazing [GuessTheUtils](https://modrinth.com/project/49W6BOju) mod!
  
## To-Do List
- Preview Video
- `/spb builds` - Link to spreadsheet
- One time in game toast notification for build spreadsheet
