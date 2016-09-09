# Google Translate Alfred Workflow

## Author

* Hashman
* Blog: [http://coosos.blogspot.tw/](http://coosos.blogspot.tw/)
* Blog: [http://hashman-blog.logdown.com/](http://hashman-blog.logdown.com/)

## Change Log

* 2016.09.09 - v1.1.0
    1. Change Stichoza/google-translate-php to composer package

* 2016.07.09 - v1.0.0
	1. Google Translate main function.
	2. Translate English to Traditional Chinese by default.
	3. Set default source/target translate Language code.

## Installation

Just double click on `Google Translate.alfredworkflow` file and it will import in your Alfred app automatically.


## Usage

### Language code usage

Translate supported languages [here](https://cloud.google.com/translate/v2/translate-reference#supported_languages).

_Note: Please use "tw" as the Traditional Chinese Language code "zh-TW"._

### Basic Useage
```
1. Open Alfred console
2. type "tranlate"
3. add space then type any sentance you want to translate
```
![](https://dl.dropboxusercontent.com/u/33150136/markdown/github/google%20translate%20alfred/useage.jpg)

### set default source language

If you don't set any default source language code, it will be english(en)

```
1. Open alfred console
2. type "trsdlan" [translate default source language]
3. add space then type the language code
```

### set default target language

If you don't set any default target language code, it will be Traditional Chinese(tw)

```
1. Open alfred console
2. type "trtdlan" [translate default target language]
3. add space then type the language code
```

## Reference

1. [Github Project: google-translate-php by Stichoza](https://github.com/Stichoza/google-translate-php)
