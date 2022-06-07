# eth\_call

Executes a new message call without creating a transaction.

**Request Payload**_Transaction Call Object_`{from}` - Address from which the transaction is sent. `{to}` - Address to which the transaction will be directed. `{gas}` - Integer of gas provided for transaction.&#x20;

**\* Optional** `{gas_price}` - Integer of the gas price used for each paid gas.&#x20;

**\* Optional** `{value}` - Integer of the value sent with this transaction. **\*Optional** `{data}` - Hash of the method signature and encoded parameters.&#x20;

**\* Optional** _Block Parameter_`{block_parameter}` - Integer block number, or the string 'latest', 'earliest', or 'pending'.

**Result Fields**`{returned_value}` - The returned value of the executed contract method.
