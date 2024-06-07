## Don't use...

 - ... the built-in Pinyin options. Microsoft's IME is generally awful. If you plan to type Simplified, then it might be acceptable? It's definitely garbage for traditional. ), 
 - Baidu or Sogou, unless you like playing fast and loose with data security and privacy. But feel free to make your own choices if your PC only contains your own data. 

## Do use:
### RIME
It supports basically everything you want, including proper traditional chinese punctuation and filtering pinyin by tones.

#### Installing RIME
[latest release on Github](https://github.com/rime/weasel/releases/latest)

The installer & options are unfortunately only in chinese at the time of this writing ([although that should change soon](https://github.com/rime/weasel/pull/900)). You can use google lens / google translate's camera feature for now. Once installed it has probably the best IME you can get.

#### Customizing RIME
🐧 You can find the user files for RIME at `$HOME/.config/ibus/rime/` if using iBus. It's recommended you read the [Arch Wiki for this topic](https://wiki.archlinux.org/title/Rime), even if not using Arch.
🪟 You can find the files for RIME at `C:/Program Files (x86)/RIME/Weasel/` on Windows.
The `.schema.yaml` files are the ones that define a layout. With a text editor you can change a few things (such as disabling the shift button from enabling alphabet mode, forcing ROC standard characters rather than variant characters used over in Singapore or mainland China (為 instead of 爲 etc.), and more. 

#### Using Terra Pinyin (地球拼音） in RIME
If you want to be able to type not just `hao` and get a whole list of Hanzi, but be able to specify *which* `hao` you want (for example, `hao4` which among others would give you `號`), you will want to use Terra Pinyin. It's like normal pinyin you already know, supports typing just the first letter and have it suggest the correct sentence (for example: `jttqhh` might suggest `今天天氣很好`), but it also let's you enter tones. 

By default, the tones are entered as follows:
 - `-` is first tone. So `ma-` would be `mā`, which would give you `媽`
 - `/` is second tone. So `hui/` would be `huí`, which would give you `回`
 - `<` is third tone. So `ma<` would be `mǎ`, which would give you `馬`
 - `\` is fourth tone. So `hui\` would be `huì`, which would give you `會`.

#### Using Terra Pinyin with simplified chinese characters
 - Drop [this file](https://raw.githubusercontent.com/null-von-sushi/website-how-to-guoyu-shurufa/main/RIME/Windows_CN/terra_pinyin_cn.schema.yaml) to `C:\Program Files (x86)\RIME\Weasel\data` (note that the `Weasel` folder will likely be called `weasel-0.14` or whatever version you installed, instead of *just* 'Weasel'.
 - Drop [this file] at `%appdata%\Rime` and replace the existing file.
 - Then right click the tray icon for RIME, and select the option with (R) to restart.
