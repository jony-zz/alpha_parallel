This folder contains the input files for the capacitor set-up with SPC/E water.

System description:

The system corresponds to SPC/E water confined between two plates separated by a distance l_p = 950 Å. Two different voltage differences between the plates are considered.

Folder structure:

1. 0_V/

   Simulations performed with a voltage difference of ΔV = 0 V between the plates.

2. 0.5_V/

   Simulations performed with a voltage difference of ΔV = 0.5 V between the plates.

Files included in each folder:

Each folder contains 10 LAMMPS input files and the corresponding equilibrated data file.

The input files are named:

   in.water_number

where number labels the different runs. These input files differ in the duration of the initial high-temperature run at 600 K, with a difference of 25 ps between consecutive runs.

The data file is named:

   data_eq.lmp

This file contains the equilibrated configuration used as the initial structure for the simulations.
