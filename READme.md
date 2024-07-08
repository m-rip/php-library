## PHP basic syntexes
### PHP datatype
| Datatype Name | string | integer | float | boolean | array |
| ---------- | ----- | ------ | ----- | --------- | ----- |
| Example | 'forgive me' |  143 | 5 . 5 | true / false |  array('apple', 'mango', 'lichi') |

---

### Print value in PHP
```
echo 'hello, I am Rafiul from Dhaka, Bangladesh.';
```
```
print 'hello, I am Rafiul from Dhaka, Bangladesh.';
```
---
### typeof operator syntex in PHP
```
var_dump('hello kitty');
```
### Variable
```
$fruit = apple;
echo $fruit;
```
---
### Constent variable
<p>constent in PHP . It's like a variable. but it is not changable. It is global.</p>

```
define('statement', 'not changable variale');
echo statement;
```
---
### Object in PHP
```
class car {
        var $car_model;
        function car_model_name($value) {
            global $car_model;
            $car_model = $value;
            echo "$car_model <br>";
        }
    }
var_dump($car_details);
```
---
### String in PHP
```
$str = 'Hello, I am Rafiul. I am a student of Web Development from my home. I am loved to learn by self study.'

// length of string i PHP
    echo strlen($str) . '<br>';
// word count in PHP
    echo str_word_count($str) . '<br>';
// revers
    echo strrev($str) . '<br>';
// find length position by searching in PHP code
    echo strpos($str , 'u') . '<br>';
// replace a word
    echo str_replace('Rafiul', ' rafael', $str) . '<br>';
```
---
### Number in PHP
```
// all about Number
    echo pi() . '<br>';
    echo min(5,23,2,56,1.3) . '<br>';
    echo max(5,23,2,56,1.3) . '<br>';
    echo abs(-23) . '<br>'; //abs means absolute number. it means number always positive.
    // all about Number
    echo sqrt(4) . '<br>'; // root of squre number

    echo round(pi()) . '<br>';

    // all about Number
    echo rand() . '<br>';
    echo rand(1, 6) . '<br>';
```

# END