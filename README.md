# UPI Transactions – Power BI Dashboard

Yeh project **UPI (Unified Payments Interface) transactions** ka analysis aur dashboard hai, Power BI mein banaya gaya hai. Data **dummy/sample** hai, koi real customer information nahi hai.

## 📁 Project Structure

```
├── Report_1.pbix          # Power BI report (version/view 1)
├── Report_2.pbix          # Power BI report (version/view 2)
├── UPI_Transactions.xlsx  # Source dataset (20,000 dummy transaction records)
├── .gitattributes         # Git LFS config for binary files
└── README.md
```

## 📊 Dataset Overview

`UPI_Transactions.xlsx` mein ~20,000 rows hain, columns include:

- Transaction details: `TransactionID`, `TransactionDate`, `TransactionTime`, `Amount`, `Status`
- Bank info: `BankNameSent`, `BankNameReceived`, `RemainingBalance`
- Customer info: `City`, `Gender`, `CustomerAge`
- Payment info: `TransactionType`, `PaymentMethod`, `PaymentMode`, `Currency`
- Merchant info: `MerchantName`, `Purpose`
- Account numbers (dummy): `CustomerAccountNumber`, `MerchantAccountNumber`

> ⚠️ Note: Saare account numbers aur customer details **dummy/synthetic** hain — koi real financial data nahi hai.

## 🚀 How to Open

1. [Power BI Desktop](https://powerbi.microsoft.com/desktop/) install karo (free).
2. Repo clone karo:
   ```bash
   git clone <your-repo-url>
   ```
3. `Report_1.pbix` ya `Report_2.pbix` ko Power BI Desktop mein open karo.

## 🛠️ Tech Stack

- Power BI Desktop
- Excel (data source)

## 📝 License

Feel free to use/modify for learning purposes.
