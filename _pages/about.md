---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I am Samyadeep Basu, a 3rd year CS PhD student at UMD, College Park (2022 - Present). I work with [Soheil Feizi](https://www.cs.umd.edu/~sfeizi/) in the [Center for Machine Learning](https://ml.umd.edu/). My research focus is reliable deep learning, where I build methods to understand models through the lens of data and control both generative and discriminative deep models using light-weight tweaks (aka model editing) or light-weight fine-tuning. Previously I received my MS from UMD in 2020 and then spent close to two years at Microsoft AI in the [ML rotation program](https://www.microsoftnewengland.com/maidap/). During my stint at Microsoft AI, I worked with the Language Science Team at [Azure AI](https://www.microsoft.com/en-us/research/group/cognitive-services-research/knowledge-and-language/) and [MSAI](https://www.microsoft.com/en-us/research/group/artificial-intelligence-research-munich/) where I researched, developed and deployed large-scale language models for various scenarios. 

My latest CV can be accessed at: [CV](https://drive.google.com/file/d/1fpDMF078bSlExDIFAzOgMxJ2Smbe2gpe/view?usp=sharing).

News 
======
 (September 2024): 2 papers on mechanistic interpretability for vision models and MLLMs accepted to NeurIPS 2024! 2 papers on VLM compositionality, VLM prompt tuning accepted to EMNLP 2024 (Main)!
 
 (August 2024): Finished an exciting internship at Adobe. Also excited to pass my PhD preliminary examination!

 (May 2024): Submitted multiple papers to NeurIPS on: (i) Multimodal VQA models, (ii) compositionality in t2i models, (iii) internal mechanistic understanding of ViTs and (iv) a new framework for copyright attribution in t2i models! 
 
 (April 2024): Excited to be rejoining Adobe Research for a summer internship to work on small language models!; Paper on diffusion model editing accepted to ICML 2024!
 
 (Jan 2024 - May 2024): Started an internship at Microsoft Research working on interpretability for multimodal language models!
 
 (January 2024) : Paper on diffusion model interpretability accepted to ICLR 2024!
 
 (December 2023) : Paper on few-shot finetuning for vision models accepted to AAAI 2024!
 
 (August-October 2023): Paper on surgical fine-tuning for "small" language models accepted to EMNLP 2023!
 
 (July 2023): Excited to announce two new projects : (i) Improving CLIP using knowledge distillation from diffusion models; (ii) Benchmark for text-guided  image editing methods! 
 
 (June 2023): Started internship at Adobe Research! Working on interpretability + model editing for text-to-image generative models!
 
 (Jan 2023): Paper on algorithm to design difficult few-shot tasks accepted at ICLR 2023!
 
 (September 2022): Finished an amazing research internship at [Microsoft Research](https://www.microsoft.com/en-us/research/) working with [Daniela Massiceti](https://www.microsoft.com/en-us/research/people/dmassiceti/) on few-shot learning!
 
 (Feb 2022): Started my PhD to work on few-shot learning and model interpretability!

 (October 2020 - Jan 2022) : Break from Grad School to work at Microsoft AI as an Applied Scientist!
 
 (Feb 2021): Papers on influence functions at ICLR 2021 and ICML 2020!

**Recent Preprints**
======
1. [Decomposing and Interpreting Image Representations via Text in ViTs Beyond CLIP](https://arxiv.org/abs/2406.01583)
   
   **NeurIPS 2024** 
   > We interpret different components of vision transformers using text!
   
   **Short version appearing at ICML 2024 mechanistic interpretability workshop as a Spotlight talk!**
  
2. [Rethinking Artistic Copyright Infringements in the Era of Text-to-Image Generative Models](https://arxiv.org/abs/2404.08030)

   **EvalEval @ Neurips 2024**
   > A new framework for copyright infringement detection from text-to-image models!

3. [Understanding Information Storage and Transfer in Multimodal Language Models](https://arxiv.org/html/2406.04236v1)
   
   **NeurIPS 2024**
   > Causality based approaches for model interpretability and editing methods extended to multimodal language models (e.g., LLaVa)

   **Also appearing at ECCV 2024 KGM Workshop as Oral Presentation!**

4. [Understanding and Mitigating Compositionality Issues in Text-to-Image Models](https://arxiv.org/abs/2406.07844)

   > We find two sources of error which leads to erroneous compositionality in text-to-image models and mitigate it with a strong baseline!
   
   

Selected Publications
======
1. [On Mechanistic Knowledge Localization in Text-to-Image Models](https://arxiv.org/abs/2405.01008)
   
   **ICML 2024** [Project Poster](https://drive.google.com/file/d/1LyiLP3sWK09m7SJ9gYIXqdXGKD7ER2Gv/view?usp=sharing) [Code](https://github.com/samyadeepbasu/LocoGen)
   > We investigate cross-attention layers in text-to-image models on knowledge storage!
     
2. [Localizing and Editing Knowledge in Text-to-Image Models](https://arxiv.org/abs/2310.13730)
   
   **ICLR 2024** [Project Poster](https://drive.google.com/file/d/1wyvOe1vhsE8eF_YeztvbMdlbbEXOoNmW/view?usp=sharing) [Code](https://github.com/adobe-research/DiffQuickFixRelease)
   > We propose an interpretability framework + model editing method to ablate concepts from text-to-image models, fast!
   
3. [Distilling Knowledge From Text-to-Image Models Improves Visio-Linguistic Reasoning in CLIP](https://arxiv.org/abs/2307.09233)

   **EMNLP 2024 (Main)** 
   > We propose a knowledge-distillation technique to improve reasoning abilities in CLIP!

4. [IntCoOp: Interpretability Aware Vision-Language Prompt Tuning](https://arxiv.org/abs/2406.13683)

   **EMNLP 2024 (Main)** [Code](https://github.com/Soumya1612-Rasha/IntCoOp)
   > We propose a new prompt tuning method for VLMs by using inductive biases from interpretable image level attributes!
     
5. [EditVal: Benchmarking Diffusion Based Text-Guided Image Editing Methods](https://arxiv.org/abs/2310.02426)
 
   **Under Review** [Code](https://github.com/deep-ml-research/editval_code), [Webpage](https://deep-ml-research.github.io/editval/)
  > We propose a new comprehensive benchmark for evaluating diffusion based editing methods!

6. [On Surgical Finetuning for Language Encoders](https://samyadeepbasu.github.io)

   **EMNLP 2023** [Code](https://github.com/ymtao5219/surgical_fine_tuning)
   > Method to surgically finetune language encoders with a subset of layers to perform close to full-finetuning!
   
7. [Strong Baselines for Parameter-Efficient Few-Shot Fine-Tuning](https://arxiv.org/abs/2304.01917) 

   **AAAI 2024** [Code](https://github.com/Samyadeep/)
  > We propose two easy-to-implement strong baselines for PEFT which leads to SoTA on MD!

8. [Hard Meta-Dataset++: Towards Understanding Few-shot Performance on Difficult Tasks](https://openreview.net/pdf?id=wq0luyH3m4) 

   **ICLR 2023** [Code](https://github.com/Samyadeep/HardMD) / [Media Coverage](https://www.microsoft.com/en-us/research/blog/frontiers-of-multimodal-learning-a-responsible-ai-approach/)
  > We propose a fast algorithm - FastDiffSel which can extract difficult few-shot tasks in a computational efficient way from large vision datasets!

9. [Strategies to Improve Few-Shot Learning for Intent Classification and Slot Filling](https://arxiv.org/abs/2109.08754) 

   **NAACL 2022 (SUKI)**
  > Propose empirical strategies to improve few-shot performance for joint intent classification and slot-filling.

10. [Influence Functions in Deep Learning are Fragile](https://arxiv.org/abs/2006.14651) 
    
   **ICLR 2021**
  > End to end analysis of influence functions in deep learning!


11. [On Second-Order Group Influence Functions for Black-Box Predictions](http://proceedings.mlr.press/v119/basu20b.html) 

     **ICML 2020**
  > We propose second-order group influence functions, which are better suited to handle group effects!


