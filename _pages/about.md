---
layout: about
title: about
permalink: /
subtitle: Postdoctoral Research Associate · <a href="https://www.uwa.edu.au/">The University of Western Australia</a> · Trustworthy AI for medical imaging

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>School of Earth and Oceans</p>
    <p>The University of Western Australia</p>
    <p>Perth, Australia</p>

selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: true
  limit: # show all news

latest_posts:
  enabled: false
---

I am a Postdoctoral Research Associate at the [School of Earth and Oceans](https://www.uwa.edu.au/schools/earth-and-oceans), The University of Western Australia, working with Prof. Mark Jessell on multimodal foundation models with reliable uncertainty estimates. I am also a Postdoctoral Research Associate with the Cystic Fibrosis Airway Research Group in Adelaide, working with A/Prof. Martin Donnelley on spatio-temporal biomarkers from X-ray velocimetry imaging.

I completed my PhD in Computer Science at the [Australian Institute for Machine Learning](https://www.adelaide.edu.au/aiml/about-us), [Adelaide University](https://adelaideuni.edu.au/), advised by [Dr. Zhibin Liao](https://researchers.adelaide.edu.au/profile/zhibin.liao), [Dr. Johan Verjans](https://researchers.adelaide.edu.au/profile/johan.verjans) and [Dr. Vu Minh Hieu Phan](https://scholar.google.com/citations?user=gSEw8EsAAAAJ). Before that, I was a Research Scientist Intern at [Dolby Laboratories](https://www.dolby.com/), spent four years as an ML and data engineer in industry, and received my BSc (summa cum laude) from [North South University](http://www.northsouth.edu/).

#### Research

My research asks one question: **when can a clinician trust a medical AI model?** A prediction is only as trustworthy as the chain that produced it: the data the model learned from, the representations it built, and the decision it made. A flaw at any link carries forward. Noisy labels corrupt what a model learns, and a model that relies on spurious features cannot be explained faithfully. My work therefore develops methods to **audit each link of this chain**:

1. **Trustworthy data: _what did the model learn from?_** I detect unreliable training samples from their training dynamics ([GradTrack, NeurIPS 2026](/publications/)) and test whether models recognise ambiguous inputs ([Visual Semantic Entropy, ECCV 2026](https://arxiv.org/abs/2606.31407)), so the data can be audited before a model is validated.
2. **Inspectable representations: _what did the model learn?_** I map a model's internal features to human-understandable concepts ([AdaCBM, MICCAI 2024](https://arxiv.org/abs/2408.02001); [AR&D, ICASSP 2026 Oral](https://arxiv.org/abs/2602.22253)), so the evidence it relies on can be checked against clinical knowledge.
3. **Faithful decisions: _why did the model decide?_** I build explanations that reflect what actually drove each prediction ([CAPE, CVPR 2024](https://arxiv.org/abs/2404.02388); [Mirror-CFE, ICCV 2025 Oral](https://arxiv.org/abs/2509.16822)), so clinicians can verify a decision rather than take it on faith.

Together, these give an end-to-end account of a model's behaviour, from its training data to each prediction. I develop them with clinicians, from respiratory imaging in cystic fibrosis to leukaemia cytology, and I am now bringing them to **cardiovascular imaging**.

I am always happy to discuss collaborations. Feel free to [email me](mailto:faisal.townim@gmail.com).
