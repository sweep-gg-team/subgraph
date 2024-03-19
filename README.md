# Subgraph

We are using subgraphs to track the state of the contract. This is so we can use logs instead of using contract state to store some events.

## Quickstart
`curl https://goldsky.com | sh`

`goldsky login` Note, get the api key from albert

`goldsky subgraph deploy sweep-fpmm/1 --from-abi subgraph.json`
