# immutable contract

## Build
```sh
# build the debug version
node cli.js build-all --generate_authorize immutable debug immutable.proto 

# build the release version
node cli.js build-all --generate_authorize immutable release immutable.proto 
```

## Upload
```sh
# using the Koinos CLI
upload immutable/build/release/contract.wasm immutable/abi/immutable.abi false false true
```