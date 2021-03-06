# PN2S

Supplmentary data for the maniscript "Essential Step toward Mining Big Polymer Data: PolyName2Structure, Mapping Polymer Names to Structures".
Please cite our article if you use the dataset:
```
Lin, C., Wang, P. H., Hsiao, Y., Chan, Y. T., Engler, A. C., Pitera, J. W., ... & Tseng, Y. J. (2020). Essential Step Toward Mining Big Polymer Data: PolyName2Structure, Mapping Polymer Names to Structures. ACS Applied Polymer Materials, 2(8), 3107-3113.
```

## Data Description

- `Curated Cases/` contains the manual curated cases
  - ROP1Fiexd_final.tsv_test.txt: ring opening with 1 monomer
  - CON1Fiexd_final.tsv_test.txt: condensation with 1 monomer
  - CON2Fiexd_final.tsv_test.txt: condensation with 1 monomer
  - ADD1Fiexd_final.tsv_test.txt: addition with 1 monomer

- `Machine_Learning/Final_Training_Set/` contains the full traning set used in the study
  - `All_good_train.txt`: all the polymers in the training set
  - `Addition/RingOpening/Condensation1/2_good_train.txt`: the polymers with the reaction type of addition/ring opening/condensation with 1 or 2 monomers

- `Machine_Learning/Test_Set/` contains the full testing set used in the study

## Data Format of Training Set

Eevery datapoint in training set provided here is composed of serveral units. Every unit consists of four lines.

- First line: ID in PoLyInfo database
- Second line: Name of the polymer
- Third line: SMILES of the polymer
- Fourth line: SMILES of the monomer

## Other Useful Links

- [OPSIN](https://opsin.ch.cam.ac.uk/)
