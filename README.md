
# Change Log
All notable changes to this project will be documented in this file.
 
 
## [Unreleased] - Expected 2022-01-23
 
### Added
#### All plans
- New deals column with price deviation from Base Order
- New indicator on main table when bots DCA strategies are over (max. SO reached) and current price outside max deviation %
  
#### Silver+ plans
- The "Add funds" form now includes the list of selected pairs

#### Gold+ plans
- New "Positions & Orders" tab
- Live data & direct actions on Exchanges
  - List of opened positions on Binance Futures & FTX Futures
  - Orderbooks from Binance Spot, Binance Futures & FTX Futures
  - Bulk "Close at market price" positions on Binance Futures & FTX positions
  - Bulk "Cancel / delete" open orders on Binance Spot, Binance Futures & FTX Futures
 
### Changed

- New TradingView chart widget including coin technical analysis
- Get Exchanges data from user streams (Binance & FTX)
- Load-balancing of exchanges REST API requests over a cluster of cloud proxies to avoid rate limits
- One time email code for password reset if MFA has not been set
 
### Fixed
- Change/Upgrade plan


## [2.1.5] - 2022-01-05

### Added
- New deals & trades live PnLs
- New daily / weekly / monthly profits in the top navigation bar

### Fixed
- Sorting issue on PnL columns with en-GB locales

 
## [2.1.2] - 2022-01-02
 
This is the first commercial release of 3C Dashboard
   
### Added
 
- [CoinPayments](https://coinpayments.net)
