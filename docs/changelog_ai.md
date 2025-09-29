# AI-Enhanced Changelog

## Release 26.0.313.0 (PR #457) - 28/09/2025
### ✨ Features
  * **[Sales]:** CRM Annotation feature and related logic for handling comments in Sales Orders. Sales teams can now **work more efficiently** with customers. [*albertodone*]
  * **[Sales]:** Calculation of shipping no. series during SalesOrder creation from SalesBlanket. This **improves customer management** and sales processes. [*albertodone*]
  * **[Finance]:** Payment Method Code feature from Acc. General Journal feature improvement. Users now have **better control** over accounting workflows. [*albertodone*]
  * **[Sales]:** Salesperson and Responsibility Center features to CRM Account and Order features, and update related logic in API management. This **streamlines order processing** and customer interactions. [*albertodone*]
  * **[System]:** Packaging Type Code feature in various detail sections with tooltip and application area. Users can now **work more efficiently** with the system. [*albertodone*]
  * **[Reporting]:** Scheduled import feature in Expenses management. Users can now **generate reports** more easily. [*mpisana*]
  * **[Reporting]:** Added SEPA Ditrect Debit Mandates report. This **improves data analysis** and decision making. [*albertodone*]
  * **[Finance]:** Payment Method Code feature to Profile General Journal feature. This helps users manage **financial processes** more efficiently. [*mpisana*]
  * **[Sales]:** improvement for "Order No." visibility in Posted Purchase Receipt Lines feature. This **improves customer management** and sales processes. [*mpisana*]
  * **[Inventory]:** Action to view item availability by event in Import Req. Worksheet feature. Users can now **track inventory** more accurately. [*mpisana*]
  * **[Inventory]:** Address columns in Warehouse Shipment report to use AddressDict for Ship-to code and address number. Users can now **track inventory** more accurately. [*mpisana*]
  * **[Inventory]:** Address handling in warehouse shipment report by adding Ship-to code and updating address features. Users can now **track inventory** more accurately. [*mpisana*]
  * **[Inventory]:** Report for updating item descriptions on open orders. This **optimizes warehouse workflows** and item handling. [*albertodone*]
  * **[Finance]:** Payment Method Code feature to Acc. General Journal with non-edifeature property. Users now have **better control** over accounting workflows. [*albertodone*]
  * **[System]:** Email subject assignment to use GetSubjectFromWordTemplate method. This **enhances security** and system reliability. [*mpisana*]
### 🪲 Bug Fixes
  * **[System]:** Vessel Status dropdown options and captions for clarity. Users can now **work more efficiently** with the system. [*mpisana*]
  * **[Purchase]:** Report ID for Expenses Receipts Images. Procurement teams can now **process orders faster**. [*albertodone*]
---

## Release 26.0.312.0 (PR #451) - 25/09/2025
### ✨ Features
  * **[Sales]:** Handling for Sales and Purchase document type in DocuFlow copy/link/move. This **improves customer management** and sales processes. [*albertodone*]
  * **[Purchase]:** Print Receipts Images action to Expenses Card and List features, and implement corresponding report for receipts images. This **enhances supplier management** and purchasing workflows. [*albertodone*]
  * **[System]:** User settings feature for DocuFlow with sorting preferences and new features. Users can now **work more efficiently** with the system. [*albertodone*]
  * **[System]:** Refactor container handling to use Dictionary for improved efficiency. Users can now **work more efficiently** with the system. [*mpisana*]
  * **[System]:** ES Intrastat Management feature with event subscribers and feature updates. This **improves system performance** and user experience. [*albertodone*]
  * **[Inventory]:** Item By Event action to Transfer Order detail section. This **optimizes warehouse workflows** and item handling. [*mpisana*]
  * **[System]:** Drill-down feature for Qty on SO/BSO PO/BPO. This **improves system performance** and user experience. [*mpisana*]
  * **[Sales]:** Hide Email features in purchase order improvements. Sales teams can now **work more efficiently** with customers. [*mpisana*]
### 🪲 Bug Fixes
  * **[System]:** Missing dependency entry for Intrastat Core in app.json. This **enhances security** and system reliability. [*albertodone*]
  * **[Inventory]:** item tracking and correct location code reference in item tracking lines improvement. This **improves stock management** and warehouse operations. [*mpisana*]
  * **[Sales]:** Make GetRecurringPurchaseLines action visible in Log. Purchase Order feature. This **streamlines order processing** and customer interactions. [*albertodone*]
  * **[System]:** Renamed file. This **improves system performance** and user experience. [*albertodone*]
  * **[Inventory]:** Ensure valid remaining quantity before inserting entry in blanket purchase order processing. This **improves stock management** and warehouse operations. [*albertodone*]
  * **[Sales]:** Prevent division by zero in commission amount calculation in Sales Detail Mgmt. This **streamlines order processing** and customer interactions. [*albertodone*]
  * **[Sales]:** SubfeatureLink to use 'Blanket Order' for consistency. Sales teams can now **work more efficiently** with customers. [*mpisana*]
  * **[System]:** Updated 'Requested Delivery Date'. This **improves system performance** and user experience. [*mpisana*]
  * **[System]:** Obsolete reason for Client ID feature in Dyn365 Integration Setup feature. Users can now **work more efficiently** with the system. [*albertodone*]
---

## Release 26.0.311.0 (PR #446) - 22/09/2025
### ✨ Features
  * **[Inventory]:** Key for Item Ledger Entry No. in Tracking Specification improvement. This **optimizes warehouse workflows** and item handling. [*albertodone*]
  * **[Inventory]:** New key for Item Ledger Entry and create PBI Tracking Spec. improvement. Users can now **track inventory** more accurately. [*albertodone*]
  * **[Inventory]:** Record retrieval logic in PBI Item Ledg. Entries API. Users can now **track inventory** more accurately. [*albertodone*]
  * **[Inventory]:** New key for Item No., Variant Code, Lot No., and Open in Sell Off List Entry feature. Users can now **track inventory** more accurately. [*albertodone*]
  * **[Sales]:** Validation for CustomerId feature in Dyn365APIfeature. This **streamlines order processing** and customer interactions. [*albertodone*]
  * **[Reporting]:** Import Requisition Worksheets action to Logistic Role Center. This **improves data analysis** and decision making. [*mpisana*]
  * **[Sales]:** Email management by adding customer and vendor email. This **streamlines order processing** and customer interactions. [*mpisana*]
  * **[Inventory]:** Receipt Name feature to Warehouse Receipt List feature. Users can now **track inventory** more accurately. [*mpisana*]
  * **[Inventory]:** Excel import/export feature to Warehouse Receipts and Shipment List features. Users can now **track inventory** more accurately. [*mpisana*]
  * **[System]:** Req. Worksheet Ext. Whse feature and update permissionset. This **enhances security** and system reliability. [*mpisana*]
  * **[System]:** Refactor: remove unused user tasks and job queue entry parts; add import action to Ext. Logistic Role Center. This **improves system performance** and user experience. [*mpisana*]
  * **[System]:** New feature improvements and modify visibility settings for various features in Profile. This **enhances security** and system reliability. [*mpisana*]
### 🪲 Bug Fixes
  * **[Integration]:** Vehicle mapping in Transporeon Purch. Line feature connection. This **connects systems** for smoother data flow. [*mpisana*]
  * **[System]:** Correct indexing in Evaluate calls for ExpenseLineKey. This **enhances security** and system reliability. [*mpisana*]
  * **[Sales]:** Correct parameter for GetLinkedPurchOrderFilter in Sales Order Serv. Info feature improvement. This **streamlines order processing** and customer interactions. [*albertodone*]
  * **[Integration]:** Correct authorization header handling in Transporeon API requests. Users benefit from **automated processes** and reduced manual work. [*mpisana*]
---

## Release 26.0.310.0 (PR #441) - 18/09/2025
### ✨ Features
  * **[System]:** Security Vault dependency in Transporeon API. Users can now **work more efficiently** with the system. [*albertodone*]
---

## Release 26.0.309.0 (PR #440) - 18/09/2025
### ✨ Features
  * **[System]:** features for Add. Tax Standard Text Code and Add. Tax Country Filter in Packaging Taxes feature. Users can now **work more efficiently** with the system. [*albertodone*]
  * **[System]:** Refactor Commission Mgt. to use temporary Reason Code records for compliance checks. This **enhances security** and system reliability. [*albertodone*]
  * **[Sales]:** Sales Order Serv. Info to filter linked purchase orders. Sales teams can now **work more efficiently** with customers. [*albertodone*]
  * **[System]:** Transporeon API with security vault integration and update token handling. This **enhances security** and system reliability. [*mpisana*]
  * **[Sales]:** Set Purch. Order No. feature as non-edifeature in Sales Order improvement. This **improves customer management** and sales processes. [*albertodone*]
  * **[Sales]:** Order Receipt Confirmation feature to Blanket Sales Order Email feature. This **improves customer management** and sales processes. [*mpisana*]
  * **[System]:** Data Security dependency and filter for approved EOS DS status in Role Center. Users can now **work more efficiently** with the system. [*mpisana*]
  * **[Sales]:** Event subscriber to set manual price as default for sales lines fix: remove redundant OnAfterValidate trigger for unit price in sales line improvement. Sales teams can now **work more efficiently** with customers. [*albertodone*]
  * **[System]:** Reason Code filter and related features to commission calculations. This **improves system performance** and user experience. [*albertodone*]
  * **[Inventory]:** Validation for Scrap Quantity on Assembly Header. This **improves stock management** and warehouse operations. [*albertodone*]
  * **[Inventory]:** Inventory Reason Code feature. This **optimizes warehouse workflows** and item handling. [*mpisana*]
  * **[System]:** Integrate subject retrieval from word templates in email management. Users can now **work more efficiently** with the system. [*mpisana*]
### 🪲 Bug Fixes
  * **[System]:** Correct reference from WarehouseReceiptHeader to WarehouseShipmentHeader in Packaging Management. Users can now **work more efficiently** with the system. [*mpisana*]
  * **[Inventory]:** Validate Shipment Information on Purchase Header. This **improves stock management** and warehouse operations. [*mpisana*]
  * **[Sales]:** Tracking logic for linked purchase orders in Sales Order features. Sales teams can now **work more efficiently** with customers. [*mpisana*]
---

## Release 26.0.308.0 (PR #434) - 12/09/2025
### ✨ Features
  * **[Reporting]:** ENV code retrieval logic in Doc. Report ES Mgt.. Users can now **generate reports** more easily. [*mpisana*]
  * **[System]:** Support for Option feature type in Expr. Solver Functions. This **improves system performance** and user experience. [*mpisana*]
  * **[Purchase]:** Make "Ship-to code" feature edifeature in Purchase Req. Worksheet. This **improves vendor relationships** and order tracking. [*mpisana*]
  * **[Sales]:** Sell-to Customer No. feature to Requisition Line and update related logic. Sales teams can now **work more efficiently** with customers. [*mpisana*]
  * **[Sales]:** Refactor Sales Order and Sales Order List improvements to use LinkedPurchOrder variable. This **streamlines order processing** and customer interactions. [*mpisana*]
  * **[Finance]:** Intrastat and invoicing management by adding Reason Code features and updating payment terms handling. This helps users manage **financial processes** more efficiently. [*albertodone*]
  * **[Sales]:** Refactor Transporeon Sales Order and Sales Orders features to use TransportID and TransportOrderStatus variables. Sales teams can now **work more efficiently** with customers. [*mpisana*]
  * **[Sales]:** Unused journal template inheritance procedures for sales and purchase headers. This **streamlines order processing** and customer interactions. [*albertodone*]
  * **[Sales]:** Journal template inheritance logic for sales and purchase headers. This **improves customer management** and sales processes. [*albertodone*]
  * **[Reporting]:** Document Report ES with new features and improved translations. Users can now **generate reports** more easily. [*mpisana*]
  * **[Finance]:** Credit memo payment terms handling. This helps users manage **financial processes** more efficiently. [*albertodone*]
  * **[Finance]:** Invoice Document HU word layout. Users now have **better control** over accounting workflows. [*mpisana*]
  * **[System]:** Filter obsolete features in DB Correction Management. Users can now **work more efficiently** with the system. [*albertodone*]
### 🪲 Bug Fixes
  * **[Sales]:** Updates Sales Document ES and  Purchase Document ES. Sales teams can now **work more efficiently** with customers. [*mpisana*]
---

## Release 26.0.307.0 (PR #430) - 08/09/2025
### ✨ Features
  * **[System]:** New features and extend existing functionalities for Intrastat management. Users can now **work more efficiently** with the system. [*albertodone*]
### 🪲 Bug Fixes
  * **[Sales]:** Deletion of PullId in ProcessTransporeonOrderLog procedure. This **streamlines order processing** and customer interactions. [*mpisana*]
  * **[System]:** Version to 26.0.0.0 and extend id range to 55999. Users can now **work more efficiently** with the system. [*mpisana*]
---

## Release 26.0.306.0 (PR #424) - 06/09/2025
### ✨ Features
  * **[System]:** Created new app Base ES. This **improves system performance** and user experience. [*mpisana*]
  * **[Sales]:** New email templates for purchase orders, sales confirmations, and invoices in English and Spanish. This **improves customer management** and sales processes. [*mpisana*]
  * **[Sales]:** Transporeon order handling in sales and purchase order features. This **streamlines order processing** and customer interactions. [*mpisana*]
### 🪲 Bug Fixes
  * **[Sales]:** Updated Sales Order Confirmation ENU template (ES). Sales teams can now **work more efficiently** with customers. [*mpisana*]
  * **[Sales]:** Correct grammatical error in Sales Order Confirmation DEU template. Sales teams can now **work more efficiently** with customers. [*mpisana*]
---

## Release 26.0.305.0 (PR #422) - 05/09/2025
### ✨ Features
  * **[System]:** Report permission for "Update Item Desc. on Ord.". This **improves system performance** and user experience. [*albertodone*]
---

## Release 26.0.304.0 (PR #421) - 05/09/2025
### ✨ Features
  * **[System]:** ID ranges in app.json files across multiple modules to extend the range to 55999. This **enhances security** and system reliability. [*albertodone*]
  * **[System]:** Dyn365 as a dependency in app.json. This **enhances security** and system reliability. [*albertodone*]
  * **[Inventory]:** Shipment method code assignment logic in transport management. Users can now **track inventory** more accurately. [*albertodone*]
  * **[Inventory]:** Update Item Description on Orders report. Users can now **track inventory** more accurately. [*albertodone*]
  * **[System]:** Permissions for Return Receipt Header and Return Receipt Line. This **improves system performance** and user experience. [*albertodone*]
### 🔧 Other Changes
  * **[System]:** New Version number 26.0. This **enhances security** and system reliability. [*albertodone*]
  * **[System]:** [adone/testalgo@556404d] Update AL-Go System Files from microsoft/AL-Go-PTE@main - 920b9e1. This **improves system performance** and user experience. [*albertodone*]
---
