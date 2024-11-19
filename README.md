# CharityFundDistribution

This project is a blockchain-based charity fund distribution system that leverages smart contracts to ensure transparency and accountability.

## Requirements
1. A supported web browser:
   - Google Chrome
   - Microsoft Edge
   - Mozilla Firefox, etc.
2. MetaMask Browser Extension:
   - [Install MetaMask](https://metamask.io/)
     
3. Ganache (Local Blockchain):  
   - [Download and install Ganache](https://trufflesuite.com/ganache/).  

4. Node.js and npm:  
   - [Download and install Node.js](https://nodejs.org/).  
   - npm is included with Node.js.  


## Setup Process

### 1. Clone the Repository
Clone the project into your local machine using the following command:
```bash
git clone https://github.com/teja-naidu/CharityFundDistribution.git

###2. Install Dependencies
Navigate to the project folder and install the required Node.js modules:
'''bash
cd CharityFundDistribution
npm install

###3. Compile and Deploy the Contracts
Use the Truffle framework to compile and deploy the smart contracts:
'''bash
truffle compile

Setting Up Your Local Blockchain Environment
Ganache Configuration
Ganache acts as your personal local blockchain environment for development and testing.

1. Create a Workspace
Launch Ganache.
Click "New Workspace".
Assign a meaningful name, such as CharityChain-Dev.
2. Link Your Project
Locate the truffle-config.js file in the project directory.
Add this file to your workspace in Ganache.
This step connects your project to the local blockchain.
3. Configure the Workspace
Set the port in Ganache to 7545.
Ensure the port matches the configuration in your truffle-config.js file.
