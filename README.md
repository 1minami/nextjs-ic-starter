# Next.js Internet Computer Starter Template

This project provides a simple starter template for Dfinity Internet Computer using Next.js framework as frontend.

**Backend**

- A simple greeting hello world canister written in Motoko
- ImageBucket canister written in Motoko with create image, delete image and getImageById

**Frontend**

- A simple React HTML form with name input, sending it to greet canister and showing the returned result
- An Image Upload HTML form with Pick an Image button, upload the image to image canister, loading the image back from the canister and display it using useImageObject React Hook

## Original repo

https://github.com/dappblock/nextjs-ic-starter

## Original video

https://www.youtube.com/watch?v=8ElPDw0laIo

## Quick Start (Run locally)

Install:

- NodeJS 16.\* or higher https://nodejs.org/en/download/
- Internet Computer dfx CLI https://sdk.dfinity.org/docs/quickstart/local-quickstart.html
- Visual Studio Code (Recommended Code Editor) https://code.visualstudio.com/Download
- VSCode extension - Motoko (Recommended) https://marketplace.visualstudio.com/items?itemName=dfinity-foundation.vscode-motoko

```bash
sh -ci "$(curl -fsSL https://sdk.dfinity.org/install.sh)"
```

Clone this Git repository:

```bash
git clone https://github.com/dappblock/nextjs-ic-starter
```

Open command terminal:
Enter the commands to start dfx local server:

```bash
cd nextjs-ic-starter
dfx start
```

Note: If you run it in MacOS, you may be asked to allow connections from dfx local server.

Enter the commands to install dependencies, deploy canister and run Next.js dev server:

```bash
yarn install
dfx deploy
yarn run dev
```

Open in Chrome the following URL to try the demo app:  
http://localhost:3000/

Cleanup - stop dfx server running in background:

```bash
dfx stop
```

Note: CSS frame & get random number

```bash
yarn add bulma
yarn add @chainlink/contracts
```

## Quick Start 

**① Connect Wallet**

Rinkeby testnet

**②Play now**

Bet on 0.11ETH

**③Pick winner**

Admin only: Pick winner

**④Pay winner**

Interesting if there are many participants.

## License

MIT
