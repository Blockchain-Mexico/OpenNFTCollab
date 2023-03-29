# OpenNFTCollab

A JavaScript library for crypto-native ecommerce: buying, selling, and bidding on any cryptogood. With OpenSea.js, you can easily build your own native marketplace for your non-fungible tokens, or NFTs. These can be ERC-721 or ERC-1155 (semi-fungible) items. You don't have to deploy your own smart contracts or backend orderbooks.**

**
Installation
Switching to Node.js version 16 is required for SDK Version 3.0+ and to make sure common crypto dependencies work. Execute nvm use, if you have Node Version Manager.

Then, in your project, run:

npm install --save opensea-js
Warning Due to the use of git-url dependencies, versions of npm below 8.5.2 are incompatible with this package due to broken integrity checksum validation. Above version 8.5.2, npm will no longer validate integrity checksums for git-url dependencies.

Install web3 too if you haven't already.

If you run into an error while building the dependencies and you're on a Mac, run this:

xcode-select --install # Install Command Line Tools if you haven't already.
sudo xcode-select --switch /Library/Developer/CommandLineTools # Enable command line tools
sudo npm explore npm -g -- npm install node-gyp@latest # (Optional) update node-gyp


