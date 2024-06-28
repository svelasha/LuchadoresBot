# Luchadores.io OpenSea Sales Twitter Bot

A bot that monitors Opensea sales for the Luchadores.io collection & then posts them to Twitter.

## Donations

If you find this script/repo useful for your project, any ETH/Altcoin/NFT donations are greatly appreciated 🙏

Eth Address: [NelsonRodMar.eth](https://etherscan.io/address/0x770569f85346b971114e11e4bb5f7ac776673469)

![NelsonRodMar.eth QR Code](https://chart.googleapis.com/chart?chs=300x300&cht=qr&chl=0x770569f85346B971114e11E4Bb5F7aC776673469&choe=UTF-8)


## Requirements

- [Twitter Developer Account](https://developer.twitter.com/en/apply-for-access)


## Setup

- Clone/Fork/Copy this project to your local public/private git repo

- Create a Twitter Developer App (make sure you change it to have both read/write permissions)

Complete the env.dist information :

- **TWITTER_CONSUMER_KEY** - Your Twitter Developer App's Consumer Key
- **TWITTER_CONSUMER_SECRET** - Your Twitter Developer App's Consumer Secret
- **TWITTER_ACCESS_TOKEN** - The Access Token Key of the Twitter Account your bot is posting from
- **TWITTER_ACCESS_TOKEN_SECRET** - The Access Token Secret of the Twitter Account your bot is posting from
- **TWITTER_USER_ID** - Your Twitter user id
- **OPENSEA_API_KEY** - Your OpenSea Api Key
- **LUCHADORES_IMAGE_URL** - The Luchadores distant image website

- Then use the ```php bin/console bot:post``` to post the last sales

## F.A.Q

**Q:** Name a new commit ?

**A:** Follow the rules of [Gitmoji](https://gitmoji.dev/).

##

**Q:** Upgrade and Changement ?

**A:** To make some upgrade, changement make a merge request and to discuss about it don't hesitate to contact me on Twitter.
##

**Q:** Contact me / my Twitter ?

**A:** On Twitter [@NelsonRodMar](https://twitter.com/NelsonRodMar).
