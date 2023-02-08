# <p align="center">Safe Deep Learning-Based Global Path Planning Using a Fast Collision-Free Path Generator
<div align = center>
<a href='https://github.com/our-projects-github/Safe-Deep-Learning-Based-Global-Path-Planning-Using-a-Fast-Collision-Free-Path-Generator'><img src='https://www.linkpicture.com/q/cover_10.png' type='image'></a>
<div align = center>
<a href='https://github.com/allenai/ai2thor-colab'><img src='https://www.linkpicture.com/q/cover_ai2thor.png' type='image'></a>
<div align = left>
    
---
    
#### 📃 paper
- Link:  </a> <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4170011" target="_blank">
        <img src="https://img.shields.io/badge/Paper-Link-orange">

#### 📝 Authors

1. Shirin Chehelgami:   </a> <a href="https://scholar.google.com/citations?hl=en&user=9o7mR3oAAAAJ" target="_blank">
        <img src="https://img.shields.io/badge/Google Scholar-Link-blue"> </a> <a href="https://github.com/shirin-chehelgami" target="_blank">
        <img src="https://img.shields.io/badge/github-Link-darkblue">

2. Erfan Ashtari:  </a> <a href="https://scholar.google.com/citations?user=HAQgK8UAAAAJ&hl=en" target="_blank">
        <img src="https://img.shields.io/badge/Google Scholar-Link-blue"> </a> <a href="https://github.com/erfan-ashtari" target="_blank">
        <img src="https://img.shields.io/badge/github-Link-darkblue">

<div align = center>
  
# Instructions

<div align = left>
  
#### AI2THOR_py    
    
- <strong> ai2thorgeneratepatches: </strong> contain a function that displays polygons of the considered environment in AI2THOR.
    

- <strong> ai2thorgeneratesamlpes: </strong> contain functions that generates sample points from free-space in the environment.
    
    
- <strong> ai2thorcreatedata: </strong> contain functions that creates any amount of path data that is needed using GB method for the desired environment.
    
    
- <strong> ai2thorprocessdata: </strong> contains functions that selects the required input and output of the LSTM network using the path create by the GB method.
        
    
- <strong> ai2thorloss: </strong> tensorflow implementation of the MSE-NER and keras implementation of the MSE loss functions.
    
    
- <strong> ai2thorloss: </strong> implementation of the LSTM network (OracleNet) used for path planning.
    
    
- <strong> ai2thortrain: </strong> contains functions that train the LSTM network using the processed data created by GB method and save the model.
    
    
- <strong> ai2thortest: </strong> contains functions that evaluate the trained model for the desired as well as random start and goal points.

    
    
    
    
## References
#### 🤖 AI2THOR
- Link:   </a> <a href="https://ai2thor.allenai.org/" target="_blank">
        <img src="https://img.shields.io/badge/AI2THOR-Website-green">

#### 🦾 AI2THOR Full-Starter
- Link:  </a> <a href="https://colab.research.google.com/github/allenai/ai2thor-colab/blob/main/templates/AI2_THOR_Full_Starter_Template.ipynb" target="_blank">
        <img src="https://img.shields.io/badge/AI2THOR-Google Colab-green">
---

