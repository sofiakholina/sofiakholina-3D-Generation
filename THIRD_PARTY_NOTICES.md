# Third-party notices

This repository (workflows, installer) is GPL-3.0. It uses or is based on the following third-party work.
Models and node packs are **not** included here: the installer downloads them from their original sources.

## Workflows

The workflows are based on the ComfyUI workflow templates by Comfy Org
(3d_triposplat_image_to_gaussian_splat, 3d_pixal3d_trellis2_image_to_model, 3d_pixal3d_multi_views):
https://github.com/Comfy-Org/workflow_templates

```
MIT License

Copyright (c) 2023-present Comfy Org

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Node packs (downloaded by the installer)

| Pack | Source | Version | License |
|---|---|---|---|
| s_tools | https://github.com/sofiakholina/sofiakholina-s_tools | 1.0.1 | GPL-3.0 |

All other nodes are built into ComfyUI (GPL-3.0).

## Models (downloaded by the installer)

| File | Source | License |
|---|---|---|
| triposplat_fp16.safetensors, triposplat_vae_decoder_fp16.safetensors | huggingface.co/VAST-AI/TripoSplat | MIT |
| flux2-vae.safetensors | huggingface.co/VAST-AI/TripoSplat (FLUX.2 VAE, Black Forest Labs) | Apache-2.0 |
| dino_v3_vit_h.safetensors | huggingface.co/VAST-AI/TripoSplat (DINOv3, Meta) | DINOv3 License (https://github.com/facebookresearch/dinov3/blob/main/LICENSE.md) |
| trellis_2_int8_convrot.safetensors, trellis_2_shape_vae_bf16.safetensors | huggingface.co/Comfy-Org/TRELLIS.2 (TRELLIS.2, Microsoft) | MIT |
| pixal3d_multiview_int8_convrot.safetensors | huggingface.co/Comfy-Org/Pixal3D | MIT |
| dino_v3_L_naf_fp32.safetensors | huggingface.co/Comfy-Org/Pixal3D (DINOv3, Meta) | DINOv3 License (https://github.com/facebookresearch/dinov3/blob/main/LICENSE.md) |
| birefnet.safetensors | huggingface.co/Comfy-Org/BiRefNet | MIT |
