# A set of QR code scan and display components

The latest version can be included in your player from this location: -

```
https://files-manywho-com.s3.amazonaws.com/e1dbcceb-070c-4ce6-95b0-ba282aaf4f48/qr.js
https://files-manywho-com.s3.amazonaws.com/e1dbcceb-070c-4ce6-95b0-ba282aaf4f48/qr.css
```


# QRCodeReader

Uses the camera of the device to scan for QR Codes & Barcodes from live video.

Uses the zxing library for image interpretation.

Set the state to a string value to receive the barcode value.

Set the width & height to control the display size on the page.

## OUtcomes

### OnDetect 
Will be triggered on barcode read if it exists.

### OnCancel
Will be triggered if the user presses the cancel button while scanning if exists.
 = to the name of an outcome.  This will add a cancel button which will trigger the outcome, optional.


# QRCodeWriter

Generates a QR code on screen from the string state value.

Uses the zxing library.

Set the state to a string value which provides the barcode value.

Set the width & height to control the display size on the page.


