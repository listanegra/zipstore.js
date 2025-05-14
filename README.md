# zipstore.js
### Simple and efficient zip file bundler for JS

This library can create zip files on the browser, it does not have any built-in compression algorithm whatsoever, it simply stores all files with compression method 0 (aka store-only), solely for the purpose of grouping multiple files that could be downloaded at once for example.
