# Mult-Language

AddChat CodeIgniter supports multiple languages. 

---

![Addchat Multi-language](https://addchat-docs.classiebit.com/images/multi-lang.jpg "Multi-language")

---

> {success} AddChat `auto-detects` & `auto-adapts` your website current default language.

---

- [Add New Language](#Add-New-Language)


<a name="Add-Language"></a>
## Add Language

AddChat installer transfers a file `addchat_lang.php` inside your website English Language (`application/language/english/addchat_lang.php`) directory. 

<br>

To add a new language, simply copy the `addchat_lang.php` into any other language folder and translate all variable's **VALUES** inside the new language folder `addchat_lang.php` file.

---

>{warning} Translate variable **VALUES** only and not **VARIABLE NAMES**

---

e.g Suppose you wanna add `hindi` language. Simply copy the `addchat_lang.php` from the English language folder and paste it into the `hindi` language folder.

```bash

    application
        │
        ├── language
            ├── english
            │   └── addchat_lang.php
            │
            └── hindi
                └── addchat_lang.php
```