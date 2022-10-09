INFO 4430 Project Idea - D&D CMS
================================

#### • Benjamin Keninger

* * *

### Project Outline

This site will host a Character Management System (CMS) for Dungeons and Dragons characters.  
The webapp will maintain a database of D&D characters (including monsters and NPCs) which will keep track of basic stats about each character, and users will be able to create, view, edit, and delete these characters.  
By default users will only be able to view previously created characters by other registered users, but logging in will give them access to make their own.  

I got the idea for this project from my work where we use a customer management system to keep track of our company's customers.  
I thought it would be both fun and interesting to combine this kind of application with my hobby of playing Dungeons and Dragons and create a customer management system for D&D characters.

This site is hosted through AWS and the domain name is registered through Epik.  
As I currently use the domain name "kenibenj" for a personal website, it made sense just to use a subdomain for this webapp instead of purchasing another domain name.  
The webapp will use the following WISA software stack:

*   **W**indows
*   **I**IS
*   **S**QL Server (might change in the future - still looking into it.)
*   **A**SP.NET

The Minimum Viable Product (MVP) will support a login system and basic CRUD(create, read, update, delete) operations for the characters.  
Each character will have at least a name, HP, class/type, stats (STR, DEX, CON, INT, WIS, CHA), and a description.  
The user will be able to search for characters, and will be able to filter this search by attribute.

Some things I still need to think about/some features I might implement:

*   What SQL RDBMS do I want to use
*   What exact information will be recorded for each character?
*   Having the ability to make a character's visibility private so only the creator of that character can see it
*   Verify user account with email authentication?
*   Forbid certain usernames in order to prevent distasteful public usernames. (here is a pretty good list of censored words I found : https://mod.gib.me/darksouls2/ngword/english.txt)

### Current Goal

Right now I am working on a proof of concept app that will support some of the features of the finished project.  
It is currently using Entity Framework though this will obviously be changed in the final release of the webapp.  
![](images/sites.JPG)  
As of right now the proof of concept only functions properly on localhost, so I can't feature what I have done so far on this site just yet.  
  
![](images/Capture.JPG)
