# AnyText(非官方实现)

# 安装


```
#0. clone project
git clone https://github.com/MaletteAI/anytext.git

cd anytext

#1. install torch

pip install torch==2.2.2 torchvision==0.17.2 torchaudio==2.2.2 --index-url https://download.pytorch.org/whl/cu121

#2. install requirements

pip install -r requirements.txt

```

# 下载模型

进入 models 目录

```
cd models
```

下载必选模型

```
git clone https://www.modelscope.cn/iic/cv_anytext_text_generation_editing.git anytext_models
```

# 使用

## 本地调试

```

python main.py

```

## 启动 API 服务

```
python app.py
```

访问：http://localhost:8080/docs

![](docs/images/api-ref.png)

点击 "Try it out" 测试效果

# Credit to

+ [AnyText](https://github.com/tyxsspa/AnyText) 官方项目
+ [IOPaint](https://github.com/Sanster/IOPaint) 代码参考

# Other Things
you can contact me at Twitter: https://twitter.com/jinchanzx
