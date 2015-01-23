Request is designed to be the simplest way possible to make http calls. It supports HTTPS and follows redirects by default.

```javascript
var request = require('request');
request('http://www.google.com', function (error, response, body) {
  if (!error && response.statusCode == 200) {
    console.log(body) // Print the google web page.
  }
})
```
###References
https://www.npmjs.com/package/request
