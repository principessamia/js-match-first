# match-first

Retrieve the first item in an array that matches a callback function.

Returns `null` if a matching element is not found.


## Installation

```npm install find-first```

## Example

```javascript
var findFirst = require('find-first');

var arr1 = ['1', '2', '3'];
var arr2 = [1, 2, 3];

function matcher(i) {
	return i === '1';
}

findFirst(arr1, matcher); // '1'
findFirst(arr2, matcher); // null
```

File size: **414 bytes**.<br/>
Supported platforms: **server and browser**.<br/>
Supported language versions: **ES3 and above**.
