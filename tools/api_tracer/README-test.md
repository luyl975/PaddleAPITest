# API Tracer 测试说明

## 环境依赖

```bash
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
pip install transformers huggingface_hub

# image video
pip install diffusers decord

# moonshotai
pip install tiktoken blobfile

# RWKV
pip install flash-linear-attention

# baidu
pip install sentencepiece moviepy

# OpenGVLab
pip install timm

# MonkeyOCR
# refer to https://github.com/Yuliang-Liu/MonkeyOCR/blob/main/docs/install_cuda_pp.md#install-with-cuda-support

# Wan-AI
pip install ftfy

# Keye
pip install "keye-vl-utils[decord]==1.0.0"

# DeepSeek-ai/Janus-Pro-1B
# need clone https://github.com/deepseek-ai/Janus/tree/main
pip install attrdict timm

# ByteDance-Seed/BAGEL-7B-MOT
# need clone https://github.com/ByteDance-Seed/BAGEL
pip install opencv-python flash-attn
```
