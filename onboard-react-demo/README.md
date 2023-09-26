# React Demo

This code has been copied from the [official onboard demo](https://github.com/blocknative/react-demo).

Just a heads up: this demo requires ssl on localhost.

If you run into a situation where you can not proceed to the site: \
just type `thisisunsafe` after clicking on an empty space in the window

---

A repository to demonstrate a basic integration of 
[Web3 Onboard](https://github.com/blocknative/web3-onboard) into a React project. 
For detailed documentation, head to [onboard.blocknative.com](hhttps://onboard.blocknative.com/docs/overview/introduction)


<div align="center">
  <img style="border-radius: 8px" width="75%" src="assets/web3-onboard-react.png">
</div>

View live demo [here](https://reactdemo.blocknative.com/)!

## Getting started

Clone the repo:

```bash
git clone https://github.com/blocknative/react-demo.git
```

Navigate to the project directory:

```bash
cd react-demo
```

Install the dependencies:

```bash
yarn
```

Start the development server:

```bash
yarn start
```

The project will be running on [localhost:3000](http://localhost:3000)

### SSL
Some wallets require that the website within which it runs by using an https 
connection. If you are testing one of these wallets, Ledger is one, then you have
two options:
 1. Setup a valid certificate for localhost using [this guide](https://www.freecodecamp.org/news/how-to-set-up-https-locally-with-create-react-app/).
 2. Allow invalid certificates for resources loaded from localhost by navigating here within a chrome based browser: [chrome://flags/#allow-insecure-localhost](chrome://flags/#allow-insecure-localhost)