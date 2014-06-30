# Function deepEqual

Test element wise whether two matrices are equal.
The function accepts both matrices and scalar values.


## Syntax

```js
math.deepEqual(x, y)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`x` | Number &#124; BigNumber &#124; Boolean &#124; Complex &#124; Unit &#124; Array &#124; Matrix | First matrix to compare
`y` | Number &#124; BigNumber &#124; Boolean &#124; Complex &#124; Unit &#124; Array &#124; Matrix | Second matrix to compare

### Returns

Type | Description
---- | -----------
Number &#124; BigNumber &#124; Complex &#124; Unit &#124; Array &#124; Matrix |  Returns true when the input matrices have the same size and each of their elements is equal.


## Examples

```js
math.deepEqual(2, 4);   // returns false

a = [2, 5, 1];
b = [2, 7, 1];

math.deepEqual(a, b);   // returns false
math.equal(a, b);       // returns [true, false, true]
```


## See also

[equal](equal.md),
[unequal](unequal.md)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->