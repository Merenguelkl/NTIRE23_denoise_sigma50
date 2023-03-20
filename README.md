# [NTIRE 2023 Challenge on Image Denoising](https://cvlai.net/ntire/2023/) @ [CVPR 2023](https://cvpr2023.thecvf.com/)

Team ID: 18

Team Name: IMCgo

Contact email address: klliu21@m.fudan.edu.cn

### Create Environment

```
conda create -n DDT python=3.8
conda activate DDT

pip3 install torch torchvision torchaudio
pip install timm einops opencv-python matplotlib
```

### Test

```CUDA_VISIBLE_DEVICES=0 python test_demo.py --data_dir [data_dir] --save_dir [save_dir] --model_id 18```

