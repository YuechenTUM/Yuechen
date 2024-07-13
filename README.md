# Main Projects

## CFD simulation and optimization of water pit heat storage
- **Description**: Master thesis.
- **Technologies Used**: Ansys Fluent.

## Abstract
With the progress of industrialization, there is a growing focus on developing sustainable technologies to reduce carbon emissions and slow global warming. For instance, photovoltaics, as a mature technology, has been widely used in recent years, the mismatch between the production and demand side of solar energy must be clarified, although it is a promising renewable energy alternative, hence, applying seasonal thermal energy storage technology in solar district heating systems can effectively compensate for the lack of system elasticity. Among these, PTES (Pit Thermal Energy Storage) can be well integrated into DH (District Heating) to assist the solar collector field in providing flexibility to systems. Denmark has successfully implemented several large­scale projects, proving that PTES has a promising future from a practical perspective, and more and more projects using this technology are being implemented in the foreseeable future.

Considering that there are few previous studies on long­term CFD simulations of pit thermal energy storage systems, this paper aims to use CFD technology to deeply study the operating characteristics of PTES systems over a long period. It aims to improve computational efficiency by optimizing the computational model, numerical settings, hardware and software settings, exploring the balance between computational efficiency and accuracy, and aiming to quickly and accurately complete the simulation in the long run. 

<table>
  <tr>
    <td style="text-align: center;">
      <img src="https://github.com/YuechenTUM/Yuechen/raw/main/Figures/Dronninglund%20PTES.jpg" alt="Dronninglund PTES" width="500" height="300"/>
      <p>
        Figure 1: <a href="https://planenergi.eu/wp-content/uploads/2023/09/SUNSTORE-3-Phase-2-Implementation.pdf" target="_blank">Aerial view of the PTES and solar collector field</a>
      </p>
    </td>
    <td style="text-align: center;">
      <img src="https://github.com/YuechenTUM/Yuechen/raw/main/Figures/Dronninglund%20Implementation.png" alt="Dronninglund Implementation" width="500" height="300"/>
      <p>
        Figure 2: <a href="https://planenergi.eu/wp-content/uploads/2023/09/SUNSTORE-3-Phase-2-Implementation.pdf" target="_blank">Construction of the pit heat water storage</a>
      </p>
    </td>
  </tr>
</table>

## Video Demonstration
[![Watch the video](https://img.youtube.com/vi/qmprPzF2EIw/0.jpg)](https://www.youtube.com/watch?v=qmprPzF2EIw)

## Numerical analysis of Long term 3D model

<div style="display: flex; flex-wrap: wrap;">
  <div style="flex: 1; max-width: 50%;">
    <img src="https://github.com/YuechenTUM/Yuechen/raw/main/Figures/Model_Mesh.jpg" alt="Model Mesh" style="width: 50%; max-width: 600px;"/>
  </div>
  <div style="flex: 1; max-width: 50%; padding-left: 10px;">
    <p>
      The geometry is constructed using ANSYS DesignModeler, meshing is accomplished via ANSYS Meshing and the CFD simulations are conducted using ANSYS Fluent, version 2020R1. To improve efficiency and reduce calculation time, this study simplifies the model. The inlet and outlet of the original model were relocated to the centre of the water body, and the entire model was converted into a quarter using the symmetry of the origin geometry.
    </p>
  </div>
</div>
<div style="padding-top: 10px;">
  <p>
    The length and width of the computational domain of this CFD model are both 135 meters, and the height is 66 meters, the artificial computational domain size was set to 55 m from the edge of the water body and 30 m from the bottom of the water body, which was considered to eliminate the impact of the artificial computational domain size selection. The water body is prism-shaped, with a top length and width of 45 meters, a bottom length and width of 13 meters, and an overall depth of 16 meters; a slope angle of 26.6° is specially chosen for the water body to reduce construction costs and prevent sidewall collapse [18].
  </p>
</div>


