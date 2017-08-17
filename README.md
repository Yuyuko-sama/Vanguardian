# Vanguardian
A tera-proxy module that automatically finishes Vanguard Initiative quests on completion.  
It finishes the quest 2 seconds after it got completed if you are able to finish it.  
If you are dead or in a battleground, it will recheck if the quest can be completed every 5 seconds.  
  
## Usage  
While in game, open a proxy chat session by typing "/proxy" or "/8" in chat and hitting the space bar.  
This serves as the script's command interface.  
The following commands are supported:  
  
* vg - enable/disable Vanguardian  
  
## Safety
Whatever you send to the proxy chat in game is intercepted client-side. The chat is NOT sent to the server.  
  
## Changelog
### 1.2.0
* [*] Some code cleanup
* [*] Full conversion to Pinkie Pie's command module
### 1.1.0
* [+] Added automatic completion of daily and weekly bonus
### 1.0.0
* [*] Initial Release