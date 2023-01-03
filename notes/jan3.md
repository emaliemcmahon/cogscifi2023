---
layout: page
title: Jan 3
parent: Notes
description: Notes for the first day of class
---

# Decoding in fMRI

## Unimodal analyses

Using fMRI, a common question that a research might ask is whether a particular cognitive function occurs or is represented in a given brain region. 

For example, we might ask whether there is a region of the brain that represents faces.  

One way of answering this question is to show participants images in the scanner of faces and other categories like houses and scrambled houses. 

 Using this we can take the amount of activation in the brain to faces and subtract the activation to houses. This would tell us that a particular region responds more to faces than houses. This method reveals a region in the fusiform gyrus that has since been named the fusiform face area (FFA). 

|  ![Haxby2000_fig3](../../assets/images/Haxby2000_fig3.jpg) |
|:--:|
| Univariate fMRI contrasts to faces, houses, and camels. Figure from [Haxby et al (2000)](https://www.sciencedirect.com/science/article/pii/S1364661300014820#FIGGR4) |
 
 Does this region of the brain also represent the identity of different people? 
 
 It is possible that the brain could represent the identity of different people by responding a certain amount to me, a little more to your classmate, a bit more to your study friend, and so, but this seems unlikely and very inefficient. 
 
## Multivariate analyses
 
An alternative is that the identity of people in the FFA is represented as a pattern of response across many different neurons in a region. 

Imagine that we record fMRI responses while participants look at images of two different people (Red and Blue) in a variety of different contexts. In some images Red is facing to the left, some to the right, and in others he has a mask on, and the same for blue. 

In the below schematized data, the overall activation to Red and Blue is very similar, but the pattern of responses across the unique images of Red and Blue and different. 

In this case, unimodal analyses described above would find no difference between Red and Blue, but we can use multivariate analyses such as linear classification to determine whether a participant was viewing Red or Blue based on this pattern. 
  
|  ![Face discrimination](../../assets/images/faces.jpg) |
|:--:|
| fMRI response to two different individuals (Red and Blue) in a variety of views and contexts.|
  
## Take aways

The details of how the analyses are performed is beyond the scope of this class, but multivariate analyses are a popular method to investigate whether something is represented in the brain. 

In [Song et al (2008)](https://www.nature.com/articles/nn.2112), they use multivariate decoding to discriminate left from right key presses to determine how early different regions represent the decision relative to when participants report being consciously aware. 
