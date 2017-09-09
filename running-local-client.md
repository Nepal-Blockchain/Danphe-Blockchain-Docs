#Running Local Client

Extract your client to new folder.
eg. `D:\Danphe\geth-windows-4.0-amd64.exe`

Rename client file to short `geth.exe`

##Start 
Use this command to connect with https://web3.danphe.network & other web3 socket clients
>`geth.exe --danphe --identity "YOURNAME" --ws --wsorigins "*" --ethstats "YOURNAME:DaNpHeMoNaL@stats.danphe.network" console`↵
You can edit & save this command as `start.bat` file inside `D:\Danphe\start.bat`  
#### Flags description
1. `--danphe`(required): Switch to Danphe Blockchain. 
2. `--identity "YOURNAME"` : Set your node's identity/name to ~~YOURNAME~~ 
3. `--ws` : Start websocket API
4. `--wsorigins "*"` : Accept all websocket origins
5. `--ethstats "YOURNAME:DaNpHeMoNaL@stats.danphe.network"` : Connect your node to [Stats Server](https://stats.danphe.network).
6. `console` : Start Geth JavaScript console.


