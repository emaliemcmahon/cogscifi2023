---
layout: page
title: Jan 4
parent: Notes
description: Notes on Soon et al (2008) and Smith (2011)
---

# Free Will: [Soon et al (2008)](https://www.nature.com/articles/nn.2112) & [Smith (2001)](https://www.nature.com/articles/477023a)


## fMRI Primer

Functional magnetic resonance imaging (fMRI) works by measuring the blood-oxygen-level-dependent (BOLD) signal. When a region is more active, there is more oxygenated blood flow (also known as the hemodynamic response) to that area of the brain. This change in oxygenated blood flow is detectable by the MRI machine. 

| ![fMRI](../../assets/images/resting-and-activated.jpg) |
|:--:|
| When a region is more active, there is more oxygenated blood flow to that area of the brain. Figure from [Introduction to fMRI](https://www.ndcn.ox.ac.uk/divisions/fmrib/what-is-fmri/introduction-to-fmri) |

Unlike other methods to record brain activity, the time course of the hemodynamic response is slow, on the order of 10-15 seconds.  

|  ![hemodynamic response](../../assets/images/hemodynamic_response.png) |
|:--:|
| Figure from [BOLD and Brain Activity](https://mriquestions.com/does-boldbrain-activity.html) |

In a typical fMRI experiment, one image of the brain is acquired every 2 seconds. The time to acquire one image is the repitition time (TR). 

## Soon et al (2008)

### fMRI Task

In Soon et al (2008), for each trial, they showed participants a string of randoms letters. Participants decided at will to make a response with either the left or right button. 

At the end of the trial, participants were asked to report the letter that was on the screen when they decided to make a choice. 

*Question for the class*: Why could the authors not use the time that the participants hit the button as the time that participants had made the choice? 

|  ![Soon2008_fig1](../../assets/images/Soon2008_fig1.jpg) |
|:--:|
| fMRI tasks that participants performed. Participants were shown a sequence of letters and were asked to first decide at will to respond with either the left or right key. At the end of the trial, participants reported which letter was on the screen when they made their decision. Figure from [Soon et al (2008)](https://www.nature.com/articles/nn.2112) |

### fMRI Analysis

Soon et al (2008) used searchlight (a movable sphere of voxels in the brain that determines where the analysis is taking place) classification analysis. 

The used a classification algorithm to decode whether participants had responded with the left or right key on every TR proceeding their decision.

|  ![Soon2008_sfig4](../../assets/images/Soon2008_sfig4.png) |
|:--:|
| Searchlight classification method from [Soon et al (2008)](https://www.nature.com/articles/nn.2112) |

### Results

Soon et al (2008) found that although there was no difference in mean activation for left and right key presses in ROIs other than SMA and motor cortex, they were able to decode the decision as much as 7 seconds before the decision was made in frontopolar cortex, precuneus, and posterior cingulate cortex. 

*Question for the class*: Why would there be a mean signal difference between left and right key press in the left and right motor cortices?

|  ![Soon2008_sfig5](../../assets/images/Soon2008_sfig5.png) |
|:--:|
| Decoding and univarate activation in selection ROIs at TRs proceeding the decision. Figure from [Soon et al (2008)](https://www.nature.com/articles/nn.2112) |
