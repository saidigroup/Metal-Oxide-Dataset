# Metal-Oxide-Dataset
Supporting Data for the Metal Oxide MLP
<br><br>
If you use this dataset, please cite: <br>
https://doi.org/10.1021/acs.jpclett.2c03445
<br><br>
If you use the MgO melting dataset (liquid and solid-liquid MgO), please also cite:<br>
https://doi.org/10.1021/acs.jpclett.3c02424
<br><br>
The dataset consist of the *.raw and *.npy files. The former is a text file and the latter is a binary Numpy file. <br>
The *.pb file is the pre-prepared potential file. The details on the software packages utilizing this potential and the generation of it can be found in our publication. This will be added once it is publicly available <br>
<br>
The dataset can be turned into a human readable format through Numpy.
<br>
For bulk potentials the directory structure is:<br>
[iteration #] -- [Materials Project Structure ID] -- [cell size] -- [temperature in Kelvin] <br>
<br>
The surface, additional structure, and thermal expansion dataset are meant to be combined with the bulk potential, hence the iteration number continues from the bulk.<br>
<br>
The surface dataset directory structure is: <br>
[iteration #] -- [surface orientation] -- [surface thickness] -- [surface area] -- [temperature in Kelvin] <br>
<br>
The thermal expansion dataset directory structure is: <br>
[iteration #] -- [% lattice expansion/contraction] -- [temperature in Kelvin]

![image](https://user-images.githubusercontent.com/51385062/199827439-3f1a17f1-7c7f-480b-8142-4d81292864d6.png)
