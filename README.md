# Accounts Payable Three-Way Match Model | Excel

Checks every vendor invoice against the **Purchase Order** (price, quantity) and **Goods Receipt Note** (quantity received) before payment, and flags invoices to hold.

## Data
Sample data for fictional heavy-industry vendors, Jul–Oct 2026: **15 vendors, 180 PO lines, GRNs and 200 invoices**, including non-PO invoices and planted errors.

## Build
- Vendor master, PO, GRN and invoice sheets
- Three_Way_Match sheet: one row per invoice, all formulas
- Adjustable tolerance rules (price ±2%, quantity) – change one cell and every result updates
- Summary by status, key metrics and holds by vendor, plus a Formula_Guide sheet

## Key findings
- **148 invoices (74%)** match and are OK to pay
- **37 invoices (18.5%) on hold, worth INR 1.47 crore** – price mismatch (12), quantity mismatch (9), no GRN (8), duplicate (5), PO not found (3)
- **INR 11.4 lakh** of duplicate payments stopped and **INR 1.9 lakh** of price overcharges caught
- 18 MSME invoices on hold, at risk under the 45-day payment rule

## Files
- `AP_Three_Way_Match_Model.xlsx`
- `AP_Three_Way_Match_Summary.pdf`

## Tools
MS Excel

## Note
Sample data for learning purposes.

## Author
**Aditya Kushwaha** · [LinkedIn](https://www.linkedin.com/in/aditya-kushwaha16)
