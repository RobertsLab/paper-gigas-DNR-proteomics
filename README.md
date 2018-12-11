# paper-gigas-DNR-proteomics
Supporting information for paper detailing proteomic variation in Pacific oysters (Crassostrea gigas) between different outplant locations

### Additional methods informations:

**Table 1**. Solutions and buffers for mass spectrometry sample preparation, listen in order of use.

|                        **Solution**                        |          **Step**          |                                 **Use**                                 |
|:----------------------------------------------------------:|:--------------------------:|:-----------------------------------------------------------------------:|
|                  50 mM NH4HCO3 in 6M Urea                  |        Tissue Lysis        |                               Lysis buffer                              |
|                        50 mM NH4HCO3                       |   Protein Quantification   |                              Urea dilution                              |
|                 Bovine serum albumin (BSA)                 |   Protein Quantification   |                      Protein concentration standard                     |
|                      1.5 M Tris pH 8.8                     |      Protein Digestion     |                              Neutralize pH                              |
|         200 mM Tris(2-carboxyethyl)phosphine (TCEP)        |      Protein Digestion     | Reduce disufide crosslinks of cystines in proteins to cysteine residues |
|                    200 mM Iodoacetamide                    |      Protein Digestion     |        Maximize digestion enzyme access to protein cleavage sites       |
|                            (IAA)                           |                            |                                                                         |
|                 200 mM Dithiothreitol (DTT)                |      Protein Digestion     | Reduce disufide crosslinks of cystines in proteins to cysteine residues |
|                     Lysyl Endopeptidase                    |      Protein Digestion     |                     Catalyzes cleavage at Lys sites                     |
|                        25 mM NH4HCO3                       |      Protein Digestion     |                              Urea dilution                              |
|                     HPLC grade methanol                    |      Protein Digestion     |                              Urea dilution                              |
|                           Trypsin                          |      Protein Digestion     |                             Digestion enzyme                            |
|  Solvent A (5% Acetonitrile and 0.1% Trifluoroacetic Acid) |      Peptide Isolation     |                  Peptide reconstitution, column washing                 |
|                       10% Formic Acid                      |      Peptide Isolation     |                               pH modifier                               |
| Solvent B (60% Acetonitrile and 0.1% Trifluoroacetic Acid) |      Peptide Isolation     |                              Column washing                             |
|            3% Acetonitrile and 0.1% Formic Acid            |      Peptide Isolation     |                          Peptide reconstitution                         |
| 0.5 pmol/µL stock Peptide Retention Calibration Mix (PRTC) | Internal Standard Addition |                      Reference for sample analysis                      |
|                    PRTC and BSA solution                   | Internal Standard Addition |                    Mass spectrometry quality control                    |

**Table 2**. Methods used for Data-Independent Acquisition. Peptides were analyzed on an Orbitrap Fusion Lumos mass spectrometer (Thermo Scientific) and analyzed in MS1 over the m/z range of 450-950 with 12 m/z wide windows with 5 m/z overlaps.

|     ﻿**Method Parameter**    |  **MS1** |  **MS2** |
|:---------------------------:|:--------:|:--------:|
|     Orbitrap Resolution     |   60000  |   15000  |
|    Isolation Window (m/z)   |    N/A   |    10    |
|          Loop Count         |    N/A   |    20    |
|       Scan Range (m/z)      | 400-1000 | 350-2000 |
| Maximum Injection Time (ms) |    50    |    17    |
|          AGC Target         |  400000  |   50000  |
|        Cycle Time (s)       |     3    |    N/A   |
|    Accepted Charge State    |    N/A   |     2    |
|      Dynamic Exclusion      |   None   |   None   |

**Table 3**. Dilution ratios and sample volumes. The dilution series was used to verify the specificity of target peptides.

| ﻿**Dilution Ratio (oyster:geoduck)** | **µg to Inject** | **µg oyster** | **PRTC (µL)** | **ACN (µL)** | **Total (µL)** |
|:-----------------------------------:|:----------------:|:-------------:|:-------------:|:------------:|:--------------:|
|                10:01                |         1        |      0.9      |     1.875     |       6      |       15       |
|                7.5:1                |         1        |      0.87     |     1.875     |     6.125    |       15       |
|                 5:01                |         1        |      0.8      |     1.875     |     6.375    |       15       |
|                2.5:1                |         1        |      0.6      |     1.875     |     7.125    |       15       |
|               01:02.5               |         1        |      0.4      |     1.875     |     7.875    |       15       |
|                 1:05                |         1        |      0.2      |     1.875     |     8.625    |       15       |
|               01:07.5               |         1        |      0.13     |     1.875     |     8.875    |       15       |
|                 1:10                |         1        |      0.1      |      3.75     |       3      |       15       |