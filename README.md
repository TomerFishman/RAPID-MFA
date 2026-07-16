# The RAPID-MFA project
__RAPID-MFA__: **R**eusable **A**lgorithms and **P**rocesses for **I**ntegrated **D**ynamic **M**aterial **F**low **A**nalysis

## What is RAPID-MFA?
A portfolio of dynamic MFA model variants, in Python codes with descriptions in Jupyter Notebooks.
It aims to provide **easily understandable** models of common usages of dynamic MFA that are **ready to work**.

The RAPID-MFA project has two objectives:
1. Simple, accessible, streamlined, flexible, and easily adaptable Dynamic MFA modeling.
2. Easy learning curve for self-study and for courses such as [the MFA course of the Industrial Ecology MSc program of Leiden University](https://studiegids.universiteitleiden.nl/modules/4413MFA10Y).

## Project principles

RAPID-MFA intends to emphasize clarity, simplicity, and being self-explanatory by sticking to certain principles:

1. __Traceability__: All models and examples share the same basic codebases of the RAPID-MFA basic flow-driven model and basic stock driven model. Each model's notebook describes its relations to other notebooks. 
2. __Clarity and readability__: Keeping code as close as possible to the dynamic MFA modelling equations. Lots of explanations, notes,  comments, and visualizations.
3. __Transparency over efficiency__: Simple inflows-stocks-outflows modeling. Minimal wrapping of code in _functions_, etc. that might become black boxes. No use of custom objects/classes or other black boxes. Users can always wrap the basic code in those themselves. 
4. __Explicit over implicit__: Step-by-step modeling. Thoughtful use of common Python packages including Pandas, Numpy, Scipy, and Seaborn for straightforward and simple general tasks, but not as shortcuts for fundamental dynamic MFA operations (unless done on purpose in specific notebooks to compare with the basic models).
5. __Modularity__: each model notebook does one thing only. Different code files and code blocks/cells should be easily swappable, combined, and daisy-chained by simple copying and pasting together of the code snippets.

## Usage notes
1. Find the RAPID-MFA notebook that covers what you want to do in the (Table of Contents)[https://github.com/TomerFishman/RAPID-MFA/blob/master/RAPID-MFA%20notebooks/README.md]
2. Read the notebook's introduction section. The notebooks are meant to be self-explanatory with lots of descriptions, equations, visualizations, and notes in Markdown. Note the relations with other notebooks and check them too.
3. Run the code one block at a time, reading the accompanying Markdown and inline comments.
4. Copy and paste relevant code snippets into your own work, modifying them as you wish.
5. Tell us what you think!

## Contributors and acknowledgements

Project lead: Tomer Fishman, CML Institute of Environmental Sciences, Leiden University. 

Developers and contributors (past and present, in no special order): 
- Alessia Linares-Capurro, Leiden University
- Pablo Ilgemann, Leiden University
- Nils Pauliks, Leiden University
- Catrin Böcher, Leiden University
- Takuma Watari, National Institute of Environmental Science
- Adrien Perello-y-bestard, Leiden University
- Janneke van Ooorschot, Leiden University
- Sebastiaan Deetman, Leiden University

Many thanks to Stefan Pauliuk (Freiburg University), Alessio Miatto (CSIRO), and the very dynamic cohorts of students of the MFA1 and MFA2 courses in Leiden University for many discussions and feedbacks.

Contact [Tomer Fishman](t.fishman@cml.leidenuniv.nl) for more information.

## Versioning, licence, and how to cite

This GitHub repository tracks changes and versions. 

Please check the [license](https://github.com/TomerFishman/RAPID-MFA/blob/master/LICENSE) before proceeding. You can - and should! - freely reuse and adapt the RAPID-MFA models and codes for noncommercial purposes __as long as you attribute this source__. 
