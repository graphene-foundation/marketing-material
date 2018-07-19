# In other cryptocurrencies like bitcoin and ethereum, there is an "address" which is hex-string. How are accounts different?

An account can be seen as a registered name that only you own. This this
accomplished by linking your cryptographic secret (private/public key
pair) with your account, publicly. By this, only those entities that
have access to the correct private keys can access a particular
accounts. This comes with another advantages and that is, accounts can
be setup to grant access not just to one key, but to many and allows
sophisticated multi-signature setups for every account. Even accounts
can be allowed to have access to other accounts. That said,
Graphene-based blockchains do not use *addresses* or *public keys*
outside of account authentication and authorization.

# What kind of information does the Bitshares wallet include else private key?

A wallet merely needs to contain private keys. Fro those private keys,
the software can identify automatically which accounts can be access
partially or in full.

# In case of Cloud wallet, where is such a information (wallet info including private key) stored in?

The Cloud wallet scheme allows you to *remember* the private key to your
account. Basically it uses your password and account name to generated
your private key deterministically. Other than the public key that
corresponds to your private key and your account name, no information is
stored on the blockchain.

# I know that the URL of Bitshares wallet is "wallet.bitshares.org".

On this domain, you will be delivered the *web app* which is a set of
HTML, JS, and CSS files. It is the web application that shows you the
wallet. This application also connects to API nodes, such as
`wss://node.bitshares.eu` to connect to the Blockchain.


# Where could I find the document which describes the details of structure of block or transaction in Bitshares including source?

More information about the block header can be found [here](https://bitshares.org/doxygen/structgraphene_1_1chain_1_1block__header.html)

# Could you explain the way how to become a committee member? To be a committee member, does it first require to become a witness?

Witnesses and committee members are independent entities on the
blockchain. You can become witness without becoming committee member and
vise versa. To become a committee one must create a committee-member
object using the cli-wallet and obtain sufficient votes by BTS holders.

# In bitshares whitepaper, it is said that Bitshares' Tx processing could speed up to 100,000 TPS. Is it actually possible?

So far, we managed to prove 3k tps easily on the BitShares testnet. A
new stress-test is in the making and we expect to go beyond the previous
limits. Last time, we lacked sufficient stress
