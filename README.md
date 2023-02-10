<div align = center>
<a href='https://github.com/our-projects-github/Safe-Deep-Learning-Based-Global-Path-Planning-Using-a-Fast-Collision-Free-Path-Generator'><img src='https://github.com/our-projects-github/Safe-Deep-Learning-Based-Global-Path-Planning-Using-a-Fast-Collision-Free-Path-Generator/blob/main/cover.png' type='image'></a>
<div align = center>
<a href='https://github.com/allenai/ai2thor-colab'><img src='https://github.com/our-projects-github/Safe-Deep-Learning-Based-Global-Path-Planning-Using-a-Fast-Collision-Free-Path-Generator/blob/main/cover_ai2thor.png' type='image'></a>
<div align = left>
    
---
    
# <p align="center"> <fon>Safe Deep Learning-Based Global Path Planning Using a Fast Collision-Free Path Generator</strong>
    
### 📃 papers
- Safe Deep Learning-Based Global Path Planning Using a Fast Collision-Free Path Generator:  </a> <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4170011" target="_blank"><img src="https://img.shields.io/badge/Preprint-Link-gold"> </a>
    
- Synergy of Deep Learning and Artificial Potential Field Methods for Robot Path Planning in the Presence of Static and Dynamic Obstacles:  <a href="https://ieeexplore.ieee.org/document/9827047   " target="_blank">
        <img src="https://img.shields.io/badge/IEEE-Link-gold">
    
    

 
### 📝 Authors

1. <strong>Shirin Chehelgami:</strong>   </a> <a href="https://scholar.google.com/citations?hl=en&user=9o7mR3oAAAAJ" target="_blank">
        <img src="https://img.shields.io/badge/Google Scholar-Link-lightblue"> </a> <a href="https://github.com/shirin-chehelgami" target="_blank">
        <img src="https://img.shields.io/badge/github-Link-blue"> </a> <a href="https://www.linkedin.com/in/shirin-chehelgami-208568148/" target="_blank">
        <img src="https://img.shields.io/badge/Linkedin-Link-darkblue"> </a> <a href="https://www.researchgate.net/profile/Shirin-Chehelgami" target="_blank">
        <img src="https://img.shields.io/badge/Researchgate-Link-lightgreen">
    
2. <strong>Erfan Ashtari:</strong>  </a> <a href="https://scholar.google.com/citations?user=HAQgK8UAAAAJ&hl=en" target="_blank">
        <img src="https://img.shields.io/badge/Google Scholar-Link-lightblue"> </a> <a href="https://github.com/erfan-ashtari" target="_blank">
        <img src="https://img.shields.io/badge/github-Link-blue"> </a> <a href="https://www.linkedin.com/in/erfan-ashtari-60241ba5/" target="_blank">
        <img src="https://img.shields.io/badge/Linkedin-Link-darkblue"> </a> <a href="https://www.researchgate.net/profile/Erfan-Ashtari" target="_blank">
        <img src="https://img.shields.io/badge/Researchgate-Link-lightgreen">

---

### Explanation

This repository share the implementation of "Safe Deep Learning-Based Global Path Planning Using a Fast Collision-Free Path Generator". in this project we present a safe deep learning based global path planning method. this method is based on an LSTM model which predicts paths for desired start and goal points in an enviroment containing polygonal obstacles. for obtaining safe paths which have appropriate distance from obstacles we developed a new loss function that is implemented in this project. you can use both "main" and "main_test a sample" notebooks for your experiments to do the project from scratch or use the pre-traind models. the Results of this project led to publishing 2 papers which you can access from the above links.  


  
# Instructions
   

### ⚙ Usage Steps
1. clone the repository in your google drive. 
2. use the main or main_test a sample notebooks. 
3. In the second cell of the notebooks, you can change the root directory for accessing AI2THOR_py folder.

---       
    
### 📄 main 

<strong>Use it for doing all the project from the scratch.</strong>
<br> 
At first, it gets the number of your desired environment between 194 different AI2THOR environments. Then it creates a map containing polygonal obstacles

---

### 📄 main_test a smple  

<strong>Use it for simulating a sample path in AI2THOR environment.</strong>
<br> 
this notebook runs the simulation of AI2THOR on a path that you can create using a pre-trained model. the output of this noteboke contains 3 videos of the robot movement from different point of views.

---
    
### 📁 AI2THOR_py    
    
- <strong> ai2thormap: </strong> creates map contains obstacle polygons for AI2THOR environments
    
    
- <strong> ai2thorgeneratepatches: </strong> contain a function that displays polygons of the considered environment in AI2THOR.
    

- <strong> ai2thorgeneratesamlpes: </strong> contain functions that generates sample points from free-space in the environment.
    
    
- <strong> ai2thorcreatedata: </strong> contain functions that creates any amount of path data that is needed using GB method for the desired environment.
    
    
- <strong> ai2thorprocessdata: </strong> contains functions that selects the required input and output of the LSTM network using the path create by the GB method.
        
    
- <strong> ai2thorloss: </strong> tensorflow implementation of the MSE-NER and keras implementation of the MSE loss functions.
    
    
- <strong> ai2thormodel: </strong> implementation of the LSTM network (OracleNet) used for path planning.
    
    
- <strong> ai2thortrain: </strong> contains functions that train the LSTM network using the processed data created by GB method and save the model.
    
    
- <strong> ai2thortest: </strong> contains functions that evaluate the trained model for the desired as well as random start and goal points.
    

- <strong> AI2THOR_PATH2GIF: </strong> Simulates the Robot movement in an AI2THOR environment.
    
    
    
    

  
# References

#### 📃 Reference paper   
- Neural Path Planning: Fixed Time, Near-Optimal Path Generation via Oracle Imitation :   </a> <a href="https://ieeexplore.ieee.org/abstract/document/8968089" target="_blank">
        <img src="https://img.shields.io/badge/IEEE-Link-darkblue"> </a> <a href="https://arxiv.org/abs/1904.11102" target="_blank">
        <img src="https://img.shields.io/badge/Arxiv-Link-blue">


#### 🤖 AI2THOR
- Link:   </a> <a href="https://ai2thor.allenai.org/" target="_blank">
        <img src="https://img.shields.io/badge/AI2THOR-Website-green"> </a> <a href="https://github.com/allenai/ai2thor-colab" target="_blank">
        <img src="https://img.shields.io/badge/AI2THOR-Github-darkgreen">

#### 🦾 AI2THOR Full-Starter
- Link:  </a> <a href="https://colab.research.google.com/github/allenai/ai2thor-colab/blob/main/templates/AI2_THOR_Full_Starter_Template.ipynb" target="_blank">
        <img src="https://img.shields.io/badge/AI2THOR-Google Colab-orange">
---

# Gallery / Cool things

You can open a Mixture graph just by double clicking any texture field in the inspector with a Mixture assigned to it.
![](docs/docfx/images/MixtureOpen.gif)

[Surface Gradient](https://blogs.unity3d.com/2019/11/20/normal-map-compositing-using-the-surface-gradient-framework-in-shader-graph/) powered normal map operations.
![](docs/docfx/images/NormalBlend.gif)

Extract buffers (depth, normal, color or position) from the rendering of a prefab and use it directly in the graph (HDRP Only).
![](docs/docfx/images/SceneCapture.gif)

Fractal nodes in Mixture:
![image](https://user-images.githubusercontent.com/6877923/102915300-d8944e00-4481-11eb-8e93-f7a57c21b830.png)

Mixture Variants:

https://user-images.githubusercontent.com/6877923/115474571-03c75800-a23e-11eb-8096-8973aad5fa9f.mp4


Earth Heightmap node:

https://user-images.githubusercontent.com/6877923/123006036-64e2e780-d3b7-11eb-922e-018994b32da5.mov
