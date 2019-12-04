# GitHub Tutorial

_by <your-name-here>_

---
## Git vs. GitHub
Git: a programming lanugage that you can code by keeping snapshots of codes and back track to previous ones.
Github: Pleace where coding is stored, specifically git. Github tracks the changes made so you can always revert or go to a code version.

---
## Initial Setup
**git config* Used to shape/order/put together or order something.
### To start using git and github, follow the steps below.
1. Use git config --global user.email "you@example.com
    - Example:git config --global user.email _"johndoe@hstat.org"_
2. Then type git config --global user.name "Your Name for githhub/git"
    - Example:gitconfig --global user.name _"JaneDoe"_
3. Do _cd ~_ (makes sure you are in the root directory) 
4. Type in ssh--keygen -t rsa -b 4096 --C "you@email.com"
    - Example: ssh--keygen -t rsa -b 4096 ---C _"Johndoe@hstat.org"_ 
5. Keep pressing the _Enter_ key slowly until you see a weird block of text.
    - It should look basically like this..
The key's randomart image is:
+--[ RSA 4096]----+
|       .o o..    |
|       o +Eo     |
|        + .      |
|         . + o   |
|        S o = * o|
|           . o @.|
|            . = o|
|           . o   |
|            o.   |
+-----------------+
6. Do eval "$(ssh-agent -s)", this starts the agent in the background.
7. Do ls -al.ssj (List all files long and looks for ~/.ssh), you should now see a file named  *id_rsa.pub*
8. Use cat ~/.ssh/id_rsa.pub which then copies all of the result into your clipboard (it should start with ssh-rsa and end with YOUR email address)
9. Go into the link... To create a new SSH Key.          Title it: ide50           Key: paste your ssh key          Press the green _Add SSH Key_ button.
   https://github.com/settings/keys





---
## Repository Setup



---
## Workflow & Commands
