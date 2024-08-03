# Swisstronik Testnet 2.0 // Deploy Proxy.

Link : [Click!](https://www.swisstronik.com/testnet2/dashboard)

## Steps

### 1. Clone Repository

```bash
git clone https://github.com/ragilzy/swisstronik-deploy-proxy.git
```

```bash
cd swisstronik-deploy-proxy
```

### 2. Install Dependency

```bash
npm install
```

### 3. Set .env File

create .env file in root project

```bash
touch .env
```

add this to your .env file

```bash
PRIVATE_KEY="your private key"
```

### 4. Compile Smart Contract

```bash
npm run compile
```

### 5. Deploy Smart Contract

```bash
npm run deploy
```

### 6. Initialize Owner

```bash
npm run initialize
```

### 7. Add Issuer

```bash
npm run add-issuers
```

### 8. Get Issuers list

```bash
npm run list-issuers
```

### 9. Upgrade Smart Contract

```bash
npm run upgrade
```

### Finished.

Github  : [ragilzy](https://github.com/ragilzy)

Swisstronik Address Testnet 0xBD686f99674d8c96597f9B70a2e27EfF3c8BEF74
