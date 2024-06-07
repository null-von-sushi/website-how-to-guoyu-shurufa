## Your options

### RIME
It supports basically everything you want, including proper traditional chinese punctuation and filtering pinyin by tones.

- [Installation](#installing-rime)
- [Customization](#customizing-rime)
- [How to type with tones](#using-terra-pinyin-地球拼音-in-rime)
- [Enabling Taiwanese Mandarin](#using-terra-pinyin-with-chinese-characters-adhering-to-the-taiwanese-roc-standard)

#### Installing RIME

Install using your distro's package manager.

It's recommended you read the [Arch Wiki for this topic](https://wiki.archlinux.org/title/Rime), even if not using Arch.

⚠️ Layouts might be split into different packages, so check if they exist. For example `rime-terra-pinyin`. ⚠️

#### Customizing RIME

Note that unlike the Windows version, most things are configured in config files.

Again, check the [Arch wiki](https://wiki.archlinux.org/title/Rime#Selecting_Input_Method)

The `.schema.yaml` files are the ones that define a layout. With a text editor you can change a few things (such as disabling the shift button from enabling alphabet mode, forcing ROC standard characters rather than variant characters used over in Singapore or mainland China (為 instead of 爲 etc.), and more. 

#### Using Terra Pinyin (地球拼音） in RIME
If you want to be able to type not just `hao` and get a whole list of Hanzi, but be able to specify *which* `hao` you want (for example, `hao4` which among others would give you `號`), you will want to use Terra Pinyin. It's like normal pinyin you already know, supports typing just the first letter and have it suggest the correct sentence (for example: `jttqhh` might suggest `今天天氣很好`), but it also let's you enter tones. 

By default, the tones are entered as follows:
 - `-` is first tone. So `ma-` would be `mā`, which would give you `媽`
 - `/` is second tone. So `hui/` would be `huí`, which would give you `回`
 - `<` is third tone. So `ma<` would be `mǎ`, which would give you `馬`
 - `\` is fourth tone. So `hui\` would be `huì`, which would give you `會`.

#### Using Terra Pinyin with chinese characters adhering to the Taiwanese (ROC) standard
 - Drop [this file]([https://raw.githubusercontent.com/null-von-sushi/website-how-to-guoyu-shurufa/main/RIME/Windows_CN/terra_pinyin_cn.schema.yaml) to ...
   - (if using ibus) ... `$HOME/.config/ibus/rime/` and `$HOME/.config/ibus/rime/build`.
 - Then set it as the active layout:
   - (if using ibus) Edit `$HOME/.config/ibus/rime/default.custom.yaml` and make it look like bellow. Then restart ibus.

<details> <summary> contents of 'default.custom.yaml' <b>(click to open) </summary>

```
patch:
  schema_list:
    - schema: terra_pinyin_tw
```

</details>

If you have issues on Linux, I am happy to try and help you, so feel free to contact me.
