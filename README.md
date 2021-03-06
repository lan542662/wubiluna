# wubiluna 五笔朙月流 #

**五笔朙月流输入法** （Wubiluna）是融合（混用）了五笔86和拼音的一种输入法。
因为用了中州韵的朙月拼音，所以称之为五笔朙月。当使用者输入时，会以五笔的候选字为优先。且同时也会出现拼音的候选字

## 更新 ##

* 2018-09-05 - 加入台湾繁体中文。导入八股文词汇。
* 2016-08-08 - 加入绘文字（Emoji）。如输入“``horse``”就会看到🐎。

## 提示 ##

若不知某字的五笔代码，可以使用反查。先输入“`` ` ``”符号，再输入拼音就可反查五笔的代码。结束时可输入“;”。

若不知某字的拼音，可以用五笔反查。先输入“`` `W ``”，再输入五笔就可反查字的拼音。结束时可输入“;”。

若要输入拼音而已，可以先输入“~”，之后的输入全是拼音。结束时可输入“;”。

若想输入符号，可以在输入“/”后，输入xl（希腊）、sx（数学）等。可参考symbols.yaml。

若知道五笔画（不是五笔），却不知道五笔的输入法，可以“`` `S ``”，再输入文字的hspnz（横竖撇捺折）来反查五笔。

## 繁体输入 ##

目前有两种繁体中文。两种繁体即台湾繁体和默认的繁体。若要输入繁体，可以使用 Rime 本身的组合键``Ctrl+` ``，然后按2，再做出其它选择即可。选项有：

1. 字型 → 汉字
2. 字型 → 漢字（臺）
3. 字型 → 漢字

使用者也可以用 Ctrl+Shift+4 来快速简繁转换。若通过组合键选择了台湾繁体，那简繁转换则会以台湾繁体为基础；若是选择了简体或是默认的繁体，转换时则是以默认的繁体为基础。

台湾繁体和默认的繁体差别如下：

- 台湾繁体：“為了”、“抬頭”
- 默认的繁体：“爲了”、“擡頭”

## 词典修改 ##

wubiluna.dict.yaml 里包含了一些emoji。使用者可根据自己的喜好来更改。

