# AI-Enhanced Changelog

## Release 26.0.313.0 (PR #457) - 28/09/2025
### ✨ Features
#### 🛍️ Purchase
  * improvement for "Order No." visibility in Posted Purchase Receipt Lines feature. **Improved vendor relationships** and order tracking. [*mpisana*]
#### 💰 Finance
  * Payment Method Code feature from Acc. General Journal feature improvement. Users can now **manage finances** more efficiently. [*albertodone*]
  * Scheduled import feature in Expenses management. **Better financial control** for accounting teams. [*mpisana*]
  * Payment Method Code feature to Profile General Journal feature. Users can now **manage finances** more efficiently. [*mpisana*]
  * Payment Method Code feature to Acc. General Journal with non-edifeature property. Users can now **manage finances** more efficiently. [*albertodone*]
#### 📦 Logistic
  * Calculation of shipping no. series during SalesOrder creation from SalesBlanket. This **optimizes warehouse operations**. [*albertodone*]
  * Action to view item availability by event in Import Req. Worksheet feature. Users can **track shipments** more effectively. [*mpisana*]
  * Address columns in Warehouse Shipment report to use AddressDict for Ship-to code and address number. **Better logistics management** and delivery tracking. [*mpisana*]
  * Address handling in warehouse shipment report by adding Ship-to code and updating address features. **Better logistics management** and delivery tracking. [*mpisana*]
  * Report for updating item descriptions on open orders. This **optimizes warehouse operations**. [*albertodone*]
#### 🌐 General
  * Packaging Type Code feature in various detail sections with tooltip and application area. **Enhanced capabilities** for business operations. [*albertodone*]
  * Added SEPA Ditrect Debit Mandates report. **Enhanced capabilities** for business operations. [*albertodone*]
  * Email subject assignment to use GetSubjectFromWordTemplate method. This **improves overall functionality**. [*mpisana*]
#### 🛒 Sales
  * CRM Annotation feature and related logic for handling comments in Sales Orders. This **improves customer management** processes. [*albertodone*]
  * Salesperson and Responsibility Center features to CRM Account and Order features, and update related logic in API management. **Better sales workflows** and customer tracking. [*albertodone*]
---
### 🪲 Bug Fixes
#### 🛍️ Purchase
  * Report ID for Expenses Receipts Images. This **enhances supplier management** workflows. [*albertodone*]
#### 📦 Logistic
  * Vessel Status dropdown options and captions for clarity. This **optimizes warehouse operations**. [*mpisana*]

## Release 26.0.312.0 (PR #451) - 25/09/2025
### ✨ Features
#### 🛍️ Purchase
  * Handling for Sales and Purchase document type in DocuFlow copy/link/move. Procurement teams can **process orders faster**. [*albertodone*]
  * Print Receipts Images action to Expenses Card and List features, and implement corresponding report for receipts images. This **enhances supplier management** workflows. [*albertodone*]
  * Drill-down feature for Qty on SO/BSO PO/BPO. **Improved vendor relationships** and order tracking. [*mpisana*]
  * Hide Email features in purchase order improvements. Procurement teams can **process orders faster**. [*mpisana*]
#### 💰 Finance
  * ES Intrastat Management feature with event subscribers and feature updates. Users can now **manage finances** more efficiently. [*albertodone*]
#### 📦 Logistic
  * Refactor container handling to use Dictionary for improved efficiency. This **optimizes warehouse operations**. [*mpisana*]
  * Item By Event action to Transfer Order detail section. This **optimizes warehouse operations**. [*mpisana*]
#### ⚙️ Platform
  * User settings feature for DocuFlow with sorting preferences and new features. This **enhances technical capabilities**. [*albertodone*]
---
### 🪲 Bug Fixes
#### 🛍️ Purchase
  * Make GetRecurringPurchaseLines action visible in Log. Purchase Order feature. Procurement teams can **process orders faster**. [*albertodone*]
#### 💰 Finance
  * Missing dependency entry for Intrastat Core in app.json. **Better financial control** for accounting teams. [*albertodone*]
#### 📦 Logistic
  * item tracking and correct location code reference in item tracking lines improvement. This **optimizes warehouse operations**. [*mpisana*]
  * Ensure valid remaining quantity before inserting entry in blanket purchase order processing. Users can **track shipments** more effectively. [*albertodone*]
#### 🌐 General
  * Renamed file. This **improves overall functionality**. [*albertodone*]
  * SubfeatureLink to use 'Blanket Order' for consistency. **Enhanced capabilities** for business operations. [*mpisana*]
  * Updated 'Requested Delivery Date'. **Enhanced capabilities** for business operations. [*mpisana*]
#### ⚙️ Platform
  * Obsolete reason for Client ID feature in Dyn365 Integration Setup feature. Users benefit from **improved system performance**. [*albertodone*]
#### 🛒 Sales
  * Prevent division by zero in commission amount calculation in Sales Detail Mgmt. **Better sales workflows** and customer tracking. [*albertodone*]

## Release 26.0.311.0 (PR #446) - 22/09/2025
### ✨ Features
#### 🛍️ Purchase
  * Email management by adding customer and vendor email. This **enhances supplier management** workflows. [*mpisana*]
#### 📦 Logistic
  * Key for Item Ledger Entry No. in Tracking Specification improvement. This **optimizes warehouse operations**. [*albertodone*]
  * New key for Item Ledger Entry and create PBI Tracking Spec. improvement. This **optimizes warehouse operations**. [*albertodone*]
  * Record retrieval logic in PBI Item Ledg. Entries API. **Better logistics management** and delivery tracking. [*albertodone*]
  * New key for Item No., Variant Code, Lot No., and Open in Sell Off List Entry feature. **Better logistics management** and delivery tracking. [*albertodone*]
  * Import Requisition Worksheets action to Logistic Role Center. Users can **track shipments** more effectively. [*mpisana*]
  * Receipt Name feature to Warehouse Receipt List feature. This **optimizes warehouse operations**. [*mpisana*]
  * Excel import/export feature to Warehouse Receipts and Shipment List features. This **optimizes warehouse operations**. [*mpisana*]
  * Refactor: remove unused user tasks and job queue entry parts; add import action to Ext. Logistic Role Center. Users can **track shipments** more effectively. [*mpisana*]
#### ⚙️ Platform
  * Req. Worksheet Ext. Whse feature and update permissionset. Users benefit from **improved system performance**. [*mpisana*]
  * New feature improvements and modify visibility settings for various features in Profile. **Better platform stability** and functionality. [*mpisana*]
#### 🛒 Sales
  * Validation for CustomerId feature in Dyn365APIfeature. **Better sales workflows** and customer tracking. [*albertodone*]
---
### 🪲 Bug Fixes
#### 📦 Logistic
  * Vehicle mapping in Transporeon Purch. Line feature relation. **Better logistics management** and delivery tracking. [*mpisana*]
  * Correct authorization header handling in Transporeon API requests. Users can **track shipments** more effectively. [*mpisana*]
#### ⚙️ Platform
  * Correct indexing in Evaluate calls for ExpenseLineKey. Users benefit from **improved system performance**. [*mpisana*]
#### 🛒 Sales
  * Correct parameter for GetLinkedPurchOrderFilter in Sales Order Serv. Info feature improvement. **Better sales workflows** and customer tracking. [*albertodone*]

## Release 26.0.310.0 (PR #441) - 18/09/2025
---
### ✨ Features
#### 📦 Logistic
  * Security Vault dependency in Transporeon API. Users can **track shipments** more effectively. [*albertodone*]

## Release 26.0.308.0 (PR #434) - 12/09/2025
### ✨ Features
#### 🛍️ Purchase
  * Make "Ship-to code" feature edifeature in Purchase Req. Worksheet. Procurement teams can **process orders faster**. [*mpisana*]
  * Unused journal template inheritance procedures for sales and purchase headers. Procurement teams can **process orders faster**. [*albertodone*]
  * Journal template inheritance logic for sales and purchase headers. Procurement teams can **process orders faster**. [*albertodone*]
#### 💰 Finance
  * Intrastat and invoicing management by adding Reason Code features and updating payment terms handling. This **improves financial workflows** and reduces errors. [*albertodone*]
  * Invoice Document HU word layout. **Better financial control** for accounting teams. [*mpisana*]
#### 📦 Logistic
  * Refactor Transporeon Sales Order and Sales Orders features to use TransportID and TransportOrderStatus variables. Users can **track shipments** more effectively. [*mpisana*]
#### 💳 Credit
  * Credit memo payment terms handling. **Improved risk management** and collection workflows. [*albertodone*]
#### 🌐 General
  * ENV code retrieval logic in Doc. Report ES Mgt.. This **improves overall functionality**. [*mpisana*]
  * Support for Option feature type in Expr. Solver Functions. Users benefit **across the system**. [*mpisana*]
  * Document Report ES with new features and improved translations. Users benefit **across the system**. [*mpisana*]
  * Filter obsolete features in DB Correction Management. This **improves overall functionality**. [*albertodone*]
#### 🛒 Sales
  * Sell-to Customer No. feature to Requisition Line and update related logic. **Better sales workflows** and customer tracking. [*mpisana*]
  * Refactor Sales Order and Sales Order List improvements to use LinkedPurchOrder variable. This **improves customer management** processes. [*mpisana*]
---
### 🪲 Bug Fixes
#### 🛍️ Purchase
  * Updates Sales Document ES and  Purchase Document ES. **Improved vendor relationships** and order tracking. [*mpisana*]

## Release 26.0.307.0 (PR #430) - 08/09/2025
### ✨ Features
#### 💰 Finance
  * New features and extend existing functionalities for Intrastat management. Users can now **manage finances** more efficiently. [*albertodone*]
---
### 🪲 Bug Fixes
#### 📦 Logistic
  * Deletion of PullId in ProcessTransporeonOrderLog procedure. **Better logistics management** and delivery tracking. [*mpisana*]
#### 🌐 General
  * Version to 26.0.0.0 and extend id range to 55999. Users benefit **across the system**. [*mpisana*]

## Release 26.0.306.0 (PR #424) - 06/09/2025
### ✨ Features
#### 🛍️ Purchase
  * New email templates for purchase orders, sales confirmations, and invoices in English and Spanish. Procurement teams can **process orders faster**. [*mpisana*]
#### 📦 Logistic
  * Transporeon order handling in sales and purchase order features. This **optimizes warehouse operations**. [*mpisana*]
#### 🌐 General
  * Created new app Base ES. Users benefit **across the system**. [*mpisana*]
---
### 🪲 Bug Fixes
#### 🛒 Sales
  * Updated Sales Order Confirmation ENU template (ES). **Better sales workflows** and customer tracking. [*mpisana*]
  * Correct grammatical error in Sales Order Confirmation DEU template. **Better sales workflows** and customer tracking. [*mpisana*]

## Release 25.4.302.0 (PR #457) - 28/09/2025
### ✨ Features
#### 🛍️ Purchase
  * improvement for "Order No." visibility in Posted Purchase Receipt Lines feature. Procurement teams can **process orders faster**. [*mpisana*]
#### 💰 Finance
  * Payment Method Code feature from Acc. General Journal feature improvement. Users can now **manage finances** more efficiently. [*albertodone*]
  * Scheduled import feature in Expenses management. This **improves financial workflows** and reduces errors. [*mpisana*]
  * Payment Method Code feature to Profile General Journal feature. This **improves financial workflows** and reduces errors. [*mpisana*]
  * Payment Method Code feature to Acc. General Journal with non-edifeature property. This **improves financial workflows** and reduces errors. [*albertodone*]
#### 📦 Logistic
  * Calculation of shipping no. series during SalesOrder creation from SalesBlanket. **Better logistics management** and delivery tracking. [*albertodone*]
  * Action to view item availability by event in Import Req. Worksheet feature. This **optimizes warehouse operations**. [*mpisana*]
  * Address columns in Warehouse Shipment report to use AddressDict for Ship-to code and address number. This **optimizes warehouse operations**. [*mpisana*]
  * Address handling in warehouse shipment report by adding Ship-to code and updating address features. This **optimizes warehouse operations**. [*mpisana*]
  * Report for updating item descriptions on open orders. This **optimizes warehouse operations**. [*albertodone*]
#### 🌐 General
  * Packaging Type Code feature in various detail sections with tooltip and application area. This **improves overall functionality**. [*albertodone*]
  * Added SEPA Ditrect Debit Mandates report. Users benefit **across the system**. [*albertodone*]
  * Email subject assignment to use GetSubjectFromWordTemplate method. Users benefit **across the system**. [*mpisana*]
#### 🛒 Sales
  * CRM Annotation feature and related logic for handling comments in Sales Orders. This **improves customer management** processes. [*albertodone*]
  * Salesperson and Responsibility Center features to CRM Account and Order features, and update related logic in API management. This **improves customer management** processes. [*albertodone*]
---
### 🪲 Bug Fixes
#### 🛍️ Purchase
  * Report ID for Expenses Receipts Images. Procurement teams can **process orders faster**. [*albertodone*]
#### 📦 Logistic
  * Vessel Status dropdown options and captions for clarity. Users can **track shipments** more effectively. [*mpisana*]

## Release 25.4.301.0 (PR #415) - 04/09/2025
---
### ✨ Features
#### 📦 Logistic
  * Expand permissions for Transporeon API and Tracking Management. **Better logistics management** and delivery tracking. [*albertodone*]

## Release 25.4.298.0 (PR #407) - 29/08/2025
### ✨ Features
#### 📦 Logistic
  * Calc. Availability Management feature with event subscribers for item availability filtering. Users can **track shipments** more effectively. [*mpisana*]
  * Enable delayed insert for Cust. Alternative Payments feature and enforce NotBlank for Item Category Code. **Better logistics management** and delivery tracking. [*mpisana*]
#### 🛒 Sales
  * Purch. Doc. Summary Buffer and related feature for Sales Order linking and pricing. **Better sales workflows** and customer tracking. [*mpisana*]
---
### 🪲 Bug Fixes
#### 📦 Logistic
  * Exclude Shipment Method Code assignment in SSO Purchase Header. Users can **track shipments** more effectively. [*albertodone*]
#### 💳 Credit
  * Correct spelling in app name for Credit Mixer Interface. **Improved risk management** and collection workflows. [*albertodone*]
#### 🛒 Sales
  * Calculation method for Sales Detail unit cost. **Better sales workflows** and customer tracking. [*albertodone*]
  * Correct spelling in procedure names for Sales Header VAT category updates. **Better sales workflows** and customer tracking. [*albertodone*]

## Release 25.4.297.0 (PR #402) - 26/08/2025
---
### ✨ Features
#### 🌐 General
  * Base dependency to app.json. Users benefit **across the system**. [*albertodone*]

## Release 25.4.294.0 (PR #395) - 24/08/2025
---
### ✨ Features
#### 📦 Logistic
  * Shipment Method Code feature to Sales Open Price Closing feature. **Better logistics management** and delivery tracking. [*mpisana*]
  * Moved shipping section after sales lines. Users can **track shipments** more effectively. [*mpisana*]
#### 🌐 General
  * DependenciesGraphALL.gv to refine relationships and add new nodes. **Enhanced capabilities** for business operations. [*mpisana*]

## Release 25.4.293.0 (PR #393) - 18/08/2025
---
### ✨ Features
#### 🌐 General
  * Updated DE translations. This **improves overall functionality**. [*mpisana*]
#### 🛒 Sales
  * Acc. Customer List improvement and include in IPL_ACCOUNTING profile. Sales teams can **work more efficiently** with customers. [*mpisana*]

## Release 25.4.292.0 (PR #391) - 08/08/2025
### ✨ Features
#### 🛍️ Purchase
  * Event subscriber to update payment reference on vendor invoice number change. **Improved vendor relationships** and order tracking. [*albertodone*]
#### 💰 Finance
  * Amount per Ton (LCY) feature and update calculations in commission entries. Users can now **manage finances** more efficiently. [*albertodone*]
#### 📦 Logistic
  * Message Center on Posted Return Shipment and Posted Return Shipments. **Better logistics management** and delivery tracking. [*albertodone*]
  * Action to force update purchase order with Transporeon data in Transporeon Purch. Order feature. Propagation of SuspendStatusCheck on Line Disc. % validation. Users can **track shipments** more effectively. [*albertodone*]
#### 🌐 General
  * feature to download selected documents as a single PDF across various document types. This **improves overall functionality**. [*albertodone*]
#### ⚙️ Platform
  * User task actions to support bulk marking as read/unread with confirmation prompts. **Better platform stability** and functionality. [*albertodone*]
### 🪲 Bug Fixes
#### 💰 Finance
  * Review commission calculations. **Better financial control** for accounting teams. [*albertodone*]
#### 🌐 General
  * Report caption to include 'IPL' for clarity. Users benefit **across the system**. [*albertodone*]
---
### 🔧 Other Changes
#### 🌐 General
  * Move PropagateSuspendStatusCheck event subscriber to the end of the procedure for better organization. This **improves overall functionality**. [*albertodone*]

## Release 25.4.291.0 (PR #387) - 05/08/2025
---
### ✨ Features
#### 🛍️ Purchase
  * feature to disable purchase and sales defaults from posting groups. This **enhances supplier management** workflows. [*albertodone*]
#### 💰 Finance
  * Posting actions with new preview feature in Financial Journal. This **improves financial workflows** and reduces errors. [*albertodone*]
  * Replaced actions for posting and added action for preview posting in Financial Journal improvement. This **improves financial workflows** and reduces errors. [*albertodone*]
#### 📦 Logistic
  * "Item By Event" action to Role Center and Sales Role Center features. **Better logistics management** and delivery tracking. [*mpisana*]
#### 🌐 General
  * Navigation action and posting date feature to Email with Missing CoA features. Users benefit **across the system**. [*albertodone*]
  * DependencyGraph with new relationships and remove obsolete ones. This **improves overall functionality**. [*mpisana*]

## Release 25.4.290.0 (PR #382) - 04/08/2025
### ✨ Features
#### 🛍️ Purchase
  * Default assignment for VAT and Gen. Business Posting Groups in Purchase Header. This **enhances supplier management** workflows. [*albertodone*]
  * Reorganize VAT Info group and features in Purchase Return Order feature improvement. **Improved vendor relationships** and order tracking. [*mpisana*]
#### 💰 Finance
  * OnRun trigger to schedule Costing Period calculation. **Better financial control** for accounting teams. [*albertodone*]
#### 🌐 General
  * General Ledger report. **Enhanced capabilities** for business operations. [*albertodone*]
  * Handling Unit Type Code feature to Packaging Types feature. Users benefit **across the system**. [*mpisana*]
#### ⚙️ Platform
  * Reports for Financial Ledger and General Ledger to IPLBaseDE permissionset. **Better platform stability** and functionality. [*albertodone*]
  * User task management with "Task to Read" feature. **Better platform stability** and functionality. [*albertodone*]
#### 🛒 Sales
  * Unit Price feature to PUR Sales Lines feature improvement. **Better sales workflows** and customer tracking. [*mpisana*]
---
### 🪲 Bug Fixes
#### 🌐 General
  * Rename task count procedures and features for consistency. **Enhanced capabilities** for business operations. [*albertodone*]
  * VATDateCaption to DateCaption in report layout. Users benefit **across the system**. [*albertodone*]
  * Redundant variable declaration in GetCurrencyCode procedure. **Enhanced capabilities** for business operations. [*albertodone*]
  * Report improvement ID for Suggest Worksheet Lines. Users benefit **across the system**. [*albertodone*]
#### ⚙️ Platform
  * Redundant GLSetup record declaration in GetCurrencyCode procedure. This **enhances technical capabilities**. [*albertodone*]
  * Correct parameter usage in OnSetUpNewLineOnBeforeIncrDocNoHandler procedure. Users benefit from **improved system performance**. [*albertodone*]
  * Integration setup retrieval in order creation process. Users benefit from **improved system performance**. [*albertodone*]
  * Ensure correct language setting when applying saved views in cue management. Users benefit from **improved system performance**. [*mpisana*]

## Release 25.4.289.0 (PR #375) - 29/07/2025
---
### ✨ Features
#### ⚙️ Platform
  * Refactor authentication logic in DocuFlow ArxNext Mgt. feature. Users benefit from **improved system performance**. [*albertodone*]

## Release 25.4.287.0 (PR #370) - 28/07/2025
### ✨ Features
#### ⚙️ Platform
  * Start Date feature and enhance Azure Key Vault secret handling. Users benefit from **improved system performance**. [*albertodone*]
---
### 🪲 Bug Fixes
#### 🌐 General
  * Unused namespaces in Base.DE. **Enhanced capabilities** for business operations. [*albertodone*]
#### ⚙️ Platform
  * Unused IPLSecurityVaultDataScopeType enum file. **Better platform stability** and functionality. [*albertodone*]

## Release 25.4.281.0 (PR #354) - 21/07/2025
---
### 🪲 Bug Fixes
#### 🌐 General
  * Set Subject feature as non-edifeature. Users benefit **across the system**. [*mpisana*]
  * Ensure "Word Template Code" feature is not blank. This **improves overall functionality**. [*mpisana*]
  * "Your Reference" feature to Profile Purch. Ret. Order feature improvement. Users benefit **across the system**. [*mpisana*]
#### 🛒 Sales
  * Simplify condition for EOS Type check in Sales Document report. **Better sales workflows** and customer tracking. [*mpisana*]

## Release 25.4.280.0 (PR #351) - 21/07/2025
---
### 🪲 Bug Fixes
#### 🌐 General
  * Correct feature reference from "Expr. Solver Tester" to "Expr. Solver Editor". This **improves overall functionality**. [*albertodone*]

## Release 25.4.277.0 (PR #344) - 17/07/2025
---
### ✨ Features
#### 💰 Finance
  * Payment Terms Additional Description to invoice report and update DE translations. **Better financial control** for accounting teams. [*mpisana*]
#### 📦 Logistic
  * Sales and Shipment documents to improve item number formatting and handling of charge items + update DE Translations. Users can **track shipments** more effectively. [*mpisana*]
#### 🌐 General
  * ES report translations. This **improves overall functionality**. [*mpisana*]
  * New app Document Report ES. **Enhanced capabilities** for business operations. [*mpisana*]
  * Email Management features including Word Template handling and subject entries. Users benefit **across the system**. [*mpisana*]
  * Expression solver feature and related features. This **improves overall functionality**. [*mpisana*]
#### ⚙️ Platform
  * IPL.Email Mgmt permissionset to include Email Subject Entry and related features. This **enhances technical capabilities**. [*mpisana*]

## Release 25.4.276.0 (PR #338) - 14/07/2025
---
### 🪲 Bug Fixes
#### 🌐 General
  * feature ID for Reason Code Type in feature improvement. This **improves overall functionality**. [*albertodone*]

## Release 25.4.273.0 (PR #330) - 04/07/2025
---
### ✨ Features
#### 🌐 General
  * Ship-to Mail Address feature and related features/improvements. Users benefit **across the system**. [*albertodone*]
  * Refactor: update visibility for EU 3rd Party Trade. This **improves overall functionality**. [*mpisana*]
  * Refactor: reorder Source Name feature for better layout consistency. This **improves overall functionality**. [*mpisana*]
  * Added source type and source no features. This **improves overall functionality**. [*mpisana*]
  * Refactor: SK > fixed featureExt to address IT localization requirements. Users benefit **across the system**. [*mpisana*]
  * Refactor: W1 > fixed featureExt to address IT localization requirements. Users benefit **across the system**. [*mpisana*]
  * Refactor: HU > fixed featureExt to address IT localization requirements. This **improves overall functionality**. [*mpisana*]
  * Refactor: ES > fixed featureExt to address IT localization requirements. **Enhanced capabilities** for business operations. [*mpisana*]
  * Refactor: DE > fixed featureExt to address IT localization requirements. Users benefit **across the system**. [*mpisana*]
  * Refactor: BE > fixed featureExt to address IT localization requirements. **Enhanced capabilities** for business operations. [*mpisana*]
  * Refactor: HU > corrected certain features to address IT localization requirements. Users benefit **across the system**. [*mpisana*]
  * Refactor: SK > corrected certain features to address IT localization requirements. This **improves overall functionality**. [*mpisana*]
  * Refactor: ES > corrected certain features to address IT localization requirements. **Enhanced capabilities** for business operations. [*mpisana*]
  * Refactor: DE > corrected certain features to address IT localization requirements. This **improves overall functionality**. [*mpisana*]
  * Refactor: BE > corrected certain features to address IT localization requirements. **Enhanced capabilities** for business operations. [*mpisana*]
  * Refactor: W1 > corrected certain features to address IT localization requirements. **Enhanced capabilities** for business operations. [*mpisana*]

## Release 25.4.272.0 (PR #327) - 03/07/2025
---
### 🪲 Bug Fixes
#### 🛍️ Purchase
  * Correct report ID for Vendor Statement. **Improved vendor relationships** and order tracking. [*mpisana*]

## Release 25.4.270.0 (PR #321) - 02/07/2025
---
### 🪲 Bug Fixes
#### 🛍️ Purchase
  * feature order and remove unused feature in Profile BPO detail section. **Improved vendor relationships** and order tracking. [*albertodone*]

## Release 25.4.265.0 (PR #307) - 26/06/2025
---
### 🪲 Bug Fixes
#### 🛍️ Purchase
  * Vendor - Balance to Date report with configurable options. Procurement teams can **process orders faster**. [*albertodone*]

## Release 25.4.263.0 (PR #304) - 26/06/2025
---
### 🔧 Other Changes
#### 🌐 General
  * [main@138d8b9] Update AL-Go System Files from microsoft/AL-Go-PTE@main - e247881. This **improves overall functionality**. [*albertodone*]

## Release 25.4.260.0 (PR #299) - 19/06/2025
---
### 🪲 Bug Fixes
#### ⚙️ Platform
  * Extend permission set for Email Management to include Address Book entries. This **enhances technical capabilities**. [*albertodone*]

## Release 25.4.257.0 (PR #457) - 28/09/2025
### ✨ Features
#### 🛍️ Purchase
  * improvement for "Order No." visibility in Posted Purchase Receipt Lines feature. This **enhances supplier management** workflows. [*mpisana*]
#### 💰 Finance
  * Payment Method Code feature from Acc. General Journal feature improvement. **Better financial control** for accounting teams. [*albertodone*]
  * Scheduled import feature in Expenses management. **Better financial control** for accounting teams. [*mpisana*]
  * Payment Method Code feature to Profile General Journal feature. **Better financial control** for accounting teams. [*mpisana*]
  * Payment Method Code feature to Acc. General Journal with non-edifeature property. Users can now **manage finances** more efficiently. [*albertodone*]
#### 📦 Logistic
  * Calculation of shipping no. series during SalesOrder creation from SalesBlanket. This **optimizes warehouse operations**. [*albertodone*]
  * Action to view item availability by event in Import Req. Worksheet feature. This **optimizes warehouse operations**. [*mpisana*]
  * Address columns in Warehouse Shipment report to use AddressDict for Ship-to code and address number. **Better logistics management** and delivery tracking. [*mpisana*]
  * Address handling in warehouse shipment report by adding Ship-to code and updating address features. This **optimizes warehouse operations**. [*mpisana*]
  * Report for updating item descriptions on open orders. **Better logistics management** and delivery tracking. [*albertodone*]
#### 🌐 General
  * Packaging Type Code feature in various detail sections with tooltip and application area. This **improves overall functionality**. [*albertodone*]
  * Added SEPA Ditrect Debit Mandates report. This **improves overall functionality**. [*albertodone*]
  * Email subject assignment to use GetSubjectFromWordTemplate method. Users benefit **across the system**. [*mpisana*]
#### 🛒 Sales
  * CRM Annotation feature and related logic for handling comments in Sales Orders. **Better sales workflows** and customer tracking. [*albertodone*]
  * Salesperson and Responsibility Center features to CRM Account and Order features, and update related logic in API management. **Better sales workflows** and customer tracking. [*albertodone*]
---
### 🪲 Bug Fixes
#### 🛍️ Purchase
  * Report ID for Expenses Receipts Images. **Improved vendor relationships** and order tracking. [*albertodone*]
#### 📦 Logistic
  * Vessel Status dropdown options and captions for clarity. This **optimizes warehouse operations**. [*mpisana*]

## Release 25.4.256.0 (PR #290) - 15/06/2025
---
### 🪲 Bug Fixes
#### ⚙️ Platform
  * Define permissions for IPL.UserMgt.Admin permission set. **Better platform stability** and functionality. [*albertodone*]

## Release 25.4.251.0 (PR #279) - 10/06/2025
---
### 🪲 Bug Fixes
#### ⚙️ Platform
  * Permissions for Surplus Output management in IPL.TransformOrder. This **enhances technical capabilities**. [*albertodone*]
#### 🛒 Sales
  * Refine competence date logic in Sales Detail management. This **improves customer management** processes. [*albertodone*]

## Release 25.4.249.0 (PR #272) - 06/06/2025
### ✨ Features
#### 💰 Finance
  * Added 'Skipped' status to Expenses. Updated related logic in features, features, and reports. Updated "open expense" on header. This **improves financial workflows** and reduces errors. [*mpisana*]
#### 📦 Logistic
  * Event subscriber to delete all warehouse shipment lines before updating receipt line. **Better logistics management** and delivery tracking. [*albertodone*]
#### 🌐 General
  * DE add new document template. **Enhanced capabilities** for business operations. [*mpisana*]
  * Created IPL.Profile DE. Users benefit **across the system**. [*mpisana*]
  * Patching feature for DocuFlow entries and enhance UI with new features. **Enhanced capabilities** for business operations. [*mpisana*]
---
### 🪲 Bug Fixes
#### 💰 Finance
  * Rename 'Payment Method Code' feature to 'Payment Method Code'. Users can now **manage finances** more efficiently. [*albertodone*]
#### 📦 Logistic
  * Case handling for Sales Shipment Header in OnPreReport trigger. Users can **track shipments** more effectively. [*mpisana*]
  * GetTransferShipmentHeader procedure and update logic for Transfer Shipment Header. This **optimizes warehouse operations**. [*mpisana*]
#### 🌐 General
  * Category validation logic in ApplyOrderHeaderCategories procedure. **Enhanced capabilities** for business operations. [*mpisana*]
  * Current feature on file upload triggers. This **improves overall functionality**. [*albertodone*]
#### 🛒 Sales
  * Handle customer retrieval in GetCustomer procedure. This **improves customer management** processes. [*albertodone*]

## Release 25.4.248.0 (PR #267) - 29/05/2025
---
### 🪲 Bug Fixes
#### ⚙️ Platform
  * Rename 'Verificator' to 'Verifier' in user task features and filters for consistency. **Better platform stability** and functionality. [*albertodone*]

## Release 25.4.244.0 (PR #262) - 23/05/2025
---
### 🪲 Bug Fixes
#### 💰 Finance
  * Move Acc. Financial Journal into Profile.BE. Users can now **manage finances** more efficiently. [*albertodone*]

## Release 25.4.240.0 (PR #255) - 21/05/2025
---
### 🔧 Other Changes
#### 🌐 General
  * Incremented Version number by +0.1. This **improves overall functionality**. [*albertodone*]

## Release 25.3.236.0 (PR #251) - 16/05/2025
---
### 🔧 Other Changes
#### 🌐 General
  * [main@158f974] Update AL-Go System Files from microsoft/AL-Go-PTE@main - 14c066b. Users benefit **across the system**. [*albertodone*]

## Release 25.3.233.0 (PR #247) - 15/05/2025
### ✨ Features
#### 🛍️ Purchase
  * Navigate Exxon API feature to manage promoted actions and clean up code. Procurement teams can **process orders faster**. [*mpisana*]
#### 💰 Finance
  * "Acc. Reminder List" improvement to IPL_ACCOUNTING profile. **Better financial control** for accounting teams. [*mpisana*]
  * improvement for Acc. Issued Reminder List and include in IPL_ACCOUNTING profile. Users can now **manage finances** more efficiently. [*mpisana*]
#### 📦 Logistic
  * Gross Weight feature to Update Sales Shpt Lines feature and create Utility User Settings improvement for customer, vendor, and item management. **Better logistics management** and delivery tracking. [*mpisana*]
---
### 🪲 Bug Fixes
#### ⚙️ Platform
  * Validation for Customer Price Group based on Price List Header settings. **Better platform stability** and functionality. [*mpisana*]

## Release 25.3.231.0 (PR #244) - 14/05/2025
---
### ✨ Features
#### 🛍️ Purchase
  * Vendor Order No. feature to PUR Blanket Purch. Orders feature. This **enhances supplier management** workflows. [*mpisana*]
  * OnLookup trigger for Posting No. Series in sales and purchase order improvements. This **enhances supplier management** workflows. [*mpisana*]

## Release 25.3.229.0 (PR #240) - 14/05/2025
### ✨ Features
#### 💰 Finance
  * improvement for File SEPA Payments with file name as filename. This **improves financial workflows** and reduces errors. [*albertodone*]
#### 📦 Logistic
  * Event subscribers for direct shipment and receipt handling in Warehouse Management. Users can **track shipments** more effectively. [*albertodone*]
  * New BE.Base App. feat: Journal Management in Extended Combine Shipment. This **optimizes warehouse operations**. [*albertodone*]
---
### 🪲 Bug Fixes
#### 📦 Logistic
  * Comb. Shipment improvement feature with event subscriber for Location, Categories and Posting No. Series copy from order. **Better logistics management** and delivery tracking. [*albertodone*]

## Release 25.3.227.0 (PR #237) - 12/05/2025
### ✨ Features
#### 📦 Logistic
  * Update Lot Info Item Entries feature. Users can **track shipments** more effectively. [*albertodone*]
---
### 🪲 Bug Fixes
#### 📦 Logistic
  * Correct caption for Update Lot Info Item Entry feature. **Better logistics management** and delivery tracking. [*albertodone*]
  * Update Lot Info on Item Entry feature. Users can **track shipments** more effectively. [*albertodone*]

## Release 25.3.223.0 (PR #231) - 09/05/2025
### ✨ Features
#### 🛍️ Purchase
  * BE Add EU 3-Party Trade Purchase dependency and enhance visibility in Purchase Invoice feature improvement. **Improved vendor relationships** and order tracking. [*mpisana*]
#### 🌐 General
  * improvements for IPL_CSR_PURCH. **Enhanced capabilities** for business operations. [*mpisana*]
#### 🛒 Sales
  * Enterprise no. to Profile Sales Ret.Order BE. This **improves customer management** processes. [*mpisana*]
---
### 🪲 Bug Fixes
#### 🛍️ Purchase
  * HU Add EU 3-Party Trade Purchase dependency and enhance visibility in Purchase Invoice improvement. This **enhances supplier management** workflows. [*mpisana*]
  * SK Add EU 3-Party Trade Purchase improvement and update profile improvements. Procurement teams can **process orders faster**. [*mpisana*]
  * "Pay-to Vendor No." feature from PUR Purchase Order improvement (added in featureExt). **Improved vendor relationships** and order tracking. [*mpisana*]
#### 💰 Finance
  * Layout and visibility for IC and Invoice details in multiple features. **Better financial control** for accounting teams. [*mpisana*]
#### 🌐 General
  * Background color. Users benefit **across the system**. [*mpisana*]
#### ⚙️ Platform
  * EU 3-Party Trade Purchase dependency and related visibility settings in Purchase Invoice improvement. **Better platform stability** and functionality. [*mpisana*]
  * Reorder User Tasks Activities and add actions for Sales group in Purch. Role Center. This **enhances technical capabilities**. [*mpisana*]
#### 🛒 Sales
  * Comment out "Bill-to Name" modification and related features in CSR Sales Return Order feature improvement. Sales teams can **work more efficiently** with customers. [*mpisana*]

## Release 25.3.221.0 (PR #228) - 08/05/2025
---
### 🪲 Bug Fixes
#### 📦 Logistic
  * ApplicationArea to Show Qty. (Calculated) and Show Serial/Lot Number features in Phys. Inventory List report. **Better logistics management** and delivery tracking. [*albertodone*]
