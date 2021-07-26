---
date: 2021-06-16
title: "Project: Detecting Multiple Sclerosis Symptoms using AI" 
linkTitle: "Multiple Schelrosis and AI"
tags: ["project", "reu", "multiple sclerosis", "disease", "AI", "machine learning"]
description: "This work implements machine learning algorithim Multiple Sclerosis symptoms and provides treatment options available"
Author: "Raeven Hatcher"
github_url: https://github.com/cybertraining-dsc/su21-reu-371/edit/main/project/index.md
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
---

[![Check Report](https://github.com/cybertraining-dsc/su21-reu-371/workflows/Check%20Report/badge.svg)](https://github.com/cybertraining-dsc/su21-reu-371/actions)
[![Status](https://github.com/cybertraining-dsc/su21-reu-371/workflows/Status/badge.svg)](https://github.com/cybertraining-dsc/su21-reu-371/actions)
Status: draft, Type: Project


Raeven Hatcher, [su21-reu-371](https://github.com/cybertraining-dsc/su21-reu-371), [Edit](https://github.com/cybertraining-dsc/su21-reu-371/blob/main/project/index.md)

{{% pageinfo %}}

## Abstract

Multiple sclerosis, also known as M.S., is a chronic central nervous system disease that potentially affects the brain, spinal cord, and optic nerves in the eyes. In this potentially disabling disease, one's immune system attacks the myelin (protective sheath) that covers nerve fibers, resulting in communication problems between the brain and the body. The cause of M.S. is unknown; however, researchers believe that genetic and environmental factors play a role in those affected. Symptoms differ significantly from person to person due to varying nerves involved. The most common symptoms include tremors, numbness or weakness in limbs, vision loss, blurry vision, double vision, slurred speech, fatigue, dizziness, involuntary movement, and muscle paralysis. There is currently no cure for Multiple sclerosis. Treatment focuses on slowing the progression of the disease and managing symptoms.  
	There is no proven way to predict how an individual with Multiple Sclerosis will progress certainly. However, researchers established four phenotypes that will assist in identifying those who are more inclined to have disease progression and help aid in more effective treatment targeting.     
	In this experiment, Artificial Intelligence will be applied by ascertaining what causes these different phenotypes and which phenotype is at most risk for disease progression using a Magnetic Resonance Scan (MRI).  

Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

**Keywords:** tensorflow, example. 

## 1. Introduction

MS or Multiple sclerosis is a potentially disabling autoimmune disease that can damage the brain, spinal cord, and optic nerves located in the eyes. It is the most common progressive neurological disability that affects adolescents. The immune system attacks the central nervous system in this disease, specifically myelin (sheth that covers and protects nerve fibers), oligodendrocytes (myelin-producing cells), and the nerve fibers located under myelin. Myelin enables nerves to send and receive electrical signals swiftly and effectively. The myelin sheath becomes scarred from being attacked. These attacks make the myelin sheath inflamed in little patches, observable on an MRI scan. These little inflamed patches potentially disrupt messages moving along the nerves, which ultimately lead to the symptoms of Multiple sclerosis. If these attacks happen frequently, permanent damage can occur to the involved nerve.  

Because Multiple sclerosis affects the central nervous system, which control all of the actions carried out in the body, symptoms can affect any part of the body and vary. The most common symptoms of this progressive disease include muscle weakness, pins and needle sensation, electrical shock sensation, loss of bladder control, muscle spasms, tremors, double or blurred vision, partial or total vision loss, to name a few. Researchers are not sure what causes Multiple sclerosis but believe those between the ages of 20 and 40, women, smoke, are exposed to certain infections, have a vitamin D and B12 deficiency, and related to someone affected by this disease are more susceptible.

It can be difficult to diagnose MS due to the symptoms usually being vague or very similar to other conditions. There is no single test to diagnose it positively. However, doctors can choose a neurological examination, MRI scan, evoked potential test, lumbar puncture, or a blood test to diagnose a patient properly. Currently, clinical practices divide MS into four phenotypes: clinically isolated syndrome (CIS), relapsing-remitting MS (RRMS), primary-progressive MS (PPMS), and secondary progressive MS (SPMS). Two factors define these phenotypes; disease activity (evidenced by relapses or new activity on MRI scan) and progression of disability. Phenotypes are routinely used in clinical trials to choose patients and conduct treatment plans. 

New technologies, such as artificial intelligence and machine learning, help assess multidimensional data to recognize groups with similar features. When implemented in apparent abnormalities on MRI scans, these new technologies have assured promising results in classifying patients who share similar pathobiological mechanisms rather than the typical clinical features. 
Researchers at UCL work with the Artificial intelligence (AI) tool SuStain (Subtype and Stage Inference) to ask whether AI can find Multiple sclerosis subtypes that follow a particular pattern on brain images? 
The results uncovered three data-driven MS subtypes defined by pathological abnormalities seen on brain images (Skylar).  The three data-driven MS subtypes are cortex-led, normal-appearing WM-led, Lesion-led. Cortex-led MS is characterized by early tissue shrinkage (atrophy) in the outer layer of the brain. Normal-appearing WM-led is identified by irregular diffused tissue located in the middle of the brain. Lastly, a lesion-led subtype is characterized by early extension accumulation of brain damage areas that lead to severe atrophy in numerous brain regions. All three of these subtypes correlate to the earliest abnormalities observed on an MRI scan within each pattern.
In this experiment, researchers utilized the SuStain tool to capture MRI scans of 6,332 patients. The unsupervised SuStain taught itself and identified those three patterns that were previously undiscovered.
 



## 3. Using Images

![Figure 1](https://github.com/cybertraining-dsc/fa20-523-314/raw/main/project/images/chart.png)

**Figure 1:** Images can be included in the report, but if they are copied you must cite them [^1].

 steps to insert picture
 1. download picture to computer
 2. Upload image into repository
 3. Change path to what I saved picture as on github
 4. Create a description for the image 


   
## 4. Datasets

Datasets can be huge and GitHub has limited space. Only very small datasets should be stored in GitHub.
However, if the data is publicly available you program must contain a download function instead that you customize.
Write it using pythons `request`. You will get point deductions if you check-in data sets that are large and do not use
the download function.
- [ ] look on google or kaggle to find dataset 
- [ ] http://biogps.org/#goto=genereport&id=1017&show_dataset=E-GEOD-21942.  look on this website! find this first
- [ ] describe the dataset found
- [ ] mode, median, mean (can calculate this to add into section)

## 5. Benchmark

Your project must include a benchmark. The easiest is to use cloudmesh-common [^2]
- [ ] define method that will be used to study the performance of the proposed method 
 
## 6. Conclusion

A convincing but not fake conclusion should summarize what the conclusion of the project is.

## 7. Acknowledgments

Please add acknowledgments to all that contributed or helped on this project.  can put instructors

## 8. References

https://www.mayoclinic.org/diseases-conditions/multiple-sclerosis/symptoms-causes/syc-20350269#:~:text=The%20cause%20of%20multiple%20sclerosis,and%20spinal%20cord%20(myelin).

Your report must include at least 6 references. Please use customary academic citation and not just URLs. As we will at 
one point automatically change the references from superscript to square brackets it is best to introduce a space before 
the first square bracket.

 [^1]: Eshaghi, A., Young, A. L., Wijeratne, P. A., Prados, F., Arnold, D. L., Narayanan, S., Guttmann, C. R. G., Barkhof, F., Alexander, D. C., Thompson, A. J., Chard, D., &amp; Ciccarelli, O. (2021, April 6). Identifying multiple sclerosis subtypes using unsupervised machine learning and MRI data. Nature News. https://www.nature.com/articles/s41467-021-22265-2. 
 [^2]: Skylar Kenney, A. E. (2021, April 12). Artificial Intelligence Identifies Novel Multiple Sclerosis Subtypes. Pharmacy Times. https://www.pharmacytimes.com/view/artificial-intelligence-identifies-novel-multiple-sclerosis-subtypes. 
