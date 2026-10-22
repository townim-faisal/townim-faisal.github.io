---
layout: about
title: about
permalink: /

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false

selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: true
  limit: # show all news

latest_posts:
  enabled: false
---

<style>
  /* Title-case the "News" and "Selected Publications" headings added by the about layout. */
  .post article > h2 { text-transform: capitalize; }
  /* Smaller profile photo (theme default is 30%). */
  @media (min-width: 576px) { .profile { width: 24%; } }
  /* Start the research section below the photo. */
  .research-heading { clear: both; }
</style>

I am a Postdoctoral Research Associate at the [School of Earth and Oceans](https://www.uwa.edu.au/schools/earth-and-oceans), The University of Western Australia, working with [Prof. Mark Jessell](https://research-repository.uwa.edu.au/en/persons/mark-jessell) on multimodal foundation models with reliable uncertainty estimates. I am also a Postdoctoral Research Associate with the Cystic Fibrosis Airway Research Group in Adelaide, working with [A/Prof. Martin Donnelley](https://researchers.adelaide.edu.au/profile/martin.donnelley) on spatio-temporal biomarkers from X-ray velocimetry imaging.

I completed my PhD in Computer Science at the [Australian Institute for Machine Learning](https://www.adelaide.edu.au/aiml/about-us), [Adelaide University](https://adelaideuni.edu.au/), advised by [Dr. Zhibin Liao](https://researchers.adelaide.edu.au/profile/zhibin.liao), [Dr. Johan Verjans](https://researchers.adelaide.edu.au/profile/johan.verjans) and [Dr. Vu Minh Hieu Phan](https://scholar.google.com/citations?user=gSEw8EsAAAAJ). During my PhD, I was also a Research Scientist Intern at [Dolby Laboratories](https://www.dolby.com/), working on the interpretability of audio LLMs.

Before my PhD, I received my BSc in Computer Science & Engineering (summa cum laude) from [North South University](http://www.northsouth.edu/), where I was a research assistant working with [Dr. Shafin Rahman](https://scholar.google.com/citations?user=Pe8C-SUAAAAJ) on zero-shot and continual learning for 3D point clouds ([ECCV 2022](https://arxiv.org/abs/2205.15225), [IJCV 2022](https://arxiv.org/abs/2104.04980)) and with [Dr. Ahsanur Rahman](https://sites.google.com/site/rahmanmahsanur) on graph algorithms ([KDD 2024](https://dl.acm.org/doi/10.1145/3637528.3672066)). I also spent four years in industry as an ML and data engineer, building production ML pipelines.

#### Research
{: .research-heading}

My research asks one question: **when can a clinician trust a medical AI model?** A prediction is only as trustworthy as the chain that produced it: the data the model learned from, the representations it built, and the decision it made. A flaw at any link carries forward. Noisy labels corrupt what a model learns, and a model that relies on spurious features cannot be explained faithfully. My work therefore develops methods to **audit each link of this chain**:

1. **Trustworthy data: _what did the model learn from?_** I detect unreliable training samples from their training dynamics ([GradTrack, NeurIPS 2026](/publications/)) and test whether models recognise ambiguous inputs ([Visual Semantic Entropy, ECCV 2026](https://arxiv.org/abs/2606.31407)), so the data can be audited before a model is validated.
2. **Inspectable representations: _what did the model learn?_** I map a model's internal features to human-understandable concepts ([AdaCBM, MICCAI 2024](https://arxiv.org/abs/2408.02001); [AR&D, ICASSP 2026 Oral](https://arxiv.org/abs/2602.22253)), so the evidence it relies on can be checked against clinical knowledge.
3. **Faithful decisions: _why did the model decide?_** I build explanations that reflect what actually drove each prediction ([CAPE, CVPR 2024](https://arxiv.org/abs/2404.02388); [Mirror-CFE, ICCV 2025 Oral](https://arxiv.org/abs/2509.16822)), so clinicians can verify a decision rather than take it on faith.

Together, these give an end-to-end account of a model's behaviour, from its training data to each prediction. I develop them with clinicians, from respiratory imaging in cystic fibrosis to leukaemia cytology, and I am now bringing them to **cardiovascular imaging**.

I am always happy to discuss collaborations. Feel free to [email me](mailto:faisal.townim@gmail.com).
