# YSO.and.RNe
Work started as Project C of ESO Summer Research Programme 2023.

## Repository content

### [YSO](./YSO)
contains the [catalogues](./YSO/catalogues) of Young Stellar Objects in the Corona Australis star forming region and the [jupyter notebook](./YSO/JoinCatalogues.ipynb)
used to join the literature catalogues.

Original data is from:

* Esplin and Luhman, 2023 ([doi:10.3847/1538-3881/ac3e64](https://ui.adsabs.harvard.edu/link_gateway/2022AJ....163...64E/doi:10.3847/1538-3881/ac3e64)) 
* Marton et al., 2019 ([doi:10.1093/mnras/stz1301](https://ui.adsabs.harvard.edu/link_gateway/2019MNRAS.487.2522M/doi:10.1093/mnras/stz1301)) 
* Dunham et al., 2015 ([doi:10.1088/0067-0049/220/1/11](https://ui.adsabs.harvard.edu/link_gateway/2015ApJS..220...11D/doi:10.1088/0067-0049/220/1/11)) 
* Manara et al., 2023 ([doi:10.48550/arXiv.2203.09930](https://ui.adsabs.harvard.edu/link_gateway/2023ASPC..534..539M/doi:10.48550/arXiv.2203.09930))

### [RNe_in_CrA](./RNe_in_CrA)
contains the catalogue of Reflection Nebulae (RNe) in the Corona Australis (CrA) star forming region, the script used to analyze the data and the results obtained analyzing the catalogue.

Content:
* [`getdata`](./RNe_in_CrA/getdata) : script used to crop the data around each yso and open it with ds9.
* [`Results.ipynb`](./RNe_in_CrA/Results.ipynb) : jupyter notebook with the analysis on the final catalogue.
* [`catalogue.csv`](./RNe_in_CrA/catalogue.csv) : final catalogue of RNe in CrA in csv format.
* [`catalogue.ods`](./RNe_in_CrA/catalogue.ods) : final catalogue of RNe in CrA in ods format.
