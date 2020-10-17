---
layout: archive
title: "Work Responsibilities"
permalink: /work/
author_profile: true
---

My name is Jannik Gut and I am a Computer Science Master Student specialising in Machine Learning and Natural Language Processing at ETH Zürich in Switzerland.

On this website you can find out more about:
- [my work experience](https://rostro36.github.io/work/)
- [my academic career and the projects I did in this time](https://rostro36.github.io/homeworks/)
- [the projects I do in my free time](https://rostro36.github.io/projects/)

## CV
Or if you want all this information in a single page or a [PDF](https://rostro36.github.io/files/Jannik_Gut_CV.pdf), you can download it [here](https://rostro36.github.io/cv/).

## Hobbies
Other than working on computer science projects I enjoy hiking up mountains and climbing some smaller hills with my bicycle in the summer.

When that is not possible due to the season I go skiing or as a last resort go jogging to stay healthy.

This physical activity is badly needed since I stress my digestive system often with cakes or other desserts that I made myself and I also stress my heart too much by supporting Chelsea F.C.  in England and the local teams F.C. Luzern and EV Zug in Switzerland too much. (Thankfully, the local bicycle rider stopped riding for GCs.)

When I read about them in the local newspaper I usually also read the rest about national and international politics and the economy.
## Contact
The easiest way to contact me is via one of the methods listed on the left. They are links to my social sites or my e-mail address.
'''
{\% include base_path \%}

{\% for post in site.work reversed \%}
  {\% include archive-single.html \%}
{\% endfor \%}
'''