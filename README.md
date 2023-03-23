# KYC-MANAGEMENT-USING-BLOCKCHAIN

Any firm today, especially those in the financial sector, must prioritise a deeper understanding of its client's financial transactions. KYC is a procedure used to confirm a customer's identification and other pertinent information. The existing KYC procedure has a serious financial entity since it necessitates a separate ledger for each of the several financial firms.
Each institution has its own KYC procedure, which occasionally may involve a third party and may result in increased maintenance expenses, delays, and redundancies. According to an economic survey, there is a significant amount of money lost in the form of opportunity expenses, maintenance costs, customer verification fees, and many more. The customer experience is negatively impacted by the lengthy KYC process currently in place. To augment the current KYC system, we have suggested a more advanced blockchain-based KYC solution.
Also, it raises customer ownership and raises customer satisfaction. It not only shortens the time required and solves the issue of updating documents, but it also saves money on opportunity costs, aggregation costs, maintenance costs, and a host of other expenses that can have an impact on an organization's performance.

# STEPS TO RUN 

1. Download Node version 10.15.3 from given link below

   https://nodejs.org/dist/v10.15.3/node-v10.15.3-x64.msi

2. Download npm version 6.9.0 

   open cmd and type command
   ```
   npm install -g npm@6.9.0
   ```

3. Check the node and npm version to setup the correct environment 

   open cmd type
   ```
   node --version 
   ```
   ```
   npm --version 
   ```
   if both are correct proceed further
   
4. Install the ethereum env 

   open cmd type 
   ```
   npm install -g ethereumjs-testrpc
   ```
   
5. Open the Folder in VScode and hit "ctrl+j" to open the terminal 

6. Install the solc & web3 

   open vs code terminal make sure you in the folder 
   
   ```
   npm install solc@0.4.26
   ```
   ``` 
   npm install web3@0.20.1
   ```
   
 7. Now start the eth. env in vscode
 
  ```
  testrpc
  ```
  
  Open another terminal now, 
  
  
 8. Start the node 
 
   ```
   node init.js
   ```
   
 9. An ethereum address will be generated this address will act as the admin to add the Banks Copy that Eth.Address and paste it in 
 js > contractDetails > var contractAddress = 'Your Eth. Address'; then "ctrl+s save" the file
 
 10. Open the index.html file with live server and there you go!!!


 11. Copy any of the available account and paste it in add bank portal in index.html with a name and login through it and perform various operations as in Add Kyc,     modify kyc, increase customer rating etc..
  
 
