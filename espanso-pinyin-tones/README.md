---
package_name: "espanso-pinyin-tones"
package_title: "Espanso pinyin tones"
package_desc: "A package for typing Chinese pinyin tones"
package_version: "0.1.0"
package_author: "James Clark"
package_repo: "https://github.com/IdiosApps/espanso-pinyin-tones"
---
## An Espanso package for typing Chinese pinyin tones

This package allows you to quickly and easily write characters marked with pinyin tones. For example, marked characters for the letter "e" can be created as follows:

| Input      | Output |
| ----------- | ----------- |
| :e1      | ē       |
| :e2   | é        |
| :e3      | ě       |
| :e4   | è        |
| :e5      | e       |

Similarly, other tones can be created:

| letter | 1st tone  |  2nd tone | 3rd tone  | 4th tone
|---|---|---|---|---|---|
| a  | ā  | á  | ǎ  | à  | 
| e  | ē  | é  | ě  |  è |
| i  | ī  |  í | ǐ  | ì  |
| o  | ō  |  ó | ǒ  | ò  |
| u  | ū  |  ú | ǔ  | ù  |
| ü  | ǖ  |  ǘ | ǚ  | ǜ  |

The only exception is that the marked characters for "ü" are typed a bit differently: {:u:5 -> ü}, {:u:1 -> ǖ}, etc.

___

### Installation

This package is _not yet approved for the espanso-hub_ - but you can still install and use it!
There isn't much in this [open-source espanso-pinyin-tones repository](https://github.com/IdiosApps/espanso-pinyin-tones), so have a look around and confirm you're happy to install this unapproved package:

`espanso install -e espanso-pinyin-tones https://github.com/IdiosApps/espanso-pinyin-tones`

