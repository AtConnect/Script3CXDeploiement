# Script déploiement Centreon pour 3CX

This script has been writed by Kévin Perez for AtConnect Anglet

![asciicast](http://www.atconnect.net/images/header/logo.png)
![image](https://image.noelshack.com/fichiers/2019/17/3/1556112297-telechargement.png)

## Compatible with Debian 7/8/9 only.
#### Need Bash 4.2 at least to run.

# Step 1 - Run update and install git
```
apt-get update && apt-get install git-core -y && apt-get install curl -y

```
# Step 2 - Clone the repository and install it
```
cd /tmp
git clone https://github.com/AtConnect/Script3CXDeploiement
cd Script3CXDeploiement
chmod a+x lancercescriptsur3cx.sh
./lancercescriptsur3cx.sh
```


## Versions
- **1.0** Kévin Perez
  - *New:* Repository added
