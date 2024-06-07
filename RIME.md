#### Using Terra Pinyin (地球拼音） in RIME
If you want to be able to type not just `hao` and get a whole list of Hanzi, but be able to specify *which* `hao` you want (for example, `hao4` which among others would give you `號`), you will want to use Terra Pinyin. It's like normal pinyin you already know, supports typing just the first letter and have it suggest the correct sentence (for example: `jttqhh` might suggest `今天天氣很好`), but it also let's you enter tones. 

By default, the tones are entered as follows:
 - `-` is first tone. So `ma-` would be `mā`, which would give you `媽`
 - `/` is second tone. So `hui/` would be `huí`, which would give you `回`
 - `<` is third tone. So `ma<` would be `mǎ`, which would give you `馬`
 - `\` is fourth tone. So `hui\` would be `huì`, which would give you `會`.

### Customizing RIME
You can find the files for RIME at `C:/Program Files/RIME/Weasel/` on Windows.
The `.schema.yaml` files are the ones that define a layout. With a text editor you can change a few things (such as disabling the shift button from enabling alphabet mode, forcing ROC standard characters rather than variant characters used over in Singapore or mainland China (為 instead of 爲 etc.), and more. 

