<p align="center">
    <img src="./assets/readme/kotoba.png" width="250"/>
</p>
<div align="center">
    <a href="https://github.com/kotoba-tech/Open-GPT-4o/stargazers"><img src="https://img.shields.io/github/stars/kotoba-tech/Open-GPT-4o?style=social"></a>
    <a href="https://discord.gg/2GMpFwZ9"><img src="https://img.shields.io/badge/Discord-join-blueviolet?logo=discord&amp"></a>
    <a href="https://twitter.com/kotoba_tech"><img src="https://img.shields.io/badge/Twitter-Discuss-blue?logo=twitter&amp"></a>
</div>

## Open-GPT-4o: Democratizing Speech Foundation Models for All

We develop **Open-GPT-4o** with a focus on speech (audio) foundation models, receiving inspiration from the [Open-Sora](https://github.com/hpcaitech/Open-Sora) initiative. We will make models and training details accessible to everyone. Open-GPT-4o will open up an avenue for contributions from the open-source community and make technologies available in non-English languages (e.g., Asian languages like Japanese). 

**Under development. Currently we have building blocks: audio tokenization, voice cloning, text-to-speech, and fast ASR.**

## 📰 News

* **[2024.05.15]** Launching Open-GPT-4o.
* **[~2024.05.15]** Kotoba Technologies open-source preliminary building blocks towards Open-GPT-4o: [Kotoba-Speech](https://huggingface.co/kotoba-tech/kotoba-speech-v0.1) (a state-of-the-art Japanese voice cloning and text-to-speech model) and [Kotoba-Whisper](https://huggingface.co/kotoba-tech/kotoba-whisper-v1.0) (fast and accurate Japanese ASR, 6.3x faster than OpenAI Whisper-large with competitive performance).

## Latest Demo (To Be Updated)

We plan to create many demos using our foundation models. As a first step, we provide  [🤗 Kotoba-Speech Demo on HuggingFace](https://huggingface.co/spaces/kotoba-tech/Kotoba-Speech) and [🤗 Kotoba-Whisper Demo on HuggingFace](https://huggingface.co/spaces/kotoba-tech/kotoba-whisper-demo). These serve as building blocks for creating speech foundation models. 


## New Features/Updates
TBA

### TODO list 

* [ ] LLamma-recipes adaptation for text LLM integration ([@kojimano](https://github.com/kojimano))
* [ ] Collecting speech training data
    * [ ] Japanese ([@yuta0306](https://github.com/yuta0306))
    * [ ] English ([@yuta0306](https://github.com/yuta0306))
    * [ ] Vietnamese
    * [ ] Indonesian
* [ ] Audio tokenization BPE to reduce sequence lengths ([@jungokasai](https://github.com/jungokasai))
* [ ] Support streaming generation of audio (fully autoregressive token generation) ([@jungokasai](https://github.com/jungokasai))
* [ ] Add downstream task data
    * [ ] English <> Japanese speech translation 

## Contents

**Under development**

* [Installation](#installation)
* [Model Weights](#model-weights)
* [Inference](#inference)
* [Data Processing](#data-processing)
* [Training](#training)
* [Evaluation](#evaluation)
* [Contribution](#contribution)
* [Acknowledgement](#acknowledgement)


## Installation

### Open-GPT-4o Model Weights 

## Data Processing

## Training

### Open-GPT-4o Training

## Evaluation

## Contribution

## References
* [Jungo's quick tutorial video on audio tokenization](https://www.youtube.com/watch?v=2vu6u5CrMYQ)


## Acknowledgement

* [MetaVoice](https://github.com/metavoiceio/metavoice-src): An autoregressive (+non-autoregressive part) voice cloning/TTS model for English.
* [audiocraft](https://github.com/facebookresearch/audiocraft): Speech/audio tokenization model for preprocessing and generation.
* [llama recipes](https://github.com/meta-llama/llama-recipes): distirubted training library that supports llama's continuous training.
We are grateful for the amazing open-sourcing community. 
