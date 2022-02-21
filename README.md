# duckiebot_gym_LaneFollowing
Duckiebot Lane Following
Reference Professor Zhou Zejian
## Installation 
## Install Anaconda
Ref: [link](https://docs.anaconda.com/anaconda/install/linux/) 
- Install the GUI tools for Ubuntu
```
sudo apt-get install libgl1-mesa-glx libegl1-mesa libxrandr2 libxrandr2 libxss1 libxcursor1 libxcomposite1 libasound2 libxi6 libxtst6
```
- Download Anaconda at [link](https://repo.anaconda.com/archive/Anaconda3-2021.11-Linux-x86_64.sh). Select "Download" at the prompt window. 
- Install by entering
```
bash ~/Downloads/Anaconda3-2021.11-Linux-x86_64.sh
```
- Keep pressing enter to view the user agreement.
- Type `yes`.
- Press enter to confirm the installation location. Change if you want to install in other locations (NOT recommended).
- Answer `yes` all the way to the end.
- Open a new terminal, type in 
```
conda -V
```
You should see `conda 4.10.3` as the Anaconda version. That means the installation is complete.
- Turn off automatically activate `base` environment
```
conda config --set auto_activate_base false
```
Now you're all set for Anaconda. 

## Acess the anaconda navigator
If you do not want to view packages by command line, you can access a GUI-based environment manageer. If you're comfortable with command line, skip this step. 
- Get into the `base` environment
```
conda activate base
```
- Access anaconda navigator
```
anaconda-navigator
```
- In the prompt GUI, create new environment following this tutorial [link](https://docs.anaconda.com/anaconda/navigator/getting-started/)
- Set the environment name as `unh_robots`, Python version as 3.7.

## Create new environment from fresh
- Get into the `base` environment
```
conda activate base
```
- Create a new environment
```
conda create -n unh_robots python=3.7.11
```
- Activate the created environment
  ```
 conda activate unh_robots

- Activate the anaconda environment
 ```
 conda activate unh_robots
 ```
- If you have created the `unh_duckie` folder before, skip this step. 
 ```
 mkdir ~/unh_duckie
 ```
- Get into the operating directory. 
```
 cd ~/unh _duckie
```
- Download the package 
```
git clone https://github.com/duckietown/gym-duckietown.git
```
- cd into the package
```
cd gym-duckietown
```
- Install the package
```
pip3 install -e .
```
## Download the lane following package 
```
git clone https://github.com/Paul-timie/duckiebot_gym_LaneFollowing.git
```
## Run the Lane Following code
```
python homework1.py

```
-Reference Professor Zhou Zejian
-Ayodele Paul
