1. Install prerequisites

- [Git](https://www.atlassian.com/git/tutorials/install-git)
- [Node](http://nodejs.org/) v16 (To manage multiple node versions we recommend [nvm](https://github.com/nvm-sh/nvm#installing-and-updating))


2. Install package manager (Yarn)

```
nvm install
npm -g install yarn
```

3. Clone the repo by running the command below in terminal.

```
git clone git@github.com:NASA-IMPACT/veda-config.git --recursive
```

4. Run setup script by running the command below in terminal

```
./.veda/setup
```

5. Follow [Usage](https://github.com/NASA-IMPACT/veda-config/blob/develop/docs/SETUP.md#usage) step  in setup doc. Reach out to me for Mapbox token. 
   
6. Start local dev environment by running the command below in terminal.
```
yarn serve
```
