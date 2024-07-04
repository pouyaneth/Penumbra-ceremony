![group-of-people-in-the-catholic-church-on-a-dark-background-with-smoke-secret-society-ceremony-people-in-hoods-praying-together-members-of-sect-perform-the-ritual-in-dark-ai-generated-free-photo](https://github.com/pouyaneth/Penumbra-ceremony/assets/87922204/6dae5f4f-d1df-4f60-a77d-125fe0e5d083)

# Introduction to the Penumbra Project

The Penumbra Project is a cutting-edge initiative focused on developing a modular and Fully Homomorphic Encryption (FHE) network within the Cosmos ecosystem. Its primary goal is to enable private and anonymous transactions, offering enhanced privacy features for users. Penumbra aims to provide a secure environment for confidential asset management and transactions, integrating seamlessly with other blockchain networks in the Cosmos ecosystem.

---

# Penumbra Ceremony Phase 2

# dependencies
```
sudo apt-get update && sudo apt-get upgrade -y 
sudo apt-get install curl 
sudo apt-get install build-essential glibc-source pkg-config libssl-dev clang git-lfs -y
```

# Installing Penumbra

```
#Install
curl --proto '=https' --tlsv1.2 -LsSf https://github.com/penumbra-zone/penumbra/releases/download/v0.77.2/pcli-installer.sh | sh

source $HOME/.cargo/env

#Check if installed correctly

pcli --version
```

# Wallet
```
#Import old wallet
pcli init soft-kms import-phrase

#OR

#Create new wallet (Save seed phrase if you created a new one)
pcli init soft-kms generate
```
```
#sync wallet
pcli view sync
```
```
#Check address
pcli view address 0
```

**Now go and get some faucet from discord's #-testnet-faucet channel(get as much as you can)**

# Ceremony
```
#Open screen
screen -S pe

#start Ceremony
pcli ceremony contribute --phase 2 --bid 99penumbra
```
Press Ctrl + A + D

**for reattaching the screen use**
```
screen -r pe
```

** if you wanna restart the ceremony in any case**
```
pcli ceremony contribute --phase 2 --bid 0penumbra
```

**ceremony dashboard**

https://summoning.penumbra.zone/


**If you do it right it'll give you a slot number and a transcript hash
take a screenshot, copy them and tweet it with tagging Penumbra twitter and at last fill this form.**

https://form.asana.com/?k=THhk7qmp3IDwCvXWTPHkow&d=1206052071402903








