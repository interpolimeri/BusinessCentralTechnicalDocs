# AI-Enhanced Changelog

## Release 26.0.313.0 (PR #457) - 28/09/2025
### ✨ Features
#### 💰 Finance
  * Payment feature Code feature from Acc. General Journal feature improvement. Users can now **manage finances** more efficiently. [*albertodone*]
  * Scheduled import featureality in Expenses management. **Better financial control** for accounting teams. [*mpisana*]
  * Added SEPA Ditrect Debit Mandates report. **Better financial control** for accounting teams. [*albertodone*]
  * Payment feature Code feature to Profile General Journal feature. Users can now **manage finances** more efficiently. [*mpisana*]
  * improvement for "Order No." visibility in Posted Purchase Receipt Lines feature. This **improves financial workflows** and reduces errors. [*mpisana*]
  * Payment feature Code feature to Acc. General Journal with non-edifeature property. This **improves financial workflows** and reduces errors. [*albertodone*]
  * Email subject assignment to use GetSubjectFromWordTemplate feature. This **improves financial workflows** and reduces errors. [*mpisana*]
#### 📦 Logistic
  * Packaging Type Code feature in various detail sections with tooltip and application area. This **optimizes warehouse operations**. [*albertodone*]
  * Action to view item availability by event in Import Req. Worksheet feature. **Better logistics management** and delivery tracking. [*mpisana*]
  * Address columns in Warehouse Shipment report to use AddressDict for Ship-to code and address number. Users can **track shipments** more effectively. [*mpisana*]
  * Address handling in warehouse shipment report by adding Ship-to code and updating address features. **Better logistics management** and delivery tracking. [*mpisana*]
  * Report for updating item descriptions on open orders. This **optimizes warehouse operations**. [*albertodone*]
#### �️ Sales
  * CRM Annotation feature and related logic for handling comments in Sales Orders. Sales teams can **work more efficiently** with customers. [*albertodone*]
  * Calculation of shipping no. series during SalesOrder creation from SalesBlanket. Sales teams can **work more efficiently** with customers. [*albertodone*]
  * Salesperson and Responsibility Center features to CRM Account and Order features, and update related logic in API management. This **improves customer management** processes. [*albertodone*]
---
### 🪲 Bug Fixes
#### 💰 Finance
  * Report ID for Expenses Receipts Images. Users can now **manage finances** more efficiently. [*albertodone*]
#### 📦 Logistic
  * Vessel Status dropdown options and captions for clarity. This **optimizes warehouse operations**. [*mpisana*]

## Release 26.0.312.0 (PR #451) - 25/09/2025
### ✨ Features
#### � Purchase
  * Hide Email features in purchase order improvements. This **enhances supplier management** workflows. [*mpisana*]
#### 💰 Finance
  * Print Receipts Images action to Expenses Card and List features, and implement corresponding report for receipts images. This **improves financial workflows** and reduces errors. [*albertodone*]
  * ES Intrastat Management feature with features and feature updates. **Better financial control** for accounting teams. [*albertodone*]
#### 📦 Logistic
  * Refactor container handling to use Dictionary for improved efficiency. This **optimizes warehouse operations**. [*mpisana*]
  * Item By Event action to Transfer Order detail section. Users can **track shipments** more effectively. [*mpisana*]
#### ⚙️ System
  * User settings featureality for DocuFlow with sorting preferences and new features. Users benefit from **improved system performance**. [*albertodone*]
#### �️ Sales
  * Handling for Sales and Purchase document type in DocuFlow copy/link/move. **Better sales workflows** and customer tracking. [*albertodone*]
  * Drill-down featureality for Qty on SO/BSO PO/BPO. Sales teams can **work more efficiently** with customers. [*mpisana*]
---
### 🪲 Bug Fixes
#### � Purchase
  * Make GetRecurringPurchaseLines action visible in Log. Purchase Order feature. **Improved vendor relationships** and order tracking. [*albertodone*]
#### 💰 Finance
  * Missing system component entry for Intrastat Core in app.json. **Better financial control** for accounting teams. [*albertodone*]
#### 📦 Logistic
  * item tracking and correct location code reference in item tracking lines improvement. This **optimizes warehouse operations**. [*mpisana*]
  * Ensure valid remaining quantity before inserting entry in blanket purchase order processing. This **optimizes warehouse operations**. [*albertodone*]
  * Updated 'Requested Delivery Date'. This **optimizes warehouse operations**. [*mpisana*]
#### ⚙️ System
  * system update. Users benefit from **improved system performance**. [*albertodone*]
  * Obsolete reason for Client ID feature in Dyn365 Integration Setup feature. This **enhances system capabilities**. [*albertodone*]
#### 🌐 General
  * SubfeatureLink to use 'Blanket Order' for consistency. Users benefit **across the system**. [*mpisana*]
#### �️ Sales
  * Prevent division by zero in commission amount calculation in Sales Detail Mgmt. **Better sales workflows** and customer tracking. [*albertodone*]

## Release 26.0.311.0 (PR #446) - 22/09/2025
### ✨ Features
#### 📦 Logistic
  * data structure Item Ledger Entry No. in Tracking Specification improvement. This **optimizes warehouse operations**. [*albertodone*]
  * New data structure Item Ledger Entry and create PBI Tracking Spec. improvement. Users can **track shipments** more effectively. [*albertodone*]
  * Record retrieval logic in PBI Item Ledg. Entries API. Users can **track shipments** more effectively. [*albertodone*]
  * Import Requisition Worksheets action to Logistic Role Center. Users can **track shipments** more effectively. [*mpisana*]
  * Receipt Name feature to Warehouse Receipt List feature. **Better logistics management** and delivery tracking. [*mpisana*]
  * Excel import/export featureality to Warehouse Receipts and Shipment List features. This **optimizes warehouse operations**. [*mpisana*]
  * Req. Worksheet Ext. Whse feature and update permissionset. This **optimizes warehouse operations**. [*mpisana*]
  * Refactor: remove unused user tasks and job queue entry parts; add import action to Ext. Logistic Role Center. Users can **track shipments** more effectively. [*mpisana*]
#### ⚙️ System
  * New feature improvements and modify visibility settings for various features in Profile. **Better system stability** and functionality. [*mpisana*]
#### �️ Sales
  * New data structure Item No., Variant Code, Lot No., and Open in Sell Off List Entry feature. **Better sales workflows** and customer tracking. [*albertodone*]
  * Validation for CustomerId feature in Dyn365APIfeature. **Better sales workflows** and customer tracking. [*albertodone*]
  * Email management by adding customer and vendor email. **Better sales workflows** and customer tracking. [*mpisana*]
---
### 🪲 Bug Fixes
#### 💰 Finance
  * Correct indexing in Evaluate calls for ExpenseLineKey. This **improves financial workflows** and reduces errors. [*mpisana*]
#### 📦 Logistic
  * Vehicle mapping in Transporeon Purch. Line feature relation. Users can **track shipments** more effectively. [*mpisana*]
  * Correct authorization header handling in Transporeon API requests. Users can **track shipments** more effectively. [*mpisana*]
#### �️ Sales
  * Correct parameter for GetLinkedPurchOrderFilter in Sales Order Serv. Info feature improvement. This **improves customer management** processes. [*albertodone*]

## Release 26.0.310.0 (PR #441) - 18/09/2025
---
### ✨ Features
#### 📦 Logistic
  * Security Vault system component in Transporeon API. **Better logistics management** and delivery tracking. [*albertodone*]

## Release 26.0.308.0 (PR #434) - 12/09/2025
### ✨ Features
#### 💰 Finance
  * ENV code retrieval logic in Doc. Report ES Mgt.. Users can now **manage finances** more efficiently. [*mpisana*]
  * Intrastat and invoicing management by adding Reason Code features and updating payment terms handling. This **improves financial workflows** and reduces errors. [*albertodone*]
  * Credit memo payment terms handling. This **improves financial workflows** and reduces errors. [*albertodone*]
  * Invoice Document HU word layout. This **improves financial workflows** and reduces errors. [*mpisana*]
#### 📦 Logistic
  * Make "Ship-to code" feature edifeature in Purchase Req. Worksheet. **Better logistics management** and delivery tracking. [*mpisana*]
#### ⚙️ System
  * system cleanup features in DB Correction Management. **Better system stability** and functionality. [*albertodone*]
#### 🌐 General
  * Support for Option feature type in Expr. Solver features. **Enhanced capabilities** for business operations. [*mpisana*]
  * Document Report ES with new features and improved translations. Users benefit **across the system**. [*mpisana*]
#### �️ Sales
  * Sell-to Customer No. feature to Requisition Line and update related logic. **Better sales workflows** and customer tracking. [*mpisana*]
  * Refactor Sales Order and Sales Order List improvements to use LinkedPurchOrder variable. **Better sales workflows** and customer tracking. [*mpisana*]
  * Refactor Transporeon Sales Order and Sales Orders features to use TransportID and TransportOrderStatus variables. Sales teams can **work more efficiently** with customers. [*mpisana*]
  * Unused journal template inheritance features for sales and purchase headers. Sales teams can **work more efficiently** with customers. [*albertodone*]
  * Journal template inheritance logic for sales and purchase headers. Sales teams can **work more efficiently** with customers. [*albertodone*]
---
### 🪲 Bug Fixes
#### �️ Sales
  * Updates Sales Document ES and  Purchase Document ES. This **improves customer management** processes. [*mpisana*]

## Release 26.0.307.0 (PR #430) - 08/09/2025
### ✨ Features
#### 💰 Finance
  * New features and extend existing featurealities for Intrastat management. This **improves financial workflows** and reduces errors. [*albertodone*]
---
### 🪲 Bug Fixes
#### 📦 Logistic
  * Deletion of PullId in ProcessTransporeonOrderLog feature. This **optimizes warehouse operations**. [*mpisana*]
#### ⚙️ System
  * system upgrade 26.0.0.0 and extend id range to 55999. This **enhances system capabilities**. [*mpisana*]

## Release 26.0.306.0 (PR #424) - 06/09/2025
### ✨ Features
#### 🌐 General
  * Created new app Base ES. This **improves overall functionality**. [*mpisana*]
#### �️ Sales
  * New email templates for purchase orders, sales confirmations, and invoices in English and Spanish. Sales teams can **work more efficiently** with customers. [*mpisana*]
  * Transporeon order handling in sales and purchase order features. This **improves customer management** processes. [*mpisana*]
---
### 🪲 Bug Fixes
#### �️ Sales
  * Updated Sales Order Confirmation ENU template (ES). Sales teams can **work more efficiently** with customers. [*mpisana*]
  * Correct grammatical error in Sales Order Confirmation DEU template. **Better sales workflows** and customer tracking. [*mpisana*]

## Release 25.4.302.0 (PR #457) - 28/09/2025
### ✨ Features
#### 💰 Finance
  * Payment feature Code feature from Acc. General Journal feature improvement. Users can now **manage finances** more efficiently. [*albertodone*]
  * Scheduled import featureality in Expenses management. Users can now **manage finances** more efficiently. [*mpisana*]
  * Added SEPA Ditrect Debit Mandates report. Users can now **manage finances** more efficiently. [*albertodone*]
  * Payment feature Code feature to Profile General Journal feature. This **improves financial workflows** and reduces errors. [*mpisana*]
  * improvement for "Order No." visibility in Posted Purchase Receipt Lines feature. Users can now **manage finances** more efficiently. [*mpisana*]
  * Payment feature Code feature to Acc. General Journal with non-edifeature property. **Better financial control** for accounting teams. [*albertodone*]
  * Email subject assignment to use GetSubjectFromWordTemplate feature. Users can now **manage finances** more efficiently. [*mpisana*]
#### 📦 Logistic
  * Packaging Type Code feature in various detail sections with tooltip and application area. This **optimizes warehouse operations**. [*albertodone*]
  * Action to view item availability by event in Import Req. Worksheet feature. This **optimizes warehouse operations**. [*mpisana*]
  * Address columns in Warehouse Shipment report to use AddressDict for Ship-to code and address number. **Better logistics management** and delivery tracking. [*mpisana*]
  * Address handling in warehouse shipment report by adding Ship-to code and updating address features. Users can **track shipments** more effectively. [*mpisana*]
  * Report for updating item descriptions on open orders. Users can **track shipments** more effectively. [*albertodone*]
#### �️ Sales
  * CRM Annotation feature and related logic for handling comments in Sales Orders. This **improves customer management** processes. [*albertodone*]
  * Calculation of shipping no. series during SalesOrder creation from SalesBlanket. Sales teams can **work more efficiently** with customers. [*albertodone*]
  * Salesperson and Responsibility Center features to CRM Account and Order features, and update related logic in API management. Sales teams can **work more efficiently** with customers. [*albertodone*]
---
### 🪲 Bug Fixes
#### 💰 Finance
  * Report ID for Expenses Receipts Images. Users can now **manage finances** more efficiently. [*albertodone*]
#### 📦 Logistic
  * Vessel Status dropdown options and captions for clarity. Users can **track shipments** more effectively. [*mpisana*]

## Release 25.4.301.0 (PR #415) - 04/09/2025
---
### ✨ Features
#### 📦 Logistic
  * Expand permissions for Transporeon API and Tracking Management. This **optimizes warehouse operations**. [*albertodone*]

## Release 25.4.298.0 (PR #407) - 29/08/2025
### ✨ Features
#### 📦 Logistic
  * Calc. Availability Management feature with features for item availability filtering. Users can **track shipments** more effectively. [*mpisana*]
  * Enable delayed insert for Cust. Alternative Payments feature and enforce NotBlank for Item Category Code. This **optimizes warehouse operations**. [*mpisana*]
#### �️ Sales
  * Purch. Doc. Summary Buffer and related feature for Sales Order linking and pricing. Sales teams can **work more efficiently** with customers. [*mpisana*]
---
### 🪲 Bug Fixes
#### 📦 Logistic
  * Exclude Shipment feature Code assignment in SSO Purchase Header. **Better logistics management** and delivery tracking. [*albertodone*]
#### 💳 Credit
  * Correct spelling in app name for Credit Mixer Interface. **Improved risk management** and collection workflows. [*albertodone*]
#### �️ Sales
  * Calculation feature for Sales Detail unit cost. **Better sales workflows** and customer tracking. [*albertodone*]
  * Correct spelling in feature names for Sales Header VAT category updates. **Better sales workflows** and customer tracking. [*albertodone*]

## Release 25.4.297.0 (PR #402) - 26/08/2025
---
### ✨ Features
#### ⚙️ System
  * Base system component to app.json. **Better system stability** and functionality. [*albertodone*]

## Release 25.4.294.0 (PR #395) - 24/08/2025
---
### ✨ Features
#### ⚙️ System
  * system componentGraphALL.gv to refine relationships and add new nodes. **Better system stability** and functionality. [*mpisana*]
#### �️ Sales
  * Shipment feature Code feature to Sales Open Price Closing feature. Sales teams can **work more efficiently** with customers. [*mpisana*]
  * Moved shipping section after sales lines. This **improves customer management** processes. [*mpisana*]

## Release 25.4.293.0 (PR #393) - 18/08/2025
---
### ✨ Features
#### 🌐 General
  * Updated DE translations. Users benefit **across the system**. [*mpisana*]
#### �️ Sales
  * Acc. Customer List improvement and include in IPL_ACCOUNTING profile. **Better sales workflows** and customer tracking. [*mpisana*]

## Release 25.4.292.0 (PR #391) - 08/08/2025
### ✨ Features
#### 💰 Finance
  * Amount per Ton (LCY) feature and update calculations in commission entries. This **improves financial workflows** and reduces errors. [*albertodone*]
  * feature to update payment reference on vendor invoice number change. This **improves financial workflows** and reduces errors. [*albertodone*]
#### 📦 Logistic
  * Message Center on Posted Return Shipment and Posted Return Shipments. Users can **track shipments** more effectively. [*albertodone*]
  * Action to force update purchase order with Transporeon data in Transporeon Purch. Order feature. Propagation of SuspendStatusCheck on Line Disc. % validation. Users can **track shipments** more effectively. [*albertodone*]
#### ⚙️ System
  * User task actions to support bulk marking as read/unread with confirmation prompts. This **enhances system capabilities**. [*albertodone*]
#### 🌐 General
  * featureality to download selected documents as a single PDF across various document types. **Enhanced capabilities** for business operations. [*albertodone*]
### 🪲 Bug Fixes
#### 💰 Finance
  * Review commission calculations. This **improves financial workflows** and reduces errors. [*albertodone*]
#### 🌐 General
  * Report caption to include 'IPL' for clarity. This **improves overall functionality**. [*albertodone*]
---
### 🔧 Other Changes
#### 🌐 General
  * Move PropagateSuspendStatusCheck feature to the end of the feature for better organization. **Enhanced capabilities** for business operations. [*albertodone*]

## Release 25.4.291.0 (PR #387) - 05/08/2025
---
### ✨ Features
#### 💰 Finance
  * Posting actions with new preview featureality in Financial Journal. This **improves financial workflows** and reduces errors. [*albertodone*]
  * Replaced actions for posting and added action for preview posting in Financial Journal improvement. This **improves financial workflows** and reduces errors. [*albertodone*]
#### 🌐 General
  * Navigation action and posting date feature to Email with Missing CoA features. This **improves overall functionality**. [*albertodone*]
  * system componentGraph with new relationships and remove obsolete ones. **Enhanced capabilities** for business operations. [*mpisana*]
#### �️ Sales
  * featureality to disable purchase and sales defaults from posting groups. **Better sales workflows** and customer tracking. [*albertodone*]
  * "Item By Event" action to Role Center and Sales Role Center features. **Better sales workflows** and customer tracking. [*mpisana*]

## Release 25.4.290.0 (PR #382) - 04/08/2025
### ✨ Features
#### � Purchase
  * Default assignment for VAT and Gen. Business Posting Groups in Purchase Header. **Improved vendor relationships** and order tracking. [*albertodone*]
  * Reorganize VAT Info group and features in Purchase Return Order feature improvement. This **enhances supplier management** workflows. [*mpisana*]
#### 💰 Finance
  * Reports for Financial Ledger and General Ledger to IPLBaseDE permissionset. This **improves financial workflows** and reduces errors. [*albertodone*]
  * OnRun trigger to schedule Costing Period calculation. **Better financial control** for accounting teams. [*albertodone*]
#### 📦 Logistic
  * Handling Unit Type Code feature to Packaging Types feature. This **optimizes warehouse operations**. [*mpisana*]
#### ⚙️ System
  * User task management with "Task to Read" featureality. This **enhances system capabilities**. [*albertodone*]
#### 🌐 General
  * General Ledger report. **Enhanced capabilities** for business operations. [*albertodone*]
#### �️ Sales
  * Unit Price feature to PUR Sales Lines feature improvement. This **improves customer management** processes. [*mpisana*]
---
### 🪲 Bug Fixes
#### ⚙️ System
  * Redundant GLSetup record declaration in GetCurrencyCode feature. **Better system stability** and functionality. [*albertodone*]
  * Correct parameter usage in OnSetUpNewLineOnBeforeIncrDocNoHandler feature. **Better system stability** and functionality. [*albertodone*]
  * Integration setup retrieval in order creation process. This **enhances system capabilities**. [*albertodone*]
  * Ensure correct language setting when applying saved views in cue management. This **enhances system capabilities**. [*mpisana*]
#### 🌐 General
  * Rename task count features and features for consistency. **Enhanced capabilities** for business operations. [*albertodone*]
  * VATDateCaption to DateCaption in report layout. This **improves overall functionality**. [*albertodone*]
  * Redundant variable declaration in GetCurrencyCode feature. This **improves overall functionality**. [*albertodone*]
  * Report improvement ID for Suggest Worksheet Lines. Users benefit **across the system**. [*albertodone*]

## Release 25.4.289.0 (PR #375) - 29/07/2025
---
### ✨ Features
#### ⚙️ System
  * Refactor authentication logic in DocuFlow ArxNext Mgt. feature. This **enhances system capabilities**. [*albertodone*]

## Release 25.4.287.0 (PR #370) - 28/07/2025
### ✨ Features
#### ⚙️ System
  * Start Date feature and enhance Azure Key Vault secret handling. **Better system stability** and functionality. [*albertodone*]
---
### 🪲 Bug Fixes
#### ⚙️ System
  * Unused IPLSecurityVaultDataScopeType enum file. Users benefit from **improved system performance**. [*albertodone*]
#### 🌐 General
  * Unused namespaces in Base.DE. Users benefit **across the system**. [*albertodone*]

## Release 25.4.281.0 (PR #354) - 21/07/2025
---
### 🪲 Bug Fixes
#### 💰 Finance
  * Ensure "Word Template Code" feature is not blank. Users can now **manage finances** more efficiently. [*mpisana*]
#### 🌐 General
  * Set Subject feature as non-edifeature. **Enhanced capabilities** for business operations. [*mpisana*]
  * "Your Reference" feature to Profile Purch. Ret. Order feature improvement. This **improves overall functionality**. [*mpisana*]
#### �️ Sales
  * Simplify condition for EOS Type check in Sales Document report. This **improves customer management** processes. [*mpisana*]

## Release 25.4.280.0 (PR #351) - 21/07/2025
---
### 🪲 Bug Fixes
#### 🌐 General
  * Correct feature reference from "Expr. Solver Tester" to "Expr. Solver Editor". Users benefit **across the system**. [*albertodone*]

## Release 25.4.277.0 (PR #344) - 17/07/2025
---
### ✨ Features
#### 💰 Finance
  * Payment Terms Additional Description to invoice report and update DE translations. **Better financial control** for accounting teams. [*mpisana*]
  * Email Management features including Word Template handling and subject entries. This **improves financial workflows** and reduces errors. [*mpisana*]
#### ⚙️ System
  * IPL.Email Mgmt permissionset to include Email Subject Entry and related features. **Better system stability** and functionality. [*mpisana*]
#### 🌐 General
  * ES report translations. Users benefit **across the system**. [*mpisana*]
  * New app Document Report ES. Users benefit **across the system**. [*mpisana*]
  * Expression solver featureality and related features. Users benefit **across the system**. [*mpisana*]
#### �️ Sales
  * Sales and Shipment documents to improve item number formatting and handling of charge items + update DE Translations. **Better sales workflows** and customer tracking. [*mpisana*]

## Release 25.4.276.0 (PR #338) - 14/07/2025
---
### 🪲 Bug Fixes
#### 🌐 General
  * feature ID for Reason Code Type in feature improvement. This **improves overall functionality**. [*albertodone*]

## Release 25.4.273.0 (PR #330) - 04/07/2025
---
### ✨ Features
#### 🌐 General
  * Ship-to Mail Address featureality and related features/improvements. Users benefit **across the system**. [*albertodone*]
  * Refactor: update visibility for EU 3rd Party Trade. **Enhanced capabilities** for business operations. [*mpisana*]
  * Refactor: reorder Source Name feature for better layout consistency. This **improves overall functionality**. [*mpisana*]
  * Added source type and source no features. Users benefit **across the system**. [*mpisana*]
  * Refactor: SK > fixed featureExt to address IT localization requirements. This **improves overall functionality**. [*mpisana*]
  * Refactor: W1 > fixed featureExt to address IT localization requirements. Users benefit **across the system**. [*mpisana*]
  * Refactor: HU > fixed featureExt to address IT localization requirements. Users benefit **across the system**. [*mpisana*]
  * Refactor: ES > fixed featureExt to address IT localization requirements. This **improves overall functionality**. [*mpisana*]
  * Refactor: DE > fixed featureExt to address IT localization requirements. Users benefit **across the system**. [*mpisana*]
  * Refactor: BE > fixed featureExt to address IT localization requirements. Users benefit **across the system**. [*mpisana*]
  * Refactor: HU > corrected certain features to address IT localization requirements. **Enhanced capabilities** for business operations. [*mpisana*]
  * Refactor: SK > corrected certain features to address IT localization requirements. This **improves overall functionality**. [*mpisana*]
  * Refactor: ES > corrected certain features to address IT localization requirements. **Enhanced capabilities** for business operations. [*mpisana*]
  * Refactor: DE > corrected certain features to address IT localization requirements. Users benefit **across the system**. [*mpisana*]
  * Refactor: BE > corrected certain features to address IT localization requirements. This **improves overall functionality**. [*mpisana*]
  * Refactor: W1 > corrected certain features to address IT localization requirements. **Enhanced capabilities** for business operations. [*mpisana*]

## Release 25.4.272.0 (PR #327) - 03/07/2025
---
### 🪲 Bug Fixes
#### � Purchase
  * Correct report ID for Vendor Statement. Procurement teams can **process orders faster**. [*mpisana*]

## Release 25.4.270.0 (PR #321) - 02/07/2025
---
### 🪲 Bug Fixes
#### � Purchase
  * feature order and remove unused feature in Profile BPO detail section. **Improved vendor relationships** and order tracking. [*albertodone*]

## Release 25.4.265.0 (PR #307) - 26/06/2025
---
### 🪲 Bug Fixes
#### � Purchase
  * Vendor - Balance to Date report with configurable options. This **enhances supplier management** workflows. [*albertodone*]

## Release 25.4.263.0 (PR #304) - 26/06/2025
---
### 🔧 Other Changes
#### 🌐 General
  * [main@138d8b9] Update AL-Go System Files from microsoft/AL-Go-PTE@main - e247881. This **improves overall functionality**. [*albertodone*]

## Release 25.4.260.0 (PR #299) - 19/06/2025
---
### 🪲 Bug Fixes
#### ⚙️ System
  * Extend permission set for Email Management to include Address Book entries. Users benefit from **improved system performance**. [*albertodone*]

## Release 25.4.257.0 (PR #457) - 28/09/2025
### ✨ Features
#### 💰 Finance
  * Payment feature Code feature from Acc. General Journal feature improvement. This **improves financial workflows** and reduces errors. [*albertodone*]
  * Scheduled import featureality in Expenses management. Users can now **manage finances** more efficiently. [*mpisana*]
  * Added SEPA Ditrect Debit Mandates report. Users can now **manage finances** more efficiently. [*albertodone*]
  * Payment feature Code feature to Profile General Journal feature. **Better financial control** for accounting teams. [*mpisana*]
  * improvement for "Order No." visibility in Posted Purchase Receipt Lines feature. **Better financial control** for accounting teams. [*mpisana*]
  * Payment feature Code feature to Acc. General Journal with non-edifeature property. This **improves financial workflows** and reduces errors. [*albertodone*]
  * Email subject assignment to use GetSubjectFromWordTemplate feature. This **improves financial workflows** and reduces errors. [*mpisana*]
#### 📦 Logistic
  * Packaging Type Code feature in various detail sections with tooltip and application area. This **optimizes warehouse operations**. [*albertodone*]
  * Action to view item availability by event in Import Req. Worksheet feature. This **optimizes warehouse operations**. [*mpisana*]
  * Address columns in Warehouse Shipment report to use AddressDict for Ship-to code and address number. Users can **track shipments** more effectively. [*mpisana*]
  * Address handling in warehouse shipment report by adding Ship-to code and updating address features. This **optimizes warehouse operations**. [*mpisana*]
  * Report for updating item descriptions on open orders. This **optimizes warehouse operations**. [*albertodone*]
#### �️ Sales
  * CRM Annotation feature and related logic for handling comments in Sales Orders. This **improves customer management** processes. [*albertodone*]
  * Calculation of shipping no. series during SalesOrder creation from SalesBlanket. This **improves customer management** processes. [*albertodone*]
  * Salesperson and Responsibility Center features to CRM Account and Order features, and update related logic in API management. This **improves customer management** processes. [*albertodone*]
---
### 🪲 Bug Fixes
#### 💰 Finance
  * Report ID for Expenses Receipts Images. **Better financial control** for accounting teams. [*albertodone*]
#### 📦 Logistic
  * Vessel Status dropdown options and captions for clarity. Users can **track shipments** more effectively. [*mpisana*]

## Release 25.4.256.0 (PR #290) - 15/06/2025
---
### 🪲 Bug Fixes
#### ⚙️ System
  * Define permissions for IPL.UserMgt.Admin permission set. This **enhances system capabilities**. [*albertodone*]

## Release 25.4.251.0 (PR #279) - 10/06/2025
---
### 🪲 Bug Fixes
#### ⚙️ System
  * Permissions for Surplus Output management in IPL.TransformOrder. Users benefit from **improved system performance**. [*albertodone*]
#### �️ Sales
  * Refine competence date logic in Sales Detail management. **Better sales workflows** and customer tracking. [*albertodone*]

## Release 25.4.249.0 (PR #272) - 06/06/2025
### ✨ Features
#### 💰 Finance
  * DE add new document template. Users can now **manage finances** more efficiently. [*mpisana*]
  * Added 'Skipped' status to Expenses. Updated related logic in features, features, and reports. Updated "open expense" on header. This **improves financial workflows** and reduces errors. [*mpisana*]
#### 📦 Logistic
  * feature to delete all warehouse shipment lines before updating receipt line. **Better logistics management** and delivery tracking. [*albertodone*]
#### 🌐 General
  * Created IPL.Profile DE. Users benefit **across the system**. [*mpisana*]
  * Patching featureality for DocuFlow entries and enhance UI with new features. **Enhanced capabilities** for business operations. [*mpisana*]
---
### 🪲 Bug Fixes
#### 💰 Finance
  * Rename 'Payment feature Code' feature to 'Payment feature Code'. Users can now **manage finances** more efficiently. [*albertodone*]
#### 📦 Logistic
  * GetTransferShipmentHeader feature and update logic for Transfer Shipment Header. This **optimizes warehouse operations**. [*mpisana*]
#### 🌐 General
  * Category validation logic in ApplyOrderHeaderCategories feature. **Enhanced capabilities** for business operations. [*mpisana*]
  * Current feature on file upload triggers. **Enhanced capabilities** for business operations. [*albertodone*]
#### �️ Sales
  * Case handling for Sales Shipment Header in OnPreReport trigger. **Better sales workflows** and customer tracking. [*mpisana*]
  * Handle customer retrieval in GetCustomer feature. This **improves customer management** processes. [*albertodone*]

## Release 25.4.248.0 (PR #267) - 29/05/2025
---
### 🪲 Bug Fixes
#### ⚙️ System
  * Rename 'Verificator' to 'Verifier' in user task features and filters for consistency. **Better system stability** and functionality. [*albertodone*]

## Release 25.4.244.0 (PR #262) - 23/05/2025
---
### 🪲 Bug Fixes
#### 💰 Finance
  * Move Acc. Financial Journal into Profile.BE. **Better financial control** for accounting teams. [*albertodone*]

## Release 25.4.240.0 (PR #255) - 21/05/2025
---
### 🔧 Other Changes
#### ⚙️ System
  * Incremented Version number by +0.1. Users benefit from **improved system performance**. [*albertodone*]

## Release 25.3.236.0 (PR #251) - 16/05/2025
---
### 🔧 Other Changes
#### 🌐 General
  * [main@158f974] Update AL-Go System Files from microsoft/AL-Go-PTE@main - 14c066b. **Enhanced capabilities** for business operations. [*albertodone*]

## Release 25.3.233.0 (PR #247) - 15/05/2025
### ✨ Features
#### � Purchase
  * Navigate Exxon API feature to manage promoted actions and clean up code. This **enhances supplier management** workflows. [*mpisana*]
#### 💰 Finance
  * "Acc. Reminder List" improvement to IPL_ACCOUNTING profile. This **improves financial workflows** and reduces errors. [*mpisana*]
  * improvement for Acc. Issued Reminder List and include in IPL_ACCOUNTING profile. Users can now **manage finances** more efficiently. [*mpisana*]
#### �️ Sales
  * Gross Weight feature to Update Sales Shpt Lines feature and create Utility User Settings improvement for customer, vendor, and item management. Sales teams can **work more efficiently** with customers. [*mpisana*]
---
### 🪲 Bug Fixes
#### �️ Sales
  * Validation for Customer Price Group based on Price List Header settings. **Better sales workflows** and customer tracking. [*mpisana*]

## Release 25.3.231.0 (PR #244) - 14/05/2025
---
### ✨ Features
#### � Purchase
  * Vendor Order No. feature to PUR Blanket Purch. Orders feature. Procurement teams can **process orders faster**. [*mpisana*]
#### �️ Sales
  * OnLookup trigger for Posting No. Series in sales and purchase order improvements. Sales teams can **work more efficiently** with customers. [*mpisana*]

## Release 25.3.229.0 (PR #240) - 14/05/2025
### ✨ Features
#### 💰 Finance
  * improvement for File SEPA Payments with file name as filename. This **improves financial workflows** and reduces errors. [*albertodone*]
#### 📦 Logistic
  * features for direct shipment and receipt handling in Warehouse Management. Users can **track shipments** more effectively. [*albertodone*]
  * New BE.Base App. feat: Journal Management in Extended Combine Shipment. Users can **track shipments** more effectively. [*albertodone*]
---
### 🪲 Bug Fixes
#### 📦 Logistic
  * Comb. Shipment improvement feature with feature for Location, Categories and Posting No. Series copy from order. This **optimizes warehouse operations**. [*albertodone*]

## Release 25.3.227.0 (PR #237) - 12/05/2025
### ✨ Features
#### 📦 Logistic
  * Update Lot Info Item Entries featureality. This **optimizes warehouse operations**. [*albertodone*]
---
### 🪲 Bug Fixes
#### 📦 Logistic
  * Correct caption for Update Lot Info Item Entry feature. This **optimizes warehouse operations**. [*albertodone*]
  * Update Lot Info on Item Entry feature. This **optimizes warehouse operations**. [*albertodone*]

## Release 25.3.223.0 (PR #231) - 09/05/2025
### ✨ Features
#### 💰 Finance
  * BE Add EU 3-Party Trade Purchase system component and enhance visibility in Purchase Invoice feature improvement. This **improves financial workflows** and reduces errors. [*mpisana*]
#### 🌐 General
  * improvements for IPL_CSR_PURCH. Users benefit **across the system**. [*mpisana*]
#### �️ Sales
  * Enterprise no. to Profile Sales Ret.Order BE. **Better sales workflows** and customer tracking. [*mpisana*]
---
### 🪲 Bug Fixes
#### � Purchase
  * SK Add EU 3-Party Trade Purchase improvement and update profile improvements. Procurement teams can **process orders faster**. [*mpisana*]
  * "Pay-to Vendor No." feature from PUR Purchase Order improvement (added in featureExt). This **enhances supplier management** workflows. [*mpisana*]
#### 💰 Finance
  * EU 3-Party Trade Purchase system component and related visibility settings in Purchase Invoice improvement. Users can now **manage finances** more efficiently. [*mpisana*]
  * HU Add EU 3-Party Trade Purchase system component and enhance visibility in Purchase Invoice improvement. **Better financial control** for accounting teams. [*mpisana*]
  * Layout and visibility for IC and Invoice details in multiple features. Users can now **manage finances** more efficiently. [*mpisana*]
#### 🌐 General
  * Background color. This **improves overall functionality**. [*mpisana*]
#### �️ Sales
  * Comment out "Bill-to Name" modification and related features in CSR Sales Return Order feature improvement. **Better sales workflows** and customer tracking. [*mpisana*]
  * Reorder User Tasks Activities and add actions for Sales group in Purch. Role Center. Sales teams can **work more efficiently** with customers. [*mpisana*]

## Release 25.3.221.0 (PR #228) - 08/05/2025
---
### 🪲 Bug Fixes
#### 📦 Logistic
  * ApplicationArea to Show Qty. (Calculated) and Show Serial/Lot Number features in Phys. Inventory List report. **Better logistics management** and delivery tracking. [*albertodone*]
