1. I installed a UNIX-based operating system, Ubuntu.

2. I used commands: 
sudo apt install zsh
zsh --version
chsh -s $(which zsh)
echo $SHELL
$SHELL --version
for installing zsh and making it my default shell.

3. I used commands:
apt-get install git
git status
git --version
for installing git

4. I used commands:
sudo snap install curl # version 7.84.0
curl -L https://install.ohmyz.sh | sh
for installing oh my zsh.

5. I used command:
sudo apt install gcc
for installing gcc

6. I used commands:
sudo snap install atom --classic
sudo apt update
sudo apt install software-properties-common apt-transport-https wget
wget -q https://packagecloud.io/AtomEditor/atom/gpgkey -O- | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://packagecloud.io/AtomEditor/atom/any/ any main"
sudo apt install atom
for installing atom

7. I created a file : nano hello.c
The code: #include <stdio.h>
 
          int main() {
             printf("Hello, world!\n");
             return 0;
          }
I saved the file and compiled it into an executable : gcc hello.c -o hello
I executed the program : ./hello
Output was: Hello World!

8. I made a repositori in git and pushed all the files there.
git add .
git commit -m "v2"
git push
