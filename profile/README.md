# MetaMask Embedded Wallets (Web3Auth)

MetaMask Embedded Wallets (formerly Web3Auth) is a pluggable wallet infrastructure that brings non-custodial social login wallets to any application. Users authenticate with familiar OAuth providers — Google, X, Discord, GitHub, and more — and get a secure, recoverable wallet without ever seeing a seed phrase.

- **Non-custodial by design** — private keys are split across multiple parties using Shamir Secret Sharing and MPC. No single party, including MetaMask, ever holds the full key.
- **Chain-agnostic** — built-in providers for EVM and Solana; export the private key for any other chain.
- **Every platform** — Web, React Native, Android, iOS, Flutter, Unity, Unreal, and Node.js.

## SDKs

### Web

| Package | Description |
|---|---|
| [`@web3auth/modal`](https://github.com/Web3Auth/web3auth-web) | Core Web SDK — modal UI and headless mode. Works in any web framework. |
| [`@web3auth/modal/react`](https://github.com/Web3Auth/web3auth-web) | React hooks + native Wagmi integration for React / Next.js / Vite. |
| [`@web3auth/modal/vue`](https://github.com/Web3Auth/web3auth-web) | Vue composables + native Wagmi Vue support for Vue / Nuxt. |

### Mobile

| Package | Description |
|---|---|
| [`@web3auth/react-native-sdk`](https://github.com/Web3Auth/web3auth-react-native-sdk) | React Native — Expo and bare. Built-in EVM and Solana providers. |
| [`Android SDK`](https://github.com/Web3Auth/web3auth-android-sdk) | Kotlin. Export private key; use web3j or similar. |
| [`Swift SDK`](https://github.com/Web3Auth/web3auth-swift-sdk) | iOS. Export private key; use web3swift or similar. |
| [`Flutter SDK`](https://github.com/Web3Auth/web3auth-flutter-sdk) | Dart. Export private key; use web3dart or similar. |

### Gaming

| Package | Description |
|---|---|
| [`Unity SDK`](https://github.com/Web3Auth/web3auth-unity-sdk) | C#. Export private key; use a Unity-compatible EVM library. |
| [`Unreal SDK`](https://github.com/MetaMask/web3auth-unreal-sdk) | C++ / Blueprints. Maintained under the MetaMask org. |

### Backend

| Package | Description |
|---|---|
| [`@web3auth/node-sdk`](https://github.com/Web3Auth/web3auth-backend) | Node.js. Custom auth only (JWT). Per-request stateless key derivation. |

## Get started

1. Create a project at [dashboard.web3auth.io](https://dashboard.web3auth.io) and get a Client ID.
2. Choose **Sapphire Devnet** for local development or **Sapphire Mainnet** for production.
3. Follow the [quick start](https://docs.metamask.io/embedded-wallets/get-started) for your platform.

## Resources

- **Documentation** — [docs.metamask.io/embedded-wallets](https://docs.metamask.io/embedded-wallets/)
- **Dashboard** — [dashboard.web3auth.io](https://dashboard.web3auth.io)
- **Examples** — [github.com/Web3Auth/web3auth-examples](https://github.com/Web3Auth/web3auth-examples)
- **Community & Support** — [builder.metamask.io](https://builder.metamask.io/c/embedded-wallets/5)
