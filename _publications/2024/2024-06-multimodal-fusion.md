---
title: "Data-Efficient Multimodal Fusion on a Single GPU"
collection: publications
permalink: /publication/2024-06-multimodal-fusion
excerpt: 
date: 2024-06-17
authors: 'Noël Vouitsis, Zhaoyan Liu, Satya Krishna Gorti, Valentin Villecroze, <b>Jesse C. Cresswell</b>, Guangwei Yu, Gabriel Loaiza-Ganem, Maksims Volkovs'
note: 'Highlight, Top 3% of submitted papers'
venueshort: 'CVPR 2024'
venue: 'Computer Vision and Pattern Recognition Conference 2024'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2024/html/Vouitsis_Data-Efficient_Multimodal_Fusion_on_a_Single_GPU_CVPR_2024_paper.html'
pdf: 'https://arxiv.org/pdf/2312.10144.pdf'
codeurl: 'https://github.com/layer6ai-labs/fusemix'
videourl:
slidesurl:
citation: 'Noël Vouitsis, Zhaoyan Liu, Satya Krishna Gorti, Valentin Villecroze, Jesse C. Cresswell, Guangwei Yu, Gabriel Loaiza-Ganem, and Maksims Volkovs. Data-Efficient Multimodal Fusion on a Single GPU. Computer Vision and Pattern Recognition Conference 2024'
---
The goal of multimodal alignment is to learn a single latent space that is shared between multimodal inputs. We surmise that existing unimodal encoders pre-trained on large amounts of unimodal data should provide an effective bootstrap to create multimodal models from unimodal ones at much lower costs. We therefore propose FuseMix, a multimodal augmentation scheme that operates on the latent spaces of arbitrary pre-trained unimodal encoders. Using FuseMix for multimodal alignment, we achieve competitive performance in both image-text and audio-text retrieval, with orders of magnitude less compute and data: for example, we outperform CLIP on the Flickr30K text-to-image retrieval task with ∼600× fewer GPU days and ∼80× fewer image-text pairs.