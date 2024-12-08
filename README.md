## Hi there 👋

<!--
**ben120-web/ben120-web** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

### Repository Structure

```mermaid
graph TD;
    MScProject["MSc-Project"] -->|Deep learning models for removing electrode motion noise from ECG signals.| DSP["Digital Signal Processing"];
    MScProject --> ISC["Intelligent Systems and Control"];
    MScProject --> CET["Control and Estimation Theory"];
    DSP --> Quadcopter["Quadcopter Simulation and Analysis"];
    ISC --> MPC["Model Predictive Control for Aircraft Pitch"];
    CET --> Microelectronics["Microelectronic Devices and Technology"];
    Quadcopter --> Backend["Back-End Development Course"];
    MPC --> Microelectronics;
    Backend --> MScProject;
