# 🎯 Survey: Content-Generation-for-IR-System

 This is the collection of papers related to bias and fairness in IR with LLMs. These papers are organized according to our survey paper **Content Generation for Information Retrieval Systems: A Survey from the Supply-Side Optimization Perspective** [[PDF]]().

---

## 📚 Paper List

### 🧩 Generic Content Generation
#### 📢 Advertising Content Generation
1. **Neural Retrievers are Biased Towards LLM-Generated Content**, KDD 2024. [[Paper]](https://arxiv.org/abs/2310.20501) ![](https://img.shields.io/badge/Source_Bias-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
2. **Invisible Relevance Bias: Text-Image Retrieval Models Prefer AI-Generated Images**, SIGIR 2024. [[Paper]](https://arxiv.org/abs/2311.14084) ![](https://img.shields.io/badge/Source_Bias-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
3. **Blinded by Generated Contexts: How Language Models Merge Generated and Retrieved Contexts for Open-Domain QA?**, ACL 2024. [[Paper]](https://arxiv.org/abs/2401.11911) ![](https://img.shields.io/badge/Source_Bias-orange)
4. **Perplexity-Trap: PLM-Based Retrievers Overrate Low Perplexity Documents**, ICLR 2025. [[Paper]](https://arxiv.org/abs/2503.08684) ![](https://img.shields.io/badge/Source_Bias-orange)

1. **Learning to Create Better Ads: Generation and Ranking Approaches for Ad Creative Refinement**, CIKM 2020. [[Paper]](https://dl.acm.org/doi/10.1145/3340531.3412720) ![](https://img.shields.io/badge/Advertising_Text_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
2. **An Empirical Study of Generating Texts for Search Engine Advertising**, NAACL 2021. [[Paper]](https://aclanthology.org/2021.naacl-industry.32/) ![](https://img.shields.io/badge/Advertising_Text_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
3. **PLATO-Ad: A Unified Advertisement Text Generation Framework with Multi-Task Prompt Learning**, EMNLP Industry 2022. [[Paper]](https://aclanthology.org/2022.emnlp-industry.52/) ![](https://img.shields.io/badge/Advertising_Text_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
4. **CREATER: CTR-driven Advertising Text Generation with Controlled Pre-Training and Contrastive Fine-Tuning**, NAACL 2022. [[Paper]](https://aclanthology.org/2022.naacl-industry.2/) ![](https://img.shields.io/badge/Advertising_Text_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
5. **GCOF: Self-iterative Text Generation for Copywriting Using Large Language Model**, arXiv 2024. [[Paper]](https://arxiv.org/abs/2402.13667) ![](https://img.shields.io/badge/Advertising_Text_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
6. **Generating Attractive and Authentic Copywriting from Customer Reviews**, NAACL 2024. [[Paper]](https://aclanthology.org/2024.naacl-long.259/) ![](https://img.shields.io/badge/Advertising_Text_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
7. **Generating Attractive Ad Text by Facilitating the Reuse of Landing Page Expressions**, INLG 2024. [[Paper]](https://aclanthology.org/2024.inlg-main.46/) ![](https://img.shields.io/badge/Advertising_Text_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
8. **CTR-Driven Ad Text Generation via Online Feedback Preference Optimization**, arXiv 2025. [[Paper]](https://arxiv.org/abs/2507.20227) ![](https://img.shields.io/badge/Advertising_Text_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
9. **LLM-driven Constrained Copy Generation through Iterative Refinement**, arXiv 2025. [[Paper]](https://arxiv.org/abs/2504.10391) ![](https://img.shields.io/badge/Advertising_Text_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)

#### 🖼️ Advertising Image Generation
1. **Persuasive Faces: Generating Faces in Advertisements**, arXiv 2018. [[Paper]](https://arxiv.org/abs/1807.09882) ![](https://img.shields.io/badge/Advertising_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
2. **AutoPoster: A Highly Automatic and Content-aware Design System for Advertising Poster Generation**, MM 2023. [[Paper]](https://dl.acm.org/doi/10.1145/3581783.3611930) ![](https://img.shields.io/badge/Advertising_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
3. **TextPainter: Multimodal Text Image Generation with Visual-harmony and Text-comprehension for Poster Design**, MM 2023. [[Paper]](https://dl.acm.org/doi/10.1145/3581783.3611929) ![](https://img.shields.io/badge/Advertising_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
4. **Relation-Aware Diffusion Model for Controllable Poster Layout Generation**, CIKM 2023. [[Paper]](https://dl.acm.org/doi/10.1145/3583780.3615028) ![](https://img.shields.io/badge/Advertising_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
5. **Product2IMG: Prompt-Free E-commerce Product Background Generation with Diffusion Model and Self-Improved LMM**, MM 2024. [[Paper]](https://dl.acm.org/doi/10.1145/3664647.3680753) ![](https://img.shields.io/badge/Advertising_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
6. **Prompt2Poster: Automatically Artistic Chinese Poster Creation from Prompt Only**, MM 2024. [[Paper]](https://dl.acm.org/doi/10.1145/3664647.3681495) ![](https://img.shields.io/badge/Advertising_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
7. **Chaining Text-to-Image and Large Language Model: A Novel Approach for Generating Personalized e-commerce Banners**, KDD 2024. [[Paper]](https://dl.acm.org/doi/10.1145/3637528.3671636) ![](https://img.shields.io/badge/Advertising_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
8. **Towards Reliable Advertising Image Generation Using Human Feedback**, ECCV 2024. [[Paper]](https://dl.acm.org/doi/10.1007/978-3-031-72661-3_23) ![](https://img.shields.io/badge/Advertising_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
9. **A New Creative Generation Pipeline for Click-Through Rate with Stable Diffusion Model**, WWW 2024. [[Paper]](https://dl.acm.org/doi/10.1145/3589335.3648315) ![](https://img.shields.io/badge/Advertising_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
10. **Mirror in the Model: Ad Banner Image Generation via Reflective Multi-LLM and Multi-modal Agents**, EMNLP 2025. [[Paper]](https://aclanthology.org/2025.emnlp-industry.17/) ![](https://img.shields.io/badge/Advertising_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
11. **BannerAgency: Advertising Banner Design with Multimodal LLM Agents**, EMNLP  2025. [[Paper]](https://aclanthology.org/2025.emnlp-main.214/) ![](https://img.shields.io/badge/Advertising_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
12. **The Face of Persuasion: Analyzing Bias and Generating Culture-Aware Ads**, EMNLP Findings 2025. [[Paper]]() ![](https://img.shields.io/badge/Advertising_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
13. **AutoPP: Towards Automated Product Poster Generation and Optimization**, arXiv 2025. [[Paper]](https://aclanthology.org/2025.findings-emnlp.344/) ![](https://img.shields.io/badge/Advertising_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
14. **PosterMaker: Towards High-Quality Product Poster Generation with Accurate Text Rendering**, CVPR 2025. [[Paper]](https://ieeexplore.ieee.org/document/11094331/) ![](https://img.shields.io/badge/Advertising_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
15. **T-Stars-Poster: A Framework for Product-Centric Advertising Image Design**, CIKM 2025. [[Paper]](https://dl.acm.org/doi/10.1145/3746252.3761554) ![](https://img.shields.io/badge/Advertising_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
16. **CTR-Driven Advertising Image Generation with Multimodal Large Language Models**, WWW 2025. [[Paper]](https://dl.acm.org/doi/10.1145/3696410.3714836) ![](https://img.shields.io/badge/Advertising_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)

#### 🎬 Advertising Video Generation
1. **VC-LLM: Automated Advertisement Video Creation from Raw Footage using Multi-modal LLMs**, arXiv 2025. [[Paper]](https://arxiv.org/pdf/2504.05673) ![](https://img.shields.io/badge/Advertising_Video_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)

#### 📝 Item Description Completion
1. **LLM Based Generation of Item-Description for Recommendation System**, RecSys 2023. [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3604915.3610647) ![](https://img.shields.io/badge/Item_Description_Completion-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
2. **Using Large Language Models to Improve Product Information in E-commerce Catalogs**, CIKM 2025. [[Paper]](https://dl.acm.org/doi/10.1145/3746252.3761437) ![](https://img.shields.io/badge/Item_Description_Completion-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)

#### 🔍 Generative Engine Optimization (GEO)
1. **GEO: Generative Engine Optimization**, KDD 2024. [[Paper]](https://dl.acm.org/doi/10.1145/3637528.3671900) ![](https://img.shields.io/badge/Generative_Engine_Optimization-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
2. **What Generative Search Engines Like and How to Optimize Web Content Cooperatively**, ICLR 2026. [[Paper]](https://openreview.net/forum?id=K8EinVWtUB) ![](https://img.shields.io/badge/Generative_Engine_Optimization-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
3. **AgenticGEO: A Self-Evolving Agentic System for Generative Engine Optimization**, arXiv 2026. [[Paper]](https://arxiv.org/html/2603.20213v1) ![](https://img.shields.io/badge/Generative_Engine_Optimization-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)

### 👤 Personalized Content Generation
#### 🖼️ Personalized Image Generation
1. **PMG: Personalized Multimodal Generation with Large Language Models**, WWW 2024. [[Paper]](https://dl.acm.org/doi/10.1145/3589334.3645633) ![](https://img.shields.io/badge/Personalized_Generic_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
2. **I-AM-G: Interest Augmented Multimodal Generator for Item Personalization**, EMNLP 2024. [[Paper]](https://aclanthology.org/2024.emnlp-main.1187/) ![](https://img.shields.io/badge/Personalized_Generic_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
3. **Personalized Image Generation for Recommendations Beyond Catalogs**, RecSys 2025. [[Paper]](https://dl.acm.org/doi/10.1145/3705328.3748757) ![](https://img.shields.io/badge/Personalized_Generic_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
4. **Personalized Image Generation with Large Multimodal Models**, WWW 2025. [[Paper]](https://dl.acm.org/doi/10.1145/3696410.3714843) ![](https://img.shields.io/badge/Personalized_Generic_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
5. **RAGAR: Retrieval Augmented Personalized Image Generation Guided by Recommendation**, arXiv 2025. [[Paper]](https://arxiv.org/abs/2505.01657) ![](https://img.shields.io/badge/Personalized_Generic_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
6. **DRC: Enhancing Personalized Image Generation via Disentangled Representation Composition**, MM 2025. [[Paper]](https://dl.acm.org/doi/10.1145/3746027.3755051) ![](https://img.shields.io/badge/Personalized_Generic_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
7. **Personalized Visual Content Generation in Conversational Systems**, NeurIPS 2025. [[Paper]](https://openreview.net/forum?id=6MUgQXkxIC) ![](https://img.shields.io/badge/Personalized_Generic_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)

1. **Visually-Aware Fashion Recommendation and Design with Generative Image Models**, ICDM 2017. [[Paper]](https://ieeexplore.ieee.org/document/8215493/) ![](https://img.shields.io/badge/Personalized_Outfit_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
2. **From Recommendation to Generation: A Novel Fashion Clothing Advising Framework**, ICDH 2018. [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8634794) ![](https://img.shields.io/badge/Personalized_Outfit_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
3. **Compatibility family learning for item recommendation and generation**, AAAI 2018. [[Paper]](https://dl.acm.org/doi/10.5555/3504035.3504328) ![](https://img.shields.io/badge/Personalized_Outfit_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
4. **c^+GAN: Complementary Fashion Item Recommendation**, arXiv 2019. [[Paper]](https://arxiv.org/abs/1906.05596) ![](https://img.shields.io/badge/Personalized_Outfit_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
5. **M6-Rec: Generative Pretrained Language Models are Open-Ended Recommender Systems**, arXiv 2022. [[Paper]](https://arxiv.org/abs/2205.08084) ![](https://img.shields.io/badge/Personalized_Outfit_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
6. **Diffusion Models for Generative Outfit Recommendation**, SIGIR 2024. [[Paper]](https://dl.acm.org/doi/10.1145/3626772.3657719) ![](https://img.shields.io/badge/Personalized_Outfit_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
7. **Sell It Before You Make It: Revolutionizing E-Commerce with Personalized AI-Generated Items**, arXiv 2025. [[Paper]](https://arxiv.org/abs/2503.22182) ![](https://img.shields.io/badge/Personalized_Outfit_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
8. **FashionDPO: Fine-tune Fashion Outfit Generation Model using Direct Preference Optimization**, SIGIR 2025. [[Paper]](https://dl.acm.org/doi/10.1145/3726302.3729976) ![](https://img.shields.io/badge/Personalized_Outfit_Image_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)

#### ✍️ Personalized Text Generation
1. **Put Your Voice on Stage: Personalized Headline Generation for News Articles**, TKDD 2023. [[Paper]](https://dl.acm.org/doi/full/10.1145/3629168) ![](https://img.shields.io/badge/Personalized_Text_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
2. **HLLM-Creator: Hierarchical LLM-based Personalized Creative Generation**, arXiv 2025. [[Paper]](https://arxiv.org/abs/2508.18118) ![](https://img.shields.io/badge/Personalized_Text_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)

#### 🎥  Personalized Video Generation
1. **NextAds: Towards Next-generation Personalized Video Advertising**, arXiv 2026. [[Paper]](https://arxiv.org/abs/2603.02137) ![](https://img.shields.io/badge/Personalized_Video_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)

#### 🔎 Search Advertisement Generation
1. **Generating Better Search Engine Text Advertisements with Deep Reinforcement Learning**, KDD 2019. [[Paper]](https://dl.acm.org/doi/10.1145/3292500.3330754) ![](https://img.shields.io/badge/Search_Advertisement_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
2. **Reinforcing Pretrained Models for Generating Attractive Text Advertisements**, KDD 2021. [[Paper]](https://dl.acm.org/doi/10.1145/3447548.3467105) ![](https://img.shields.io/badge/Search_Advertisement_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)
3. **DeepGen: Diverse Search Ad Generation and Real-Time Customization**, EMNLP 2022. [[Paper]](https://aclanthology.org/2022.emnlp-demos.19/) ![](https://img.shields.io/badge/Search_Advertisement_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)

#### 🛍️  On-Demand Product Generation
1. **Sell It Before You Make It: Revolutionizing E-Commerce with Personalized AI-Generated Items**, arXiv 2025. [[Paper]](https://arxiv.org/abs/2503.22182) ![](https://img.shields.io/badge/On-Demand_Product_Generation-orange) ![](https://img.shields.io/badge/Regularization-darkcyan)

---

## 🤝 Contribution
:tada::+1: Please feel free to open an issue or make a pull request! :tada::+1:
