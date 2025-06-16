# 📊 MrRexoPanel – Trading Panel for MetaTrader 5

![Screenshot](gallery/screen.png)

## 🛠️ Installation

1. Copy `MrRexoPanel.ex5` to:
   ```
   MQL5/Experts
   ```
2. Copy graphic files (e.g., `lock.bmp`, `lock_open.bmp`, `calc_buy.bmp`, `calc_sell.bmp`) to:
   ```
   MQL5/Images
   ```
3. Launch MetaTrader 5 terminal.
4. Open a chart for the selected instrument.
5. Drag MrRexoPanel from “Navigator” onto the chart and confirm.

---

## ⚙️ Main Panel Features

### ✅ Position Management
- Automatic position size calculation based on risk (% of balance).
- Graphical display of SL (Stop Loss), TP (Take Profit), and OPEN (entry level).

### 📉 Trend on M1–D1 Timeframes
- 🟩 Green – uptrend  
- 🟥 Red – downtrend  
- ⬜ Gray – consolidation  
- 🟧 Orange – no clear direction

### 📈 Pivot Lines
Supported models:
- Floor
- Woodie
- Camarilla
- Fibonacci

---

## ⌨️ Keyboard Shortcuts

| Key | Action                              |
|-----|-------------------------------------|
| B   | Buy                                 |
| S   | Sell                                |
| E   | Move SL to Break Even               |
| C   | Close all positions                 |

---

## 🧩 Position Closing Buttons

| Button | Description                              |
|--------|------------------------------------------|
| CB     | Close all Buy positions                  |
| CS     | Close all Sell positions                 |
| CP     | Close all profitable positions           |
| CL     | Close all losing positions               |
| CA     | Close all positions (also key C)         |

---

## 📏 SL / TP Management

- Buy/Sell TP/SL – set common TP/SL for all positions of a given type.
- [>] button – bulk modification of SL/TP for selected position type.

---

## ⚙️ Automatic Features

- **Break Even (p)**: Move SL to entry price after reaching a set profit in points.
- **Trailing Stop (p)**: Automatically trail SL behind price.

---

## 💰 Profit and Loss Limits

- **SL Value**: Close all positions at a specified total loss.
- **TP Value**: Close all positions at a specified total profit.

---

## 📊 Real-Time Information

- **LV** – Total profit/loss of LONG positions (green/red/gray)
- **SV** – Total profit/loss of SHORT positions
- **Balance** – Total: LV + SV

---

## 🖱️ Interface Behavior

- On startup or timeframe change, R:R panel snaps to ASK/BID based on position direction.
- Dragging TP/SL with mouse updates levels and recalculates values.
- Dragging OPEN moves entire setup while preserving TP/SL.
- Double-click arrow icon – collapse R:R panel.
- Dragging R:R above/below ASK/BID switches BUY/SELL labels.

---

## 🔒 Risk Lock

- **Locked padlock** – Fixed risk percentage, auto-adjusts position size with SL changes.
- **Unlocked padlock** – Manual position size setting, independent of SL.

---

> 📧 Contact: mrrexo.mt5@gmail.com
