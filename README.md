

# Build for Whive Cpu-miner for MacOs

### MacOS
Run the following commands in your mac terminal:
```bash

$ git clone https://github.com/xyephy/cpuminer-mc-yespower.git 

$ brew install curl

$ brew install autoconf

$ brew install automake

$ cd cpuminer-mc-yespower 

$ ./autogen.sh

$ ./nomacro.pl

$ ./configure CFLAGS="-O3 -march=native -funroll-loops -fomit-frame-pointer" 

$ make

```


# Run

### Mac
yespower solo mining example: ( -u for username -p password, change them to your own)
```bash
./minerd -a yespower -o http://127.0.0.1:1867 -u whive -p pass --coinbase-addr= <YOUR WHIVE ADDRESS>
```


