## Carry Trade Examples

#### Below is a simulated carry trade resulting in a loss of ¥45,548, or about -0.46% over one year.

##### Key insight:

Although the interest rate differential was favorable (4.5% - 0.1%), the foreign exchange rate volatility (AUD depreciating against JPY) completely erased all prior gains resulting in a loss.

Additional examples include

###  Hedged FX Carry Trade (Classic + Hedge)
#### Using a delta-hedge on a forward contract on AUD, we lock in the future exchange rate, and are able eliminate FX volatility.
##### Hedging ensures your return equals the interest-rate spread (approx. 4.4%), regardless of FX moves.

### Crypto Carry Trade on DeFi
#### Scenario:
Borrow USDC at 4% APR
Lend USDC in DeFi pool earning 8% APR
Net carry = 4%, before fees

## Back Test with Real Interest Rate Data 
### The back test version includes liquidation and gas fee costs in our Defi simulation.


#### Real Interest Rate Data:
Current Aave USDC rates (Ethereum mainnet V3):

#### Supply APR ~3.36%, Borrow APR ~4.73% 
medium.com
+15
aavescan.com
+15
arxiv.org
+15

#### Governance recommendation (Mar '25): borrow rate target ~6.5% for stablecoins 
governance.aave.com

#### We'll assume:

Borrow APR = 6%
Supply APR = 9%
(reflecting potential higher rates in other pools like Morpho)

### Simulation Model
#### Setup:
Initial USDC collateral: $100,000

Borrow 50% LTV ($50,000 USDC at 6%)

Supply borrowed at 9%

Duration: 180 days

Gas + transaction fees: $50 total

Liquidation threshold: 78%, penalty = 5% 
banque-france.fr
+15
bankofcanada.ca
+15
krayondigital.com
+15
bitdegree.org
+1
arxiv.org
+1
governance.aave.com
coingecko.com
+1
milkroad.com
+1
medium.com
+1
bitdegree.org
+1
app.aave.com
+1
medium.com
+1

Simulated ETH volatility triggers liquidation with 10% chance over 6 months if ETH used as collateral.

