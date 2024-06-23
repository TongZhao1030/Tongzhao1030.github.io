---
title: "Linearity in Deng entropy"
collection: publications
permalink: /publication/Linearity_in_Deng_entropy
excerpt: 'This paper conducts an in-depth exploration of the linear relationship between Deng entropy and the scale of the frame of discernment (SFOD), and find that the slope is nothing else but the information fractal dimension of mass function. It shows that entropy can not only increase, but also increase in a linear way, leading to the convenience of approximate calculation.'
date: 2024-01-01
venue: 'Chaos, Solitons & Fractals'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0960077923012900'
citation: 'Tong Zhao, Zhen Li, and Yong Deng.&quot;Linearity in Deng entropy.&quot; <i>Chaos, Solitons & Fractals</i> 178 (2024): 114388.'
---

Highlights
=====
- The linearity in Deng entropy is systematically reviewed and discussed.
- The slope of Deng entropy is the information fractal dimension of mass function.
- A set of mass functions which can result linearity in Deng entropy are presented.
- For any given slope from 0 to ln 3/ln 2, at least one mass function can be derived.
- Some proofs, numerical examples and discussions are presented.

Deng entropy - a generalization of Shannon entropy
=====
To understand [Deng entropy](https://www.sciencedirect.com/science/article/abs/pii/S0960077916302363), it is necessary to first understand evidence theory. Evidence theory, also known as Dempster-Shafer evidence theory, is a generalization of probability theory. In contrast to probability theory, which assigns probabilities to singleton subsets of the sample space, evidence theory assigns probabilities to subsets containing multiple elements, namely the power set of the sample space.

Consider the following example: Suppose you have two boxes, A and B, with box A filled with red balls and box B filled with green balls. Now, let's say the probability of picking a ball from box A is 0.4, and from box B is 0.6. We can easily calculate the probabilities of picking red or green balls. However, if we slightly alter the conditions so that box A still contains only red balls, but box B contains both green and red balls, and we are uncertain about the exact number of each color, can we still use probabilities to represent the situation? This is where evidence theory comes into play.

![DS](https://github.com/TongZhao1030/Tongzhao1030.github.io/assets/164134563/7f62a908-0f05-43b0-8658-75121a8d0a4f "D-S Evidence Theory")

The linearity in Deng entropy
=====
We know that Shannon entropy can measure the uncertainty of a probability distribution, while Deng entropy serves as a generalization of Shannon entropy for handling mass functions in evidence theory. Due to the presence of "log" in the expression of entropy, the entropy graph typically exhibits logarithmic properties. However, in [previous research on information dimension](https://www.worldscientific.com/doi/abs/10.1142/S0218348X22501109), we observed that Deng entropy can exhibit linear property and discovered certain mass functions that can cause Deng entropy to exhibit linearity, which has greatly arisen our interest.

The presence of linearity in Deng entropy has raised two significant questions:
- Are there other mass functions that could result in a linear relationship between Deng entropy and the scale of the frame of discernment (SFOD)? 
- Given a specific slope, can we find mass functions that yield Deng entropy with that slope?
These two questions have prompted us to delve into and discuss the linearity in Deng entropy in greater depth.

![Deng](https://github.com/TongZhao1030/Tongzhao1030.github.io/assets/164134563/e4d76266-302f-4175-8e99-d74c53c38c74 "The linearity in Deng entropy")

A specific mass function corresponds to a specific entropy, but a particular entropy can correspond to multiple mass functions. Therefore, it is challenging to deduce mass functions from a particular entropy. However, thanks to the linearity, we demonstrate that it is possible to derive at least one mass function from a linear Deng entropy. Moreover, due to the simplicity of linearity, we can also utilize it to simplify our calculations of entropy. Last but not least, we find the slope is nothing else but the information fractal dimension of mass function.

For more details, please refer to the [paper](../files/Selected_Pub_Entropy.pdf).

