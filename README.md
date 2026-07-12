<img src="https://github.com/MauricioCafiero/MauricioCafiero.github.io/blob/main/images/comp_chem_2_small.jpg" height="200" align="top" style="height:240px">

# Latest additions!

## dock_assist - AI-assisted blind docking
A conversational CLI agent (powered by Ollama) that takes a plain-English request like *"dock dopamine into SULT1A3"* and autonomously runs the full workflow: PDB lookup, blind binding-site detection, and AutoDock Vina docking — no prior knowledge of the binding site required.
- Pure-Python buriedness grid scan for pocket detection — no external pocket tool needed
- Proximity fallback: auto-corrects off-target poses using co-crystallized ligand proximity
- Validated on DUD-E receptors (HMGCR, ADRB1, ADRB2, MAOB, DRD2) — true binding site is **#1 pocket** on all five
- See the [repo!](https://github.com/MauricioCafiero/dock_assist)

## MolecularPropertyOptimization (FAO-MOLPROP)
A fragment-based, AI-assisted framework for molecular property optimization combining tool-augmented LLMs with computational chemistry — no model fine-tuning required.
- 10 LLMs benchmarked (3 closed-weight, 7 open-weight) across zero-shot, one-shot, and adversarial design modes
- Adversarial framework: two LLMs debate and validate proposals for superior results
- Demonstrated for HMGCR docking (best: −9.90 kcal/mol) and HOMO-LUMO gap minimization (best: 1.39 eV)
- Tools: AutoDock Vina, PySCF DFT, Lipinski, SAS/NP scoring, PubChem queries
- See the [repo!](https://github.com/MauricioCafiero/MolecularPropertyOptimization)

## MoDrAg_CLI - Command-Line MoDrAg
A full-featured CLI version of the MOdular DRug design AGent with rich terminal output, IC50 prediction, and an easy node-integration system for adding new tools.
- Molecular tools: SMILES conversion, similarity search, 3D structure generation, pharmacophore analysis
- Protein tools: UniProt/PDB lookup, ChEMBL bioactives, AutoDock Vina docking, LightGBM IC50 prediction
- Setup script to create a `modrag` shell alias for use from anywhere
- See the [repo!](https://github.com/MauricioCafiero/MoDrAg_CLI)

## FAO_MOLPROP_CLI - Fragment-based Optimization on the command line
Adversarial molecule optimization from the command line: an Ollama main model designs molecules to bind a protein target while an OpenAI/Anthropic adversary critiques each proposal, with all steps written to a timestamped Markdown report.
- See the [repo!](https://github.com/MauricioCafiero/FAO_MOLPROP_CLI)

## Rotaxanes - SMILES → MD
Build a rotaxane (rod threaded through a wheel) from two SMILES strings, relax it with Meta's UMA ML potential, map the shuttle energy landscape, and run ab-initio-style MD with UMA forces.
- Chain-seeded relaxed shuttle scan maps every energy well along the rod, with Eyring rate estimates
- Validated on two systems: multi-well landscape on a long rod (28.6 Å) vs. clean two-well landscape on a short rod (16.8 Å)
- See the [repo!](https://github.com/MauricioCafiero/Rotaxanes)

## MoDrAg - the MOdular DRug design AGent
We have two new flavors of the MoDrAg drug design helper agent! Both are a ground-up revision of the original from November 2025. Tools can be added very easily, hence the *modular* in the title! 
- Semantic MoDrAg - A drug design agent with strong human-in-the-loop functionality. See the [main page!](https://github.com/MauricioCafiero/MoDrAg/tree/main)
- OpenAI MoDrAg - uses LangGraph to create a drug design agent driven by OpenAI's GPT5.2. See the [OpenAI agent page!](https://github.com/MauricioCafiero/MoDrAg/tree/main/OpenAIComboMoDrAg/code)
- HuggingFace demo for the [Semantic Agent](https://huggingface.co/spaces/cafierom/MoDrAg2)
- HuggingFace demo for the [OpenAI Agent](https://huggingface.co/spaces/cafierom/MoDrAg2-OpenAI)
- Use a notebook to run Semantic MoDrAg [on Colab!](https://github.com/MauricioCafiero/MoDrAg/blob/main/SemanticMoDrAg/MoDrAg2_CafChem.ipynb)

## Ollama chats:
### A simple command-line chatbot using Ollama including RAG functionality.
- Runs from a [short page of code!](https://github.com/MauricioCafiero/CafChemTeach/blob/main/ollama_chat_rag.py)
- Read in a PDF and chat with the document
- Create a custom model right in the chat.
- Requires Ollama to be installed on your machine. See [this page](https://github.com/MauricioCafiero/CafChemTeach/blob/main/using_ollama.md) to get started!
### Run large LLMs in the cloud (for free!)
- Requires an API key from Ollama
- Free allocations from Ollama
- see the [code!](https://github.com/MauricioCafiero/CafChemTeach/blob/main/ollama_cloud.py)

## MACE training
Simplified code for training and fine-tuning MACE machine-learned interatomic potential models
- [Repo](https://github.com/MauricioCafiero/MACE_training/tree/main) with code and notebook
  
## Quantum computing intro
Find background on the quantum mechanics of quantum computing as well as introductions to quantum computing with Q#, Cirq and Qiskit!
- See the repo [here!](https://github.com/MauricioCafiero/CafChemQuantum)

## Use the MLIP-based docking code, UMADock
- Dock molecules in a selection of 6 proteins using the UMA MLIP for all energy evaluations.
- Includes ligand desolvation and strain energy.
- See the repo [here!](https://github.com/MauricioCafiero/UMADock)
