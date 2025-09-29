# AI-Enhanced Changelog

## Release 26.0.313.0 (PR #457) - 28/09/2025
### ✨ Features
  * Added CRM Annotation table and related logic for handling comments in Sales Orders (Enhanced offline) [*albertodone*]
  * Added calculation of shipping no. series during SalesOrder creation from SalesBlanket (Enhanced offline) [*albertodone*]
  * Remove Payment Method Code field from Acc. General Journal page customization (Enhanced offline) [*albertodone*]
  * Added Salesperson and Responsibility Center fields to CRM Account and Order tables, and Updated related logic in API management (Enhanced offline) [*albertodone*]
  * Updated Packaging Type Code field in various subforms with tooltip and application area (Enhanced offline) [*albertodone*]
  * Implement scheduled import functionality in Expenses management (Enhanced offline) [*mpisana*]
  * Added SEPA Ditrect Debit Mandates report (Enhanced offline) [*albertodone*]
  * Added Payment Method Code field to Profile General Journal page (Enhanced offline) [*mpisana*]
  * Added customization for "Order No." visibility in Posted Purchase Receipt Lines page (Enhanced offline) [*mpisana*]
  * Added action to view item availability by event in Import Req. Worksheet page (Enhanced offline) [*mpisana*]
  * Updated address columns in Warehouse Shipment report to use AddressDict for Ship-to code and address number (Enhanced offline) [*mpisana*]
  * Enhance address handling in warehouse shipment report by adding Ship-to code and updating address fields (Enhanced offline) [*mpisana*]
  * Added report for updating item descriptions on open orders (Enhanced offline) [*albertodone*]
  * Added Payment Method Code field to Acc. General Journal with non-editable property (Enhanced offline) [*albertodone*]
  * Updated email subject assignment to use GetSubjectFromWordTemplate method (Enhanced offline) [*mpisana*]
### 🪲 Bug Fixes
  * Updated Vessel Status enum values and captions for clarity (Enhanced offline) [*mpisana*]
  * Updated report ID for Expenses Receipts Images (Enhanced offline) [*albertodone*]
---

## Release 26.0.312.0 (PR #451) - 25/09/2025
### ✨ Features
  * Added handling for Sales and Purchase document type in DocuFlow copy/link/move (Enhanced offline) [*albertodone*]
  * Added Print Receipts Images action to Expenses Card and List pages, and implement corresponding report for receipts images (Enhanced offline) [*albertodone*]
  * Added user settings functionality for DocuFlow with sorting preferences and new pages (Enhanced offline) [*albertodone*]
  * Refactor container handling to use Dictionary for improved efficiency (Enhanced offline) [*mpisana*]
  * Added ES Intrastat Management codeunit with event subscribers and field updates (Enhanced offline) [*albertodone*]
  * Added Item By Event action to Transfer Order Subform (Enhanced offline) [*mpisana*]
  * Added drill-down functionality for Qty on SO/BSO PO/BPO (Enhanced offline) [*mpisana*]
  * Hide Email fields in purchase order extensions (Enhanced offline) [*mpisana*]
### 🪲 Bug Fixes
  * Added missing dependency entry for Intrastat Core in app.json (Enhanced offline) [*albertodone*]
  * Updated tracking filter logic and correct location code reference in item tracking lines extension (Enhanced offline) [*mpisana*]
  * Make GetRecurringPurchaseLines action visible in Log. Purchase Order page (Enhanced offline) [*albertodone*]
  * Renamed file (Enhanced offline) [*albertodone*]
  * Ensure valid remaining quantity before inserting entry in blanket purchase order processing (Enhanced offline) [*albertodone*]
  * Prevent division by zero in commission amount calculation in Sales Detail Mgmt (Enhanced offline) [*albertodone*]
  * Updated SubPageLink to use 'Blanket Order' for consistency (Enhanced offline) [*mpisana*]
  * Updated 'Requested Delivery Date' (Enhanced offline) [*mpisana*]
  * Updated obsolete reason for Client ID field in Dyn365 Integration Setup table (Enhanced offline) [*albertodone*]
---

## Release 26.0.311.0 (PR #446) - 22/09/2025
### ✨ Features
  * Added key for Item Ledger Entry No. in Tracking Specification extension (Enhanced offline) [*albertodone*]
  * Added new key for Item Ledger Entry and create PBI Tracking Spec. extension (Enhanced offline) [*albertodone*]
  * Enhance record retrieval logic in PBI Item Ledg. Entries API (Enhanced offline) [*albertodone*]
  * Added new key for Item No., Variant Code, Lot No., and Open in Sell Off List Entry table (Enhanced offline) [*albertodone*]
  * Added validation for CustomerId field in Dyn365APIField (Enhanced offline) [*albertodone*]
  * Added Import Requisition Worksheets action to Logistic Role Center (Enhanced offline) [*mpisana*]
  * Enhance email management by adding customer and vendor email (Enhanced offline) [*mpisana*]
  * Added Receipt Name field to Warehouse Receipt List page (Enhanced offline) [*mpisana*]
  * Added Excel import/export functionality to Warehouse Receipts and Shipment List pages (Enhanced offline) [*mpisana*]
  * Added Req. Worksheet Ext. Whse page and Updated permissionset (Enhanced offline) [*mpisana*]
  * Refactor: remove unused user tasks and job queue entry parts; Added import action to Ext. Logistic Role Center (Enhanced offline) [*mpisana*]
  * Added new page customizations and modify visibility settings for various pages in Profile (Enhanced offline) [*mpisana*]
### 🪲 Bug Fixes
  * Updated vehicle mapping in Transporeon Purch. Line table relation (Enhanced offline) [*mpisana*]
  * Correct indexing in Evaluate calls for ExpenseLineKey (Enhanced offline) [*mpisana*]
  * Correct parameter for GetLinkedPurchOrderFilter in Sales Order Serv. Info page extension (Enhanced offline) [*albertodone*]
  * Correct authorization header handling in Transporeon API requests (Enhanced offline) [*mpisana*]
---

## Release 26.0.310.0 (PR #441) - 18/09/2025
### ✨ Features
  * Added Security Vault dependency in Transporeon API (Enhanced offline) [*albertodone*]
---

## Release 26.0.309.0 (PR #440) - 18/09/2025
### ✨ Features
  * Added fields for Add. Tax Standard Text Code and Add. Tax Country Filter in Packaging Taxes page (Enhanced offline) [*albertodone*]
  * Refactor Commission Mgt. to use temporary Reason Code records for compliance checks (Enhanced offline) [*albertodone*]
  * Enhance Sales Order Serv. Info to filter linked purchase orders (Enhanced offline) [*albertodone*]
  * Enhance Transporeon API with security vault integration and Updated token handling (Enhanced offline) [*mpisana*]
  * Set Purch. Order No. field as non-editable in Sales Order extension (Enhanced offline) [*albertodone*]
  * Added Order Receipt Confirmation field to Blanket Sales Order Email page (Enhanced offline) [*mpisana*]
  * Added Data Security dependency and filter for approved EOS DS status in Role Center (Enhanced offline) [*mpisana*]
  * Added event subscriber to set manual price as default for sales lines fix: remove redundant OnAfterValidate trigger for unit price in sales line extension (Enhanced offline) [*albertodone*]
  * Added Reason Code filter and related fields to commission calculations (Enhanced offline) [*albertodone*]
  * Added validation for Scrap Quantity on Assembly Header (Enhanced offline) [*albertodone*]
  * Added Inventory Reason Code functionality (Enhanced offline) [*mpisana*]
  * Integrate subject retrieval from word templates in email management (Enhanced offline) [*mpisana*]
### 🪲 Bug Fixes
  * Correct reference from WarehouseReceiptHeader to WarehouseShipmentHeader in Packaging Management (Enhanced offline) [*mpisana*]
  * Validate Shipment Information on Purchase Header (Enhanced offline) [*mpisana*]
  * Updated tracking logic for linked purchase orders in Sales Order pages (Enhanced offline) [*mpisana*]
---

## Release 26.0.308.0 (PR #434) - 12/09/2025
### ✨ Features
  * Improve ENV code retrieval logic in Doc. Report ES Mgt. (Enhanced offline) [*mpisana*]
  * Added support for Option field type in Expr. Solver Functions (Enhanced offline) [*mpisana*]
  * Make "Ship-to code" field editable in Purchase Req. Worksheet (Enhanced offline) [*mpisana*]
  * Added Sell-to Customer No. field to Requisition Line and Updated related logic (Enhanced offline) [*mpisana*]
  * Refactor Sales Order and Sales Order List extensions to use LinkedPurchOrder variable (Enhanced offline) [*mpisana*]
  * Enhance Intrastat and invoicing management by adding Reason Code fields and updating payment terms handling (Enhanced offline) [*albertodone*]
  * Refactor Transporeon Sales Order and Sales Orders pages to use TransportID and TransportOrderStatus variables (Enhanced offline) [*mpisana*]
  * Remove unused journal template inheritance procedures for sales and purchase headers (Enhanced offline) [*albertodone*]
  * Updated journal template inheritance logic for sales and purchase headers (Enhanced offline) [*albertodone*]
  * Enhance Document Report ES with new fields and improved translations (Enhanced offline) [*mpisana*]
  * Added credit memo payment terms handling (Enhanced offline) [*albertodone*]
  * Updated Invoice Document HU word layout (Enhanced offline) [*mpisana*]
  * Filter obsolete fields in DB Correction Management (Enhanced offline) [*albertodone*]
### 🪲 Bug Fixes
  * Updates Sales Document ES and  Purchase Document ES (Enhanced offline) [*mpisana*]
---

## Release 26.0.307.0 (PR #430) - 08/09/2025
### ✨ Features
  * Added new codeunits and extend existing functionalities for Intrastat management (Enhanced offline) [*albertodone*]
### 🪲 Bug Fixes
  * Added deletion of PullId in ProcessTransporeonOrderLog procedure (Enhanced offline) [*mpisana*]
  * Updated version to 26.0.0.0 and extend id range to 55999 (Enhanced offline) [*mpisana*]
---

## Release 26.0.306.0 (PR #424) - 06/09/2025
### ✨ Features
  * Created new app Base ES (Enhanced offline) [*mpisana*]
  * Added new email templates for purchase orders, sales confirmations, and invoices in English and Spanish (Enhanced offline) [*mpisana*]
  * Enhance Transporeon order handling in sales and purchase order pages (Enhanced offline) [*mpisana*]
### 🪲 Bug Fixes
  * Updated Sales Order Confirmation ENU template (ES) (Enhanced offline) [*mpisana*]
  * Correct grammatical error in Sales Order Confirmation DEU template (Enhanced offline) [*mpisana*]
---

## Release 26.0.305.0 (PR #422) - 05/09/2025
### ✨ Features
  * Remove report permission for "Updated Item Desc. on Ord." (Enhanced offline) [*albertodone*]
---

## Release 26.0.304.0 (PR #421) - 05/09/2025
### ✨ Features
  * Updated ID ranges in app.json files across multiple modules to extend the range to 55999 (Enhanced offline) [*albertodone*]
  * Added Dyn365 as a dependency in app.json (Enhanced offline) [*albertodone*]
  * Updated shipment method code assignment logic in transport management (Enhanced offline) [*albertodone*]
  * Remove Updated Item Description on Orders report (Enhanced offline) [*albertodone*]
  * Added permissions for Return Receipt Header and Return Receipt Line (Enhanced offline) [*albertodone*]
### 🔧 Other Changes
  * New Version number 26.0 (Enhanced offline) [*albertodone*]
  * [adone/testalgo@556404d] Updated AL-Go System Files from microsoft/AL-Go-PTE@main - 920b9e1 (Enhanced offline) [*albertodone*]
---
