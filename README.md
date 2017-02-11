# Mecab dictionary for Artificial Khufu language (偽クフ語)

A [mecab](https://github.com/taku910/mecab) dictionary for Artificial Khufu language (偽クフ語) used in the book [白と黒のとびら](http://www.utp.or.jp/bd/4-13-063357-0.html).

## Build

```
$ git clone git@github.com:kuy/khufu-dic.git
$ cd khufu-dic
$ /usr/local/libexec/mecab/mecab-dict-index -d dic -o dic
```

## Use

Example: ●●○●○●●○●○●○●●○●○

```
$ mecab -d dic -N10
●●○●○●●○●○●○●●○●○
●●○●	留まる,動詞
○●●	ならば,その他
○●○●○	黄色い,形容詞
●●○●○	青い,形容詞

●●○●	時,名詞
○●●	ならば,その他
○●○●○	黄色い,形容詞
●●○●○	青い,形容詞
```

## Example

- ○○○●○○○●○○●○●●○●○●●○●○○●●●○●●●●○○●●
- ●●○●○●●○●○●○●●○●○

## License

MIT

## Author

Yuki Kodama / [@kuy](https://twitter.com/kuy)