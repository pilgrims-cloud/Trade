# Global Pilgrim Trader - Forex Trading Platform

## Overview
Global Pilgrim Trader is a comprehensive forex trading platform with advanced features including automated trading, MetaTrader integration, and multiple payment options.

**Owner:** Olawale Abdul-Ganiyu  
**Email:** adeganglobal@gmail.com  
**Phone:** +2349030277275  
**Admin Account:** 0022345678

## Features

### Core Trading Features
- **Manual Trading:** Full control over buy/sell decisions
- **Automatic Trading:** Algorithm-based trading strategies
- **Robot Trading:** 6-second cycle automated trading with profit reinvestment
- **MetaTrader Integration:** Full support for MT4 and MT5 platforms
- **Binary Options:** Trade binary options with various strategies
- **Lot Size Support:** Trade up to 500 lots per transaction
- **Real-time Market Data:** Live CSCS/Capital Market updates

### Account Management
- **User Registration:** Easy account creation with email verification
- **Account Numbers:** 10-digit unique account numbers
- **Serial Numbers:** Unique serial numbers for each account
- **Profile Management:** Complete user profile customization
- **Balance Management:** Credit/debit balance editing (admin)
- **Profit Tracking:** Separate profit folder and tracking
- **Account Status:** Pending, Approved, Active statuses

### Payment System
- **Credit Cards:** Visa, MasterCard, American Express
- **Debit Cards:** Visa Debit, MasterCard Debit
- **Gift Cards:** Amazon, Apple iTunes, Google Play
- **Cryptocurrencies:** Bitcoin, Ethereum, Ripple, Litecoin, Bitcoin Cash, and more
- **Bank Transfers:** Direct bank transfers worldwide
- **Internal Transfers:** Transfer between trading accounts
- **Payment Gateway:** Secure payment processing
- **Transaction History:** Complete transaction records

### Security Features
- **VPN Integration:** Built-in VPN for secure trading
- **API Access:** Full API documentation and access
- **Network Authentication:** Auto-update when connected to network
- **Secure Login:** Encrypted password storage
- **Session Management:** Secure session handling

### Admin Dashboard
- **User Management:** Create, edit, approve, delete users
- **Balance Editing:** Credit/debit user balances
- **Trade Monitoring:** View all active trades
- **Payment Processing:** Approve/reject transactions
- **System Statistics:** Real-time platform statistics
- **Terminal Display:** Live system terminal
- **Password Generation:** Generate passwords for users

### Market Data
- **Currency Pairs:** All major forex pairs
- **Cryptocurrencies:** BTC, ETH, XRP, LTC, BCH, and more
- **Country Currencies:** Support for all world currencies
- **Real-time Updates:** Live market data feeds
- **CSCS Integration:** Capital market data integration

### Trading Modes
1. **Manual Trading:**
   - Full user control
   - Custom lot sizes
   - Manual entry/exit points

2. **Automatic Trading:**
   - Pre-set strategies
   - Automated execution
   - Risk management

3. **Robot Trading:**
   - 6-second trading cycles
   - Automatic buy/sell decisions
   - Profit reinvestment (0.02 threshold)
   - 24/7 operation

### Platform Features
- **Demo Account:** Practice trading with virtual funds
- **Real Account:** Live trading with real funds
- **Mobile Responsive:** Trade on any device
- **Dark Mode:** Easy on the eyes
- **Fast Execution:** Quick trade execution
- **Low Latency:** Minimal delay in trading

## Installation

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection
- JavaScript enabled

### Setup
1. Download all files to your web server
2. Open `index.html` in your browser
3. Register a new account or login with admin credentials

### Admin Login
- **Email:** adeganglobal@gmail.com
- **Password:** admin123
- **Account Number:** 0022345678

## Usage

### For Users
1. **Register:** Create a new account
2. **Login:** Access your dashboard
3. **Deposit:** Add funds using any payment method
4. **Trade:** Choose manual, automatic, or robot trading
5. **Withdraw:** Request withdrawals to your preferred method

### For Admins
1. **Login:** Access admin dashboard
2. **Approve Users:** Review and approve pending registrations
3. **Manage Balances:** Credit/debit user accounts
4. **Monitor Trades:** View all active trading activity
5. **Process Payments:** Approve deposits and withdrawals

## Supported Cryptocurrencies
- Bitcoin (BTC)
- Ethereum (ETH)
- Ripple (XRP)
- Litecoin (LTC)
- Bitcoin Cash (BCH)
- Cardano (ADA)
- Solana (SOL)
- Polkadot (DOT)
- Dogecoin (DOGE)
- And many more...

## Supported Countries
All countries worldwide with local currency support including:
- United States (USD)
- United Kingdom (GBP)
- European Union (EUR)
- Japan (JPY)
- Nigeria (NGN)
- And 150+ more countries

## Payment Methods

### Cards
- Visa
- MasterCard
- American Express
- Discover

### Gift Cards
- Amazon
- Apple iTunes
- Google Play
- Netflix
- PlayStation

### Cryptocurrencies
- Bitcoin
- Ethereum
- USDT
- USDC
- And 50+ more

### Bank Transfers
- Direct Bank Transfer
- Wire Transfer
- SEPA (Europe)
- SWIFT (International)

## Robot Trading Logic

The robot trading system operates on a 6-second cycle:

1. **Market Analysis:** Analyzes market trends every 6 seconds
2. **Trade Decision:** 
   - If trade is going UP → BUY
   - If trade is going DOWN → SELL
3. **Profit Monitoring:**
   - Monitors profit continuously
   - When profit reaches 0.02 → Close trade
   - Reinvest profit into new trade
4. **Loss Prevention:**
   - Stop loss at -0.01
   - Automatic trade closure

## API Documentation

### Authentication
```javascript
// Login
POST /api/login
{
  "email": "user@example.com",
  "password": "password"
}
```

### Trading
```javascript
// Execute Trade
POST /api/trade
{
  "symbol": "EUR/USD",
  "type": "buy",
  "lotSize": 0.1,
  "mode": "manual"
}
```

### Payments
```javascript
// Deposit
POST /api/deposit
{
  "amount": 1000,
  "method": "credit_card",
  "cardDetails": {...}
}
```

## Security

- All passwords are encrypted
- Secure HTTPS connections
- VPN integration for privacy
- Regular security updates
- Two-factor authentication (coming soon)

## Support

For support, contact:
- **Email:** adeganglobal@gmail.com
- **Phone:** +2349030277275
- **Owner:** Olawale Abdul-Ganiyu

## License

Proprietary - Global Pilgrim Trader © 2024

## Disclaimer

Trading forex and cryptocurrencies involves significant risk of loss. Please trade responsibly and only invest what you can afford to lose. Past performance is not indicative of future results.

---

**Global Pilgrim Trader** - Your Gateway to Professional Forex Trading