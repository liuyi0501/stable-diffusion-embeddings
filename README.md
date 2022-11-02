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

效果图都是按照如下TAG生成的
>{best quality}, {{masterpiece}}, {highres}, original, extremely detailed wallpaper, {an extremely delicate and beautiful},2girls, arms_behind_back, bandaid, beach, bikini, bikini_top, black_bikini, blonde_hair, blue_eyes, blue_hair, bottomless, bow, breasts, day, hair_ornament, hairclip, horizon, long_hair, looking_at_viewer, micro_bikini, multiple_girls, navel, navel_piercing, nipple_piercing, no_panties, ocean, outdoors, pasties, piercing, pussy, red_bow, shore, short_hair, smile, swimsuit, tattoo, twintails, water, art by 特定模型名称

>Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, artist name

>Steps: 28, Sampler: Euler a, CFG scale: 7.5, Seed: -1, Size: 512x768, Model hash: 925997e9, Seed resize from: -1x-1, Denoising strength: 0.75, Clip skip: 2, ENSD: 31337

<details>
  <summary>BadApple</summary>
  
  ![](https://github.com/liuyi0501/stable-diffusion-embeddings/raw/main/embeddings/badapple-200000.png)
</details>

<details>
  <summary>佩城</summary>
  
  ![](https://github.com/liuyi0501/stable-diffusion-embeddings/raw/main/embeddings/petra-200000.png)
</details>
