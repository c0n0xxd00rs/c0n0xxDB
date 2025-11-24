

CH 4:



 GIT CONFIGURATION;

 git config --global user.name "NAME"

 git config --global user.email example@gmail.com

 git config --global color.ui auto

 git config --global core.editor "code --wait"

 git config --list



SSH SETUPS:

generate SSH keys: ssh-keygen -t ed25519 -C "example@gmail.com"

Press Enter 3x

view the key : cat ~/.ssh/id_ed25519.pub {copy the entire line}


Add to GitHub : GitHub|Settings| SSH&GPG Keys| New SSH Key | Paste | Save


Test the connection : ssh -T git@github.com

-------------------------------------------------
Shows: edd25519 key fingerprint is : {copy that} , Enter Y/Yes

{PASTE THE COPIED FINGERPRINT KEY}

AUTHENTICATED --> you're done

Test connection again: ssh -T git@github.com



