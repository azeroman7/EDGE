# Diffusion Models

This repository contains implementations of EDGE (Editable Dance Generation From Music), wave-to-video

## Git clone
```bash
git clone https://github.com/azeroman7/EDGE.git
```

## Install Environment via Anaconda (Recommended)
```bash
cd EDGE
conda create python=3.10 --name  edge -y
conda activate edge

pip install git+https://github.com/rodrigo-castellon/jukemirlib.git
pip install wandb

pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
#pip install torch torchvision torchaudio
pip install fvcore iopath
pip install --no-index --no-cache-dir pytorch3d -f https://dl.fbaipublicfiles.com/pytorch3d/packaging/wheels/py310_cu118_pyt201/download.html

pip install matplotlib einops p_tqdm

```
## Download ckpt
--> download checkpoint.pt from https://drive.google.com/file/d/1BAR712cVEqB8GR37fcEihRV_xOC-fZrZ/view

## Run script --> renders/*.mp4
```bash
./run.sh
```
