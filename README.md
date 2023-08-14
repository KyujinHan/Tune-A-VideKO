# Tune-A-VideKO :video_camera:🇰🇷  
<p align="center">
  <img src="./results/overview.gif" alt="animated"/>
</p>  
  
**One-shot video tuning with Korean-Stable Diffusion** [![Hugging Face Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue)]([https://huggingface.co/spaces/Tune-A-Video-library/Tune-A-Video-Training-UI](https://huggingface.co/kyujinpy/Tune-A-VideoKO-v1-5/tree/main))

# Introduction
- 한국어 기반 [stable-diffusion](https://arxiv.org/abs/2112.10752)을 활용하여 [Tune-A-Video](https://github.com/showlab/Tune-A-Video/tree/main)를 접목한 Tune-A-VideKO입니다!
- Bingsu님의 [CLIP-VIT](https://huggingface.co/Bingsu/clip-vit-large-patch14-ko/tree/main)를 활용한 [korean-stable-diffusion](https://huggingface.co/Bingsu/my-korean-stable-diffusion-v1-5)에서 감명을 받아 만들게 되었습니다.
  
# Setup
[Tune-A-Video](https://github.com/showlab/Tune-A-Video/tree/main)  
[Pytorch](https://pytorch.org/)==1.12.1  
🤗[Diffusers](https://huggingface.co/docs/diffusers/index)  
  
# Quick Start
```python
(coming soon...)
```
  
# Training and Inference Code
- (DreamBooth version coming soon...)  
- **[2023.08.15]**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1U7ON76oXw6Glz2BflnshuaOEuJF1A2z9?usp=sharing) 코드로 실행하실 수 있습니다
  
# Results
### Pretrained T2I (tune-a-video-v1-5) :baby_chick:  

<table class="center">
<tr>
  <td style="text-align:center;"><b>Input Video</b></td>
  <td style="text-align:center;" colspan="3"><b>Output Video</b></td>
</tr>
<tr>
  <td><img src="./results/v1-5/man-ski.gif"></td>
  <td><img src="./results/v1-5/video1.gif"></td>
  <td><img src="./results/v1-5/video2.gif"></td>              
  <td><img src="./results/v1-5/video3.gif"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;color:gray;">"A man is skiing"</td>
  <td width=25% style="text-align:center;">"미키 마우스가 눈 위에서 스키를 타고 있습니다”</td>
  <td width=25% style="text-align:center;">"외계인이 보드를 타고 있습니다"</td>
  <td width=25% style="text-align:center;">"한 남자가 모래 위에서 스키를 타고 있습니다"</td>
</tr>

<tr>
  <td><img src="./results/v1-5/rabbit.gif"></td>
  <td><img src="./results/v1-5/video4.gif"></td>
  <td><img src="./results/v1-5/video5.gif"></td>           
  <td><img src="./results/v1-5/video6.gif"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;color:gray;">"A rabbit is eating a watermelon on the table"</td>
  <td width=25% style="text-align:center;">"고양이가 해변에서 수박을 먹고 있습니다"</td>
  <td width=25% style="text-align:center;">"강아지가 오렌지를 먹고 있습니다"</td>
  <td width=25% style="text-align:center;">"강아지가 만화 스타일로 상자를 먹고 있습니다"</td>
</tr>

<tr>
  <td><img src=""></td>
  <td><img src=""></td>
  <td><img src=""></td>            
  <td><img src=""></td>
</tr>
<tr>
  <td width=25% style="text-align:center;color:gray;">"A jeep car is moving on the road"</td>
  <td width=25% style="text-align:center;">"A Porsche car is moving on the beach"</td>
  <td width=25% style="text-align:center;">"A car is moving on the road, cartoon style"</td>
  <td width=25% style="text-align:center;">"A car is moving on the snow"</td>
</tr>

<tr>
  <td><img src=""></td>
  <td><img src=""></td>
  <td><img src=""></td>            
  <td><img src=""></td>
</tr>
<tr>
  <td width=25% style="text-align:center;color:gray;">"A man is dribbling a basketball"</td>
  <td width=25% style="text-align:center;">"James Bond is dribbling a basketball on the beach"</td>
  <td width=25% style="text-align:center;">"An astronaut is dribbling a basketball, cartoon style"</td>
  <td width=25% style="text-align:center;">"A lego man in a black suit is dribbling a basketball"</td>
</tr>
</table>
  
### Pretrained T2I (tune-a-video-v2-base) :hatched_chick:  

### Pretrained T2I (tune-a-video-v2-1) :hatching_chick:  
  
### Pretrained T2I(tune-a-video-dreambooth) :chicken: (Coming soon...)  

# Pre-trained weights
  

# Acknowledgement
[Tune-A-Video](https://github.com/showlab/Tune-A-Video/tree/main)  
[SD](https://github.com/Stability-AI/stablediffusion)  
[DreamBooth](https://dreambooth.github.io/)  
[Bingsu's CLIP](https://huggingface.co/Bingsu/clip-vit-large-patch14-ko)  
