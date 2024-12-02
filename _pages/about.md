---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Meng Wang joined Lingnan University, Hong Kong, as a tenure-track Assistant Professor since August 2024. She holds a Ph.D. degree from the City University of Hong Kong under the supervision of Prof. Shiqi Wang in 2021, a Master's degree in Computer Application Technology from Peking University under the supervision of Prof. Wen Gao, Prof. Siwei Ma and Prof. Xiaodong Xie in 2018, a B.Sc. in Electronic Engineering from China Agricultural University in 2015. She has been actively participating in the development of VVC, AVS3 and JPEG-AI standards and 27 technical proposals have been adopted. She has authored or co-authored over 40 refereed journal articles/conference papers. Her primary research interests include image and video coding and processing and generative coding.

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).


