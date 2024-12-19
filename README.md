# StableDiffusion-TRT

```
git clone --recursive https://github.com/NVIDIA/TensorRT.git 
cd TensorRT/demo/Diffusion
pip3 install -r requirements.txt 
```

```
export HF_TOKEN=<your access token>
```

```
python3 demo_txt2img_sd3.py "A vibrant street wall covered in colorful graffiti" --hf-token=$HF_TOKEN
```
