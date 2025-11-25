📈**Binance Futures PnL Calculator**

A simple and intuitive Profit and Loss (PnL) Calculator for Binance USDT-M Futures, built with React and Ant Design (AntD).

🔧** Features**

-Supports Long and Short positions

-Input parameters:

Entry Price

Exit Price

Position Size (in USDT or contracts)

Leverage

Trading Fee Rate (customizable, default 0.04%)

Wallet Balance (optional, for rough liquidation price)

-Outputs:

✅ Gross PnL

✅ Trading Fees (entry + exit)

✅ Net PnL (after fees)

✅ ROE (%)

✅ Liquidation Price (approximate)

💰 Calculation Details

-Gross PnL = (Exit - Entry) × Size × Leverage

-Fees = (Entry + Exit Notional) × Fee Rate

-Net PnL = Gross PnL − Total Fees

-ROE (%) = Net PnL / Initial Margin × 100

-Liquidation Price: estimated using leverage only (simplified)

🚀 Tech Stack

⚛️ React

🎨 Ant Design

📏 JavaScript (ES6+)
