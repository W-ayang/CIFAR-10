# CIFAR-10 数据集（数据无缺省值）

## 1 数据集介绍

CIFAR-10 数据集由 10 个类别的 60000 张 32x32 彩色图像组成，每个类别 6000 张图像。有50000张训练图像和10000张测试图像。数据集分为 5 个训练批次和 1 个测试批次，每个批次有 10000 张图像。测试批次包含从每个类别中随机选择的 1000 张图像。训练批次以随机顺序包含剩余图像，但某些训练批次可能包含来自一个类别的图像多于另一类别的图像。其中，训练批次恰好包含每个类别的 5000 张图像。

- **文件格式：**文件包含5个训练批次核一个测试批次，每个批次有10000张图像。测试批次包含从每个类别中**随机**选择的 1000 张图像。训练批次随机顺序包含剩余图像，但某些训练批次可能包含来自一个类别的图像多于另一类别的图像。其中，训练批次恰好包含每个类别的 5000 张图像。

- **每个图像的格式：**32 × 32 彩色图像；

- **类别：**✈️(飞机)、🚗(汽车)、🐦(鸟)、🐈(猫)、🦌(鹿)、🐶(狗)、🐸(青蛙)、🐎(马)、🚢(船)、🚛(卡车)；

以下是数据集中的类别，以及每个类别的 10 张随机图像：

| 飞机 | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/airplane1.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/airplane2.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/airplane3.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/airplane4.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/airplane5.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/airplane6.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/airplane7.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/airplane8.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/airplane9.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/airplane10.png) |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 汽车 | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/automobile1.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/automobile2.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/automobile3.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/automobile4.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/automobile5.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/automobile6.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/automobile7.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/automobile8.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/automobile9.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/automobile10.png) |
| 鸟   | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/bird1.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/bird2.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/bird3.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/bird4.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/bird5.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/bird6.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/bird7.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/bird8.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/bird9.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/bird10.png) |
| 猫   | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/cat1.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/cat2.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/cat3.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/cat4.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/cat5.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/cat6.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/cat7.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/cat8.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/cat9.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/cat10.png) |
| 鹿   | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/deer1.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/deer2.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/deer3.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/deer4.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/deer5.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/deer6.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/deer7.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/deer8.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/deer9.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/deer10.png) |
| 狗   | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/dog1.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/dog2.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/dog3.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/dog4.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/dog5.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/dog6.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/dog7.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/dog8.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/dog9.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/dog10.png) |
| 青蛙 | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/frog1.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/frog2.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/frog3.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/frog4.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/frog5.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/frog6.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/frog7.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/frog8.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/frog9.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/frog10.png) |
| 马   | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/horse1.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/horse2.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/horse3.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/horse4.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/horse5.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/horse6.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/horse7.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/horse8.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/horse9.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/horse10.png) |
| 船   | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/ship1.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/ship2.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/ship3.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/ship4.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/ship5.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/ship6.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/ship7.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/ship8.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/ship9.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/ship10.png) |
| 卡车 | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/truck1.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/truck2.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/truck3.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/truck4.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/truck5.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/truck6.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/truck7.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/truck8.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/truck9.png) | ![img](http://www.cs.toronto.edu/~kriz/cifar-10-sample/truck10.png) |

## 2 数据集加载

```python
# python3版本
def unpickle(file): 
    import pickle 
    with open(file, 'rb') as fo: 
        dict = pickle.load(fo,encoding='bytes') 
    return dict
```

通过这种方式加载，每个批处理文件都包含一个包含以下元素的字典：

- **data ——** `uint8`的`10000x3072` [numpy](http://numpy.scipy.org/)数组。数组的每一行存储一个 `32x32` 彩色图像。前 `1024` 个条目包含红色通道值，接下来的 `1024` 个条目包含绿色通道值，最后 `1024` 个条目包含蓝色通道值。图像按行优先顺序存储，因此数组的前 `32` 个条目是图像第一行的红色通道值。
- **labels** —— `0-9` 范围内 `10000` 个数字的列表。索引 `$i$` 处的数字表示数组`data`中第 `$i$ `个图像的标签。

该数据集包含另一个文件，名为`ches.meta`。它也包含一个 Python 字典对象。它有以下条目：

- **label_names** —— 一个 `10` 元素列表，为上述**标签数组中的数字标签提供有意义的名称。**

  ```python
  # 例如:
  label_names[0] == "airplane"、label_names[1] == "automobile"等。
  ```

## 3 code.ipynb 查看数据的具体情况

```python
import matplotlib.pyplot as plt

def unpickle(file): 
    import pickle 
    with open(file, 'rb') as fo: 
        dict = pickle.load(fo,encoding='bytes') 
    return dict

print("="*50)
print("字典里的内容:")
data1 = unpickle("data_batch_1")
print(data1.keys())

# batch_label 里面存的内容
print("="*50)
print("batch_label 里面存的内容:")
batch_label = data1[b'batch_label'].decode('utf-8')
print(f"batch_label: {batch_label}")

# 每个键对应值的内容
for key, value in data1.items():
    key_str = key.decode('utf-8')
    type_info = f"type: {type(value)}"
    
    if isinstance(value, list):
        print(f"key: {key_str}, {type_info}")
        print(f"  list_en: {len(value)}")
        print(f"  前5个: {value[:5]}")
    elif isinstance(value, dict):
        print(f"key: {key_str}, {type_info}")
        print(f"  dict_keys: {str(value.keys())}")
    elif hasattr(value, 'shape'):
        print(f"key: {key_str}, {type_info}")
        print(f"  shape: {value.shape}")
        print(f"  前5个: \n{value[:5]}")
    else:
        print(f"key: {key_str}, {type_info}")

    print("="*50)
```

## 4 数据集出处

[Learning Multiple Layers of Features from Tiny Images, Alex Krizhevsky, Technical Report, Computer Science Department, University of Toronto, 2009.](https://archive.ics.uci.edu/dataset/691/cifar+10)

