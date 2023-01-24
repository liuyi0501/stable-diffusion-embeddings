# 欢迎liuyi0501的stable-diffusion-embeddings库
来自b站Up“2481asd”（https://space.bilibili.com/46453008）
如果方便，请star本仓库或b站一键三连
非常感谢
这里存放着我个人训练的模型

本模型均基于Stable Diffusion。
Stable Diffusion checkpoint: animefull.ckpt [925997e9]

`embeddings`文件夹下是选择出来的的`，pt`模型

`textual_inversion`文件夹下是训练过程中的中间版本

官方webui项目地址：
>https://github.com/AUTOMATIC1111/stable-diffusion-webui

# 更新历史：
- 2022.11.10
  - 风格模型
    - ICELAKE ICECAKE-40000.pt
- 2022.11.09
  - 风格模型
    - MだSたろう mda-starou-33500.pt
- 2022.11.07
  - 风格模型
    - hiten hiten-95000.pt
- 2022.11.06
  - 人物模型（存疑）
    - もり苔 画师的精灵 morikoke_elf-20000.pt
  - 风格模型
    - Sakimi Chan sakimichan-100000.pt
- 2022.11.05
  - 人物模型
    - 铃兰 铃兰-12500.pt
- 2022.11.03
  - 风格模型
    - 粉红黏黏怪 粉红黏黏怪-100000.pt
    - 大猫板蓝根 大猫板蓝根-100000.pt
- 2022.11.02
  - 风格模型
    - 佩城 petra-200000.pt
    - badapple badapple-200000.pt
    - aki99 aki99-100000.pt

## 要饭
![](https://pic1.imgdb.cn/item/6366837016f2c2beb1de7a5f.jpg)
![](https://pic1.imgdb.cn/item/6366841316f2c2beb1e06651.png)
每天租GPU服务器训练得花30多，帮忙减点赤字罢
如果有训练的需要，可以加我QQ(2042456367)代训练。

# 目前包含模型
## 人物模型
- もり苔 画师的精灵 (2022.11.06):
  - **NSFW**
  - 本来是想练画风的，但是因为偷懒，把もり苔 画师的《[Morikoke] Chijoku no Mori -Elf Kanraku- ch.1-10》下下来当训练集了，于是模型自然而然地在产精灵。
- 铃兰(2022.11.05):
  - 训练下来，感觉AI还是不太理解垂耳狐狸。
  - 你可以加点TAG类似：**铃兰, loli, fox_ears, fox_tail, nine talis,  multiple_tails, look_to_viewer, very low height**
  
## 风格模型
- ICECAKE(2022.11.10):
  - 光影很好
  - 因为训练集中有脏脚底的拆分，所以最好在**Negative Tag**中加入**dirty**
- MだSたろう(2022.11.09):
  - **NSFW**
- Hiten (2022.11.07):
  - 人物风格比较像了，但是那种淡淡的，若隐若现的样式还需要TAG补充
- Sakimi Chan(2022.11.06):
  - 使用的时候建议多试几次
  - 我测试下来，设置
    - 8-14 steps
    - DDIM 
  - 会更符合目标画风
- 粉红黏黏怪(2022.11.03):
  - **NSFW**
- 大猫板蓝根(2022.11.03):
  - **NSFW**
- aki99(2022.11.02):
  - **NSFW**
  - 个人认为画风很立体
- 佩城(2022.11.02):
  - **NSFW** 
- badapple(2022.11.02):
  - **NSFW**
  - 似乎眼睛和手还有点问题，可以自行训练一番。
  - 用的时候如果不要NSFW，记得多打点负面tag，不然很容易出NSFW

后续有更新也会往这里上传

# 效果图
<details>
  <summary>人物</summary>
  <details>
    <summary>もり苔 画师的精灵 </summary>
  
  ![](https://github.com/liuyi0501/stable-diffusion-embeddings/raw/main/embeddings/morikoke_elf-20000.png)
  </details>

<details>
  <summary>铃兰</summary>
  
  ![](https://github.com/liuyi0501/stable-diffusion-embeddings/raw/main/embeddings/铃兰-12500.png)
  </details>
</details>

<details>
  <summary>ICECAKE</summary>
  
  ![](https://github.com/liuyi0501/stable-diffusion-embeddings/raw/main/embeddings/ICECAKE-40000.png)
</details>

<details>
  <summary>MだSたろう</summary>
  
  ![](https://github.com/liuyi0501/stable-diffusion-embeddings/raw/main/embeddings/mda-starou-33500.png)
</details>

<details>
  <summary>Hiten</summary>
  
  ![](https://github.com/liuyi0501/stable-diffusion-embeddings/raw/main/embeddings/hiten-95000.png)
</details>

<details>
  <summary>Sakimi Chan</summary>
  
  ![](https://github.com/liuyi0501/stable-diffusion-embeddings/raw/main/embeddings/sakimichan-100000.png)
</details>

<details>
  <summary>BadApple</summary>
  
  ![](https://github.com/liuyi0501/stable-diffusion-embeddings/raw/main/embeddings/badapple-200000.png)
</details>

<details>
  <summary>佩城</summary>
  
  ![](https://github.com/liuyi0501/stable-diffusion-embeddings/raw/main/embeddings/petra-200000.png)
</details>

<details>
  <summary>aki99</summary>
  
  ![](https://github.com/liuyi0501/stable-diffusion-embeddings/raw/main/embeddings/aki99-100000.png)
</details>

<details>
  <summary>粉红黏黏怪</summary>
  
  ![](https://github.com/liuyi0501/stable-diffusion-embeddings/raw/main/embeddings/粉红黏黏怪-100000.png)
</details>

<details>
  <summary>大猫板蓝根</summary>
  
  ![](https://github.com/liuyi0501/stable-diffusion-embeddings/raw/main/embeddings/大猫板蓝根-100000.png)
</details>
