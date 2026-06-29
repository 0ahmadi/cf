# cf


## Setup
 
```bash
git clone https://github.com/dwrrio/cf.git
cd cf
chmod +x cf
sudo mv cf /usr/local/bin/cf
pip install requests
```

## Usage
 
```bash
cf 282/A      # fetch samples + open solution.cpp in vim
cf test       # compile, run all tests → CORRECT or show failing case
cf add 1      # manually add a test case (paste input/output, then Ctrl-D)
```
