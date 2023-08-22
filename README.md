# 🚀 openaiapi

用于openai的api域名中转到cloudfare pages的中转服务 🌐

## 🛠 使用方法
1. 先点击点击 [fork](https://github.com/XingYu-Zhong/openaiapi/fork) 按钮创建一个新的代码库。🍴
2. 然后去到 [cloudfare](https://dash.cloudflare.com/) pages 创建一个pages项目，然后把代码库中的代码复制到pages项目中，然后就可以使用了 🌪
   ![01.png](img%2F01.png)
   ![02.png](img%2F02.png)
   ![03.png](img%2F03.png)
   ![04.png](img%2F04.png)
   ![05.png](img%2F05.png)
   ![06.png](img%2F06.png)
   ![07.png](img%2F07.png)

## 📝 使用说明
使用的时候需要替换openai的api域名为：把官方接口的https://api.openai.com 替换为 https://xxx.pages.dev 即可 👌

Python 调用可以这样 👩‍💻:
```python
import os
os.environ['OPENAI_API_BASE']='https://xxx.pages.dev/v1'
```
这样就完成系统的域名替换了，可以正常使用了 🎊

如果不在代码中设置环境变量，也可以在系统环境变量中设置 OPENAI_API_BASE，这样也可以正常使用 ✨

比如在 windows 系统中，可以在系统环境变量中设置 OPENAI_API_BASE，这样就可以正常使用了 🖥

🌍 环境变量设置

1️⃣ 第一步，按下“win+r”键，打开运行框 🪟

2️⃣ 第二步，输入命令“control system” 📝

3️⃣ 第三步，在控制面板主页，打开“高级系统设置” ⚙️

4️⃣ 第四步，在高级系统设置界面，选择“环境变量”选项 🔄

5️⃣ 第五步，根据需求进行设置 ✅ 

参考

https://github.com/opentdp/openai-chat
