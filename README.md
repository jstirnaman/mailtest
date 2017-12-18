# Examples of emails with embedded inline and attached images
* `node index.js` creates and sends test emails.
* `*.eml` files are raw source examples.
* Screenshots are example results in Mac OSX mail client.

OSX example with Base64-encoded inline image...
 1. [OSX 10.11.16 without specified content-type](Screen_Shot_2017-12-18_at_8.50.57_AM.png)
 2. [OSX 10.11.16 with specified content-type](Screen_Shot_2017-12-18_at_8.54.03_AM.png)

## iOS
Before upgrading the device to iOS 11, the inline attachment displayed when the content-type header was provided. No screenshot of this is available.
After upgrading to iOS11, the inline related/CID attachment does not display even when the content-type header is provided. The img-embedded base64 still displays as expected.

iOS example with Base64-encoded inline image...
1. [iOS v. 11, with content-type](mail-ios-content-type-ios11.mov)
2. [iOS prior to v. 11, without content-type](mail-ios-no-content-type-pre-ios11.mov)
