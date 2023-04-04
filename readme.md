# This is a collection of Regex to match URLs of popular websites

## Feel free to add more 🖊

- Please follow the alphabetical order while adding more

```Javascript
  const amazon = /https?:\/\/(www\.)?amazon\.com\/[\w.-]*/;
  const flipkart = /https?:\/\/(www\.)?flipkart\.com\/[\w.-]*/;
  const googleMeet = /https?:\/\/(meet|hangouts)\.google\.com\/[\w.-]*/;
  const instagram = /https?:\/\/(www\.)?instagram\.com\/[\w.-]*/;
  const notion = /https?:\/\/[\w.-]*\.notion\.so\/[\w.-]*/;
  const reddit = /https?:\/\/(www\.)?reddit\.com\/[\w.-]*/;
  const slack = /https?:\/\/[\w.-]*\.slack\.com\/[\w.-]*/;
  const snapchat = /https?:\/\/(www\.)?snapchat\.com\/[\w.-]*/;
  const twitter = /https?:\/\/(www\.)?twitter\.com\/[\w.-]*/;
  const youtube = /^(https?:\/\/)?(www\.)?(youtube\.com|youtu\.?be)\/.+$/;
  const validURL = /^(?:(?:(?:https?|ftp):)?\/\/)(?:\S+(?::\S*)?@)?(?:(?!(?:10|127)(?:\.\d{1,3}){3})(?!(?:169\.254|192\.168)(?:\.\d{1,3}){2})(?!172\.(?:1[6-9]|2\d|3[0-1])(?:\.\d{1,3}){2})(?:[1-9]\d?|1\d\d|2[01]\d|22[0-3])(?:\.(?:1?\d{1,2}|2[0-4]\d|25[0-5])){2}(?:\.(?:[1-9]\d?|1\d\d|2[0-4]\d|25[0-4]))|(?:(?:[a-z\u00a1-\uffff0-9]-*)*[a-z\u00a1-\uffff0-9]+)(?:\.(?:[a-z\u00a1-\uffff0-9]-*)*[a-z\u00a1-\uffff0-9]+)*(?:\.(?:[a-z\u00a1-\uffff]{2,})))(?::\d{2,5})?(?:[/?#]\S*)?$/i
```
