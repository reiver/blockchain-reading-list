# Blockchain Reading List

This is a list of readings (and watchings) on **blockchain** related topics.


## Preamble

The word _"blockchain"_ (or _"block chain"_) started off as a more or less narrowly defined technical term.

It (_"blockchain"_) later became a buzzword that represented anything related to BitCoin, alt-coins (ex: LiteCoin, Ethereum, etc), cryptocurrencies, etc.

And now that the word _"blockchain"_ is on the verge of becoming a _household name_,
it seems like it is starting to include what some others used to call _"P2P"_, and are now calling _"distributed computing"_.

(In some usages of the label _"blockchain"_, neither _blocks_ or _hash lists_ seemed to be necessary for that thing to be called a _"blockchain"_.)

This seems to somewhat mirror how previously the usage of the word _"P2P"_ seemed to broaden and also include what others are calling  _"distributed computing"_.

(Although this time around, cryptography and various concepts of "money" seems to have prominence.)

Regardless, this document focuses on a more traditional definition of _"blockchain"_.

But also includes some topics that the author of this document feels that, while not strictly about blockchains,
will help provide readers with a deep(er) technical background that can be useful when working with or creating blockchain based technologies.


## Audience

This document is targeted at technical people, who are looking to gain a deep understand of the concepts behind blockchain based technologies.


## Topics
* [Abstract Algebra](#abstract-algebra)
* [Behavioral Science](#behavioral-science)
* [BitCoin](#bitcoin)
* [Bit Gold](#bit-gold)
* [B-Money](#b-money)
* [Colored Coins](#colored-coins)
* [Consensus](#consensus)
* [Content Addressing](#content-addressing)
* [Cryptocurrency](#cryptocurrency)
* [Cryptography](#cryptography)
* [Distributed Computing](#distributed-computing)
* [Distributed Hash Tables](#distributed-hash-tables)
* [eCash](#ecash)
* [Error Detection and Correction](#error-detection-and-correction)
* [Ethereum](#ethereum)
* [Handicap Principle](#handicap-principle)
* [Hashcash](#hashcash)
* [Hash Lists](#hash-lists)
* [History (Cypherpunk)](#history-cypherpunk)
* [History (Open Source)](#history-open-source)
* [Identity](#identity)
* [Mastercoin](#mastercoin)
* [Money](#money)
* [Onion Routing](#onion-routing)
* [Paxos](#paxos)
* [Peer-to-Peer Networks](#peer-to-peer-networks)
* [Privacy](#privacy)
* [Proof-of-Stake](#proof-of-stake)
* [Proof-of-Work](#proof-of-work)
* [Raft](#raft)
* [Rai](#rai)
* [Randomness](#randomness)
* [Selfish Mining Attack](#selfish-mining-attack)
* [Smart Contracts](#smart-contracts)
* [Solidity](#solidity)
* [Sybil Attack](#sybil-attack)
* [Tamper Detection](#tamper-detection)
* [Trust Networks](#trust-networks)
* [Worse Is Better](#worse-is-better)
* [Zero-Knowledge Proof Protocol](#zero-knowledge-proof-protocol)


## Abstract Algebra

* [Abstract Algebra (Socratica)](https://www.youtube.com/playlist?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6),
  by Liliana de Castro, Michael Harrison, Hatch Harrison


## Behavioral Science

* [Please, not another bias! An evolutionary take on behavioural economics](https://jasoncollins.blog/2015/07/30/please-not-another-bias-an-evolutionary-take-on-behavioural-economics/),
  by Jason Collins

* [The Hidden Agenda of the Political Mind](https://www.goodreads.com/book/show/21981657-the-hidden-agenda-of-the-political-mind),
  by Jason Weeden, Robert Kurzban

* [Hierarchy in the Forest](https://www.goodreads.com/book/show/2131522.Hierarchy_in_the_Forest),
  by Christopher Boehm

* [The Biology of Moral Systems](https://www.goodreads.com/book/show/1446851.The_Biology_of_Moral_Systems),
  by Richard D. Alexander

* See also: [Handicap Principle](#handicap-principle)


## BitCoin

* [Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf),
  by Satoshi Nakamoto

* [Annotated: "Bitcoin: A Peer-to-Peer Electronic Cash System"](https://genius.com/2698706),
  by Satoshi Nakamoto, Balaji Srinivasan, Et al.

* [How the Bitcoin protocol actually works](http://www.michaelnielsen.org/ddi/how-the-bitcoin-protocol-actually-works/),
  by Michael Nielsen

* [Ever wonder how Bitcoin (and other cryptocurrencies) actually work?](https://youtu.be/bBC-nXj3Ng4),
  by Grant Sanderson

* [Mastering Bitcoin](https://github.com/bitcoinbook/bitcoinbook),
  by Andreas M. Antonopoulos

* [Why Is It Taking 20 Minutes to Mine This Bitcoin Block?](http://r6.ca/blog/20180225T160548Z.html),
  by Russell O’Connor

* [OP_RETURN and the Future of Bitcoin](https://bitzuma.com/posts/op-return-and-the-future-of-bitcoin/),
  by Rich Apodaca

* [Explanation of what an OP_RETURN transaction looks like](https://bitcoin.stackexchange.com/questions/29554/explanation-of-what-an-op-return-transaction-looks-like)

* [Hidden surprises in the Bitcoin blockchain and how they are stored: Nelson Mandela, Wikileaks, photos, and Python software](http://www.righto.com/2014/02/ascii-bernanke-wikileaks-photographs.html),
  by Ken Shirriff


## Bit Gold

* [Bit gold](https://unenumerated.blogspot.com/2005/12/bit-gold.html),
  by Nick Szabo


## B-Money

* [b-money, an anonymous, distributed electronic cash system](http://weidai.com/bmoney.txt),
  by Wei Dai

* [B-money - Bitcoin Wiki](https://en.bitcoin.it/wiki/B-money)


## Colored Coins

* [Colored Coins - Bitcoin Wiki](https://en.bitcoin.it/wiki/Colored_Coins)

* [Colored Coins - Wikipedia](https://en.wikipedia.org/wiki/Colored_coin)

* [Coloring Scheme](https://github.com/Colored-Coins/Colored-Coins-Protocol-Specification/wiki/Coloring%20Scheme)


## Consensus

* See also: [BitCoin](#bitcoin), [Paxos](#paxos), [Raft](#raft)


## Content Addressing

* [Magnet URI Project](http://magnet-uri.sourceforge.net/)

* [MAGNET v0.1 (Draft Tech Overview/Spec)](http://magnet-uri.sourceforge.net/magnet-draft-overview.txt),
  by Gordon Mohr

* [Magnet URI scheme (Wikipedia)](https://en.wikipedia.org/wiki/Magnet_URI_scheme),

* [A URN Namespace For Identifiers Based on Cryptographic Hashes](https://tools.ietf.org/html/draft-thiemann-hash-urn-01)
  by Peter Thiemann

* [IETF RFC 6920: Naming Things with Hashes](https://tools.ietf.org/search/rfc6920)

* [Trusty URIs: Verifiable, Immutable, and Permanent Digital Artifacts for Linked Data](https://arxiv.org/abs/1401.5775),
  by Tobias Kuhn, Michel Dumontier

* [BIP 122](https://github.com/bitcoin/bips/blob/master/bip-0122.mediawiki)

* [HTTP Extensions for a Content-Addressable Web](http://lists.w3.org/Archives/Public/www-talk/2001NovDec/0090.html)

* [IETF RFC 2397: The "data" URL scheme](https://tools.ietf.org/html/rfc2397)

* [Hash URI Specification](https://github.com/hash-uri/hash-uri)

* See also: [Distributed Hash Tables](#distributed-hash-tables)


## Cryptocurrency

* See also: [BitCoin](#bitcoin), [Bit Gold](#bit-gold), [B-Money](#b-money), [eCash](#ecash), [Ethereum](#ethereum),


## Cryptography

* [Everything you need to know about cryptography in 1 hour](https://youtu.be/jzY3m5Kv7Y8),
  by Colin Percival

* [$5 wrench attack](https://xkcd.com/538/),
  by Randall Munroe

* [Communication Theory of Secrecy Systems](http://netlab.cs.ucla.edu/wiki/files/shannon1949.pdf),
  by Claude Elwood Shannon

* [New Directions in Cryptography](http://wwwknoll.in.tum.de/pub/Main/TeachingSs2006EinfuehrungInformatik2/diffie.pdf),
  by Whitfield Diffie, Martin E. Hellman

* [A Method for Obtaining Digital Signatures and Public-Key Cryptosystems](https://people.csail.mit.edu/rivest/Rsapaper.pdf),
  by Ronald Linn Rivest, Adi Shamir, Leonard Adleman

* [How RSA Works With Examples](http://doctrina.org/How-RSA-Works-With-Examples.html),
  by Barry Steyn

* [Why RSA Works: Three Fundamental Questions Answered](http://doctrina.org/Why-RSA-Works-Three-Fundamental-Questions-Answered.html),
  by Barry Steyn

* [Cryptographic Hash VS MAC: What You Need To Know](http://doctrina.org/Cryptographic-Hash-Vs-MAC:What-You-Need-To-Know.html),
  by Barry Steyn

* [End to End Encryption (E2EE) (Computerphile)](https://youtu.be/jkV1KEJGKRA),
  by Mike Pound

* [Secret Key Exchange (Diffie-Hellman) (Computerphile)](https://youtu.be/NmM9HA2MQGI),
  by Mike Pound

* See also: [Onion Routing](#onion-routing), [Randomness](#randomness), [Zero-Knowledge Proof Protocol](#zero-knowledge-proof-protocol)


## Distributed Computing

* [Introduction to Distributed System Design](http://www.hpcs.cs.tsukuba.ac.jp/~tatebe/lecture/h23/dsys/dsd-tutorial.html)

* [Perspectives on the CAP Theorem](http://groups.csail.mit.edu/tds/papers/Gilbert/Brewer2.pdf),
  by Seth Gilbert, Nancy A. Lynch

* [The Log: What every software engineer should know about real-time data's unifying abstraction](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying),
  by Jay Kreps

* [Notes on Distributed Systems for Young Bloods](https://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods/),
  by Jeff Hodges

* [Immutability Changes Everything (video)](https://vimeo.com/52831373),
  by Pat Helland

* [Immutability Changes Everything (paper)](http://cidrdb.org/cidr2015/Papers/CIDR15_Paper16.pdf),
  by Pat Helland

* [Kafka: a Distributed Messaging System for Log Processing](http://notes.stephenholiday.com/Kafka.pdf),
  by Jay Kreps, Neha Narkhede, Jun Rao

* [Chord: A Scalable Peer-to-peer Lookup Service for Internet Applications](https://pdos.csail.mit.edu/papers/chord:sigcomm01/chord_sigcomm.pdf),
  by Ion Stoica, Robert Morris, David Karger, M. Frans Kaashoek, Hari Balakrishnan

* [Dynamo: Amazon’s Highly Available Key-value Store ](http://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf),
  by Giuseppe DeCandia, Deniz Hastorun, Madan Jampani, Gunavardhan Kakulapati, Avinash Lakshman, Alex Pilchin, Swaminathan Sivasubramanian, Peter Vosshall, Werner Vogels

* [MapReduce: Simplified Data Processing on Large Clusters](https://research.google.com/archive/mapreduce.html),
  by Jeffrey Dean, Sanjay Ghemawat

* [The Chubby Lock Service for Loosely-Coupled Distributed Systems](https://research.google.com/archive/chubby.html),
  by Mike Burrows

* [So, you want to trace your distributed system? Key design insights from years of practical experience](http://www.pdl.cmu.edu/PDL-FTP/SelfStar/CMU-PDL-14-102.pdf)
  by Raja R. Sambasivan, Rodrigo Fonseca, Ilari Shafer, Gregory R. Ganger

* [Dapper, a Large-Scale Distributed Systems Tracing Infrastructure](https://research.google.com/pubs/pub36356.html),
  by Benjamin H. Sigelman, Luiz André Barroso, Mike Burrows, Pat Stephenson, Manoj Plakal, Donald Beaver, Saul Jaspan, Chandan Shanbhag

* [Queues Don't Fix Overload](https://ferd.ca/queues-don-t-fix-overload.html),
  by Fred Hebert

* See also: [Consensus](#consensus), [Peer-to-Peer Networks](#peer-to-peer-networks)


## Distributed Hash Tables

* [Kademlia: A Peer-to-peer Information System Based on the XOR Metric](https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf),
  by Petar Maymounkov, David Mazières


## eCash

* [Blind signatures for untraceable payments](http://sceweb.sce.uhcl.edu/yang/teaching/csci5234WebSecurityFall2011/Chaum-blind-signatures.PDF),
  by David Chaum

* [eCash Bitcoin wiki](https://en.bitcoinwiki.org/wiki/Ecash)

* [An introduction to ecash](https://web.archive.org/web/19971009044558/http://digicash.com/publish/ecash_intro/ecash_intro.html)


## Error Detection and Correction

* [Information Theory & Coding (Computerphile)](https://www.youtube.com/playlist?list=PLzH6n4zXuckpKAj1_88VS-8Z6yn9zX_P6),
  by David Brailsford

* [Multiple Dimension Error Correction (Computerphile)](https://youtu.be/1_X-7BgHbE0),
  by David Brailsford

* [The Perfect Code (Computerphile)](https://youtu.be/WPoQfKQlOjg),
  by David Brailsford

* [EXTRA BITS: More on Perfect Codes (Computerphile)](https://youtu.be/i4zC67Yf5Iw),
  by David Brailsford


## Ethereum

* [Ethereum in 25 Minutes](https://www.youtube.com/watch?v=66SaEDzlmP4&t=22s),
  by Vitalik Buterin

* [Ethereum White Paper](https://github.com/ethereum/wiki/wiki/White-Paper)

* [Ethereum Yellow Paper](https://github.com/ethereum/yellowpaper),
  by Gav Would, et al

* [Ethereum Beige Paper: Rewrite of the Yellowpaper in non-Yellowpaper syntax](https://github.com/chronaeon/beigepaper/),
  by Micah Dameron

* [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook),
  by Andreas M. Antonopoulos, Gavin Wood

* See also: [Solidity](#solidity)


## Handicap Principle

* [The Handicap Principle: A Missing Piece of Darwin's Puzzle](http://www.goodreads.com/book/show/885547.The_Handicap_Principle),
  by Amotz Zahavi, Avishag Zahavi


## Hashcash

* [Hashcash - A Denial of Service Counter-Measure](http://www.hashcash.org/papers/hashcash.pdf),
  by Adam Back


## Hash Lists

* [How to Time-Stamp a Digital Document](https://link.springer.com/chapter/10.1007/3-540-38424-3_32),
  by Stuart Haber, W. Scott Stornetta


## History (Cypherpunk)

* [A Cypherpunk's Manifesto](https://www.activism.net/cypherpunk/manifesto.html),
  by Eric Hughes

* [The Crypto Anarchist Manifesto](https://www.activism.net/cypherpunk/crypto-anarchy.html),
  by Timothy C. May

* [Cyphernomicon](https://www.cypherpunks.to/faq/cyphernomicron/cyphernomicon.html),
  by Timothy C. May

* [This Machine Kills Secrets](https://www.goodreads.com/book/show/13586738-this-machine-kills-secrets),
  by Andy Greenberg

* [Crypto](https://www.goodreads.com/book/show/984428.Crypto),
  by Steven Levy


## History (Open Source)

* [The Cathedral and the Bazaar ](http://www.catb.org/esr/writings/cathedral-bazaar/cathedral-bazaar/),
  by Eric Steven Raymond

* [Homesteading the Noosphere](http://www.catb.org/esr/writings/homesteading/homesteading/),
  by Eric Steven Raymond

* [The Wikipedia Revolution](https://www.goodreads.com/book/show/4606921-the-wikipedia-revolution),
  by Andrew Lih


## Identity

* [Identity Crisis: How Identification Is Overused and Misunderstood](https://www.goodreads.com/book/show/171237.Identity_Crisis),
  by Jim Harper

* [Secrets and Lies: Digital Security in a Networked World](https://www.goodreads.com/book/show/304482.Secrets_and_Lies),
  by Bruce Schneier

* [Secure Electronic Commerce: Building the Infrastructure for Digital Signatures and Encryption](https://www.goodreads.com/book/show/1174424.Secure_Electronic_Commerce),
  by Warwick Ford, Michael S. Baum

* [Understanding Windows CardSpace: An Introduction to the Concepts and Challenges of Digital Identities ](https://www.goodreads.com/book/show/22380161-understanding-windows-cardspace),
  by Vittorio Bertocci, Garrett Serack, Caleb Baker

* [7 Laws of Identity](https://web.archive.org/web/20090824224507/https://www.identityblog.com/?p=1065)
  by Kim Camerons,

* [Getting Started with OAuth 2.0](https://www.goodreads.com/book/show/13228633-getting-started-with-oauth-2-0),
  by Ryan Boyd

* [Digital Identity](https://www.goodreads.com/book/show/155374.Digital_Identity),
  by Phillip J. Windley

* [Identity Management: A Primer](https://www.goodreads.com/book/show/7273193-identity-management),
  by Graham Williamson, David Yip, Ilan Sharoni, Kent Spaulding


## Mastercoin

* [Mastercoin: A Second-Generation Protocol on the Bitcoin Blockchain](https://bitcoinmagazine.com/articles/mastercoin-a-second-generation-protocol-on-the-bitcoin-blockchain-1383603310/),
  by Vitalik Buterin

* [MasterCoin Complete Specification Version 1.0](https://www.scribd.com/document/157454619/MasterCoin-Specification),
  by J.R. Willett


## Money

* [Shelling Out: The Origins of Money](http://nakamotoinstitute.org/shelling-out/),
  by Nick Szabo

* [The Ascent of Money: A Financial History of The World (Documentary)](https://youtu.be/fsrtB5lp60s),
  by Niall Ferguson

* See also: [BitCoin](#bitcoin), [Bit Gold](#bit-gold), [B-Money](#b-money), [eCash](#ecash), [Ethereum](#ethereum), [Rai](#rai)


## Onion Routing

* [Onion Routing (Computerphile)](https://youtu.be/QRYzre4bf7I),
  by Mike Pound

* [EXTRA BITS: Onion Routing (Computerphile)](https://youtu.be/6eWkdyRNfqY),
  by Mike Pound

* [Tor: The Second-Generation Onion Router](https://www.usenix.org/conference/13th-usenix-security-symposium/tor-second-generation-onion-router),
  by Roger Dingledine, Nick Mathewson, Paul Syverson

* [Circuit Fingerprinting Attacks: Passive Deanonymization of Tor Hidden Services](https://people.csail.mit.edu/devadas/pubs/circuit_finger.pdf),
  by Albert Kwon, Mashael AlSabah, David Lazar, Marc Dacier, Srinivas Devadas

* [Garlic Routing](https://geti2p.net/en/docs/how/garlic-routing)


## Paxos

* [Neat Algorithms - Paxos](http://harry.me/blog/2014/12/27/neat-algorithms-paxos/),
  by Harry Brundage

* [The Paxos Algorithm](https://youtu.be/d7nAGI_NZPk),
  by Luis Quesada Torres

* [The Part-Time Parliament](https://www.microsoft.com/en-us/research/uploads/prod/2016/12/The-Part-Time-Parliament.pdf),
  by Leslie Lamport


## Peer-to-Peer Networks

* [Understanding Churn in Peer-to-Peer Networks](http://www.barsoom.org/papers/imc-2006-churn.pdf),
  by Daniel Stutzbach, Reza Rejaie

* See also: [BitCoin](#bitcoin), [Bit Gold](#bit-gold), [Distributed Hash Tables](#distributed-hash-tables)


## Privacy

* [An Overview of Blockchain Privacy Mechanisms](https://steemit.com/zcoin/@zcoinofficial/an-overview-of-blockchain-privacy-mechanisms-and-how-zerocoin-in-zcoin-usdxzc-not-zcash-stacks-up),

* See also: [Cryptography](#cryptography), [Zero-Knowledge Proof Protocol](#zero-knowledge-proof-protocol)


## Proof-of-Stake

* [On Stake and Consensus](https://download.wpsoftware.net/bitcoin/pos.pdf),
  by Andrew Poelstra

* [Cryptocurrencies without Proof of Work](https://arxiv.org/abs/1406.5694),
  by Iddo Bentov, Ariel Gabizon, Alex Mizrahi


## Proof-of-Work

* See also: [Handicap Principle](#handicap-principle), [Hashcash](#hashcash), [Selfish Mining Attack](#selfish-mining-attack)


## Raft

* [The Raft Consensus Algorithm](https://raft.github.io/),
  by Diego Ongaro, Et al.

* [Raft: Understandable Distributed Consensus](http://thesecretlivesofdata.com/raft/),
  by Ben Johnson

* [In Search of an Understandable Consensus Algorithm (Extended Version)](https://raft.github.io/raft.pdf),
  by Diego Ongaro, John Ousterhout

* [Tangaroa: a Byzantine Fault Tolerant Raft](http://www.scs.stanford.edu/14au-cs244b/labs/projects/copeland_zhong.pdf),
  by Christopher Copeland, Hongxia Zhong


## Rai

* [Island Money](https://www.clevelandfed.org/en/newsroom-and-events/publications/economic-commentary/economic-commentary-archives/2004-economic-commentaries/ec-20040201-island-money.aspx),
  by Michael F. Bryan

* [The Rai Stones are huge stone wheels used as currency on the island of Yap](http://www.thevintagenews.com/2017/10/25/the-rai-stones-are-huge-stone-wheels-used-as-currency-on-the-island-of-yap/),
  by Boban Docevski


## Randomness

* [Uniform Non-Random Random Numbers](http://changelog.ca/quote/2011/10/29/uniform_non-random_random_numbers),
  by Timothy Masters

* [TIFU by using Math.random()](https://medium.com/@betable/tifu-by-using-math-random-f1c308c4fd9d),
  by Mike Malone

* [The Lava Lamps That Help Keep The Internet Secure](https://youtu.be/1cUUfMeOijg),
  by Tom Scott


## Selfish Mining Attack

* [Majority is not Enough: Bitcoin Mining is Vulnerable](https://www.cs.cornell.edu/~ie53/publications/btcProcFC.pdf),
  by Ittay Eyal and Emin G ̈un Sirer

* See also: [Proof-of-Work](#proof-of-work)


## Smart Contracts

* [The Idea of Smart Contracts](http://www.fon.hum.uva.nl/rob/Courses/InformationInSpeech/CDROM/Literature/LOTwinterschool2006/szabo.best.vwh.net/idea.html),
  by Nick Szabo

* See also: [B-Money](#b-money), [Solidity](#solidity)


## Solidity

* [What's Solidity](https://www.youtube.com/watch?v=v_hU0jPtLto&list=PL16WqdAj66SCOdL6XIFbke-XQg2GW_Avg)

* [Solidity Bytecode and Opcode Basics](https://medium.com/@blockchain101/solidity-bytecode-and-opcode-basics-672e9b1a88c2), by Bernard Peh

* [CryptoZombies](https://cryptozombies.io/)


## Sybil Attack

* [The Sybil Attack](http://research.microsoft.com/pubs/74220/IPTPS2002.pdf),
  by John R. Douceur


## Tamper Detection

* [The Playdough Protocols](http://nakamotoinstitute.org/the-playdough-protocols/),
  by Nick Szabo

* See also: [Hash Lists](#hash-lists)


## Trust Networks

* [Advogato's Trust Metric](https://web.archive.org/web/20121025175345/http://www.advogato.org:80/trust-metric.html),
  by Raph Levien

* [Attack Resistant Trust Metrics](http://www.levien.com/thesis/compact.pdf),
  by Raph Levien

* [Advogato Has Failed](https://web.archive.org/web/20170628190710/http://www.advogato.org/article/928.html),
  by Bryan Taylor

* [Eigenmorality](https://www.scottaaronson.com/blog/?p=1820),
  by Scott Aaronson

* See also: [Sybil Attack](#sybil-attack)


## Worse Is Better

* [The Rise of “Worse is Better”](https://www.jwz.org/doc/worse-is-better.html),
  by Richard P. Gabriel

* [Worse Is Better](http://dreamsongs.com/WorseIsBetter.html),
  by Richard P. Gabriel

* [“RethinkDB: why we failed” (Worse Is Better: RethinkDB vs MongoDB)](http://www.defmacro.org/2017/01/18/why-rethinkdb-failed.html),
  by Slava Akhmechet

* [Lisp: Good News, Bad News, How to Win Big](http://dreamsongs.com/WIB.html),
  by Richard P. Gabriel

* [Worse Is Better (WikiWikiWeb)](http://wiki.c2.com/?WorseIsBetter)


## Zero-Knowledge Proof Protocol

* [Zero Knowledge Proofs (Computerphile)](https://youtu.be/HUs1bH85X9I),
  by Alberto Sonnino

* [Zero Knowledge Proofs](https://youtu.be/0Sy6nb72gCk),
  by Scott Twombly

* [Introduction to zkSNARKs](https://youtu.be/jr95o_k_SwI),
  by Christian Reitwiessner

* [Bulletproofs: Short Proofs for Confidential Transactions and More](https://eprint.iacr.org/2017/1066.pdf),
  by Benedikt Bünz, Jonathan Bootle, Dan Boneh, Andrew Poelstra, Pieter Wuille, Greg Maxwell
