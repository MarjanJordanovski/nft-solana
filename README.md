Distribuirani sistemi zasnovani na Blockchain tehnologiji - Master4.0

Koraci za pokretanje aplikacije:

- **Preuzeti kod iz repozitorijuma:** git clone --branch master https://github.com/MarjanJordanovski/nft-solana.git
- **Instalirati neophodne dependencies:** cd /nft-solana/js/packages/candy-machine-ui ,i potom pokrenuti komandu: yarn
- **U istom direktorijumu kreirati .env fajl sa sledecim env varijablama definisanim:** 
```
REACT_APP_CANDY_MACHINE_ID=7bXKTR9f95XUFw2WEM6zyXv3xrosSrWjLsoCWpackf3q
REACT_APP_SOLANA_NETWORK=devnet
REACT_APP_SOLANA_RPC_HOST=https://metaplex.devnet.rpcpool.com/
SKIP_PREFLIGHT_CHECK=true
```
- **Pokrenuti aplikaciju komandom iz istog direktorijuma:** yarn start
- **Otici na 127.0.0.1:5000**


