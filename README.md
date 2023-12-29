Sardis Blockchain Node    
## Usage/Examples

change directory to sardis-core by
```bash
cd sardis-core
```
then

Display help
```bash
./node-setup.sh --help
```
To create/install a validator node. Fresh first-time install
```bash
./node-setup.sh --validator 1
```
To run the validator node
```bash
./node-start.sh --validator
```
To create/install one RPC node. Fresh first-time install
```bash
./node-setup.sh --rpc
```
To run the RPC node
```bash
./node-start.sh --rpc
```
To get into a running node's interactive console/tmux session 
```bash
tmux attach -t node1
```
To exit/detach from an interactive console
```text
Press CTRL & b , release both keys, and press d
```