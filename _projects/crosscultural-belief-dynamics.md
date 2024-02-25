---
title: "Cross-Cultural Belief Dynamics"
excerpt: "A case study of cross cultural belief dynamics through the interaction between K-pop fans and BLM movement"
layout: single
key: 1
skip_pagination: true
header:
  teaser: assets/images/attractors_orig.png
sidebar:
  - title: Focus Areas
    image: assets/images/attractors_orig.png
    image_alt: "picture"
    text: "Belief Dynamics, Cross cultural analysis"
  - title: "Status"
    text: "Active"
  - title: "People"
    text: "Yuheun Kim"
  
  
---
      
The internet has reduced barriers to cross-cultural communication, facilitating global activism aimed at addressing social, political, or environmental issues on a worldwide scale. Examples such as the Arab Spring, Occupy Wall Street, and the MeToo movement highlight the power of digital media in transcending national boundaries to mobilize support and solidarity globally. Despite the observable exchange of beliefs on a global scale, the underlying mechanisms driving such cross-cultural transfer remain unclear. To address this gap, we propose two research questions: (1) How does global activism spread across national boundaries in the era of digital media? (2) Does global activism lead to enduring shifts in beliefs among individuals across cultural or national boundaries?

In investigating the first research question, we propose two hypotheses that address both quantitative and qualitative aspects of our study. First, the "Top-Down Opinion Leadership" hypothesis posits that influential figures, so called opinion leaders <sup>1</sup>, play a pivotal role in binding global movements, with digital media amplifying their reach of communication. On the other hand, the ``Bottom-Up Value Alignment" hypothesis suggests that physically and culturally distinct groups cluster around common issues leading to grassroots movements on a global scale. In essence, digital media enhances in the visibility and relatability of an activism to the global audience. 

Social media, including platforms like Twitter, plays a crucial role online, facilitating transnational thought exchange. Therefore, our analysis on how information exchanges globally will be conducted through a specific case study that takes place in social media platforms. As a case study, we examine the interaction between K-pop fans and the Black Lives Matter (BLM) movement following the murder of George Floyd. The interaction between these distinctive groups is chosen as K-pop fans have several cases where they throw themselves into other activism movements, and BLM is an example of an activism  that involves the use of online media extensively. The intriguing movement of K-pop fans towards the BLM movement serves as a case study examining how culturally distinct groups corroborate for a specific cause. Less commonalities between the groups will aid us in dissecting the diverse factors influencing global communication.

To capture the belief dynamics between the two groups, we employ the Belief Landscape Framework introduced by Introne (2023)<sup>2</sup>. This framework encapsulates the belief dynamics, helping us examine where users in each group are situated and how their beliefs change over time. This aids in understanding how people move across different beliefs and how distinct groups move among belief belief clusters. We extend its utility in capturing exchange of beliefs on a global scale and shed light on the mechanisms driving cross-cultural communication by integrating bilingual text data. 

We collected data from Twitter using the Academic API, focusing on tweets posted between May and August 2020 with the hashtags \#Kpop and \#BLM. This timeframe was chosen in light of George Floyd's murder on May 25, 2020, to capture discussions during this significant period. We then implemented rigorous filtering criteria to select significant users for analysis. Following the data collection, we proceed on to building the belief landscape . The methodology is outlined in Introne (2023)<sup>2</sup> with slight modifications tailored to our dataset. We especially focused on representing our bilingual dataset into a single representation space for coherent analysis. Since Korean and English are syntactically distant languages, using a single dependency parser for both languages posed challenges. To address this, we translated Korean tweets leveraging a fine-tuned KoBART model, which has been extensively trained on Korean-English text pairs. 

-----------------

<sup>1</sup> Carpenter, C. R., & Sherbino, J. (2010). How does an “opinion leader” influence my practice?. Canadian Journal of Emergency Medicine, 12(5), 431-434.
<sup>2</sup> Introne, J. (2023, June). Measuring Belief Dynamics on Twitter. In Proceedings of the International AAAI Conference on Web and Social Media (Vol. 17, pp. 387-398).