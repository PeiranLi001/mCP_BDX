Here are the simulated samples.

The first radiation length approximation is in ./Madgraph_simulation

The shower, (including bremsstrahlung(trident), annihilation, Compton process), is in ./Shower

bremsstrahlung process: e- N -> e- N mCP+ mCP-

bremsstrahlung process: e+ N -> e+ N mCP+ mCP- where the e+ appears during QED shower

annihilation process: e+ e- -> mCP+ mCP- where the e+ appears during QED shower, e- is at rest

Compton process: gamma e- -> mCP+ mCP- e- where the photon appears during QED shower

You can also find the sample file in Google drive:

https://drive.google.com/drive/folders/1dHyj4BjHfqAv6PO22GyiLwriO0WGBV10?usp=drive_link

For example:

the benchmark for Mass of mCP is 0.001 GeV, produced by annihilation, please use ./Shower/annihilation/m_1e_3GeV/m_1e_3GeV.csv

don't use ./Shower/annihilation/m_1e_3GeV/m_1e_3GeV_10GeV.csv , ./Shower/annihilation/m_1e_3GeV/m_1e_3GeV_9GeV.csv , ...

Inside the .csv sample file, each row refers to one mCP's 4-momentum and weight: {px, py, pz, E, weight}.

Sometimes it is empty in the .csv sample file, because the total production is zero.

total_number_mCP_include_shower.nb includes the total number of mCP and anti-mCP for production.

