# README
## Contact Manager

 Contact Manager is a fully offline, lightweight, browser-based contact management app. It requires no backend, saves all data locally, and supports encryption, CSV import/export, custom fields, password-protected access, and a clean UI for viewing, editing, and organizing contacts.

## How to Use

1. Download the HTML file
2. Open the HTML file in any modern browser (tested to work in Opera, Chrome, and other Chromium browsers)
3. Follow the simple on-screen directions to manage contacts
4. Export, print or save your contacts if preferred

## Features

1. Fully stable version
2. Runs entirely in the browser — no internet, no servers, no tracking.
3. Add, Edit, Delete Contacts
4. Create contacts with: First and Last Name, Email, Phone, Notes, and Unlimited Custom Fields
5. CSV Import with decryption if password-protected
6. CSV Import of unprotected files
7. CSV Import of foreign formats
8. Allows for Imports to replace or add to current contact(s) if any
9. Allows for export as a CSV file
10. Allows for files to be encrypted with password
11. Encrypted using SHA-256 derived AES-GCM and Base-64
12. Dynamically rendered with user-friendly UI/UX
13. Allows for Printing or saving as PDF
14. Allows for CSV naming
15. Default name includes timestamp in UTC +0 time
16. The CSV File contains all standard and custom fields

## Notes

1. The CSV Import tool will attempt to decode all information, however there is no guarentees of proper display of information if the file is foreign or corrupt
2. The file is unrecoverable if the password is forgotten
3. All data is stored in memory only and will be lost when you close or refresh this page. Always export your contacts to CSV to save them.
4. Pure JavaScript — no frameworks
5. Uses crypto.subtle WebCrypto API
6. Works on all modern browsers
7. Fully sandboxed on the client
8. All data remains client-side.
9. No servers or cloud storage involved.
10. The data will not save unless manually saved

*End of Document*
