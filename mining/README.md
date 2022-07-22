---
description: >-
  PoW is still CryptoNight Lite v7. Please make sure your wallet and daemon are
  v6.x to prevent synchronization issues
---

# Mining

**Official Mining Pool:** [https://pool.bbscoin.click/](https://pool.bbscoin.click/)

**Mining Pool Host Address:** mine.bbscoin.click (_Host to use/connect in mining software._)

**Mining Ports**

| Connection Port | Starting Difficulty | Description                |
| --------------- | ------------------- | -------------------------- |
| 3334            | 10000               | Low end hardware           |
| 3335            | 20000               | Low end hardware           |
| 3336            | 50000               | Low end hardware           |
| 5556            | 100000              | Mid range hardware         |
| 7778            | 500000              | High end hardware          |
| 8889            | 2500000             | Professionals and NiceHash |

#### Configuration tip

For optimal mining efficency use static difficutly. You can activate static difficutly by adding ".desiredDifficutly" to your walletid. You can use any of the above ports for static difficutly.\


A good static difficutly would be 40 \* hashrate. Example for 1250H/s:

**Ex.:**`fyTpS7UgsfTJaGWxKoBcYNAie7ZXkia8UKarA8mAEnusGpM1JQPAzvFd6S8fpDR7WgEN9wTVL6vdBe3PjPmqafpm2PogvpQna.50000`

#### Mining Apps(there may be more around)

| XMR-Stak | CPU / GPU (choose bbscoin as currency) | [Github](https://github.com/fireice-uk/xmr-stak/releases) | [Reddit](https://www.reddit.com/r/Monero/comments/5lsfgt/xmrstakcpu\_high\_performance\_open\_source\_miner/) | [Github](https://github.com/fireice-uk/xmr-stak) |
| -------- | -------------------------------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| XMRig    | CPU / GPU (set --variant=1)            | [Github](https://github.com/xmrig/xmrig/releases)         |                                                                                                               |                                                  |
