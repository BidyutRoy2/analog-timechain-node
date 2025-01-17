
# VPS Requirements

```bash
RAM : 16 GB
CPU : 8 cores
Disk : 300 GB NVME SSD
Bandwidth : 500 Mb/s
```
- You can buy VPS from [PQ Hosting](https://pq.hosting/?from=557648)

# Wallet Set Up & Request Faucet

- Download [Fearless Extension](https://chromewebstore.google.com/detail/fearless-wallet/nhlnehondigmgckngjomcpcefcdplmgc)
- Create a new wallet
- Join [Analog Discord](https://discord.gg/analog)
- Request faucet in `🚰| faucet` channel by using below mentioned command
```bash
!faucet your..analog..wallet..address..here
```
# Deployment

https://github.com/dxzenith/analog-timechain-node/assets/161211651/3e1cc4b9-5494-4dd7-ac04-9029daaa6103

- Open Termius / Putty
- Paste this below mentioned command
```bash
wget https://raw.githubusercontent.com/BidyutRoy2/analog-timechain-node/main/analog.sh && chmod +x analog.sh && ./analog.sh
```
- You can check analog node logs by using this command :
```bash
docker logs analog
```

# Validator Setup
- Visit : [This Site](https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Frpc.testnet.analog.one#/staking/actions)
- Click on `Validator` option in the top right corner
- In `stash account` select your analog wallet and keep other details as default
- Click next button
- Write your `rotate key` in `keys from rotatekeys` section
- You can write 1 to 10 in `reward commission percentage` section
- Then click on `Bond & Validate`

# Submit Whitelist Form
- Submit this [Form](https://l5d87lam6fy.typeform.com/to/kwlADm6U?typeform-source=docs.analog.one) with proper details and wait for the approval from Analog team
