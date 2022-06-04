---
date: "2022-03-05"
external_link: ""
image:
  caption: Photos by Hiten Patel
  focal_point: Smart
links:
slides: ""
summary: I was team leader of the winning team in the **Robofest2.0** competition under the powered lower-limb exoskeleton category. The competition was a **state-level** competition, and teams from **tier-1** universities such as **SVNIT, Nirma University, BVM, and more** participated. Click and find more details regarding the competition and our project.  
tags:
- Rehabilitation Robotics
- Mechanical & Mechatronics Design 
- Control Systems
title: Powered Lower Limb Exoskeleton
url_code: https://github.com/devsonni/Powered-Lowerlimb-Exoskeleton
url_pdf: https://github.com/devsonni/Powered-Lowerlimb-Exoskeleton/blob/main/Pdf/Powered%20Exoskeleton%20-%20ITM%20Vocational%20University.pdf
url_slides: https://drive.google.com/file/d/1UiS9KuFzgWpcNpdP616V2AENGmsnLGZb/view?usp=sharing
url_video: "https://youtu.be/J-kVJl1uBLg"
---
---------------------------------------------------------------------------------------------------------------------------
{{< youtube J-kVJl1uBLg >}}

---------------------------------------------------------------------------------------------------------------------------    

## **This project was build for the ROBOFEST2.0 competition which was organized by GUJCOST (Gujarat Council On Science and Technology)**
     
### Competition was conducted in three rounds:
1. Idealization round (won **50,000 INR** for presenting solid ideas for building exoskeleton robot & for building proof of concept).           
2. Proof of concept round (won **2,00,000 INR** for building proper working proof of concept & for building final prototype).   
3. Finale (won **5,00,000 INR** ~ 6,600 USD as a **winning prize**).
4. In short, we avail total of **7,50,000 INR** in this project.


### Technical Details     

- Human gait trajectories was analysed & plotted with the use of [**kinovea**](https://www.kinovea.org/) software.
- Torque requirements of each lower-limb joints was calculated with the use of musculoskeletal model in [**opensim**](https://opensim.stanford.edu/) software.
- According to torque requirements **DC planetary geared motors** was selected and **spur gears** was designed.
- Whole body with the gears was designed in **solidworks**.
- Six proportional derivative and integral (**PID**) controllers was coded on **arduino** micro-controller in a way that follows the angle inputs and feedback was given by **encoders**.
- All system parameters such as PID constants, speed of exoskeleton, & etc. was tuned by trial and error method.

### Currently, Robot is showcasing at India's first & only Robotics gallery in Ahmadabad, Gujarat.
### Watch linked video to see robot in working.