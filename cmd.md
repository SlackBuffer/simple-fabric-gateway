
# Admin

export FABRIC_CFG_PATH=/home/ubuntu/go/src/github.com/hyperledger/fabric/_debug/sampleconfig
export CORE_PEER_ADDRESS=peer0.org1.example.com:7051
export CORE_PEER_LOCALMSPID=Org1MSP
export CORE_PEER_TLS_ENABLED=true
export CORE_PEER_TLS_CERT_FILE=/home/ubuntu/go/src/github.com/hyperledger/fabric/_debug/first-network-simple/crypto-config/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
export CORE_PEER_TLS_KEY_FILE=/home/ubuntu/go/src/github.com/hyperledger/fabric/_debug/first-network-simple/crypto-config/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
export CORE_PEER_TLS_ROOTCERT_FILE=/home/ubuntu/go/src/github.com/hyperledger/fabric/_debug/first-network-simple/crypto-config/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/ca.crt
export CORE_PEER_MSPCONFIGPATH=/home/ubuntu/go/src/github.com/hyperledger/fabric/_debug/first-network-simple/crypto-config/peerOrganizations/org1.example.com/users/Admin@org1.example.com/msp

# User1

export FABRIC_CFG_PATH=/home/ubuntu/go/src/github.com/hyperledger/fabric/_debug/sampleconfig
export CORE_PEER_ADDRESS=peer0.org1.example.com:7051
export CORE_PEER_LOCALMSPID=Org1MSP
export CORE_PEER_TLS_ENABLED=true
export CORE_PEER_TLS_CERT_FILE=/home/ubuntu/go/src/github.com/hyperledger/fabric/_debug/first-network-simple/crypto-config/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
export CORE_PEER_TLS_KEY_FILE=/home/ubuntu/go/src/github.com/hyperledger/fabric/_debug/first-network-simple/crypto-config/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
export CORE_PEER_TLS_ROOTCERT_FILE=/home/ubuntu/go/src/github.com/hyperledger/fabric/_debug/first-network-simple/crypto-config/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/ca.crt
export CORE_PEER_MSPCONFIGPATH=/home/ubuntu/go/src/github.com/hyperledger/fabric/_debug/first-network-simple/crypto-config/peerOrganizations/org1.example.com/users/User1@org1.example.com/msp

ll /home/ubuntu/go/src/github.com/hyperledger/fabric/_debug/first-network-simple/crypto-config/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/msp/crls

rm /home/ubuntu/go/src/github.com/hyperledger/fabric/_debug/first-network-simple/crypto-config/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/msp/crls/crl.pem

## peer channel list

ChainID ??????????????? localMsp???msp/mgnt ???????????????????????????????????????

- [x] ????????? localMsp ??????????????????????????????????????? peer ??? crl.pem ??????????????????????????????????????????????????? crl.pem ?????????????????????????????????

## peer channel getinfo -c mychannel

ChainID ?????????

- [ ] ??????????????????????????????????????????????????????

qscc/GetChainInfo