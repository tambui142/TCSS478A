# TCSS478A
## Synapse Encode Imputation Challenge

The goal of this challenge is to build a comprehensive parts list of functional elements in the human genome, including elements that act at the protein and RNA levels and regulatory elements that control cells and circumstances in which a gene is active. 

For the first step, that’s data processing. Base on the information in the table, the team chose out the cells and assays we want to work with and loading the bigwig file through anaconda navigator with Python language. 

**Prerequisites:**

- Anaconda navigator: https://www.anaconda.com/distribution/

- Spyder exists in Anaconda navigator

- Jupyter Notebook: https://jupyter.org/

- Installing the IRkernel on Jupyter: https://irkernel.github.io/installation/

- BigWig data files: https://www.synapse.org/#!Synapse:syn17083203/wiki/

**Running:**

Open anaconda prompt and type in Jupyter Notebook to open Jupyter Notebook using Python3 kernel. 
For running
```
exec("C03M%d = pyBigWig.open(\"/Users/gurchetan/Desktop/BioData/training/C03M%d.bigwig\")" %(i, i))
exec("C04M%d = pyBigWig.open(\"/Users/gurchetan/Desktop/BioData/validation/C04M%d.bigwig\")" %(i, i))
exec("C09M%d = pyBigWig.open(\"/Users/gurchetan/Desktop/BioData/validation/C09M%d.bigwig\")" %(i, i))
exec("C%dM%d = pyBigWig.open(\"/Users/gurchetan/Desktop/BioData/validation/C%dM%d.bigwig\")" %(j, i, j, i))
exec("C%dM%d = pyBigWig.open(\"/Users/gurchetan/Desktop/BioData/training/C%dM%d.bigwig\")" %(j, i, j, i))
```
need
```
import pyBigWig
```

My part is building logic to read through BigWig data dynamiccally working with Gurchentan Singh to complete the data proccessing.

**Authors:**

- Tam Bui

**Contributors:**

- Gurchetan Singh
