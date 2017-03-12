# PoE Sniper

A democratic PoE trade sniping tool using GNU Bash scripting.

##Usage
```
poe_sniper <item> <league> <(optional)max currency quantity> <(optional)currency type>
```

Example 1:
```
poe_sniper 'Jewel' 
```
Will look for any item name or type containing the string 'Jewel' in any league at any price.

Example 2:
```
poe_sniper 'Ancient Rel' 'Hardcore Stand' 5 chaos
```
Will look for any item name or type containing the string 'Ancient Rel' in the league containing 'Hardcore Stand' that is under 5 chaos orbs in price.