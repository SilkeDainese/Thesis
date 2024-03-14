**Welcome** 

This is the repository for my master's thesis in Astronomy at Aarhus University. It is still very much a work in progress. 

I am currently working on turning my thesis work into a paper, with a working title of Where are the Water Worlds. For the most up to date figure, look in the folder Figures_WhereAreTheWaterWorlds.

**A brief introduction to my work:**

The M dwarf opportunity has allowed for the observation of exoplanets with a large range of orbital periods, masses, and radii. In particular, in recent years, this has led to discussions about the existence of water worlds, planets that would be found in the mass-density diagram as planets between rocky and gas planets. 

Classification into gas, water, and rocky worlds has been largely model-based, which requires compositional assumptions. Here, I take a data science perspective on looking at the classification and groupings of small exoplanets with M-type host stars. I have gathered a sample of 55 exoplanets, upon which we used density-based unsupervised machine learning, specifically the DBSCAN algorithm, to determine the number of clusters in our 2024 sample. The algorithm robustly returns two large populations, rocky and gas planets, and a number of outliers. 
I further use a Mixture Density Neural Network, [ExoMDN](https://github.com/philippbaumeister/ExoMDN/tree/main/more_examples), to predict the composition of the planets in my sample and cluster the planets based on these using KMeans.

I find that only two populations are apparent in the data, rocky planets, and gas planets, which contradicts previous results of [Luque and Pallé (2022)](https://www.science.org/doi/10.1126/science.abl7164). 
I will be presenting my results at the conference Exoplanet V and at this year's Annual Danish Astronomy Meeting (ADAM).
 
