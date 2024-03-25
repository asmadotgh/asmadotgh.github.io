---
layout: page
title: DISSECT 
description: Disentangled Simultaneous Explanationsvia Concept Traversals
img: # assets/img/12.jpg
importance: 1
category: [Interpretability, Machine Learning, Computer Vision, Deep Learning]
related_publications: false
---


One of the principal benefits of counterfactual explanations is allowing users to explore "what-if" scenarios through what does not and cannot exist in the data, a quality that many other mediums of explanation such as heatmaps and influence functions are inherently incapable of doing. However, most previous work on generative explainability cannot disentangle important concepts effectively, produces poor quality or unrealistic examples, or fails to retain relevant information. We propose a novel approach, DISSECT, that trains a generator, a discriminator, and a concept disentangler simultaneously to overcome such challenges using little supervision. DISSECT offers a way to automatically discover a classifier's inherent notion of distinct concepts rather than rely on user-predefined concepts. We validate our approach on several challenging synthetic and realistic datasets where previous methods fall short of satisfying desirable criteria for interpretability and show that our method performs consistently well across all. We demonstrate applications of DISSECT for detecting potential biases of a classifier, investigating its alignment with expert domain knowledge, and identifying spurious artifacts that impact predictions using simulated experiments. 


<p><b>Publications:</b> <a href="https://arxiv.org/abs/2105.15164" target="_blank">ICLR 2022</a></p>

 <a href="https://github.com/asmadotgh/dissect" target="_blank">Code</a>
 
 <a href="https://mitmedialabaffectivecomputing.github.io/SynthDermDataset/" target="_blank">SynthDerm dataset</a></p>