# Blockchain App Builder VSCode Extension
1. Search in Google for ***Oracle Live Labs***.
<p align="center"  alt="find oracle live labs">
<img width="577" height="212" src="https://github.com/antoniogomezr/Visual-Builder-Oracle-Blockchain/blob/main/images/2-dev-2-1.png"/>
</p>

2. Push the first link, and in the Oracle LiveLabs page search for ***Low Code Blockchain*** labs.
<p align="center"  alt="Select The compartment where the instance of the founder organization will be created">
<img width="860" height="390" src="https://github.com/antoniogomezr/Visual-Builder-Oracle-Blockchain/blob/main/images/2-dev-2-2.png"/>
</p>

3. Select the ***Developing Low Code Blockchain Applications using Apex and Blockchain App Builder*** lab.
<p align="center"  alt="Select The compartment where the instance of the founder organization will be created">
<img width="328" height="273" src="https://github.com/antoniogomezr/Visual-Builder-Oracle-Blockchain/blob/main/images/2-dev-2-3.png"/>
</p>

4. Push the ***Star*** button to start the lab, and the select the only option you have to execute this lab ***Run on your tenant***.
<p align="center"  alt="Select The compartment where the instance of the founder organization will be created">
<img width="954" height="330" src="https://github.com/antoniogomezr/Visual-Builder-Oracle-Blockchain/blob/main/images/2-dev-2-4.png"/>
</p>

5. Once you are inside the Lab, to get a cloud machine ready whith Visual Code Studio, and with the AppBuilder low code plugin installed on it, you only need to execute step 1 on the ***Prepare Setup*** and ***Environment Setup*** steps, which should not take more than 25 minutes in total. 
<p align="center"  alt="Select The compartment where the instance of the founder organization will be created">
<img width="790" height="525" src="https://github.com/antoniogomezr/Visual-Builder-Oracle-Blockchain/blob/main/images/2-dev-2-5.png"/>
</p>

If you are new on OCI, no VNC will be available so you will need to create it.

5.1. On the on the ***Prepare Setup***, you will only need to execute step 1.
<p align="center"  alt="Select The compartment where the instance of the founder organization will be created">
<img width="790" height="525" src="https://github.com/antoniogomezr/Visual-Builder-Oracle-Blockchain/blob/main/images/2-dev-2-6.png"/>
</p>

5.2. On the ***Environment Setup*** follow Task 1A.
<p align="center"  alt="Select The compartment where the instance of the founder organization will be created">
<img width="790" height="525" src="https://github.com/antoniogomezr/Visual-Builder-Oracle-Blockchain/blob/main/images/2-dev-2-7.png"/>
</p>

6. After all the work done, you will get the URL of the remote desktop to access your VS with Oracle Blockchain extension installed.
<p align="center"  alt="Select The compartment where the instance of the founder organization will be created">
<img width="790" height="525" src="https://github.com/antoniogomezr/Visual-Builder-Oracle-Blockchain/blob/main/images/2-dev-2-8.png"/>
</p>

This should take you directly to your remote desktop in a single click.
<p align="center"  alt="Select The compartment where the instance of the founder organization will be created">
<img width="790" height="525" src="https://github.com/antoniogomezr/Visual-Builder-Oracle-Blockchain/blob/main/images/2-dev-2-10.png"/>
</p>

7. Once in your environment, open a terminal an execute "code" that will open Visual Studio.
<p align="center"  alt="App Builder in VSCode">
<img width="840" height="525" src="https://github.com/antoniogomezr/Visual-Builder-Oracle-Blockchain/blob/main/images/2-dev-2-11.png"/>
</p>

8. Your Blockchain App Builder VSCode Extension should be 22.4.3 and Go version 1.18.5.

8.1. Check go version and if it is not 1.18.5 download from http://go.dev/dl/go1.18.5.linux-amd64.tar.gz

8.2. If Blockchain App Builder VSCode Extension is not 22.4.3 you will need to unistalled and installed from oracle-ochain-extension-22.4.3.vsix file.

8.3. Once intalled, you should get this information from the VS Extension management module.
<p align="center"  alt="App Builder in VSCode">
<img width="840" height="525" src="https://github.com/antoniogomezr/Visual-Builder-Oracle-Blockchain/blob/main/images/2-dev-2-12.png"/>
</p>

9. If you don't have an Oracle Blockchain Cloud Service environment set up:
9.1. You can locally execute tasks from 4 to 8 from the live lab and also locally test the chaincode.
<p align="center"  alt="App Builder in VSCode">
<img width="840" height="525" src="https://github.com/antoniogomezr/Visual-Builder-Oracle-Blockchain/blob/main/images/2-dev-2-13.png"/>
</p>

9.2. You can also locally execute examples from @jvillenap github, always locally so NOT going through deployment into Founder or Participant steps:

https://github.com/jvillenap/Using-NFT-and-FT-Tokens-in-Oracle-Blockchain/tree/main/03-Creation-and-Deployment-of-an-FT-SmartContract
https://github.com/jvillenap/Using-NFT-and-FT-Tokens-in-Oracle-Blockchain/tree/main/04-Creation-and-Deployment-of-an-NFT-SmartContract
