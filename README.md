
   Copyright (C) 2019 Bartomeu Rubí, Adrián Ruiz, 
                      Ramon Pérez, Bernardo Morcego

 Path-Flyer is free software; you can redistribute it and/or modify
 it under the terms of the GNU General Public License as published by
 the Free Software Foundation; either version 2, or (at your option)
 any later version.

 Path-Flyer is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 GNU General Public License for more details.
 
Authors:
Bartomeu Rubı́, Adrián Ruiz, Bernardo Morcego, Ramon Pérez.
Specific Center of Research at CS2AC in the Universitat Politècnica de Catalunya (UPC).
Rbla Sant Nebridi 22, Terrassa (Spain). (email: tomeu.rubi, adrian.ruiz, bernardo.morcego,
ramon.perez at upc.edu)

# Path-Flyer: A Benchmark of Quadrotor Path Following Algorithms

The benchmark has been build upon the Quad-Sim platform¹, a quadrotor simulation
tool developed on the Drexdel University for simulation and control of quadrotors. That is,
it has been improved and modified to have a realistic mathematical and dynamic model of the
quadrotor and its environment, to implement a proper structure to solve the path following
problem and include various path following algorithms, and to incorporate new functionalities 
suited for the present benchmark.

¹https://github.com/dch33/Quad-Sim

Some key features of Path-Flyer are:

• It has a complete and validated model of the Asctec Hummingbird Quadrotor.

• Wind disturbance and noise on the measured states are modeled and can be customized.

• Four path following algorithms; Non-linear Guidance Law (NLGL), Carrot-Chasing
and its adaptive versions have been implemented.

• Path following algorithms can be tested in diverse simulation scenarios.

• A user interface helps the user to modify test conditions and to explore simulation
results.

• It is modular and programmable, meaning that new path following algorithms and/or
reference paths can be incorporated with ease.

In the user guide it is found how to install the benchmark, how to use the user interface,
how to modify parameters such as wind disturbance or noise, how to program a new algo-
rithm and how to incorporate new path references.

Hope you find it useful. If you have any doubts do not hesitate to contact us.


Note: More information about the mathematical model of the quadrotor and its environment,
the implemented path following algorithms and control structure, and the validation
process of the Path-Flyer platform is found on the following publication:

Rubı́, B., Ruiz, A., Morcego, B., and Pérez, R. (2019). Benchmark of Quadrotor Path Following
Algorithms [SUBMITTED]. In 2019 15th IEEE International Conference on Control and
Automation (ICCA).