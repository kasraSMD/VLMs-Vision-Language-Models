<div align="center">

# 👁️ Vision-Language Models (VLMs)

### Hands-on notebooks: CLIP, multimodal inference, video understanding, and VLM fine-tuning

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/🤗_Transformers-FFD21E)
![TRL](https://img.shields.io/badge/TRL-SFT_%7C_DPO_%7C_GRPO_%7C_MPO-orange)
![Unsloth](https://img.shields.io/badge/Unsloth-Fast_Fine--Tuning-blueviolet)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

---

## 📖 About

A practical, notebook-driven guide to **Vision-Language Models**. The series starts with contrastive image-text models (CLIP, SigLIP), moves on to modern multimodal models for captioning, detection, and video understanding, and finishes with fine-tuning VLMs using SFT, DPO, GRPO, and MPO.

| Area | What you'll find |
|---|---|
| 🔍 **CLIP & Embeddings** | Joint image-text embeddings and zero-shot classification |
| 💬 **Inference & Understanding** | Captioning (English and Persian), object detection, multimodal chat, and video |
| 🔧 **Fine-Tuning (SFT)** | Domain adaptation for OCR, radiology, and grounding |
| 🎯 **Preference & RL Alignment** | DPO, GRPO, and MPO on compact VLMs |

---

## 🗂️ Notebooks

| # | Notebook | Description | Category |
|:-:|---|---|---|
| 01 | [`01_CLIP_Embeddings_with_clip-vit-base-patch32.ipynb`](./01_CLIP_Embeddings_with_clip-vit-base-patch32.ipynb) | Image and text embeddings with CLIP (ViT-B/32) | 🔍 CLIP & Embeddings |
| 02 | [`02_Zero-Shot-Classification-CLIP_with_clip-vit-base-patch32.ipynb`](./02_Zero-Shot-Classification-CLIP_with_clip-vit-base-patch32.ipynb) | Zero-shot image classification with CLIP | 🔍 CLIP & Embeddings |
| 03 | [`03_Inference_with_(multilingual)_SigLIP_a_better_CLIP_model.ipynb`](./03_Inference_with_%28multilingual%29_SigLIP_a_better_CLIP_model.ipynb) | Inference with (multilingual) SigLIP, an improved CLIP-style model | 🔍 CLIP & Embeddings |
| 04 | [`04_English-Image-Captioning_with_Qwen2.5-VL-3B-Instruct.ipynb`](./04_English-Image-Captioning_with_Qwen2.5-VL-3B-Instruct.ipynb) | English image captioning with Qwen2.5-VL-3B-Instruct | 💬 Inference & Understanding |
| 05 | [`05_Persian-Image-Captioning_with_PTIR.ipynb`](./05_Persian-Image-Captioning_with_PTIR.ipynb) | Persian image captioning with PTIR | 💬 Inference & Understanding |
| 06 | [`06_Object-Detection_with_unsloth_Qwen2.5-VL-7B-Instruct.ipynb`](./06_Object-Detection_with_unsloth_Qwen2.5-VL-7B-Instruct.ipynb) | Object detection with Qwen2.5-VL-7B-Instruct via Unsloth | 💬 Inference & Understanding |
| 07 | [`07_Multimodal-LLMs-Gemma3.ipynb`](./07_Multimodal-LLMs-Gemma3.ipynb) | Multimodal inference with Gemma 3 | 💬 Inference & Understanding |
| 08 | [`08_Multimodal_apple_FastVLM-0.5B.ipynb`](./08_Multimodal_apple_FastVLM-0.5B.ipynb) | Multimodal inference with Apple FastVLM-0.5B | 💬 Inference & Understanding |
| 09 | [`09_Video-understanding_with_Qwen2.5-VL-7B-Instruct.ipynb`](./09_Video-understanding_with_Qwen2.5-VL-7B-Instruct.ipynb) | Video understanding with Qwen2.5-VL-7B-Instruct | 💬 Inference & Understanding |
| 10 | [`10_Fine-tuning-SFT_granite-vision-3.1-2b-preview_with_TRL.ipynb`](./10_Fine-tuning-SFT_granite-vision-3.1-2b-preview_with_TRL.ipynb) | Supervised fine-tuning (SFT) of Granite Vision 3.1 2B with TRL | 🔧 Fine-Tuning (SFT) |
| 11 | [`11_Vision-Fine-Tuning_LaTeX-OCR_gemma-3-4b-pt_with_Unsloth.ipynb`](./11_Vision-Fine-Tuning_LaTeX-OCR_gemma-3-4b-pt_with_Unsloth.ipynb) | LaTeX OCR: fine-tuning Gemma 3 4B with Unsloth | 🔧 Fine-Tuning (SFT) |
| 12 | [`12_Vision-Fine-Tuning_Radiology_Llama-3.2-11B-Vision-Instruct_with_unsloth.ipynb`](./12_Vision-Fine-Tuning_Radiology_Llama-3.2-11B-Vision-Instruct_with_unsloth.ipynb) | Radiology: fine-tuning Llama-3.2-11B-Vision-Instruct with Unsloth | 🔧 Fine-Tuning (SFT) |
| 13 | [`13_VLM-Fine-Tuning_Object-Detection-Grounding_paligemma2-3b-pt-448.ipynb`](./13_VLM-Fine-Tuning_Object-Detection-Grounding_paligemma2-3b-pt-448.ipynb) | Object detection and grounding: fine-tuning PaliGemma 2 (3B, 448px) | 🔧 Fine-Tuning (SFT) |
| 14 | [`14_VLM_Fine-Tuning_DPO_SmolVLM-Instruct_with_TRL_QLoRA.ipynb`](./14_VLM_Fine-Tuning_DPO_SmolVLM-Instruct_with_TRL_QLoRA.ipynb) | DPO preference tuning of SmolVLM-Instruct with TRL and QLoRA | 🎯 Preference & RL Alignment |
| 15 | [`15_VLM_Fine-Tuning_GRPO_Qwen2.5-VL-3B-Instruct_with_TRL_LoRA.ipynb`](./15_VLM_Fine-Tuning_GRPO_Qwen2.5-VL-3B-Instruct_with_TRL_LoRA.ipynb) | GRPO reinforcement learning on Qwen2.5-VL-3B-Instruct with TRL and LoRA | 🎯 Preference & RL Alignment |
| 16 | [`16_VLM_Fine-Tuning_MPO_Qwen2.5-VL-3B-Instruct_with_TRL_QLoRA.ipynb`](./16_VLM_Fine-Tuning_MPO_Qwen2.5-VL-3B-Instruct_with_TRL_QLoRA.ipynb) | Mixed Preference Optimization (MPO) on Qwen2.5-VL-3B-Instruct with TRL and QLoRA | 🎯 Preference & RL Alignment |

---

## 🧭 Learning Path

<div align="center">

<img src="./learning_path_vlm.svg" alt="VLM learning path: CLIP and SigLIP, Inference, Supervised Fine-Tuning, Alignment" width="100%"/>

</div>

| Stage | Notebooks | Focus |
|:-:|:-:|---|
| 1️⃣ | 01 – 03 | CLIP and SigLIP: image-text embeddings |
| 2️⃣ | 04 – 09 | Captioning, detection, multimodal chat, video |
| 3️⃣ | 10 – 13 | Supervised fine-tuning (OCR, radiology, grounding) |
| 4️⃣ | 14 – 16 | DPO, GRPO, MPO alignment |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/kasraSMD/VLMs-Vision-Language-Models.git
cd VLMs-Vision-Language-Models
```

### 2. Create an environment (recommended)

```bash
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
```

### 3. Install core dependencies

```bash
pip install torch torchvision transformers datasets peft trl accelerate bitsandbytes pillow jupyter
```

> 💡 Each notebook installs its own extras in the first cells (for example `unsloth` in notebooks 06, 11, and 12). Always check the top of a notebook before running it.

### 4. Launch Jupyter

```bash
jupyter notebook
```

> ☁️ **GPU strongly recommended.** The larger models (7B and 11B) in notebooks 06, 09, and 12 need a high-memory GPU. [Google Colab](https://colab.research.google.com/) or Kaggle works well. Some models, such as Gemma, Llama, and PaliGemma, may require accepting their license and logging in to Hugging Face (`huggingface-cli login`).

---

## 🧰 Tech Stack

- **[🤗 Transformers](https://huggingface.co/docs/transformers)**: model loading and inference
- **[TRL](https://huggingface.co/docs/trl)**: SFT, DPO, GRPO, and MPO training
- **[PEFT](https://huggingface.co/docs/peft)**: LoRA and QLoRA adapters
- **[Unsloth](https://github.com/unslothai/unsloth)**: memory-efficient, faster fine-tuning
- **[bitsandbytes](https://github.com/bitsandbytes-foundation/bitsandbytes)**: 4-bit quantization

## 🤖 Models Used

`CLIP ViT-B/32` · `SigLIP (multilingual)` · `Qwen2.5-VL (3B / 7B)` · `PTIR` · `Gemma 3` · `Apple FastVLM-0.5B` · `Granite Vision 3.1 2B` · `PaliGemma 2 (3B)` · `Llama-3.2-11B-Vision` · `SmolVLM-Instruct`

---

## 🎯 What You'll Learn

- ✅ Build joint image-text embeddings and run **zero-shot classification**
- ✅ Caption images in **English and Persian**
- ✅ Run **object detection**, multimodal chat, and **video understanding** with VLMs
- ✅ Fine-tune VLMs for specialized domains such as **LaTeX OCR** and **radiology**
- ✅ Teach models **grounding** and detection with PaliGemma 2
- ✅ Align VLMs with **DPO**, **GRPO**, and **MPO** using parameter-efficient methods

---

## 🤝 Contributing

Suggestions and improvements are welcome. Feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

---

<div align="center">

⭐ If you find this repository useful, please consider giving it a star! ⭐

Made with ❤️ by [kasraSMD](https://github.com/kasraSMD)

</div>
