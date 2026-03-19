# Charity-donation-Tracker-
A blockchain-based charity donation tracker built with Soroban on Stellar, ensuring transparent, secure, and traceable fund management.
<img width="1920" height="1080" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/efe02f6a-b257-4b8a-aacb-30df827ce5ed" />
# Charity Donation Tracker (Soroban Smart Contract)

## 📌 Project Description
The Charity Donation Tracker is a decentralized smart contract built on the Stellar Soroban platform. It enables transparent tracking of donations made by users to a charity. Each donor's contribution is securely recorded on-chain, ensuring trust, accountability, and immutability.

---

## ⚙️ What it does
This smart contract allows users to:
- Donate funds to a charity
- Track individual donation amounts
- View the total amount of donations collected

All records are stored on-chain using Soroban's persistent storage, making the system fully transparent and tamper-proof.

---

## ✨ Features
- 🔐 Secure donations with authentication
- 📊 Track individual donor contributions
- 📈 Calculate total donations in real-time
- 🌐 Fully decentralized and transparent
- ⚡ Built using Soroban smart contracts (Rust)

---

## 🛠️ Functions

### `donate(donor: Address, amount: i128)`
Allows a user to donate a specified amount. Requires authentication.

### `get_donation(donor: Address) -> i128`
Returns the total donation made by a specific donor.

### `get_total() -> i128`
Returns the total sum of all donations.

---

## 🚀 Deployed Smart Contract Link
🔗 https://stellar.expert/explorer/testnet/tx/48eb5ac7652b17ef5fb52999b4e5f92d17051923e34f5b97f878eee7f9602470
🔗 https://lab.stellar.org/r/testnet/contract/CAFV2WGHQM2FM4BSV7XXP7TR27BBVGIZ6XNUCOWZFBUK2LBREW57DPY6

---

## 🧪 How to Use

1. Deploy the contract on Stellar Soroban
2. Call `donate()` with your wallet address and amount
3. Use `get_donation()` to check your contribution
4. Use `get_total()` to view total funds raised

---

## 📚 Tech Stack
- Rust
- Soroban SDK
- Stellar Blockchain

---

## 📜 License
MIT License

