# AI-Enhanced Changelog

## Release 26.0.313.0 (PR #457) - 28/09/2025
### ✨ Features
  * Feat: add CRM Annotation table and related logic for handling comments in Sales Orders [*albertodone*]
  * Feat: add calculation of shipping no. series during SalesOrder creation from SalesBlanket [*albertodone*]
  * Feat: remove Payment Method Code field from IPL Acc. General Journal page customization [*albertodone*]
  * Feat: add Salesperson and Responsibility Center fields to CRM Account and Order tables, and update related logic in API management [*albertodone*]
  * Feat: update Packaging Type Code field in various subforms with tooltip and application area [*albertodone*]
  * Feat: implement scheduled import functionality in IPL Expenses management [*mpisana*]
  * Feat: Added SEPA Ditrect Debit Mandates report [*albertodone*]
  * Feat: add Payment Method Code field to IPL Profile General Journal page [*mpisana*]
  * Feat: add customization for "Order No." visibility in Posted Purchase Receipt Lines page [*mpisana*]
  * Feat: add action to view item availability by event in IPL Import Req. Worksheet page [*mpisana*]
  * Feat: update address columns in IPL Warehouse Shipment report to use AddressDict for Ship-to code and address number [*mpisana*]
  * Feat: enhance address handling in warehouse shipment report by adding Ship-to code and updating address fields [*mpisana*]
  * Feat: add report for updating item descriptions on open orders [*albertodone*]
  * Feat: add Payment Method Code field to IPL Acc. General Journal with non-editable property [*albertodone*]
  * Feat: update email subject assignment to use GetSubjectFromWordTemplate method [*mpisana*]
### 🪲 Bug Fixes
  * Fix: update IPL Vessel Status enum values and captions for clarity [*mpisana*]
  * Fix: update report ID for IPL Expenses Receipts Images [*albertodone*]
### 🔧 Other Changes
  * Merge pull request #456 from interpolimeri/adone/dev [*albertodone*]
  * Merge pull request #454 from interpolimeri/adone/dev [*albertodone*]
  * Merge pull request #453 from interpolimeri/mpisana/dev [*albertodone*]
  * Merge pull request #452 from interpolimeri/adone/dev [*albertodone*]
---

## Release 26.0.312.0 (PR #451) - 25/09/2025
### ✨ Features
  * Feat: add handling for Sales and Purchase document type in DocuFlow copy/link/move [*albertodone*]
  * Feat: add Print Receipts Images action to IPL Expenses Card and List pages, and implement corresponding report for receipts images [*albertodone*]
  * Feat: add user settings functionality for IPL DocuFlow with sorting preferences and new pages [*albertodone*]
  * Feat: refactor container handling to use Dictionary for improved efficiency [*mpisana*]
  * Feat: add IPL ES Intrastat Management codeunit with event subscribers and field updates [*albertodone*]
  * Feat: add IPL Item By Event action to Transfer Order Subform [*mpisana*]
  * Feat: add drill-down functionality for Qty on SO/BSO PO/BPO [*mpisana*]
  * Feat: hide Email fields in purchase order extensions [*mpisana*]
### 🪲 Bug Fixes
  * Fix: add missing dependency entry for Intrastat Core in app.json [*albertodone*]
  * Fix: update tracking filter logic and correct location code reference in item tracking lines extension [*mpisana*]
  * Fix: make GetRecurringPurchaseLines action visible in IPL Log. Purchase Order page [*albertodone*]
  * Fix: renamed file [*albertodone*]
  * Fix: ensure valid remaining quantity before inserting entry in blanket purchase order processing [*albertodone*]
  * Fix: prevent division by zero in commission amount calculation in IPL Sales Detail Mgmt [*albertodone*]
  * Fix: update SubPageLink to use 'Blanket Order' for consistency [*mpisana*]
  * Fix: updated 'Requested Delivery Date' [*mpisana*]
  * Fix: update obsolete reason for Client ID field in IPL Dyn365 Integration Setup table [*albertodone*]
### 🔧 Other Changes
  * Merge pull request #450 from interpolimeri/adone/dev [*albertodone*]
  * Merge pull request #449 from interpolimeri/mpisana/dev [*albertodone*]
  * Merge pull request #448 from interpolimeri/adone/dev [*albertodone*]
  * Merge pull request #447 from interpolimeri/main [*mpisana*]
---

## Release 26.0.311.0 (PR #446) - 22/09/2025
### ✨ Features
  * Feat: add key for Item Ledger Entry No. in IPL Tracking Specification extension [*albertodone*]
  * Feat: add new key for IPL Item Ledger Entry and create IPL PBI Tracking Spec. extension [*albertodone*]
  * Feat: enhance record retrieval logic in IPL PBI Item Ledg. Entries API [*albertodone*]
  * Feat: add new key for Item No., Variant Code, Lot No., and Open in IPL Sell Off List Entry table [*albertodone*]
  * Feat: add validation for CustomerId field in Dyn365APIField [*albertodone*]
  * Feat: add Import Requisition Worksheets action to IPL Logistic Role Center [*mpisana*]
  * Feat: enhance email management by adding customer and vendor email [*mpisana*]
  * Feat: add Receipt Name field to IPL Warehouse Receipt List page [*mpisana*]
  * Add Excel import/export functionality to Warehouse Receipts and Shipment List pages [*mpisana*]
  * Feat: add IPL Req. Worksheet Ext. Whse page and update permissionset [*mpisana*]
  * Feat: add new page customizations and modify visibility settings for various pages in IPL Profile [*mpisana*]
### 🪲 Bug Fixes
  * Fix: update vehicle mapping in Transporeon Purch. Line table relation [*mpisana*]
  * Fix: correct indexing in Evaluate calls for ExpenseLineKey [*mpisana*]
  * Fix: correct parameter for GetLinkedPurchOrderFilter in IPL Sales Order Serv. Info page extension [*albertodone*]
  * Fix: correct authorization header handling in Transporeon API requests [*mpisana*]
### 🔧 Other Changes
  * Merge pull request #445 from interpolimeri/mpisana/dev [*albertodone*]
  * Merge pull request #444 from interpolimeri/adone/dev [*albertodone*]
  * Refactor: remove unused user tasks and job queue entry parts; add import action to IPL Ext. Logistic Role Center [*mpisana*]
  * Merge pull request #443 from interpolimeri/main [*mpisana*]
  * Merge pull request #442 from interpolimeri/main [*albertodone*]
---

## Release 26.0.310.0 (PR #441) - 18/09/2025
### ✨ Features
  * Feat: add IPL Security Vault dependency in Transporeon API [*albertodone*]
---

## Release 26.0.308.0 (PR #434) - 12/09/2025
### ✨ Features
  * Feat: improve ENV code retrieval logic in IPL Doc. Report ES Mgt. [*mpisana*]
  * Feat: add support for Option field type in IPL Expr. Solver Functions [*mpisana*]
  * Feat: make "Ship-to code" field editable in IPL Purchase Req. Worksheet [*mpisana*]
  * Feat: add IPL Sell-to Customer No. field to Requisition Line and update related logic [*mpisana*]
  * Feat: refactor IPL Sales Order and Sales Order List extensions to use LinkedPurchOrder variable [*mpisana*]
  * Feat: enhance Intrastat and invoicing management by adding Reason Code fields and updating payment terms handling [*albertodone*]
  * Feat: refactor IPL Transporeon Sales Order and Sales Orders pages to use TransportID and TransportOrderStatus variables [*mpisana*]
  * Feat: remove unused journal template inheritance procedures for sales and purchase headers [*albertodone*]
  * Feat: update journal template inheritance logic for sales and purchase headers [*albertodone*]
  * Feat: enhance IPL Document Report ES with new fields and improved translations [*mpisana*]
  * Feat: add credit memo payment terms handling [*albertodone*]
  * Feat: update IPL Invoice Document HU word layout [*mpisana*]
  * Feat: filter obsolete fields in IPL DB Correction Management [*albertodone*]
### 🪲 Bug Fixes
  * Fix: updates IPL Sales Document ES and  IPL Purchase Document ES [*mpisana*]
### 🔧 Other Changes
  * Merge pull request #433 from interpolimeri/adone/dev [*albertodone*]
  * Merge pull request #432 from interpolimeri/mpisana/dev [*mpisana*]
  * Merge pull request #431 from interpolimeri/main [*mpisana*]
---

## Release 26.0.307.0 (PR #430) - 08/09/2025
### ✨ Features
  * Feat: add new codeunits and extend existing functionalities for Intrastat management [*albertodone*]
### 🪲 Bug Fixes
  * Fix: add deletion of PullId in ProcessTransporeonOrderLog procedure [*mpisana*]
  * Fix: update version to 26.0.0.0 and extend id range to 55999 [*mpisana*]
### 🔧 Other Changes
  * Merge pull request #429 from interpolimeri/adone/dev [*albertodone*]
  * Merge pull request #428 from interpolimeri/mpisana/dev [*mpisana*]
  * Merge pull request #427 from interpolimeri/main [*mpisana*]
  * Merge pull request #426 from interpolimeri/main [*mpisana*]
  * Merge pull request #425 from interpolimeri/main [*albertodone*]
---

## Release 26.0.306.0 (PR #424) - 06/09/2025
### ✨ Features
  * Feat: created new app IPL Base ES [*mpisana*]
  * Feat: add new email templates for purchase orders, sales confirmations, and invoices in English and Spanish [*mpisana*]
  * Feat: enhance Transporeon order handling in sales and purchase order pages [*mpisana*]
### 🪲 Bug Fixes
  * Fix: updated Sales Order Confirmation ENU template (ES) [*mpisana*]
  * Fix: correct grammatical error in Sales Order Confirmation DEU template [*mpisana*]
### 🔧 Other Changes
  * Merge pull request #423 from interpolimeri/mpisana/dev [*albertodone*]
  * Merge pull request #416 from interpolimeri/main [*mpisana*]
---

## Release 26.0.305.0 (PR #422) - 05/09/2025
### ✨ Features
  * Feat: remove report permission for "IPL Update Item Desc. on Ord." [*albertodone*]
---

## Release 26.0.304.0 (PR #421) - 05/09/2025
### ✨ Features
  * Update ID ranges in app.json files across multiple modules to extend the range to 55999 [*albertodone*]
  * Feat: add IPL Dyn365 as a dependency in app.json [*albertodone*]
  * Feat: update shipment method code assignment logic in transport management [*albertodone*]
  * Feat: remove IPL Update Item Description on Orders report [*albertodone*]
  * Feat: add permissions for Return Receipt Header and Return Receipt Line [*albertodone*]
### 🔧 Other Changes
  * Merge pull request #420 from interpolimeri/increment-version-number/prerelease/250905213346 [*albertodone*]
  * New Version number 26.0 [*albertodone*]
  * Merge pull request #419 from interpolimeri/adone/dev [*albertodone*]
  * Merge pull request #418 from interpolimeri/adone/testalgo [*albertodone*]
  * Merge pull request #417 from interpolimeri/update-al-go-system-files/adone/testalgo/250905153312 [*albertodone*]
  * [adone/testalgo@556404d] Update AL-Go System Files from microsoft/AL-Go-PTE@main - 920b9e1 [*albertodone*]
---

## Release 25.4.302.0 (PR #457) - 28/09/2025
### ✨ Features
- **[Sales]**: Added **comment management** to sales orders. Users can now **add and track notes** directly on orders, improving **collaboration** and ensuring **important details** are easily accessible. [*albertodone*]
- **[Sales]**: Automatically calculate the **shipping number series** when creating sales orders from blanket orders, saving time and reducing errors. [*albertodone*]
- **[Sales]**: Added **Salesperson** and **Responsibility Center** fields to CRM accounts and orders. This helps users **assign ownership** and **track responsibilities** more effectively. [*albertodone*]
- **[Sales]**: Updated the **Packaging Type Code** field with helpful **tooltips** and improved visibility, making it easier to understand and use. [*albertodone*]
- **[Sales]**: Added a new report to **update item descriptions** on open orders, ensuring **accuracy** and saving time on manual updates. [*albertodone*]
- **[Finance]**: Added the **Payment Method Code** field to the general journal page, improving **clarity** and **customization** for financial entries. [*mpisana*]
- **[Finance]**: Introduced a **SEPA Direct Debit Mandates** report, enabling users to **generate and manage mandates** for streamlined payment processing. [*albertodone*]
- **[Purchase]**: Added a customization to control the **visibility of "Order No."** in the posted purchase receipt lines page, improving **data clarity**. [*mpisana*]
- **[Inventory]**: Enhanced the warehouse shipment report by adding the **Ship-to code** and updating address fields for **better accuracy** in shipping details. [*mpisana*]
- **[Inventory]**: Added an action to **view item availability by event** in the import requisition worksheet, helping users **plan inventory** more effectively. [*mpisana*]
- **[Integration]**: Improved email subject lines by using the **GetSubjectFromWordTemplate** method, ensuring **consistent and professional communication**. [*mpisana*]
- **[Integration]**: Implemented a **scheduled import feature** for expense management, automating data imports and saving time. [*mpisana*]
### 🪲 Bug Fixes
- **[Inventory]**: Updated the **vessel status options** for clearer descriptions, making it easier to understand and select the correct status. [*mpisana*]
- **[Reporting]**: Fixed the **report ID** for expense receipt images to ensure the correct report is generated. [*albertodone*]
---

## Release 25.4.301.0 (PR #415) - 04/09/2025
## Changelog for Version 25.4.301.0
### ✨ Features
- **[Integration]**: Expanded permissions for IPL Transporeon API and Tracking Management to enhance integration capabilities and streamline logistics tracking processes. [*albertodone*]
### 🪲 Bug Fixes
*(No bug fixes were included in this release)*
---

## Release 25.4.298.0 (PR #407) - 29/08/2025
## Changelog for Version 25.4.298.0
### ✨ Features
- **[Sales]**: Updated IPL Purch. Doc. Summary Buffer and related codeunit to enable Sales Order linking and pricing improvements. [*mpisana*]
- **[Inventory]**: Introduced IPL Calc. Availability Management codeunit with event subscribers for enhanced item availability filtering. [*mpisana*]
- **[System]**: Enabled delayed insert for IPL Cust. Alternative Payments page and enforced NotBlank validation for Item Category Code to improve data integrity. [*mpisana*]
### 🪲 Bug Fixes
- **[Purchase]**: Excluded Shipment Method Code assignment in SSO Purchase Header to prevent incorrect data population. [*albertodone*]
- **[Sales]**: Updated calculation method for Sales Detail unit cost to ensure accurate cost reporting. [*albertodone*]
- **[Integration]**: Corrected spelling in app name for IPL Credit Mixer Interface to align with naming standards. [*albertodone*]
- **[Sales]**: Fixed spelling errors in procedure names for Sales Header VAT category updates to improve code readability and maintainability. [*albertodone*]
---

## Release 25.4.297.0 (PR #402) - 26/08/2025
## Changelog for Version 25.4.297.0
### ✨ Features
- **[System]**: Added IPL Base dependency to `app.json` to enhance app extensibility and ensure compatibility with future integrations. [*albertodone*]
### 🪲 Bug Fixes
*(No bug fixes were included in this release)*
---

## Release 25.4.294.0 (PR #395) - 24/08/2025
## Changelog for Version 25.4.294.0
### ✨ Features
- **[System]**: Updated `DependenciesGraphALL.gv` to refine relationships and add new nodes, improving system clarity and maintainability. [*mpisana*]
- **[Sales]**: Added the "Shipment Method Code" field to the IPL Sales Open Price Closing page, enhancing shipment tracking and accuracy. [*mpisana*]
- **[Sales]**: Reorganized the shipping section to appear after sales lines, improving workflow and user experience. [*mpisana*]
### 🪲 Bug Fixes
*(No bug fixes were included in this release)*
---

## Release 25.4.293.0 (PR #393) - 18/08/2025
## Changelog for Version 25.4.293.0
### ✨ Features
- **[System]**: Updated German translations to improve localization and user experience for German-speaking users. [*mpisana*]
- **[Finance]**: Added IPL Accounting Customer List customization and integrated it into the IPL_ACCOUNTING profile, enhancing tailored financial workflows. [*mpisana*]
---

## Release 25.4.292.0 (PR #391) - 08/08/2025
## Changelog for Version 25.4.292.0
### ✨ Features
- **[Sales]**: Added Message Center functionality to Posted Return Shipment and Posted Return Shipments, improving communication and visibility for return processes. [*albertodone*]
- **[Sales]**: Enabled downloading selected documents as a single PDF across various document types, streamlining document management. [*albertodone*]
- **[Finance]**: Introduced the "IPL Amount per Ton (LCY)" field and updated commission entry calculations for enhanced financial accuracy. [*albertodone*]
- **[Finance]**: Added an event subscriber to update payment references when vendor invoice numbers change, ensuring data consistency. [*albertodone*]
- **[System]**: Enhanced user task actions to support bulk marking as read/unread with confirmation prompts, improving task management efficiency. [*albertodone*]
- **[Purchase]**: Added an action to force update purchase orders with Transporeon data on the IPL Transporeon Purch. Order page, ensuring data accuracy. [*albertodone*]
### 🪲 Bug Fixes
- **[Finance]**: Reviewed and corrected commission calculations to ensure accurate financial reporting. [*albertodone*]
- **[Reporting]**: Updated report captions to include "IPL" for improved clarity and alignment with business terminology. [*albertodone*]
- **[System]**: Reorganized the `PropagateSuspendStatusCheck` event subscriber for better procedural clarity and maintainability. [*albertodone*]
---

## Release 25.4.291.0 (PR #387) - 05/08/2025
## Changelog for Version 25.4.291.0
### ✨ Features
- **[Finance]**: Enhanced IPL Financial Journal with a new preview posting functionality, improving accuracy and reducing errors before posting. [*albertodone*]
- **[Finance]**: Replaced existing posting actions and added a dedicated preview posting action in the IPL Financial Journal extension for better control. [*albertodone*]
- **[Finance]**: Updated DependencyGraph to reflect new relationships and removed obsolete ones, ensuring accurate dependency tracking. [*mpisana*]
- **[Sales]**: Added "Item By Event" action to IPL Role Center and Sales Role Center pages, streamlining item tracking and event-based workflows. [*mpisana*]
- **[Sales & Purchase]**: Introduced functionality to disable purchase and sales defaults from posting groups, offering greater flexibility in configuration. [*albertodone*]
- **[Integration]**: Added navigation action and posting date field to IPL Email with Missing CoA pages, improving usability and data traceability. [*albertodone*]
### 🪲 Bug Fixes
(No bug fixes were included in this release.)
---
This changelog highlights the new features and improvements introduced in version 25.4.291.0, focusing on enhancing user experience, flexibility, and operational efficiency.
---

## Release 25.4.290.0 (PR #382) - 04/08/2025
## Changelog for Version 25.4.290.0
### ✨ Features
- **[Finance]**: Added reports for Financial Ledger and General Ledger to the IPLBaseDE permission set, improving reporting capabilities. [*albertodone*]
- **[Finance]**: Implemented a General Ledger report to enhance financial analysis and reporting. [*albertodone*]
- **[Finance]**: Scheduled Costing Period calculation via OnRun trigger, automating cost management processes. [*albertodone*]
- **[Purchase]**: Added default assignment for VAT and Gen. Business Posting Groups in Purchase Header, streamlining purchase order creation. [*albertodone*]
- **[Purchase]**: Reorganized VAT Info group and fields in the Purchase Return Order page extension for improved usability. [*mpisana*]
- **[Sales]**: Added Unit Price field to the IPL PUR Sales Lines page customization, enhancing sales line visibility. [*mpisana*]
- **[Inventory]**: Added IPL Handling Unit Type Code field to the IPL Packaging Types page, improving inventory categorization. [*mpisana*]
- **[System]**: Enhanced user task management with "Task to Read" functionality, improving task tracking and user productivity. [*albertodone*]
### 🪲 Bug Fixes
- **[Finance]**: Corrected parameter usage in the OnSetUpNewLineOnBeforeIncrDocNoHandler procedure, ensuring accurate document numbering. [*albertodone*]
- **[Finance]**: Removed redundant GLSetup record declaration and variable in the GetCurrencyCode procedure, optimizing code efficiency. [*albertodone*]
- **[Finance]**: Updated VATDateCaption to DateCaption in report layout for consistency in financial reporting. [*albertodone*]
- **[Purchase]**: Added integration setup retrieval in the order creation process, ensuring proper configuration during purchase order generation. [*albertodone*]
- **[System]**: Renamed task count procedures and fields for consistency, improving code readability and maintainability. [*albertodone*]
- **[System]**: Ensured correct language setting when applying saved views in cue management, enhancing user experience. [*mpisana*]
- **[Reporting]**: Updated report extension ID for IPL Suggest Worksheet Lines, ensuring proper report execution. [*albertodone*]
---

## Release 25.4.289.0 (PR #375) - 29/07/2025
## Changelog for Version 25.4.289.0
### ✨ Features
- **[Integration]**: Refactored authentication logic in IPL DocuFlow ArxNext Management codeunit to enhance security and streamline integration workflows. [*albertodone*]
---
