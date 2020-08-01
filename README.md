# Text Renderer
生成OCR 字符识别的训练数据


## 参考代码

[https://github.com/Sanster/text_renderer](https://github.com/Sanster/text_renderer)


## 安装依赖
```
pip3 install -r requirements.txt
```


## 修改配置文件

修改 `configs/default.yaml` 文件里面的内容


## 添加字体文件

`data/fonts` 字体文件存放目录

`data/fonts_list` 指定使用那些字体


## 添加数据文件

将文本文件添加到 `data/corpus/` 目录西面


## 生成图片和label 文件
```
python3 main.py --num_img=10
```
