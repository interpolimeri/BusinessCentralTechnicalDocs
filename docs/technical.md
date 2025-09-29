# Changelog

## Release 26.0.313.0 (PR #457) - 28/09/2025
### ✨ Features
  * Add CRM Annotation table and related logic for handling comments in Sales Orders [*albertodone*]
  * Add calculation of shipping no. series during SalesOrder creation from SalesBlanket [*albertodone*]
  * Remove Payment Method Code field from IPL Acc. General Journal page customization [*albertodone*]
  * Add Salesperson and Responsibility Center fields to CRM Account and Order tables, and update related logic in API management [*albertodone*]
  * Update Packaging Type Code field in various subforms with tooltip and application area [*albertodone*]
  * Implement scheduled import functionality in IPL Expenses management [*mpisana*]
  * Added SEPA Ditrect Debit Mandates report [*albertodone*]
  * Add Payment Method Code field to IPL Profile General Journal page [*mpisana*]
  * Add customization for "Order No." visibility in Posted Purchase Receipt Lines page [*mpisana*]
  * Add action to view item availability by event in IPL Import Req. Worksheet page [*mpisana*]
  * Update address columns in IPL Warehouse Shipment report to use AddressDict for Ship-to code and address number [*mpisana*]
  * Enhance address handling in warehouse shipment report by adding Ship-to code and updating address fields [*mpisana*]
  * Add report for updating item descriptions on open orders [*albertodone*]
  * Add Payment Method Code field to IPL Acc. General Journal with non-editable property [*albertodone*]
  * Update email subject assignment to use GetSubjectFromWordTemplate method [*mpisana*]
### 🪲 Bug Fixes
  * Update IPL Vessel Status enum values and captions for clarity [*mpisana*]
  * Update report ID for IPL Expenses Receipts Images [*albertodone*]
---

## Release 26.0.312.0 (PR #451) - 25/09/2025
### ✨ Features
  * Add handling for Sales and Purchase document type in DocuFlow copy/link/move [*albertodone*]
  * Add Print Receipts Images action to IPL Expenses Card and List pages, and implement corresponding report for receipts images [*albertodone*]
  * Add user settings functionality for IPL DocuFlow with sorting preferences and new pages [*albertodone*]
  * Refactor container handling to use Dictionary for improved efficiency [*mpisana*]
  * Add IPL ES Intrastat Management codeunit with event subscribers and field updates [*albertodone*]
  * Add IPL Item By Event action to Transfer Order Subform [*mpisana*]
  * Add drill-down functionality for Qty on SO/BSO PO/BPO [*mpisana*]
  * Hide Email fields in purchase order extensions [*mpisana*]
### 🪲 Bug Fixes
  * Add missing dependency entry for Intrastat Core in app.json [*albertodone*]
  * Update tracking filter logic and correct location code reference in item tracking lines extension [*mpisana*]
  * Make GetRecurringPurchaseLines action visible in IPL Log. Purchase Order page [*albertodone*]
  * Renamed file [*albertodone*]
  * Ensure valid remaining quantity before inserting entry in blanket purchase order processing [*albertodone*]
  * Prevent division by zero in commission amount calculation in IPL Sales Detail Mgmt [*albertodone*]
  * Update SubPageLink to use 'Blanket Order' for consistency [*mpisana*]
  * Updated 'Requested Delivery Date' [*mpisana*]
  * Update obsolete reason for Client ID field in IPL Dyn365 Integration Setup table [*albertodone*]
---

## Release 26.0.311.0 (PR #446) - 22/09/2025
### ✨ Features
  * Add key for Item Ledger Entry No. in IPL Tracking Specification extension [*albertodone*]
  * Add new key for IPL Item Ledger Entry and create IPL PBI Tracking Spec. extension [*albertodone*]
  * Enhance record retrieval logic in IPL PBI Item Ledg. Entries API [*albertodone*]
  * Add new key for Item No., Variant Code, Lot No., and Open in IPL Sell Off List Entry table [*albertodone*]
  * Add validation for CustomerId field in Dyn365APIField [*albertodone*]
  * Add Import Requisition Worksheets action to IPL Logistic Role Center [*mpisana*]
  * Enhance email management by adding customer and vendor email [*mpisana*]
  * Add Receipt Name field to IPL Warehouse Receipt List page [*mpisana*]
  * Add Excel import/export functionality to Warehouse Receipts and Shipment List pages [*mpisana*]
  * Add IPL Req. Worksheet Ext. Whse page and update permissionset [*mpisana*]
  * Refactor: remove unused user tasks and job queue entry parts; add import action to IPL Ext. Logistic Role Center [*mpisana*]
  * Add new page customizations and modify visibility settings for various pages in IPL Profile [*mpisana*]
### 🪲 Bug Fixes
  * Update vehicle mapping in Transporeon Purch. Line table relation [*mpisana*]
  * Correct indexing in Evaluate calls for ExpenseLineKey [*mpisana*]
  * Correct parameter for GetLinkedPurchOrderFilter in IPL Sales Order Serv. Info page extension [*albertodone*]
  * Correct authorization header handling in Transporeon API requests [*mpisana*]
---

## Release 26.0.310.0 (PR #441) - 18/09/2025
### ✨ Features
  * Add IPL Security Vault dependency in Transporeon API [*albertodone*]
---

## Release 26.0.309.0 (PR #440) - 18/09/2025
### ✨ Features
  * Add fields for Add. Tax Standard Text Code and Add. Tax Country Filter in IPL Packaging Taxes page [*albertodone*]
  * Refactor IPL Commission Mgt. to use temporary Reason Code records for compliance checks [*albertodone*]
  * Enhance IPL Sales Order Serv. Info to filter linked purchase orders [*albertodone*]
  * Enhance IPL Transporeon API with security vault integration and update token handling [*mpisana*]
  * Set Purch. Order No. field as non-editable in IPL Sales Order extension [*albertodone*]
  * Add IPL Order Receipt Confirmation field to Blanket Sales Order Email page [*mpisana*]
  * Add Data Security dependency and filter for approved EOS DS status in Role Center [*mpisana*]
  * Add event subscriber to set manual price as default for sales lines fix: remove redundant OnAfterValidate trigger for unit price in sales line extension [*albertodone*]
  * Add IPL Reason Code filter and related fields to commission calculations [*albertodone*]
  * Add validation for IPL Scrap Quantity on Assembly Header [*albertodone*]
  * Add IPL Inventory Reason Code functionality [*mpisana*]
  * Integrate subject retrieval from word templates in email management [*mpisana*]
### 🪲 Bug Fixes
  * Correct reference from WarehouseReceiptHeader to WarehouseShipmentHeader in IPL Packaging Management [*mpisana*]
  * Validate IPL Shipment Information on Purchase Header [*mpisana*]
  * Update tracking logic for linked purchase orders in Sales Order pages [*mpisana*]
---

## Release 26.0.308.0 (PR #434) - 12/09/2025
### ✨ Features
  * Improve ENV code retrieval logic in IPL Doc. Report ES Mgt. [*mpisana*]
  * Add support for Option field type in IPL Expr. Solver Functions [*mpisana*]
  * Make "Ship-to code" field editable in IPL Purchase Req. Worksheet [*mpisana*]
  * Add IPL Sell-to Customer No. field to Requisition Line and update related logic [*mpisana*]
  * Refactor IPL Sales Order and Sales Order List extensions to use LinkedPurchOrder variable [*mpisana*]
  * Enhance Intrastat and invoicing management by adding Reason Code fields and updating payment terms handling [*albertodone*]
  * Refactor IPL Transporeon Sales Order and Sales Orders pages to use TransportID and TransportOrderStatus variables [*mpisana*]
  * Remove unused journal template inheritance procedures for sales and purchase headers [*albertodone*]
  * Update journal template inheritance logic for sales and purchase headers [*albertodone*]
  * Enhance IPL Document Report ES with new fields and improved translations [*mpisana*]
  * Add credit memo payment terms handling [*albertodone*]
  * Update IPL Invoice Document HU word layout [*mpisana*]
  * Filter obsolete fields in IPL DB Correction Management [*albertodone*]
### 🪲 Bug Fixes
  * Updates IPL Sales Document ES and  IPL Purchase Document ES [*mpisana*]
---

## Release 26.0.307.0 (PR #430) - 08/09/2025
### ✨ Features
  * Add new codeunits and extend existing functionalities for Intrastat management [*albertodone*]
### 🪲 Bug Fixes
  * Add deletion of PullId in ProcessTransporeonOrderLog procedure [*mpisana*]
  * Update version to 26.0.0.0 and extend id range to 55999 [*mpisana*]
---

## Release 26.0.306.0 (PR #424) - 06/09/2025
### ✨ Features
  * Created new app IPL Base ES [*mpisana*]
  * Add new email templates for purchase orders, sales confirmations, and invoices in English and Spanish [*mpisana*]
  * Enhance Transporeon order handling in sales and purchase order pages [*mpisana*]
### 🪲 Bug Fixes
  * Updated Sales Order Confirmation ENU template (ES) [*mpisana*]
  * Correct grammatical error in Sales Order Confirmation DEU template [*mpisana*]
---

## Release 26.0.305.0 (PR #422) - 05/09/2025
### ✨ Features
  * Remove report permission for "IPL Update Item Desc. on Ord." [*albertodone*]
---

## Release 26.0.304.0 (PR #421) - 05/09/2025
### ✨ Features
  * Update ID ranges in app.json files across multiple modules to extend the range to 55999 [*albertodone*]
  * Add IPL Dyn365 as a dependency in app.json [*albertodone*]
  * Update shipment method code assignment logic in transport management [*albertodone*]
  * Remove IPL Update Item Description on Orders report [*albertodone*]
  * Add permissions for Return Receipt Header and Return Receipt Line [*albertodone*]
### 🔧 Other Changes
  * New Version number 26.0 [*albertodone*]
  * [adone/testalgo@556404d] Update AL-Go System Files from microsoft/AL-Go-PTE@main - 920b9e1 [*albertodone*]
---
