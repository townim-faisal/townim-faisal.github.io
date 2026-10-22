---
layout: about
title: about
permalink: /
subtitle: <b>Research interests:</b> Trustworthy AI · Multimodal Learning · Medical Image Analysis

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

👋 Hi, I am a Postdoctoral Research Associate at [The University of Western Australia](https://www.uwa.edu.au/), working with [Prof. Mark Jessell](https://research-repository.uwa.edu.au/en/persons/mark-jessell), and with the Cystic Fibrosis Airway Research Group in Adelaide, working with [A/Prof. Martin Donnelley](https://researchers.adelaide.edu.au/profile/martin.donnelley). My research focuses on trustworthy and interpretable AI for general and medical applications.

I received my PhD in Computer Science from the [Australian Institute for Machine Learning](https://www.adelaide.edu.au/aiml/about-us), [Adelaide University](https://adelaideuni.edu.au/), advised by [Dr. Zhibin Liao](https://researchers.adelaide.edu.au/profile/zhibin.liao), [Dr. Johan Verjans](https://researchers.adelaide.edu.au/profile/johan.verjans) and [Dr. Vu Minh Hieu Phan](https://scholar.google.com/citations?user=gSEw8EsAAAAJ), and spent part of it as a Research Scientist Intern at [Dolby Laboratories](https://www.dolby.com/). Before that, I completed my BSc (summa cum laude) at [North South University](http://www.northsouth.edu/), where I was a research assistant with [Dr. Shafin Rahman](https://scholar.google.com/citations?user=Pe8C-SUAAAAJ) on 3D point cloud learning ([ECCV 2022](https://arxiv.org/abs/2205.15225), [IJCV 2022](https://arxiv.org/abs/2104.04980)) and with [Dr. Ahsanur Rahman](https://sites.google.com/site/rahmanmahsanur) on graph algorithms ([KDD 2024](https://dl.acm.org/doi/10.1145/3637528.3672066)), and I spent four years in industry as an ML and data engineer.

## Research Focus: Trustworthy and Interpretable AI
{: .research-heading}

**Research vision.** I aim to build AI systems that can be trusted when the stakes are high, as in healthcare. Trusting a model means being able to answer three questions: can its data and predictions be relied on, what has it learned, and why did it make a particular decision? My work develops methods to answer each of these, for both conventional deep networks and multimodal foundation models.

1. **Reliability:** _when should a model's data or predictions be doubted?_<br>
   Methods that detect mislabelled training data and measure uncertainty on ambiguous inputs, so unreliable samples and predictions can be flagged before they cause harm.<br>
   _Selected work:_ [GradTrack](/publications/) (NeurIPS 2026), [Visual Semantic Entropy](https://arxiv.org/abs/2606.31407) (ECCV 2026)
2. **Inspectable Representations:** _what has the model learned?_<br>
   Methods that map a model's internal features to human-understandable concepts, so the knowledge it relies on can be checked against domain expertise.<br>
   _Selected work:_ [AdaCBM](https://arxiv.org/abs/2408.02001) (MICCAI 2024), [AR&D](https://arxiv.org/abs/2602.22253) (ICASSP 2026, Oral)
3. **Faithful Decisions:** _why did the model make this prediction?_<br>
   Explanation methods for individual predictions that reflect the model's actual decision process rather than a plausible approximation, so users such as clinicians can verify them.<br>
   _Selected work:_ [CAPE](https://arxiv.org/abs/2404.02388) (CVPR 2024), [Mirror-CFE](https://arxiv.org/abs/2509.16822) (ICCV 2025, Oral)

I am always happy to discuss collaborations. Feel free to [email me](mailto:faisal.townim@gmail.com).
