# CH504
Material for CH504 Lab mid sem exam

# Instructions

## Transition States
The initial guess geometries for both endo and exo transition states are provided in the [Final transition states](https://github.com/Swastik166/CH504/tree/main/Final_transition_states) folder. Please copy and paste the coordinates to your respective .com file and optimize them.

## Using Colab to create initial guess geometries
For certain geometries, such as those of the endo and exo products, generating an accurate initial guess in MOLDEN may prove challenging. We will use RDKit, a Python-based open-source cheminformatics toolkit, to generate a high-quality 3D geometry in these cases. The process involves converting the SMILES representation of the molecule into a 3D structure and then optimizing it using the MMFF force field to obtain suitable coordinates.

To acquire the SMILES string for a molecule, use the [SMILES generator](https://www.cheminfo.org/flavor/malaria/Utilities/SMILES_generator___checker/index.html), an online chemical editor that converts molecular structures into SMILES notation.
Steps:
- Open the Colab notebook available at [link](https://colab.research.google.com/drive/1z9A7lthvTLbLiKtJ6u9npuoWNSq0dAjQ?usp=sharing)
- Navigate to **File** and **Save a copy in Drive**
- Access the [SMILES generator](https://www.cheminfo.org/flavor/malaria/Utilities/SMILES_generator___checker/index.html) and draw the required molecules to get its SMILES string
- Copy and paste the obtained SMILES string into the fourth code block of the provided notebook, assigning it to the variable **SMILES_STR**
- Execute all code blocks to generate the coordinates.
- Transfer the generated coordinates into your .com file and perform molecular optimization.
- Repeat the procedure for the remaining products as required.

## Drawing Molecules
![image](https://github.com/user-attachments/assets/1374334c-7888-4eba-95a4-f5ce431f4744)
