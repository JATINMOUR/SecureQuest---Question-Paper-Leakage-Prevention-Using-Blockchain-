<<<<<<< HEAD


##  🚩 Technologies used:

#### Programming Languages : Solidity, Javascript, HTML, CSS
#### Face Recognition Model :  TensorflowJS
#### Database : Polygon (Ethereum Layer-2) Blockchain
####  Frameworks/Libraries/Tools : Bootstrap, FreeOCR, Google Transalate, Truffle, Ganache, VSCode, IPFS, Moralis, Web3, Tokenizer
#### Version Control : Git
###### You can also see the list of dependencies in the package.json file.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🚩Installation/Environment Setup 

  #### Login Credentials 
       Username - "Divij" password - "divij0406" passcode - "123456"
       Ethereum address - "0xED620CdD26E4adfae79Ea12f5fadd2c4c6ab54a4"
       
  #### 1. Clone App
  
  * Write the following command and press enter.
  
  ```
    $ git clone https://github.com/Divijkatyal0406/CrowdQuest.git
  ```
    
 #### 2. Install node packages
  * Move to the parent/root directory (CrowdQuest) cd CrowdQuest
  * Write the following command and press enter to download all required node modules.
 
   ```
   $ cd CrowdQuest
   $ npm install 
  ```
  
#### 3. Ganache
  - Open Ganache and click on settings in the top right corner.
  - Under **Server** tab:
    - Set Hostname to 127.0.0.1 -lo
    - Set Port Number to 8545
    - Enable Automine
  - Under **Accounts & Keys** tab:
    - Enable Autogenerate HD Mnemonic

#### 4. IPFS
  - Fire up your terminal and run `ipfs init`
  - Then run 
    ```
    ipfs config --json API.HTTPHeaders.Access-Control-Allow-Origin "['*']"
    ipfs config --json API.HTTPHeaders.Access-Control-Allow-Credentials "['true']"
    ipfs config --json API.HTTPHeaders.Access-Control-Allow-Methods "['PUT', 'POST', 'GET']"
    ```

    > Note: If you face any issues with the above command on windows, try using command prompt and escape sequences or git bash.
#### 5. Metamask
  - After installing Metamask, click on the metamask icon on your browser.
  - Click on __TRY IT NOW__, if there is an announcement saying a new version of Metamask is available.
  - Click on continue and accept all the terms and conditions after reading them.
  - Stop when Metamask asks you to create a new password. We will come back to this after deploying the contract in the next section.
  
#### 6. Smart Contract

1. Install Truffle using `npm install truffle -g`
2. Compile Contracts using `truffle compile`

#### 7. Starting your local development blockchain
  - Open Ganache.
  - Make sure to configure it the way mentioned above.
    7.1. Open new Terminal and deploy contracts using `truffle migrate`

#### 8. Local server

1. Install Node lite-server by running the following command on your terminal `npm install -g lite-server`

#### 9. Run Locally
  * Move back to the parent directory by cd..
  * While you are still inside the cloned folder, write the following command to run the website locally.
 
 ```
   $ npm run dev
 ```
 
 
 ###### NOTE: After performing all the steps give a few seconds for frontend to load and the port by default will be ```http://localhost:3000/```
=======
# SecureQuest---Question-Paper-Leakage-Prevention-Using-Blockchain-
>>>>>>> 27e7c721c0f578d40e2f990b301cbaeea04dba15
