# What is "Blockchain"

A blockchain is one component of a technology that allows to construct
robust, distributed and autonomously acting databases.

### In simple terms

Think of a blockchain system as a spreadsheet that everyone can read and
edit at the same time. Each modification is instantly shared among all
participants. A consensus mechanism ensures that conflicting
modifications are resolved on a first-come-first-serve basis.
Additionally to being able to modify cells of the spreadsheet, the
blockchain system supports *macros* that automate behavior on specific
changes. These *macros* are shared among participants and perform the
same tasks everywhere.

### In technical terms

Blockchain technologies constitute multiple components:

* **blockchain** as a means of tamper-proof storage by means of a
  *hash-linked* list. Modifications to blocks in the chain are easy to
  identify and impossible to hide. This enables a resistant audit-trail.
* a **consensus scheme** is used to identify the entity that is allowed
  to produce a new block (and extend the blockchain) with new data
* **transactions** are *user-signed* instructions (letters-of-intend)
  that are stored on the blockchain and come with certain consequences
  (think of a transfer that causes a credit and debit on sender and
  receiver)
* a **peer-2-peer network** enables servers to communicate and exchange
  messages including transactions and blocks, and enable to synchronize
  the entire mesh-network of computers.
* the **business logic** gives the blockchain its functionalities. It
  provides a certain set of features and operations that can be
  executed.

Once a transactions is received, it is authenticated (signature
verification), validated (state-less consistency check), evaluated
(state-full checks) and applied (instructions are executed). For
non-block producing participants, only those transactions are applied
that are part of an existing block. In case of block producers,
transactions are bundled into a new block upon execution and are
broadcast to the network.

The business logic describes one or many functionalities that are
available to be used thru the blockchain. A simple *transfer* can be
seen as part of the business logic as well as a much more complex escrow
system. Any business process that does not rely on human intervention
can be implemented and thus automated by the blockchain. This is often
referred to as *smart contract* or *blockchain protocol*.

# What is "Graphene"

The Graphene technology is an MIT-licensed framework to build blockchain
systems. It constitutes all the required components including
peer-2-peer networking, data storage, in-RAM database, elliptic-curve
cryptography, hashing, validation, block construction, and efficient
consensus scheme and much more.

However, it leaves the business logic open to the business case.
Multiple examples exist already that share the common Graphene framework
and [differ in their business logic](https://github.com/graphene-foundation/blockchains)

As such, a business that would like to automated business processes by
means of a blockchain can get started with the Graphene framework much
faster and more efficiently while being future proof and scalable.

# What are the advantages of Graphene over other Blockchain Technologies

 * **Graphene vs. Bitcoin/Litecoin etc.**: In contrast to
   Bitcoin/Litecoin and *Satoshi*-blockchains in general, Graphene
   offers a much wider range of possibilities thanks to its flexibility
   in the business logic. Furthermore, its consensus mechanism allows
   for much faster interactions.

 * **Graphene vs. Ethereum**: Ethereum is a smart-contracting platform
   that anyone can use to *install* new business logic that is evaluated
   by the entire Ethereum network. The basic difference between Graphene
   and the Ethereum framework is that Graphene preferred Speed and
   Scalability over on-line flexibility and easy of deployment of new
   business logic. While the business logic can still be changed and
   updated with Graphene, Ethereum's interpretation of smart contracting
   is more flexible at the cost of speed, scalability and security.
