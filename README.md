# Tools we like

### Table of contents

1. [Front end tooling](#front-end-tooling)
1. [Ethereum-related tooling](#ethereum-related-tooling)
1. [Contract development](#contract-development)
1. [Project management](#project-management)

### Front end tooling

##### Mobile
- [React Native](https://react-native.org/)
- [Expo](https://expo.io/) to make it easier to iterate on top of React Native
- [React Navigation](https://reactnavigation.org/)

##### Web
- [React](https://reactjs.org/) (using [Hooks](https://reactjs.org/docs/hooks-intro.html))
- [Create React App](https://create-react-app.dev/) to handle build configuration
- [`emotion`](https://emotion.sh) for styling components on the web with css-in-js
- [React Router](https://github.com/ReactTraining/react-router) v5 for client-side routing
- [Rebass](https://rebassjs.org/) for responsive grid and base component library
- [GitHub Pages](https://pages.github.com/) for hosting

##### Cross-platform

- [TypeScript](https://www.typescriptlang.org/)
- [Apollo Client](https://www.apollographql.com/docs/react/) for querying for indexed data from smart contracts using GraphQL

### Ethereum-related tooling

- [`web3-react`](https://github.com/NoahZinsmeister/web3-react) as an abstraction that lets us easily swap in and out web3 providers (MetaMask, WalletConnect, etc.) and a dev-friendly context containing an instantiated ethers.js instance, the current account, and network id available globally throughout the dapp via a [React Context](https://reactjs.org/docs/context.html).
- [`ethers.js`](https://github.com/ethers-io/ethers.js) v4/v5 for writing data to the contracts
- [The Graph](https://thegraph.com/) for indexing data from the contracts
- [Contract-based accounts](https://contractbasedaccounts.com/) like [Gnosis Safe](https://safe.gnosis.io/), [Argent](https://www.argent.xyz/), [Abridged](https://abridged.io/), [Authereum](https://authereum.org/), and [Universal Login](https://universallogin.io/)
- [ENS](https://ens.domains/)

### Contract development

- [OpenZeppelin](https://openzeppelin.com/)
- [Buidler](https://buidler.dev/)
- [TypeChain](https://github.com/ethereum-ts/Typechain)

### Project management
 - [Canny](https://canny.io/) for feature requests
