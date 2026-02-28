# App-Physics-157
This is a repository of projects done in **App Physics 157**, officially *Computational Analysis and Modeling in Physics*. 

## Projects under this Folder:
1. Percolation = This project works with randomized cellular automata and studies how likely a state (e.g. water breaking through rock, or rock fracturing laterally) is going to span the space, given occupation probability, that is, the threshold below which a cell of a lattice is in occupied state (this is the one that is analogously filled by fracture or water in a rock).
**Skills**: Cellular Automata, Conditionals, For-loop statements

2. Ising Model = In this project, we have built upon the cellular automaton of Percolation. But this time, we only have two types of cells and an individual can flip between type if their assigned probabilities are greater than a number dependent on their energies. That is, an individual's tendency to flip is affected by their grid's temperature via its inverse.
**Skills**: Cellular Automata, Diffusion, Conditionals, For-loop statements.

3. Diffusion-Limited Aggregation (DLA) = Solute Precipitation and Cluster Growth in a fluid with uniform solute influx is modelled under random walk, that is, the particles do not deterministically find for clusters. They still end up attaching to an existing dendritic cluster, in which the interior becomes inert for sticking with incoming particles. As such, it also has a non-integral fractal dimension, smaller than that of a 2D plane.
**Skills**: Diffusion, Random Walks, For-loop statements.

4. Schelling Model = It physically models the system of individual agents, each with a set tolerance, which for simplicity is set equal. Their happiness is calculated by the proportion of their alike neighbors from that of the total from eight directions (vacant cells not counted). If the agent is unhappy, they would randomly walk to an empty spot until there's sufficient like neighbors. As seen here, at an optimally set tolerance, agents form a large exclusive cluster for their kind, almost always separated to that of another camp by emptty spaces as a buffer. This can serve as a primitive model of how people of a certain demographic cluster or segregate in a city, only to be improved by more sociological, psychological, and/or economic assumptions.
**Skills**: Segregation, Clustering, Conditional Transport, Agent-based Modeling

5. Signal Processing = (*This is an ongoing project*) Given a data from Laser Interferometer Gravitational-Wave Observatory (LIGO), we're tasked to retrieve the region where a gravitational wave could have existed in the time domain. Initially, we have, by visual inspection, sampled a time window from the given output data from LIGO. Then, it is transformed to the frequency domain, filtered out the frequencies where seismic, atmospheric, material, and other known irrelevant oscillations dominates. Time window and frequency masks are adjusted until a peak is detected at around time of 14 seconds, and frequency of between 100 and 200 Hz, where the Tukey-windowed spectrum is almost flat with barely discernible spikes. This detected peak is likely the desired "chirp", or the gravitational wave signal from black hole collision. Next week, the data is expected to be further cleaned to significantly reduce the noise in comparison to the signal.
**Skills**: Tukey Window, Frequency Masking, Physics-Informed Data Analysis, Fourier Transform
