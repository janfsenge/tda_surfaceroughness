# tda_surfaceroughness
_Apply Topological Data Analysis for understanding surface morphology and extending ISO methods._

Surface topography and roughness evaluation play an important role in numerous engineering applications. Impact surface treatments can change the mechanical properties of metallic materials and improve the behavior of the treated surface in such applications. To model and understand the interconnections of these factors with the change of the surface morphology, suitable mathematical descriptors which are powerful enough to describe the relationship between process parameters and the surface state are needed. _Today’s standard surface roughness description methods can struggle in certain situations to understand and quantify the evolution of the surface. In this case, one could benefit greatly if more sophisticated methods existed. Herein, as a remedy for this shortcoming, methods from computational topology are proposed, namely persistence homology, which captures significant topological features and uses suitable invariants as descriptors for the surface._ Persistent homology is shown to be a natural extension of ideas and methods of the existing framework offering the possibility to enable a flexible, task-oriented choice of suitable parameters helping surface analysis. 

This repository contains the implementation for the paper (to be submitted) 
>*2021* Jan F. Senge, A. Heydari Astaraee, Pawel Dłotko, Sara Bagherifard, and Wolfram A. Bosbach _Advantages of Topological Data Analysis compared to Conventional Surface Roughness ISO Parameters on mechanically treated surfaces_ 

In this paper, a detailed numerical model of shot peening process, as an representative mechanical surface treatment, is used highlighting the transformation of the surface in accordance with the coverage percentage, the ratio of surface material being impacted, to develop suitable surface roughness parameters and compare them with the existing ones. The results indicate that opposed to the existing standard surface roughness parameters, the chosen persistence-based parameters are better in the distinction of surfaces for different stages of this process, grouping surfaces in the same stage together as well as using them as a proxy for the coverage percentage showing the benefits of using topological data analysis in conjunction with existing techniques.

The project tda_shotpeening was a brainchild from contacts established during the 2nd International Conference on Trauma Surgery Technology in Giessen 
> Bosbach, W. A., Presas, A., Roehr, C., Valentin, D., Deering, J., Lee, B. E., Yu, B., et al. [2019](https://doi.org/10.17863/CAM.45844))

and lead to discussion later the next year yielding the first draft in 
> Bosbach, W. A., Yu, B., Gonder, N. S., Tyedmers , W. A., Deering , J., D'Elia, A., Clifford, A., et al. [2020](https://www.repository.cam.ac.uk/handle/1810/313451)).
