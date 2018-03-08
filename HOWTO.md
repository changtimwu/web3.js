due to npm/yarn can't add subdirectory as package source
please refer to
* https://github.com/npm/npm/issues/2974
* https://github.com/yarnpkg/yarn/issues/4725

to use this customized web3.js.  please clone
```
git clone git@github.com:changtimwu/web3.js.git -b 1.0
```

In your JS project, change web3 source to
```
yarn add ../web3.js/packages/web3
```
