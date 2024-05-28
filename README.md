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

    chmod +x getbalance.sh

    ./getbalance.sh

    pip3 install numpy
    
    apt-get update

sudo apt-get install g++ -y

sudo apt-get install libgmp3-dev libmpfr-dev -y

wget https://ftp.openssl.org/source/old/0.9.x/openssl-0.9.8c.tar.gz

tar xfz openssl-0.9.8c.tar.gz

mv openssl-0.9.8c openssl-0.9.8c-vuln

cd openssl-0.9.8c-vuln

ls -lh

patch -p1 <../make-OpenSSL-0-9-8c-vulnerable-again.diff

./Configure linux-x86_64 shared no-ssl2 no-ssl3 no-comp no-asm

make depend all

cd /

ls

cd content
