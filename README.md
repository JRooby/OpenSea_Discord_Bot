## Run locally

You can run this script locally by pulling the repo to your local machine.

First, install the dependencies with `npm` or `yarn`.

Then copy the `.env.example` file to `.env` and replace the example values with your own. Or set them in your environment manually.

The contract address for the NFT collection:
```
CONTRACT_ADDRESS=0x8943c7bac1914c9a7aba750bf2b6b09fd21037e0
```

The collection slug as found in the OS URL `https://opensea.io/collection/lazy-lions`:
```
COLLECTION_SLUG=lazy-lions
```

The Id of the discord channel to post sales to:
```
DISCORD_CHANNEL_ID=123456789101112130
```

You can also send to multiple channels by adding multiple IDs:
```
DISCORD_CHANNEL_ID=123456789101112130;123456789101738273;123456783649182736
```

The token from the discord bot you created above:
```
DISCORD_BOT_TOKEN=SBI1MDI0NzUyNDQ3NzgyOTEz.YF36LQ.Sw-rczOfalK0lVzuW8vBjjcnsy0
```

Your OpenSEA API token:
```
OPENSEA_TOKEN=some-key-here
```

 If you don't have one yet, [request for an API token](https://docs.opensea.io/reference/request-an-api-key).

Then just run the code!
```
$ yarn ts-node ./checkSales.ts
// or
$ ts-node ./checkSales.ts
```
