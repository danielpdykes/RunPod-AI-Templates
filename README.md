# RunPod-AI-Templates
A list of various RunPod template resources for AI in the (GPU) cloud.

## Learning resources

1. [**Getting Started with RunPod Serverless**](https://trapdoor.cloud/getting-started-with-runpod-serverless/) - Some of the listed templates are for RunPod Serverless. If you're not familiar, read this
2. [**Using Stable Diffusion Kohya_ss ComfyUI Ultimate**](https://www.youtube.com/watch?v=N_zhQSx2Q3c) - Somewhat overly detailed tutorial for using Kohya_ss to train SDXL LoRAs. Checks in a nearly an hour. Covers RunPod and the Stable Diffusion Kohya_ss ComfyUI Ultimate RunPod tutorial. Based upon v.21.8 of Kohya.

## Generative image templates

1. [**Kohya_ss**](https://runpod.io/gsc?template=51q837fywe&ref=2xxro4sy) - Kohya_ss RunPod template. Use this to fine tune LoRA and checkpoint (dreambooth) models for use with Stable Diffusion [Author](https://github.com/ashleykleynhans/kohya-docker)
2. [**Stable Diffusion Kohya_ss ComfyUI Ultimate**](https://runpod.io/gsc?template=ya6013lj5a&ref=2xxro4sy) - A template for Automatic1111 which includes ControlNet, Roop, and Deforum extensions. It also contains Dreambooth and Kohya_ss, though I'd recommend using just the Kohya_ss template for fine tuning, along with ComfyUI if you prefer working with notes [Author](https://github.com/ashleykleynhans/stable-diffusion-docker)

## Audio generation and transcription templates

1. [**Text To Speech**](https://runpod.io/gsc?template=j898rhd8t6&ref=2xxro4sy) - Text To Speech Generation Web UI template thus Bark, MusicGen + AudioGen, Tortoise, RVC, Vocos, and Demucs. Offers multiple languages beyond English including French, German, and Spanish. [Author](https://github.com/ashleykleynhans/tts-generation-docker)
2. [**Whisper Worker**](https://github.com/runpod-workers/worker-whisper) - Whisper serverless worker for RunPod: Processing and transcribing audio with various Whisper models. Part of RunPod Workers collection.
