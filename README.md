<img src="https://github.com/MauricioCafiero/MauricioCafiero.github.io/blob/main/images/comp_chem_2_small.jpg" height="200" align="top" style="height:240px">

# Latest additions!

## InflectionLM - Output and Token Visualization
A tool that visualizes "inflection points" in LLM generation by generating multiple independent output paths and highlighting low-confidence tokens — moments where the model's output could easily have diverged.
- Generates 3 independent responses per prompt using GEMMA 4 with Top-P/Top-K sampling for diversity
- Highlights tokens with probability < 0.6 in red, marking them as inflection points
- Interactive Gradio GUI with toggleable per-token probability scores and light/dark mode
- See the [repo!](https://github.com/MauricioCafiero/InflectionLM)
- Try the [HuggingFace demo!](https://huggingface.co/spaces/build-small-hackathon/InflectionLM)

## dock_assist - AI-assisted blind docking
A conversational CLI agent (powered by Ollama) that takes a plain-English request like *"dock dopamine into SULT1A3"* and autonomously runs the full workflow: PDB lookup, blind binding-site detection, and AutoDock Vina docking — no prior knowledge of the binding site required.
- Pure-Python buriedness grid scan for pocket detection — no external pocket tool needed
- Proximity fallback: auto-corrects off-target poses using co-crystallized ligand proximity
- Validated on DUD-E receptors (HMGCR, ADRB1, ADRB2, MAOB, DRD2) — true binding site is **#1 pocket** on all five
- See the [repo!](https://github.com/MauricioCafiero/dock_assist)

## FAO_MOLPROP_CLI - Fragment-based Optimization on the command line
Adversarial molecule optimization from the command line: an Ollama main model designs molecules to bind a protein target while an OpenAI/Anthropic adversary critiques each proposal, with all steps written to a timestamped Markdown report.
- See the [repo!](https://github.com/MauricioCafiero/FAO_MOLPROP_CLI)

## MoDrAg_CLI - Command-Line MoDrAg
A full-featured CLI version of the MOdular DRug design AGent with rich terminal output, IC50 prediction, and an easy node-integration system for adding new tools.
- Molecular tools: SMILES conversion, similarity search, 3D structure generation, pharmacophore analysis
- Protein tools: UniProt/PDB lookup, ChEMBL bioactives, AutoDock Vina docking, LightGBM IC50 prediction
- Setup script to create a `modrag` shell alias for use from anywhere
- See the [repo!](https://github.com/MauricioCafiero/MoDrAg_CLI)
  
## Quantum computing intro
Find background on the quantum mechanics of quantum computing as well as introductions to quantum computing with Q#, Cirq and Qiskit!
- See the repo [here!](https://github.com/MauricioCafiero/CafChemQuantum)

## Use the MLIP-based docking code, UMADock
- Dock molecules is a selction of 6 proteins using the UMA MLIP for all energy evaluations.
- Includes ligand desolvation and strain energy.
- See the repo [here!](https://github.com/MauricioCafiero/UMADock)
