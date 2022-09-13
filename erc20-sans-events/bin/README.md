The bytecode here deploys the presets/ERC20PresetFixedSupply.sol contract with f0100 as the owner actor.
It deploys a token called "littlecoin" with symbol LIT, and total supply 1000000 LIT.
To deploy with a different owner actor or parameters, you will need to generate the right init code.
You can do that using https://remix.ethereum.org/ and generating a deployment transaction with the new
constructor parameters.
