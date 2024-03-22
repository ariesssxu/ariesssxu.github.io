---
title: "On the Complexity of Bayesian Generalization"
collection: publications
permalink: '/publication/bayesian'
excerpt: '[Paper](https://yzhu.io/publication/intent2023neurips/paper.pdf) [Code](https://github.com/YuzheSHI/bayesian-generalization-complexity) [Video](https://vimeo.com/845790787) [Web](https://sites.google.com/view/bayesian-generalization)'
date: '2023.05' 
venue: '[ICML23] Proceedings of the International Conference on Machine Learning'
# paperurl: 'https://yzhu.io/publication/intent2023neurips/paper.pdf'
---

We examine concept generalization at a large scale in the natural visual spectrum. Established computational modes (i.e., rule-based or similarity-based) are primarily studied isolated, focusing on confined and abstract problem spaces. In this work, we study these two modes when the problem space scales up and when the complexity of concepts becomes diverse. At the representational level, we investigate how the complexity varies when a visual concept is mapped to the representation space. Prior literature has shown that two types of complexities build an inverted-U relation. Leveraging Representativeness of Attribute (RoA), we computationally confirm: Models use attributes with high RoA to describe visual concepts, and the description length falls in an inverted-U relation with the increment in visual complexity. At the computational level, we examine how the complexity of representation affects the shift between the rule- and similarity-based generalization. We hypothesize that category-conditioned visual modeling estimates the co-occurrence frequency between visual and categorical attributes, thus potentially serving as the prior for the natural visual world. Experimental results show that representations with relatively high subjective complexity outperform those with low subjective complexity in rule-based generalization, while the trend is the opposite in similarity-based generalization.