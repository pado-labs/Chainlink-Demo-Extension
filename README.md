# Chainlink-Demo-Extension
This is a demo code base for the Chainlink Hackathon. In general, a user can use this extension to retrieve his token balance from a CEX and prove that its value is greater than X. This proof will be submitted to the smart contract via the [EAS](https://attest.sh/) attestation framework.

There will be a dApp (smart contracts) to check the token price via Chainlink functions, where the DON-hosted secret management manages the API key. 
The dApp will check the amount threshold with the proof, and together with the price from the functions, to determine the eligibility of the particular user.

Typical examples could be rewarding a community NFT, fee discount or MEME to an off-chain token holder, for whose holdings are not analyzable unlike on-chain addresses.

## Compile

npm install
npm run build

## Running

1. Access `chrome://extensions/`
2. Check `Developer mode`
3. Click on `Load unpacked extension`
4. Select the `build` folder.
