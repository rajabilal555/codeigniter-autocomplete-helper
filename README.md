
# CodeIgniter AutoComplete Helper
Just a PHP file which will trick the IDE into recognizing CodeIgniter 3 Libraries and functions 
(Tested on VSCode with PHP Intelephense)

The `autocomplete.php` can be placed anywhere, but I just like to place it in the config folder as I need to change it every time I create a new `Model`, but It is mostly personal Preference.

## Installation/Usage
- Download this repository
- Extract the contents into your project root folder 
- Add your models into the file (`applicaton/config/autocomplete.php`) near : 
```php
 * ============ Codeigniter Project Models ================
 *  Models that are in your project. if the model is in a folder, still just use the model name.
 *
 *  $this->People-> will show all the methods in the People model
 *	Change the following according to your own Models
 *
 * @property People $People // Replace This
 *
 * @property Products $Products // And This
 * 
```
 - That's it, Enjoy!


**Note:** I have been using this code for some time now and I cannot remember where I found It I have made some modifications to it but its still quite the same.
