# MKDRD

This repository contains the ground truth dataset from our research paper "MKDRD: A multi-modal Korean review dataset and deep learning model for deceptive review detection".

## Dataset Overview

MKDRD is the first large-scale multi-modal Korean dataset specifically designed for detecting deceptive reviews.
This ground truth dataset contains 963 human-annotated Korean restaurant reviews from Naver Blog, carefully labeled and processed through rigorous annotation procedures.
You can receive text, images and metadata about our dataset.
Due to privacy concerns, original text and images are not provided. 
Instead, we provide embedding files through a Google Drive URL.

## Architecture
<img src="https://github.com/user-attachments/assets/44078340-910a-4da5-9db2-51f88f89549e" alt="figure-model2" style="width: 70%; max-width: 800px;" />


## Abstract

Online review platforms face increasing challenges in distinguishing authentic user opinions from deceptive content intended to influence consumer decisions. Existing detection systems have achieved progress in English text analysis, but remain inadequate for multi-modal content and non-English texts. This study introduces MKDRD (Multi-modal Korean Deceptive Review Detection Dataset), the first large-scale Korean dataset specifically designed for detecting deceptive reviews in multi-modal contexts. The dataset comprises 11,799 restaurant reviews from Naver Blog, which include text, images, and metadata. Each entry is annotated with a sponsored or unsponsored scheme that captures commercial influence beyond traditional binary labels. To prevent annotation bias, we applied content masking methods that remove sponsorship indicators while maintaining semantic meaning. We developed MKD-Net (Multi-modal Korean Deceptive Review Detection Network), combining TF-IDF and VGG-16, with comprehensive experiments using state-of-the-art detection models, including BERT, ResNet50, and multi-modal fusion architectures. Our results demonstrate that multi-modal approaches significantly outperform text-only methods, achieving up to 94.18\% accuracy compared to 92.21\% for text-only models, highlighting the critical importance of visual information in deceptive review detection. The dataset and experimental findings reveal unique characteristics of Korean deceptive reviews, including linguistic patterns, image usage strategies, and platform-specific behaviors that differ from English-language contexts. MKDRD provides researchers with essential resources for developing culturally-aware multi-modal detection systems and advancing the understanding of deceptive content in non-English digital ecosystems.

