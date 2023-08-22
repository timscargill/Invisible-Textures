# Invisible Textures

This repository accompanies the paper '[_Invisible Textures: Comparing Machine and Human Perception of Environment Texture for AR_](https://www.researchgate.net/publication/372985913_Invisible_Textures_Comparing_Machine_and_Human_Perception_of_Environment_Texture_for_AR#fullTextFileContent)', to appear at ACM Immercom 2023 (co-located with ACM MobiCom 2023). In this paper we compare the effect of environment texture on machine perception for augmented reality (AR), i.e., visual-inertial simultaneous localization and mapping (VI-SLAM), with human perception of texture, to inform the design of environments which support good device tracking performance yet have minimal impact on user perception of virtual content. 

We perform extensive experiments on the effect of visual texture on VI-SLAM performance using our previously published game engine-based emulator, **Virtual-Inertial SLAM**. For more information on this tool, implementation code and instructions, and examples of the types of projects it can support, please visit the [Virtual-Inertial SLAM GitHub repository](https://github.com/timscargill/Virtual-Inertial-SLAM/).  

# Motivation

The motivation for Invisible Textures is the conflicting requirements of machine and human peception in AR. While complex environment textures are beneficial for device pose tracking (and therefore virtual content stability), human perception of virtual content can be impacted by textured environments. This includes background textures being visible through transparent regions of virtual content on AR headsets with optical see-through displays (e.g., the Microsoft HoloLens, Magic Leap), as shown belown:

![OST-example1](https://github.com/timscargill/Invisible-Textures/blob/main/OST-example1.png?raw=true)

# Texture Datasets

For our VI-SLAM visual texture experiments we chose the texture images used in '[_Predicting Complexity Perception of Real World Images_](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0157986)'. This paper also provides the human subjective scores of complexity we use for comparison with human perception of texture. 

The set of 112 textures comprises two datasets: 54 images from the [VisTex dataset](https://vismod.media.mit.edu/vismod/imagery/VisionTexture/), and 58 images from the [RawFooT dataset](http://www.ivl.disco.unimib.it/minisites/rawfoot/):

VisTex            |  RawFooT
:-------------------------:|:-------------------------:
![]([https://github.com/timscargill/Invisible-Textures/blob/main/VisTex.png)  |  ![](https://github.com/timscargill/Invisible-Textures/blob/main/RawFooT.png)

# Virtual Environments

We


# Citation

To cite Invisible Textures in an academic work, please use: 

```
@inproceedings{Invisible-Textures,
  title={Invisible textures: Comparing machine and human perception of environment texture for AR},
  author={Scargill, Tim and Hadziahmetovic, Majda and Gorlatova, Maria},
  booktitle={To appear in Proceedings of ACM Immercom '23 (co-located with ACM MobiCom '23)},
  year={2023}
 }
 ```

# Acknowledgements 

The authors of this repository are Tim Scargill and Maria Gorlatova. Contact information of the authors:

* Tim Scargill (timothyjames.scargill AT duke.edu)
* Maria Gorlatova (maria.gorlatova AT duke.edu)

This work was supported in part by NSF grants CSR-1903136, CNS-1908051, and CNS-2112562, NSF CAREER Award IIS-2046072, a Meta Research Award and a CISCO Research Award. 
