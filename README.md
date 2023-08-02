## Flex,bisonを用いた字句解析及び構文解析による数式演算システム

入力された数式に対して字句解析、構文解析を行い演算の結果を出力する。

四則演算(+,-,*,/)及び、大小比較(<,>,<=,>=)、等価演算(==,!=)に対応している。

```
12+7
>> 19
(10+10)*2
>> 40
(1+2+3)*4<567
>> 1
12>17           
>> 0
11==11
>> 1
11==12
>> 0
11!=11
>> 0
11!=12
>> 1

```

何も入力をせずに改行を行うとこのプログラムは終了する。


* 動かし方
```
git clone git@github.com:mimic-asy/c_simple_compiler.git
make
./mycalc
```
 
  
