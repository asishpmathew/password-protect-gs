# password-protect-gs

Access to Google Drive requires logging into Google. Since we are typically logged into Google on our phones and PCs, anyone briefly gaining access to your device could potentially view your Drive contents. This poses a significant security risk.

The ideal resolution for this issue would involve Google Drive prompting for a password every time a document is opened. However, Google does not currently offer this built-in protection feature. Nevertheless, you can achieve a similar level of security by utilizing password-protected Google Spreadsheets through Google Scripts. This repository can assist you in encrypting and decrypting your Google spreadsheet.

## How-to

1. Open your desired Google Sheet.
2. Go to Tools > Script editor.
3. Copy and paste the code from the Password Protect GS repository (https://github.com/asishpmathew/password-protect-gs/blob/main/Code.gs) into the script editor window.
4. Save the project (File > Save).
5. Now select "Publish->Deploy as webapp" and click on the "Deploy" button. You will now be shown a confirmation that you app has been deployed as a web app.

![how-to](https://github.com/asishpmathew/password-protect-gs/blob/main/test-pic.png)

## sample of encrypted page

![how-to](https://github.com/asishpmathew/password-protect-gs/blob/main/sample-encrypted.png)

