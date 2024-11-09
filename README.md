# Ocean Incentivized Node

Meet Ocean: Tokenized AI & Data


**COMPUTE-TO-DATA**
Shift the computation towards the data instead, and not vice versa. Coupled with Data NFTs and Datatokens, users can remotely leverage machine learning and AI without relocating their assets, paving the way for novel revenue streams. It enables people to sell private data while preserving privacy, as an opportunity for companies to monetize their data assets.

**Rewards Breakdown** :
🚀 Ocean Noders, we give you the detailed incentive breakdown: [Rewards Link](https://blog.oceanprotocol.com/ocean-nodes-incentives-a-detailed-breakdown-0baf8fc98001)

💻5,000 $FET/weekly reward pool, starting August 22

🔑How to earn:

→Maximize Uptime: Longer node activity = higher reward chances
→Collect ONBs: Stack all 3 ONBs for 2x multipliers
→Keep It Up: Consistent performance each week increases your earnings

Site : [Ocean](https://oceanprotocol.com/) | Docs : [Oceandocs](https://docs.oceanprotocol.com/) | X : [X.com](https://x.com/oceanprotocol) |

| **Hardware** | **Minimum Requirement** |
|--------------|-------------------------|
| **CPU**      | 1 Cores                 |
| **RAM**      | 2 GB                    |
| **Disk**     | 4 GB                    |


**Youtube Video Guide** : 

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/7CMaBFgaTl8/0.jpg)](https://www.youtube.com/watch?v=7CMaBFgaTl8)

# Prerequires
- Docker
- Docker Compose

# Run installation ocean node
```
mkdir ocean && cd ocean
source <(curl -s https://raw.githubusercontent.com/ryzwan29/ocean-node/quick-install.sh)
```
1. Do you have your private key for running the Ocean Node [ y/n ]: n
2. Do you want me to create a private key for you [ y/n ]: y
   **→save the private key**
4. Please provide the wallet address to be added as Ocean Node admin account: "INPUT YOUR EVM WALLET ADDRESS"
after that you can use custom ports or just press enter
5. once docker-compose.yml is generated, you can change the RPC to your trusted RPC provider like [INFURA](https://app.infura.io/) or [ALCHEMY](https://dashboard.alchemy.com/)

Edit **docker-compose.yml** using [video](https://youtu.be/7CMaBFgaTl8?si=IYmThBnaHrr0h-wD)

Infura RPC : https://app.infura.io/

Alchemy RPC : https://dashboard.alchemy.com/

Chainlist : https://chainlist.org/

Ocean Faucet : https://faucet.sepolia.oceanprotocol.com/

# Creat and Setup RPC

- Login to [Alchemy Dashboard](https://dashboard.alchemy.com/)
- Create new app:
```
Name: Ocean-Node
Description: Optional
Use Case: Infra & Tools

Chain:
- ETH
- Optimism
- Polygon

"Create Apps"
```
- Edit your docker compose file
```
nano docker-compose.yml
```
## Start your Ocean Node:
```
docker-compose up -d
```
### Check logs :
```
docker-compose logs -f
```

Check peer ID : change port respectively - http://<your_public_ip>:8000/dashboard/ 

Check Rewards : https://nodes.oceanprotocol.com/
