# eth\_getTransactionReceipt

Returns the transaction receipt of a specific transaction hash. Note that this isn't available for any transactions that hasn't been confirmed yet.

**Request Payload**`{txnHash}` - Transaction hash.

**Result Fields**`{txnReceipt}` - Transaction receipt object, or null when no receipt was found.

`{txnHash}` - Hash of the transaction.&#x20;

`{txnIndex}` - Integer of the transactions index position in the block. `{blockHash}` - Hash of the block where the transaction was placed. `{blockNumber}` - Number of the block where the transaction was placed.&#x20;

`{from}` - Address of the sender.&#x20;

`{to}` - Address of the receiver.&#x20;

`{cumulativeGasUsed}` - Total amount of gas used by the block.&#x20;

`{gasUsed}` - Amount of gas used by the specific transaction.&#x20;

`{contractAddress}` - The contract address created, or null if no new contract was created.&#x20;

`{logs}` - Array of log objects.&#x20;

`{logsBloom}` - Bloom filter for light clients.&#x20;

`{status}` - Boolean for success or failure.
