# raptoreum-saltyminer
An open-source miner for the Raptoreum cryptocurrency with a simple user interface.

Welcome! I created this miner interface to be used in conjunction with the [cpuminer-gr] binaries.
Please note that this application might have a few bugs that need to be fixed. If you find any, feel free to open an issue on our GitHub.

*DISCLAIMER: The miner contains a 0.5% developer's fee for the user interface and a 1.75% developer's fee for the binaries.*
________________________________________________________________________________________________________________________________________________________________
**For new users:**

This miner is very simple and easy for newcomers. Here's the way to use it:

1. Enter your Raptoreum (RTM) address into the designated input field. You can get a wallet from:
https://github.com/Raptor3um/raptoreum/releases/tag/1.2.15.2
2. Enter your chosen pool into the designated input field. There are quite a few different ones you can choose from.
3. Enter the amount of cores you would like to run during the mining process.
4. Enter any additional information or arguements you would like to feed to the miner.
5. Choose the proper instruction set. This is absolutely required for the application to run properly.
6. Click the nice big green button and get to mining!
________________________________________________________________________________________________________________________________________________________________

**For developers or anyone who wants to modify the code:**

I wrote this UI wrapper using WinForms, along with C#. The application, when compiled, does not directly contain the binaries required to run the system.
Instead, the binaries are put into the temporary Binaries folder and then are copied into the release folder where the application is held. 
This happens when the new program is to be transfered over for a GitHub Release.
________________________________________________________________________________________________________________________________________________________________
If you would like to support us, feel free to donate below.

noahtheprogrammer:  `RWXmeVTEJYNVp2htJQ97DMYvwytWUFTi8E`

authrequest: `RXrkvhFSYk9VBp7DzueLEZaGCpWB4nuTGT`
