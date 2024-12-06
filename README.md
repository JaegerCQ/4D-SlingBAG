# 4D-SlingBAG
4D SlingBAG: spatial-temporal coupled Gaussian ball for large-scale dynamic 3D photoacoustic iterative reconstruction

[***ArXiv paper***](https://arxiv.org/abs/2412.03898)

Large-scale dynamic three-dimensional (3D) photoacoustic imaging (PAI) is significantly important in clinical applications. In practical implementations, large-scale 3D real-time PAI systems typically utilize sparse two-dimensional (2D) sensor arrays with certain angular deficiencies, necessitating advanced iterative reconstruction (IR) algorithms to achieve quantitative PAI and reduce reconstruction artifacts. However, for existing IR algorithms, multi-frame 3D reconstruction leads to extremely high memory consumption and prolonged computation time, with limited consideration of the spatial-temporal continuity between data frames. Here, we propose a novel method, named the 4D sliding Gaussian ball adaptive growth (4D SlingBAG) algorithm, based on the current point cloud-based IR algorithm sliding Gaussian ball adaptive growth (SlingBAG), which has minimal memory consumption among IR methods. Our 4D SlingBAG method applies spatial-temporal coupled deformation functions to each Gaussian sphere in point cloud, thus explicitly learning the deformations features of the dynamic 3D PA scene. This allows for the efficient representation of various physiological processes (such as pulsation) or external pressures (e.g., blood perfusion experiments) contributing to changes in vessel morphology and blood flow during dynamic 3D PAI, enabling highly efficient IR for dynamic 3D PAI. Simulation experiments demonstrate that 4D SlingBAG achieves high-quality dynamic 3D PA reconstruction. Compared to performing reconstructions by using SlingBAG algorithm individually for each frame, our method significantly reduces computational time and keeps a extremely low memory consumption.

![image](https://github.com/JaegerCQ/4D-SlingBAG/blob/main/figures/4D_pipeline.png)   
_The overview framework of 4D SlingBAG._


## Display of 4D SlingBAG's results

![image](https://github.com/JaegerCQ/4D-SlingBAG/blob/main/figures/4D_liver.gif)    
_Comparison of reconstruction results of dynamic rat liver between 4D SlingBAG and UBP._  


## Guidance

This project is still under construction, we will complete it as soon as possible. Sorry for all the inconvenience!  
If you have any questions, please be free to contact us. Best wishes!
