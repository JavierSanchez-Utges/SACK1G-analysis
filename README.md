# Mutations in fragment site of SACK1G abolish interaction with CK1α

This repository includes the code and results of the computational analysis of our pre-print **_"Mutations within the predicted fragment-binding region of FAM83G/SACK1G abolish its interaction with the Ser/Thr kinase CK1α"_**, which can be found [here]().

Within the [`AFDB_FAM83B_model`](./AFDB_FAM83B_model) and [`AFDB_FAM83G_model`](./AFDB_FAM83G_model) directories, the AlphaFold DB models for human [SACK1B](https://alphafold.ebi.ac.uk/entry/Q5T0W9) ([Q5T0W9](https://www.uniprot.org/uniprotkb/Q5T0W9/entry)) and [SACK1G](https://alphafold.ebi.ac.uk/entry/A6ND36) ([A6ND36](https://www.uniprot.org/uniprotkb/A6ND36/entry)) can be found, respectively.

The [`FAM83B_FRAGSYS`](./FAM83B_FRAGSYS) directory includes the necessary data from the FRAGSYS [[1](https://doi.org/10.1038/s42003-024-05970-8)] analysis of FAM83B/SACK1B, which was employed to hightlight the most likely sites to affect SACK1B function as well as the individual residues within them.

The [`FAM83G_SS_prediction_JPRED`](./FAM83G_SS_prediction_JPRED) directory include [JPred](https://www.compbio.dundee.ac.uk/jpred/) [[2](https://doi.org/10.1093/nar/gkv332)] secondary structure predictions for FAM83G/SACK1G employed to complement secondary structure assignments from the AlphaFold [[3](https://doi.org/10.1038/s41586-021-03819-2)]three-dimensional structure models.

The [`FAM83_dimers`](./FAM83_dimers) directory includes the 3D structure models obtained in this work using the Colabfold v1.5.2 [[4](https://doi.org/10.1038/s41592-022-01488-1)] implementation of AlphaFold Multimer v3 [[5](https://doi.org/10.1038/s41586-024-07487-w)].

Finally, the [`notebooks`](./notebooks) directory includes the two Jupyter notebooks employed to carry out the computational analysis described in our manuscript.

## Dependencies

- [Colabfold](https://github.com/sokrypton/ColabFold)
- [Matplotlib](https://matplotlib.org/) 
- [Numpy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/) 
- [Seaborn](https://seaborn.pydata.org/) 

## References

1. **Utgés, J.S.**, MacGowan, S.A., Ives, C.M. et al. Classification of likely functional class for ligand binding sites identified from fragment screening. _Commun. Biol._ **7**, 320 (2024). [https://doi.org/10.1038/s42003-024-05970-8](https://doi.org/10.1038/s42003-024-05970-8)
2. Alexey Drozdetskiy, Christian Cole, James Procter, Geoffrey J. Barton, JPred4: a protein secondary structure prediction server, _Nucleic Acids Res._, Volume 43, Issue W1, 1 July 2015, Pages W389–W394, [https://doi.org/10.1093/nar/gkv332](https://doi.org/10.1093/nar/gkv332)
4. Jumper, J., Evans, R., Pritzel, A. et al. Highly accurate protein structure prediction with AlphaFold. _Nature_ **596**, 583–589 (2021). [https://doi.org/10.1038/s41586-021-03819-2](https://doi.org/10.1038/s41586-021-03819-2)
5. Mirdita, M., Schütze, K., Moriwaki, Y. et al. ColabFold: making protein folding accessible to all. _Nat. Methods_ **19**, 679–682 (2022). [https://doi.org/10.1038/s41592-022-01488-1](https://doi.org/10.1038/s41592-022-01488-1)
6. Abramson, J., Adler, J., Dunger, J. et al. Accurate structure prediction of biomolecular interactions with AlphaFold 3. _Nature_ **630**, 493–500 (2024). [https://doi.org/10.1038/s41586-024-07487-w](https://doi.org/10.1038/s41586-024-07487-w)
