# polies-swap
To start the installation, follow the steps below and get your own DEX
<br>

Start by purchasing your VPS and we recommend the <a href="https://www.vultr.com/?ref=8912463">Here</a> <br>
After getting your VPS of at least 4GB of RAM we can get started
<br>

Connect via terminate using the program that best suits you, we recommend Putty <br>
Use the codes mentioned one by one
<br>
<br>
Let's update all your VPS data
```
sudo apt update -y && sudo apt upgrade -y
```
we will install nodejs , npm and yarn <br>
```
sudo apt install npm -y && sudo apt install nodejs -y && sudo apt install yarn -y
```
```
mkdir PoliesSwap && cd PoliesSwap 
```
Now that we've created a folder and entered it, we can clone the official repository, be sure to go there and rate it with the stars <br>
```
git clone https://github.com/pancakeswap/pancake-frontend.git
```
enter the folder <br>
```
cd pancake-frontend
```
Install the official npm repository <br>
```
npm install
```
now start the instance to run the test
```
npm run start
```
run in your browser (VPS ip + Port: 3000)



