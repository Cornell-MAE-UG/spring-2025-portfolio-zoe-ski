---
layout: project
title: MAE 4272 Blade Project 
description: Advanced CAD Project
technologies: [Autodesk Fusion, MATLAB]
image: /assets/images/Screenshot 2025-12-17 142052.png
---

For a MAE senior lab class we were tasked with designing a blade that would perform optimally in the wind tunnel we have lab access to. The blade should achieve the following design objective: Design a blade which is optimized for the peak of the probability distribution, which is 4.78m/s. The blade also must align with the given constraint and material properties outlined in the assignment details. Additionally, this blade will be designed to maximize lift-to-drag ratio. This project is used to demonstrate an understanding and application of the skills we have learned in fluid mechanics and apply them to the lab procedures and analysis skills we learned in MAE 4272. 


![Photo of old radio]({{ "/assets/images/Screenshot 2025-12-17 141943.png" | relative_url }}){: .inline-image-l}

For this project we used a MATLAB script to design a blade. First we derived our model, for this model we made the assumptions that the flow was steady and incompressible. We also assumed a Re of 50,000 and that the blades were ideal. Then we used this MATLAB model to iterate through various designs including changes in length, chord length, taper and pitch until we determined the blade that had the maximum average power output by our model. We used the NACA 4412 due to the high lift -to-drag ratio and the low angle-of-attack. We then CADED and printed our design for testing


In order to test our blade design we gathered data to determine the measured performance of our designed turbine lab to the calculated performance from our MATLAB script. For this process we recorded five power curves ranging from 3.5m/s to 7m/s. Then measured the power curves by calibrating the wind tunnel and setting the wind speed. Next we increased the voltage of the torque brake until the turbine stopped spinning. Our testing range covered a large portion of the operational range which was important to verify the expected performance range of our blade. This range was designed for an optimized peak of 4.78m/s and is set to include wind speeds that are 1 and 2 standard deviations from the peak. As part of this project I worked on the derived constraints and the CAD. As well as working with my team to determine the optimal blade for our objectives. Following our testing I also worked with my team to investigate the cause of our over calculated torque values and correlate the performance of both of our blades. 

![Photo of old radio]({{ "/assets/images/Screenshot 2025-12-17 141759.png" | relative_url }}){: .inline-image-l}

![Photo of old radio]({{ "/assets/images/Screenshot 2025-12-17 141909.png" | relative_url }}){: .inline-image-l}
