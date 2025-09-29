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

## Release 25.4.302.0 (PR #457) - 28/09/2025
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

## Release 25.4.301.0 (PR #415) - 04/09/2025
### ✨ Features
  * Expand permissions for IPL Transporeon API and Tracking Management [*albertodone*]
---

## Release 25.4.298.0 (PR #407) - 29/08/2025
### ✨ Features
  * Update IPL Purch. Doc. Summary Buffer and related codeunit for Sales Order linking and pricing [*mpisana*]
  * Add IPL Calc. Availability Management codeunit with event subscribers for item availability filtering [*mpisana*]
  * Enable delayed insert for IPL Cust. Alternative Payments page and enforce NotBlank for Item Category Code [*mpisana*]
### 🪲 Bug Fixes
  * Exclude Shipment Method Code assignment in SSO Purchase Header [*albertodone*]
  * Update calculation method for Sales Detail unit cost [*albertodone*]
  * Correct spelling in app name for IPL Credit Mixer Interface [*albertodone*]
  * Correct spelling in procedure names for Sales Header VAT category updates [*albertodone*]
---

## Release 25.4.297.0 (PR #402) - 26/08/2025
### ✨ Features
  * Add IPL Base dependency to app.json [*albertodone*]
---

## Release 25.4.294.0 (PR #395) - 24/08/2025
### ✨ Features
  * Update DependenciesGraphALL.gv to refine relationships and add new nodes [*mpisana*]
  * Add Shipment Method Code field to IPL Sales Open Price Closing page [*mpisana*]
  * Moved shipping section after sales lines [*mpisana*]
---

## Release 25.4.293.0 (PR #393) - 18/08/2025
### ✨ Features
  * Updated DE translations [*mpisana*]
  * Add IPL Acc. Customer List customization and include in IPL_ACCOUNTING profile [*mpisana*]
---

## Release 25.4.292.0 (PR #391) - 08/08/2025
### ✨ Features
  * Add Message Center on Posted Return Shipment and Posted Return Shipments [*albertodone*]
  * Add functionality to download selected documents as a single PDF across various document types [*albertodone*]
  * Add IPL Amount per Ton (LCY) field and update calculations in commission entries [*albertodone*]
  * Add event subscriber to update payment reference on vendor invoice number change [*albertodone*]
  * Enhance user task actions to support bulk marking as read/unread with confirmation prompts [*albertodone*]
  * Add action to force update purchase order with Transporeon data in IPL Transporeon Purch. Order page. Propagation of SuspendStatusCheck on Line Disc. % validation [*albertodone*]
### 🪲 Bug Fixes
  * Review commission calculations [*albertodone*]
  * Update report caption to include 'IPL' for clarity [*albertodone*]
### 🔧 Other Changes
  * Move PropagateSuspendStatusCheck event subscriber to the end of the procedure for better organization [*albertodone*]
---

## Release 25.4.291.0 (PR #387) - 05/08/2025
### ✨ Features
  * Add functionality to disable purchase and sales defaults from posting groups [*albertodone*]
  * Add navigation action and posting date field to IPL Email with Missing CoA pages [*albertodone*]
  * Enhance posting actions with new preview functionality in IPL Financial Journal [*albertodone*]
  * Replaced actions for posting and added action for preview posting in IPL Financial Journal extension [*albertodone*]
  * Update DependencyGraph with new relationships and remove obsolete ones [*mpisana*]
  * Add "Item By Event" action to IPL Role Center and Sales Role Center pages [*mpisana*]
---

## Release 25.4.290.0 (PR #382) - 04/08/2025
### ✨ Features
  * Add reports for Financial Ledger and General Ledger to IPLBaseDE permissionset [*albertodone*]
  * Add default assignment for VAT and Gen. Business Posting Groups in Purchase Header [*albertodone*]
  * Reorganize VAT Info group and fields in Purchase Return Order page extension [*mpisana*]
  * Implement General Ledger report [*albertodone*]
  * Add Unit Price field to IPL PUR Sales Lines page customization [*mpisana*]
  * Add OnRun trigger to schedule Costing Period calculation [*albertodone*]
  * Enhance user task management with "Task to Read" functionality [*albertodone*]
  * Add IPL Handling Unit Type Code field to IPL Packaging Types page [*mpisana*]
### 🪲 Bug Fixes
  * Rename task count procedures and fields for consistency [*albertodone*]
  * Update VATDateCaption to DateCaption in report layout [*albertodone*]
  * Remove redundant GLSetup record declaration in GetCurrencyCode procedure [*albertodone*]
  * Remove redundant variable declaration in GetCurrencyCode procedure [*albertodone*]
  * Correct parameter usage in OnSetUpNewLineOnBeforeIncrDocNoHandler procedure [*albertodone*]
  * Add integration setup retrieval in order creation process [*albertodone*]
  * Ensure correct language setting when applying saved views in cue management [*mpisana*]
  * Update report extension ID for IPL Suggest Worksheet Lines [*albertodone*]
---

## Release 25.4.289.0 (PR #375) - 29/07/2025
### ✨ Features
  * Refactor authentication logic in IPL DocuFlow ArxNext Mgt. codeunit [*albertodone*]
---

## Release 25.4.287.0 (PR #370) - 28/07/2025
### ✨ Features
  * Add Start Date field and enhance Azure Key Vault secret handling [*albertodone*]
### 🪲 Bug Fixes
  * Remove unused namespaces in Base.DE [*albertodone*]
  * Remove unused IPLSecurityVaultDataScopeType enum file [*albertodone*]
---

## Release 25.4.281.0 (PR #354) - 21/07/2025
### 🪲 Bug Fixes
  * Simplify condition for EOS Type check in IPL Sales Document report [*mpisana*]
  * Set Subject field as non-editable [*mpisana*]
  * Ensure "Word Template Code" field is not blank [*mpisana*]
  * Add "Your Reference" field to IPL Profile Purch. Ret. Order page extension [*mpisana*]
---

## Release 25.4.280.0 (PR #351) - 21/07/2025
### 🪲 Bug Fixes
  * Correct page reference from "IPL Expr. Solver Tester" to "IPL Expr. Solver Editor" [*albertodone*]
---

## Release 25.4.277.0 (PR #344) - 17/07/2025
### ✨ Features
  * Add ES report translations [*mpisana*]
  * Add new app IPL Document Report ES [*mpisana*]
  * Add IPL Payment Terms Additional Description to invoice report and update DE translations [*mpisana*]
  * Update IPL Sales and Shipment documents to improve item number formatting and handling of charge items + update DE Translations [*mpisana*]
  * Update IPL.Email Mgmt permissionset to include Email Subject Entry and related pages [*mpisana*]
  * Implement IPL Email Management features including Word Template handling and subject entries [*mpisana*]
  * Add IPL expression solver functionality and related pages [*mpisana*]
---

## Release 25.4.276.0 (PR #338) - 14/07/2025
### 🪲 Bug Fixes
  * Update field ID for IPL Reason Code Type in table extension [*albertodone*]
---

## Release 25.4.273.0 (PR #330) - 04/07/2025
### ✨ Features
  * Add Ship-to Mail Address functionality and related pages/extensions [*albertodone*]
  * Refactor: update visibility for EU 3rd Party Trade [*mpisana*]
  * Refactor: reorder IPL Source Name field for better layout consistency [*mpisana*]
  * Added source type and source no fields [*mpisana*]
  * Refactor: SK > fixed pageExt to address IT localization requirements [*mpisana*]
  * Refactor: W1 > fixed pageExt to address IT localization requirements [*mpisana*]
  * Refactor: HU > fixed pageExt to address IT localization requirements [*mpisana*]
  * Refactor: ES > fixed pageExt to address IT localization requirements [*mpisana*]
  * Refactor: DE > fixed pageExt to address IT localization requirements [*mpisana*]
  * Refactor: BE > fixed pageExt to address IT localization requirements [*mpisana*]
  * Refactor: HU > corrected certain fields to address IT localization requirements [*mpisana*]
  * Refactor: SK > corrected certain fields to address IT localization requirements [*mpisana*]
  * Refactor: ES > corrected certain fields to address IT localization requirements [*mpisana*]
  * Refactor: DE > corrected certain fields to address IT localization requirements [*mpisana*]
  * Refactor: BE > corrected certain fields to address IT localization requirements [*mpisana*]
  * Refactor: W1 > corrected certain fields to address IT localization requirements [*mpisana*]
---

## Release 25.4.272.0 (PR #327) - 03/07/2025
### 🪲 Bug Fixes
  * Correct report ID for IPL Vendor Statement [*mpisana*]
---

## Release 25.4.270.0 (PR #321) - 02/07/2025
### 🪲 Bug Fixes
  * Update field order and remove unused field in IPL Profile BPO Subform [*albertodone*]
---

## Release 25.4.265.0 (PR #307) - 26/06/2025
### 🪲 Bug Fixes
  * Add IPL Vendor - Balance to Date report with configurable options [*albertodone*]
---

## Release 25.4.263.0 (PR #304) - 26/06/2025
### 🔧 Other Changes
  * [main@138d8b9] Update AL-Go System Files from microsoft/AL-Go-PTE@main - e247881 [*albertodone*]
---

## Release 25.4.260.0 (PR #299) - 19/06/2025
### 🪲 Bug Fixes
  * Extend permission set for IPL Email Management to include Address Book entries [*albertodone*]
---

## Release 25.4.257.0 (PR #457) - 28/09/2025
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

## Release 25.4.256.0 (PR #290) - 15/06/2025
### 🪲 Bug Fixes
  * Define permissions for IPL.UserMgt.Admin permission set [*albertodone*]
---

## Release 25.4.251.0 (PR #279) - 10/06/2025
### 🪲 Bug Fixes
  * Refine competence date logic in Sales Detail management [*albertodone*]
  * Add permissions for Surplus Output management in IPL.TransformOrder [*albertodone*]
---

## Release 25.4.249.0 (PR #272) - 06/06/2025
### ✨ Features
  * DE add new document template [*mpisana*]
  * Created IPL.Profile DE [*mpisana*]
  * Add patching functionality for DocuFlow entries and enhance UI with new fields [*mpisana*]
  * Added 'Skipped' status to IPL Expenses. Updated related logic in tables, pages, and reports. Updated "open expense" on header [*mpisana*]
  * Add event subscriber to delete all warehouse shipment lines before updating receipt line [*albertodone*]
### 🪲 Bug Fixes
  * Enhance category validation logic in ApplyOrderHeaderCategories procedure [*mpisana*]
  * Add case handling for Sales Shipment Header in OnPreReport trigger [*mpisana*]
  * Add GetTransferShipmentHeader procedure and update logic for Transfer Shipment Header [*mpisana*]
  * Handle customer retrieval in GetCustomer procedure [*albertodone*]
  * Update current page on file upload triggers [*albertodone*]
  * Rename 'Payment Method Code' field to 'IPL Payment Method Code' [*albertodone*]
---

## Release 25.4.248.0 (PR #267) - 29/05/2025
### 🪲 Bug Fixes
  * Rename 'Verificator' to 'Verifier' in user task fields and filters for consistency [*albertodone*]
---

## Release 25.4.244.0 (PR #262) - 23/05/2025
### 🪲 Bug Fixes
  * Move IPL Acc. Financial Journal into Profile.BE [*albertodone*]
---

## Release 25.4.240.0 (PR #255) - 21/05/2025
### 🔧 Other Changes
  * Incremented Version number by +0.1 [*albertodone*]
---

## Release 25.3.236.0 (PR #251) - 16/05/2025
### 🔧 Other Changes
  * [main@158f974] Update AL-Go System Files from microsoft/AL-Go-PTE@main - 14c066b [*albertodone*]
---

## Release 25.3.233.0 (PR #247) - 15/05/2025
### ✨ Features
  * Add Gross Weight field to IPL Update Sales Shpt Lines page and create IPL Utility User Settings extension for customer, vendor, and item management [*mpisana*]
  * Update IPL Navigate Exxon API page to manage promoted actions and clean up code [*mpisana*]
  * Add "IPL Acc. Reminder List" customization to IPL_ACCOUNTING profile [*mpisana*]
  * Add customization for IPL Acc. Issued Reminder List and include in IPL_ACCOUNTING profile [*mpisana*]
### 🪲 Bug Fixes
  * Add validation for Customer Price Group based on Price List Header settings [*mpisana*]
---

## Release 25.3.231.0 (PR #244) - 14/05/2025
### ✨ Features
  * Add Vendor Order No. field to IPL PUR Blanket Purch. Orders page [*mpisana*]
  * Add OnLookup trigger for Posting No. Series in sales and purchase order extensions [*mpisana*]
---

## Release 25.3.229.0 (PR #240) - 14/05/2025
### ✨ Features
  * Add extension for IPL File SEPA Payments with file name as filename [*albertodone*]
  * Add event subscribers for direct shipment and receipt handling in IPL Warehouse Management [*albertodone*]
  * New BE.Base App. feat: Journal Management in Extended Combine Shipment [*albertodone*]
### 🪲 Bug Fixes
  * Add IPL Comb. Shipment Extension codeunit with event subscriber for Location, Categories and Posting No. Series copy from order [*albertodone*]
---

## Release 25.3.227.0 (PR #237) - 12/05/2025
### ✨ Features
  * Add IPL Update Lot Info Item Entries functionality [*albertodone*]
### 🪲 Bug Fixes
  * Correct caption for IPL Update Lot Info Item Entry page [*albertodone*]
  * Remove IPL Update Lot Info on Item Entry page [*albertodone*]
---

## Release 25.3.223.0 (PR #231) - 09/05/2025
### ✨ Features
  * BE Add EU 3-Party Trade Purchase dependency and enhance visibility in Purchase Invoice page extension [*mpisana*]
  * Add customizations for IPL_CSR_PURCH [*mpisana*]
  * Add enterprise no. to IPL Profile Sales Ret.Order BE [*mpisana*]
### 🪲 Bug Fixes
  * Remove EU 3-Party Trade Purchase dependency and related visibility settings in Purchase Invoice customization [*mpisana*]
  * HU Add EU 3-Party Trade Purchase dependency and enhance visibility in Purchase Invoice customization [*mpisana*]
  * SK Add EU 3-Party Trade Purchase customization and update profile extensions [*mpisana*]
  * Remove "Pay-to Vendor No." field from IPL PUR Purchase Order customization (added in pageExt) [*mpisana*]
  * Comment out "Bill-to Name" modification and related fields in IPL CSR Sales Return Order page customization [*mpisana*]
  * Enhance layout and visibility for IC and Invoice details in multiple pages [*mpisana*]
  * Reorder User Tasks Activities and add actions for Sales group in Purch. Role Center [*mpisana*]
  * Add background color [*mpisana*]
---

## Release 25.3.221.0 (PR #228) - 08/05/2025
### 🪲 Bug Fixes
  * Add ApplicationArea to Show Qty. (Calculated) and Show Serial/Lot Number fields in IPL Phys. Inventory List report [*albertodone*]
---
