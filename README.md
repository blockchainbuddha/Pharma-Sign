# Pharma-Sign

Project for preventing prescription fraud using the Ethereum blockchain, as part of the "Hack the Epidemic" hackathon co-sponsored by ConsenSys Health and Booz Allen Hamilton (October 12-14, 2018).

## Mission statement

To prevent fraud, reduce costs, and improve experiences for Providers, Pharmacies, and Patients in the prescription issuance process.

## Key Features

- Fill out prescription data via ReactJS web form
- Encrypt prescription data with pharmacy's public key
- Upload encrypted prescription data to IPFS
- Store the IPFS location hash in smart contract on ETH-public
- Encode address of ETH-public smart contract in QR code

## Planned

- Add Truffle/JS tests to ensure successfull encryption and decryption of prescriptions
- Validate preferred pharmacy against External Pharmacy Registry via smart contract
- Validate doctor's National Provider Identifier (NPI) number against External Provider Registry
- Enforce prescription expiry date and number of refills

## Run the app

1.  Run `npm install`
2.  Run `npm start`

A local Ganache blockchain server will start concurrently for testing purposes.

## Contact

[Patrick](https://twitter.com/pi0neerpat)
