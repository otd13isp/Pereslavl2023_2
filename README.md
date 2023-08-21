# Application for uploading encrypted data from ODS spreadsheets to the cloud
## Free Software (free software)

The application is free software.

## Functions
- Select and upload one or more ODS files
- The application encrypts the contents of the selected files
- Encrypted data can be hosted on the cloud

 
## Requirements:
- [JavaScript](https://www.ecma-international.org/publications-and-standards/standards/ecma-262) - for website frontend and backend
- [Bootstrap](https://getbootstrap.com/) - for website frontend and Web Apps
- [Node.js](https://nodejs.org/) - for npm usage
- [npm](https://www.npmjs.com) - Node.js package manager
- [SheetJS Community Edition](https://docs.sheetjs.com/docs) - for extracting spreadsheetdata and generating new spreadsheets
- [CryptoJS](https://cryptojs.gitbook.io/docs) - JavaScript library of crypto standards
 
 
The application is also open source with code on Github

## Installation
You need to create a directory and copy index.html file there.
From the inside of this directory install the dependencies using the following instructions:
**npm i xlsx**
**npm i crypto-js**

In the index.html file, you need to check that the paths for the libraries are correctly specified:
**<script src="node_modules/xlsx/dist/xlsx.full.min.js"></script>**
**<script src="node_modules/crypto-js/crypto-js.js"></script>**


## Usage
Upload the index.html file into the browser.
Select one or more files to encrypt their content.
Press the "Download" button.
The result of the application will be presented on the screen: file name, spreadsheet sheet number, and each element of the cell
in its original form, in encrypted form and in decrypted form to control the correctness of encryption.
The symbol "|" is used as a separator.
The ciphertext can be uploaded to the cloud.

## License
MIT