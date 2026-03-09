## Billion Towers - Project Proposal

**1. What I implemented:**

* The first card on the Marketplace now displays the price of 300 ETH, while the rest of the cards remain unchanged.
* Added the current ETH price at the top of the cards.
* Implemented a 10-second auto-update to fetch the latest ETH price (also added console logs since sometimes the price stays the same for a while and it can look like nothing is updating).
* All cards now convert and display their price based on the current ETH value and ETH/USD price.
* The first card changes background color based on price movement:
* Green when the price increases
* Red when the price decreases
* Other cards update the price as ETH changes but do not change background color.

**2. Extra (Web3 integration showcase):**
* Implemented wallet connection — clicking Connect Wallet opens MetaMask (or any installed browser wallet).
* Once connected, the wallet address appears in the header instead of the connect button.
* On the Market Details page, clicking Invest Now opens MetaMask with a pre-initiated transaction that the user can approve.
* Added these extras mainly to demonstrate a bit of Web3 integration alongside the task.
