# open-oracle-medianizer

> See full discussion here: https://www.comp.xyz/t/building-a-medianizer/1031

## Summary 

This repository is a POC implementation of [Compound Open Oracle](https://compound.finance/docs/prices) medianizer. 
The smart contract allows its governor to set weights of multiple data reporting sources. The final price of a symbol
is the [weighted median](https://en.wikipedia.org/wiki/Weighted_median) of the prices from all the *active sources* 
of which prices are delayed by no more than `MIN_STALE_PRICE` parameter.

Note that this repository is intended to be a POC implementation. Code is neither audited nor optimized yet.

## License
MIT
