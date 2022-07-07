# Protocol

## Dual Coin
The price of FRAX, FXS, and collateral are calculated using a time-weighted average of the Uniswap pair price and the ETH:USD Chainlink oracle. 

### FRAX 
USD-pegged fractional/algorithmic stablecoin.Initial FXS supply of 100m at genesis - more FRAX used the more FXS value rises as minting FRAX needs FXS to be burned (decreasing supply and driving up prices).

### FXS
Dual coin, governance token of ecosystem, absorbs/drains excess volatility. As FXS value increases the cost to mint FRAX grows and the collateral value rises thus 
- dampening the flow of FRAX into ecosystem 
- apply positive pressure to the peg. Since the minting of FRAX seen before that led to FXS price increase would have appleid negative pressure on peg - the overall effect is more stable peg.

## Frax v2: AMOs
Frax v2 launched the Algorithmic Market Operations modules, or AMO. An AMO creates smoother operations for Frax by automating the movement of FRAX and its collateral across the DeFi ecosystem. 

The Frax AMOs further enable FRAX growth by leveraging Frax’s assets in a capital efficient way by programmatically moving collateral and/or FRAX to capital efficient locations depending on the collateral ratio. 

## FXS1559
FXS1559 is an in-protocol rule that all AMOs  utilize - it calculates excessss value in ecosystem (liqudity >  collateral ratio) and buys same amoutn of FXS burning. 

Till late 2021, FXS1559 used 50% of value to buy then burn FXS (increasing FXS price by decreasing supply) and 50% was given directly to Curve FXS (veFXS) holders (thus they benefitted twice in effect).

Since October 2021, FXS1559 disburses 100% of AMO profits to veFXS holders - to foster  locking FXS in Frax protocol via veFXS, rather than pure FXS hold.

