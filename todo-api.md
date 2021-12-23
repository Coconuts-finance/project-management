1. ~~Finalize APY calculations to mimic https://api.robo-vault.com/vault and allow the dapp display correct informations;~~ Done at /api/apys?network={network-id}
2. ~~Check refactorization of priceRepo.js / priceManager.js. The prices are requested to coingecko via the vaults/stakes declarations;~~
3. Clean code;
4. ~~Create a new route to retrieve vaults/stakes declarations in the dapp.~~ Done at /api/vaults?network={network-id}&type={stakes|vaults}
    - Refactorization is needed to exclude ABI from stakes list and include it "dynamically" when on the dapp;
5. Secure the API routes to access it only from the dapp;
