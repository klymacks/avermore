# avermore
Optimized AMD miner for x16r / x16s
Original repo:
https://github.com/brian112358/avermore-miner
# Usage
## Windows
sgminer.exe -k x16r -o stratum+tcp://rvn-eu1.nanopool.org:12222 -u YOUR_ADDRESS/YOUR_WORKER_NAME/YOUR_EMAIL -p x -o stratum+tcp://rvn-eu2.nanopool.org:12222 -u YOUR_ADDRESS/YOUR_WORKER_NAME/YOUR_EMAIL -p x -X 256 --log-file "log.txt"

## Linux
./sgminer -k x16r -o stratum+tcp://rvn-eu1.nanopool.org:12222 -u YOUR_ADDRESS/YOUR_WORKER_NAME/YOUR_EMAIL -p x -o stratum+tcp://rvn-eu2.nanopool.org:12222 -u YOUR_ADDRESS/YOUR_WORKER_NAME/YOUR_EMAIL -p x -X 256 --log-file "log.txt"

# bitcointalk link
https://bitcointalk.org/index.php?topic=3330680.msg34813230

# Dev fee
Dev fee is set to 1%
