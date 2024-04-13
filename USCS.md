# Universal Ship Classification System
*REV: 2.0*

**Rules:**
- The ID must always start with the pad size.
- Pad size and purpose must be separated with a dot.
- Each ID cannot be longer than 6 characters (this includes every part, including the dash).
- Numbers cannot be used due to the character limit. If you want to differentiate between ships with the same ID, do so with their name.

**Format:**
- A dot means a primary purpose; these can be used on any ship that serves said purpose.
- An indented dot means that this purpose falls under the last purpose, so TRD covers MIN and LAS, but MIN doesn't cover TRA.
- An indented square means a sub-sub purpose, for example, the difference between a trading ship, a mining ship, and a core mining ship.

**Pad Size:**
- MP: Medium pad (for ships that require medium-sized landing pads)    
- SP: Small pad (for ships that require small-sized landing pads)    
- LP: Large pad (for ships that require large-sized landing pads)    

**Purpose:**
- EXP: Explorer (for ships designed for exploration)    
  - GRD: Guardian (for ships designed for running Guardian monuments, usually equipped with an SRV bay and point defense turrets)    
  - LRG: Long range (for ships with long jump ranges, usually equipped with an engineered FSD and/or a Guardian FSD booster)    
- TRD: Trade (for ships designed for trading)    
  - MIN: Miner (for ships designed for mining)    
    - LAS: Laser (for mining ships designed for laser mining, usually equipped with mining lasers)    
    - SUR: Surface (for mining ships designed for surface mining, usually equipped with abrasion lasers)    
    - SUB: SubSurface (for mining ships designed for subsurface mining, usually equipped with subsurface displacement missiles)    
    - COR: Deep-Core (for mining ships designed for core mining, usually equipped with seismic charge launchers and a pulse wave scanner)    
  - TRA: Transporter (for ships designed for transporting, usually have weak or no shields with lots of cargo space)    
- CMB: Combat (for ships designed for combat)    
  - GRA: Ground attack (for ships specialized in Ground attack roles)    
  - PVE: Player vs. Entity (for ships specialized in combating NPCs)    
  - PVP: Player vs. Player (for ships specialized in player combat)    
  - AXO: Anti-Xeno Operations (for ships designed for combating alien threats)    
- REC: Rescue (for ships designed for player rescues)    
  - FUL: Refueler (for ships meant to refuel others)
    - RAT: Fuel Rat (for ships specifically designed for hull seals. see [fuelrats.com](https://fuelrats.com))
  - REP: Repair (for ships designed to repair other ships, usually equipped with repair limpet controllers or rescue multi-limpet controllers)
    - HUL: Hull Seal (for ships specifically designed for hull seals. see [hullseals.space](https://hullseals.space))

        
- GEN: General-Purpose (for ships designed for versatile or undefined roles)    
- UTL: Utility (for ships designed for general-purpose utility or miscellaneous roles)    
- DEC: Decommissioned (for ships that are no longer in use and/or been stripped of all modules)    

**Examples:**
- MP-EXP: Medium pad exploration ship
- SP-TRD: Small pad trade ship
- LP-MIN: Large pad mining ship
- MP-TRA: Medium pad transporter
- SP-CMB: Small pad combat ship
- LP-PVE: Large pad PVE combat ship
- MP-PVP: Medium pad PVP combat ship
- SP-AXO: Small pad anti-xeno operations ship
- LP-GEN: Large pad general-purpose ship
- MP-UTL: Medium pad utility ship
- LP-LAS: Large pad laser mining ship
- MP-COR: Medium pad deep-core mining ship
