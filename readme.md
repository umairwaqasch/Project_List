# Ultimate ComfyUI & AI Resources Hub

A comprehensive master list of ComfyUI custom nodes, core AI frameworks, video/audio models, cloud pipelines, checkpoints, and workflow utilities.

---

## 📋 Table of Contents
* [🚀 FLUX Ecosystem](#-flux-ecosystem)
* [🎬 Video Generation, Animation & Inversion](#-video-generation-animation--inversion)
* [🗣️ Talking Heads, Lip-Sync & Portrait Driving](#️-talking-heads-lip-sync--portrait-driving)
* [🎭 Face Swapping, Try-on & Identity Control](#-face-swapping-try-on--identity-control)
* [🎨 Image Editing, Inpainting & Background Masking](#-image-editing-inpainting--background-masking)
* [🔊 TTS (Text-to-Speech) & Audio Frameworks](#-tts-text-to-speech--audio-frameworks)
* [🛠️ ComfyUI Frameworks, Utilities & Logic Nodes](#️-comfyui-frameworks-utilities--logic-nodes)
* [🌐 Standalone UI Engines & Local Environment Deployments](#-standalone-ui-engines--local-environment-deployments)
* [☁️ Cloud Platforms, External APIs & Script Environments](#️-cloud-platforms-external-apis--script-environments)
* [📖 Workflows, Video Tutorials & Graphic Plugins](#-workflows-video-tutorials--graphic-plugins)
* [🧱 ComfyUI Checkpoints & Base Models](#-comfyui-checkpoints--base-models)
* [📦 Framework Dependencies, Libraries & Miscellaneous Bookmarks](#-framework-dependencies-libraries--miscellaneous-bookmarks)

---

## 🚀 FLUX Ecosystem

Advanced controllers, prompt builders, and optimization nodes tailored to the FLUX architecture.

| Resource / Repository | Description |
| :--- | :--- |
| [ComfyUI-Fluxpromptenhancer](https://github.com/marduk191/ComfyUI-Fluxpromptenhancer) | Local pipeline to optimize, detail, and expand prompt syntax for FLUX models. |
| [ComfyUI-nunchaku](https://github.com/nunchaku-tech/ComfyUI-nunchaku) | Fast backend integration implementation targeting accelerated FLUX inference. |
| [FluxKontextCreator](https://github.com/ShmuelRonen/FluxKontextCreator) | Context management node stack optimizing multi-stage prompt generations. |
| [ComfyUI_PuLID_Flux_ll](https://github.com/lldacing/ComfyUI_PuLID_Flux_ll) | Implementation of PuLID identity retention training for FLUX models. |
| [ComfyUI-Fluxtapoz](https://github.com/logtd/ComfyUI-Fluxtapoz) | Advanced canvas layout, structural alignment, and image blending utilities for FLUX. |
| [FLUX-Prompt-Generator (HF)](https://huggingface.co/spaces/gokaygokay/FLUX-Prompt-Generator) | Online interface space designed to structure functional FLUX prompt styling. |
| [FLUX LoRA Collections (HF)](https://huggingface.co/collections/prithivMLmods/flux-lora-collections-66dd5908be2206cfaa8519be) | Massive aggregation repository containing fine-tuned style and character FLUX LoRAs. |

## 🎬 Video Generation, Animation & Inversion

Text-to-video wrappers, frame interpolation processing, and advanced motion transfer adapters.

| Resource / Repository | Description |
| :--- | :--- |
| [Wan2.1 Core Repository](https://github.com/Wan-Video/Wan2.1) | Official source files, architecture details, and standalone configurations for Wan2.1. |
| [Wan2GP Getting Started](https://github.com/deepbeepmeep/Wan2GP/blob/main/docs/GETTING_STARTED.md) | In-depth deployment logic and execution parameters targeting Wan model extensions. |
| [Awesome-Training-Free-WAN2.1-Editing](https://github.com/KyujinHan/Awesome-Training-Free-WAN2.1-Editing) | Curated collection of training-free structural editing methods for Wan2.1 setups. |
| [ComfyUI-CogVideoXWrapper](https://github.com/kijai/ComfyUI-CogVideoXWrapper) | Highly flexible integration node for running CogVideoX motion paths inside graphs. |
| [EasyAnimate](https://github.com/aigc-apps/EasyAnimate) | End-to-end multi-frame generative workspace targeting long video iterations. |
| [UniAnimate](https://github.com/ali-vilab/UniAnimate) | Image-to-video human animation pipeline mapping reference skeletal maps cleanly. |
| [ComfyUI-MVAdapter](https://github.com/huanngzh/ComfyUI-MVAdapter) | Multi-view camera configuration nodes helping construct spatial frame passes. |
| [FramePack](https://github.com/lllyasviel/FramePack) | High-speed structural video manipulation and packed canvas array utilities by lllyasviel. |
| [LongCat-Video-Avatar GGUF (HF)](https://huggingface.co/vantagewithai/LongCat-Video-Avatar-ComfyUI-GGUF) | Quantized model checkpoints for generating video avatars in VRAM-constrained systems. |
| [ComfyUI-MimicMotion](https://github.com/AIFSH/ComfyUI-MimicMotion) | High-fidelity motion imitation wrapper for precise character animation. |

## 🗣️ Talking Heads, Lip-Sync & Portrait Driving

Audio-driven face animation, structural landmark transfers, and deep temporal lip-sync arrays.

| Resource / Repository | Description |
| :--- | :--- |
| [ComfyUI-Hallo](https://github.com/AIFSH/ComfyUI-Hallo) | Audio-driven portrait animation custom node pipeline mapping detailed facial changes. |
| [ComfyUI_Hallo2](https://github.com/smthemex/ComfyUI_Hallo2) | Alternative updated custom node container supporting advanced Hallo2 functions. |
| [ComfyUI_EchoMimic](https://github.com/smthemex/ComfyUI_EchoMimic) | Node wrapper orchestrating audio and landmark-driven expressive face animations. |
| [X-Portrait Core Engine](https://github.com/bytedance/X-Portrait) | Official ByteDance framework mapping video driver frames over target characters. |
| [ComfyUI-X-Portrait-Nodes](https://github.com/akatz-ai/ComfyUI-X-Portrait-Nodes) | Unofficial node configuration integrating X-Portrait model execution structures. |
| [ComfyUI-AdvancedLivePortrait](https://github.com/PowerHouseMan/ComfyUI-AdvancedLivePortrait) | Advanced portrait rigging environment featuring precise landmark translation logic. |
| [LatentSync Engine](https://github.com/bytedance/LatentSync) | ByteDance lip-sync asset framework fixing audio-to-mouth layout temporal drift. |
| [video-retalking](https://github.com/OpenTalker/video-retalking) | Rigging tool modifying video lip layout assets to fit completely new audio layers. |
| [SadTalker Repository](https://github.com/OpenTalker/SadTalker) | Classic structural facial expression system via audio or pre-baked landmark maps. |
| [Comfyui-SadTalker Wrapper](https://github.com/haomole/Comfyui-SadTalker) | Simple node translation bringing native SadTalker functionalities to the canvas. |
| [InfiniteTalk Codebase](https://github.com/MeiGen-AI/InfiniteTalk/tree/comfyui) | ComfyUI setup files for establishing looping talking-head generations. |
| [InfiniteTalk Weights (HF)](https://huggingface.co/MeiGen-AI/InfiniteTalk/tree/main/comfyui) | Required model assets and weights directory to run InfiniteTalk structures. |
| [fantasy-talking](https://github.com/Fantasy-AMAP/fantasy-talking) | Audio-to-video speech translation framework optimizing portrait generation outputs. |

## 🎭 Face Swapping, Try-on & Identity Control

High-fidelity deepfake swaps, virtual apparel layering, and actor composition tools.

| Resource / Repository | Description |
| :--- | :--- |
| [FaceFusion](https://github.com/facefusion/facefusion) | Advanced, standalone GUI and command-line tool for high-speed face swapping. |
| [ComfyUI-DeepFuze](https://github.com/SamKhoze/ComfyUI-DeepFuze) | Highly integrated face replacement logic packaged natively for standard graphs. |
| [IMAGDressing](https://github.com/muzishen/IMAGDressing) | Identity-preserving virtual garment modeling and clothing replacement pipelines. |
| [ComfyUI-StoryMaker](https://github.com/tanglaoya321/ComfyUI-StoryMaker) | Character preservation nodes maintaining facial likeness across varying background prompts. |
| [MagicClothing](https://github.com/ShineChen1024/MagicClothing) | Detailed garment-driven image rendering framework optimizing custom clothing assets. |
| [SDXL_EcomID_ComfyUI](https://github.com/alimama-creative/SDXL_EcomID_ComfyUI) | Alimama Creative's identity-retention pipeline specialized for e-commerce generation. |

## 🎨 Image Editing, Inpainting & Background Masking

Object removal, canvas expansion, precision mask generation, and upscaling restoration models.

| Resource / Repository | Description |
| :--- | :--- |
| [ComfyUI_ProPainter_Nodes](https://github.com/daniabib/ComfyUI_ProPainter_Nodes) | Video inpainting and optical-flow object tracking nodes to erase elements cleanly. |
| [ComfyUI_DiffuEraser](https://github.com/smthemex/ComfyUI_DiffuEraser) | Specialized inpainting node optimized to remove intricate artifacts from layout sheets. |
| [ComfyUI-RMBG](https://github.com/1038lab/ComfyUI-RMBG) | Integration of Bria AI's background removal model for automated alpha masking. |
| [FlowEdit](https://github.com/fallenshock/FlowEdit) | Text-guided image editing system utilizing flow-based diffusion inversion loops. |
| [AnyDoor for Windows](https://github.com/sdbds/AnyDoor-for-windows) | Windows-native deployment setup instructions for zero-shot object layout generation. |
| [ComfyUI_InvSR](https://github.com/yuvraj108c/ComfyUI_InvSR) | High-fidelity image restoration, sharpening, and ultra-resolution processing node. |

## 🔊 TTS (Text-to-Speech) & Audio Frameworks

Voice synthesis, zero-shot audio cloning, and cross-platform speech-generation sandboxes.

| Resource / Repository | Description |
| :--- | :--- |
| [ComfyUI-KokoroTTS](https://github.com/benjiyaya/ComfyUI-KokoroTTS) | Native high-speed voice synthesis utilizing lightweight, natural Kokoro weights. |
| [DJZ-KokoroTTS](https://github.com/MushroomFleet/DJZ-KokoroTTS) | Alternative layout node configuration mapping special parsing parameters to Kokoro. |
| [ComfyUI-F5-TTS](https://github.com/niknah/ComfyUI-F5-TTS) | Flow-matching text-to-speech framework optimized for high-fidelity voice clones. |
| [ComfyUI-Qwen-TTS](https://github.com/flybirdxx/ComfyUI-Qwen-TTS) | Text-to-Speech module generation backed by Alibaba’s language-audio framework. |
| [tts-generation-webui](https://github.com/rsxdalv/tts-generation-webui) | Standalone UI containing multi-model audio generation blocks (Bark, XTTS, MusicGen). |
| [xtts-webui](https://github.com/daswer123/xtts-webui) | Dedicated environment for fine-tuning Coqui XTTS weights and audio generation testing. |
| [Bark Engine (JonathanFly)](https://github.com/JonathanFly/bark) | Suno Bark audio transformer setups handling background sound effects and music hooks. |
| [Bark Engine Releases (Fictiverse)](https://github.com/Fictiverse/bark/releases) | Pre-compiled packages and release pipelines for local Bark environment loads. |
| [unsilence](https://github.com/lagmoellertim/unsilence) | Python tool designed to programmatically strip dead audio/silence gaps from tracks. |

## 🛠️ ComfyUI Frameworks, Utilities & Logic Nodes

Object detection masking, graph programming adjustments, asset managers, and execution filters.

| Resource / Repository | Description |
| :--- | :--- |
| [adetailer (After Detailer)](https://github.com/Bing-su/adetailer) | Detection and automatic regional re-rendering script targeting faces, eyes, and hands. |
| [ComfyUI-YoloWorld-EfficientSAM](https://github.com/ZHO-ZHO-ZHO/ComfyUI-YoloWorld-EfficientSAM) | Real-time object zero-shot detection bound with segment-anything custom masking. |
| [ComfyUI-Copilot](https://github.com/AIDC-AI/ComfyUI-Copilot) | Canvas-integrated AI assistant assisting graph assembly and layout generation. |
| [ComfyUI-Lora-Manager](https://github.com/willmiao/ComfyUI-Lora-Manager) | Visual dashboard interface allowing users to filter, sort, and tag their local LoRA folders. |
| [ComfyUI-OOP](https://github.com/0xRavenBlack/ComfyUI-OOP) | System adjustments implementing Object-Oriented programming habits into node arrays. |
| [ComfyUI-FLOAT](https://github.com/yuvraj108c/ComfyUI-FLOAT) | Precision math utilities processing logic control and floating-point data values. |
| [ComfyUI-SeqImageLoader](https://github.com/bruefire/ComfyUI-SeqImageLoader) | Batch frame loading scripts reading custom sequential folders for video pipelines. |
| [ComfyUI_AdvancedRefluxControl](https://github.com/kaibioinfo/ComfyUI_AdvancedRefluxControl) | Complex generation control nodes offering iterative generation feedback routing. |
| [ComfyUI_ExtraModels (Efficient)](https://github.com/Efficient-Large-Model/ComfyUI_ExtraModels) | Expansive model configuration patch resolving non-native diffusion loading loops. |
| [ComfyUI_ExtraModels (Lawrence)](https://github.com/lawrence-cj/ComfyUI_ExtraModels) | Alternative configuration set expanding system capability into unrecognized model types. |
| [ControlAltAI-Nodes](https://github.com/gseth/ControlAltAI-Nodes) | Canvas enhancement blocks packaging everyday image formatting helpers. |
| [ComfyUI-iTools](https://github.com/MohammadAboulEla/ComfyUI-iTools) | Image translation utility nodes fixing workflow execution sequence steps. |
| [ComfyUI_Isulion](https://github.com/Isulion/ComfyUI_Isulion) | Workspace macro setups and personalized pipeline shortcut configuration assets. |
| [ComfyUI-Mana-Nodes](https://github.com/ForeignGods/ComfyUI-Mana-Nodes) | Custom canvas block formatting processing variable routing and organizational layers. |
| [kaytool](https://github.com/kk8bit/kaytool) | Automation helper utility scripts configuring core local generation structures. |
| [comfyui-plugins](https://github.com/WASasquatch/comfyui-plugins) | Legacy custom script library optimizing legacy backend data formatting hooks. |
| [ComfyUI-Chatterbox](https://github.com/wildminder/ComfyUI-Chatterbox) | API and local framework mapping text-conversational engines onto canvas outputs. |
| [ComfyUI-DreamO](https://github.com/ToTheBeginning/ComfyUI-DreamO) | Experimental model processing node blocks managing visual content parsing layers. |
| [ComfyUI_Human_Parts](https://github.com/metal3d/ComfyUI_Human_Parts) | Visual segmentation node dividing human body outlines into usable parsing masks. |
| [comfyui_face_parsing (Ryuukeisyou)](https://github.com/Ryuukeisyou/comfyui_face_parsing) | Semantic segmentation module resolving fine face boundaries into detailed layout maps. |
| [ComfyUI_FaceParsing (Bwebbfx)](https://github.com/Bwebbfx/ComfyUI_FaceParsing) | Structural face feature isolation code sorting individual elements out for masking. |

## 🌐 Standalone UI Engines & Local Environment Deployments

Package managers, alternative interfaces, and independent local generation software.

| Resource / Repository | Description |
| :--- | :--- |
| [StabilityMatrix](https://github.com/LykosAI/StabilityMatrix) | Package manager organizing, downloading, and deploying multiple independent generative UIs. |
| [Ollama](https://github.com/ollama/ollama) | Lightweight system running and interacting with Large Language Models (LLMs) locally. |
| [SwarmUI](https://github.com/mcmonkeyprojects/SwarmUI) | Multi-backend generation web frontend leveraging ComfyUI execution logic. |
| [Fooocus](https://github.com/lllyasviel/Fooocus) | Streamlined local generation engine providing simplified, high-fidelity Midjourney styling. |
| [Muse-Studio](https://github.com/benjiyaya/Muse-Studio_) | Production-focused node interface workspace designed for studio-grade generative tools. |
| [In-Context-LoRA](https://github.com/ali-vilab/In-Context-LoRA) | Canvas generation architecture maintaining multi-concept layout consistency. |
| [Bagel Environment](https://github.com/ByteDance-Seed/Bagel) | ByteDance's generative canvas workspace organizing layout planning pipelines. |
| [MoneyPrinterV2](https://github.com/FujiwaraChoki/MoneyPrinterV2) | Automated content creation script building localized shorts/TikToks from simple scripts. |

## ☁️ Cloud Platforms, External APIs & Script Environments

Cloud sandboxes, execution APIs, runtime actors, and cloud-hosted environments.

* [Fal.ai Models](https://fal.ai/models) — Cloud compute developer platform running image, text, and fast video endpoints.
* [MimicPC Pricing](https://www.mimicpc.com/pricing) — Browser-accessible cloud runtime environments deploying full instances of ComfyUI.
* [Apify Actor Runs](https://console.apify.com/actors/shu8hvrXbJbY3Eb9W/runs) — Automation platform sandbox monitoring automated worker scripts and API endpoints.
* [LTX Studio Script Platform](https://app.ltx.studio/start-from-script) — Video editing framework generating narrative visual story assets out of raw scripts.
* [FocalML](https://focalml.com/) — Machine learning pipeline checking and tracking system platform.
* [Kive AI Hub](https://kive.ai/heart-hacker?sessionId=e78107e7-9384-49a6-a1cd-5552fc8d5397) — Shared online collaboration dashboard staging generative visual workspaces.

## 📖 Workflows, Video Tutorials & Graphic Plugins

Educational guides, community hubs, pre-built template files, and design suite extensions.

* [ComfyUI Wiki - Workflows](https://comfyui-wiki.com/en/workflows) — Central resource index archiving verified community-built graph templates.
* [Wan 2.2 Video Generation Tutorial](https://www.stablediffusiontutorials.com/2025/08/wan-2.2-video-generation.html#b.-wan2.2-quantized-fp8-by-kijai) — Multi-step breakdown outlining quantized FP8 Wan setups via Kijai wrappers.
* [Benji's AI Playground (YouTube Video)](https://www.youtube.com/watch?v=6MS-KAnvTBg) — Video walk-through demonstrating custom node deployment steps.
* [Auto-Photoshop Stable Diffusion Plugin](https://github.com/AbdullahAlfaraj/Auto-Photoshop-StableDiffusion-Plugin) — Connects local stable diffusion rendering loops inside standard Adobe Photoshop projects.
* [Urdu-TTS Web Application](https://ahmedhanzala.github.io/urdu-tts/) — Targeted regional voice translation engine handling specialized phonetic text files.
* [Wyrde ComfyUI Workflows](https://github.com/wyrde/wyrde-comfyui-workflows/tree/main/hr-fix-upscale) — Graph templates prioritizing high-resolution repair loops and upscale steps.

## 🧱 ComfyUI Checkpoints & Base Models

Curated collection of high-fidelity open weights base models, fine-tunes, and stylistic checkpoints for SD 1.5, SDXL, and Turbo pipelines.

| Resource / Repository | Description |
| :--- | :--- |
| [Animagine XL V3](https://civitai.com/models/212426?modelVersionId=239306) | Premier anime-focused fine-tune model built on the SDXL architecture. |
| [Civitai Model 1545303](https://civitai.com/models/1545303?modelVersionId=1748507) | Modern generation fine-tune checkpoint tailored for complex illustration styles. |
| [Pony Diffusion V6 XL](https://civitai.com/models/297501?modelVersionId=357959) | Highly versatile SDXL model engineered for stylized, cartoon, and fine art prompt execution. |
| [DreamShaper XL](https://civitai.com/models/129922) | All-in-one photorealistic and semi-stylized foundation checkpoint derived from SDXL. |
| [MagMix Checkpoint](https://civitai.com/models/18523/magmix) | Popular aesthetic-driven Stable Diffusion 1.5 multi-model blend. |
| [AbsoluteReality Mix](https://civitai.com/models/81458?modelVersionId=132760) | High-fidelity photorealistic SD 1.5 checkpoint processing organic light maps well. |
| [ArteYou Style Model](https://civitai.com/models/83429/arteyou) | Highly stylized creative checkpoint emphasizing illustrative digital artwork finishes. |
| [Artius 1.5 Foundation](https://civitai.com/models/47691/artius-1-5) | Finetuned stable diffusion 1.5 core asset specialized in rendering cinematic scenery. |
| [CyberRealistic Base](https://civitai.com/models/15003/cyberrealistic) | Renowned photorealistic asset producing balanced textures, skin detail, and anatomy. |
| [Civitai Model 123605](https://civitai.com/models/123605) | Specialized multi-concept model configuration optimized for modern canvas logic. |
| [Juggernaut Engine](https://civitai.com/models/46422/juggernaut) | Legendary cinematic model series famed for prompt adherence and realistic grading. |
| [EpicRealism Fine-Tune](https://civitai.com/models/93028?modelVersionId=99169) | High-tier photographic SD 1.5 checkpoint eliminating typical generative noise structures. |
| [Realistic Vision V5](https://civitai.com/models/4201?modelVersionId=501240) | The definitive benchmark checkpoint for photorealism pipelines inside standard node runs. |
| [ToonYou Canvas Checkpoint](https://civitai.com/models/30240?modelVersionId=125771) | Richly blended 3D/2D animation checkpoint producing consistent comic profiles. |
| [CyberRealistic Upgraded Version](https://civitai.com/models/15003?modelVersionId=560903) | Alternative modern version patch updating model responses and prompt clarity profiles. |
| [RealVisXL V4.0 (HuggingFace)](https://huggingface.co/SG161222/RealVisXL_V4.0) | Top-tier hyper-realistic SDXL model engineered for commercial photographic output. |
| [SDXL Unstable Diffusers YamerMix](https://civitai.com/models/84040/sdxl-unstable-diffusers-yamermix) | Dynamic model configuration processing fluid, artistic multi-genre illustrations. |
| [WildCardX XL Turbo](https://civitai.com/models/293331/wildcardx-xl-turbo) | Fast step-distilled model variant yielding production frames in fewer inference runs. |
| [LEOSAM HelloWorld XL Variant](https://civitai.com/models/231258) | High-end photo-realistic rendering mix executing precise composition structures. |

## 📦 Framework Dependencies, Libraries & Miscellaneous Bookmarks

Core project code libraries, scheduling tools, references, and remaining browser saves.

* [Postiz App Scheduler](https://github.com/gitroomhq/postiz-app) — Open-source automation suite organizing social media scheduling loops.
* [PyTorch Torchvision Setup](https://github.com/pytorch/vision#installation) — Fundamental configuration and installation files for local computer vision libraries.
* [Flash Attention Setup](https://github.com/bdashore3/flash-attention) — Computational engine acceleration code blocks reducing local GPU processing memory overhead.
* [Anatomy360 Scan Dump](https://anatomy360.info/anatomy-scan-reference-dump/) — 3D body reference library material ideal for training spatial posing models.
* [ArtStation Community Dashboard](https://www.artstation.com/?sort_by=community&dimension=all) — Creative design asset and composition community repository.
* [Emailnator Disposable Generator](https://www.emailnator.com/) — Multi-use temporary testing address portal helper.
* [Presenton Dashboard](https://github.com/presenton/presenton) — Open structural content display tool.
* [NewBie Image Experiment Weights (HF)](https://huggingface.co/NewBie-AI/NewBie-image-Exp0.1) — Custom testing base checkpoint repository.