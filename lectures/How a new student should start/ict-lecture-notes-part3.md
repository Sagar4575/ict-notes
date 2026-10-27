# ICT Mentorship Lecture Notes: How New Students Should Start (Part 3)
**Source:** *How New Students Should Start Part 3* (The Inner Circle Trader)  
**Topic:** Macro Trading Keys, Chart Information Management, and PD Array Matrices  

---

## Executive Summary & Core Philosophy

- **Information Management over Chart Clutter:** New traders often overload charts with indicators, heatmaps, and liquidity maps, creating analysis paralysis. Effective trading requires managing data through structured, separate chart layouts and detailed journals.
- **The Core Notepad Principle:** The chart layout should mirror what is in your trading journal/notepad. Avoid cluttering your primary execution screen; keep specialized studies on designated layout spaces.
- **Five Pillars of Algorithmic Price Delivery:**
  1. HTF Macro Perspective (Monthly, Weekly, Daily Keys: Open, High, Low, Close).
  2. New Week Opening Gap (NWOG) Matrix.
  3. New Day Opening Gap (NDOG) Matrix.
  4. First Presented Fair Value Gap Matrix.
  5. Regular Trading Hours (RTH) Opening Range Gap Matrix.

---

## 1. Monthly Macro Keys & High Time Frame (HTF) Perspective

### Setup & Regimen
- **Timeframe:** Monthly Chart (`1M`).
- **Rolling 3-Month Window:** Highlight and annotate the Open, High, Low, and Close for the past 3 consecutive completed calendar months (e.g., June, July, August).
- **Previous Week Reference:** Annotate the Previous Week's High (PWH) and Previous Week's Low (PWL) using clean, consistent visual cues (e.g., blue solid lines for highs/lows, black dashed lines for opening prices).

### Market Structure & Bias Principles
- **Equilibrium (50%):** Find the midpoint between the 3-month high and 3-month low.
  - **Premium (> 50%):** Look for short-term sell ideas or target discount levels.
  - **Discount (< 50%):** Look for short-term buy ideas or target premium levels.
- **Quarterly Shifts & Seasonal Tendencies:**
  - Macro swings move in 1-to-3 month quarterly shifts.
  - *Example Seasonal Tendency:* Index futures generally display weakness during September, often trading down into a low in late September/October before an end-of-year rally.

---

## 2. Transposing HTF Levels to Lower Timeframes

### Multi-Timeframe Alignment
- Higher time frame levels (Monthly/Weekly/Daily) dictate the direction and high-probability targets for lower time frames (`1D` down to `1m`).
- Price moves smoothly through "open space" (areas lacking HTF friction or opposing order blocks) once HTF inefficiencies or key levels are engaged.

### Grading Ranges: Octants & Quadrants
When evaluating Fair Value Gaps (FVG) or Volume Imbalances (VI):
- **Consequent Encroachment (CE):** The 50% midpoint of an inefficiency or gap.
- **Quadrant Division (25% Increments):** Upper Quadrant (75%), Midpoint/CE (50%), Lower Quadrant (25%).
- **Octant Division (12.5% Increments):** Breaks the range into 8ths to track algorithmic precision on intraday charts (e.g., `1m` candles turning precisely at the 1/8th or 7/8th octant levels).

---

## 3. New Week Opening Gap (NWOG) Matrix

### Definition & Calculation
- **NWOG:** The price gap between Friday’s market close at **4:59 PM EST** and Sunday’s market open at **6:00 PM EST**.

### Management Rules
- Maintain a **rotating 5-week display** of NWOGs on a dedicated chart layout (`NWOG Matrix`).
- Use TradingView Object Tree / Layer settings to keep past gaps organized by week/month and toggle visibility cleanly.

---

## 4. New Day Opening Gap (NDOG) & First Presented FVG Matrix

### First Presented Fair Value Gap
- Defined as the **very first Fair Value Gap** that forms after the **9:30 AM EST** equity market open.
- Tracks initial institutional displacement and establishes intraday directional bias.

### Matrix Separation
- Keep NDOGs and First Presented FVGs on a separate layout tab if chart density becomes cumbersome.

---

## 5. Regular Trading Hours (RTH) Opening Range Gap Matrix

### Calculation
- Toggle chart settings to **Regular Trading Hours (RTH)**.
- **Anchor Points:** Measure the gap between the previous trading day's RTH close (**4:14 PM EST**) and the current day's RTH open (**9:30 AM EST**).

### Nested PD Arrays & "Shadows"
- **Nested Gaps:** When multiple RTH gaps overlap during market consolidation, focus on the **widest gap** as the master reference.
- **Shadows:** The specific region where two distinct RTH opening range gaps overlap (bleed-over area). 
  - Overlapping RTH gap bounds create high-probability order block support/resistance levels without needing traditional trendlines.

---

## 6. Student Execution & Regimen Guidelines

### Rules for New Students
1. **NFP Week Rule:** During Non-Farm Payroll (NFP) week, new traders should **stop active trading by Wednesday at 11:00 AM EST**.
2. **Process over Action:** Avoid "action-hound" trading in consolidation or post-objective environments.
3. **Daily Routine:**
   - Maintain clean HTF levels (Monthly/Weekly/Daily).
   - Log key PD arrays and gap matrices in your notepad/journal.
   - Clean up intraday chart scribbles after each trading session to maintain fresh technical focus.
