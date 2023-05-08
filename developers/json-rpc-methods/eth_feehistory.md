# eth\_feeHistory

Returns a base fee per gas and an effective estimate of the priority fee, using the gas history for the requested block range, if available.

`{blockCount}` and `{newestBlock}` are required parameters.

**Result Fields**`{oldestBlock}` - Oldest block fetched, in hex. `{baseFeePerGas}` - Array of block base fees per gas. `{gasUsedRatio}` - Array of gas used ratios. `{reward}` - Array of effective priority fees per gas data points from a single block.
