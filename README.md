## Overview
This document provides a descrption of the work developed for [GNSS-SDR](https://gnss-sdr.org/) during the Google Summer of Code 2020 program. This project intended to extend the capabilities of the GNSS-SDR software by providing implementation of [robust anti-jamming processing](https://github.com/HaoqingLi/gnss-sdr).

# Team
|Team member         | Position   | 
| ------------- |:-------------:| 
| Gerald Lamountain     | Mentor | 
| Pau Closas     | Mentor      |  
| Haoqing Li | Developer      |  

# Project
With Global Navigation Satellite System (GNSS) being popular in position-based applications with high accuracy, our growing dependence on GNSS within critical infrastructures has posed some concerns about the potential threats to GNSS. While GNSS can provide us precise positions estimation, the GNSS signal can be easily affected by some error sources, for example, jamming signal in this project. In this project, our main hypothesis is that jamming signals can be considered as outliers (either in time of frequency domain) to the received GNSS signal. To mitigate those outliers, robust version of cross-ambiguity functions (CAFs) are introduced with Maximum Likelihood (ML) estimator under heavy tailed distribution and M-estimator. Thus we can reduce the affect of jamming signals in terms of outliers and make GNSS more robust.

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/HaoqingLi/GSOC_2020/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
