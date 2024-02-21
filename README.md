# SimNeuroStim Analysis
Analysis of simulated optogenetic neural stimulation with NEURON simulator.

### Requirements
This repository should be embedded inside two other repositories. Namely [morph_impact_on_opt_stim](https://github.com/dberling/morph_impact_on_opt_stim) and [simneurostim](https://github.com/dberling/simneurostim).
In this way:

**morph_impact_on_opt_stim**
├── scripts
├── workflows
├── ... other stuff ...
└── **simneurostim**
    ├── base-neurostim/neurostim
    ├── model
    ├── ... other stuff ...
    └── **simneurostim-analysis**


You also have to follow every instruction in both repositories.
