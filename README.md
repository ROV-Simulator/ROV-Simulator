# ROV-Simulator
ROV Simulator is a modular simulator fully implemented in MATLAB™ and Simulink™


## Journal Paper
[An Open-Source Benchmark Simulator: Control of a BlueROV2 Underwater Robot](https://www.mdpi.com/2077-1312/10/12/1898)

## Cite
If you use the simulator in your research, please cite the following paper:

**Chicago/Turabian Style**

von Benzon, Malte, Fredrik Fogh Sørensen, Esben Uth, Jerome Jouffroy, Jesper Liniger, and Simon Pedersen. 2022. "An Open-Source Benchmark Simulator: Control of a BlueROV2 Underwater Robot" *Journal of Marine Science and Engineering* 10, no. 12: 1898. https://doi.org/10.3390/jmse10121898

**BibTeX**
```BibTex
@Article{jmse10121898,
  AUTHOR = {von Benzon, Malte and Sørensen, Fredrik Fogh and Uth, Esben and Jouffroy, Jerome and Liniger, Jesper and Pedersen, Simon},
  TITLE = {An Open-Source Benchmark Simulator: Control of a BlueROV2 Underwater Robot},
  JOURNAL = {Journal of Marine Science and Engineering},
  VOLUME = {10},
  YEAR = {2022},
  NUMBER = {12},
  ARTICLE-NUMBER = {1898},
  URL = {https://www.mdpi.com/2077-1312/10/12/1898},
  ISSN = {2077-1312},
  ABSTRACT = {This paper presents a simulation model environment for the popular and low-cost remotely operated vehicle (ROV) BlueROV2 implemented in Simulink&trade; which has been designed and experimentally validated for benchmark control algorithms for underwater vehicles. The BlueROV2 model is based on Fossen&rsquo;s equations and includes a kinematic model of the vehicle, the hydrodynamics of vehicle and water interaction, a dynamic model of the thrusters, and, lastly, the gravitational/buoyant forces. The hydrodynamic parameters and thruster model have been validated in a test facility. The benchmark model also includes the ocean current, modeled as constant velocity. The tether connecting the ROV to the top-site facility has been modeled using the lumped mass method and is implemented as a force input to the ROV model. At last, to show the usefulness of the benchmark model, a case study is presented where a BlueROV2 is deployed to inspect an offshore monopile structure. The case study uses a sliding mode controller designed for the BlueROV2. The controller fulfills the design criteria defined for the case study by following the provided trajectory with a low error. It is concluded that the simulator establishes a benchmark for future control schemes for position control and trajectory tracking under the influence of environmental disturbances.},
  DOI = {10.3390/jmse10121898}
}
```
