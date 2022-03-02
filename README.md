# 3D_animation_simulink

### Contents
- Simulink project for a 3D visualization of the modeled movement of the body and the head of an hoverfly.
- 3D file for head (_Mouche3D/Head.stl_) and abdomen (_Mouche3D/Body.stl_) of a hoverfly.


### Instructions

- When you will lunch the file, the 3D visualisation will be in the matlab interface:

![screenshot](https://user-images.githubusercontent.com/100707728/156327397-3d925374-3167-46ac-969c-c573c94f6310.png)

- In my case I needed two visualisations, one without gravity where I can see in one point the fly rotating (Simulinkfile_V2.slx), one with the fly rotating during the fall (Simulinkfile_V1.slx). For that I add or suppress gravity in the box "Mechanism Configuration": 
![screenshot](https://user-images.githubusercontent.com/100707728/156331065-db82e784-4d51-46bb-b5ca-17113085d56a.png)

### Notes
- This repository only explains the visualization, not the modeling.
- MATLAB version: MATLAB R2018a
- Scientific paper link to the modeling: Anna Verbe, Léandre P. Varennes, Jean-Louis Vercher, Stéphane Viollet; How do hoverflies use their righting reflex?. *J Exp Biol* 1 July 2020; 223 (13): jeb215327. doi: https://doi.org/10.1242/jeb.215327

[go](https://doi.org/10.1242/jeb.215327){:target="_blank" rel="noopener"}
