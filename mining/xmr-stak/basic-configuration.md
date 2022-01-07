# Basic configuration

In the following configuration example, we will be setting xmr-stak to use just an AMD GPU.

Copy the following JSON settings into your text editor and save it as text file called: pools.txt, in to the xmr-stak folder where it contains the executable files.

```json
"pool_list" :
[
	{
		"pool_address" : "mine.bbscoin.click:PORT",
		"wallet_address" : "REPLACE_ME_WITH_YOUR_WALLET_ADDRESS_AND.DIFFICULTY",
		"rig_id" : "",
		"pool_password" : "x",
		"use_nicehash" : false,
		"use_tls" : false,
		"tls_fingerprint" : "",
		"pool_weight" : 1
	},
],
"currency" : "bbscoin",
```

Replace the PORT in "pool\_address" to match a your desired difficulty port from the [Mining](../) page. Should look like "mine.bbscoin.click:3336". Then, change the "wallet\_address" to your walletAddress.difficulty | Making it look similar to this, but with your address and difficulty.

`fyTpS7UgsfTJaGWxKoBcYNAie7ZXkia8UKarA8mAEnusGpM1JQPAzvFd6S8fpDR7WgEN9wTVL6vdBe3PjPmqafpm2PogvpQna.50000`

We will navigate to the xmr-stak folder, and run: `./xmr-stak --noCPU --noNVIDIA` . This tells it to not load those drivers, so only the AMD GPU drivers will be loaded.

xmr-stak: Use simple setup method? (Y/n) : `Y [ ENTER ]`&#x20;

