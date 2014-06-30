# Function sin

Calculate the sine of a value.

For matrices, the function is evaluated element wise.


## Syntax

```js
math.sin(x)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`x` | Number &#124; Boolean &#124; Complex &#124; Unit &#124; Array &#124; Matrix | Function input

### Returns

Type | Description
---- | -----------
Number &#124; Complex &#124; Array &#124; Matrix | Sine of x


## Examples

```js
math.sin(2);                      // returns Number 0.9092974268256813
math.sin(math.pi / 4);            // returns Number 0.7071067811865475
math.sin(math.unit(90, 'deg'));   // returns Number 1
math.sin(math.unit(30, 'deg'));   // returns Number 0.5

var angle = 0.2;
math.pow(math.sin(angle), 2) + math.pow(math.cos(angle), 2); // returns Number ~1
```


## See also

[cos](cos.md),
[tan](tan.md)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->