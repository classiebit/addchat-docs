# Mult-Language

AddChat Laravel supports multiple languages.

---

![Addchat Multi-language](https://addchat-docs.classiebit.com/images/multi-lang.jpg "Multi-language")

---

> {success} AddChat `auto-detects` & `auto-adapts` your website current default language.

---

- [Add New Language](#Add-New-Language)


<a name="Add-Language"></a>
## Add Language

When you run the AddChat install command, it publishes all the languages to your application `resources/lang/vendor/addchat` directory. So that if you wanna change something in an existing language, you can do so. 

1. And, to add a new language, simply copy the `en` directory and paste it as `<your_language_name_shortcode>`. Then translate all the variable's **VALUES** inside the new language folder `ac.php` file.

    ---

    >{warning} Translate variable **VALUES** only and not **VARIABLE NAMES**

    ---

    e.g Suppose you wanna add `romanian` language. Simply copy the `en` folder and paste it as `ro`

    ```bash

        resources
            │
            ├── lang
                ├── vendor
                    ├── addchat
                        ├── en
                        └── ro

    ```
