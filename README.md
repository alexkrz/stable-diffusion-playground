# Stable Diffusion using Huggingface

Setup repo:

1.) Install miniconda

2.) Run `conda env create -f environment.yml`

3.) Download Stable Diffusion model checkpoint from https://huggingface.co/runwayml/stable-diffusion-v1-5 into the `checkpoints/` directory with the following commands:

```
git lfs install
git clone https://huggingface.co/runwayml/stable-diffusion-v1-5
```

4.) Execute pipeline: `python pipeline.py`

