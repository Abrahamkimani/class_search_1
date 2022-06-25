This contract registers students in an online class

The contract helps the tr to keep track of the students present

and absent in an online class



*near commands: 
Test the contract:
  `cargo test `

*Build the contract:
  'cargo build --target wasm32-unknown-unknown --release`
 
 *To deploy the code:
 eg
  'near deploy --wasmFile target/wasm32-unknown-unknown/release/class_search_1.wasm --accountId kimani.testnet'
 
*To call any function:
eg
 'near call abraham.kimani.testnet register_student '{"name": "kimani", "admission":"210"}' --accountId kimani.testnet

