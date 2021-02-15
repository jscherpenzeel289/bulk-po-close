Bulk Close Purchase Orders App.

A light web based application which allows users with correct role permissions to close purchase order headers in bulk.
Security and Permissions:
As this app uses standard Coupa permissions there is no additional security or content required. The acting user must be logged into their Coupa instance and have the ability to close purchase order headers. All purchase order close history events are still retained and all standard purchase order closing requirements apply, see Coupa’s PO close documentation for support. https://success.coupa.com/Support/Docs/Core_Apps/Procurement/Getting_Started_with_Procurement/Purchase_Orders/Closing_Purchase_Orders

Instructions:
The attached file must be uploaded into your Coupa instance using the file option under a PO Customisation template.
Step 1: Navigate to Setup > PO Customisation
Step 2: Select and edit a chart of accounts PO custom template using the edit/pencil action. (The chart of accounts does not have to be active)
Step 3: Under PO Layout, use the Image / Choose File option to select and upload the .html file.
Step 4: Click Save
Step 5: Edit the same PO custom template or go back in your browser.
Step 6: Click and open the app file you just uploaded.
Step 7: You are ready to go.
Step 8: Additionally you can add to an iframe panel app using the address url.


Customisation:
The banner color can be changed to suit your instance. To change the color, you must add the “color” parameter to the URL address. Open the app in your browser, and in the address bar, add &color= plus your hex color code
Example: https://yourinstance/public_attachments/r3YWLaQK?etag=ef58b0...&color=6e0070
The max row limit can also be changed, by adding the lines parameter to the URL address. (Its recommended you do not exceed 1000 which is its default)
Example: https://yourinstance/public_attachments/r3YWLaQK?etag=ef58b0...&lines=500
