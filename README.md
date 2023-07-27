# fancy_text
convert your normal text to fancy text

# How To Use
first, include fancytext.php to your project
then we can call it by writing the function

fancytext(0,'your text')

0 is fancytext type
then 'your text' is the string that will be converted to fancytext

and this function will return array

open index.php you will know how to use it.


Kamu juga bisa tambahkan fungsi bash ke file .bashrc anda
Tambahkan kode ini:
```
fancytext () {                                                          #!/bin/bash                                                         

homeDirectory=$(eval echo ~)                                          

php -r "include('${homeDirectory}/wibi9424/fancy_text/fancytext.php'); echo fancytext($1, '$2')[1];"

} ```



