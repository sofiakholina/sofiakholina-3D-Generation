# Установка вручную / Manual install

**Русский** · [English](#english)

## 1. Скачайте модели по ссылкам

Только для своего workflow.

**3D-Gen_TripoSplat** (3.5 GB)

| Файл | Положить в |
|---|---|
| [triposplat_fp16.safetensors](https://huggingface.co/VAST-AI/TripoSplat/resolve/main/diffusion_models/triposplat_fp16.safetensors) | Comfy Desktop: `C:\Users\<имя пользователя>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\diffusion_models`<br>Portable: `<папка, куда вы распаковали Portable>\ComfyUI_windows_portable\ComfyUI\models\diffusion_models` |
| [dino_v3_vit_h.safetensors](https://huggingface.co/VAST-AI/TripoSplat/resolve/main/clip_vision/dino_v3_vit_h.safetensors) | Comfy Desktop: `C:\Users\<имя пользователя>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\clip_vision`<br>Portable: `<папка, куда вы распаковали Portable>\ComfyUI_windows_portable\ComfyUI\models\clip_vision` |
| [triposplat_vae_decoder_fp16.safetensors](https://huggingface.co/VAST-AI/TripoSplat/resolve/main/vae/triposplat_vae_decoder_fp16.safetensors) | Comfy Desktop: `C:\Users\<имя пользователя>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\vae`<br>Portable: `<папка, куда вы распаковали Portable>\ComfyUI_windows_portable\ComfyUI\models\vae` |
| [flux2-vae.safetensors](https://huggingface.co/VAST-AI/TripoSplat/resolve/main/vae/flux2-vae.safetensors) | Comfy Desktop: `C:\Users\<имя пользователя>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\vae`<br>Portable: `<папка, куда вы распаковали Portable>\ComfyUI_windows_portable\ComfyUI\models\vae` |
| [birefnet.safetensors](https://huggingface.co/Comfy-Org/BiRefNet/resolve/main/background_removal/birefnet.safetensors) | Comfy Desktop: `C:\Users\<имя пользователя>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\background_removal`<br>Portable: `<папка, куда вы распаковали Portable>\ComfyUI_windows_portable\ComfyUI\models\background_removal` |

**3D-Gen_Trellis** (7.5 GB)

| Файл | Положить в |
|---|---|
| [trellis_2_int8_convrot.safetensors](https://huggingface.co/Comfy-Org/TRELLIS.2/resolve/main/diffusion_models/trellis_2_int8_convrot.safetensors) | Comfy Desktop: `C:\Users\<имя пользователя>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\diffusion_models`<br>Portable: `<папка, куда вы распаковали Portable>\ComfyUI_windows_portable\ComfyUI\models\diffusion_models` |
| [dino_v3_L_naf_fp32.safetensors](https://huggingface.co/Comfy-Org/Pixal3D/resolve/main/clip_vision/dino_v3_L_naf_fp32.safetensors) | Comfy Desktop: `C:\Users\<имя пользователя>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\clip_vision`<br>Portable: `<папка, куда вы распаковали Portable>\ComfyUI_windows_portable\ComfyUI\models\clip_vision` |
| [trellis_2_shape_vae_bf16.safetensors](https://huggingface.co/Comfy-Org/Pixal3D/resolve/main/vae/trellis_2_shape_vae_bf16.safetensors) | Comfy Desktop: `C:\Users\<имя пользователя>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\vae`<br>Portable: `<папка, куда вы распаковали Portable>\ComfyUI_windows_portable\ComfyUI\models\vae` |
| [birefnet.safetensors](https://huggingface.co/Comfy-Org/BiRefNet/resolve/main/background_removal/birefnet.safetensors) | Comfy Desktop: `C:\Users\<имя пользователя>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\background_removal`<br>Portable: `<папка, куда вы распаковали Portable>\ComfyUI_windows_portable\ComfyUI\models\background_removal` |

**3D-Gen_Pixal_MV** (7.8 GB)

| Файл | Положить в |
|---|---|
| [pixal3d_multiview_int8_convrot.safetensors](https://huggingface.co/Comfy-Org/Pixal3D/resolve/main/diffusion_models/pixal3d_multiview_int8_convrot.safetensors) | Comfy Desktop: `C:\Users\<имя пользователя>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\diffusion_models`<br>Portable: `<папка, куда вы распаковали Portable>\ComfyUI_windows_portable\ComfyUI\models\diffusion_models` |
| [dino_v3_L_naf_fp32.safetensors](https://huggingface.co/Comfy-Org/Pixal3D/resolve/main/clip_vision/dino_v3_L_naf_fp32.safetensors) | Comfy Desktop: `C:\Users\<имя пользователя>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\clip_vision`<br>Portable: `<папка, куда вы распаковали Portable>\ComfyUI_windows_portable\ComfyUI\models\clip_vision` |
| [trellis_2_shape_vae_bf16.safetensors](https://huggingface.co/Comfy-Org/Pixal3D/resolve/main/vae/trellis_2_shape_vae_bf16.safetensors) | Comfy Desktop: `C:\Users\<имя пользователя>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\vae`<br>Portable: `<папка, куда вы распаковали Portable>\ComfyUI_windows_portable\ComfyUI\models\vae` |
| [birefnet.safetensors](https://huggingface.co/Comfy-Org/BiRefNet/resolve/main/background_removal/birefnet.safetensors) | Comfy Desktop: `C:\Users\<имя пользователя>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\background_removal`<br>Portable: `<папка, куда вы распаковали Portable>\ComfyUI_windows_portable\ComfyUI\models\background_removal` |

## 2. Скачайте ноды

[s_tools](https://github.com/sofiakholina/sofiakholina-s_tools/archive/refs/heads/main.zip): распакуйте, назовите папку `s_tools` и положите в:

- Comfy Desktop: `C:\Users\<имя пользователя>\AppData\Local\Comfy-Desktop\ComfyUI-Installs\ComfyUI\ComfyUI\custom_nodes`
- Portable: `<папка, куда вы распаковали Portable>\ComfyUI_windows_portable\ComfyUI\custom_nodes`

**Важно (!): внутри папки s_tools сразу должен быть набор файлов, а не ещё одна папка.**

## 3. Запуск

1. Откройте папку [workflows](workflows) и нажмите на нужный файл.
2. Справа над текстом файла нажмите значок скачивания (стрелка вниз, подсказка «Download raw file»).
3. Запустите ComfyUI и перетащите скачанный файл в его окно.

---

<a name="english"></a>
# Manual install

## 1. Download the models

Only for your workflow.

**3D-Gen_TripoSplat** (3.5 GB)

| File | Put into |
|---|---|
| [triposplat_fp16.safetensors](https://huggingface.co/VAST-AI/TripoSplat/resolve/main/diffusion_models/triposplat_fp16.safetensors) | Comfy Desktop: `C:\Users\<user name>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\diffusion_models`<br>Portable: `<folder where you unpacked Portable>\ComfyUI_windows_portable\ComfyUI\models\diffusion_models` |
| [dino_v3_vit_h.safetensors](https://huggingface.co/VAST-AI/TripoSplat/resolve/main/clip_vision/dino_v3_vit_h.safetensors) | Comfy Desktop: `C:\Users\<user name>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\clip_vision`<br>Portable: `<folder where you unpacked Portable>\ComfyUI_windows_portable\ComfyUI\models\clip_vision` |
| [triposplat_vae_decoder_fp16.safetensors](https://huggingface.co/VAST-AI/TripoSplat/resolve/main/vae/triposplat_vae_decoder_fp16.safetensors) | Comfy Desktop: `C:\Users\<user name>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\vae`<br>Portable: `<folder where you unpacked Portable>\ComfyUI_windows_portable\ComfyUI\models\vae` |
| [flux2-vae.safetensors](https://huggingface.co/VAST-AI/TripoSplat/resolve/main/vae/flux2-vae.safetensors) | Comfy Desktop: `C:\Users\<user name>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\vae`<br>Portable: `<folder where you unpacked Portable>\ComfyUI_windows_portable\ComfyUI\models\vae` |
| [birefnet.safetensors](https://huggingface.co/Comfy-Org/BiRefNet/resolve/main/background_removal/birefnet.safetensors) | Comfy Desktop: `C:\Users\<user name>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\background_removal`<br>Portable: `<folder where you unpacked Portable>\ComfyUI_windows_portable\ComfyUI\models\background_removal` |

**3D-Gen_Trellis** (7.5 GB)

| File | Put into |
|---|---|
| [trellis_2_int8_convrot.safetensors](https://huggingface.co/Comfy-Org/TRELLIS.2/resolve/main/diffusion_models/trellis_2_int8_convrot.safetensors) | Comfy Desktop: `C:\Users\<user name>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\diffusion_models`<br>Portable: `<folder where you unpacked Portable>\ComfyUI_windows_portable\ComfyUI\models\diffusion_models` |
| [dino_v3_L_naf_fp32.safetensors](https://huggingface.co/Comfy-Org/Pixal3D/resolve/main/clip_vision/dino_v3_L_naf_fp32.safetensors) | Comfy Desktop: `C:\Users\<user name>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\clip_vision`<br>Portable: `<folder where you unpacked Portable>\ComfyUI_windows_portable\ComfyUI\models\clip_vision` |
| [trellis_2_shape_vae_bf16.safetensors](https://huggingface.co/Comfy-Org/Pixal3D/resolve/main/vae/trellis_2_shape_vae_bf16.safetensors) | Comfy Desktop: `C:\Users\<user name>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\vae`<br>Portable: `<folder where you unpacked Portable>\ComfyUI_windows_portable\ComfyUI\models\vae` |
| [birefnet.safetensors](https://huggingface.co/Comfy-Org/BiRefNet/resolve/main/background_removal/birefnet.safetensors) | Comfy Desktop: `C:\Users\<user name>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\background_removal`<br>Portable: `<folder where you unpacked Portable>\ComfyUI_windows_portable\ComfyUI\models\background_removal` |

**3D-Gen_Pixal_MV** (7.8 GB)

| File | Put into |
|---|---|
| [pixal3d_multiview_int8_convrot.safetensors](https://huggingface.co/Comfy-Org/Pixal3D/resolve/main/diffusion_models/pixal3d_multiview_int8_convrot.safetensors) | Comfy Desktop: `C:\Users\<user name>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\diffusion_models`<br>Portable: `<folder where you unpacked Portable>\ComfyUI_windows_portable\ComfyUI\models\diffusion_models` |
| [dino_v3_L_naf_fp32.safetensors](https://huggingface.co/Comfy-Org/Pixal3D/resolve/main/clip_vision/dino_v3_L_naf_fp32.safetensors) | Comfy Desktop: `C:\Users\<user name>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\clip_vision`<br>Portable: `<folder where you unpacked Portable>\ComfyUI_windows_portable\ComfyUI\models\clip_vision` |
| [trellis_2_shape_vae_bf16.safetensors](https://huggingface.co/Comfy-Org/Pixal3D/resolve/main/vae/trellis_2_shape_vae_bf16.safetensors) | Comfy Desktop: `C:\Users\<user name>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\vae`<br>Portable: `<folder where you unpacked Portable>\ComfyUI_windows_portable\ComfyUI\models\vae` |
| [birefnet.safetensors](https://huggingface.co/Comfy-Org/BiRefNet/resolve/main/background_removal/birefnet.safetensors) | Comfy Desktop: `C:\Users\<user name>\AppData\Local\Comfy-Desktop\ComfyUI-Shared\models\background_removal`<br>Portable: `<folder where you unpacked Portable>\ComfyUI_windows_portable\ComfyUI\models\background_removal` |

## 2. Download the nodes

[s_tools](https://github.com/sofiakholina/sofiakholina-s_tools/archive/refs/heads/main.zip): unzip, name the folder `s_tools` and put it into:

- Comfy Desktop: `C:\Users\<user name>\AppData\Local\Comfy-Desktop\ComfyUI-Installs\ComfyUI\ComfyUI\custom_nodes`
- Portable: `<folder where you unpacked Portable>\ComfyUI_windows_portable\ComfyUI\custom_nodes`

**Important: the files must be directly inside the s_tools folder, not in another nested folder.**

## 3. Run

1. Open the [workflows](workflows) folder and click the file you need.
2. Above the file text on the right, click the download icon (down arrow, tooltip "Download raw file").
3. Start ComfyUI and drag the downloaded file into its window.
