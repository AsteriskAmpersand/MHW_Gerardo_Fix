# MHW_Gerardo_Fix
Complete all special assignments before applying the fix. It will mess up Jho, FFXIV Kulu and Behe quests if you don't.

Fixes the issues with Geralt not spawning if using the hub mod.
 * Save on the Research Base.
 * Make a backup of your save.
 * Ensure the game is closed from this point on.
 * Drag your save file (SAVEDATA1000) to the GerardoFix.exe program.
 * Open your save in the Save Editor (https://github.com/AsteriskAmpersand/MHW-Save-Editor) (check the releases tab, not the code tab).
 * Save over it.
 * Pray.
___
 * If your character is not on slot 1 you can call the scripts as:  
`GerardoFix.exe "PATH_TO_SAVEFILE\SAVEDATA1000" SLOTNUMBER`
 * Step by Step:
   * Win+R
   * cmd
   * cd /d "Path to Gerardo Fix between quotes"
   * GerardoFix.exe "Path to your save file between quotes" 2
 * If you become unable to save just delete all files in the remote folder that aren't SAVEDATA1000 or SAVEDATAB
 ___
  * The fix is provided as is with no guarantee of working, it's unlikely I'll attempt to rewrite for every bizarre case there is as it's a pretty egregious blind patch.

# Old_MHW_Gerardo_Fix
Fixes the issues with Geralt not spawning if using the hub mod.
Use this version (on a clean unfixed file) if the first didn't work.
 * Save on the Research Base.
 * Make a backup of your save.
 * Ensure the game is closed from this point on.
 * Open the save on the Save Editor (https://github.com/AsteriskAmpersand/MHW-Save-Editor) (check the releases tab, not the code tab). 
 * Save unencrypted (Dropdown when "Save As" and pick unencrypted)
 * Drag your save file (SAVEDATA1000.bin) to the OldGerardoFix.exe program. 
 * Open Fix.bin and save encrypted as SAVEDATA1000 (over your save file) on your save directory. Pray.  
___
 * If your character is not on slot 1 you can call the scripts as:  
`GerardoFix.exe PATH_TO_SAVEFILE SLOTNUMBER`
 * Step by Step:
   * Win+R
   * cmd
   * cd /d "Path to Gerardo Fix between quotes"
   * GerardoFix.exe "Path to your save file between quotes" 2
 * If you become unable to save just delete all files in the remote folder that aren't SAVEDATA1000 or SAVEDATAB
 ___
  * The fix is provided as is with no guarantee of working, it's unlikely I'll attempt to rewrite for every bizarre case there is as it's a pretty egregious blind patch.
