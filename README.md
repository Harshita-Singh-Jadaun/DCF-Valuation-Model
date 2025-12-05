# 📊 Discounted Cash Flow (DCF) Valuation Model

This repository contains an Excel-based **Discounted Cash Flow (DCF) valuation model** used to estimate the intrinsic value of a company based on its future free cash flows.

The model is suitable for:
- Finance students
- Equity research & investment roles
- Portfolio / resume showcase

---

## 🔍 Project Overview

The objective of this project is to calculate the **intrinsic value of a stock** and compare it with its current market price to see whether it is **undervalued, fairly valued, or overvalued**.

The model includes:

- Revenue & EBIT projections  
- NOPAT (Net Operating Profit After Tax)  
- Free Cash Flow to Firm (FCFF)  
- Terminal value based on long-term growth  
- Discounting using WACC  
- Enterprise value & equity value  
- Intrinsic value per share  

> 📝 All calculations are done in Excel with clear formula flow.

---

## 📁 Files in this Repository

| File | Description |
|------|------------|
| `DCF_Model.xlsx` | Core Excel model containing all calculations and assumptions |

---

## 🧮 Methodology (High-Level)

1. **Forecast Revenue & EBIT**  
   Revenue and operating profit are projected over a future period (for example 5–10 years) based on growth assumptions.

2. **Calculate NOPAT**  
   NOPAT is calculated as:  
   `NOPAT = EBIT × (1 – Tax Rate)`

3. **Compute Free Cash Flow to Firm (FCFF)**  
   `FCFF = NOPAT + Depreciation – CapEx – Change in Working Capital`

4. **Estimate Terminal Value**  
   Terminal value is calculated using the Gordon Growth formula:  
   `TV = FCF in final forecast year × (1 + g) / (WACC – g)`

5. **Discount Cash Flows to Present Value**  
   All yearly FCFF and the terminal value are discounted using the Weighted Average Cost of Capital (WACC) to arrive at **Enterprise Value**.

6. **Calculate Intrinsic Value per Share**  
   `Intrinsic Value per Share = (Enterprise Value – Net Debt) / Number of Shares`

---

## 📊 Key Inputs (in the Excel file)

Some of the main assumptions in the model (you can view or change them directly in Excel):

- Revenue growth rate
- EBIT margin
- Tax rate
- Depreciation as % of revenue or fixed amount
- Capital expenditure (CapEx)
- Change in working capital
- WACC (discount rate)
- Terminal growth rate

> You can adjust these inputs to see how the intrinsic value changes under different scenarios.

---

## 💡 How to Use This Model

1. **Download** `DCF_Model.xlsx` from this repository.
2. Open it in **Microsoft Excel** (or compatible spreadsheet software).
3. Go to the **assumptions section** in the Excel sheet.
4. Edit the inputs (growth, margins, WACC, etc.) according to the company you want to value.
5. Review the **calculated intrinsic value per share** and compare it with the current market price.

---

## 🎯 Purpose of This Project

- To practice and understand **DCF valuation** in a structured way  
- To demonstrate **valuation skills** for finance / equity research / investment roles  
- To showcase ability to build and work with **financial models in Excel**

---

## 📬 Contact

If you want to discuss the model, assumptions, or improvements, feel free to connect with me on LinkedIn or reach out via email.
Linkdin: linkedin.com/in/harshita-singh-jadaun-820b611b3
Email: 1108harshita@gmail.com
