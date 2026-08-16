<img src="https://github.com/MauricioCafiero/MauricioCafiero.github.io/blob/main/images/comp_chem_2_small.jpg" height="200" align="top" style="height:240px">

# Featured Projects

### [UMADock](https://github.com/MauricioCafiero/UMADock)
Docking molecules into protein binding sites scored by a pluggable MLIP energy function (Meta's UMA by default, MACE-OMOL-0 and AIMNet2 also supported). Automatically preps the binding site from any PDB, then combines desolvation and ligand-strain corrections into an electronic binding energy — runnable from an AI agent.

### [dock_assist](https://github.com/MauricioCafiero/dock_assist)
A conversational CLI agent (powered by Ollama) that turns a plain-English request like *"dock dopamine into SULT1A3"* into a full docking run — PDB lookup, blind binding-site detection, and AutoDock Vina docking — with no prior knowledge of the binding site required.

### [CheMLAgent](https://github.com/MauricioCafiero/CheMLAgent)
An agentic system for building and training chemistry ML models (QSAR / bioactivity / property prediction). An Ollama-driven chat model chains together real, reusable tools — ChEMBL data prep, featurization, RF/LightGBM/MPNN/Chemprop training, evaluation — to satisfy a plain-language modeling request.

### [MoDrAg_CLI](https://github.com/MauricioCafiero/MoDrAg_CLI)
A full-featured command-line version of the MOdular DRug design AGent, with rich terminal output. Combines molecular and protein tools, IC50 prediction, AutoDock Vina docking, and a fine-tunable SMILES-GPT generator, with an easy node-integration system for adding new tools.

### [admet_assist](https://github.com/MauricioCafiero/admet_assist)
Local, no-network ADMET prediction from SMILES using two independent Chemprop v2 MPNN model families — ADMET-AI (52 endpoints + DrugBank percentiles) and Admetica (22 per-endpoint models with applicability-domain scores) — each shipped as both a batch CLI and an LLM-callable tool.

### [fold](https://github.com/MauricioCafiero/fold)
Protein structure prediction and protein/ligand cofolding with no local GPU required. OpenFold3, RosettaFold3, and ESMFold run on Modal GPUs on demand, while ESM2 embeddings run locally on CPU.

### [MD_openmm](https://github.com/MauricioCafiero/MD_openmm)
An OpenMM molecular-dynamics pipeline for solvated protein/ligand complexes and single small molecules, built on the AMBER force-field family. Prep, build, run, and analyze are separate `omd` subcommands so intermediates stay inspectable.

---

# All Repositories

## Drug Design
- [UMADock](https://github.com/MauricioCafiero/UMADock) — MLIP-scored blind docking
- [dock_assist](https://github.com/MauricioCafiero/dock_assist) — conversational AI-assisted blind docking
- [MoDrAg](https://github.com/MauricioCafiero/MoDrAg) — modular drug-design AI agent
- [MoDrAg_CLI](https://github.com/MauricioCafiero/MoDrAg_CLI) — command-line MoDrAg
- [admet_assist](https://github.com/MauricioCafiero/admet_assist) — local ADMET prediction
- [fold](https://github.com/MauricioCafiero/fold) — protein structure prediction and cofolding
- [MD_openmm](https://github.com/MauricioCafiero/MD_openmm) — OpenMM molecular dynamics pipeline
- [Boltz](https://github.com/MauricioCafiero/Boltz) — scripts for running Boltz on the API
- [FAO_MOLPROP_CLI](https://github.com/MauricioCafiero/FAO_MOLPROP_CLI) — adversarial molecule optimization from the CLI
- [MolecularPropertyOptimization](https://github.com/MauricioCafiero/MolecularPropertyOptimization) — agentic molecular property optimization
- [sim_assist](https://github.com/MauricioCafiero/sim_assist) — molecular similarity measures
- [GenMask](https://github.com/MauricioCafiero/GenMask) — hit expansion via token unmasking
- [SMILES_GPT](https://github.com/MauricioCafiero/SMILES_GPT) — GPT for SMILES generation
- [SMILES_VAE](https://github.com/MauricioCafiero/SMILES_VAE) — variational SMILES autoencoder

## Machine Learning
- [CheMLAgent](https://github.com/MauricioCafiero/CheMLAgent) — agent for cleaning CSVs, featurizing molecules, training ML models
- [admet_assist](https://github.com/MauricioCafiero/admet_assist) — Chemprop MPNN ADMET models
- [MACE_UseAndTrain](https://github.com/MauricioCafiero/MACE_UseAndTrain) — use/fine-tune MACE for small molecules
- [Simple_Molecular_Graph_models](https://github.com/MauricioCafiero/Simple_Molecular_Graph_models) — MPNN and classical ML models for molecular graphs
- [smiles_embed](https://github.com/MauricioCafiero/smiles_embed) — SMILES embedding model training
- [SMILES_GPT](https://github.com/MauricioCafiero/SMILES_GPT) — GPT for SMILES generation
- [SMILES_VAE](https://github.com/MauricioCafiero/SMILES_VAE) — variational SMILES autoencoder
- [serve_azo_model](https://github.com/MauricioCafiero/serve_azo_model) — serves a trained MLP for azo dye lambda max
- [InflectionLM](https://github.com/MauricioCafiero/InflectionLM) — visualizing LLM output inflection points
- [GenMask](https://github.com/MauricioCafiero/GenMask) — hit expansion via token unmasking
- [FAO_MOLPROP_CLI](https://github.com/MauricioCafiero/FAO_MOLPROP_CLI) — adversarial molecule optimization
- [MolecularPropertyOptimization](https://github.com/MauricioCafiero/MolecularPropertyOptimization) — agentic molecular property optimization

## Quantum Chemistry
- [Gaussian16-Scripts-and-Functions](https://github.com/MauricioCafiero/Gaussian16-Scripts-and-Functions) — bash functions and scripts for Gaussian 16
- [Many-body-input-files](https://github.com/MauricioCafiero/Many-body-input-files) — Gaussian input files for 2- and 3-body interaction energies
- [NBO_CorrelatedGaussians](https://github.com/MauricioCafiero/NBO_CorrelatedGaussians) — non-Born-Oppenheimer explicitly correlated spherical floating gaussians
- [ExplicitlyCorrelatedGaussians_StochasticGrowth](https://github.com/MauricioCafiero/ExplicitlyCorrelatedGaussians_StochasticGrowth) — stochastic optimization of explicitly correlated gaussian wavefunctions
- [MACE_UseAndTrain](https://github.com/MauricioCafiero/MACE_UseAndTrain) — use/fine-tune MACE from GFN2 data

## Educational Resources
- [CafChem](https://github.com/MauricioCafiero/CafChem) — libraries/modules for the CafChem computational chemistry / drug design tools
- [CafChemTeach](https://github.com/MauricioCafiero/CafChemTeach) — notebooks for the Python, Machine Learning, and AI for Chemistry module
- [CafChemQuantum](https://github.com/MauricioCafiero/CafChemQuantum) — quantum computing practice and teaching code in Q#, Qiskit, and Cirq
- [Java_teaching_examples](https://github.com/MauricioCafiero/Java_teaching_examples) — linear regression with a Java GUI
