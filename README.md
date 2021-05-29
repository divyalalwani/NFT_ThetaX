# NFT_ThetaX
# NFTs-for-artists
Information and educational resources for artists interested in Non-Fungible Tokens / NFTs / crypto collectibles.

DISCLAIMER: none of this should be interpreted as financial advise.

## What are NFTs?

Non-Fungible Tokens are essentially digital serial numbers that can have art or other media attached, and then can be given, sold or traded via various cryptocurrency blockchains and marketplaces. They are now being used for digital trading cards, fine art certificates of authenticity, celebrity memorabilia, music, image, movies and even tweets. The creator of the artwork can retain a royalty on future sales and more complicated royalty structures are coming.

https://www.esquire.com/entertainment/a35742083/what-are-nfts-explained/
https://www.npr.org/2021/03/05/974089381/whats-an-nft-and-why-are-people-paying-millions-to-buy-them

## How to make NFTs?

There are several competing platforms and many more on the way. The biggest factor will be what marketplace do you want to use and what blockchain is that on? There is a large difference with regards to efficiency, and creating NFTs on the most popular platform, Ethereum costs over 300x more than using a more efficient platform and uses much more electricity. There are currently fewer buyers on smaller platforms like Tezos, but in the future it appears that tokens will be able to move between blockchains and they will all be aggregated in marketplaces like OpenSea, which is kind of like eBay for NFTs.

## Proof of Work

The breakthrough discovery behind Bitcoin in 2008 is a system called Proof of Work. It enables collaboration at scale by providing insurance that the other parties will not be able to cheat. This insurance is accomplished by incentivizing people to invest money into hardware and into electricity and participating in kind of a race to solve math problems. Beyond demonstrating this new concept, Bitcoin has almost no optimization of any kind – all the work has to be done by every participant, and the more value in the system, the more incentive they have to buy expensive hardware and use increasing amounts of electricity. Most people agree that this design is fundamentally wasteful of energy and unable to scale. Bitcoin (BTC) and Ethereum (ETH) are currently using Proof of Work. The vast majority of the industry is in the progress of migrating to newer systems. Even if Bitcoin remains in its current form, it’s energy usage, carbon and environmental footprints are still arguably better than an industry like gold mining.

## Proof of Stake

Beginning in 2012 developers began exploring a new model called Proof of Stake. In this model validators would put up some cryptographic assets as a form of insurance, rather than constantly spending money on hardware and electricity. Rather than massive and expensive hardware, processor nodes can now start running on smaller hardware, even down to a Raspberry Pi in some cases. The main factor differentiating these platforms is how cheaply they are able to deliver their services. There is clear incentive to be efficient and the main input is now an economic input, not electricity. Nearly every main platform for smart contracts or financial services are now transitioning to this model and away from Proof of Work mining. The most successful second-generation platform, ETH, has been struggling with this transition and is currently clogged with transactions and still heavily mining dependent.

## Fees and Environmental Costs

As of March 7, 2021 it costs over $100 in GAS fees to create an NFT on the ETH platform. Those fees create a direct incentive for miners to use electricity to try to collect them. To create an NFT on Tezos, which is a Proof of Stake platform is roughly $0.34. The overhead costs for stake pools on Tezos range from 5%-10% and that includes all hardware and operating costs. From that I estimate that maybe 1-3% of the fee is being used for electricity on the Tezos chain.

It is also important to understand that there can also be other transactions involved with the NFT sale that can cost GAS. In particular, selling via auction conducted by smart contract is very inefficient and every bid placed will use additional GAS. In addition, selling or transferring the NFT in the future will have some unknown cost.

Carbon.fyi has developed software and a methodology for estimating emissions for specific operations on ETH.
- https://carbon.fyi/
- https://www.notion.so/Carbon-FYI-Methodology-51e2d8c41d1c4963970a143b8629f5f9
- https://github.com/Offsetra/ethereum-emissions-calculator

Joanie Lemercier recently calculated the cost of minting a single NFT on ETH to be about 80kg of CO2. 
- https://joanielemercier.com/the-problem-of-cryptoart/

Memo Atken has created a tool where you can estimate the cost of a specific work on ETH and has also written extensively on the topic. Some overzealous people started using his tools to make death threats and other irresponsible behiavor and as a result he took the cryptoart.wtf tool down. The underlying research from carbon.fyi is still available.

## Practical Workarounds

- Avoid auction sales - every auction bid results in additional GAS being spent and CO2 emitted.
- Use lazy minting and don't spend GAS unless someone buys the NFT. Production on demand.
- - https://opensea.io/blog/announcements/introducing-the-collection-manager/
- - https://www.ovr.ai/blog/introducing-light-minting/

## Privacy

One caveat to public blockchains is transactions and finances are out in the open. If someone buys an NFT from you they can see your balance, transfer and sales history if they use a block explorer. It is recommended to keep your account numbers private, but as an artist doing open sales your entire wallet history will be visible to your buyers. The reverse is also true and you could use analytics to tell you when you have had sales to any prolific collectors and what else they like. This can potentially result in a cultural race to the bottom, similar to what happened with online news sources. We already see some clickbait artists selling for huge figures.

In Tezos there may be a few things possible to address this. Some kind of aliases might be possible in the short term. It also has some privacy features called Sapling, but it isn't currently in use here. https://tezos.gitlab.io/008/sapling.html

I believe you could also agressively rotate wallets as a creator as a way to keep your data in silos. If each NFT is issued from a separate wallet it becomes harder to know your exact finances in aggregate.

## How to mint on Tezos

- Quick video - https://www.youtube.com/watch?v=Apyd-I2DMVk

- Complete detailed guide including a way to get 2 tezos for free to get started. (Updated March 16, 2021) - https://xtz.news/tezos-user-guides/nfts/getting-started-as-an-nft-artist-on-tezos-using-hicetnunc/

1. You will need a small amount of Tezos to pay for minting fees. A few dollars should be enough to get started. Exchanges where it is available are: https://www.kraken.com/ https://www.binance.com/ or https://www.binance.us/
2. Install the Brave browser. https://brave.com/
3. Open Brave and then install Temple Wallet. https://templewallet.com/
4. In Temple Wallet you will need to create a new wallet. This involves writing down a number of secret words (used to recover your wallet or transfer to another computer - keep it safe) and creating a password.
5. Once your wallet is set up and open, click the receive button. An address will be displayed - it looks like tz...... Click the 'copy to clipboard' button.
6. Switch back to the exchange where you got the Tezos. You will want to 'send' or 'withdraw' and when it gives you a place to paste the Tezos address and enter how much to send. You will likely also have to put in a 2FA security code to make a transfer.
7. In a minute or two your funds should show up in your wallet.
8. Now you can go to Hic Et Nunc, using Brave browser. https://www.hicetnunc.xyz/mint
9. Click 'sync' and approve your wallet to talk to the site.
10. Enter a title, description, # of NFTs in the edition and upload your JPG, PNG, GIF, SVG or MP4 attachment.
11. Once you click Mint you will need to approve the operation and there will be a fee, although the current wallet interface doesn't show this clearly.
12. You will need to wait a few minutes and then you can use the menu to 'manage assets'.
13. When you bring up your NFT you will nave a new link to +curate.
14. Enter the number you want to sell and how much to charge. You are entering µtez, or the number of Tezos followed by six zeros.
15. Finally click curate and approve the wallet operation.
16. Sales and royalty fees will automatically appear in your wallet. Now you just need to promote your NFT to your fans.

## Tezos / Market info

- You can examine the growth of the Tezos platform here. Total (smart) contract calls is at an all time high and about 3x the volume of Feb. https://better-call.dev/stats/mainnet/general
- Top arists on Hic Et Nunc - https://hashquine.github.io/hicetnunc/
- Browse Hic et Nunc data -https://projects.stroep.nl/hicetnunc/#tags
- Hic Et Nunc discord - https://discord.gg/CSs6e9uG
- Hic Et Nunc github - https://github.com/hicetnunc2000/hicetnunc/
- Multisig wallet for collaborations - https://medium.com/eosatticlab/tzsign-tezos-multisig-wallet-is-here-28ddcf40ec64

## Alternative Platforms

https://docs.google.com/spreadsheets/d/1A-7Ama31sYWhXDl6NoJaXnbAV9pFbjxLIgl7jb3CHOs/edit?fbclid=IwAR1nZAMrJcq7gPy1BP8OAa2X7ZH4X5pQKZ0jlqwMEAzODB-eRikSRIfZAb4#gid=0
DOT - https://kodadot.xyz/
https://zilliqa.mintable.app/
https://epor.io/

## H=N API queries

Thanks to bors_nft for help with some of these queries. https://www.hicetnunc.xyz/tz/tz1fb6jz7rh4H7AojLShvhiXKaSNDyvkH7sM

- Royalties - https://staging.api.tzkt.io/v1/bigmaps/522/keys?sort.desc=id&active=true&key.eq=[objkt id]
- Latest Minted OBJKT number - https://api.tzkt.io/v1/operations/transactions?target=KT1RJ6PbjHpwc3M5rw5s2Nbmefwbuwbdxton&entrypoint=mint&status=applied&limit=1&sort.desc=id
- OBJKT metadata - https://api.better-call.dev/v1/tokens/mainnet/metadata?token_id=50000
- Swaps - https://staging.api.tzkt.io/v1/bigmaps/523/keys?sort.desc=id&active=true&value.issuer=[account id]

## Digital Art Links

- Ongoing NFT discussion panel for artists - https://www.youtube.com/channel/UCo74_bEOow_-_FGn9WT263Q
- My experiments - https://www.hicetnunc.xyz/tz/tz1cTS1WwovU7SC783xgJxZrzr151mcshmNi
- Joanie Lemercier - https://www.hicetnunc.xyz/tz/tz1P5Za1TUMsDejgzMM5iMNfHAxDUpPCHiwZ
- Quasimondo - https://www.hicetnunc.xyz/tz/tz1hb9PiWxQEf6J9xevPsUM6dkuCLnhDMvsp
- Exsstas - https://www.hicetnunc.xyz/tz/tz1Tk1MJDZ96bK85RLAqtKfnptZZyXsJ2jaq
- Boris Chimp 504 - https://www.hicetnunc.xyz/tz/tz1WeuBKYd2BQMbwgivmYqvt4dFuNudBHH56
