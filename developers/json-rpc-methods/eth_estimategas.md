# eth\_estimateGas

Returns an estimate of how much gas will be needed for the transaction to complete. When estimating gas, the transaction will not be automatically added to the network. This cannot be used as a hard indicator, as fluctuations on gas prices can occur very quickly, making estimates inaccurate after just a few seconds.

**Request Payload**_Transaction Call Object_`{from}` - Address from which the transaction is sent.&#x20;

**\* Optional**&#x20;

`{to}` - Address to which the transaction will be directed. `{gas}` - Integer of gas provided for transaction.&#x20;

**\* Optional**&#x20;

`{gas_price}` - Integer of the gas price used for each paid gas.&#x20;

**\* Optional**&#x20;

`{value}` - Integer of the value sent with this transaction.&#x20;

**\*Optional**&#x20;

`{data}` - Hash of the method signature and encoded parameters.&#x20;

**\* Optional**

**Result Fields**`{gas_used}` - The amount of gas estimated to be necessary for the transaction to complete.
