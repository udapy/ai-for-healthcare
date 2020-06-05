## Regulatory Landscape
Given what you learned throughout this lesson, but especially what we just learned about key stakeholders, we want you to get creative in this lesson and imagine a type of algorithm that you think would be clinically useful for 2D medical imaging, and what the FDA would think about it. This exercise is open-ended because there isn't really a right or wrong answer. What we want you to do is synthesize your current knowledge into a holistic idea about 2D imaging as it could be brought from bench to bedside.<br>

Imagine an algorithm and cover the following elements in your solution:
- Disease or abnormality of interest
- What type of 2D imaging you will use
- What type of algorithm you would use (segmentation, localization, or classification)
- How your algorithm would fit into a medical imaging workflow
- How you think the FDA would classify your algorithm
---
Answer:<br>
- The algorithm would use Chest CT scan data and a segmentation algorithm will be used to segment ground-glass opacity (GGO) to detect early stage COVID19 infection and a pulmonary consolidation (PC) to detect late stage COVID19 infection from CT axial slice. [1]

- This would have to occur in the workflow after digitization of the images, but before the pathologist got to the image. Our algorithm would help radiologist quickly detect infectious region (GGO/PC)  in lungs, which will reduce time to get patient's COVID19 test results. Further, classify early stage or late stage infections.

- This could be Class II or Class III, because if FP increases it is risk to spread of a infection COVID19. If radiologist looks image again after segmentation, it can be fall into Class II.

[1] "Inf-Net: Automatic COVID-19 Lung Infection Segmentation from CT Images" : https://arxiv.org/pdf/2004.14133.pdf