# 欢迎liuyi0501的stable-diffusion-embeddings库

这里存放着我个人训练的模型

本模型均基于Stable Diffusion。
Stable Diffusion checkpoint: animefull.ckpt [925997e9]

`embeddings`文件夹下是选择出来的的`.pt`模型

`textual_inversion`文件夹下是训练过程中的中间版本

官方webui项目地址：
>https://github.com/AUTOMATIC1111/stable-diffusion-webui

# 使用方法

把.pt放到embeddings里，生成图片时加个“art by 文件名”的tag，例如art by badapple-200000
# 更新历史：
- 2022.11.02
  - 风格模型
    - 佩城 petra-200000.pt
    - badapple badapple-200000.pt
    
# 目前包含模型

风格模型：

- 佩城(2022.11.02):
  - **NSFW** 
- badapple(2022.11.02):
  - **NSFW**
  - 似乎眼睛和手还有点问题，可以自行训练一番。
  - 用的时候如果不要NSFW，记得多打点负面tag，不然很容易出NSFW

后续有更新也会往这里上传

# 效果图
<details>
  <summary>BadApple</summary>
  
  ![](https://github.com/liuyi0501/stable-diffusion-embeddings/raw/main/embeddings/badapple-200000.png)
</details>

<details>
  <summary>佩城</summary>
  
  ![](https://github.com/liuyi0501/stable-diffusion-embeddings/raw/main/embeddings/petra-200000.png)
</details>
