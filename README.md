# Deep-Crypto-Tools-revamped
A set of scripts for detailed cryptanalysis of the Blockchain network in cryptocurrency Bitcoin taken from demining DeepCryptoTools and updated so it actually works 
* Open Our [Terminal for Google Colab](https://github.com/demining/TerminalGoogleColab)
* Create a folder "Blockchain"
* Run script [getrawtx.sh]

## Commands:

    git clone https://github.com/demining/CryptoDeepTools.git

    cd 01BlockchainGoogleDrive/

    chmod +x getrawtx.sh

    ./getrawtx.sh git clone https://github.com/demining/CryptoDeepTools.git

    cd 01BlockchainGoogleDrive/

    chmod +x getrawtx.sh

    ./getrawtx.sh bc1qgrtzmk5fuw7h700zhadps57fuxsx8ut60vvu6h

*Next, change the Bitcoin Address to any.*
## Parsing Blockchain in Google Drive, we need to use Google Colab to log in

## All content will be saved in a file: "RawTX.json"## Analyze the data from the file "RawTX.json" (which we received in [01BlockchainGoogleDrive](https://github.com/demining/CryptoDeepTools/tree/main/01BlockchainGoogleDrive))

Script breakECDSA.py reconstructs the signed message for each to find the Z value. The result is returned as R, S, Z, PUBKEY for each of the inputs present in the data in the "RawTX.json" file
*Runscriptgetsigh.sh 

## Commands:
    
    cd CryptoDeepTools/02BreakECDSAcryptography/
    
    sudo apt install python3
    
    wget https://bootstrap.pypa.io/pipx/get-pip.py
    
    sudo python3 get-pip.py
    
    pipx install  requirements.txt

    chmod +x getsign.sh
    
    ./getsign.sh

---
### All content will be saved in a file: "signatures.json"



