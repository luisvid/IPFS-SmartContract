Para instalar

npm install

Arrancar Ganache y conectar MetaMask

Para compilar smart contract

truffle compile
truffle migrate

Para probar smart contract desde la consola

truffle console
const meme = await Meme.deployed()
meme.set("abcd1234")
memeHash = meme.get()

Para arrancar server de prueba de la webapp

npm run start
