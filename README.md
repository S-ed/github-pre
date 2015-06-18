# Github Word Wrapping for CODE blocks
Userscript for github that adds a button to switch word wrapping for code in comments.

![Example usage](https://cloud.githubusercontent.com/assets/3008353/8000621/f215e8b2-0b65-11e5-89da-45bff12229cf.gif)

Script uses Local Storage to store a default setting of word wrapping for whole site.
It will use hardcoded value
```
var wrapDefault = false;
```
if no Local Storage available.

There is no also menu to reset default value stored in Local Storage.
```
localStorage.removeItem("wrapDefault");
```
command may be used to reset the value.
