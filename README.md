# Tune-A-VideKO :video_camera:🇰🇷  
한국어 기반 One-shot video tuning with Stable Diffusion

# Introduction
- 한국어 기반 [stable-diffusion](https://arxiv.org/abs/2112.10752)을 활용하여 [Tune-A-Video](https://github.com/showlab/Tune-A-Video/tree/main)를 접목한 Tune-A-VideKO입니다!
- Bingsu님의 [CLIP-VIT](https://huggingface.co/Bingsu/clip-vit-large-patch14-ko/tree/main)를 활용한 [korean-stable-diffusion](https://huggingface.co/Bingsu/my-korean-stable-diffusion-v1-5)에서 감명을 받아 만들게 되었습니다.
  
# Setup
[Tune-A-Video](https://github.com/showlab/Tune-A-Video/tree/main)  
[Pytorch](https://pytorch.org/)==1.12.1

# Quick Start

# Training

# Inference

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
  <td><img src="https://tuneavideo.github.io/assets/data/rabbit-watermelon.gif"></td>
  <td><img src="https://tuneavideo.github.io/assets/results/tuneavideo/rabbit-watermelon/rabbit.gif"></td>
  <td><img src="https://tuneavideo.github.io/assets/results/tuneavideo/rabbit-watermelon/cat.gif"></td>              
  <td><img src="https://tuneavideo.github.io/assets/results/tuneavideo/rabbit-watermelon/puppy.gif"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;color:gray;">"A rabbit is eating a watermelon on the table"</td>
  <td width=25% style="text-align:center;">"A rabbit is <del>eating a watermelon</del> on the table"</td>
  <td width=25% style="text-align:center;">"A cat with sunglasses is eating a watermelon on the beach"</td>
  <td width=25% style="text-align:center;">"A puppy is eating a cheeseburger on the table, comic style"</td>
</tr>

<tr>
  <td><img src="https://tuneavideo.github.io/assets/data/car-turn.gif"></td>
  <td><img src="https://tuneavideo.github.io/assets/results/tuneavideo/car-turn/porsche-beach.gif"></td>
  <td><img src="https://tuneavideo.github.io/assets/results/tuneavideo/car-turn/car-cartoon.gif"></td>              
  <td><img src="https://tuneavideo.github.io/assets/results/tuneavideo/car-turn/car-snow.gif"></td>
</tr>
<tr>
  <td width=25% style="text-align:center;color:gray;">"A jeep car is moving on the road"</td>
  <td width=25% style="text-align:center;">"A Porsche car is moving on the beach"</td>
  <td width=25% style="text-align:center;">"A car is moving on the road, cartoon style"</td>
  <td width=25% style="text-align:center;">"A car is moving on the snow"</td>
</tr>

<tr>
  <td><img src="https://tuneavideo.github.io/assets/data/man-basketball.gif"></td>
  <td><img src="https://tuneavideo.github.io/assets/results/tuneavideo/man-basketball/bond.gif"></td>
  <td><img src="https://tuneavideo.github.io/assets/results/tuneavideo/man-basketball/astronaut.gif"></td>              
  <td><img src="https://tuneavideo.github.io/assets/results/tuneavideo/man-basketball/lego.gif"></td>
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
  

# Acknowledgement
[Tune-A-Video](https://github.com/showlab/Tune-A-Video/tree/main)
[SD](https://github.com/Stability-AI/stablediffusion)
[DreamBooth](https://dreambooth.github.io/)
