## Don't use...

 - Baidu or Sogou, unless you like playing fast and loose with data security and privacy. Please think carefully about who's data you are putting at risk (contacts in your address book for example).

## Do use:

| IME                 | Can type pinyin   | Can *show* you pinyin          | Can punctuate correctly via touch |  Can punctuate correctly via physical keyboard |
|:--------------------|:------------------|:-------------------------------|:----------------------------------|:-----------------------------------------------|
| GBoard              | yes               | [yes](#the-pinyin-bugfeature)  | yes, but on second page           | no                                             |
| Google Zhuyin Input | yes               | no                             | ?                                 | ?                                              |

Correct punctuation refers to being able to type the quotation marks 「」mainly. Some apps show English/Simplified Chinese quotes first ("") and have the correct 「」on the second page, wile others do not have it at all.

If unsure which to install, know that you can also just install both. They're free and don't take much space. It's also possible to use GBoard as your main keyboard, but then switch to Zhuyin Input temporarily if you need a function from it, or vice versa.

Note: RIME technically does exist for Android too, but the UI/UX is awful. Gboard is a better experience for now.

- [Gboard](#gboard)
  - [Installation](#installing-gboard)
  - [Customization](#configuring-gboard)
  - [Enabling Pinyin Bug]([#enabling-the-pinyin-bug)
- [Google Zhuhyin Input](#google-zhuyin-input)
  - [Installation](#installation)
 
### GBoard
For now, this is one of the better ones. Open Source replacement may exist in the future.

#### Installing Gboard
[Just download it from Google Play](https://play.google.com/store/apps/details?id=com.google.android.inputmethod.latin), though it may be preinstalled on your phone already

The installer & options are unfortunately only in chinese at the time of this writing ([although that should change soon](https://github.com/rime/weasel/pull/900)). You can use google lens / google translate's camera feature for now. Once installed it has probably the best IME you can get.

#### The Pinyin Bug/Feature

The main reason you should use it is because it has a really really cool bug we can use if we're learning Mandarin: It can really quickly show you pinyin + tones for words you're typing!

For example, you're trying to type "Bubble Tea", but you only vaguely remember the word. 
 
*"Something with a Z ... then another Z? But I know the last two words are nai3 cha2!"*

So normally you might type `zznaicha` and tap the first suggestion: `珍珠奶茶`. But how does that help you learn the word or tone? 
Well, with Gboard you can *tap and hold* the suggestion to show the pinyin. 

<details> <summary> This is what it looks like <b>(click to open)</b> </summary>
 
![Gboard-bug](https://raw.githubusercontent.com/null-von-sushi/website-how-to-guoyu-shurufa/main/assets/gboard-bug.png)

</details>

#### Enabling the pinyin bug

- Go into the Gboard options and add both Chinese Traditional/Chinese Simplified (whichever you're learning preferred one), and Cantonese (Cantonese is it's own language, it's not shown under "Chinese").
- Once added, go into the Cantonese settings and enable the "Romanisation" layout (it used to be called Jyutping, and might still be called that if you haven't updated the app)
- In the Romanisation layout preferences, enable the "show canonical romanisation" option.
- Now go to any text window, switch to Cantonese (粵語拼音)
- Type `o`, then and tap-and-hold the first suggestion: `我`. It should show you `ngo` above the character now.
- Now switch to mandarin and try typing `nihao`, then tap and hold again. It should show you `ni3 hao3`.
- If everything so far works correctly, you can go back into Gboard settings and remove Cantonese (the "show caninical romanisation" option seems to apply to Mandarin too, despite there not being a setting for it under the Chinese language layouts).

### Google Zhuyin Input
Part of a set of older legacy IMEs that Google deprecated. Despite no longer being in active development, it still works and can still be downloaded. 

Some people prefer Google Zhuyin Input's automatic word suggestions, and it has the advantage of not just allowing you to very quickly switch between english & chinese, but within chinese also between pinyin, zhuyin, handwriting and cangjie. This can be very useful if you have native-speaker-friends who might not know pinyin/zhuyin, so you can quickly switch to handwriting mode and hand your phone to them when asking "what character is that".

The disadvantages will be the lack of Material You theming, no custom dictionary entries and no 'pinyin bug' that Gboard has.

####Installation
[Google Zhuyin Input on Google Play](https://play.google.com/store/apps/details?id=com.google.android.apps.inputmethod.zhuyin)
