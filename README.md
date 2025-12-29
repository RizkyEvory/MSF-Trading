# 🧠 MarketStructureFusion v1.0 — MT5 Indicator  
**Smart Money Breakout Confirmation System**

![MarketStructureFusion Banner](https://i.imgur.com/0zX8kYp.png)

> Trade breakouts dengan **validasi struktur pasar nyata**, bukan sekadar candle tembus level.  
> Deteksi **Higher High / Lower Low**, **Liquidity Grab**, **Stop Hunt**, dan **Breakout Valid** hanya saat *Smart Money confirmation* benar-benar selaras.

**Author:** M4DI~UciH4  
**GitHub:** https://github.com/RizkyEvory  

---

## 🔍 Apa itu MarketStructureFusion?

**MarketStructureFusion** adalah indikator **MetaTrader 5 (MQL5)** yang dirancang untuk trader yang ingin:

- Menghindari **fake breakout**
- Memahami **niat Smart Money**
- Entry hanya saat **struktur + likuiditas + momentum** sejalan

Indikator ini **tidak mengejar signal banyak**, tetapi fokus pada:
> **Breakout berkualitas tinggi dengan probabilitas nyata**

---

## 🧠 Filosofi Trading

> ❝ Breakout yang valid SELALU didahului oleh perubahan struktur dan manipulasi likuiditas ❞

MarketStructureFusion bekerja berdasarkan prinsip:
- Smart Money **mengambil likuiditas lebih dulu**
- Struktur pasar **berubah sebelum breakout**
- Breakout tanpa konfirmasi struktur = **trap**

---

## 🚀 Core Features

### 🏗 Market Structure Engine
- Deteksi otomatis:
  - **Higher High (HH)**
  - **Higher Low (HL)**
  - **Lower High (LH)**
  - **Lower Low (LL)**
- Identifikasi:
  - **Market Structure Shift (MSS)**
  - **Trend Continuation vs Reversal**
- Visual structure lines (HH–HL / LH–LL)

---

### ⚡ Breakout Validation Matrix
Breakout **HANYA dianggap valid** jika seluruh konfirmasi berikut terpenuhi:

✔ Struktur selaras (HH+HL atau LH+LL)  
✔ Volume spike ≥ **200%**  
✔ Strong candle close (body dominance)  
✔ Spread dalam batas optimal  
✔ Higher Timeframe Bias (H4 / D1)  
✔ News filter aktif (hindari high-impact event)

> Jika satu elemen gagal → **tidak ada signal**

---

### 💧 Liquidity & Stop Hunt Detection
- Deteksi:
  - Buy-side liquidity
  - Sell-side liquidity
- Visualisasi:
  - **Liquidity grab**
  - **Stop hunt zone**
- Membantu membedakan:
  - Breakout asli
  - Manipulasi sebelum reversal

---

### 🛡 Smart Risk Management (Built-In)
- **Stop Loss otomatis**:
  - Swing High / Low
  - Liquidity zone (lebih akurat)
- **Take Profit bertahap**:
  - TP1 → 1:1
  - TP2 → Next market structure
  - TP3 → Fibonacci Extension 161.8%
- **Auto trailing** aktif setelah TP1 tercapai

---

### 🖥 Premium Visual & Dashboard
- Breakout arrow + SL/TP marker
- Breakout zone & liquidity zone
- Structure connecting lines
- **Dashboard Profesional 3 Panel**:
  1. **Market Structure Map**
  2. **Breakout Validation Matrix**
  3. **Execution Blueprint**
     - Entry
     - SL / TP
     - Risk–Reward
     - Confidence Score
     - Signal Grade

---

### 🔔 Alerts System
- Popup Alert
- Sound Alert
- Push Notification
- Email Notification

---

## 📊 Chart Preview

### Dashboard 3 Panel
![Dashboard](https://i.imgur.com/placeholder-dashboard.png)

### Market Structure & Breakout Zones
![Structure](https://i.imgur.com/placeholder-structure.png)

### Liquidity Grab & Stop Hunt Zones
![Liquidity](https://i.imgur.com/placeholder-liquidity.png)

---

## ⚙️ Installation Guide

1. Download `MarketStructureFusion.mq5`
2. Open **MetaTrader 5**
3. `File → Open Data Folder → MQL5 → Indicators`
4. Paste file `.mq5`
5. Restart MT5 / Refresh Navigator
6. Attach ke chart

**Rekomendasi:**
- Pair: EURUSD, GBPUSD, XAUUSD  
- Timeframe: **H1 – H4**

---

## 🛠 Recommended Settings

| Parameter | Value | Notes |
|--------|-------|------|
| Swing_Lookback | 5 | Default optimal |
| Volume_Threshold | 200% | Valid breakout |
| Use_HTF_Confluence | true | Sangat disarankan |
| Wait_For_Retest | false | Entry agresif |
| Use_Structure_TP | true | TP realistis |
| Use_Fib_Extension | true | TP3 optimal |
| Show_Dashboard | true | Informasi wajib |

---

## 📈 Trading Workflow

1. Tunggu **breakout arrow**
2. Cek Dashboard:
   - Confidence Score ≥ **75%**
   - Validation Matrix **hijau semua**
3. Entry di **close candle breakout**
4. SL & TP sudah otomatis
5. Partial:
   - TP1: 50%
   - TP2: 30%
   - Sisanya trail ke TP3

### ❌ Hindari Trading Saat:
- Confidence < 60%
- News high-impact (auto filtered)
- Spread > 3 pips (Forex) / > 5 pips (Gold)

---

## ⚠️ Disclaimer

Indikator ini adalah **alat bantu analisis**, bukan jaminan profit.  
Gunakan manajemen risiko yang disiplin dan lakukan backtest sebelum live trading.

---

## ❤️ Support & Contribution

- ⭐ Star repository ini jika bermanfaat
- 🐞 Laporkan bug di Issues
- 💡 Feature request sangat diterima
- 🤝 Kontribusi code terbuka

---

**Trade with real structure.  
Trade with liquidity awareness.  
No more fake breakouts.**

© 2025 M4DI~UciH4 — All Rights Reserved
