# UPI Transactions – Power BI Dashboard

This project involves the analysis and dashboarding of **UPI (Unified Payments Interface) transactions**, created in Power BI. The data is **dummy/sample** data; it does not contain any real customer information.

## 📁 Project Structure

```
├── Report_1.pbix          # Power BI report (version/view 1)
├── Report_2.pbix          # Power BI report (version/view 2)
├── UPI_Transactions.xlsx  # Source dataset (20,000 dummy transaction records)
├── .gitattributes         # Git LFS config for binary files
└── README.md
```

## 📊 Dataset Overview

`UPI_Transactions.xlsx` contains ~20,000 rows, columns include:

- Transaction details: `TransactionID`, `TransactionDate`, `TransactionTime`, `Amount`, `Status`
- Bank info: `BankNameSent`, `BankNameReceived`, `RemainingBalance`
- Customer info: `City`, `Gender`, `CustomerAge`
- Payment info: `TransactionType`, `PaymentMethod`, `PaymentMode`, `Currency`
- Merchant info: `MerchantName`, `Purpose`
- Account numbers (dummy): `CustomerAccountNumber`, `MerchantAccountNumber`

## 🚀 How to Open

1.Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
2. clone Repo:
   ```bash
   git clone <your-repo-url>
   ```
3. `Report_1.pbix` ya `Report_2.pbix` open in Power BI Desktop.

## 🛠️ Tech Stack

- Power BI Desktop
- Excel (data source)

## 👤 Author

Sushant Kumar
