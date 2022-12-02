# work
SMARTCONTRACT IN STARKNET| PROTOSTAR | MAC OS  
Hello, in this topic I will teach you how to make the simplest smart contract in Starknet.

For this you need a Unix system (MacOs/Linux).

1. Install Protostar

curl -L https://raw.githubusercontent.com/software-mansion/protostar/master/install.sh | 
bash

2. Checking the version

protostar -v 

3 Create a project

protostar init

4. In the same folder, run

protostar build

5. Expand the contract

protostar deploy ./build/main.json --network testnet


6.Done
