# Yggdrasil Essence for Electron-forge

Copyright © 2025 [Yggdrasil Leaves, LLC.](https://yggdrasil-leaves.com)

## What's it?

These are useful extra features on Electron.  
You can select source files under your wish from this solution and copy freely.  

## Need a Help?

But we'll not help you:-P

## Documentation

see web version that placed in web submodule.  
to build by Doxygen.  
see web/README.md  

## Required Packages

see package.json  
and update them.
```
$ npm update
```

### for Windows

Can one touch installing with setup.bat

## Test Run

```
$ npm start
```
### for Windows

Can one touch running with run.bat

## Build to an Application

```
$ npm run make
```

see out/YggdrasilEssenseExamples-*/  
and run YggdrasilEssenseExamples

### for Windows

Can one touch building with build.bat

## Tips

### Show Packaged Files

forge.config.js

```
module.exports = {
  packagerConfig: {
    asar: false,

	:

      [FuseV1Options.OnlyLoadAppFromAsar]: false,
    }),
  ],
};

```

build and see out/YggdrasilEssenseExamples-*/resources  
(for debug, and not recommended for release)  


