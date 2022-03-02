# 3D_animation_simulink

You will find in this project the simulink file which allowed me to obtain a 3D visualization of the modeled movement of the body and the head of an hoverfly. 
You will also find the body (head + abdomen) of an hoverfly I made in 3D (in the file Mouche3D)

I will not explain the modeling part here, only the part that lead to the 3D animation. 
When you will lunch the file, the 3D visualisation will be in the matlab interface (as you can see in this ![screenshot](https://user-images.githubusercontent.com/100707728/156327397-3d925374-3167-46ac-969c-c573c94f6310.png) )

In my case I needed two visualisations, one without gravity where I can see in one point the fly rotating (Simulinkfile_V2.slx), one with the fly rotating during the fall (Simulinkfile_V1.slx). For that I add or suppress gravity in the box "Mechanism Configuration" (in this ![screenshot](https://user-images.githubusercontent.com/100707728/156331065-db82e784-4d51-46bb-b5ca-17113085d56a.png))


Version of matlab : MATLAB R2018a

Article link to this modelisation: https://journals.biologists.com/jeb/article/223/13/jeb215327/222900/How-do-hoverflies-use-their-righting-reflex 
