---
# we will misuse date to be the date the guide updated
date: 2018-07-06 13:40:09 +0000

# Update page modified by changing the date.
# In Vim use `:r! date -u +"%F %T %z"`
---

### {{ site.description | default: site.github.project_tagline }}

Bitcoin mining is currently too expensive for an individual to join. However, the field of blockchain software is still in its infancy. Without a question, hardware will be used to accelerate computation around blockchain developments and cryptocurrencies.

We (that meaning and could include YOU) made this website to be a group editable resource to break thru the noise of the web, and paid reviews, or guides, to be an open community process for jumpstarting the world of Blockchain Hardware from the individual up. We are contributors made up from the team that invented Bitcoin mining, living and working Beijing, Shenzhen, Hong Kong, Taiwan and San Francisco, coming together to bring software developers closer to hardware realities.

Please add your knowledge to these guides, and see you at a future event in Shenzhen :)


## Guides

### Full Node

Here is a "Full node" definition from [Mastering Bitcoin](https://github.com/bitcoinbook/bitcoinbook): 
 "[A bitcoin network node with all four functions: wallet, miner, full blockchain database, and network routing](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch08.asciidoc#full_node_reference)"

Actually, any healthy crypto currency should contain all of four of these fundamental functions.

You may use them separately, part of them or combine them to make your product.

For example:

1. __Mining pool__: only use part of full blockchain database, network routing, wallet and miner.

2. __Cryptocurrency trading platform__: only uses wallet.

3. __Block Explorer__: uses full blockchain database.

4. __Hardware wallet__: only use part of the wallet.

The more components used, the more complexity is added.

If you can't wait to try, the following are best practice guides:

- [Setup an Ethereum Miner](/guide/setup-ethereum-miner)
- [Setup a Bitcoin Fullnode](/guide/setup-bitcoin-fullnode)
- [Setup an Ethereum Fullnode](/guide/setup-ethereum-fullnode)
- [Hello World for Fullnode](/guide/fullnode-helloworld)
- [Your first cryptocurrency transaction without real coins](/guide/testnet-guide.md)

### IPFS

IPFS is a [distributed file system](https://en.wikipedia.org/wiki/Clustered_file_system#Distributed_file_systems), not the blockchain.

If you want to know more about instances of distributed file system, there are lots of information available through [Wikipedia](https://en.wikipedia.org/wiki/List_of_file_systems#Distributed_file_systems).

Here are our best practices:

- [Setup an IPFS Node](/guide/setup-ipfs-node)

## Surveys

- [Wallets](/survey/wallets)
- [Put It On the Blockchain](/survey/put-it-on-the-blockchain)
- [Cryptocurrency](/survey/cryptocurrency)
- [Books](/survey/books)

## Events

- Currently we are planning a summertime Proof of Hardware summit in Shenzhen.
- Stay tuned here for more details.

## Contact

- <a href="mailto:{{ site.email }}">{{ site.email }}</a>
- Telegram: [https://t.me/proofofhardware](https://t.me/proofofhardware)
- Twitter: [https://twitter.com/proofofhardware](https://twitter.com/proofofhardware) (news & for public announcements)
- WeChat: Ask in Telegram or via e-mai for invite.

## Sponsors

- [POEX](https://poex.io)
- [Proof of Existence](https://proofofexistence.com)
- Contact to be a sponsor <a href="mailto:{{ site.email }}">{{ site.email }}</a>  :)


{% include footer_meta.md mod_date=page.date %}
