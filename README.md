# Easy-Diffusion_Termux_Android
Another one bites the dust! You can install easy Diffusion on android this is the best for low ram devices it only requires 2 GB of vram!!! But it's very slow so be patient 



FIRST DOWNLOAD EASY DIFFUSION LINUX ZIP FROM EASY DIFFUSION GITHUB PAGE
THEN GO TO GOOGLE PLAY STORE AND DOWNLOAD MARCO FILE MANAGER THEN INSTALL STEP 1 
THEN GO TO MARCO FILE MANAGER AND MOVE THE easy-diffusion FOLDER TO THE TERMUX DRIVE UBUNTU-FS ROOT FOLDER
THEN START STEP 2


COPY ALL 3 LINES AND PASTE IN TERMUX!
pkg updated && pkg upgrade -y && termux-setup-storage &&
pkg install wget -y && pkg install git -y && pkg install proot -y &&
cd ~ && git clone https://github.com/MFDGaming/ubuntu-in-termux.git && cd ubuntu-in-termux && chmod +x ubuntu.sh && ./ubuntu.sh -y && ./startubuntu.sh 


apt update && apt upgrade -y && apt-get install curl git gcc make build-essential python3 python3-dev python3-distutils python3-pip python3-venv python-is-python3 -y 


cd easy-diffusion

chmod +x start.sh

cd scripts 

COPY ALL 3 LINES AND PASTE IN TERMUX!
chmod +x bootstrap.sh  &&
chmod +x functions.sh &&
chmod +x on_env_start.sh
 
cd
 
 cd easy-diffusion
 
 ./start.sh
 
 
 
 
 
 after restarting termux 
 
 cd ubuntu-in-termux && ./startubuntu.sh
 
 cd easy-diffusion
 
 ./start.sh4
