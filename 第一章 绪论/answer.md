## 1.1

```lisp
版本空间包括训练集和假设空间
样本空间为:
1	青绿	蜷缩	浊响	是
2 	乌黑	稍蜷	沉闷	否
只取是好瓜，包括(色泽=青绿；根蒂=蜷缩；敲声=浊响)作为训练集
进行拓展，得到假设空间
    1 (色泽=青绿；根蒂=蜷缩；敲声=浊响)
    2 (色泽=*；根蒂=蜷缩；敲声=浊响)
    3 (色泽=青绿；根蒂=*；敲声=浊响)
    4 (色泽=青绿；根蒂=蜷缩；敲声=*)
    5 (色泽=*；根蒂=*；敲声=浊响)
    6 (色泽=*；根蒂=蜷缩；敲声=*)
    7 (色泽=青绿；根蒂=*；敲声=*)
    8 (色泽=*；根蒂=*；敲声=*)
由于8包含了坏瓜样本，故去掉，只取1-7作为版本空间：
    1 (色泽=青绿；根蒂=蜷缩；敲声=浊响)
    2 (色泽=*；根蒂=蜷缩；敲声=浊响)
    3 (色泽=青绿；根蒂=*；敲声=浊响)
    4 (色泽=青绿；根蒂=蜷缩；敲声=*)
    5 (色泽=*；根蒂=*；敲声=浊响)
    6 (色泽=*；根蒂=蜷缩；敲声=*)
    7 (色泽=青绿；根蒂=*；敲声=*)
```

## 1.2

**析合范式**表示多个合取式的析取

题目中假设空间可表示成：`4*4*4+1=65`  种，这种情况就是按照 `k=1`条件下产生的

而`k`的情况最大是有`2*3*3=19`种，这种情况下假设空间就只剩下 ` 1 ` 种情况了

## 1.3

不妨考虑同时去掉在相同属性条件下不同分类的数据，留下的数据就是没有误差的数据

## 1.4



