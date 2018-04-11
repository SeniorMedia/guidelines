# PHP projects guidelines


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

* Use `elseif` not `else if`
