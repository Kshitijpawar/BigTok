# BigTok: Expert-Curated Multimodal Dataset for Characterizing Harmful Pro-Bigorexia Content on TikTok

### Abstract: 
Video sharing platforms like TikTok significantly influence body image, particularly among adolescents and young adults. While much attention has been paid to the ``thin ideal,'' emerging evidence highlights bigorexia, i.e., a muscularity-oriented eating disorder disproportionately affecting boys and men, as a growing concern. Characterized by compulsive behaviors to increase muscle mass and reduce body fat, bigorexia remains under-recognized and under-moderated. In this paper, we develop a clinically informed, fine-grained taxonomy of pro-bigorexia content spanning body image, diet, exercise, supplements, and masculinity. We introduce BigTok, the first expert-annotated dataset of over 2,400 TikTok videos curated by clinical psychologists and psychiatrists, and BigTok-Detect, a multimodal harm detection framework leveraging state-of-the-art vision–language models. We benchmark proprietary and open-source models, conduct ablation studies across modalities, and demonstrate the importance of clinical expertise and multimodal fusion for accurate, scalable detection of bigorexia-related harms.

### Folders
- `few-shot`: Sample train and test dataset used for few-shot inference.
- `zero-shot`: Sample train and test dataset used for zero-shot inference and supervised-finetuning.
- `all_sample.csv`: Sample dataset in CSV format.