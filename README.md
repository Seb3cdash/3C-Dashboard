# [3C Dashboard](https://www.3cdashboard.com) Change Log
All notable changes to this project will be documented in this file.


## [2.4.3] - 2022-04-03

### Added
- Detailed error messages returned by 3commas
- SL % column (deals & smart trades)
- Bot# column
- Enable/Disable Paper Account option in dropdown menu

### Changed

### Fixed
- Slow loading of accounts at the beginning of the session
- Undefined account in the Exchanges tab
- Exchanges statistics graphs were not using UTC dates
- Max active deals error message while updating bots
- Cleanup of unexisting pairs failure


## [2.2.20] - 2022-02-20

### Added
- Option to show/hide errors notifications
- Option to show/hide paper account notifications
- Option to show/hide Smart trades, Spot deals and Futures deals independently
- Add funds "Unit size" field
 
### Changed
- Deals table button have been optimized by using drodown menus
- All table fields related to date are now displayed in localtime (logs, Positions & Orders)


## [2.2.14] - 2022-02-14
 
### Added
- Click-to-copy Bot ID
- Copy & Paste pairs in bots settings
- Add x_ALL pairs buttons
 
### Changed
- Pairs are now validated against available market pairs (bots edit / copy)

### Fixed
- Deals selection is cleared when a new deal is opened


## [2.2.13] - 2022-02-13
 
### Added
- A "clear columns filters" button has been added (bots tab)
- Maximum price to open deal column (bots tab)
- Minimum price to open deal column (bots tab)
 
### Changed
- "Created at" values are now converted to localtime
 
### Fixed
- "Created at" sorting issue fixed (deals & bots tables)
- "Completed" deals sorting issue fixed (bots table)
- Active "Deals" sorting issue fixed (bots table)
- System status URL missing

 
## [2.1.22] - 2022-01-22
 
### Added
#### All plans
- New deals column with price deviation from Base Order
- New deals column with % from average buy price (DCA) to Take Profit price
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
