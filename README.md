# Skin-Mueller-Polarimetry
Repository of the MATLAB code generated for skin optical properties and plots generated in TFG Physics



In CODE #1, the IPPS space parameters are given for two selected zones: red and green ( which in the original TFG code corresponded to damaged (tattooed) and normal skin, respectively). MATLAB code also generates the IPPS tethraedrical space with all the selected values in red and green regions of P1,P2 and P3 associated parameters. This code also gives a Pseudocolored map (Pseudocolor map #1 named in the thesis) based on the characteristic decomposition of IPPs.

CODE #2 returns values of all the direct optical parameters: Index of depolarization (PD), polarizance (P), diattenuation (D) and creates an imagesc colormap of values.

CODE #3 gives all the retardance associated plots and imagesc of t (from MMT) and R (from Chipman decomposition). Also imagesc of \Delta values ( depolarization of Chipman depolarization matrix) are given. Fastaxis and transmission axis orientations are also shown in form of imagesc. 3D distributions of Components of Purity space with t values (CPs) are plotted. Code gives mean values of t and R for each of the two green and red regions, and for the all sample.

CODE #4 generates PCA analysis of previously mean values from CODE #2 and CODE #3 computed parameters that must be written in the datos_estandarizados matrix (line 4).

CODE #5 gives the representation of mean values tendency for all selected wavelengths and the 3 individuals (Figure 4.2 from the thesis). It is designed to avaluate only P1,P2,P3 or PD values aech time, and also gives the histogram distributions of the complete individual samples at the specified wavelength.


Order #1->#2->#3 must be preserved, as later scripts may need of in-previous codes defined variables.
