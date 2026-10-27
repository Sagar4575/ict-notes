# ICT Lecture Notes: How New Students Should Start (Part 1)
## Core Framework: Economic Calendar, HTF Chart Mapping, Macro Windows & Tape Reading

---

## Executive Summary & Overview

In **Part 1** of the *"How New Students Should Start"* series, Michael Huddleston (The Inner Circle Trader - ICT) establishes the foundational workflow for brand-new and developing students. The lecture lays out the exact step-by-step routine required to prepare charts, filter fundamental news drivers, map macro levels across multiple timeframes, measure algorithmic price delivery using gradient matrices, and execute disciplined tape-reading drills without risking capital.

---

## Table of Contents
1. [Economic Calendar & Macro Event Discipline](#1-economic-calendar--macro-event-discipline)
2. [Multi-Timeframe Workspace & Layout Architecture](#2-multi-timeframe-workspace--layout-architecture)
3. [Higher Timeframe Chart Mapping & Annotations](#3-higher-timeframe-chart-mapping--annotations)
4. [PD Arrays, Suspension Blocks & Gradient Matrices](#4-pd-arrays-suspension-blocks--gradient-matrices)
5. [Regular Trading Hours (RTH) Opening Range Gap Matrix](#5-regular-trading-hours-rth-opening-range-gap-matrix)
6. [Wick Analysis, Consequent Encroachment & Event Horizons](#6-wick-analysis-consequent-encroachment--event-horizons)
7. [Macro Time Windows & Post-Macro Animation](#7-macro-time-windows--post-macro-animation)
8. [Trade Execution, Risk Management & Partial Framework](#8-trade-execution-risk-management--partial-framework)
9. [Daily Student Execution & Journaling Protocol](#9-daily-student-execution--journaling-protocol)

---

## 1. Economic Calendar & Macro Event Discipline

### 1.1 Seasonal Tendency Window
* **Timing:** September through year-end (holiday spending, institutional rebalancing, quarterly drivers).
* **Characteristics:** Price delivery transitions into clean, high-probability algorithmic trends with reduced random noise compared to summer consolidation.

### 1.2 Forex Factory Filtering Protocol
* **Currency Toggle:** Toggle **USD** ON when trading index futures (NASDAQ/S&P). Filter out non-pertinent foreign currencies unless actively trading forex pairs.
* **Impact Color Folder Coding:**
  * **Red Folder:** High Impact (e.g., NFP, CPI, FOMC, ISM PMI). High volatility potential.
  * **Orange Folder:** Medium Impact (e.g., JOLTS Job Openings, ADP Employment Change). Significant market drivers.
  * **Yellow/Gray Folder:** Low Impact / Speeches. Generally ignored unless high-impact events are absent.

```
+-----------------------------------------------------------------------+
|                       NFP WEEK TRADING MATRIX                         |
+---------------+-------------------------------------------------------+
| Monday        | PREMIER TRADING DAY                                   |
|               | - Highest probability setup of NFP week.              |
|               | - Institutions position early to avoid end-of-week    |
|               |   volatility.                                         |
+---------------+-------------------------------------------------------+
| Tuesday       | REGULAR ENGAGEMENT                                    |
|               | - Trade around scheduled medium/high impact news      |
|               |   drivers (e.g., 10:00 AM ISM/JOLTS).                 |
+---------------+-------------------------------------------------------+
| Wednesday     | HARD CUTOFF AT 11:00 AM EST                           |
|               | - Morning setups allowed until 11:00 AM EST.          |
|               | - Cease all trading activity after 11:00 AM.          |
+---------------+-------------------------------------------------------+
| Thursday      | STRICT NO-TOUCH ZONE (Study / Observation Only)       |
|               | - Pre-NFP positioning causes deceptive price swings.  |
+---------------+-------------------------------------------------------+
| Friday        | STRICT NO-TOUCH ZONE (8:30 AM EST NFP Data Release)   |
|               | - Extreme volatility ("Moth to a flame").             |
|               | - Government economic data is unreliable / revised.   |
+---------------+-------------------------------------------------------+
```

### 1.3 Debunking Monday Trading Myths
* **Myth:** *"ICT says never trade on Mondays."*
* **Fact:** **NFP Monday is an absolute guarantee that a high-probability setup will form**, as traders rush to capture profit before Thursday/Friday danger zones.
* **Non-NFP Mondays:** Hit-or-miss ("potluck"). Requires advanced experience; new students should remain patient and avoid forcing trades on non-NFP Mondays.

---

## 2. Multi-Timeframe Workspace & Layout Architecture

### 2.1 Workspace Separation Rule
To eliminate chart clutter and cognitive overload, **never place all annotations on a single workspace chart**. Maintain dedicated TradingView layouts:

1. **Naked / Working Chart:** Primary execution and short-term markup workspace.
2. **HTF Macro Levels Workspace:** Contains Monthly, Weekly, and Daily high/low/close levels.
3. **NWOG / NDOG Workspace:** Dedicated to tracking New Week Opening Gaps and New Day Opening Gaps.
4. **RTH Opening Range Gap Workspace:** Specifically records Regular Trading Hours settlement gaps.
5. **First Presented FVG Workspace:** Tracks original, unmitigated Fair Value Gaps across higher timeframes.

---

## 3. Higher Timeframe Chart Mapping & Annotations

### 3.1 Monthly Level Mapping
* **Levels Required:**
  * **PMH:** Previous Month High (e.g., July Monthly High).
  * **PML:** Previous Month Low (e.g., July Monthly Low).
  * **PMC:** Previous Month Close (exact closing price on the last calendar day at 17:00 EST).
* **Monthly Open Rule:** The Monthly Open is **omitted** because monthly opening prices naturally get absorbed into New Week Opening Gaps (NWOG) every 4 weeks.

### 3.2 Formatting & Visibility Settings
* **Font Style:** Bold, Black, Middle-Right Justified.
* **Right-Justification Rationale:** Anchoring text labels to the far right prevents labels from migrating across the screen when compressing or expanding lower timeframes (15-min, 5-min, 1-min).
* **Timeframe Visibility Toggles:** Toggle visibility ON across **Monthly, Weekly, Daily, Hourly, Minute, and Second** tabs so HTF key levels remain visible during lower-timeframe tape reading.

```
+-----------------------------------------------------------------------+
|                    MONTHLY & DAILY RANGE ANALYSIS                     |
+-----------------------------------------------------------------------+
|                     PREMIUM ZONE (Above Equilibrium)                  |
|                     - Look for SIBIs, Premium Wicks, BSL Runs          |
|                                                                       |
| ------------------- EQUILIBRIUM (50% Midpoint) ----------------------- |
|                                                                       |
|                     DISCOUNT ZONE (Below Equilibrium)                 |
|                     - Look for BISIs, Discount Wicks, SSL Runs         |
+-----------------------------------------------------------------------+
```

### 3.3 Liquidity Pool Mapping
* **Buy Side Liquidity (BSL):** Resting above PMH, PDH, and swing highs (buy stops, breakout buyers). Color code: **Blue**.
* **Sell Side Liquidity (SSL):** Resting below PML, PDL, and swing lows (sell stops, breakout sellers). Color code: **Red / Deep Red**, right-justified under price axis.

---

## 4. PD Arrays, Suspension Blocks & Gradient Matrices

### 4.1 Inefficiency Classifications
* **SIBI (Sellside Imbalance Buyside Efficiency):** Price trades down aggressively leaving a gap where only sellside was delivered. Functions as a Premium array (resistance).
* **BISI (Buyside Imbalance Sellside Efficiency):** Price trades up aggressively leaving a gap where only buyside was delivered. Functions as a Discount array (support).
* **Volume Imbalance:** A gap created between consecutive candlestick bodies where wicks overlap, but bodies do not touch.

### 4.2 Suspension Blocks
* **Definition:** A SIBI or BISI bounded at both its top and bottom by a **Volume Imbalance** (where body shadows fail to overlap).
* **Significance:** Represents extreme institutional order flow displacement. Functions as a major barrier and key reference array on lower timeframes.

### 4.3 Octant & Quadrant Gradient Matrices
When grading wide higher-timeframe inefficiencies or ranges:
* **Quadrants (1/4ths):** Divide range at **25%, 50% (Equilibrium), and 75%**.
* **Octants (1/8ths):** Divide range into equal eights (**12.5% / 0.125 increments**).
  * **Upper Octant (0.125 / 87.5%):** Key sensitivity level when price first enters a HTF SIBI from below.

---

## 5. Regular Trading Hours (RTH) Opening Range Gap Matrix

### 5.1 RTH Settlement Baseline
* **Settlement Time:** Friday 16:00 / 17:00 EST closing price.
* **Pre-Market Annotation:** Prior to 09:30 AM EST, draw a horizontal line on the Friday settlement price and label it **`RTH ORG Settlement`**.

### 5.2 09:30 AM EST Label Transition Protocol

```
                      [09:30 AM EST Open Price]
                                 |
         +-----------------------+-----------------------+
         |                                               |
  Opens ABOVE Settlement                           Opens BELOW Settlement
         |                                               |
         v                                               v
  Settlement = LOW of Gap                         Settlement = HIGH of Gap
  Label: "RTH ORG Low"                            Label: "RTH ORG High"
  (Premium Gap Above Open)                        (Discount Gap Below Open)
```

### 5.3 Gap Closure Probability Rule
* **70% Probability Rule:** In the first 30 minutes of trading (09:30 AM – 10:00 AM EST), price has a **70% probability of filling at least 50% (half gap) of the RTH Opening Range Gap** before establishing the true directional trend for the morning session.

---

## 6. Wick Analysis, Consequent Encroachment & Event Horizons

### 6.1 Consequent Encroachment (CE)
* **Definition:** The exact **50% midpoint** of a prominent candlestick wick/tail.
* **Execution Marker:**
  * **Bearish / Premium Wick:** Price can wick into the upper half of a premium wick, but **candlestick bodies must close below Consequent Encroachment (CE)** to maintain bearish continuation.
  * A body closing above CE indicates loss of bearish momentum and signals higher timeframe retracement.

### 6.2 Event Horizon
* **Definition:** The exact **50% midpoint** calculated between a recent swing low/high and a major HTF PD Array target (e.g., HTF SIBI or SSL).
* **Partial Profit Anchor:** Functions as the primary target for taking a first partial profit (e.g., taking off 1 of 3 micro contracts) to de-risk the trade early.

---

## 7. Macro Time Windows & Post-Macro Animation

### 7.1 Hourly Macro Window Structure
* **Window Duration:** The last 10 minutes of the closing hour to the first 10 minutes of the new hour (**20-minute total window**).
  * *Examples:* 08:50–09:10 AM EST, 09:50–10:10 AM EST, 10:50–11:10 AM EST, 11:50–12:10 PM EST.

### 7.2 Function & Anomaly Handling
* **Core Function:** Macro windows do **not** provide directional bias; they act as time-based catalysts for **price spooling / animation** toward liquidity or inefficiencies.
* **Macro Consolidation Anomaly:** If price consolidates without direction during the 20-minute macro window, expect **aggressive, explosive price animation immediately after the 10-minute mark** (e.g., post-09:10 AM EST).

---

## 8. Trade Execution, Risk Management & Partial Framework

### 8.1 Inversion Fair Value Gaps (IFVG) & Immediate Rebalance (IRB)
* **Inversion Fair Value Gap (IFVG):** A SIBI that fails as resistance, gets crossed above by a strong candle, and then acts as support on a return visit (or vice versa for BISI).
* **Immediate Rebalance (IRB):** Occurs when a candle closes and the very next candle immediately rebalances the space without leaving an open gap. **One of ICT's highest-probability delivery signatures.**

### 8.2 Partial Profit Logic ("Paying Yourself")
* Taking partials at Event Horizons or 50% gap closure levels removes emotional anxiety, protects capital, and converts open float into realized profit.
* **Stop Loss Management:** After securing a partial, roll the stop loss to just above/below the **Mean Threshold (50% midpoint)** of the key entry candle or 1 tick above/below the CE of a key wick.

```
+-----------------------------------------------------------------------+
|                    ICT TAPE-READING EXECUTION MODEL                   |
+-----------------------------------------------------------------------+
| 1. Identify HTF Draw on Liquidity (e.g., SSL or RTH Settlement Gap). |
| 2. Wait for 09:30 AM EST Open & check RTH ORG Gap direction.           |
| 3. Observe 08:50-09:10 or 09:50-10:10 AM Macro Windows for spooling.  |
| 4. Identify Entry Array: IFVG / Immediate Rebalance / Volume Imbalance.|
| 5. Take Partial 1 at Event Horizon (50% distance to target).          |
| 6. Trail Stop Loss to Mean Threshold / CE of entry candle.            |
| 7. Exit remaining position at full HTF target / Gap closure.          |
+-----------------------------------------------------------------------+
```

---

## 9. Daily Student Execution & Journaling Protocol

### 9.1 Daily Screen Recording Drill
1. **Record the 1-Minute Chart:** Screen record 1-minute price action during RTH (09:30 AM – 10:30 AM EST).
2. **Review Session Drills:** Play back the recording after trading hours.
3. **Pause-Predict-Unpause Routine:**
   * **Pause:** At key inflection points (09:30 AM open, entry into macro window, touch of SIBI/BISI).
   * **Predict:** State expected delivery (e.g., *"Price should respect CE of this wick and draw down to SSL"*).
   * **Unpause:** Observe actual candle delivery, body closes, and speed of delivery.

### 9.2 Journal Documentation Rules
* Take high-resolution screenshots at the exact moment of market inflection.
* Annotate all PD arrays, wicks, macro windows, and event horizons directly on the image.
* Log whether price respected body closure rules (CE / Mean Threshold) and record transactional operating errors for continuous improvement.
