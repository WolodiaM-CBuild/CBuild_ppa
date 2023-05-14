# Install ppa
```
curl -s --compressed "https://wolodiam-cbuild.github.io/CBuild_ppa/ubuntu/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/cbuild.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/cbuild.list "https://wolodiam-cbuild.github.io/CBuild_ppa/ubuntu/cbuild.list" 
sudo apt update
```
# Install CBuild backend
```
Firstly install ppa as described above, then run:
sudo apt install libcbuild
```
