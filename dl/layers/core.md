全连接层

全连接层实现了output = activation\(dot\(input, kernel\) + bias\)

全连接的的神经网络层。

---

激活层

对输出使用激活函数。单一层对神经网络输出施加一个激活函数。

---

Dropout层

对输入数据进行适当的丢弃

---

Flatten

对输入进行Flatten，不影响batch 大小

---

Reshape

对输出重新定义唯独。

---

Permute

根据一定的模型改变输入序列

---

RepeatVector

重复输入n次

---

Lambda

自定义层，嵌入自定义的表达式。

---

softmax层

---

$$softmax(x)_i=\frac {exp(x_i)}{\sum_{j}exp(x_j)} $$

tensorflow中定义的基本层，通常是对某一个NN的输出进行转化，转化成各个输出的概率。

![](/assets/layers-softmax.png)

