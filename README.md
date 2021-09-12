# Setup github 

This is how to setup a new machine

1- install VS code
2- install git .. follow the instructions in https://www.atlassian.com/git/tutorials/install-git
3- generate ssh key .. follow the steps in https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

4- Validate that the keys were generated.
    Issue the following commands.

    mcd $HOME/.ssh
      
    mydesktop$ ls -l

Issue the following command.

mydesktop$ cat id_rsa.pub

copy the key and past it in your github account under: settings/ssh keys 
5- Add your SSH private key to the ssh-agent. If you created your key with a different name, or if you are adding an existing key that has a different name, replace id_ed25519 in the command with the name of your private key file.

$ ssh-add ~/.ssh/id_ed25519

6- Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"


# setup docker
1- follow the instructions in https://docs.docker.com/engine/install/ubuntu/



## subheader
this is subheader

### subsubheader
added subheader
