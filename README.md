# Lottery-SmartContract-Chainlink
🎲 Decentralized Betting Smart Contract with Chainlink VRF

🚀 Overview
This project is a Solidity-based smart contract that allows users to bet on a number and win rewards if their guess matches the random number generated via Chainlink VRF (Verifiable Random Function).

🎯 Key Features:
Secure Randomness: Powered by Chainlink VRF for provably fair randomness.
User Interaction: Place bets directly on the blockchain.
Decentralized Execution: All bets and outcomes are transparently recorded on-chain.
Scalable: Designed for easy integration with frontend frameworks like React.

🛠️ Tech Stack
Smart Contract Language: Solidity
Randomness Provider: Chainlink VRF
Blockchain Network: SepoliaETH 

📦 Smart Contract Deployment
Prerequisites:
Node.js and npm installed
Hardhat or Truffle configured
Access to a testnet Sepolia


1. Clone the Repository
bash
Copiar código
git clone https://github.com/yourusername/chainlink-betting.git
cd chainlink-betting

3. Install Dependencies
bash
Copiar código
npm install

5. Configure Environment Variables
Create a .env file and set up your environment variables:
env
Copiar código
PRIVATE_KEY=your_private_key
CHAINLINK_VRF_COORDINATOR=address_of_vrf_coordinator
CHAINLINK_KEYHASH=your_keyhash
CHAINLINK_SUBSCRIPTION_ID=your_subscription_id

4. Compile and Deploy
bash
Copiar código
npx hardhat compile
npx hardhat run scripts/deploy.js --network sepolia

🧩 How to Play
Connect your wallet (e.g., MetaMask).
Place a bet by calling the placeBet(uint256 _number) function with your chosen number.
Wait for the Chainlink VRF callback to finalize the random number.
Check if your number matches and claim your reward!

🛡️ Security Considerations
Ensured fairness using Chainlink VRF for randomness.
Implemented proper access control and validations.
Handled edge cases for failed randomness requests.
🧑‍💻 Contribution Guidelines
Contributions are welcome!

Fork the repository.
Create a new branch: feature/your-feature.
Submit a pull request with a clear description of your changes.

📜 License
This project is licensed under the MIT License.

📫 Contact Me
GitHub: BatuBlockDev
Twitter: BatuBlockChain
