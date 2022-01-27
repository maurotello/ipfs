# IPFS-SmartContract
Almacena un archivo en IPFS y el hash del archivo en un Smart Contract

### Para instalar

    npm install

### Arrancar Ganache y conectar MetaMask

### Para compilar smart contract
    
    $ truffle console --network ganache 
    truffle(ganache)> compile
    truffle(ganache)> migrate

### Para probar smart contract desde la consola

    truffle console
    const meme = await Meme.deployed()
    meme.set("abcd1234")
    memeHash = meme.get()

### Para arrancar server de prueba de la webapp

    npm run start

### Para ver la imagen en IPFS
https://ipfs.infura.io/ipfs/{hash de la imagen}
https://ipfs.infura.io/ipfs/QmcB9T61nmrm9UjXRxqLrg6ywSXFhBXzRhgXHBvSCGrYjN

https://ipfs.infura.io/ipfs/QmZouvxYLttBCoCMCJAm54WWcHACaeUpdBpsMG7MTz7eE8


## Info adicional sobre timestamp: Blockchain Federal Argentina

https://bfa.ar

https://t.me/bfatec (grupo de telegram)
    
- Sello de tiempo v1
    https://gitlab.bfa.ar/pkumagae/SmartContractsOTS/blob/master/ProofOfExistence.sol

- API REST - Sello de Tiempo v1
    (llamada a helper que crea hash)
    https://gitlab.bfa.ar/renn_um/tsa1/blob/master/api/helpers/get-ots.js
    https://gitlab.bfa.ar/renn_um/tsa1
    
- Sello de tiempo v2
    https://gitlab.bfa.ar/blockchain/nucleo/blob/master/src/Stamper.sol


