# local-phrases
Translations of common web phrases. Useful for content localization.

# Install
```
$ npm install local-phrases
```

# Usage
## Example
````js
var phrases = require('local-phrases');
var vietPhrases = phrases['vi'];
console.log(vietPhrases.submit); // đệ trình
````

# Support

## Phrases
Currently supports following phrases:

Phrases        |
---------------|
edit           | 
email          |
firstName      |
language       |
lastName       |
login          |
logout         |
name           |
newPassword    |
options        |
password       |
preview        |
profile        |
repeatPassword |
save           |
settings       |
signIn         |
signUp         |
submit         |
username       |

## Languages
Currently supports following languages:

Languages |  ISO 639-1  |
--------- |-------------|
arabic    |      ar     |
chinese   |      zh     |
dutch     |      nl     |
english   |      en     |
french    |      fr     |
german    |      de     |
hindi     |      hi     |
italian   |      it     |
japanese  |      ja     |
korean    |      ko     |
portuguese|      pt     |
russian   |      ru     |
spanish   |      es     |
vietnamese|      vi     |

# Contributing
Please submit a pull request if you see an incorrect translation or want to add a new language/phrase!
Most of the current translations are from [Microsoft Language Portal](https://www.microsoft.com/Language/).

# Plug
This module was created while working on [Lang.Community](http://lang.community), 
which is super prototype-y right now, but feel free to try it out/give me feedback!
