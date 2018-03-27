Learning Areal Image Similarity using Triplet Networks

Vytautas valaitis, Virginijus Marcinkevičius, Rokas Jurevičius
Vilnius University, Faculty of Mathematics and Informatics

-Įvadas apie sritį
Unmanned areal vehicles faces localization challanges in sattelite navigation systems denied enviroment.
Images taken from onboard cameras must be compared to ones stored as a map to support many localization algorithms.

-Problema
Image similarity estimation can be achieved by template maching, correlation, (we chose Pearson correlation as baseline), distance based algorithms, etc.
Pearson correlation is not robust enought to adapt to affine transformations (e.g. rotation higher than 5 degrees, as our experiments shows).

We propose the new architecture of triplet neuron network to learn image simiarity.
The proposed network uses VGG16 networks bottom layers, top layers structure being suggested by authors.

-Sprendimas
We used our custom flight simulator, to generate areal images similar to ones obtainable in UAV's flight.
Images were matched to the maps from sattelite photo.

-Šiek tiek apie rezultatus
The matching results from our proposed network and Pearson correlation are presented in this paper.
