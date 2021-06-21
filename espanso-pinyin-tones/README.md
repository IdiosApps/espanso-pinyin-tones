---
package_name: "espanso-pinyin-tones"
package_title: "Espanso pinyin tones"
package_desc: "A package for typing Chinese pinyin tones"
package_version: "0.1.0"
package_author: "James Clark"
package_repo: "https://github.com/IdiosApps/espanso-pinyin-tones"
---
A package for typing Chinese pinyin tones

Source code is available at https://github.com/IdiosApps/espanso-pinyin-tones

Here is an example of input and output, demonstrating the package's usage:

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