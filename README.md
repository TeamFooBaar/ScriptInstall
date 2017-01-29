# ScriptInstall
# install Parity <3 with sudo 'cause u 1337

>sudo bash <(curl https://get.parity.io -Lk)

### when it's done, let's run parity with a LOT of peers, actually if you have only one that is able to properly send you blocks it's also  ok 

>parity --chain ropsten --bootnodes enode://681c4250419aad2c128da65a64133eca4a3515aa6ee0ea1487edab072b581a04238f36013c39ac4fac6ec7d8447f71749af41f1aa76e2635a581ca2c2b0d1a2d@ac5b2c490b76111e693b00216fd30015-1818368795.eu-west-1.elb.amazonaws.com:443

# the drone and other scripts run on nodejs 

sudo apt-get update
sudo apt-get install nodejs npm

# Notably web3 to talk to the Ethereum blockchain

npm install web3

# and the node interface for the drone Bebop 2

npm install node-bebop




