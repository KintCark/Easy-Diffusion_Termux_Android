# Easy-Diffusion_Termux_Android
Another one bites the dust! You can install easy Diffusion on android! But it's very slow so be patient it doesn't work on 8gb ram devices it will crash u need at least 12gb or 16gb ram


DISABLE PHANTOM PROCESS KILLLER OR U WON'T BE ABLE TO MAKE IMAGES OVER 320X320!!!!


FIRST DOWNLOAD EASY DIFFUSION LINUX ZIP FROM EASY DIFFUSION GITHUB PAGE
THEN GO TO GOOGLE PLAY STORE AND DOWNLOAD MARCO FILE MANAGER THEN INSTALL STEP 1 
THEN GO TO MARCO FILE MANAGER AND MOVE THE easy-diffusion FOLDER TO THE TERMUX DRIVE UBUNTU-FS ROOT FOLDER
THEN START STEP 2


COPY 3 LINES AND PASTE IN TERMUX!

Step 1

pkg update -y && pkg install wget curl proot tar -y && wget https://raw.githubusercontent.com/AndronixApp/AndronixOrigin/master/Installer/Ubuntu22/ubuntu22.sh -O ubuntu22.sh && chmod +x ubuntu22.sh && bash ubuntu22.sh 

Step 2

apt update && apt upgrade -y && apt-get install curl git gcc make build-essential python3 python3-dev python3-distutils python3-pip python3-venv python-is-python3 -y 

Step 3

cd easy-diffusion

Step 4

chmod +x start.sh

Step 5

cd scripts 

COPY ALL 3 LINES AND PASTE IN TERMUX!

Step 6

chmod +x bootstrap.sh  &&
chmod +x functions.sh &&
chmod +x on_env_start.sh

 Step 7
 
cd

 Step 8
 
 cd easy-diffusion



'Fix' the issue with Python running in PRoot

export ANDROID_DATA=anything 



 Step 9
 
 ./start.sh
 
 
 
 
 
AFTER RESTARTED TERMUX
 
 cd ubuntu-in-termux && ./startubuntu.sh
 
 cd easy-diffusion
 
 ./start.sh
