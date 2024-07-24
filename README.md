# Swisstronik Tesnet Techinal Task 4 (Mint a PERC20 Token)

link : [Click!](https://www.swisstronik.com/testnet2/dashboard)


## Steps

### 1. Clone Repository

```bash
git clone https://github.com/arjuna2025/swisstronik_mint_PERC20
```

```
cd swisstronik-perc20-mint-token
```

### 2. Install Dependency

```bash
npm install
```

### 3. Set .env File

create .env file in root project

```bash
PRIVATE_KEY="your private key"
```

### 4. Update Smart Contract (Skipp if you won't modify Token name)

- Open contracts folder
- Open PERC20Sample.sol file
- Feel free to modify token name and token symbol

### 5. Compile Smart Contract

```bash
npm run compile
```

### 6. Deploy Smart Contract

```bash
npm run deploy
```

### 7. Mint Token

```bash
npm run mint
```

### 8. Transfer Token

```bash
npm run transfer
```

### 8. Finsihed

- Open the deployed-adddress.ts (location in utils folder)
- Copy the address and paste the address into testnet dashboard
- Open the tx-hash.txt (location in utils folder)
- Copy the address and paste the tx hash link into testnet dashboard
- push this project to your github and paste your repository link in testnet dashboard


