# Custom Momentum Indicator for MetaTrader 5

## Overview
This is a custom momentum indicator for MetaTrader 5 (MT5) platform. The indicator measures the rate of change or the speed of price movement over a specified time period. It calculates the difference between the current closing price and the closing price X periods ago.

## Features
- Customizable colors for bullish and bearish momentum lines.
- Customizable overbought and oversold levels.
- Visual enhancements for better visibility of momentum lines.

## Installation
1. Open MetaEditor from within MetaTrader 5.
2. Click on "New" to create a new custom indicator.
3. Paste the provided code into the editor.
4. Save the file with an appropriate name (e.g., "CustomMomentum.mq5").
5. Compile the code (F7).
6. Once compiled successfully, close the MetaEditor.
7. In MetaTrader 5, navigate to the "Navigator" window, find the "Custom Indicators" section, and locate your newly created indicator ("Custom Momentum").
8. Drag and drop the indicator onto the chart where you want to apply it.
9. Adjust the parameters (if necessary) such as the period, colors, and levels.

## Usage
- The indicator plots two lines: one for bullish momentum (green by default) and one for bearish momentum (red by default).
- The overbought level is typically set at 100, and the oversold level is typically set at -100, but these levels can be customized according to preference.
- Traders often look for buy signals when the momentum crosses above the overbought level and sell signals when the momentum crosses below the oversold level.
