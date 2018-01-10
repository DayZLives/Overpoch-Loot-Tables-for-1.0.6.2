# Overpoch-Loot-Tables-for-1.0.6.2

### Install Instructions

1. 1. Click ***[Clone or Download](https://github.com/worldwidesorrow/Overpoch-Loot-Tables-for-1.0.6.2/archive/master.zip)*** the green button on the right side of the Github page.


2. Unpack your mission PBO and copy the ***dayz_code*** folder over to the root of your mission folder.

Note: if you already have this folder from installing other mods, then just copy the CrgLoot folder into the configs directory. If you don't have a configs directory, make one.

3. Edit ***description.ext

    Find this code:

      ```sqf
      #include "\z\addons\dayz_code\Configs\CfgLoot\CfgLoot.hpp"
      ```

      Overwrite it with this line:

      ```sqf
      #include "dayz_code\Configs\CfgLoot\CfgLoot.hpp"
      ```
      
4. Repack your mission PBO
