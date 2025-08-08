# Hishabee Mobile Application (Front-End)  
##  Overview  
This repository contains **critical test scenarios** and **bug reports** for the **Hishabee Mobile Application (Front-End)**, focusing on Test Scenarios:  
- **Product List Management**  
- **Business Report Management**  

The aim is to ensure the most important workflows are functional, user-friendly, and free from critical defects.  
---
## 🧪 Critical Test Scenarios  
| Module | Test Scenario | Expected Result |
|--------|---------------|-----------------|
| Product List | Verify that the Product List screen opens successfully | Product list screen loads without errors |
| Product List | Verify adding a new product succeeds | Product is added and visible in the list |
| Product List | Verify product search functionality works correctly | Search returns matching products |
| Business Report | Verify that the Business Report screen opens successfully | Report dashboard loads correctly |
| Business Report | Verify adding a new income entry succeeds | Income entry appears in report |
| Business Report | Verify adding a duplicate income sector is handled properly | App shows duplicate sector warning |
---

## 🐞 Known Bugs & Issues  
| Bug Title | Description |
|-----------|-------------|
| App allows duplicate income sector to be added without validation | Duplicate income sector creation is not restricted, leading to inconsistent reporting. |
| Product discount field accepts values over 100% | No validation exists to restrict discount input to a maximum of 100%. |
| Static Date and Time in Business Report – Income Section | Income entries display a fixed date and time instead of dynamic values. |
| Uploaded Product Images Not Displaying in Product List | Product images fail to appear after successful upload. |
| Total Income Not Visible in Business Report After Adding Income Entry | The total income field does not refresh after adding an entry. |
| Expense Name Missing in Expense Report After Entry | Expense report shows blank expense names despite successful entry. |
---
## Test Report
<img width="1000" height="500" alt="image" src="https://github.com/user-attachments/assets/12d37249-226c-47fb-92e7-b929f0c595c0" />

## 📂 Repository Structure  
├── TestCases/
│   ├── ProductList_TestCases.xlsx
│   ├── BusinessReport_TestCases.xlsx
│
├── BugReports/
│   ├── DuplicateIncomeSector.md
│   ├── DiscountFieldValidation.md
│   ├── StaticDateTime_BusinessReport.md
│   ├── ProductImageUploadIssue.md
│   ├── TotalIncomeNotVisible.md
│   ├── ExpenseNameMissing.md
│
├── README.md
├── README.md
