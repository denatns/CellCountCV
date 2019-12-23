# CellCountCV
This repository contains the code and examples accompaining our preprint https://doi.org/10.1101/867218

- **Working_with_CellCounter.ipynb** &mdash; this notebook contains the examples of pretrained FCNN model usage in Python and through JSON-RPC calls to CellCountCV.  
- **Exp1_analysis.ipynb** &mdash; a notebook with statistical analysis of results obtained in experiment #1  
- **Exp2_analysis.ipynb** &mdash; a notebook with statistical analysis of results obtained in experiment #2  
- **SupplementaryTables1_bioRxiv.xlsx** &mdash; the data obtained in experiment #1  
- **SupplementaryTables2_bioRxiv.xlsx** &mdash; the data obtained in experiment #2
- **SupplementaryTables1_bioRxiv.xlsx** &mdash; the example image  
- **model.h5** &mdash; the pretrained model  

The requirements are the following:

- Python >= 3.6
- pandas
- scipy
- tensorflow (tensorflow-gpu)
- keras (keras-gpu)
- opencv
- matplotlib
- seaborn
- statsmodels -- version 0.10.1 -- the only version tested
