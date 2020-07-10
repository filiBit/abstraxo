# Abstraxo Release Notes

## 10 July 2020
 ### UI Improvements
  - Added page transitions and load spinner
  - A scrollbar now appears in the node when it's label is focused and the text doesn't fit
  - Other minor changes
 ### Fixed Issues
  - JSON Import feature now recognizes and correctly loads node's properties (name-value pairs) from all JSON objects, including those not exported by Abstraxo.
  - Fixed a routing issue on rapid navigation, including back / forward browser navigation
  - Command card no longer shows invalid buttons while some modals are opened
  - Toggling the lock button on Node's property modal while the form is active no longer causes an error
  - Other minor issues, or inconsistencies
 ### Other
  - Added the `Node Settings` button to a node's UI. For now, It has a single option for changing the node's shape between a circle and a rectangle.
  - Changed a default shape for nodes from a rectangle to a circle
  - Added new settings for: toggling swarm bubbles, Command Card's and hud buttons' visibility
  - Improved the way node selection works
  - Added `❤ Buy me a coffee` button to the hud
  
## 30 June 2020
 ### UI Improvements
  - added a welcome modal with quick actions
 ### Fixed Issues:
  - node's property edit no longer overwrites other properties
  - other minor issues
 ### Other
  - mapped ENTER and ESCAPE keys to modal actions confirm and close respectively
  - minor code optimizations

## 20 June 2020
 ### New feature
 - Wiki Import
 
   You can now convert Wikipedia articles to mind maps! 😃
   
   Generated nodes also include text content from the article's specific section that you can access by opening the node (selecting the node, and pressing the open button)
   
   The article search is done inside the app, and can provide results in multiple languages.
   
   To access the new feature press the top left button in the app (File operations) and select the **Wiki Import** tab.

## 16 June 2020
 - swarm positioning performance optimization: now the app can import larger structures without crashing
 - minor UI fixes

## 9 June 2020
  **New feature:**
  - Hotkeys:
  
    From now on, you can use hotkeys to do most actions in the app 🙂
    
    The available hotkeys are shown in the **command card** that is displayed in the bootom right corner of the screen (visible only in widescreen mode).
  
    Command buttons are arranged in a grid, meaning that each buttons' position corresponds to a position of an assigned key on the keyboard.
    
    To see which key is mapped to a specific command button, just hover over it. Note how the app assumes keyboard with QWERTY layout, but regardless to that, the key bindings correspond to your actual keyboard layout, as expected:

    | QWERTY | QWERTZ | AZERTY | DVORAK |
    |---|---|---|---|
    | `Q` - `W` - `E` - `R` | `Q` - `W` - `E` - `R` | `A` - `Z` - `E` - `R` |  `'` - `,` - `.` - `L` | 
    | `A` - `S` - `D` - `F` | `A` - `S` - `D` - `F` | `Q` - `S` -`D` - `F` | `A` - `O` - `E` - `U` | 
    | `Z` - `X` - `C` - `V` | **`Y`** - `X` - `C` - `V` | `W` - `X` - `C` - `V` | `;` - `Q` - `J` - `K` | 
