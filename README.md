# How-To-Mine-Xelis: A Step-by-Step Guide

Xelis is a decentralized blockchain that uses a unique Proof of Work (PoW) consensus algoritm (XelisHashV2) to ensure security and integrity. What sets Xelis apart from many other blockchains is its mining approach, which is optimized for both CPU and GPU mining. This guide will walk you through the process of mining Xelis using third-party software and provide options for both CPU and GPU mining.

**Prerequisites: Before you start mining Xelis, you’ll need a few things:**

A computer with either a CPU or GPU that meets the minimum requirements for mining.
A wallet address to receive the XELIS tokens you mine. You can create a wallet here: https://xelis.org/resources
Third-party mining software (listed below).
Either a solo mining node or a mining pool to connect to.

**Step 1: Choose Your Mining Software**
There are a few options for mining Xelis, depending on whether you are using a CPU or GPU. Here’s a breakdown of the available mining software:

- CPU Mining Options:

  - SRB Miner: SRB Miner is a powerful mining software for CPUs that supports Xelis. It's easy to set up and provides excellent performance for solo or pool mining.
GitHub: [SRB Miner GitHub](https://github.com/doktor83/SRBMiner-Multi/releases)

  - TNNminer: TNNminer is another great CPU mining option for Xelis. It’s optimized for memory-intensive algorithms and offers good efficiency for solo or pool mining.
GitHub: [TNNminer GitHub](https://github.com/Tritonn204/tnn-miner/releases)

- GPU Mining Options:

  - OneZeroMiner: OneZeroMiner supports both Nvidia and AMD GPUs, making it a versatile mining software for anyone using a GPU to mine Xelis. This miner is well-optimized for the Xelis network and is one of the most popular choices.
GitHub: [OneZeroMiner GitHub](https://github.com/OneZeroMiner/onezerominer/releases)

  - Rigel Miner: Rigel Miner is designed specifically for Nvidia GPUs and offers high performance for those who have Nvidia hardware. If you have an Nvidia GPU, this software is a great choice for mining Xelis.
GitHub: [Rigel Miner GitHub](https://github.com/rigelminer/rigel/releases)

**Step 2: Download and Install the Mining Software**

Once you’ve selected your preferred mining software, you’ll need to download and install it. Here’s a general guide:

Visit the respective GitHub page of the mining software you’ve chosen.
Download the latest release or clone the repository to your local machine.
Follow the installation instructions provided in the README file or on the GitHub page.
For most miners, you’ll need to extract the files and configure the mining software by editing a configuration file (usually a .bat or .config file).

**Step 3: Configure Your Miner**

After installing the software, you’ll need to configure it. Each miner has slightly different configuration steps, but most miners require the following:

- Wallet Address: Enter your Xelis wallet address where the mined tokens will be sent.

- Mining Pool or Solo Mining: Choose whether you want to mine solo or connect to a mining pool (more on this below).

- Pool or Node Address: If mining in a pool, use the pool’s address. For solo mining, you'll need to configure your own Xelis node (see below for instructions on setting up your own node).

  - For Solo Mining: To mine solo, you’ll need to run your own Xelis node. You can find the instructions on how to set up a Xelis node here:
    - Build from Source: https://docs.xelis.io/getting-started/build-from-source-code or
    - Download Precomplied Software: https://docs.xelis.io/getting-started/download-binaries

  - For Mining Pools: If you prefer not to mine solo, you can join a mining pool. Mining pools increase your chances of earning rewards by combining the hashing power of multiple miners. A great resource to choose a mining pool is https://miningpoolstats.stream/xelis Please do not select the pool with the top hashrate as it is important to decentralize hashrate across pools. Pick a pool from the list, and use the provided mining pool address in your mining software configuration file.

**Step 4: Start Mining**

Once you’ve configured the software, run the miner. It will start hashing and working on solving blocks for the Xelis blockchain.

- Solo Mining: If you are mining solo, the software will connect directly to your Xelis node and begin mining.
- Mining Pool: If you’ve selected a mining pool, the software will connect to the pool’s server and start contributing to the collective effort of solving blocks.
  
**Step 5: Monitor and Optimize Your Mining**

Once your miner is running, you’ll want to monitor your mining performance to ensure it’s running efficiently. Many miners provide real-time stats in the console or through a web interface.

Check for mining errors, hash rate, and temperature.
Adjust settings such as clock speeds and power limits for optimal performance (especially with GPU mining).
If you're using a mining pool, you can also track your earnings and see how much you've contributed to the pool.

**Final Thoughts**

Mining Xelis is a rewarding process, especially if you have the right hardware and software. Whether you choose to mine with your CPU or GPU, the flexibility of Xelis’ mining algorithm allows you to get involved regardless of your equipment. By following this guide, you'll be able to set up your mining software, configure your settings, and start earning XELIS tokens in no time!

Happy mining!

Disclaimer: XELIS IS NOT RESPONSIBLE FOR ANY THIRD PARTY MINING SOFTWARE OR MINING POOLS. AS ALWAYS USE AT YOUR OWN RISK.







