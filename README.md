# RED-E- Regional Evolutionary Distinctiveness and Endangerment R Code

My first coding project! It's definitely rough, and I don't code much in R anymore, but I'm leaving it this way so that I can see where I came from. 

Conservation is costly, and choices must be made about where to best allocate limited resources. I propose a regional evolutionary diversity and endangerment (RED-E) approach to prioritization of endangered species. It builds off of the evolutionary diversity and global endangerment (EDGE) approach, but will allow conservation agencies to focus their efforts on species in specific regions. I used the RED-E approach to prioritize mammal and bird species listed under the U.S. Endangered Species Act (ESA), as well as to make a ranking of species without ESA critical habitat (CH), as a practical application. Regional conservation approaches differ significantly from global approaches. The RED-E approach places a high significance on the level of endangerment of a species, but also allows for very distinct species to have increased prioritization on the RED-E list. Using the CH RED-E list, the U.S. government could begin focusing resources toward endangered and genetically diverse species.

[Read my thesis here!](https://digitalcommons.fiu.edu/etd/2267/)

The bird code loops through a .tree data source, which held 10,000 possible 
evolutionary trees to show how closely related different bird species are.

The birds that were outside of the US were trimmed from the tree and 1000 of
the trees were looped through to find the average Evolutionary Distinctivess 
value for each species. 

For mammals, we only had 3 trees from which to calculate the Evolutinary 
Distinctiveness value, but the process was much the same as the bird script.
