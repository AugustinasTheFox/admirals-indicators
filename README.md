# Admirals Indicators

MT4 and MT5 indicators for Admirals trading platform.

## Contents

### Market Structure Indicators

- **MarketStructure_CHoCH_BOS** - Market Structure indicator showing Change of Character (CHoCH) and Break of Structure (BOS)
  - Detects fractal-based market structure changes
  - Shows bullish and bearish structure breaks
  - Optional support/resistance levels
  - Available for both MT4 and MT5

### Fair Value Gaps (FVG)

- **Fair_Value_Gaps** - Identifies imbalance areas where markets often move back to
  - Detects bullish (PaleGreen) and bearish (Pink) fair value gaps
  - Automatically extends boxes until gaps are filled
  - Configurable minimum gap size filter
  - Available for both MT4 and MT5

## Installation

### For MetaTrader 4 (MT4)

1. Download the compiled files (`.ex4`) from the `mt4/indicator/` directory
2. Copy the `.ex4` files to your MetaTrader 4 indicators folder:
   - Windows: `C:\Users\[YourUsername]\AppData\Roaming\MetaQuotes\Terminal\[TerminalID]\MQL4\Indicators\`
   - macOS: `~/Library/Application Support/MetaTrader 4/Bottles/[instance]/drive_c/users/[username]/Application Data/MetaQuotes/Terminal/[TerminalID]/MQL4/Indicators/`
3. Restart MetaTrader 4 or refresh the Navigator panel
4. The indicators will appear in the Navigator under "Indicators"

### For MetaTrader 5 (MT5)

1. Download the compiled files (`.ex5`) from the `mt5/indicator/` directory
2. Copy the `.ex5` files to your MetaTrader 5 indicators folder:
   - Windows: `C:\Users\[YourUsername]\AppData\Roaming\MetaQuotes\Terminal\[TerminalID]\MQL5\Indicators\`
   - macOS: `~/Library/Application Support/MetaTrader 5/Bottles/[instance]/drive_c/users/[username]/Application Data/MetaQuotes/Terminal/[TerminalID]/MQL5/Indicators/`
3. Restart MetaTrader 5 or refresh the Navigator panel
4. The indicators will appear in the Navigator under "Indicators"

## Usage

Drag and drop the indicator onto your chart to start using it. Each indicator has customizable parameters accessible through the indicator settings.

## Author

Augustinas The Fox - 2025
