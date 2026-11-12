<div align="center">

<img src="./banner.svg" width="860" alt="Mayur Bhil, Full-Stack and DevOps Engineer" />

<br />

# gm, I'm Mayur 👋
### Full-stack dev learning Web3, one block at a time ⛓️

![Ethereum](https://img.shields.io/badge/Ethereum-learning-627EEA?style=for-the-badge&logo=ethereum&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-learning-363636?style=for-the-badge&logo=solidity&logoColor=white)
![IPFS](https://img.shields.io/badge/IPFS-exploring-65C2CB?style=for-the-badge&logo=ipfs&logoColor=white)
![Polygon](https://img.shields.io/badge/Polygon-exploring-7B3FE4?style=for-the-badge&logo=polygon&logoColor=white)

![Followers](https://img.shields.io/github/followers/Mayur-Bhil?style=flat-square&labelColor=0d1117&color=627EEA&logo=github)
![Repos](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FMayur-Bhil&query=%24.public_repos&label=repos&style=flat-square&labelColor=0d1117&color=a78bfa)
![Status](https://img.shields.io/badge/open_to-freelance_projects-39d353?style=flat-square&labelColor=0d1117)

<br />

<details>
<summary><b>🦊 &nbsp;Connect Wallet &nbsp;(click me)</b></summary>

<br />

**✅ Connected. Gas fee: 0 ETH. Pick a channel:**

[![LinkedIn](https://img.shields.io/badge/linkedin-mayur--bhil-0d1117?style=for-the-badge&logo=linkedin&logoColor=0077B5)](https://linkedin.com/in/mayur-bhil)
[![X](https://img.shields.io/badge/x-@IamMayur__01-0d1117?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/IamMayur_01)
[![Email](https://img.shields.io/badge/email-send_a_message-0d1117?style=for-the-badge&logo=gmail&logoColor=D14836)](mailto:mayurbhil47@gmail.com)

</details>

</div>

<br />

## `$ node status`

```text
INFO [2026-11-12|09:41:07] Starting node            client="Mayur/full-stack-v3"  network="Surat, India"
INFO [2026-11-12|09:41:07] Loaded modules           frontend=React,Next.js  backend=Node,Express,MongoDB
INFO [2026-11-12|09:41:08] Loaded modules           devops=Docker,AWS,CI/CD  tools=Git,Linux,Python
INFO [2026-11-12|09:41:08] Syncing                  chain=Ethereum  skills=Solidity,smart-contracts  mode=learning-in-public
INFO [2026-11-12|09:41:09] Peer discovery           looking_for="freelance projects, early-stage dApps, builders"
INFO [2026-11-12|09:41:09] Node is live            status=OPEN_FOR_WORK
```

<br />

## `$ whoami`

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.24;

contract Mayur {
    string public name       = "Mayur Bhil";
    string public location   = "Surat, Gujarat, India";
    string public role       = "Full-Stack Developer, Web3 Learner";
    string public building   = "MERN, Next.js, Docker, AWS, now smart contracts";
    bool   public openToWork = true;   // freelance projects welcome

    function hire() external pure returns (string memory) {
        return "Let's build something great together.";
    }
}
```

I build clean, fast web apps from database to deployment, and I'm now taking that skill set on-chain: learning Ethereum, Solidity and dApp development in public. I also study Finance (MBA), which is exactly why DeFi pulls me in.

> [!NOTE]
> **Open for freelance projects.** Got an idea, a web app, or an early-stage dApp frontend? Message me on
> [LinkedIn](https://linkedin.com/in/mayur-bhil) or [email me](mailto:mayurbhil47@gmail.com).

<br />

## `$ my career, mined as a blockchain ⛏️`

Every block below is **real SHA-256 proof-of-work**, and each block commits to the hash of the one before it. Change one word of my history and every hash after it breaks.

```math
H_n = \mathrm{SHA256}\left(n \,\|\, H_{n-1} \,\|\, \mathrm{data}_n \,\|\, \mathrm{nonce}_n\right), \qquad H_n \text{ must start with } 0000
```

| # | Block data | Nonce | Hash (SHA-256) | Prev |
| :-: | :--- | --: | :--- | :--- |
| **0** | Joined GitHub, 13 Aug 2023 | `76073` | `0000d7feff4250…` | `00000000…` |
| **1** | Learned the MERN stack | `95524` | `0000fcb259e417…` | `0000d7fe…` |
| **2** | Shipped blinkit, a full-stack grocery app | `13059` | `0000d03fea5e23…` | `0000fcb2…` |
| **3** | Built devTinder: real-time chat and matching | `42334` | `0000654b39f709…` | `0000d03f…` |
| **4** | Built g-docs: real-time collaborative docs | `2382` | `0000aab69871f2…` | `0000654b…` |
| **5** | Deployed a monorepo with Docker | `27072` | `0000e2e30cee29…` | `0000aab6…` |
| **6** | Started the Web3 journey: Ethereum and smart contracts | `29224` | `000066f36f4602…` | `0000e2e3…` |
| ⏳ | _Pending: deploy my first smart contract to a testnet_ | | _in the mempool_ | |
| ⏳ | _Pending: ship a full dApp, frontend to contract_ | | _in the mempool_ | |

<details>
<summary><b>🔍 Verify it yourself (Python, no dependencies)</b></summary>

<br />

```python
import hashlib

def block_hash(i, prev, data, nonce):
    return hashlib.sha256(f"{i}|{prev}|{data}|{nonce}".encode()).hexdigest()

# Block 0: genesis block, prev = 64 zeros
print(block_hash(0, "0" * 64, "Joined GitHub, 13 Aug 2023", 76073))
# -> 0000d7feff425090ad1139078cd1c32e608d09fc6811cdc16fb6391eca7d6588
```

Each next block uses the full hash of the previous block as `prev`. The table above shows the first 14 characters of each hash.

</details>

<br />

## `$ web2 → web3`

```mermaid
flowchart LR
    A([👤 User]) --> B[React / Next.js]
    B --> C[ethers.js / wagmi]
    C --> D{{📜 Smart Contract}}
    D --> E[(⛓️ Ethereum / L2)]
    B --> F[Node + Express]
    F --> G[(MongoDB)]
    F -. indexes events .-> E
    classDef web2 fill:#0d1117,stroke:#00d9ff,color:#e6edf3
    classDef web3 fill:#0d1117,stroke:#627EEA,color:#e6edf3
    class A,B,F,G web2
    class C,D,E web3
```

My edge: I can build the **whole product**, from the wallet-connected frontend to the backend that indexes the chain, instead of only one layer.

<br />

## `$ my universe`

```mermaid
mindmap
  root((Mayur))
    Frontend
      React
      Next.js
      Tailwind
    Backend
      Node.js
      Express
      MongoDB
    DevOps
      Docker
      AWS
      CI/CD
    Web3
      Ethereum
      Solidity
      dApps
    Finance
      MBA
      DeFi curiosity
```

<br />

## `$ stack`

<div align="center">

<img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,nodejs,express,mongodb,tailwind&theme=dark" alt="Web stack" />
<br /><br />
<img src="https://skillicons.dev/icons?i=docker,aws,git,github,linux,python,vscode&theme=dark" alt="DevOps and tools" />

</div>

<br />

## `$ roadmap` &nbsp;·&nbsp; learning in public

| Phase | Focus | Status |
| :-: | :--- | :-: |
| **1** | Solidity fundamentals, Remix, testnets | 🟡 in progress |
| **2** | Hardhat or Foundry: build, test, deploy | ⚪ next |
| **3** | ERC-20 and ERC-721 with OpenZeppelin | ⚪ next |
| **4** | ethers.js / wagmi: connect a Next.js frontend | ⚪ next |
| **5** | IPFS storage and L2 deployment (Polygon) | ⚪ next |
| **6** | Ship a full dApp and open-source it | ⚪ goal |

<br />

## `$ projects`

| Project | What it does | Built with |
| :--- | :--- | :--- |
| [**web3-things**](https://github.com/Mayur-Bhil/web3-things) | My Web3 experiments and learning, in public | Web3 |
| [**blinkit**](https://github.com/Mayur-Bhil/blinkit) | Full-stack grocery e-commerce app: browse products, manage carts, secure checkout | MERN |
| [**devTinder-app**](https://github.com/Mayur-Bhil/devTinder-app) | Connect, chat in real time and build new friendships or professional networks | MERN |
| [**g-docs**](https://github.com/Mayur-Bhil/g-docs) | Real-time collaborative documents with a notification system | TypeScript |
| [**todo-app**](https://github.com/Mayur-Bhil/todo-app) | Monorepo deployment with Docker, a hands-on DevOps build | Docker, TypeScript |
| [**medium**](https://github.com/Mayur-Bhil/medium) | A full-stack blogging platform | TypeScript |

<br />

## `$ services`

| | Service | What you get |
| :-: | :--- | :--- |
| **01** | **Frontend and dApp UIs** | Fast, responsive React and Next.js interfaces, including wallet-connected frontends |
| **02** | **Full-Stack Applications** | End-to-end web apps with Node.js, MongoDB and clean APIs |
| **03** | **Performance Optimization** | Faster load times and smoother UX for apps you already have |
| **04** | **Cloud Deployment** | Docker, AWS and CI/CD to deploy and scale with confidence |

<br />

## `$ builder card` &nbsp;·&nbsp; ERC-721 metadata

```json
{
  "name": "Mayur Bhil #001",
  "description": "Full-stack developer from Surat, learning Web3 in public.",
  "external_url": "https://github.com/Mayur-Bhil",
  "attributes": [
    { "trait_type": "Role",      "value": "Full-Stack Developer" },
    { "trait_type": "Chain",     "value": "Ethereum (learning)" },
    { "trait_type": "Stack",     "value": "MERN + Next.js" },
    { "trait_type": "DevOps",    "value": "Docker + AWS" },
    { "trait_type": "Location",  "value": "Surat, India" },
    { "trait_type": "Rarity",    "value": "1 of 1" },
    { "trait_type": "Available", "value": "Freelance" }
  ]
}
```

<br />

## `$ my node 📡`

```geojson
{"type":"FeatureCollection","features":[{"type":"Feature","properties":{"title":"Node: Surat, Gujarat, India","description":"Online, building, open for the world.","marker-symbol":"star","marker-color":"627EEA","marker-size":"large"},"geometry":{"type":"Point","coordinates":[72.8311,21.1702]}}]}
```

<br />

## `$ on-chain activity`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Mayur-Bhil/Mayur-Bhil/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mayur-Bhil/Mayur-Bhil/output/github-snake.svg" />
  <img width="860" alt="Contribution snake" src="https://raw.githubusercontent.com/Mayur-Bhil/Mayur-Bhil/output/github-snake.svg" />
</picture>

<br /><br />

**[LinkedIn](https://linkedin.com/in/mayur-bhil)** &nbsp;·&nbsp; **[Email](mailto:mayurbhil47@gmail.com)** &nbsp;·&nbsp; **[X / Twitter](https://twitter.com/IamMayur_01)**

<sub>WAGMI · building in public, one block at a time ⛓️</sub>

</div>
