# ⚡ Custom ERC-20 Token Smart Contract

This repository contains a fully functional and customizable **ERC-20 token** implementation built with Solidity and OpenZeppelin. It's ideal for learning, prototyping, or launching your own cryptocurrency project on Ethereum.

---

## 📦 Features

- ✅ Standard ERC-20 compliance
- 🔐 Secure implementation via OpenZeppelin (v5.3.0)
- 🔁 Includes `transfer`, `approve`, `transferFrom`, `mint`, `burn`
- 🧱 Easily extendable for custom logic
- 🛡 Uses Solidity 0.8.20 with safe math and typed errors

---

## 🧾 Contract Summary

This contract is based on the OpenZeppelin ERC-20 template. You can inherit this base and call `_mint()` in your constructor or deployment script to create your token supply.

### Key Functionalities:

| Function            | Purpose                                           |
|---------------------|---------------------------------------------------|
| `name()`            | Token name                                        |
| `symbol()`          | Token symbol (short name)                         |
| `decimals()`        | Returns 18 (standard for most tokens)             |
| `totalSupply()`     | Total number of tokens in circulation             |
| `balanceOf()`       | Get balance of any wallet address                 |
| `transfer()`        | Send tokens to another address                    |
| `approve()`         | Allow another address to spend on your behalf     |
| `transferFrom()`    | Transfer using allowance set by `approve()`       |
| `_mint()`           | Create new tokens (internal use)                  |
| `_burn()`           | Destroy tokens from a wallet (internal use)       |

---

## 🧱 Folder Structure
