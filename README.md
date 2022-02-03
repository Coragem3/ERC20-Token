# Hardhat
Setting up a local environment

Using VSC

cd Hardhat

npx create-next-app [name]

cd app name


npm install ethers hardhat @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers @openzeppelin/contracts

npx hardhat
create basic project with gitignore


Change sample_test.js to just test.js

change sample_script to deploy

In another terminal run 'npx hardhat node' in same directory

Run 'npx hardhat run scripts/deploy.js --network localhost' in VSC 

(Make sure that the deploy script has the 'Hello hardhat' omitted from it before deploying. This is because in the constructor, it is not in)




