# Pre-requisites:
 Truffle,
 Ganache,
 Metamask
 

# Steps to setup testnet environment :
 
 1. Install [ganache](https://trufflesuite.com/ganache/) and start it up.
 2. Install metamask extension in your preferred browser.

 3. Run the ganache, and copy the rpc url and chain id

 4. Add network manually in metamask using the copied rpc url and chain id with any name and symbol
  
   <img src="https://i.imgur.com/r06xxjK.png" width="450">

 5. Switch to the added network.
 
 6. Copy private keys from ganache from any of the account and import it to metamask.
   
   <img src="https://i.imgur.com/HM345ms.gif" width="550">
   
   <img src="https://i.imgur.com/28plGPk.gif" width="550">


# Steps to setup project from github :

1. Create a new folder to store the project

2. Open a administrator command prompt and cd into the newly created folder.

3. Clone the project

 ```
 git clone git@github.com:IronicDeGawd/Product_Detection_with_Documentation.git
 ```

4. Follow the comamands:n
   
   ```
   npm install                  // to install npm modules
   
   npm install -g truffle       // command to install truffle
   
   truflle migrate --reset      // truffle to command reset deployed smart contracts
  
   cd client     
   
   npm install
   
   npm install --global yarn   //command to install yarn
   
   yarn build
   
   yarn global add serve
   
   npm run start
   ```
   
   
   
   
