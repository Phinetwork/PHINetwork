# 📃 Deploy a Smart Contract

If you are new to the space, we recommend using **Remix IDE** to develop, compile, and deploy your contracts. It has one of the most intuitive UIs amongst the existing EVM IDEs compatible with PHI Network, making the experience effortless.You can access it using your browser: [https://remix.ethereum.org/](https://remix.ethereum.org/)​

**Requirements:**

* A desktop or laptop computer
* MetaMask or another browser based wallet
* Enough PHI to pay for the gas fees

### Step 1: Create Your Project/File <a href="#step-1-create-your-project-file" id="step-1-create-your-project-file"></a>

Once in Remix, create a new file/folder using the icons below your workspace dropdown (see below). Make sure your file name includes the the '.sol' extension, so it’s recognized as a Solidity file. Once the file is created, all you need to do is start putting together your code. You can copy our open-source code for a simple PHI20 token in our [**Classic PHI-20 Token**](smart-contract-examples/classic-phi-20-token.md) page if you need a starting point.![](https://1479452965-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Fw8N76RudwAt1Iyty0Cmd%2Fuploads%2Fb2chSshOzv5jWlNWdT5p%2FScreenshot%202022-02-07%20095729.jpg?alt=media\&token=81b1699a-ef1f-4407-b9d1-ed89a3e1e6e7)

### Step 2: Compile <a href="#step-2-compile" id="step-2-compile"></a>

Once you have finished coding, you will have to compile your contract. To do so, click on the 'Compile' button on the left-hand side menu on Remix. Make sure that the Solidity version specified in the contract matches the Solidity version of your compiler. When you’re satisfied with your code and your compiler is set up, simply press the compile button.![](https://1479452965-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Fw8N76RudwAt1Iyty0Cmd%2Fuploads%2FW9purFdBe0MS2LHvCUcn%2FScreenshot%202022-02-07%20100042.jpg?alt=media\&token=ed13da47-715a-45b8-93ca-28bee42a4dd1)

### Step 3: Deploy <a href="#step-3-deploy" id="step-3-deploy"></a>

Once you have compiled your contract successfully, it's time to deploy! First, change the 'Environment' dropdown to **Injected Web3**, so that Remix sends the transaction to your browser wallet, rather than your localhost. With that done, make sure to fill any required fields from your smart contract compilation using the 'Contract' dropdown - in this example, specifying the name of the token, symbol, and decimals - and then click on 'Transact' to send the deployment transaction to your wallet.![](https://1479452965-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Fw8N76RudwAt1Iyty0Cmd%2Fuploads%2FFYok5ql0XD4Px6OYdQGm%2FScreenshot%202022-02-07%20100112.jpg?alt=media\&token=8fc3fc3e-3231-48aa-9340-8b5aa59eeb5d)Once confirmed, it will be sent to the blockchain, and Remix will provide you a 'Success' message, along with your newly created contract address.![](https://1479452965-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Fw8N76RudwAt1Iyty0Cmd%2Fuploads%2FHsRpK9oOPl8zh04euLo5%2FScreenshot%202022-02-07%20104815.jpg?alt=media\&token=af4d5a55-945e-40c9-b711-8f3048b0ac89)****

**All done!** Now you have your contract and can start using it straight away. To add it to your MetaMask or any browser wallet, copy the address, click on 'Import Token' on your wallet, and paste it there.
