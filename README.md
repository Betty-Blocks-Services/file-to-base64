# file-to-base64

This function can be used to convert a file (based on a URL) to a Base64 string.

## Configure the function

### File URL:

![image](https://user-images.githubusercontent.com/96063344/235083172-3d3ec76c-205b-495c-a30b-162754a91cd8.png)

Specify the URL (through a variable) to the file which you want to encode as a Base64 string. This can be a file property (e.g. from a file upload component) or a plain text URL/variable.

### Headers:

Optionally pass additional headers when fetching the file, for example an `Authorization` token when the file URL is protected. Add the required headers as key/value pairs.

### Include mime-type in output:

![image](https://user-images.githubusercontent.com/96063344/235083244-e20e764b-7f00-4d21-92b3-9c9922e6a47d.png)

This option will add the mime-type to the Base64 string which makes it possible to use in PDF templates or as an image source. When turned off, only the raw Base64 string is returned.

### Result:

![image](https://user-images.githubusercontent.com/96063344/235083346-b794477f-f2df-456d-a02d-264b0f0b290b.png)

This is the (Text) output of the function and will contain the Base64 string.

## Version history

- **1.1** — Added a `Headers` option so authenticated/protected file URLs (e.g. requiring an `Authorization` header) can be fetched. Added inline `info` descriptions for each option.
- **1.0** — Initial release.
