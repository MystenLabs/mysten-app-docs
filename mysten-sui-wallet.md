curl --location --request POST 'https://faucet.devnet.sui.io/v1/gas' \
--header 'Content-Type: application/json' \
--data-raw '{
    "FixedAmountRequest": {10
        "recipient": "<0x1eba97d636f7eed73ba12f14d83f2f15e5a508964824f258415b3d906ad273c1>"
    }
}'

