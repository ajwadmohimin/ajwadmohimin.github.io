<!-- # Research Statement -->
My research interest includes:
* Computational Fluid Dynamics, Multi-phase Flows, Fluid-Structure Interactions
* Biological Flows, Cardiovascular and Cerebrovascular Flow Simulation
* Machine Learning for Fluid System, Turbulence Modeling, Reduced Order Modeling
# Research Project
## Hemodynamics in Cerebral Aneurysms
Cerebral Aneurysm is an abnormal bulge in the wall of arteries in the brain. It usually occurs when the layers of the arterial wall get weakened and lose their integrity. Ruptured aneurysms are crucial because they result in subarachnoid hemorrhage which can be life-threatening. Behind the formation, growth, and rupture of an aneurysm, hemodynamics plays a key role. Thus, hemodynamic factors such as Wall Shear Stress, Oscillatory Shear Index, Relative Residence Time, etc. anticipate to predict the status of an aneurysm.\\
This work uses the open-source CFD toolbox *OpenFOAM* paired with patient-specific geometry and pulsatile flow rate to study the hemodynamics in the aneurysm sac. Then, visualization and the extraction of hemodynamic factors were performed using a python script in *Paraview*.\\
~~~
<p align="center">
<img src="/assets/ProjectFig/AneurysmHemodynamics/Aneurysm1.GIF" height="193px"></img>
<img src="/assets/ProjectFig/AneurysmHemodynamics/Aneurysm3.GIF" height="193px"></img>
<img src="/assets/ProjectFig/AneurysmHemodynamics/Aneurysm2.GIF" height="193px"></img>
</p>
~~~ 
* **Md. A. Mohimin**, N. M. Arefin, and P. Das, "Cerebral Aneurysm Hemodynamics In Low Hematocrit Conditions: Numerical Simulations and Analysis," in 14th International Conference on Mechanical Engineering, Dhaka, Bangladesh, Dec. 2023. (Under Review) \\
* **Md. A. Mohimin**, P. Das, and Md. A. I. H. Sharker, "Effect of RANS Turbulence Model on The Hemodynamic Factors in A Middle Cerebral Artery Aneurysm," in 7th International Conference on Mechanical Engineering and Renewable Energy 2023, Chattogram, Bangladesh, Nov. 2023. (Accepted for publication)
--------
## Flow Diverting Stents for Aneurysms
Flow-diverting stents have emerged as a potential minimally invasive treatment option for intracranial aneurysms. When placed across the neck of an aneurysm, a porous stent disrupts the blood inflow into it, which, over time, promotes blood clotting inside the aneurysm sac. Thus, the risk of rupture is minimized by isolating the aneurysm from normal blood circulation.\\
However, this is a relatively newer technique to treat brain aneurysms and requires further study. This ongoing project seeks to shed light on flow diverter parameters and their optimization for treating aneurysms having different morphology.

* **Md. A. Mohimin**, P. Das, and A. Barua, "Non-Newtonian Effects On Hemodynamics In Stented Model Aneurysm," presented at the Research Fair 2023, CUET, Chattogram-4349, Bangladesh, Aug. 2023. (Poster)
--------------
# Codes
### FasterReconstructPar
This simple project of a few lines of code can speed up the reconstruction of decomposed parallel cases in *OpenFOAM*. Using *Python*, this script launches a series of processes for different ranges of timesteps to reconstruct them. [[github repo](https://github.com/ajwadmohimin/FasterReconstructPar)]

### Quemada Viscosity Model for OpenFOAM
The Quemada viscosity model is a quasi-mechanistic viscosity model to predict the flow behavior of non-Newtonian fluids. It is widely used in blood flow simulation to account for the effect of hematocrit level. However, it does not come by default in the *OpenFOAM* package to this date. So, as a part of a vascular flow analysis project, it was implemented in *OpenFOAM*. [[github repo](https://github.com/ajwadmohimin/Quemada-Viscosity-Model-OpenFOAM)]

### Pulsatile Parabolic Boundary Condition for OpenFOAM
A boundary condition for *OpenFOAM* to produce a parabolic velocity profile from a time-varying flow rate. It can be useful when the inlet flow rate is period (i.e., in Cardiovascular Flow Simulation). [[github repo](https://github.com/ajwadmohimin/Pulsatile-Parabolic-BC-OpenFOAM)]
