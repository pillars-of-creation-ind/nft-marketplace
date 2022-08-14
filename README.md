### Full Stack NFT Metaverse Marketplace

> Building a digital marketplace with Polygon, Next.js, Tailwind,
> Solidity, Hardhat, Ethers.js, and IPFS

- Web application framework - _Next.js_
- Solidity development environment - _Hardhat_
- File Storage - _IPFS_
- Ethereum Web Client Library - _Ethers.js_

Features:

- _NFT Contract_ - This contract allows users to mint unique digital assets.
- _Marketplace Contract_ - This contract allows users to put their digital
  assets for sale on an open market.

---

NextJS

```bash
npx create-next-app digital-marketplace

```

Packages

```bash
npm install ethers hardhat @nomiclabs/hardhat-waffle \
ethereum-waffle chai @nomiclabs/hardhat-ethers \
web3modal @openzeppelin/contracts ipfs-http-client@50.1.2 \
axios
```

## Tailwaind

Installation

```bash
npm install --save-dev tailwindcss@latest postcss@latest autoprefixer@latest

```

Setup

```bash
npx tailwindcss init -p
```

| tailwind.config.js

```bash
module.exports = {
  content: [
    "./pages/**/*.{js,ts,jsx,tsx}",
    "./components/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

| styles/globals.css

```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```

```bash
# Project reference
https://www.youtube.com/watch?v=7Q5E6RvLlUw

# UI's
https://github.com/codingwithmuhib/React-NFT-Website
https://www.youtube.com/watch?v=edr2o59Twrs
```
