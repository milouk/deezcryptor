# nodeezcryptor

This is a fork from https://codeberg.org/exttex/nodeezcryptor with MacOS support

## Installation

### Linux:

Install your OS OpenSSL libraries.   
Ubuntu: `apt install libssl-dev`  

### Windows:

OpenSSL Precompiled libraries & header files are now included in this repo.

### Macos:

OpenSSL Precompiled libraries & header files are now included in this repo.

## package.json:
  "nodeezcryptor": "git+https://github.com/milouk/deezcryptor",

## Example:

    const decryptor = require('decryptor');

    //Get Key:
    decryptor.getKey("trackID");

    //Decrypt File:
    decryptor.decryptFile("key", "inputFilename", "outputFilename");
