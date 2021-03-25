# GMUD-Explorer  

GMUD Explorer is a spin off of MMUD Explorer.  Syntax did a wonderful job with MME, but as GreaterMUD continues to evolve having it's own version of MME provides for more updates that are specific to the GreaterMUD game.


v1.0.5 (03/25/2021)  
------------------------------------------  
* Removed line in path save that looks for rooms.md based on Environment variable USERPROFILE

v1.0.4 (03/25/2021)  
------------------------------------------  
* Update Monster List View, added new sortable columns for Accuracy (Max), AC/DR, Dodge, Spell Attacks (shows the spell type of attack spells cast by monster, else No)

v1.0.3 (03/19/2021)  
------------------------------------------  
* Updated Monster Attack Sim to account for GMUD hit % calculations

v1.0.2 (03/19/2021)  
------------------------------------------  
* Fixed issue with character bless dropdowns resetting when changing filters on spell list
* Added spells from usable items to spell list for classes as well as to character bless dropdown

v1.0.1 (03/18/2021)  
------------------------------------------  
* Updated tab index on Character and Equipment tabs
* Fixed issue with +/- buttons on stats and on AC (there are still others that are broken)
* Updated swing calculator to allow for 6 swings and the GMUD QnD calculation
* Updated the Bless dropdowns, they're now tied to the global filter and show only spells usable by the chosen class
* Fixed the room 0/0 bug
* Added a global ctrl+a to select all from textboxes on frmMain (which is most of the app)
* Updated CP Calculator to handle increases above 100
* Updated Accuracy vs AC calculation to account for GMUD 100% miss rate
