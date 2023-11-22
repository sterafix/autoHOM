# autoHOM
Autmomates the process of recording HOM dips with a Newport CONEX linear stage, a qutools quTAU and an Arroyo Instruments TECSource 5305. Developed at the Quantum Photonics group of the LLT at RWTH Aachen University.


Problem this script solves: When recording HOM dips, the following tasks should be automated:
- Moving the linear stage
- Recording the coincidence rate at each position
- Maybe repeating these cycles for different temperatures automatically.

This is what this script does!

This script was developed for these devices:
- [Newport CONEX-AG-LS25-27P piezo motor linear stage](https://www.newport.com/p/CONEX-AG-LS25-27P), based on the python example provided by the Newport support (just shoot them an email if you want to obtain this python example). (Basically, the ASCII commands from the manual are sent directly to the COM port of the linear stage via pyserial. See the download section of the Newport website for the manual.)
- [qutools quTAU](https://qutools.com/qutau/), based on the python examples provided in the downloads section of the qutools website
- [Arroyo Instruments TECSource 5305](https://www.arroyoinstruments.com/product/5305-tecsource-5a-12v/), based on the GitHub repo https://github.com/ArroyoInst/arroyo_tec

This script (and this whole repo) are in an early stage and will be updated and improved soon.
In addition, scripts with which the measured HOM dips can be further analyzed (most importantly, fitting a Gaussian function to them and calculating their visibility) may be added in the future.

Comments (e.g., via email or in the form of issues) and pull requests for improvements are always welcome!
