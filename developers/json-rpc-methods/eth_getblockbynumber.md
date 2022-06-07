# eth\_getBlockByNumber

Returns information about a specific block.

**Request Payload**`{blockParameter}` - A integer block number, or the string 'latest', 'earliest', or 'pending'. `{showTxnDetailsFlag}` - True for full txn objects, and false for only hashes.

**Result Fields**`{block}` - A block object, or null when no block was found.

`{number}` - The block number, or null if the block is pending.&#x20;

`{hash}` - The block hash, or null if the block is pending. `{parentHash}` - Hash of the parent block.&#x20;

`{nonce}` - Hash of the generated PoW, or null when the block is pending.&#x20;

`{sha3Uncles}` - SHA3 of uncles' data in the block.&#x20;

`{logsBloom}` - Bloom filter for the logs, or null when the block is pending.&#x20;

`{txnsRoot}` - Root of the txn trie of the block. `{stateRoot}` - Root of the final state trie of the block.&#x20;

`{receiptsRoot}` - Root of the receipts trie of the block.&#x20;

`{miner}` - Beneficiary of the mining rewards.&#x20;

`{difficulty}` - Integer of difficulty of the block. `{totalDifficulty}` - Integer of the total difficulty of the chain until this block.&#x20;

`{extraData}` - Extra data field of the block. Usually the validator's nickname.&#x20;

`{size}` - Size of the block in bytes.&#x20;

`{gasLimit}` - Maximum gas allowed in this block.&#x20;

`{timestamp}` - The unix timestamp for when the block was collated. `{txns}` - Array of transaction objetcs.&#x20;

`{uncles}` - Array of uncle hashes.
