# Odyssey of the Dragonlords currency
Module for Foundry VTT that modifies currency to fit a common Odyssey of the Dragonlords homebrew.

# Installation
1. Feed this link to Foundry's Module Manager
 > https://raw.githubusercontent.com/leonardograham/ootdcurrency/master/module.json
 
 2. Enable the Module in your Worlds Module Settings
 
 ## Details
 This module is working primarily on a cosmetic level as it's just renaming the 5e currencies as follows:


5e Default| |Odyssey
--- | --- | ---
Platinum|-->|*REMOVED*
Gold|-->|Drachmae
Electrum|-->|*REMOVED*
Silver|-->|*REMOVED*
Copper|-->|Lepta
     
In addition to the renaming and hiding of currencies the conversion button's formula has been altered to have 1 Drachma equal 100 Lepta.

 ## Known Issues
 Not compatible with Lazy Money. When subtracting lepta by any number not divisible by 100, it gives incorrect conversions.
