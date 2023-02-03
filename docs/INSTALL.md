1. Install prerequisites

- [Git](https://www.atlassian.com/git/tutorials/install-git)
- [Node](http://nodejs.org/) v16 (To manage multiple node versions we recommend [nvm](https://github.com/nvm-sh/nvm#installing-and-updating))

1. (If using NVM) Install matching Node version by running the command below
```
nvm install
```

1. Install package manager (Yarn)

```
npm -g install yarn
```

4. Clone the repo by running the command below in terminal.

```
git clone git@github.com:NASA-IMPACT/veda-config.git --recursive
```

5. Run setup script by running the command below in terminal

```
./.veda/setup
```

6. Follow [Usage](https://github.com/NASA-IMPACT/veda-config/blob/develop/docs/SETUP.md#usage) step  in setup doc. Reach out to DevSeed for Mapbox token. 
   
7. Start local dev environment by running the command below in terminal.
```
yarn serve
```
