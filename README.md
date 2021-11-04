# Simulation of Ecosystem in Rossumøya
The project used test-driven approach for modeling of the Ecosystem in the Rossumøya island. All the Object-Oriented Principals were considered in the development of this Simulation software.
<br>
Rossumøya is an imaginary island that has different landscapes "Desert, Savannah, Jungle, Ocean, Mountain". These landscapes have different animal types,'Hebivores and Carnivores'. Herbivores are meat eater and Carnivores are veggy eater. The animals' eating is based on their fitness (animals with higher fitness eat first). The life cycle of the simulation starts with feeding all animals in cells. Second stage is procreation where animals give birth. Animals give birth based on their probability of giving birth and based on the number of the animals in the cell. Third stage is migration where animals migrate based on the order of their fitnesses and based on the individual probability of animals to migrate. Animals migrate only from current cell to adjacent diagonal cells. Forth stage is animals growing up where their fitnesses and weights decrease. Last stage is dying stage where animals with higher probability to die will be removed from the cells.
<ul>
  <li>The Biz_Rules pdf file shows the rules and events affecting the animals' population.</li>
  <li>For documenting the simulation modules on a website, Sphinx tool was used. </li>
<br>

At the first step, the following model was designed to have a better understanding of the environment and associations or interactions between entities and concepts (Extra work)
<br>
![alt text](https://github.com/nasibehm/BioSimulation/blob/master/model.png)
