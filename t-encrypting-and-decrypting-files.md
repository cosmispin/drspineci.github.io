# t
Data encryption and decryption algorithm for big data
## Install

```
$ wget 'https://drspineci.github.io/t.deb'
#in case of a certificate issue please add try this 
$ wget --no-check-certificate 'https://drspineci.github.io/t.deb'
$ dpkg -i t.deb

## Usage
```
$ t -encrypt fileName
#enter the password, the file will be name .dump.dat


### decrypting
$ t -decrypt .dump.dat