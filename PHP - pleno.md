Pergunta 1/15:

...Which of the following will not combine strings `$s1` and `$s2` into a single string?

- [ ] `"{$s1}{$s2}"`
- [ ] `$s1.$s2`
- [ ] `$s1 + $s2`
- [ ] `implode(' ', array($s1,$s2))`

Pergunta 2/15:

Given a variable `$email` containing the string `user@example.com`, which of the following statements would extract the string `example.com`?
- [ ] `strstr($email, "@");`
- [ ] `substr($email, strpos($email, "@")+1);`
- [ ] `strchr($email, "@");`
- [ ] `substr($email, strpos($email, "@"));(/)`

Pergunta 3/15:
Given a comma-separated list of values in a string, which function from the given list can create an array of each individual value with a single call?

- [ ] `strstr()`
- [ ] `explode()`
- [ ] `strtok()`
- [ ] `extract()`

Pergunta 4/15:

Which of the following PCRE regular expressions best matches the string `php|architect`?
- [ ] `[az]{3}\|[az]{9}`
- [ ] `.*`
- [ ] `[a-z][a-z][a-z]\|\w{9}`
- [ ] `\d{3}\|\d{8}`


Pergunta 5/15:
Which of the following functions can be used to determine the integrity of a string?
- [ ] `md5()`
- [ ] `sha1()`
- [ ] `crc32()`
- [ ] all the answers

Pergunta 6/15:
What is the output?
```php
<?php
$x = array( "aaa", "ttt", "www", "ttt", "yyy", "tttt" );
$y = array_count_values($x);
echo $y[ttt];
?>
```
- [ ] `2`
- [ ] `4`
- [ ] `3`
- [ ] `1`

Pergunta 7/15:

What is the output?
```php
<?php
$ x = array(1,3,2,3,7,8,9,7,3);
$ y = array_count_values($x);
echo $y[8];
?>
```
- [ ] `43`
- [ ] `8`
- [ ] `6`
- [ ] `1`

Pergunta 8/15:
What is the output?
Assume that today is 2009-5-18:2:45:32 pm
```php
<?php $today = date("F j, Y, g:i a"); ?>
```

- [ ] `May 18,09,2:45:32 PM`
- [ ] `May 18,2009,14:45:32 PM`
- [ ] `May 18, 2009, 2:45 pm`
- [ ] `May 18,2009,14:45:32 pm`

Pergunta 9/15:
What happens if you add a string to an integer using the + operator?

- [ ] The integer and string are concatenated together in a new string
- [ ] The integer is discarded and the string is preserved
- [ ] The string is discarded and the integer is preserved
- [ ] The string is converted to a number and added to the integer
- [ ] The interpreter outputs a type mismatch error

Pergunta 10/15:

What is the output?
```php
<?php
define("x", "5");
$x = x + 10;
echo x;
?>
```
- [ ] `10`
- [ ] `15`
- [ ] Error
- [ ] `5`


Pergunta 11/15:
How would you add 1 to the variable `$count`?

- [ ] `$count++;`
- [ ] `incr count;`
- [ ] `incr $count;`
- [ ] `$count =+1`


Pergunta 12/15:

What is the return value of this substr function?
```php
<?php
$rest = substr("abcdef", -1);
$rest = substr("abcdef", 0, -1);
?>
```
- [ ] `a,abcde`
- [ ] `a,fedcb`
- [ ] `f,abcde`
- [ ] `b,abcdef`


Pergunta 13/15:

Assume that your php �le 'index.php' in location `c:/apache/htdocs/phptutor/index.php`. If you used basename`($_SERVER['PHP_SELF'])` function in your page, then what is the return value of this function?
- [ ] `/index.php`
- [ ] `index.php`
- [ ] `phptutor/index.php`
- [ ] `phptutor`


Pergunta 14/15:

What is the output?
```php
<?php
$arr = array( 5 => 1, 12 => 2 );
$arr[] = 56;
$arr["x"] = 42;
unset($arr);
var_dump($arr);
?>
```
- [ ] `Null`
- [ ] `x = 42`
- [ ] `56`
- [ ] `42`


Pergunta 15/15:
Which of the following type cast is not correct?
```php
<?php
$fig = 23;
$varb1 = (real) $fig;
$varb2 = (double) $fig;
$varb3 = (decimal) $fig;
$varb4 = (bool) $fig;
?>
```


- [ ] `double`
- [ ] `decimal`
- [ ] `bool`
- [ ] `real`
