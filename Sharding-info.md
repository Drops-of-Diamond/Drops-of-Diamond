# Drops of Diamond

[![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey.svg)](https://github.com/Drops-of-Diamond/Drops-of-Diamond/blob/master/LICENSE)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Drops-of-Diamond/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Want to make Ethereum faster and more mainstream? 

# About me

I'm planning to do so. For me to do:
- [x] read the [Yellow Paper](https://ethereum.github.io/yellowpaper/paper.pdf);
- [x] read about the [stateless client concept](https://ethresear.ch/t/the-stateless-client-concept/172);
- [x] familiarize with the Python sharding repo [here](https://github.com/ethereum/sharding/tree/develop/sharding) (a doc is available [here](https://github.com/ethereum/sharding/blob/develop/docs/doc.md));
- [x] learn about abstract programming language features;
- [ ] WIP: [learn Rust](https://doc.rust-lang.org/book/second-edition);
- [ ] maybe further familiarize with the sharding implementation on top of PyEVM [here](https://github.com/ethereum/py-evm/tree/sharding);
- [ ] familiarize with Parity;
- [ ] start building stateless sharding and Ethereum 2.0 in this repo;
- [ ] not a high immediate priority as others have already tested Parity with EWasm: familiarising with EWasm [WebAssembly implementation](https://github.com/ewasm); and
- [ ] (ongoing operation): keep track of major [Ethereum Research](https://ethresear.ch) topics.

Note: I have also worked on other projects with Ethereum, mainly docs such as the [Yellow Paper](https://github.com/ethereum/yellowpaper), [EIPs](https://github.com/ethereum/eips), the White paper, the [Ethereum Wiki](https://github.com/ethereum/wiki/wiki), Solidity, [Casper papers](https://github.com/ethereum/research/tree/master/papers); reading and participating on [ethresear.ch](https://ethresear.ch/), as well as reading and learning with these and other areas such as WebAssembly, Javascript and cryptography (and the maths behind it). For day-to-day details of what I've done roughly since June 2017 you can refer to [here](https://docs.google.com/spreadsheets/d/1dDglpWBhWlPyv0tfDntPQc8F-yBsP41wFQnIKgwA068/edit#gid=114542833).

------

At the moment I'm working pro-bono, living off my savings. Once funds are raised or a grant is given by the Ethereum Foundation I can pay other developers. Compensation to developers at this stage can't be offered, as it would depend on some form of revenue, which isn't available at this stage. However, revenue will be more likely to be obtained the more a product is demonstrated. All are welcome to contribute, in the spirit of open-soure code and friendly collaboration. If revenue is obtained it will be shared accordingly and fairly with a budget, after setting up a more formal organization, e.g. controlled in a similar fashion to how the Ethereum Foundation is run. (A grant from the Ethereum Foundation has been applied for, as per [this blog post](https://blog.ethereum.org/2018/01/02/ethereum-scalability-research-development-subsidy-programs/).) If you are interested in making a donation but would prefer to not send it to an individual, please say so on Gitter (click the badge above). It's probably best to have an MVP, or alpha or beta release, before actively raising funds.

After comparing Rust and C++, and Parity and cppethereum, Rust and Parity seem like better options. Rust has advantages such as better memory safety, while it also is compatible with Wasm. More details are here: https://gitter.im/ewasm/Lobby?at=5a92381135dd17022eedc444. Additionally, [Go is not compatible with Wasm at present](https://github.com/golang/go/issues/18892), so [Go-ethereum isn't either](https://github.com/ethereum/go-ethereum/issues/16192).

For an introduction to Ethereum, see https://github.com/ethereum/wiki/wiki/Ethereum-introduction.

For an introduction to sharding, see https://github.com/ethereum/wiki/wiki/Sharding-and-stateless-client-implementations.

This repo and the Drops of Diamond project it belongs to is not a part of or owned by the Ethereum Foundation, nor is it endorsed by the Foundation. A different project name and logo may be used (the logo could use a more modern design rather than just using a photo in the public domain), and alternative proposals are welcome. The Drops of Diamond project is not legally incorporated as of yet, so legally it is not an organisation. That should be done, but probably only as needed once the project is more well-developed.
