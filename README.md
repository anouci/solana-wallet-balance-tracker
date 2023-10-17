# Solana Wallet Balance Tracker 💼 🔍

An intuitive dashboard harnessing the [Mobula API](https://developer.mobula.fi/reference/metadata-api) to display Solana wallet balances in real-time.

![Solana/Mobula Logo](https://i.imgur.com/v4J2tK6.png)

---

## Table of Contents 📖

- [Features](#features-)
- [Usage](#usage-)
- [Dashboard Setup](#dashboard-setup-)
- [API Reference](#api-reference-)

---

## Features ✨

- **Real-time Balance Updates:** Seamless access to your Solana wallet balance updates.
  
- **Historical Data:** Track the historical balance of your Solana wallet with ease.

- **Secure and Reliable:** Powered by Mobula API for accurate and up-to-date information.

---

## Usage 💡

Simply input your Solana wallet address into the dashboard interface to get instant updates on your balance. In addition to real-time updates, delve into historical data, token distributions, and more!

---

## Dashboard Setup 🖥️

1. **Choose a Framework:** For beginners, a simple JavaScript framework like [Vue.js](https://vuejs.org/) can be an ideal choice. It offers a gentle learning curve and has extensive documentation.
2. **Fetch Data:** Use the provided Mobula API endpoint to fetch wallet balances. Axios is a recommended library for making HTTP requests in JavaScript.
3. **Display Data:** Visualize the fetched data using components or charts. Libraries such as [Chart.js](https://www.chartjs.org/) can be beneficial for this purpose.

---

## API Reference 🌐

Our dashboard predominantly utilizes the Mobula API's following endpoint:

- **Historical Balances:** 
  - **Method:** GET
  - **Endpoint:** `https://api.app-mobula.com/api/1/wallet/history`
  - **Description:** Get the historical balance of any EVM-compatible wallets, at any point in time.
  
More detailed information on this endpoint can be found in the official [Mobula API documentation](https://developer.mobula.fi/reference/getwallethistory). Simple as that!

---

### Crafted with ❤️ leveraging the capabilities of [Mobula API](https://developer.mobula.fi/)
