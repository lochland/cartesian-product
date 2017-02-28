# cartesian-product

Simple library to compute the cartesian product. A de-moduled version of [Izaak
Schroeder](https://github.com/izaakschroeder/cartesian-product)'s
implementation.

```javascript
var product = require('cartesian-product');
console.log(product([
	[1,2],
	[4,5]
]));
// [ [1,4], [1,5], [2,4], [2,5] ]
```
