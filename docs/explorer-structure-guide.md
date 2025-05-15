# Explorer Structure Guide
This page aims to get you into a nice clean work environment for you to build your games in! To do this, we have a set of rules that you must apply to make sure that your game works with these requirements.

## Guide Principles
The following are some general key points you should note that this guide aims for you to work on:
* Making the objects in the Explorer more readable.
  - This means truncating the names of individual objects to a format that has the same meaning behind.
  - You should use abbreviations _if possible_ over full words, as long as the abbreviation(s) are well known, and do not cross with any other ones. An example of an erroneous abbreviation would be "Temp", which could stand for both "Temporary" or "Temperature". An example of a good abbreviation could be "Misc" which stands for "Miscellanious".
* Making your game ready for change; have all possibilities thought out for where new instances can go.
  - You should however consider the necessities of whatever you're making towards change; don't add directories which are unnecessary if there are alternatives that may fit better for **all** eventualities. An example of something you _shouldn't_ do is create a "Scripts" Folder in `Workspace`, as although `Workspace` is able to run server-side Scripts inside of it, `ServerScriptService` is the most secure place for that purpose, and is designed to house all active server-side Scripts. `Workspace` is only meant to act as a container for all visible assets.
