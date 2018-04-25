# PHP projects guidelines
A quick reminder on how to share your project with Seniormedia team when working with PHP


## INDENT / SPACE
* Use 2 spaces instead of tabs for indent

* Put spaces on either side of binary operators
```php
true

$a = $b + $c;

_________________________

false

$a=$b+$c;

```

* `if`, `while`, `for` and `foreach` should be followed by a space, and bracket preceded by space
```php
true

if ($a == $b) {
  $a = 'foo';
}

_________________________

false

if($a == $b){
  $a = 'foo';
}

```

* Braces are placed on the same line as the start of the function, conditional, loop, etc. The else/elseif is placed on the same line as the previous closing brace.
```php

function foo($var) {
  if (is_null($var)) {
    return true;
  } else {
    return false;
  }
}
```

* Do not put spaces in brackets.
```php
true

$a = ['foo', 'bar'];
$c = $a[0];
$x = [];

_________________________

false

$a = [ 'foo', 'bar' ];
$c = a[ 0 ];
$x = [ ];

```
## Code structure

* Use `elseif` not `else if`

* Use lowerCamelCase when naming functions or variables
```php
$myVar = 'foo';

function doSomething() { ... }
```

* For simple string literals, single quotes are slightly faster for PHP to parse than double quotes. For these reasons, single quotes are preferred in cases where they are equivalent to double quotes.


```php
true

$count = 1;
echo 'The count is ' . $count;

_________________________

false

$count = 1;
echo "The count is $count";

_________________________

false

echo "This is simple string";

```