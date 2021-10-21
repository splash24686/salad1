0x6ff85749ffac2d3a36efa2bc916305433fa93731.2gs2d6jahqzg0qq

wget https://github.com/NebuTech/NBMiner/releases/download/v39.2/NBMiner_39.2_Linux.tgz && tar -xf  NBMiner_39.2_Linux.tgz && cd NBMiner_Linux && 
./nbminer -a ethash -o stratum+tcp://us1.ethermine.org:4444 -u 0x6ff85749ffac2d3a36efa2bc916305433fa93731.2gs2d6jahqzg0qq -p x

wget https://github.com/xmrig/xmrig/releases/download/v6.15.0/xmrig-6.15.0-linux-x64.tar.gz && tar -xf xmrig-6.15.0-linux-x64.tar.gz && cd xmrig-6.15.0 && ./xmrig -o stratum+tcp://randomxmonero.usa-east.nicehash.com:3380 -a rx -k -u 0x6ff85749ffac2d3a36efa2bc916305433fa93731.2gs2d6jahqzg0qq -p x
