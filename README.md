# ADELE: nonlineAr Damage in a magnEto-eLastic bEam

To download the vibration dataset of the benchmark ADELE, please fill the form:


__________________________________________________________________________________________________
# Description

ADELE is a dataset of vibration in a clamped beam that exhibits nonlinear behavior even in the healthy condition, and it is exposed to a type of damage that causes the structure to display a nonlinear behavior with a different nature than the initial one. Besides, the uncertainties associated with data variation are taken into account in the application of the methodology. 

The experimental setup used is presented below. The structure monitored is formed by a clamped-free beam constructed by gluing four thin beams of Lexan together, 2.4 mm x 24 mm x 240 mm each one, to emulate a damage propagation that is described further on. Two steel masses are affixed at the free boundary and interact with a magnet, generating a nonlinear behavior in the system response, even in the reference condition due to added magnetic potential.

<img src="setup.jpg " width="80%">

The setup includes the following:

 <li> A National Instruments acquisition system: CompactDAQ Chassis (NI cDAQ-9178); A C Series Sound and Vibration Input Modules
(NI-9234); A C Series Voltage Output Module (NI-9263)</li>
 <li>Electrodynamic Transducer Labworks Inc. (ET-132) </li>
 <li>Amplifier MB Dynamics (SL500VCF) </li>
 <li>Load cell PCB PIEZOTRONICS (208C02) </li>
 <li>Accelerometer PCB PIEZOTRONICS (352C22) </li><br>
 
The electrodynamic transducer is employed to excite the structure with different signals and consider two inputs (low—1 V root mean square (RMS) and high—6 V RMS). The accelerometer measures the output data positioned close to the beam's free extremity because the authors are only interested in the region of the structure's first mode shape. The input signal analyzed is the voltage signal applied in the electrodynamic transducer. As a single-input/single-output (SISO) model is considered, this pair of signals is enough to identify and monitor the structural health. All the acquisition parameters, signals considered, and equipment used were the same in the experiments performed, considering the different structural conditions.

The damage imposed on the structure aims to simulate a breathing crack present in the system. In this sense, four different beams were built to be used in the application of the damage detection methodology:

 <li> Training beam: beam constructed with four intact Lexan beams and used in the training phase of the algorithm </li>
 <li> Test beam: beam constructed with four intact Lexan beams and used in the test phase of the algorithm </li>
 <li> Damage I: beam constructed with three intact and one cut beam (see Figure 4(a) and (b)) </li>
 <li> Damage II: beam constructed with two intact and two cut beams (see Figure 4(a) and (b)) </li><br>
 
The cut in the beams is positioned close to the excitation point. This spot was chosen to obtain the required nonlinear behavior to test the performance of the algorithm. The damage condition might be judged severely, but the position and excitation combined were defined to generate a difficult condition to detect, mainly in the condition damage I. Details about the structural conditions are considered below.

<img src="damage.jpg " width="80%">

__________________________________________________________________________________________________
# Authors

  <li>Luis Villani (UNESP) </li>
  <li>Michael Douglas Todd (UCSD)</li>
  <li>Samuel da Silva (UNESP) </li>
  <li>Americo Cunha Jr (UERJ) </li>
  
__________________________________________________________________________________________________
# How to cite

The data are still available for non-commercial research under the following terms: (i) the Structural Health Monitoring (SHM) laboratory in the Department of Structural Engineering at the University of California San Diego and the SHM Lab at UNESP/Ilha Solteira should be acknowledged as the source of the data; (ii) in publications, relevant publications by members of the SHM Lab at UCSD and SHM Lab at UNESP/Ilha Solteira should be cited; (iii) this benchmark should be cited as ADELE.

This dataset was used in these publications:

<li>Villani LG, da Silva S, Cunha A, Todd MD. On the detection of a nonlinear damage in an uncertain nonlinear beam using stochastic Volterra series. Structural Health Monitoring. 2020;19(4):1137-1150. https://doi.org/10.1177/1475921719876086</li><br>

<li>Villani LG. Robust damage detection in uncertain nonlinear systems. PhD Thesis in Mechanical Engineering; São Paulo State University, Ilha Solteira/SP, Brazil, Dec. 2019, http://hdl.handle.net/11449/191200 </li><br>

If you are using a LaTeX Editor, you can cite the papers above using these BibTeX citations:

```
@article{doi:10.1177/1475921719876086,
author = {Luis GG Villani and Samuel da Silva and Americo Cunha and Michael D Todd},
title ={On the detection of a nonlinear damage in an uncertain nonlinear beam using stochastic Volterra series},
journal = {Structural Health Monitoring},
volume = {19},
number = {4},
pages = {1137-1150},
year = {2020},
doi = {10.1177/1475921719876086},
URL = { https://doi.org/10.1177/1475921719876086},
eprint = { https://doi.org/10.1177/1475921719876086},
}

@phdthesis{Villani2019,
  title={Application of Volterra series in nonlinear mechanical system identification and in structural health monitoring problems},
  author={Luis GG Villani},
  year={2019},
    school ={Universidade Estadual Paulista (UNESP)}
      note= {Ph.D. in Mechanical Engineering}
  url = " http://hdl.handle.net/11449/191200",
}

```
__________________________________________________________________________________________________
# License

<img src="licenca.png" width="10%">
Creative Commons Attribution-NonCommercial-ShareAlike (CC-BY-NC-SA):

A creative commons license that bans commercial use and requires you to release any modified works under this license.

__________________________________________________________________________________________________
# Funding

São Paulo Research Foundation (<a href="http://www.fapesp.br">FAPESP</a>), grant numbers 15/25676-2 and 17/24977-4, Brazilian National Council for Scientific and Technological Development (<a href="http://www.cnpq.br/">CNPq</a>), grant number 306526/2019-0, and Brazilian Coordination for the Improvement of Higher Education Personnel (<a href="https://www.gov.br">CAPES</a>)-Finance Code 001 funded this experimental setup.

<img src="sponsors.jpg " width="50%">
