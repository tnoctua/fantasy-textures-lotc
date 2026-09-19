  _   _ _       _   _ _       _       _____           _                  
 | \ | ( )___  | | | (_) __ _| |__   |  ___|_ _ _ __ | |_ __ _ ___ _   _ 
 |  \| |// __| | |_| | |/ _` | '_ \  | |_ / _` | '_ \| __/ _` / __| | | |
 | |\  | \__ \ |  _  | | (_| | | | | |  _| (_| | | | | || (_| \__ \ |_| |
 |_| \_| |___/ |_| |_|_|\__, |_| |_| |_|  \__,_|_| |_|\__\__,_|___/\__, |
     _       _     _    |___/__            _     ___ _____ ____    |___/ 
    / \   __| | __| |      / _ \ _ __  _  | |   / _ \_   _/ ___|         
   / _ \ / _` |/ _` |_____| | | | '_ \(_) | |  | | | || || |             
  / ___ \ (_| | (_| |_____| |_| | | | |_  | |__| |_| || || |___          
 /_/   \_\__,_|\__,_|      \___/|_| |_(_) |_____\___/ |_| \____|         
                                                                         
===============================================================
  N's High Fantasy - LOTC Add-On		Version: 1.0     
===============================================================

  This resource pack contains overlays for Lord of The Craft
to be applied to the high fantasy resource pack.  These
resources are partially compatible with 1.21.5 though they are
designed to work with 1.21.11 and later.  Using this resource
pack with game versions prior to 1.21.11 will result in issues,
and those known will be listed below.

  This resource pack is licensed under the NRP License.
Please read LICENSE.txt for the full terms and conditions.

===============================================================

  Inside this directory you will find the following overlays:
  
  - tnoctua_lotc_additions
  	|-- Provides textures for player and plugin items.
  	
  - tnoctua_lotc_herbs
  	|-- Provides textures for herb plugin items.
  	
  - tnoctua_lotc_lang
  	|-- Provides translations for LOTC server biomes.
  	
  - tnoctua_lotc_tweaks
  	|-- Provides vanilla overrides that fit with the server.
  	
  These overlays can be enabled/disabled by modifying the
pack.mcmeta file and moving overlay objects from "entries" to
"disabled_entries" in the file.  Some features cannot be
disabled due to the way Minecraft handles item definitions.

===============================================================

  Caveats/Shortcomings/Bugs:
  
  - Due to some player-signed items using the same base item as
  	herbs in the plugin, the textures cannot be disabled as it
  	causes conflict with item model definitions.
  
  - Item model definitions that target custom_data components
    such as those used in all herb tweaks appear to be bugged
    in versions prior to 1.21.11 and will fail to update the
    item models in GUI.  Items in-world such as those on market
    stalls or dropped on the ground will display correctly.
    LOTC is shite on 1.21.5 anyways, just update you hold-out.
  
  - Placeholder models that reference items not present on the
    installed game version will appear as missing textures.
    If you encounter this issue, install a later version of
    Minecraft.
  
  - Tweaks are intrusive and override vanilla game textures.
    They may impact the experience when used outside of the
    LOTC server.  Often these compromises are used when objects
    are omnipresent in LOTC and should be changed, but cannot
    be targeted with item model definitions.

===============================================================

  To report bugs and request features, please contact below:
  
  - Discord: @tnoctua
  - GitHub: https://github.com/tnoctua/fantasy-textures-lotc
  - Modrinth: https://modrinth.com/project/DnCMWQtJ
  - CurseForge: https://curseforge.com/minecraft/texture-packs/tnoctua-high-fantasy-lotc

