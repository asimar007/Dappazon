# Dappazon

Dive into the future of shopping with Dappazon, a Web 3.0 Amazon Clone. Harnessing Solidity, Ethers.js, React.js, and Hardhat, alongside IPFS for image storage, we're reshaping e-commerce for transparency, security, and innovation. Join us in building the future of shopping! 🛍️💻

![Dappazon img.png](https://github.com/asimar007/Cross-Region-Migration-of-AWS-EBS-Volumes/blob/main/Screenshot/Dappazon%20img.png?raw=true)

## Technology Stack & Tools

- Solidity (Writing Smart Contracts & Tests)

- Javascript (React & Testing)

- [Hardhat](https://hardhat.org/) (Development Framework)

- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)

- [React.js](https://reactjs.org/) (Frontend Framework)

## Setting Up

### 1. Clone/Download the Repository

```

git clone https://github.com/asimar007/Dappazon



cd Dappazon

```

### 2. Install Dependencies:

```

npm install

```

### 3. Run tests

```

npx hardhat test

```

### 4. Start Hardhat node

```

npx hardhat node

```

### 5. Run deployment script

In a separate terminal execute:

```

npx hardhat run ./scripts/deploy.js --network localhost

```

- Change `config.js` file and put your contract address
  ```
  {
  "31337": {
  "dappazon": {
  "address":  "Your Contract address"
  			}
  		}
  }
  ```

### 6. Start frontend

```

npm run start

```
