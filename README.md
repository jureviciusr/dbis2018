Learning Aerial Image Similarity using Triplet Networks

Vytautas valaitis, Virginijus Marcinkevičius, Rokas Jurevičius
Vilnius University, Faculty of Mathematics and Informatics

-Įvadas apie sritį
Unmanned aerial vehicles faces localization challanges in sattelite navigation system denied enviroments.
Images taken from on-board cameras can be used to compare against orthophotographical map to support visual localization algorithms, such as particle filter localization, synchronous localization and mapping (abbr. SLAM).

-Problema
Image similarity estimation can be achieved calculating similarity measures, such as Pearson correlation, or distance based algorithms.
Pearson correlation is not robust against image displacement caused by aircraft frame movement, previous work show that aircraft heading angle error of 5 degrees causes 35% decreased in correlation measure compared with matched image with no rotational error.

In this paper, an architecture of triplet neuron network is proposed to learn image simiarity measure.
The proposed architecture incorporates VGG16 network base layers, top layer structure being suggested by authors.

-Sprendimas
Flight simulator was used to generate aerial images simulating UAV flight conditions.
Images were matched to the maps from sattelite photo.

-Šiek tiek apie rezultatus
The matching results from proposed Neural network architecture are compared against Pearson correlation.
