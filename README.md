# Hypixel Speed Builders Trainer 
View, practice, and grind time on all of Hypixel's 350+ builds in your own world.         
**Compatible with Fabric 1.21.x** - More versions to come as released

Not affiliated with the Hypixel Network

### Dependencies 
- Requires [World Edit](https://modrinth.com/plugin/worldedit) 
- Requires [Fabric API](https://modrinth.com/mod/fabric-api) 

<details>
  <summary>Dependencies download table for convenience!</summary>
  <br>
  &#11088; All downloads are Modrinth Links
  
  Note: It is Easier to Right click &rarr; `Open link in new tab`
  
  <table>
    <thead>
      <tr>
        <th>Fabric API</th>
        <th>WorldEdit Mod</th>
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


### Notices
- Not intended for multiplayer functionallity, but you can log into servers with it safely
- Extremely easy world setup needed! (`/spb setup`) `Superflat, The Void, Allow Commands`
- Does not interfere with [Boxeth's SpeedBuildersHelper](https://modrinth.com/project/aUJs6CKs) SPB time mod
- Due to complexity, previous verisions such as 1.8.9 will most likely not be available, but I'll check it out.
### Builds are formatted with no spaces and no capitals ex: `castleonahill`
- Command Usage: `/spb grind castleonahill` or `/spb kitchen`
### Hypixel Builds Spreadsheet [Here](https://docs.google.com/spreadsheets/d/1fSd1hopLb59BqAY-T0gyVs8ceevx1QD36Xqu-oSHJBA/edit?usp=sharing)
- Please DM me builds with set hotbars that aren't already added!

`ilovelifethankyou` on Discord for any questions, issues, or concerns.

## Features
- **Practice all 350+ Hypixel builds** - All builds as of `August 3rd, 2025` are included
- **Realistic Functionality** - Mimics & Supports Hypixel's "features" such as buttons on floor and **90-Degree stair rotation placement**
- **Grind Mode** - Skips the build preview and enables replenishing blocks in order to keep practicing your time
- **Time Recorder** - Your times are viewable and recorded locally in `spbtrainer.json` within your config folder
- **Customizble Preview Time** - Run `/spb config` to set preview time, default is 5 seconds
- **Customizble Keybinds** - Clear build area `Grave Key` and Restart `F6` are default
- **Advanced Automatic World Setup** - Instantly setup your world with `/spb setup`
- **Custom Builds Support** - Create and practice your own builds
- **Randomized Layout** - Builds with set hotbars will be added soon ex:`colors` or `painting vertical`

`Buildmode` - Creative powers with limited blocks, also restricts breaking and placing blocks outside of the platform

`Grindmode` - Skips the build preview and enables replenishing blocks in order to keep practicing your time

## Commands
- `/spb config` - Shows configuration in chat with interactable buttons
- `/spb <build>` - Loads a build with a preview, then allows for building. Essentially a SPB Round
- `/spb grind <build>` - Enables grind mode, which skips the previews, and automatically replenishes blocks in order to practice
- `/spb stop` - Stops all previews and clears build region and inventory
- `/spb reset` - Resets/clears the build area
  **Default keybind: `Grave Key`**
- `/spb restart` - Resets/clears the build, area, replenishes blocks, and begins a countdown to try again
  **Default keybind: `F6`**
- `/spb setup` - Set's up the world for the mod, make sure you're in a superflat world with the void preset, and commands enabled!
- `/spb create <build>` - Creates a custom build for whatever is on the platform
- `/spb delete <build>` - Deletes your custom build
- `/spb list` - Shows your custom builds
- `/spb area` - Displays a message containing the build area
- `/spb time <build>` - Displays your best recorded time for the build
  `/spb time reset <build>` - Resets the recorded time for a build
- `/spb view <build>` - Places the complete build for learning
- `/spb buildmode <on/off>` - Toggles buildmode
- `/spb help` - Shows this!

`ilovelifethankyou` on Discord for any questions, issues, or concerns.

## World Setup
Superflat with `The Void` preset. Once you're in your world run `/spb setup`

It will work in a normal superflat, but you may have mob spawns, and it won't look as pretty!

## Known Issues
- Signs don't leave inventory on `bus` build
- Some builds don't have set hot bars yet 
  - Please DM me builds with set hotbars
- Some builds use wrong blocks - very minor issue thats being fixed as they appear 
  - Please DM me builds with wrong blocks

## Coming Soon
- `/spb game` - Mimics a game of SPB, 2 simple, 2 easy, medium, hard, insane
- More set hotbars for builds that have them

## Testers and Thanks
- Thank you `DIX0` on Hypixel for providing many of the builds!
- Thank you `HanaHippo` on Hypixel
## To-Do List
 - Preview Video
 - `/spb builds` - Link to spreadsheet
 - One time in game toast notification for build spreadsheet


If any issues occur, spbtrainer 1.21.4 is the &#96;best&#96; version
