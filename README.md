<h2 align="center">Audio-Visual Intelligence in Large Foundation Models: A Comprehensive Survey</h2>
<div align="center">

<!-- [![arXiv](https://img.shields.io/badge/arXiv-2503.12605-b31b1b?style=plastic&logo=arxiv)](https://arxiv.org/abs/2503.12605)
[![Maintenance](https://img.shields.io/badge/Maintenance-FF9800?style=plastic&logo=maintenance&logoColor=white)](https://github.com/yaotingwangofficial/Awesome-AVI/issues)
[![Discussion](https://img.shields.io/badge/Discussion-Open-brightgreen?style=plastic&logo=discussion&logoColor=white)](https://github.com/yaotingwangofficial/Awesome-AVI/discussions) -->

</div>

> 💡 *This repository contains a curated list of papers and resources for Audio-Visual Intelligence (AVI), organized following our comprehensive survey.*
> 📌 *Please feel free to open an issue or PR for any possibly missed related work.*

<p align="center">
  <img src="assets/cover_image.jpg" width="100%">
</p>

# 🎇 Introduction

Audio-Visual Intelligence (AVI) studies how machines can jointly perceive, generate, and interact with the world through sight and sound. In the era of large foundation models, AVI has rapidly evolved from task-specific alignment to unified omni-modal systems that integrate perception, generation, and embodied interaction within a single framework.

This survey provides the first systematic and in-depth treatment of AVI within the foundation-model paradigm, organizing the landscape around three interconnected pillars: **perception**, **generation**, and **interaction**. We consolidate the methodological foundations and review representative methods, datasets, and benchmarks across task families.

<p align="center">
  <img src="assets/avi_timeline.jpg" width="100%">
</p>

---

### 🔥 Updates
> 2026-05-05: We release the **Awesome-AVI repo**.

---

# 📕 Table of Contents

- [🔧 Foundation Techniques](#🔧-foundation-techniques)
  - [Representation-Centric Methods](#representation-centric-methods)
  - [Generation-Centric Methods](#generation-centric-methods)
  - [LLM-Centric Methods](#llm-centric-methods)
- [👁️ Audio-Visual Perception](#👁️-audio-visual-perception)
  - [Audio-Visual Pixel Perception](#audio-visual-pixel-perception)
  - [Audio-Visual Content Understanding](#audio-visual-content-understanding)
  - [Audio-Visual Logical Reasoning](#audio-visual-logical-reasoning)
- [🎨 Audio-Visual Generation](#🎨-audio-visual-generation)
  - [Conditional Audio/Visual Generation](#conditional-audiovisual-generation)
  - [Audio-Visual Cross-Modal Generation](#audio-visual-cross-modal-generation)
  - [Joint Audio-Visual Generation](#joint-audio-visual-generation)
- [🤝 Audio-Visual Interaction](#🤝-audio-visual-interaction)
  - [Interactive Audio-Visual Conversation](#interactive-audio-visual-conversation)
  - [Interactive Audio-Visual Embodiment](#interactive-audio-visual-embodiment)
<!-- - [❤️ Citation](#%EF%B8%8F-citation)
- [⭐️ Star History](#%EF%B8%8F-star-history) -->

---

# 🔧 Foundation Techniques

This section introduces foundational techniques developed in the era of large foundation models, which provide key technical pathways toward achieving universal audio-visual intelligence, including **representation-centric**, **generation-centric**, and **LLM-centric** methods.

## Representation-Centric Methods

### Audio-Visual Feature Extraction and Representation

+ [Look, listen and learn](https://arxiv.org/abs/1710.07260)
+ [Cooperative learning of audio and video models from self-supervised synchronization](https://arxiv.org/abs/1805.09363)
+ [Self-supervised learning by cross-modal audio-video clustering](https://arxiv.org/abs/2004.02186)
+ [Audio-visual instance discrimination with cross-modal agreement](https://arxiv.org/abs/2006.08363)
+ [Vatt: Transformers for multimodal self-supervised learning from raw video, audio and text](https://arxiv.org/abs/2104.11178)
+ [Es3: Evolving self-supervised learning of robust audio-visual speech representations](https://arxiv.org/abs/2403.10803)
+ [Wav2clip: Learning robust audio representations from clip](https://arxiv.org/abs/2205.10362)
+ [Imagebind: One embedding space to bind them all](https://arxiv.org/abs/2305.05665)
+ [EquiAV: leveraging equivariance for audio-visual contrastive learning](https://arxiv.org/abs/2403.09502)
+ [Sequential contrastive audio-visual learning](https://arxiv.org/abs/2407.05782)
+ [MAViL: masked audio-video learners](https://arxiv.org/abs/2212.08071)
+ [Self-supervised audio-visual representation learning with relaxed cross-modal synchronicity](https://arxiv.org/abs/2301.03404)
+ [Cross-modal label contrastive learning for unsupervised audio-visual event localization](https://arxiv.org/abs/2304.00557)
+ [Attention bottlenecks for multimodal fusion](https://arxiv.org/abs/2107.00135)
+ [Improving audio-visual segmentation with bidirectional generation](https://arxiv.org/abs/2403.12117)
+ [Learning audio-visual speech representation by masked multimodal cluster prediction](https://arxiv.org/abs/2201.02184)
+ [AVF-MAE++: Scaling Affective Video Facial Masked Autoencoders via Efficient Audio-Visual Self-Supervised Learning](https://arxiv.org/abs/2509.24214)

### Audio-Visual Variational Auto-Encoding and Reconstruction

+ [Auto-encoding variational bayes](https://arxiv.org/abs/1312.6114)
+ [Stochastic backpropagation and approximate inference in deep generative models](https://arxiv.org/abs/1401.4082)
+ [Multimodal Variational Autoencoder: A Barycentric View](https://arxiv.org/abs/2504.07891)
+ [A multimodal dynamical variational autoencoder for audiovisual speech representation learning](https://arxiv.org/abs/2405.18003)

### Audio-Visual Discrete Tokenization

+ [Soundstream: An end-to-end neural audio codec](https://arxiv.org/abs/2107.03312)
+ [Neural discrete representation learning](https://arxiv.org/abs/1711.00937)
+ [High Fidelity Neural Audio Compression](https://arxiv.org/abs/2406.04631)
+ [High-fidelity audio compression with improved rvqgan](https://arxiv.org/abs/2306.06546)
+ [WavTokenizer: an Efficient Acoustic Discrete Codec Tokenizer for Audio Language Modeling](https://arxiv.org/abs/2407.02891)
+ [Hubert: Self-supervised speech representation learning by masked prediction of hidden units](https://arxiv.org/abs/2106.07447)
+ [Codec does matter: Exploring the semantic shortcoming of codec for audio language model](https://arxiv.org/abs/2503.18156)
+ [Spark-TTS: An Efficient LLM-Based Text-to-Speech Model with Single-Stream Decoupled Speech Tokens](https://arxiv.org/abs/2503.01710)
+ [Moshi: a speech-text foundation model for real-time dialogue](https://arxiv.org/abs/2410.00037)
+ [Taming Transformers for High-Resolution Image Synthesis](https://arxiv.org/abs/2012.09841)
+ [Language Model Beats Diffusion--Tokenizer is Key to Visual Generation](https://arxiv.org/abs/2310.05737)
+ [Scaling the Codebook Size of VQGAN to 100,000 with a Utilization Rate of 99\%](https://arxiv.org/abs/2405.02892)
+ [Addressing representation collapse in vector quantized models with one linear layer](https://arxiv.org/abs/2405.02892)
+ [Tokenflow: Unified image tokenizer for multimodal understanding and generation](https://arxiv.org/abs/2503.07227)
+ [Divot: Diffusion Powers Video Tokenizer for Comprehension and Generation](https://arxiv.org/abs/2503.12658)
+ [Speechgpt: Empowering large language models with intrinsic cross-modal conversational abilities](https://arxiv.org/abs/2305.11000)
+ [AnyGPT: Unified Multimodal LLM with Discrete Sequence Modeling](https://arxiv.org/abs/2402.12226)

## Generation-Centric Methods

### Generative Adversarial Networks

+ [Generative adversarial nets](https://arxiv.org/abs/1406.2661)
+ [Unsupervised representation learning with deep convolutional generative adversarial networks](https://arxiv.org/abs/1511.06434)
+ [Wasserstein GAN](https://arxiv.org/abs/1701.07875)
+ [A style-based generator architecture for generative adversarial networks](https://arxiv.org/abs/1812.04948)
+ [Denoising diffusion probabilistic models](https://arxiv.org/abs/2006.11239)
+ [High-resolution image synthesis with latent diffusion models](https://arxiv.org/abs/2112.10752)
+ [Generative adversarial text to image synthesis](https://arxiv.org/abs/1606.07983)
+ [Mocogan: Decomposing motion and content for video generation](https://arxiv.org/abs/1804.07718)
+ [Melgan: Generative adversarial networks for conditional waveform synthesis](https://arxiv.org/abs/1910.06711)
+ [Hifi-gan: Generative adversarial networks for efficient and high fidelity speech synthesis](https://arxiv.org/abs/2010.05646)
+ [A lip sync expert is all you need for speech to lip generation in the wild](https://arxiv.org/abs/2006.09058)
+ [Dancing to music](https://arxiv.org/abs/1911.09507)
+ [Visually indicated sounds](https://arxiv.org/abs/1604.06960)
+ [Visual to sound: Generating natural sound for videos in the wild](https://arxiv.org/abs/1804.02501)
+ [Align your latents: High-resolution video synthesis with latent diffusion models](https://arxiv.org/abs/2304.08818)

### Diffusion-based Generation

+ [Deep Unsupervised Learning Using Nonequilibrium Thermodynamics](https://arxiv.org/abs/1503.03585)
+ [Denoising diffusion probabilistic models](https://arxiv.org/abs/2006.11239)
+ [Flow Matching for Generative Modeling](https://arxiv.org/abs/2210.02747)
+ [Flow Straight and Fast: Learning to Generate and Transfer Data with Rectified Flow](https://arxiv.org/abs/2209.03026)
+ [U-net: Convolutional networks for biomedical image segmentation](https://arxiv.org/abs/1505.04597)
+ [Scalable diffusion models with transformers](https://arxiv.org/abs/2212.09748)
+ [Scaling rectified flow transformers for high-resolution image synthesis](https://arxiv.org/abs/2403.03206)
+ [Hunyuanimage 3.0 technical report](https://arxiv.org/abs/2509.23951)
+ [Qwen-image technical report](https://arxiv.org/abs/2508.02324)
+ [Z-Image: An Efficient Image Generation Foundation Model with Single-Stream Diffusion Transformer](https://arxiv.org/abs/2511.22699)
+ [Hunyuanvideo: A systematic framework for large video generative models](https://arxiv.org/abs/2412.03603)
+ [Seedance 1.0: Exploring the Boundaries of Video Generation Models](https://arxiv.org/abs/2506.09113)
+ [Wan: Open and advanced large-scale video generative models](https://arxiv.org/abs/2503.20314)
+ [Seed-tts: A family of high-quality versatile speech generation models](https://arxiv.org/abs/2406.02430)
+ [Audioldm 2: Learning holistic audio generation with self-supervised pretraining](https://arxiv.org/abs/2305.14674)
+ [Wan-s2v: Audio-driven cinematic video generation](https://arxiv.org/abs/2508.18621)
+ [MMAudio: Taming Multimodal Joint Training for High-Quality Video-to-Audio Synthesis](https://arxiv.org/abs/2503.07539)
+ [Ovi: Twin backbone cross-modal fusion for audio-video generation](https://arxiv.org/abs/2510.01284)
+ [One-step diffusion with distribution matching distillation](https://arxiv.org/abs/2310.18872)

### Autoregressive Generation

+ [Conditional image generation with pixelcnn decoders](https://arxiv.org/abs/1606.05328)
+ [Wavenet: A generative model for raw audio](https://arxiv.org/abs/1609.03499)
+ [Neural discrete representation learning](https://arxiv.org/abs/1711.00937)
+ [Soundstream: An end-to-end neural audio codec](https://arxiv.org/abs/2107.03312)
+ [High Fidelity Neural Audio Compression](https://arxiv.org/abs/2406.04631)
+ [Visual autoregressive modeling: Scalable image generation via next-scale prediction](https://arxiv.org/abs/2404.02905)
+ [Autoregressive model beats diffusion: Llama for scalable image generation](https://arxiv.org/abs/2406.06525)
+ [Emu3: Next-token prediction is all you need](https://arxiv.org/abs/2409.18869)
+ [Emu3. 5: Native multimodal models are world learners](https://arxiv.org/abs/2510.26583)
+ [Autoregressive video generation without vector quantization](https://arxiv.org/abs/2412.14169)
+ [Audiolm: a language modeling approach to audio generation](https://arxiv.org/abs/2209.15156)
+ [Musiclm: Generating music from text](https://arxiv.org/abs/2301.11325)
+ [Simple and controllable music generation](https://arxiv.org/abs/2301.02559)
+ [Vall-e 2: Neural codec language models are human parity zero-shot text to speech synthesizers](https://arxiv.org/abs/2406.05370)
+ [Cosyvoice 2: Scalable streaming speech synthesis with large language models](https://arxiv.org/abs/2412.10117)
+ [Language models are few-shot learners](https://arxiv.org/abs/2005.14165)
+ [VideoPoet: A Large Language Model for Zero-Shot Video Generation](https://arxiv.org/abs/2312.14125)
+ [Temporally Aligned Audio for Video with Autoregression](https://arxiv.org/abs/2409.13689)

### Masked Autoregressive Generation

+ [Mask-predict: Parallel decoding of conditional masked language models](https://arxiv.org/abs/1905.02410)
+ [MaskGIT: Masked Generative Image Transformer](https://arxiv.org/abs/2202.04200)
+ [Muse: Text-To-Image Generation via Masked Generative Transformers](https://arxiv.org/abs/2301.00704)
+ [MAGVIT: Masked Generative Video Transformer](https://arxiv.org/abs/2212.05199)
+ [Language Model Beats Diffusion--Tokenizer is Key to Visual Generation](https://arxiv.org/abs/2310.05737)
+ [Open-magvit2: An open-source project toward democratizing auto-regressive visual generation](https://arxiv.org/abs/2409.04410)
+ [MaskViT: Masked Visual Pre-Training for Video Prediction](https://arxiv.org/abs/2206.11894)
+ [Phenaki: Variable Length Video Generation From Open Domain Textual Description](https://arxiv.org/abs/2210.02399)
+ [SoundStorm: Efficient Parallel Audio Generation](https://arxiv.org/abs/2305.09636)
+ [Autoregressive image generation without vector quantization](https://arxiv.org/abs/2406.11847)
+ [Maskbit: Embedding-free image generation via bit tokens](https://arxiv.org/abs/2409.16211)

## LLM-Centric Methods

### Encoder+LLM for Multimodal Perception

+ [Learning transferable visual models from natural language supervision](https://arxiv.org/abs/2103.00020)
+ [Sigmoid loss for language image pre-training](https://arxiv.org/abs/2303.15343)
+ [Qwen2. 5-vl technical report](https://arxiv.org/abs/2502.13923)
+ [Flamingo: a visual language model for few-shot learning](https://arxiv.org/abs/2204.14198)
+ [Blip-2: Bootstrapping language-image pre-training with frozen image encoders and large language models](https://arxiv.org/abs/2301.12597)
+ [MiniGPT-4: Enhancing Vision-Language Understanding with Advanced Large Language Models](https://arxiv.org/abs/2304.10592)
+ [Video-chatgpt: Towards detailed video understanding via large vision and language models](https://arxiv.org/abs/2310.02913)
+ [Video-llava: Learning united visual representation by alignment before projection](https://arxiv.org/abs/2311.15106)
+ [Video-LLaMA: An Instruction-tuned Audio-Visual Language Model for Video Understanding](https://arxiv.org/abs/2305.13660)
+ [Llama-vid: An image is worth 2 tokens in large language models](https://arxiv.org/abs/2405.03819)
+ [Qwen3-vl technical report](https://arxiv.org/abs/2511.21631)
+ [Expanding performance boundaries of open-source multimodal models with model, data, and test-time scaling](https://arxiv.org/abs/2412.05271)
+ [Internvl3. 5: Advancing open-source multimodal models in versatility, reasoning, and efficiency](https://arxiv.org/abs/2508.18265)
+ [Long context transfer from language to vision](https://arxiv.org/abs/2406.16852)
+ [Longvu: Spatiotemporal adaptive compression for long video-language understanding](https://arxiv.org/abs/2410.17434)
+ [An image is worth 1/2 tokens after layer 2: Plug-and-play inference acceleration for large vision-language models](https://arxiv.org/abs/2403.01862)
+ [Hubert: Self-supervised speech representation learning by masked prediction of hidden units](https://arxiv.org/abs/2106.07447)
+ [Speecht5: Unified-modal encoder-decoder pre-training for spoken language processing](https://arxiv.org/abs/2110.07205)
+ [BEATs: Audio Pre-Training with Acoustic Tokenizers](https://arxiv.org/abs/2212.09078)
+ [Robust speech recognition via large-scale weak supervision](https://arxiv.org/abs/2212.04356)
+ [Pengi: An audio language model for audio tasks](https://arxiv.org/abs/2305.11886)
+ [Llasm: Large language and speech model](https://arxiv.org/abs/2308.15930)
+ [Gama: A large audio-language model with advanced audio understanding and complex reasoning abilities](https://arxiv.org/abs/2406.11768)
+ [Salmonn: Towards generic hearing abilities for large language models](https://arxiv.org/abs/2310.13289)
+ [Qwen-audio: Advancing universal audio understanding via unified large-scale audio-language models](https://arxiv.org/abs/2311.07919)
+ [Qwen2-audio technical report](https://arxiv.org/abs/2407.10759)
+ [Videollama 2: Advancing spatial-temporal modeling and audio understanding in video-llms](https://arxiv.org/abs/2406.07476)
+ [Next-gpt: Any-to-any multimodal llm](https://arxiv.org/abs/2409.18613)
+ [Onellm: One framework to align all modalities with language](https://arxiv.org/abs/2312.06748)
+ [AnyGPT: Unified Multimodal LLM with Discrete Sequence Modeling](https://arxiv.org/abs/2402.12226)
+ [Vita-1.5: Towards gpt-4o level real-time vision and speech interaction](https://arxiv.org/abs/2501.01957)
+ [Gpt-4o system card](https://arxiv.org/abs/2410.21276)
+ [Qwen2. 5-omni technical report](https://arxiv.org/abs/2503.20215)
+ [Ming-Omni: A Unified Multimodal Model for Perception and Generation](https://arxiv.org/abs/2506.09344)
+ [Qwen3-omni technical report](https://arxiv.org/abs/2509.17765)

### LLM+Generator for Multimodal Generation

+ [Visual chatgpt: Talking, drawing and editing with visual foundation models](https://arxiv.org/abs/2303.04671)
+ [Audiogpt: Understanding and generating speech, music, sound, and talking head](https://arxiv.org/abs/2304.12995)
+ [Audioldm: Text-to-audio generation with latent diffusion models](https://arxiv.org/abs/2301.12503)
+ [Next-gpt: Any-to-any multimodal llm](https://arxiv.org/abs/2409.18613)
+ [Codi-2: In-context interleaved and interactive any-to-any generation](https://arxiv.org/abs/2407.04822)
+ [Javisgpt: A unified multi-modal llm for sounding-video comprehension and generation](https://arxiv.org/abs/2512.22905)
+ [A2-LLM: An End-to-end Conversational Audio Avatar Large Language Model](https://arxiv.org/abs/2602.04913)
+ [Qwen-image technical report](https://arxiv.org/abs/2508.02324)
+ [Univideo: Unified understanding, generation, and editing for videos](https://arxiv.org/abs/2510.08377)

### Unified Model for Joint Perception and Generation

+ [Gpt-4o system card](https://arxiv.org/abs/2410.21276)
+ [Qwen2. 5-omni technical report](https://arxiv.org/abs/2503.20215)
+ [Mini-omni: Language models can hear, talk while thinking in streaming](https://arxiv.org/abs/2408.16725)
+ [Interactiveomni: A unified omni-modal model for audio-visual multi-turn dialogue](https://arxiv.org/abs/2510.13747)
+ [Moshi: a speech-text foundation model for real-time dialogue](https://arxiv.org/abs/2410.00037)
+ [Qwen3-omni technical report](https://arxiv.org/abs/2509.17765)
+ [Emu: Generative pretraining in multimodality](https://arxiv.org/abs/2307.05222)
+ [Dreamllm: Synergistic multimodal comprehension and creation](https://arxiv.org/abs/2309.11499)
+ [Janus: Decoupling visual encoding for unified multimodal understanding and generation](https://arxiv.org/abs/2410.13848)
+ [Chameleon: Mixed-Modal Early-Fusion Foundation Models](https://arxiv.org/abs/2405.09818)
+ [Show-o: One Single Transformer to Unify Multimodal Understanding and Generation](https://arxiv.org/abs/2408.12528)
+ [Janus-pro: Unified multimodal understanding and generation with data and model scaling](https://arxiv.org/abs/2501.17811)
+ [Emerging properties in unified multimodal pretraining](https://arxiv.org/abs/2505.14683)
+ [Emu3: Next-token prediction is all you need](https://arxiv.org/abs/2409.18869)
+ [Transfusion: Predict the next token and diffuse images with one multi-modal model](https://arxiv.org/abs/2408.11039)
+ [VideoPoet: A Large Language Model for Zero-Shot Video Generation](https://arxiv.org/abs/2312.14125)
+ [Javisgpt: A unified multi-modal llm for sounding-video comprehension and generation](https://arxiv.org/abs/2512.22905)
+ [Object-AVEdit: An Object-level Audio-Visual Editing Model](https://arxiv.org/abs/2510.00050)

### Agentic System for Interactive Perception and Generation

+ [Hugginggpt: Solving ai tasks with chatgpt and its friends in hugging face](https://arxiv.org/abs/2303.17580)
+ [DoraemonGPT: Toward Understanding Dynamic Scenes with Large Language Models (Exemplified as A Video Agent)](https://arxiv.org/abs/2407.10809)
+ [VCA: Video Curious Agent for Long Video Understanding](https://arxiv.org/abs/2412.10471)
+ [V-Stylist: Video Stylization via Collaboration and Reflection of MLLM Agents](https://arxiv.org/abs/2503.12077)
+ [Preacher: Paper-to-Video Agentic System](https://arxiv.org/abs/2508.09632)
+ [Audio-Agent: Leveraging LLMs For Audio Generation, Editing and Composition](https://arxiv.org/abs/2410.03335)
+ [Audiotoolagent: An agentic framework for audio-language models](https://arxiv.org/abs/2510.02995)

### Visual-Language-Action Models for Embodied Interaction

+ [Rt-2: Vision-language-action models transfer web knowledge to robotic control](https://arxiv.org/abs/2307.15818)
+ [RT-H: Action Hierarchies using Language](https://arxiv.org/abs/2403.02796)
+ [RT-Trajectory: Robotic Task Generalization via Hindsight Trajectory Sketches](https://arxiv.org/abs/2310.04097)
+ [OpenVLA: An Open-Source Vision-Language-Action Model](https://arxiv.org/abs/2406.09246)
+ [Tinyvla: Towards fast, data-efficient vision-language-action models for robotic manipulation](https://arxiv.org/abs/2406.03747)
+ [Smolvla: A vision-language-action model for affordable and efficient robotics](https://arxiv.org/abs/2506.01844)
+ [Gr00t n1: An open foundation model for generalist humanoid robots](https://arxiv.org/abs/2503.14734)
+ [Gemini robotics: Bringing ai into the physical world](https://arxiv.org/abs/2503.20020)
+ [$\pi_0$: A Vision-Language-Action Flow Model for General Robot Control](https://arxiv.org/abs/2410.24164)
+ [Octo: An open-source generalist robot policy](https://arxiv.org/abs/2405.12213)
+ [Graspvla: a grasping foundation model pre-trained on billion-scale synthetic action data](https://arxiv.org/abs/2505.03233)
+ [Tracevla: Visual trace prompting enhances spatial-temporal awareness for generalist robotic policies](https://arxiv.org/abs/2412.10345)
+ [Cogact: A foundational vision-language-action model for synergizing cognition and action in robotic manipulation](https://arxiv.org/abs/2411.19650)
+ [Cogvla: Cognition-aligned vision-language-action model via instruction-driven routing \& sparsification](https://arxiv.org/abs/2508.21046)
+ [Failsafe: Reasoning and recovery from failures in vision-language-action models](https://arxiv.org/abs/2510.01642)
+ [RynnVLA-002: A Unified Vision-Language-Action and World Model](https://arxiv.org/abs/2511.17502)

---

# 👁️ Audio-Visual Perception

Perception in audio-visual systems begins with *what* can be read off raw signals, then moves to *what* those signals mean in context, and finally to *why* and *how* events are related over time. This section covers pixel-level perception, content understanding, and logical reasoning.

## Audio-Visual Pixel Perception

### Audio Perception

+ [Hubert: Self-supervised speech representation learning by masked prediction of hidden units](https://arxiv.org/abs/2106.07447)
+ [BEATs: Audio Pre-Training with Acoustic Tokenizers](https://arxiv.org/abs/2212.09078)
+ [MERT: Acoustic Music Understanding Model with Large-Scale Self-supervised Training](https://arxiv.org/abs/2306.00109)
+ [Muq: Self-supervised music representation learning with mel residual vector quantization](https://arxiv.org/abs/2501.01108)
+ [Speechprompt v2: Prompt tuning for speech classification tasks](https://arxiv.org/abs/2303.00733)
+ [Mulan: A joint embedding of music audio and natural language](https://arxiv.org/abs/2208.12415)
+ [Training sound event detection with soft labels from crowdsourced annotations](https://arxiv.org/abs/2302.09712)
+ [Svad: A robust, low-power, and light-weight voice activity detection with spiking neural networks](https://arxiv.org/abs/2408.11590)
+ [Fine-tune the pretrained ATST model for sound event detection](https://arxiv.org/abs/2402.01566)
+ [Beat Transformer: Demixed Beat and Downbeat Tracking with Dilated Self-Attention](https://arxiv.org/abs/2110.04071)
+ [CMI-Bench: A Comprehensive Benchmark for Evaluating Music Instruction Following](https://arxiv.org/abs/2506.12285)
+ [TF-GridNet: Making time-frequency domain models great again for monaural speaker separation](https://arxiv.org/abs/2209.03930)
+ [Dual-path mamba: Short and long-term bidirectional selective structured state space models for speech separation](https://arxiv.org/abs/2412.04581)
+ [Hybrid transformers for music source separation](https://arxiv.org/abs/2309.02612)
+ [Music source separation with band-split RNN](https://arxiv.org/abs/2209.15174)

### Visual Perception

+ [Faster R-CNN: Towards real-time object detection with region proposal networks](https://arxiv.org/abs/1506.01497)
+ [Deformable detr: Deformable transformers for end-to-end object detection](https://arxiv.org/abs/2010.04159)
+ [Scaling open-vocabulary object detection](https://arxiv.org/abs/2306.14693)
+ [Glipv2: Unifying localization and vision-language understanding](https://arxiv.org/abs/2206.05836)
+ [Grounding dino: Marrying dino with grounded pre-training for open-set object detection](https://arxiv.org/abs/2304.07258)
+ [Next-chat: An lmm for chat, detection and segmentation](https://arxiv.org/abs/2311.04498)
+ [Panoptic segmentation](https://arxiv.org/abs/1801.00868)
+ [Masked-attention mask transformer for universal image segmentation](https://arxiv.org/abs/2112.01527)
+ [Segment anything](https://arxiv.org/abs/2304.02643)
+ [Sam 2: Segment anything in images and videos](https://arxiv.org/abs/2408.00714)
+ [Sam 3: Segment anything with concepts](https://arxiv.org/abs/2511.16719)
+ [Sutrack: Towards simple and unified single object tracking](https://arxiv.org/abs/2503.01862)
+ [Bytetrack: Multi-object tracking by associating every detection box](https://arxiv.org/abs/2110.06864)
+ [Track anything: Segment anything meets videos](https://arxiv.org/abs/2304.11968)
+ [Follow anything: Open-set detection, tracking, and following in real-time](https://arxiv.org/abs/2305.06800)
+ [An empirical study of end-to-end temporal action detection](https://arxiv.org/abs/2204.03454)
+ [Tridet: Temporal action detection with relative boundary modeling](https://arxiv.org/abs/2303.12042)
+ [End-to-end temporal action detection with transformer](https://arxiv.org/abs/2203.16046)
+ [Actionformer: Localizing moments of actions with transformers](https://arxiv.org/abs/2207.09580)

### Audio-Visual Event Localization/Grounding

+ [Audio-visual event localization in unconstrained videos](https://arxiv.org/abs/1804.03947)
+ [The sound of pixels](https://arxiv.org/abs/1804.03160)
+ [Cross-modal relation-aware networks for audio-visual event localization](https://arxiv.org/abs/2007.09114)
+ [Dual attention matching for audio-visual event localization](https://arxiv.org/abs/1907.04401)
+ [Cross-modal attention network for temporal inconsistent audio-visual event localization](https://arxiv.org/abs/2008.03473)
+ [Dual-modality seq2seq network for audio-visual event localization](https://arxiv.org/abs/1907.05068)
+ [Positive sample propagation along the audio-visual event line](https://arxiv.org/abs/2104.00234)
+ [Dual perspective network for audio-visual event localization](https://arxiv.org/abs/2205.09510)
+ [Unified multisensory perception: Weakly-supervised audio-visual video parsing](https://arxiv.org/abs/2007.10539)
+ [Ave-clip: Audioclip-based multi-window temporal transformer for audio visual event localization](https://arxiv.org/abs/2307.01146)
+ [Vision transformers are parameter-efficient audio-visual learners](https://arxiv.org/abs/2210.06969)
+ [Towards efficient audio-visual learners via empowering pre-trained vision transformers with cross-modal adaptation](https://arxiv.org/abs/2403.01862)
+ [Prompt Image to Watch and Hear: Multimodal Prompting for Parameter-Efficient Audio-Visual Learning](https://bmva-archive.org.uk/bmvc/2025/assets/papers/Paper_949/paper.pdf)
+ [OpenAVE: Moving towards open set audio-visual event localization](https://arxiv.org/abs/2407.04822)
+ [Towards open-vocabulary audio-visual event localization](https://arxiv.org/abs/2403.17423)
+ [Dense-localizing audio-visual events in untrimmed videos: A large-scale benchmark and baseline](https://arxiv.org/abs/2303.12930)
+ [Dense audio-visual event localization under cross-modal consistency and multi-temporal granularity collaboration](https://arxiv.org/abs/2307.06451)

### Audio-Visual Segmentation

+ [Audio--visual segmentation](https://arxiv.org/abs/2206.09671)
+ [Audio-visual segmentation with semantics](https://arxiv.org/abs/2501.02367)
+ [Robust Audio-Visual Segmentation via Audio-Guided Visual Convergent Alignment](https://arxiv.org/abs/2403.12117)
+ [Dynamic Derivation and Elimination: Audio Visual Segmentation with Enhanced Audio Semantics](https://arxiv.org/abs/2403.12117)
+ [Weakly-supervised audio-visual segmentation](https://arxiv.org/abs/2305.12431)
+ [Annotation-free audio-visual segmentation](https://arxiv.org/abs/2305.12431)
+ [Unsupervised audio-visual segmentation with modality alignment](https://arxiv.org/abs/2403.14203)
+ [Segment anything](https://arxiv.org/abs/2304.02643)
+ [DINOv2: Learning Robust Visual Features without Supervision](https://arxiv.org/abs/2304.07193)
+ [Qdformer: Towards robust audiovisual segmentation in complex environments with quantization-based semantic decomposition](https://arxiv.org/abs/2403.06608)
+ [Discovering sounding objects by audio queries for audio visual segmentation](https://arxiv.org/abs/2305.12431)
+ [Cpm: Class-conditional prompting machine for audio-visual segmentation](https://arxiv.org/abs/2403.12117)
+ [Avsegformer: Audio-visual segmentation with transformer](https://arxiv.org/abs/2307.01146)
+ [Unveiling the power of audio-visual early fusion transformers with dense interactions through masked modeling](https://arxiv.org/abs/2305.12431)
+ [Prompting segmentation with sound is generalizable audio-visual source localizer](https://arxiv.org/abs/2401.00580)
+ [Cooperation does matter: Exploring multi-order bilateral relations for audio-visual segmentation](https://arxiv.org/abs/2407.04822)
+ [Sam 2: Segment anything in images and videos](https://arxiv.org/abs/2408.00714)
+ [Contrastive conditional latent diffusion for audio-visual segmentation](https://arxiv.org/abs/2403.12117)
+ [BAVS: bootstrapping audio-visual segmentation by integrating foundation knowledge](https://arxiv.org/abs/2403.06608)
+ [One transformer fits all distributions in multi-modal diffusion at scale](https://arxiv.org/abs/2303.06555)
+ [Can Textual Semantics Mitigate Sounding Object Segmentation Preference?](https://arxiv.org/abs/2401.07321)
+ [How Do Optical Flow and Textual Prompts Collaborate to Assist in Audio-Visual Semantic Segmentation?](https://arxiv.org/abs/2104.04780)
+ [Unraveling instance associations: A closer look for audio-visual segmentation](https://arxiv.org/abs/2305.12431)
+ [Ref-avs: Refer and segment objects in audio-visual scenes](https://arxiv.org/abs/2403.12117)
+ [Omni-R1: Reinforcement Learning for Omnimodal Reasoning via Two-System Collaboration](https://arxiv.org/abs/2505.20256)
+ [SAM2-LOVE: Segment Anything Model 2 in Language-aided Audio-Visual Scenes](https://arxiv.org/abs/2408.02883)
+ [TSAM: Temporal SAM Augmented with Multimodal Prompts for Referring Audio-Visual Segmentation](https://arxiv.org/abs/2407.01146)
+ [Think before you segment: An object-aware reasoning agent for referring audio-visual segmentation](https://arxiv.org/abs/2508.04418)
+ [Towards omnimodal expressions and reasoning in referring audio-visual segmentation](https://arxiv.org/abs/2507.22886)
+ [Do Audio-Visual Segmentation Models Truly Segment Sounding Objects?](https://arxiv.org/abs/2502.00358)
+ [Audio-visual instance segmentation](https://arxiv.org/abs/2503.12117)

### Audio-Visual Synchronization

+ [Detection of audio-video synchronization errors via event detection](https://arxiv.org/abs/2104.10116)
+ [Audio-visual synchronisation in the wild](https://arxiv.org/abs/2112.04432)
+ [SyncNet: Correlating Objective for Time Delay Estimation in Audio Signals](https://arxiv.org/abs/2203.14639)
+ [Interpretable Convolutional SyncNet](https://arxiv.org/abs/2409.00971)
+ [Temporally Streaming Audio-Visual Synchronization for Real-World Videos](https://arxiv.org/abs/2504.10116)
+ [Vocalist: An audio-visual synchronisation model for lips and voices](https://arxiv.org/abs/2204.02090)
+ [End-to-end lip synchronisation based on pattern classification](https://arxiv.org/abs/1905.05579)
+ [Lip reading sentences in the wild](https://arxiv.org/abs/1612.05368)
+ [A lip sync expert is all you need for speech to lip generation in the wild](https://arxiv.org/abs/2006.09058)
+ [Visualvoice: Audio-visual speech separation with cross-modal consistency](https://arxiv.org/abs/2101.03149)
+ [Out of time: automated lip sync in the wild](https://arxiv.org/abs/1612.05368)
+ [DiVAS: Video and Audio Synchronization with Dynamic Frame Rates](https://arxiv.org/abs/2407.01146)
+ [On Attention Modules for Audio-Visual Synchronization.](https://arxiv.org/abs/1905.05579)
+ [Perfect match: Improved cross-modal embeddings for audio-visual synchronisation](https://arxiv.org/abs/1905.05579)
+ [Modeformer: Modality-preserving embedding for audio-video synchronization using transformers](https://arxiv.org/abs/2305.05579)
+ [Audio set: An ontology and human-labeled dataset for audio events](https://arxiv.org/abs/1609.08198)
+ [Audio-visual event localization in unconstrained videos](https://arxiv.org/abs/1804.03947)
+ [Vggsound: A large-scale audio-visual dataset](https://arxiv.org/abs/2004.14331)
+ [LRS3-TED: a large-scale dataset for visual speech recognition](https://arxiv.org/abs/1809.00496)

## Audio-Visual Content Understanding

### Audio Understanding

+ [Deep Neural Networks for Small Footprint Text-Dependent Speaker Verification](https://arxiv.org/abs/1508.05476)
+ [X-Vectors: Robust DNN Embeddings for Speaker Recognition](https://arxiv.org/abs/2004.02355)
+ [ECAPA-TDNN: Emphasized Channel Attention, Propagation and Aggregation in TDNN Based Speaker Verification](https://arxiv.org/abs/2005.07471)
+ [Wavlm: Large-scale self-supervised pre-training for full stack speech processing](https://arxiv.org/abs/2110.13900)
+ [Emotion Recognition from Speech Using Wav2vec 2.0 Embeddings](https://arxiv.org/abs/2103.11540)
+ [wav2vec 2.0: A framework for self-supervised learning of speech representations](https://arxiv.org/abs/2006.11477)
+ [emotion2vec: Self-supervised pre-training for speech emotion representation](https://arxiv.org/abs/2312.15185)
+ [Multimodal Transformer for Unaligned Multimodal Language Sequences](https://arxiv.org/abs/1905.05579)
+ [Panns: Large-scale pretrained audio neural networks for audio pattern recognition](https://arxiv.org/abs/1912.10295)
+ [Hts-at: A hierarchical token-semantic audio transformer for sound classification and detection](https://arxiv.org/abs/2207.06411)
+ [Audio Captioning Transformer](https://arxiv.org/abs/2107.09817)
+ [RECAP: Retrieval-Augmented Audio Captioning](https://arxiv.org/abs/2309.09836)
+ [Salmonn: Towards generic hearing abilities for large language models](https://arxiv.org/abs/2310.13289)
+ [Audio flamingo: A novel audio language model with few-shot learning and dialogue abilities](https://arxiv.org/abs/2402.01831)
+ [Qwen-audio: Advancing universal audio understanding via unified large-scale audio-language models](https://arxiv.org/abs/2311.07919)
+ [Temporal reasoning via audio question answering](https://arxiv.org/abs/1911.09655)
+ [Joint audio and speech understanding](https://arxiv.org/abs/2309.14405)
+ [Qwen2-audio technical report](https://arxiv.org/abs/2407.10759)
+ [Data-Balanced Curriculum Learning for Audio Question Answering](https://arxiv.org/abs/2507.06815)

### Visual Understanding

+ [Microsoft COCO: Common Objects in Context](https://arxiv.org/abs/1405.0312)
+ [Vqa: Visual question answering](https://arxiv.org/abs/1505.00468)
+ [Deep residual learning for image recognition](https://arxiv.org/abs/1512.03385)
+ [An image is worth 16x16 words: Transformers for image recognition at scale](https://arxiv.org/abs/2010.11929)
+ [Learning transferable visual models from natural language supervision](https://arxiv.org/abs/2103.00020)
+ [Blip-2: Bootstrapping language-image pre-training with frozen image encoders and large language models](https://arxiv.org/abs/2301.12597)
+ [Coca: Contrastive captioners are image-text foundation models](https://arxiv.org/abs/2205.01917)
+ [Pali: A jointly-scaled multilingual language-image model](https://arxiv.org/abs/2209.06794)
+ [Visual instruction tuning](https://arxiv.org/abs/2304.08485)
+ [Qwen2. 5-vl technical report](https://arxiv.org/abs/2502.13923)
+ [Qwen3-vl technical report](https://arxiv.org/abs/2511.21631)
+ [Internvl3. 5: Advancing open-source multimodal models in versatility, reasoning, and efficiency](https://arxiv.org/abs/2508.18265)
+ [Mattnet: Modular attention network for referring expression comprehension](https://arxiv.org/abs/1808.05712)
+ [Generation and comprehension of unambiguous object descriptions](https://arxiv.org/abs/1605.04780)
+ [Mdetr-modulated detection for end-to-end multi-modal understanding](https://arxiv.org/abs/2104.12763)
+ [Grounded language-image pre-training](https://arxiv.org/abs/2203.16517)
+ [Grounding dino: Marrying dino with grounded pre-training for open-set object detection](https://arxiv.org/abs/2304.07258)
+ [Minigpt-v2: large language model as a unified interface for vision-language multi-task learning](https://arxiv.org/abs/2310.09478)
+ [Cogvlm: Visual expert for pretrained language models](https://arxiv.org/abs/2311.03079)
+ [Detecting moments and highlights in videos via natural language queries](https://arxiv.org/abs/2103.05610)
+ [Vid2seq: Large-scale pretraining of a visual language model for dense video captioning](https://arxiv.org/abs/2302.14115)
+ [Timechat: A time-sensitive multimodal large language model for long video understanding](https://arxiv.org/abs/2401.01649)
+ [Vtimellm: Empower llm to grasp video moments](https://arxiv.org/abs/2310.10608)
+ [Timesuite: Improving mllms for long video understanding via grounded tuning](https://arxiv.org/abs/2410.19702)
+ [Chrono: A simple blueprint for representing time in mllms](https://arxiv.org/abs/2406.18113)
+ [Time-R1: Towards Comprehensive Temporal Reasoning in LLMs](https://arxiv.org/abs/2505.13508)
+ [Videochat-r1: Enhancing spatio-temporal perception via reinforcement fine-tuning](https://arxiv.org/abs/2504.06958)
+ [Videochat-r1. 5: Visual test-time scaling to reinforce multimodal reasoning by iterative perception](https://arxiv.org/abs/2509.21100)
+ [On the Consistency of Video Large Language Models in Temporal Comprehension](https://arxiv.org/abs/2411.12951)
+ [EgoExo-Con: Exploring View-Invariant Video Temporal Understanding](https://arxiv.org/abs/2510.26113)
+ [Show, attend and tell: Neural image caption generation with visual attention](https://arxiv.org/abs/1502.03044)
+ [Bottom-up and top-down attention for image captioning and visual question answering](https://arxiv.org/abs/1707.07998)
+ [Simvlm: Simple visual language model pretraining with weak supervision](https://arxiv.org/abs/2108.10904)
+ [Blip: Bootstrapping language-image pre-training for unified vision-language understanding and generation](https://arxiv.org/abs/2201.12086)
+ [Llava-onevision: Easy visual task transfer](https://arxiv.org/abs/2408.03326)
+ [Llava-onevision-1.5: Fully open framework for democratized multimodal training](https://arxiv.org/abs/2509.23661)
+ [Llava-video: Video instruction tuning with synthetic data](https://arxiv.org/abs/2410.02713)
+ [Internvl: Scaling up vision foundation models and aligning for generic visual-linguistic tasks](https://arxiv.org/abs/2312.14238)
+ [Cider: Consensus-based image description evaluation](https://arxiv.org/abs/1411.5726)
+ [Sycophancy in vision-language models: A systematic analysis and an inference-time mitigation framework](https://arxiv.org/abs/2503.01743)
+ [Video question answering: Datasets, algorithms and challenges](https://arxiv.org/abs/2203.01525)
+ [Llama: Open and efficient foundation language models](https://arxiv.org/abs/2302.13971)
+ [Flamingo: a visual language model for few-shot learning](https://arxiv.org/abs/2204.14198)
+ [Video-chatgpt: Towards detailed video understanding via large vision and language models](https://arxiv.org/abs/2310.02913)
+ [Mvbench: A comprehensive multi-modal video understanding benchmark](https://arxiv.org/abs/2402.04346)
+ [Qwen3.5: Accelerating Productivity with Native Multimodal Agents](https://qwen.ai/blog?id=qwen3.5)
+ [Streaming video question-answering with in-context video kv-cache retrieval](https://arxiv.org/abs/2503.01862)
+ [Streammem: Query-agnostic kv cache memory for streaming video understanding](https://arxiv.org/abs/2508.15717)
+ [EgoBlind: Towards Egocentric Visual Assistance for the Blind People](https://arxiv.org/abs/2503.08221)
+ [Egotextvqa: Towards egocentric scene-text aware video question answering](https://arxiv.org/abs/2407.04822)
+ [Can i trust your answer? visually grounded video question answering](https://arxiv.org/abs/2403.01862)
+ [VideoQA in the Era of LLMs: An Empirical Study](https://arxiv.org/abs/2503.01862)

### Audio-Visual Question Answering

+ [Learning to answer questions in dynamic audio-visual scenarios](https://arxiv.org/abs/2205.03566)
+ [Avqa: A dataset for audio-visual question answering on videos](https://arxiv.org/abs/2207.02515)
+ [Vqa: Visual question answering](https://arxiv.org/abs/1505.00468)
+ [Next-qa: Next phase of question-answering to explaining temporal actions](https://arxiv.org/abs/2105.08290)
+ [Audio Visual Scene-Aware Dialog (AVSD) Challenge at DSTC7](https://arxiv.org/abs/1806.00525)
+ [Boosting Audio Visual Question Answering via Key Semantic-Aware Cues](https://arxiv.org/abs/2403.06608)
+ [Answering Diverse Questions via Text Attached with Key Audio-Visual Clues](https://arxiv.org/abs/2403.06679)
+ [Question-Aware Gaussian Experts for Audio-Visual Question Answering](https://arxiv.org/abs/2503.01862)
+ [RAVEN: Query-Guided Representation Alignment for Question Answering over Audio, Video, Embedded Sensors, and Natural Language](https://arxiv.org/abs/2505.17114)
+ [AV-Master: Dual-Path Comprehensive Perception Makes Better Audio-Visual Question Answering](https://arxiv.org/abs/2510.18346)
+ [Audio-Visual LLM for Video Understanding](https://arxiv.org/abs/2312.06720)
+ [Cat: Enhancing multimodal large language model to answer questions in dynamic audio-visual scenarios](https://arxiv.org/abs/2405.12104)
+ [Videollama 2: Advancing spatial-temporal modeling and audio understanding in video-llms](https://arxiv.org/abs/2406.07476)
+ [video-salmonn: Speech-enhanced audio-visual large language models](https://arxiv.org/abs/2406.15704)
+ [Meerkat: Audio-Visual Large Language Model for Grounding in Space and Time](https://arxiv.org/abs/2405.01862)
+ [Gpt-4o system card](https://arxiv.org/abs/2410.21276)
+ [Gemini 2.5: Pushing the frontier with advanced reasoning, multimodality, long context, and next generation agentic capabilities](https://arxiv.org/abs/2507.06261)
+ [Qwen3-omni technical report](https://arxiv.org/abs/2509.17765)
+ [Baichuan-Omni-1.5 Technical Report](https://arxiv.org/abs/2501.15368)
+ [Ming-Omni: A Unified Multimodal Model for Perception and Generation](https://arxiv.org/abs/2506.09344)
+ [Ming-flash-omni: A sparse, unified architecture for multimodal perception and generation](https://arxiv.org/abs/2510.24821)
+ [Longcat-flash-omni technical report](https://arxiv.org/abs/2511.00279)
+ [Fortisavqa and maven: a benchmark dataset and debiasing framework for robust multimodal reasoning](https://arxiv.org/abs/2504.00487)
+ [AVQACL: A Novel Benchmark for Audio-Visual Question Answering Continual Learning](https://arxiv.org/abs/2503.01862)
+ [Valor32k-AVQA v2. 0: Open-Ended Audio-Visual Question Answering Dataset and Benchmark](https://arxiv.org/abs/2503.01862)
+ [DAVE: Diagnostic Benchmark for Audio Visual Evaluation](https://arxiv.org/abs/2503.09321)
+ [Audio-centric Video Understanding Benchmark without Text Shortcut](https://arxiv.org/abs/2503.07539)
+ [AVHBench: A Cross-Modal Hallucination Benchmark for Audio-Visual Large Language Models](https://arxiv.org/abs/2410.18325)
+ [FastAV: Efficient Token Pruning for Audio-Visual Large Language Model Inference](https://arxiv.org/abs/2601.13143)
+ [Pandagpt: One model to instruction-follow them all](https://arxiv.org/abs/2305.16355)
+ [Macaw-llm: Multi-modal language modeling with image, audio, video, and text integration](https://arxiv.org/abs/2306.09093)
+ [Video-LLaMA: An Instruction-tuned Audio-Visual Language Model for Video Understanding](https://arxiv.org/abs/2305.13660)
+ [X-instructblip: A framework for aligning x-modal instruction-aware representations to llms and emergent cross-modal reasoning](https://arxiv.org/abs/2311.18799)
+ [Onellm: One framework to align all modalities with language](https://arxiv.org/abs/2312.06748)
+ [Empowering llms with pseudo-untrimmed videos for audio-visual temporal understanding](https://arxiv.org/abs/2503.07539)
+ [Crema: Generalizable and efficient video-language reasoning via multimodal modular fusion](https://arxiv.org/abs/2405.11099)

### Audio-Visual Cross-Modal Retrieval

+ [Soundnet: Learning sound representations from unlabeled video](https://arxiv.org/abs/1610.09001)
+ [Ambient sound provides supervision for visual learning](https://arxiv.org/abs/1608.07073)
+ [Look, listen and learn](https://arxiv.org/abs/1710.07260)
+ [Objects that sound](https://arxiv.org/abs/1712.00085)
+ [Cooperative learning of audio and video models from self-supervised synchronization](https://arxiv.org/abs/1805.09363)
+ [Audio-visual scene analysis with self-supervised multisensory features](https://arxiv.org/abs/1804.03645)
+ [Avlnet: Learning audio-visual language representations from instructional videos](https://arxiv.org/abs/2006.09199)
+ [Learning audio-visual source localization via false negative aware contrastive learning](https://arxiv.org/abs/2306.00224)
+ [Audio-visual instance discrimination with cross-modal agreement](https://arxiv.org/abs/2006.08363)
+ [Robust audio-visual instance discrimination](https://arxiv.org/abs/2006.08363)
+ [Broaden your views for self-supervised video learning](https://arxiv.org/abs/2104.09172)
+ [Multimodal self-supervised learning of general audio representations](https://arxiv.org/abs/2104.12807)
+ [Contrastive learning of global and local video representations](https://arxiv.org/abs/2104.09172)
+ [Self-supervised audio-visual representation learning with relaxed cross-modal synchronicity](https://arxiv.org/abs/2301.03404)
+ [EquiAV: leveraging equivariance for audio-visual contrastive learning](https://arxiv.org/abs/2403.09502)
+ [Language-Guided Contrastive Audio-Visual Masked Autoencoder with Automated Multi-Modal Auxiliary Tasks](https://arxiv.org/abs/2507.11967)
+ [Contrastive audio-visual masked autoencoder](https://arxiv.org/abs/2210.07839)
+ [Audiovisual masked autoencoders](https://arxiv.org/abs/2212.05922)
+ [MAViL: masked audio-video learners](https://arxiv.org/abs/2212.08071)
+ [Crossmae: Cross-modality masked autoencoders for region-aware audio-visual pre-training](https://arxiv.org/abs/2405.12431)
+ [Explainable audio-visual representation learning via prototypical contrastive masked autoencoder](https://arxiv.org/abs/2306.00224)
+ [Siamese Vision Transformers are Scalable Audio-Visual Learners](https://arxiv.org/abs/2305.02899)
+ [From Vision to Audio and Beyond: A Unified Model for Audio-Visual Representation Learning](https://arxiv.org/abs/2409.19132)
+ [CAV-MAE Sync: Improving Contrastive Audio-Visual Mask Autoencoders with Synchronization](https://arxiv.org/abs/2505.01237)
+ [Imagebind: One embedding space to bind them all](https://arxiv.org/abs/2305.05665)
+ [LanguageBind: Extending Video-Language Pretraining to N-modality by Language-Based Semantic Alignment](https://arxiv.org/abs/2310.01852)
+ [Separating the Chirp from the Chat: Self-supervised Visual Grounding of Sound from Text](https://arxiv.org/abs/2404.02291)
+ [Emerging Properties in Self-Supervised Vision Transformers](https://arxiv.org/abs/2011.06937)
+ [Hubert: Self-supervised speech representation learning by masked prediction of hidden units](https://arxiv.org/abs/2106.07447)
+ [Audio set: An ontology and human-labeled dataset for audio events](https://arxiv.org/abs/1609.08198)
+ [Vggsound: A large-scale audio-visual dataset](https://arxiv.org/abs/2004.14331)
+ [MSR-VTT: A Large Video Description Dataset for Bridging Video and Language](https://arxiv.org/abs/1604.07929)
+ [Towards Automatic Learning of Procedures From Web Instructional Videos](https://arxiv.org/abs/1803.01879)
+ [HowTo100M: Learning a Text-Video Embedding by Watching Hundred Million Narrated Video Clips](https://arxiv.org/abs/1906.03327)
+ [MUGEN: A Playground for Video-Audio-Text Multimodal Understanding and GENeration](https://arxiv.org/abs/2206.03649)
+ [AVSET-10M: An Open Large-Scale Audio-Visual Dataset with High Correspondence](https://arxiv.org/abs/2503.01862)

## Audio-Visual Logical Reasoning

### Audio Reasoning

+ [MMAR: A Challenging Benchmark for Deep Reasoning in Speech, Audio, Music, and Their Mix](https://arxiv.org/abs/2505.13032)
+ [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)
+ [Gama: A large audio-language model with advanced audio understanding and complex reasoning abilities](https://arxiv.org/abs/2406.11768)
+ [Salmonn: Towards generic hearing abilities for large language models](https://arxiv.org/abs/2310.13289)
+ [Audio flamingo 2: An audio-language model with long-audio understanding and expert reasoning abilities](https://arxiv.org/abs/2503.03983)
+ [CLEAR: A Dataset for Compositional Language and Elementary Acoustic Reasoning](https://arxiv.org/abs/1811.10561)
+ [CMDAR: A Chinese Multi-scene Dynamic Audio Reasoning Benchmark with Diverse Challenges](https://arxiv.org/abs/2509.22461)

### Visual Reasoning

+ [Clevr: A diagnostic dataset for compositional language and elementary visual reasoning](https://arxiv.org/abs/1612.06890)
+ [CATER: A diagnostic dataset for Compositional Actions \& TEmporal Reasoning](https://arxiv.org/abs/1910.04744)
+ [Clevrer: Collision events for video representation and reasoning](https://arxiv.org/abs/1910.01442)
+ [Gqa: A new dataset for real-world visual reasoning and compositional question answering](https://arxiv.org/abs/1902.09506)
+ [Action genome: Actions as compositions of spatio-temporal scene graphs](https://arxiv.org/abs/2004.07442)
+ [Next-qa: Next phase of question-answering to explaining temporal actions](https://arxiv.org/abs/2105.08290)
+ [Tgif-qa: Toward spatio-temporal reasoning in visual question answering](https://arxiv.org/abs/1712.04948)
+ [Invariant grounding for video question answering](https://arxiv.org/abs/2208.05263)
+ [Counterfactual vqa: A cause-effect look at language bias](https://arxiv.org/abs/2006.04660)
+ [From recognition to cognition: Visual commonsense reasoning](https://arxiv.org/abs/1811.10830)
+ [Neural-symbolic vqa: Disentangling reasoning from vision and language understanding](https://arxiv.org/abs/1804.00513)
+ [Modular visual question answering via code generation](https://arxiv.org/abs/2306.05392)
+ [Vipergpt: Visual inference via python execution for reasoning](https://arxiv.org/abs/2303.08128)
+ [Explainable and explicit visual reasoning over scene graphs](https://arxiv.org/abs/1812.01855)
+ [Relation-aware graph attention network for visual question answering](https://arxiv.org/abs/1908.04766)
+ [Scene graph reasoning for visual question answering](https://arxiv.org/abs/2007.01072)
+ [Neural module networks](https://arxiv.org/abs/1511.06035)
+ [Meta module network for compositional visual reasoning](https://arxiv.org/abs/2007.06630)
+ [Visual instruction tuning](https://arxiv.org/abs/2304.08485)
+ [Improved baselines with visual instruction tuning](https://arxiv.org/abs/2405.01546)
+ [Llava-onevision: Easy visual task transfer](https://arxiv.org/abs/2408.03326)
+ [Llava-onevision-1.5: Fully open framework for democratized multimodal training](https://arxiv.org/abs/2509.23661)
+ [Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond](https://arxiv.org/abs/2308.12966)
+ [Qwen2. 5-vl technical report](https://arxiv.org/abs/2502.13923)
+ [Internvl: Scaling up vision foundation models and aligning for generic visual-linguistic tasks](https://arxiv.org/abs/2312.14238)
+ [Internvl3. 5: Advancing open-source multimodal models in versatility, reasoning, and efficiency](https://arxiv.org/abs/2508.18265)
+ [Videoespresso: A large-scale chain-of-thought dataset for fine-grained video reasoning via core frame selection](https://arxiv.org/abs/2503.01862)
+ [Chain-of-Visual-Thought: Teaching VLMs to See and Think Better with Continuous Visual Tokens](https://arxiv.org/abs/2511.19418)
+ [Visual Intention Grounding for Egocentric Assistants](https://arxiv.org/abs/2503.01862)
+ [QVQ: To See the World with Wisdom](https://qwenlm.github.io/blog/qvq-72b-preview/)
+ [Reason-RFT: Reinforcement Fine-Tuning for Visual Reasoning of Vision Language Models](https://arxiv.org/abs/2503.20752)
+ [Point-rft: Improving multimodal reasoning with visually grounded reinforcement finetuning](https://arxiv.org/abs/2505.19702)
+ [Visionary-r1: Mitigating shortcuts in visual reasoning with reinforcement learning](https://arxiv.org/abs/2505.14677)
+ [VTool-R1: VLMs Learn to Think with Images via Reinforcement Learning on Multimodal Tool Use](https://arxiv.org/abs/2505.19255)
+ [Charxiv: Charting gaps in realistic chart understanding in multimodal llms](https://arxiv.org/abs/2410.01862)
+ [Gpt-4o system card](https://arxiv.org/abs/2410.21276)
+ [Claude 3.5 Sonnet Model Card Addendum](https://www-cdn.anthropic.com/fed9cc193a14b84131812372d8d5857f8f304c52/Model_Card_Claude_3_Addendum.pdf)
+ [Video-r1: Reinforcing video reasoning in mllms](https://arxiv.org/abs/2503.21776)
+ [Deepseek-r1: Incentivizing reasoning capability in llms via reinforcement learning](https://arxiv.org/abs/2501.12948)
+ [VideoRFT: Incentivizing Video Reasoning Capability in MLLMs via Reinforced Fine-Tuning](https://arxiv.org/abs/2505.12434)
+ [Videochat-r1: Enhancing spatio-temporal perception via reinforcement fine-tuning](https://arxiv.org/abs/2504.06958)
+ [Videochat-r1. 5: Visual test-time scaling to reinforce multimodal reasoning by iterative perception](https://arxiv.org/abs/2509.21100)
+ [Time-R1: Post-Training Large Vision Language Model for Temporal Video Grounding](https://arxiv.org/abs/2503.13377)
+ [MMMU: A Massive Multi-discipline Multimodal Understanding and Reasoning Benchmark for Expert AGI](https://arxiv.org/abs/2311.16502)
+ [MathVista: Evaluating Mathematical Reasoning of Foundation Models in Visual Contexts](https://arxiv.org/abs/2310.02255)
+ [Measuring Multimodal Mathematical Reasoning with MATH-Vision Dataset](https://openreview.net/forum?id=QWTCcxMpPA)
+ [Visual CoT: Advancing Multi-Modal Language Models with a Comprehensive Dataset and Benchmark for Chain-of-Thought Reasoning](https://arxiv.org/abs/2403.16999)
+ [VisuLogic: A Benchmark for Evaluating Visual Reasoning in Multi-modal Large Language Models](https://arxiv.org/abs/2504.15279)
+ [MMReason: An Open-Ended Multi-Modal Multi-Step Reasoning Benchmark for MLLMs Toward AGI](https://arxiv.org/abs/2506.23563)

### Audio-Visual Reasoning

+ [Learning to Reason with LLMs](https://arxiv.org/abs/2409.17663)
+ [Deepseek-r1: Incentivizing reasoning capability in llms via reinforcement learning](https://arxiv.org/abs/2501.12948)
+ [video-salmonn-o1: Reasoning-enhanced audio-visual large language model](https://arxiv.org/abs/2502.11775)
+ [Echoink-r1: Exploring audio-visual reasoning in multimodal llms via reinforcement learning](https://arxiv.org/abs/2505.04623)
+ [Omni-R1: Reinforcement Learning for Omnimodal Reasoning via Two-System Collaboration](https://arxiv.org/abs/2505.20256)
+ [Avatar: Reinforcement learning to see, hear, and reason over video](https://arxiv.org/abs/2508.03100)
+ [ThinkOmni: Lifting Textual Reasoning to Omni-modal Scenarios via Guidance Decoding](https://arxiv.org/abs/2602.23306)
+ [AVCD: Mitigating Hallucinations in Audio-Visual Large Language Models through Contrastive Decoding](https://arxiv.org/abs/2505.20862)
+ [Fork-merge decoding: Enhancing multimodal understanding in audio-visual large language models](https://arxiv.org/abs/2505.20873)
+ [Introducing OpenAI o3 and o4-mini](https://arxiv.org/abs/2502.02844)
+ [Gemini 2.5: Pushing the frontier with advanced reasoning, multimodality, long context, and next generation agentic capabilities](https://arxiv.org/abs/2507.06261)
+ [Qwen3-omni technical report](https://arxiv.org/abs/2509.17765)
+ [Omnibench: Towards the future of universal omni-language models](https://arxiv.org/abs/2409.15272)
+ [Daily-Omni: Towards Audio-Visual Reasoning with Temporal Alignment across Modalities](https://arxiv.org/abs/2505.17862)
+ [Aura: A fine-grained benchmark and decomposed metric for audio-visual reasoning](https://arxiv.org/abs/2508.07470)
+ [JointAVBench: A Benchmark for Joint Audio-Visual Reasoning Evaluation](https://arxiv.org/abs/2512.12772)
+ [OmniVideoBench: Towards Audio-Visual Understanding Evaluation for Omni MLLMs](https://arxiv.org/abs/2510.10689)
+ [When Eyes and Ears Disagree: Can MLLMs Discern Audio-Visual Confusion?](https://arxiv.org/abs/2503.14608)
+ [Unified-io 2: Scaling autoregressive multimodal models with vision language audio and action](https://arxiv.org/abs/2406.01865)
+ [Videollama 2: Advancing spatial-temporal modeling and audio understanding in video-llms](https://arxiv.org/abs/2406.07476)
+ [Ola: Pushing the frontiers of omni-modal language model](https://arxiv.org/abs/2502.04328)
+ [Qwen2. 5-omni technical report](https://arxiv.org/abs/2503.20215)

---

# 🎨 Audio-Visual Generation

Audio-visual generation studies how to synthesize temporally aligned sound and imagery from text, images, video, or audio. This section covers conditional generation, cross-modal generation, and joint audio-visual generation.

## Conditional Audio/Visual Generation

### Conditional Audio Generation

+ [Audioldm 2: Learning holistic audio generation with self-supervised pretraining](https://arxiv.org/abs/2305.14674)
+ [Stable Audio Open](https://arxiv.org/abs/2407.04822)
+ [Audiolm: a language modeling approach to audio generation](https://arxiv.org/abs/2209.15156)
+ [AudioX: A Unified Framework for Anything-to-Audio Generation](https://arxiv.org/abs/2503.10522)
+ [TF-GridNet: Making time-frequency domain models great again for monaural speaker separation](https://arxiv.org/abs/2209.03930)
+ [Dual-path mamba: Short and long-term bidirectional selective structured state space models for speech separation](https://arxiv.org/abs/2412.04581)
+ [Audio prompt tuning for universal sound separation](https://arxiv.org/abs/2403.08826)
+ [Music source separation with band-split RNN](https://arxiv.org/abs/2209.15174)
+ [Hybrid transformers for music source separation](https://arxiv.org/abs/2309.02612)
+ [AUDIT: Audio Editing by Following Instructions with Latent Diffusion Models](https://arxiv.org/abs/2304.00830)
+ [SAO-Instruct: Free-form Audio Editing using Natural Language Instructions](https://arxiv.org/abs/2510.22795)
+ [Guiding Audio Editing with Audio Language Model](https://arxiv.org/abs/2509.21625)
+ [SteerMusic: Enhanced Musical Consistency for Zero-shot Text-Guided and Personalized Music Editing](https://arxiv.org/abs/2504.10826)
+ [Step-Audio-EditX Technical Report](https://arxiv.org/abs/2511.03601)
+ [Towards Emotionally Consistent Text-Based Speech Editing: Introducing EmoCorrector and the ECD-TSE Dataset](https://arxiv.org/abs/2503.12603)
+ [Diffusion-Based Voice Conversion with Fast Maximum Likelihood Sampling Scheme](https://arxiv.org/abs/2210.17057)
+ [Solving audio inverse problems with a diffusion model](https://arxiv.org/abs/2305.14674)
+ [Music Style Transfer with Time-Varying Inversion of Diffusion Models](https://arxiv.org/abs/2402.13763)

### Conditional Visual Generation

+ [Hierarchical text-conditional image generation with clip latents](https://arxiv.org/abs/2204.06125)
+ [High-resolution image synthesis with latent diffusion models](https://arxiv.org/abs/2112.10752)
+ [Gpt-4o system card](https://arxiv.org/abs/2410.21276)
+ [Hunyuanimage 3.0 technical report](https://arxiv.org/abs/2509.23951)
+ [Qwen-image technical report](https://arxiv.org/abs/2508.02324)
+ [JoyAI-Image: Awakening Spatial Intelligence in Unified Multimodal Understanding](https://arxiv.org/abs/2503.01862)
+ [Make-A-Video: Text-to-Video Generation without Text-Video Data](https://arxiv.org/abs/2209.14792)
+ [Imagen Video: High Definition Video Generation with Diffusion Models](https://arxiv.org/abs/2210.02303)
+ [Video Generation Models as World Simulators](https://arxiv.org/abs/2402.17177)
+ [Veo 3: Tech Report](https://storage.googleapis.com/deepmind-media/veo/Veo-3-Tech-Report.pdf)
+ [Step-Video-T2V Technical Report: The Practice, Challenges, and Future of Video Foundation Model](https://arxiv.org/abs/2502.10248)
+ [Hunyuanvideo: A systematic framework for large video generative models](https://arxiv.org/abs/2412.03603)
+ [Wan: Open and advanced large-scale video generative models](https://arxiv.org/abs/2503.20314)
+ [LongCat-Video Technical Report](https://arxiv.org/abs/2510.22200)
+ [Seedance 2.0: Unified Multimodal Audio-Video Joint Generation](https://arxiv.org/abs/2503.01862)
+ [StreamingT2V: Consistent, Dynamic, and Extendable Long Video Generation from Text](https://arxiv.org/abs/2403.14773)
+ [Stable Video Infinity: Infinite-Length Video Generation with Error Recycling](https://arxiv.org/abs/2510.09212)
+ [StreamDiT: Real-Time Streaming Text-to-Video Generation](https://arxiv.org/abs/2507.03745)
+ [Self forcing: Bridging the train-test gap in autoregressive video diffusion](https://arxiv.org/abs/2506.08009)
+ [LoL: Longer than Longer, Scaling Video Generation to Hour](https://arxiv.org/abs/2601.16914)
+ [Adding conditional control to text-to-image diffusion models](https://arxiv.org/abs/2302.05543)
+ [ControlVideo: Training-free Controllable Text-to-Video Generation](https://arxiv.org/abs/2305.13077)
+ [Motion-I2V: Consistent and Controllable Image-to-Video Generation with Explicit Motion Modeling](https://arxiv.org/abs/2401.15977)
+ [Step-Video-TI2V Technical Report: A State-of-the-Art Text-Driven Image-to-Video Generation Model](https://arxiv.org/abs/2503.11251)
+ [Generative Inbetweening: Adapting Image-to-Video Models for Keyframe Interpolation](https://arxiv.org/abs/2408.15239)
+ [Adapting Image-to-Video Diffusion Models for Large-Motion Frame Interpolation](https://arxiv.org/abs/2412.17042)
+ [ViBiDSampler: Enhancing Video Interpolation Using Bidirectional Diffusion Sampler](https://arxiv.org/abs/2410.05651)
+ [InstructPix2Pix: Learning to Follow Image Editing Instructions](https://arxiv.org/abs/2211.09800)
+ [Video-p2p: Video editing with cross-attention control](https://arxiv.org/abs/2304.10303)
+ [DreamVE: Unified Instruction-based Image and Video Editing](https://arxiv.org/abs/2508.06080)
+ [InsViE-1M: Effective Instruction-based Video Editing with Elaborate Dataset Construction](https://arxiv.org/abs/2503.00603)

## Audio-Visual Cross-Modal Generation

### Video-to-Audio Generation

+ [Diff-foley: Synchronized video-to-audio synthesis with latent diffusion models](https://arxiv.org/abs/2306.17210)
+ [FoleyCrafter: Bring Silent Videos to Life with Lifelike and Synchronized Sounds](https://arxiv.org/abs/2407.01494)
+ [Frieren: Efficient Video-to-Audio Generation Network with Rectified Flow Matching](https://arxiv.org/abs/2406.00320)
+ [Tri-Ergon: Fine-grained Video-to-Audio Generation with Multi-modal Conditions and LUFS Control](https://arxiv.org/abs/2412.20378)
+ [MMAudio: Taming Multimodal Joint Training for High-Quality Video-to-Audio Synthesis](https://arxiv.org/abs/2503.07539)
+ [Smooth-Foley: Creating Continuous Sound for Video-to-Audio Generation Under Semantic Guidance](https://arxiv.org/abs/2412.18157)
+ [Kling-foley: Multimodal diffusion transformer for high-quality video-to-audio generation](https://arxiv.org/abs/2506.19774)
+ [HunyuanVideo-Foley: Multimodal Diffusion with Representation Alignment for High-Fidelity Foley Audio Generation](https://arxiv.org/abs/2508.16930)
+ [ThinkSound: Chain-of-Thought Reasoning in Multimodal Large Language Models for Audio Generation and Editing](https://arxiv.org/abs/2506.21448)
+ [PrismAudio: Decomposed Chain-of-Thoughts and Multi-dimensional Rewards for Video-to-Audio Generation](https://arxiv.org/abs/2511.18833)
+ [DreamFoley: Scalable VLMs for High-Fidelity Video-to-Audio Generation](https://arxiv.org/abs/2512.06022)
+ [Omni2Sound: Towards Unified Video-Text-to-Audio Generation](https://arxiv.org/abs/2601.02731)
+ [ALIVE: Animate Your World with Lifelike Audio-Video Generation](https://arxiv.org/abs/2602.08682)
+ [Echoes Over Time: Unlocking Length Generalization in Video-to-Audio Generation Models](https://arxiv.org/abs/2602.20981)
+ [AV-Link: Temporally-Aligned Diffusion Features for Cross-Modal Audio-Video Generation](https://arxiv.org/abs/2412.15191)
+ [Vggsound: A large-scale audio-visual dataset](https://arxiv.org/abs/2004.14331)
+ [Audio set: An ontology and human-labeled dataset for audio events](https://arxiv.org/abs/1609.08198)
+ [Visually indicated sounds](https://arxiv.org/abs/1604.06960)
+ [Audio-synchronized visual animation](https://arxiv.org/abs/2405.15371)
+ [FoleyBench: A Benchmark for Video-to-Audio Models](https://arxiv.org/abs/2511.13219)

### Audio-to-Video Generation

+ [MusicInfuser: Making Video Diffusion Listen and Dance](https://arxiv.org/abs/2503.14505)
+ [Diverse and aligned audio-to-video generation via text-to-video model adaptation](https://arxiv.org/abs/2305.14674)
+ [AV-Link: Temporally-Aligned Diffusion Features for Cross-Modal Audio-Video Generation](https://arxiv.org/abs/2412.15191)
+ [Choreomuse: Robust music-to-dance video generation with style transfer and beat-adherent motion](https://arxiv.org/abs/2503.01862)
+ [Let's play music: Audio-driven performance video generation](https://arxiv.org/abs/2104.10993)
+ [Difftalk: Crafting diffusion models for generalized audio-driven portraits animation](https://arxiv.org/abs/2301.03286)
+ [AudCast: Audio-Driven Human Video Generation by Cascaded Diffusion Transformers](https://arxiv.org/abs/2503.01862)
+ [AI Choreographer: Music Conditioned 3D Dance Generation with AIST++](https://arxiv.org/abs/2106.09149)
+ [Music-driven group choreography](https://arxiv.org/abs/2306.09149)
+ [VoxCeleb2: Deep Speaker Recognition](https://arxiv.org/abs/1806.05687)
+ [Flow-Guided One-Shot Talking Face Generation With a High-Resolution Audio-Visual Dataset](https://arxiv.org/abs/2203.07635)
+ [Vggsound: A large-scale audio-visual dataset](https://arxiv.org/abs/2004.14331)

### Audio-Synchronized Image Animation

+ [A lip sync expert is all you need for speech to lip generation in the wild](https://arxiv.org/abs/2006.09058)
+ [Hallo3: Highly dynamic and realistic portrait image animation with video diffusion transformer](https://arxiv.org/abs/2412.00790)
+ [Audio-synchronized visual animation](https://arxiv.org/abs/2405.15371)
+ [Wan-s2v: Audio-driven cinematic video generation](https://arxiv.org/abs/2508.18621)
+ [Difftalk: Crafting diffusion models for generalized audio-driven portraits animation](https://arxiv.org/abs/2301.03286)
+ [SadTalker: Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Single Image Talking Face Animation](https://arxiv.org/abs/2211.12194)
+ [Emo: Emote portrait alive generating expressive portrait videos with audio2video diffusion model under weak conditions](https://arxiv.org/abs/2504.03415)
+ [Vasa-1: Lifelike audio-driven talking faces generated in real time](https://arxiv.org/abs/2404.10667)
+ [Hallo2: Long-duration and high-resolution audio-driven portrait image animation](https://arxiv.org/abs/2410.07718)
+ [Fantasytalking: Realistic talking portrait generation via coherent motion synthesis](https://arxiv.org/abs/2503.12603)
+ [Stableavatar: Infinite-length audio-driven avatar video generation](https://arxiv.org/abs/2508.08248)
+ [Echomimicv2: Towards striking, simplified, and semi-body human animation](https://arxiv.org/abs/2410.06053)
+ [Echomimicv3: 1.3 b parameters are all you need for unified multi-modal and multi-task human animation](https://arxiv.org/abs/2502.04223)
+ [Emo2: End-effector guided audio-driven avatar video generation](https://arxiv.org/abs/2501.10687)
+ [Omniavatar: Efficient audio-driven avatar video generation with adaptive body animation](https://arxiv.org/abs/2506.18866)
+ [Omnihuman-1: Rethinking the scaling-up of one-stage conditioned human animation models](https://arxiv.org/abs/2502.19254)
+ [Humo: Human-centric video generation via collaborative multi-modal conditioning](https://arxiv.org/abs/2509.08519)
+ [AudCast: Audio-Driven Human Video Generation by Cascaded Diffusion Transformers](https://arxiv.org/abs/2503.01862)
+ [Playmate2: Training-Free Multi-Character Audio-Driven Animation via Diffusion Transformer with Reward Feedback](https://arxiv.org/abs/2510.12089)
+ [Hunyuanvideo-avatar: High-fidelity audio-driven human animation for multiple characters](https://arxiv.org/abs/2505.20156)
+ [Kling-avatar: Grounding multimodal instructions for cascaded long-duration avatar animation synthesis](https://arxiv.org/abs/2509.09595)
+ [Klingavatar 2.0 technical report](https://arxiv.org/abs/2512.13313)
+ [JoyAvatar: Unlocking Highly Expressive Avatars via Harmonized Text-Audio Conditioning](https://arxiv.org/abs/2602.00702)
+ [Keyvid: Keyframe-aware video diffusion for audio-synchronized visual animation](https://arxiv.org/abs/2504.09656)
+ [Scaling Up Audio-Synchronized Visual Animation: An Efficient Training Paradigm](https://arxiv.org/abs/2508.03955)
+ [TIA2V: Video generation conditioned on triple modalities of text--image--audio](https://arxiv.org/abs/2502.02273)
+ [Syncphony: Synchronized Audio-to-Video Generation with Diffusion Transformers](https://arxiv.org/abs/2509.21893)
+ [SkyReels-V4: Multi-modal Video-Audio Generation, Inpainting and Editing model](https://arxiv.org/abs/2602.21818)
+ [Seedance 2.0: Unified Multimodal Audio-Video Joint Generation](https://arxiv.org/abs/2503.01862)
+ [Veo 3: Tech Report](https://storage.googleapis.com/deepmind-media/veo/Veo-3-Tech-Report.pdf)
+ [Voxceleb: a large-scale speaker identification dataset](https://arxiv.org/abs/1706.08612)
+ [VoxCeleb2: Deep Speaker Recognition](https://arxiv.org/abs/1806.05687)
+ [Lip reading sentences in the wild](https://arxiv.org/abs/1612.05368)
+ [LRS3-TED: a large-scale dataset for visual speech recognition](https://arxiv.org/abs/1809.00496)
+ [Flow-Guided One-Shot Talking Face Generation With a High-Resolution Audio-Visual Dataset](https://arxiv.org/abs/2203.07635)
+ [CelebV-HQ: A large-scale video facial attributes dataset](https://arxiv.org/abs/2203.04075)
+ [TalkVid: A Large-Scale Diversified Dataset for Audio-Driven Talking Head Synthesis](https://arxiv.org/abs/2508.13618)
+ [TalkVerse: Democratizing Minute-Long Audio-Driven Video Generation](https://arxiv.org/abs/2512.14938)
+ [Talkcuts: A large-scale dataset for multi-shot human speech video generation](https://arxiv.org/abs/2510.07249)
+ [Multi-human Interactive Talking Dataset](https://arxiv.org/abs/2508.03050)
+ [THEval. Evaluation Framework for Talking Head Video Generation](https://arxiv.org/abs/2511.04520)
+ [EvalTalker: Learning to Evaluate Real-Portrait-Driven Multi-Subject Talking Humans](https://arxiv.org/abs/2512.01340)

### Audio-Driven 3D Visual Generation

+ [Capture, Learning, and Synthesis of 3D Speaking Styles](https://arxiv.org/abs/1904.06662)
+ [MeshTalk: 3D Face Animation From Speech Using Cross-Modality Disentanglement](https://arxiv.org/abs/2104.09756)
+ [FaceFormer: Speech-Driven 3D Facial Animation With Transformers](https://arxiv.org/abs/2112.05329)
+ [Codetalker: Speech-driven 3d facial animation with discrete motion prior](https://arxiv.org/abs/2305.19551)
+ [StreamingTalker: Audio-driven 3D Facial Animation with Autoregressive Diffusion Model](https://arxiv.org/abs/2511.14223)
+ [AD-NeRF: Audio Driven Neural Radiance Fields for Talking Head Synthesis](https://arxiv.org/abs/2112.09523)
+ [GeneFace: Generalized and High-Fidelity Audio-Driven 3D Talking Face Synthesis](https://openreview.net/forum?id=YfwMIDhPccD)
+ [Gaussiantalker: Speaker-specific talking head synthesis via 3d gaussian splatting](https://arxiv.org/abs/2404.16012)
+ [Syngauss: real-time 3d gaussian splatting for audio-driven talking head synthesis](https://arxiv.org/abs/2503.07560)
+ [Audio-Driven Emotional Video Portraits](https://arxiv.org/abs/2105.00979)
+ [DreamTalk: When Expressive Talking Head Generation Meets Diffusion Probabilistic Models](https://arxiv.org/abs/2312.09767)
+ [EmoGene: Audio-Driven Emotional 3D Talking-Head Generation](https://arxiv.org/abs/2410.17262)
+ [Generating Holistic 3D Human Motion From Speech](https://arxiv.org/abs/2305.19216)
+ [EMAGE: Towards Unified Holistic Co-Speech Gesture Generation via Expressive Masked Audio Gesture Modeling](https://arxiv.org/abs/2401.00340)
+ [Stereo-Talker: Audio-driven 3D Human Synthesis with Prior-Guided Mixture-of-Experts](https://arxiv.org/abs/2410.23836)
+ [Real3D-Portrait: One-shot Realistic 3D Talking Portrait Synthesis](https://openreview.net/forum?id=7ERQPyR2eb)
+ [VoxCeleb2: Deep Speaker Recognition](https://arxiv.org/abs/1806.05687)
+ [Flow-Guided One-Shot Talking Face Generation With a High-Resolution Audio-Visual Dataset](https://arxiv.org/abs/2203.07635)
+ [MEAD: A Large-Scale Audio-Visual Dataset for Emotional Talking-Face Generation](https://arxiv.org/abs/2008.04340)

## Joint Audio-Visual Generation

### Text-to-Audio-Video Generation

+ [Javisdit: Joint audio-video diffusion transformer with hierarchical spatio-temporal prior synchronization](https://arxiv.org/abs/2503.23377)
+ [Mm-diffusion: Learning multi-modal diffusion models for joint audio and video generation](https://arxiv.org/abs/2302.06194)
+ [Sound-guided semantic video generation](https://arxiv.org/abs/2203.15389)
+ [AI Choreographer: Music Conditioned 3D Dance Generation with AIST++](https://arxiv.org/abs/2106.09149)
+ [UniVerse-1: Unified Audio-Video Generation via Stitching of Experts](https://arxiv.org/abs/2509.06155)
+ [Taming Text-to-Sounding Video Generation via Advanced Modality Condition and Interaction](https://arxiv.org/abs/2510.03117)
+ [Ovi: Twin backbone cross-modal fusion for audio-video generation](https://arxiv.org/abs/2510.01284)
+ [JoVA: Unified Multimodal Learning for Joint Video-Audio Generation](https://arxiv.org/abs/2512.13677)
+ [JavisDiT++: Unified Modeling and Optimization for Joint Audio-Video Generation](https://arxiv.org/abs/2602.19163)
+ [UniForm: A Unified Multi-Task Diffusion Transformer for Audio-Video Generation](https://arxiv.org/abs/2502.03897)
+ [Harmony: Harmonizing Audio and Video Generation through Cross-Task Synergy](https://arxiv.org/abs/2511.21579)
+ [MOVA: Towards Scalable and Synchronized Video-Audio Generation](https://arxiv.org/abs/2602.08794)
+ [Uniavgen: Unified audio and video generation with asymmetric cross-modal interactions](https://arxiv.org/abs/2511.03334)
+ [Klear: Unified Multi-Task Audio-Video Joint Generation](https://arxiv.org/abs/2601.04151)
+ [OmniForcing: Unleashing Real-time Joint Audio-Visual Generation](https://arxiv.org/abs/2603.11647)
+ [Improving video generation with human feedback](https://arxiv.org/abs/2501.13918)
+ [Flow-grpo: Training flow matching models via online rl](https://arxiv.org/abs/2505.05470)
+ [Seedance 1.5 pro: A Native Audio-Visual Joint Generation Foundation Model](https://arxiv.org/abs/2512.13507)
+ [MV-Crafter: An Intelligent System for Music-guided Video Generation](https://doi.org/10.1145/3748515)
+ [ReelWave: Multi-Agentic Movie Sound Generation through Multimodal LLM Conversation](https://arxiv.org/abs/2503.07217)
+ [Orchestrating Audio: Multi-Agent Framework for Long-Video Audio Synthesis](https://aclanthology.org/2025.emnlp-main.1133/)
+ [AutoMV: An Automatic Multi-Agent System for Music Video Generation](https://arxiv.org/abs/2512.12196)
+ [AesopAgent: Agent-driven Evolutionary System on Story-to-Video Production](https://arxiv.org/abs/2403.07952)
+ [MM-StoryAgent: Immersive Narrated Storybook Video Generation with a Multi-Agent Paradigm across Text, Image and Audio](https://arxiv.org/abs/2503.05242)
+ [Automated Movie Generation via Multi-Agent CoT Planning](https://arxiv.org/abs/2503.07314)
+ [AniME: Adaptive Multi-Agent Planning for Long Animation Generation](https://doi.org/10.1145/3757374.3771455)
+ [MAViS: A Multi-Agent Framework for Long-Sequence Video Storytelling](https://aclanthology.org/2026.eacl-long.101/)
+ [Veo 3: Tech Report](https://storage.googleapis.com/deepmind-media/veo/Veo-3-Tech-Report.pdf)
+ [LTX-2: Efficient Joint Audio-Visual Foundation Model](https://arxiv.org/abs/2601.03233)
+ [Visually indicated sounds](https://arxiv.org/abs/1604.06960)
+ [Vggsound: A large-scale audio-visual dataset](https://arxiv.org/abs/2004.14331)
+ [Audio-synchronized visual animation](https://arxiv.org/abs/2405.15371)
+ [VABench: A Comprehensive Benchmark for Audio-Video Generation](https://arxiv.org/abs/2512.09299)
+ [T2AV-Compass: Towards Unified Evaluation for Text-to-Audio-Video Generation](https://arxiv.org/abs/2512.21094)
+ [PhyAVBench: A Challenging Audio Physics-Sensitivity Benchmark for Physically Grounded Text-to-Audio-Video Generation](https://arxiv.org/abs/2512.23994)

### Image-to-Audio-Video Generation

+ [Stable video diffusion: Scaling latent video diffusion models to large datasets](https://arxiv.org/abs/2311.15127)
+ [I hear your true colors: Image guided audio generation](https://arxiv.org/abs/2305.19461)
+ [Diff-foley: Synchronized video-to-audio synthesis with latent diffusion models](https://arxiv.org/abs/2306.17210)
+ [FoleyCrafter: Bring Silent Videos to Life with Lifelike and Synchronized Sounds](https://arxiv.org/abs/2407.01494)
+ [Cogvideo: Large-scale pretraining for text-to-video generation via transformers](https://arxiv.org/abs/2205.15868)
+ [Hunyuanvideo: A systematic framework for large video generative models](https://arxiv.org/abs/2412.03603)
+ [Audioldm 2: Learning holistic audio generation with self-supervised pretraining](https://arxiv.org/abs/2305.14674)
+ [Animate and Sound an Image](https://arxiv.org/abs/2503.01862)
+ [UniVerse-1: Unified Audio-Video Generation via Stitching of Experts](https://arxiv.org/abs/2509.06155)
+ [Ovi: Twin backbone cross-modal fusion for audio-video generation](https://arxiv.org/abs/2510.01284)
+ [Klear: Unified Multi-Task Audio-Video Joint Generation](https://arxiv.org/abs/2601.04151)
+ [ALIVE: Animate Your World with Lifelike Audio-Video Generation](https://arxiv.org/abs/2602.08682)
+ [SkyReels-V4: Multi-modal Video-Audio Generation, Inpainting and Editing model](https://arxiv.org/abs/2602.21818)
+ [Wan: Open and advanced large-scale video generative models](https://arxiv.org/abs/2503.20314)
+ [Seedance 1.5 pro: A Native Audio-Visual Joint Generation Foundation Model](https://arxiv.org/abs/2512.13507)
+ [Seedance 2.0: Unified Multimodal Audio-Video Joint Generation](https://arxiv.org/abs/2503.01862)
+ [Vidu Q3: 16s AI Video with Native Audio](https://www.vidu.com/vidu-q3)
+ [Video Generation Models as World Simulators](https://arxiv.org/abs/2402.17177)
+ [Veo 3: Tech Report](https://storage.googleapis.com/deepmind-media/veo/Veo-3-Tech-Report.pdf)
+ [Introducing Runway GWM-1](https://runwayml.com/research/introducing-runway-gwm-1)
+ [Audio-synchronized visual animation](https://arxiv.org/abs/2405.15371)

### Joint Audio-Video Editing

+ [Language-Guided Joint Audio-Visual Editing via One-Shot Adaptation](https://arxiv.org/abs/2410.07463)
+ [Zero-Shot Audio-Visual Editing via Cross-Modal Delta Denoising](https://arxiv.org/abs/2503.12603)
+ [Object-AVEdit: An Object-level Audio-Visual Editing Model](https://arxiv.org/abs/2510.00050)
+ [VAInpaint: Zero-Shot Video-Audio inpainting framework with LLMs-driven Module](https://arxiv.org/abs/2509.17022)
+ [Schrodinger Audio-Visual Editor: Object-Level Audiovisual Removal](https://arxiv.org/abs/2512.12875)
+ [Audio-sync Video Instance Editing with Granularity-Aware Mask Refiner](https://arxiv.org/abs/2512.10571)
+ [Coherent Audio-Visual Editing via Conditional Audio Generation Following Video Edits](https://arxiv.org/abs/2512.07209)
+ [JUST-DUB-IT: Video Dubbing via Joint Audio-Visual Diffusion](https://arxiv.org/abs/2601.22143)
+ [Uniavgen: Unified audio and video generation with asymmetric cross-modal interactions](https://arxiv.org/abs/2511.03334)
+ [SkyReels-V4: Multi-modal Video-Audio Generation, Inpainting and Editing model](https://arxiv.org/abs/2602.21818)

---

# 🤝 Audio-Visual Interaction

Audio-visual interaction concerns systems that do not merely perceive multimodal content, but must respond to it in real time. This section covers conversational interaction and embodied interaction.

## Interactive Audio-Visual Conversation

### Audio-Driven Conversation

+ [Audiogpt: Understanding and generating speech, music, sound, and talking head](https://arxiv.org/abs/2304.12995)
+ [wav2vec: Unsupervised pre-training for speech recognition](https://arxiv.org/abs/1904.05862)
+ [Hubert: Self-supervised speech representation learning by masked prediction of hidden units](https://arxiv.org/abs/2106.07447)
+ [Robust speech recognition via large-scale weak supervision](https://arxiv.org/abs/2212.04356)
+ [Wavlm: Large-scale self-supervised pre-training for full stack speech processing](https://arxiv.org/abs/2110.13900)
+ [Qwen-audio: Advancing universal audio understanding via unified large-scale audio-language models](https://arxiv.org/abs/2311.07919)
+ [Qwen2-audio technical report](https://arxiv.org/abs/2407.10759)
+ [Speechverse: A large-scale generalizable audio language model](https://arxiv.org/abs/2405.08295)
+ [E-chat: Emotion-sensitive spoken dialogue system with large language models](https://arxiv.org/abs/2402.11521)
+ [Cosyvoice: A scalable multilingual zero-shot text-to-speech synthesizer based on supervised semantic tokens](https://arxiv.org/abs/2407.05407)
+ [Speechgpt: Empowering large language models with intrinsic cross-modal conversational abilities](https://arxiv.org/abs/2305.11000)
+ [Mini-omni: Language models can hear, talk while thinking in streaming](https://arxiv.org/abs/2408.16725)
+ [Llama-omni: Seamless speech interaction with large language models](https://arxiv.org/abs/2409.06666)
+ [Moshi: a speech-text foundation model for real-time dialogue](https://arxiv.org/abs/2410.00037)
+ [Intrinsicvoice: Empowering llms with intrinsic real-time voice interaction abilities](https://arxiv.org/abs/2410.08035)
+ [Omniflatten: An end-to-end gpt model for seamless voice conversation](https://arxiv.org/abs/2410.17777)
+ [Freeze-omni: A smart and low latency speech-to-speech dialogue model with frozen llm](https://arxiv.org/abs/2411.00774)
+ [Pslm: Parallel generation of text and speech with llms for low-latency spoken dialogue systems](https://arxiv.org/abs/2406.12428)
+ [Audio flamingo: A novel audio language model with few-shot learning and dialogue abilities](https://arxiv.org/abs/2402.01831)
+ [Audio flamingo 2: An audio-language model with long-audio understanding and expert reasoning abilities](https://arxiv.org/abs/2503.03983)
+ [Salmonn: Towards generic hearing abilities for large language models](https://arxiv.org/abs/2310.13289)
+ [Gama: A large audio-language model with advanced audio understanding and complex reasoning abilities](https://arxiv.org/abs/2406.11768)
+ [Lauragpt: Listen, attend, understand, and regenerate audio with gpt](https://arxiv.org/abs/2310.04673)
+ [Speechgpt-gen: Scaling chain-of-information speech generation](https://arxiv.org/abs/2401.13527)
+ [Clotho-aqa: A crowdsourced dataset for audio question answering](https://arxiv.org/abs/2207.07880)
+ [Audiocaps: Generating captions for audios in the wild](https://arxiv.org/abs/1706.08117)
+ [Muchomusic: Evaluating music understanding in multimodal audio-language models](https://arxiv.org/abs/2408.01337)
+ [Mustango: Toward controllable text-to-music generation](https://arxiv.org/abs/2408.02585)
+ [CMI-Bench: A Comprehensive Benchmark for Evaluating Music Instruction Following](https://arxiv.org/abs/2506.12285)
+ [LibriSQA: A novel dataset and framework for spoken question answering with large language models](https://arxiv.org/abs/2407.04822)
+ [Dynamic-superb: Towards a dynamic, collaborative, and comprehensive instruction-tuning benchmark for speech](https://arxiv.org/abs/2309.15656)
+ [Audiobench: A universal benchmark for audio large language models](https://arxiv.org/abs/2406.12905)
+ [Air-bench: Benchmarking large audio-language models via generative comprehension](https://arxiv.org/abs/2402.07729)
+ [Mmau: A massive multi-task audio understanding and reasoning benchmark](https://arxiv.org/abs/2410.19168)
+ [MMAR: A Challenging Benchmark for Deep Reasoning in Speech, Audio, Music, and Their Mix](https://arxiv.org/abs/2505.13032)

### Unified Visual Understanding and Generation

+ [Transfer between modalities with metaqueries](https://arxiv.org/abs/2504.06256)
+ [Blip3o-next: Next frontier of native image generation](https://arxiv.org/abs/2510.15857)
+ [Skywork unipic 2.0: Building kontext model with online rl for unified multimodal model](https://arxiv.org/abs/2509.04548)
+ [Emerging properties in unified multimodal pretraining](https://arxiv.org/abs/2505.14683)
+ [Janusflow: Harmonizing autoregression and rectified flow for unified multimodal understanding and generation](https://arxiv.org/abs/2411.11778)
+ [Show-o2: Improved native unified multimodal models](https://arxiv.org/abs/2506.15564)
+ [Chameleon: Mixed-Modal Early-Fusion Foundation Models](https://arxiv.org/abs/2405.09818)
+ [Janus-pro: Unified multimodal understanding and generation with data and model scaling](https://arxiv.org/abs/2501.17811)
+ [Selftok: Discrete visual tokens of autoregression, by diffusion, and for reasoning](https://arxiv.org/abs/2505.07538)
+ [Ming-univision: Joint image understanding and generation with a unified continuous tokenizer](https://arxiv.org/abs/2510.06590)
+ [LongCat-Next: Lexicalizing Modalities as Discrete Tokens](https://arxiv.org/abs/2603.27538)
+ [Harmonizing visual representations for unified multimodal understanding and generation](https://arxiv.org/abs/2503.01743)
+ [Skywork unipic: Unified autoregressive modeling for visual understanding and generation](https://arxiv.org/abs/2508.03320)
+ [Omni-Diffusion: Unified Multimodal Understanding and Generation with Masked Discrete Diffusion](https://arxiv.org/abs/2603.06577)
+ [LLaDA-o: An Effective and Length-Adaptive Omni Diffusion Model](https://arxiv.org/abs/2603.01068)
+ [Omni-video: Democratizing unified video understanding and generation](https://arxiv.org/abs/2507.06119)
+ [Univid: The open-source unified video model](https://arxiv.org/abs/2509.24200)
+ [Univideo: Unified understanding, generation, and editing for videos](https://arxiv.org/abs/2510.08377)
+ [Divot: Diffusion Powers Video Tokenizer for Comprehension and Generation](https://arxiv.org/abs/2503.12658)
+ [Uni-ViGU: Towards Unified Video Generation and Understanding via A Diffusion-Based Video Generator](https://arxiv.org/abs/2604.08121)
+ [Microsoft coco captions: Data collection and evaluation server](https://arxiv.org/abs/1504.00325)
+ [Nocaps: Novel object captioning at scale](https://arxiv.org/abs/1811.00691)
+ [Making the v in vqa matter: Elevating the role of image understanding in visual question answering](https://arxiv.org/abs/1612.07047)
+ [Gqa: A new dataset for real-world visual reasoning and compositional question answering](https://arxiv.org/abs/1902.09506)
+ [Scienceqa: A novel resource for question answering on scholarly articles](https://arxiv.org/abs/2209.00562)
+ [Mmbench: Is your multi-modal model an all-around player?](https://arxiv.org/abs/2307.04950)
+ [Seed-bench: Benchmarking multimodal llms with generative comprehension](https://arxiv.org/abs/2307.16125)
+ [Microsoft COCO: Common Objects in Context](https://arxiv.org/abs/1405.0312)
+ [Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding](https://arxiv.org/abs/2205.11487)
+ [Geneval: An object-focused framework for evaluating text-to-image alignment](https://arxiv.org/abs/2310.11513)
+ [Video question answering via gradually refined attention over appearance and motion](https://arxiv.org/abs/1704.04140)
+ [Activitynet-qa: A dataset for understanding complex web videos via question answering](https://arxiv.org/abs/1906.01040)
+ [Tvqa: Localized, compositional video question answering](https://arxiv.org/abs/1811.00940)
+ 
+ [MSR-VTT: A Large Video Description Dataset for Bridging Video and Language](https://arxiv.org/abs/1604.07929)
+ [Vbench: Comprehensive benchmark suite for video generative models](https://arxiv.org/abs/2311.17982)

### Omni-Modal Audio-Visual Conversation

+ [Mini-omni: Language models can hear, talk while thinking in streaming](https://arxiv.org/abs/2408.16725)
+ [Mini-omni2: Towards open-source gpt-4o with vision, speech and duplex capabilities](https://arxiv.org/abs/2410.11190)
+ [Vita-1.5: Towards gpt-4o level real-time vision and speech interaction](https://arxiv.org/abs/2501.01957)
+ [Interactiveomni: A unified omni-modal model for audio-visual multi-turn dialogue](https://arxiv.org/abs/2510.13747)
+ [Baichuan-Omni-1.5 Technical Report](https://arxiv.org/abs/2501.15368)
+ [Gpt-4o system card](https://arxiv.org/abs/2410.21276)
+ [Gemini 3.1 Flash Live Model Card](https://deepmind.google/models/model-cards/gemini-3-1-flash-live/)
+ [Qwen2. 5-omni technical report](https://arxiv.org/abs/2503.20215)
+ [Qwen3-omni technical report](https://arxiv.org/abs/2509.17765)
+ [Ming-Omni: A Unified Multimodal Model for Perception and Generation](https://arxiv.org/abs/2506.09344)
+ [Longcat-flash-omni technical report](https://arxiv.org/abs/2511.00279)
+ [Let's Go Real Talk: Spoken Dialogue Model for Face-to-Face Conversation](https://arxiv.org/abs/2406.07867)
+ [VideoPoet: A Large Language Model for Zero-Shot Video Generation](https://arxiv.org/abs/2312.14125)
+ [Next-gpt: Any-to-any multimodal llm](https://arxiv.org/abs/2409.18613)
+ [Unified-io 2: Scaling autoregressive multimodal models with vision language audio and action](https://arxiv.org/abs/2406.01865)
+ [Javisgpt: A unified multi-modal llm for sounding-video comprehension and generation](https://arxiv.org/abs/2512.22905)
+ [X-streamer: Unified human world modeling with audiovisual interaction](https://arxiv.org/abs/2509.21574)
+ [AR-Omni: A Unified Autoregressive Model for Any-to-Any Generation](https://arxiv.org/abs/2601.17761)
+ [Cat: Enhancing multimodal large language model to answer questions in dynamic audio-visual scenarios](https://arxiv.org/abs/2405.12104)
+ [Video-chatgpt: Towards detailed video understanding via large vision and language models](https://arxiv.org/abs/2310.02913)
+ [Video-mme: The first-ever comprehensive evaluation benchmark of multi-modal llms in video analysis](https://arxiv.org/abs/2405.21075)
+ [OmniVideoBench: Towards Audio-Visual Understanding Evaluation for Omni MLLMs](https://arxiv.org/abs/2510.10689)

## Interactive Audio-Visual Embodiment

### Audio-Visual Navigation

+ [SoundSpaces: Audio-Visual Navigation in 3D Environments](https://arxiv.org/abs/1912.11474)
+ [Audio-Guided Dynamic Modality Fusion with Stereo-Aware Attention for Audio-Visual Navigation](https://arxiv.org/abs/2509.16924)
+ [Omnidirectional Information Gathering for Knowledge Transfer-based Audio-Visual Navigation](https://arxiv.org/abs/2308.10306)
+ [Learning to Set Waypoints for Audio-Visual Navigation](https://arxiv.org/abs/2008.09622)
+ [Look, Listen, and Act: Towards Audio-Visual Embodied Navigation](https://arxiv.org/abs/1912.11684)
+ [Transformer memory for interactive visual navigation in cluttered environments](https://arxiv.org/abs/2308.10306)
+ [Semantic Audio-Visual Navigation](https://arxiv.org/abs/2012.11583)
+ [Audio-Visual Navigation with Anti-Backtracking](https://arxiv.org/abs/2501.01058)
+ [Towards Audio-Visual Navigation in Noisy Environments: A Large-Scale Benchmark Dataset and an Architecture Considering Multiple Sound-Sources](https://arxiv.org/abs/2501.05172)
+ [Dual-Stream Gated Fusion for Audio-Visual Navigation](https://arxiv.org/abs/2501.08424)
+ [Boosting Audio-Visual Navigation Performance with Channel Attention in 3D Environments](https://arxiv.org/abs/2501.05172)
+ [Dynamical Audio-Visual Navigation: Catching Unheard Moving Sound Sources in Unmapped 3D Environments](https://arxiv.org/abs/2201.04279)
+ [Sound adversarial audio-visual navigation](https://arxiv.org/abs/2202.10910)
+ [Avlen: Audio-visual-language embodied navigation in 3d environments](https://arxiv.org/abs/2205.02882)
+ [Rila: Reflective and imaginative language agent for zero-shot semantic audio-visual navigation](https://arxiv.org/abs/2404.02095)
+ [Caven: An embodied conversational agent for efficient audio-visual navigation in noisy environments](https://arxiv.org/abs/2405.06502)
+ [Soundspaces 2.0: A simulation platform for visual-acoustic learning](https://arxiv.org/abs/2206.08312)
+ [Real Acoustic Fields: An Audio-Visual Room Acoustics Dataset and Benchmark](https://arxiv.org/abs/2403.18821)
+ [Sonicverse: A multisensory simulation platform for embodied household agents that see and hear](https://arxiv.org/abs/2306.00923)

### Audio-Visual Scene Understanding and Reconstruction

+ [Soundspaces 2.0: A simulation platform for visual-acoustic learning](https://arxiv.org/abs/2206.08312)
+ [Learning Neural Acoustic Fields](https://arxiv.org/abs/2205.13516)
+ [BatVision: Learning to See 3D Spatial Layout with Two Ears](https://arxiv.org/abs/2005.06715)
+ [Beyond Image to Depth: Improving Depth Prediction using Echoes](https://arxiv.org/abs/2103.08468)
+ [Few-Shot Audio-Visual Learning of Environment Acoustics](https://arxiv.org/abs/2203.12620)
+ [Av-nerf: Learning neural fields for real-world audio-visual scene synthesis](https://arxiv.org/abs/2305.11588)
+ [AV-GS: Learning Material and Geometry Aware Priors for Novel View Acoustic Synthesis](https://arxiv.org/abs/2406.08920)
+ [NeRAF: 3D Scene Infused Neural Radiance and Acoustic Fields](https://arxiv.org/abs/2405.18213)
+ [Audio visual language maps for robot navigation](https://arxiv.org/abs/2401.03796)
+ [Multimodal Spatial Language Maps for Robot Navigation and Manipulation](https://arxiv.org/abs/2406.07585)
+ [X-streamer: Unified human world modeling with audiovisual interaction](https://arxiv.org/abs/2509.21574)
+ [Sonicverse: A multisensory simulation platform for embodied household agents that see and hear](https://arxiv.org/abs/2306.00923)
+ [Real Acoustic Fields: An Audio-Visual Room Acoustics Dataset and Benchmark](https://arxiv.org/abs/2403.18821)

### Audio-Visual Embodiment Interaction and Manipulation

+ [Hearing touch: Audio-visual pretraining for contact-rich manipulation](https://arxiv.org/abs/2410.11740)
+ [See, hear, and feel: Smart sensory fusion for robotic manipulation](https://arxiv.org/abs/2212.03858)
+ [Audio-visual grounding referring expression for robotic manipulation](https://arxiv.org/abs/2209.08640)
+ [Sonicsense: Object perception from in-hand acoustic vibration](https://arxiv.org/abs/2406.17932)
+ [Learning Robot Manipulation from Audio World Models](https://arxiv.org/abs/2512.08405)
+ [Unified Multimodal Diffusion Forcing for Forceful Manipulation](https://arxiv.org/abs/2511.04812)
+ [The Sound of Simulation: Learning Multimodal Sim-to-Real Robot Policies with Generative Audio](https://arxiv.org/abs/2501.09176)
+ [Visual-auditory Extrinsic Contact Estimation](https://arxiv.org/abs/2409.14608)
+ [Vlas: Vision-language-action model with speech instructions for customized robot manipulation](https://arxiv.org/abs/2502.13508)
+ [Audio-VLA: Adding Contact Audio Perception to Vision-Language-Action Model for Robotic Manipulation](https://arxiv.org/abs/2511.09958)
+ [All robots in one: A new standard and unified dataset for versatile, general-purpose embodied agents](https://arxiv.org/abs/2408.10899)
+ [Maniwav: Learning robot manipulation from in-the-wild audio-visual data](https://arxiv.org/abs/2406.19464)
+ [Kaiwu: A Multimodal Manipulation Dataset and Framework for Robot Learning and Human-Robot Interaction](https://arxiv.org/abs/2503.05231)

---

<!-- # ❤️ Citation

> We would be honored if this work could assist you, and greatly appreciate it if you could consider starring and citing it:
```
@article{wang2025audiovisual,
  title={Audio-Visual Intelligence: A Comprehensive Survey},
  author={Wang, Yaoting and others},
  journal={arXiv preprint arXiv:2503.12605},
  year={2025}
}
```

---

# ⭐️ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yaotingwangofficial/Awesome-AVI&type=Date)](https://star-history.com/#yaotingwangofficial/Awesome-AVI&Date) -->
