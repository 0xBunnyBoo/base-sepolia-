curl --request POST \
  --url https://api.neynar.com/v2/farcaster/fungible/send/ \
  --header 'Content-Type: application/json' \
  --header 'x-api-key: <api-key>' \
  --header 'x-wallet-id: <x-wallet-id>' \
  --data '{
  "network": "base",
  "fungible_contract_address": "0x833589fcd6edb6e08f4c7c32d4f71b54bda02913",
  "recipients": [
    {
      "fid": 3,
      "amount": 1.00000001
    }
  ]
}'
