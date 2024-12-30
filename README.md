# RSA: Encryption and Decryption using NTL (Number Theory Library) on Linux
This project is an implementation of an RSA encryption and decryption using NTL which is a library for doing Number Theory.

# Requirements
1. The NTL library installed.
2. Linux system (e.g Ubuntu and Kali).

### Install NTL
Follow these steps on Linux to install.
#### Update the Package List
Open terminal and run:
```bash 
sudo apt update
```
#### Install the NTL Library
Run the following command:
```bash 
sudo apt install -y libntl-dev
```
#### Verify the Installation
Verify that the NTL library is installed by running:
```bash 
ldconfig -p | grep ntl
```
#### Optional: Compile from Source (If Needed)
If the pre-built package doesn’t meet your needs, you can compile NTL from source:
Download the latest version:
```bash 
wget https://www.shoup.net/ntl/ntl-latest.tar.gz
```
Extract the archive:
```bash 
tar -xvzf ntl-latest.tar.gz
cd ntl-<version>
```
Configure, compile, and install:
```bash 
./configure
make
sudo make install
```
#### Verify Installation Again
Ensure the library is now available:
```bash 
ldconfig -p | grep ntl
```

