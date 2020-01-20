---
layout: post
title: Translations and Languages Support
author: typora.io
category: reference
tags: [i18n]
typora-root-url: ../
date: 2018-02-10
---

## Supported Languages

+ Simplified Chinese by [abnerlee](https://github.com/abnerlee), [NoDotCat](https://github.com/NoDotCat), [HowardTangHw](https://github.com/HowardTangHw),  [Emphasia](https://github.com/Emphasia)
+ Traditional Chinese by [cyberrob](https://github.com/cyberrob)
+ Català (Catalan)
+ Čeština (Czech) by [byDave251](https://github.com/byDave251), [psimacek](https://github.com/byDave251)
+ Dansk (Danish)
+ Deutsch (German) by [rcvd](https://github.com/rcvd), Gert
+ ελληνικά (Greek) by [kiriakosv](https://github.com/kiriakosv)
+ English
+ Español (Spanish) by [thepiratejester](https://github.com/thepiratejester)
+ Français (French) by [MOrdinateur](https://github.comMOrdinateur)
+ Galego (Galician) by [nunhes](https://github.com/nunhes)
+ Hrvatski (Croatian) by [diomed](https://github.com/diomed)
+ Bahasa Indonesia by [snatalius](https://github.com/snatalius)
+ Italiana by  [starise](https://github.com/starise), [jethro17](https://github.com/jethro17) 
+ Japanese by [tomochan001](https://github.com/tomochan001) 
+ Korean by  [ryush00](https://github.com/ryush00),  [marigold9124](https://github.com/marigold9124)
+ Magyar (Hungarian) by [mocsa](https://github.com/mocsa)
+ Nederlands
+ Polski (Polish) by  [iriusturar](https://github.com/iriusturar)
+ Português (Brazil) by [akz92](https://github.com/akz92) 
+ Português (Portugal) by [camilo93](https://github.com/jcamilo93)
+ русский язык (Russian) by [dragomano](https://github.com/dragomano)
+ Schweizerdeutsch (Swiss German)
+ Slovenčina (Slovak)
+ Svenska (Swedish) by [FelixZY](https://github.com/FelixZY)
+ Tiếng Việt (Vietnamese) by [1234hdpa](https://github.com/1234hdpa)

To change language, use the Preference Panel > General > Language setting.

Note: The list above may be out of date; you could check all available languages or change the locale of Typora in the preference panel.

## How to Contribute

Please see <https://github.com/typora/Typora-i18n>.

If you can help translate Typora into other languages, we would very appreciate that.

### Improve existing translations

In Github, fork this project, change text resources and make a pull request.

### Add a new language Interface

1. Check our issue list to see if there's already someone else translating the text to your language. If not, open an issue to tell others that you doing the translation, in order to avoid duplicate work.
2. Fork this repo.
3. Create a folder named `{locale}.lproj`, `local` code should be picked from [locale-identifiers.csv](https://github.com/typora/Typora-i18n/blob/master/locale-identifiers.csv).
4. Copy `*.strings` files from `Base.lproj` to `{locale}.lproj`.
5. Open `*.strings` with any text/code editor, do the translation. Please also check the translation rules.
6. Make a pull request to us.
7. We will also appreciate if you leave any contact method, like email, in issues or in `*.strings` file after your translation, so we can reach you and, at least, give free license as rewards after we come out of beta. You could also email us directly if you do not want your email address public in Github.

### Translation rules

+ Translations in `Menu.strings` should follow <https://github.com/martnst/localize-mainmenu>.
+ If translation in the <https://github.com/martnst/localize-mainmenu> is not correct on Windows/Linux, add the correct one in `Menu-electron.strings`. (See zh-Hans.lproj as one example.)
+ Comment style `/* some words */` is supported, `// comment` is **NOT** supported.

### FAQ

> Can I test my translations?

Sorry… We do not support that. If you are not sure about the context of some original English text resource or have doubts about your translation, please feel free to contact us.

### Contact

Feel free to contact us via [hi@typora.io](mailto:hi@typora.io).
