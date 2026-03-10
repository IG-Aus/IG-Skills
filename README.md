# IG Trading Skill

Trade financial markets through natural language using the IG Trading Platform API.

## Overview

This skill enables natural language trading on the IG Platform, supporting:

- **Market Research** - Search markets, check prices, view sentiment, get historical data
- **Position Management** - View, close, and modify open positions
- **Order Execution** - Place market, limit, and stop orders
- **Account Management** - View balances, activity, and transaction history
- **Portfolio Analysis** - Performance metrics, risk analysis, position breakdown

## Requirements

- IG Trading account (DEMO or LIVE)
- Node.js 18+
- Claude Desktop with MCP protocol support

## Quick Start

1. Configure your IG API credentials
2. Connect via MCP protocol
3. Start trading with natural language commands

## Examples

```
"What's the current price of Tesla?"
"Buy 1 share of Apple"
"Show my open positions"
"Add a stop loss at $150 to my Apple position"
"Analyze my portfolio performance"
```

## Available Tools

| Tool | Purpose |
|------|---------|
| `get_accounts` | List all trading accounts with balances |
| `get_markets` | Search for markets by term or EPIC code |
| `get_market_details` | Get detailed specs for a specific market |
| `get_market_sentiment` | View trader positioning data |
| `get_positions` | List all open positions |
| `close_position` | Close a position by deal ID |
| `update_position` | Modify stop-loss or take-profit |
| `get_orders` | View pending working orders |
| `place_order` | Execute market, limit, or stop orders |
| `confirm_trade` | Verify trade execution status |
| `get_activity_history` | Recent account activity |
| `get_transaction_history` | Detailed transaction records |
| `get_price_history` | Historical OHLC price data |
| `analyze_portfolio` | Portfolio performance metrics |

## Safety Guidelines

- **Always use DEMO environment** for testing and learning
- **Confirm large orders** before execution
- **Set stop-losses** to manage risk on every position
- **Check market hours** - some markets are closed on weekends

## Documentation

See [SKILL.md](SKILL.md) for complete documentation including:
- Detailed usage examples
- Market EPICs reference
- Error handling guidance
- Environment modes

## License

MIT License - see [LICENSE](LICENSE) for details.

## Links

- [IG Labs](https://labs.ig.com/) - IG API documentation
