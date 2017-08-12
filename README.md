# A1Z26
This script that allows you to encrypt text according to a given alphabet using the cipher A1Z26.

## Encode string
```php
$str = "some code"; //The string to encode.
$abc = "abcdefghijklmnopqrstuvwxyz"; //The alphabet you need.

$new_str = A1Z26_Encode($str, $abc); //19-15-13-5 3-15-4-5
```
## Decode string
```php
$str = "19-15-13-5 3-15-4-5"; //The string to decode.
$abc = "abcdefghijklmnopqrstuvwxyz"; //The alphabet used for encoding.

$new_str = A1Z26_Decode($str, $abc); //some code
```
