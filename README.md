# Nunam-Task
These 2 data files are from the same data source and represents same data, due to space restrictions of the file type it is divided into 2 separate files named *'data.xlsx'* and *'data_1.xlsx'* and while saving the data, it is also saved not accordingly, follow the index column named *'Record Index'* to see the parity. 

## Tasks

1. Create 3 separate *'*.csv'* files named `'detail.csv'`, `'detailVol.csv'` and `'detailTemp.csv'`.
	1. Combine all the data in sheets named like "Detail_67_" only, among the two data files provided, and save into `'detail.csv'`
	2. Combine all the data in sheets named like "DetailVol_67_" only, among the two data files provided, and save into `'detailVol.csv'`
	3. Combine all the data in sheets named like "DetailTemp_67_" only, among the two data files provided, and save into `'detailTemp.csv'`
Provide attention to the column `'Record Index'` which provided index values to avoid mismatching the rows while combining multiple files.

2. Apply down-sampling method to reduce the sampling rate  to `1 sample/minute`. Apply the same to `'detail.csv'`, `'detailVol.csv'` and `'detailTemp.csv'` and creating 3 files named  `'detailDownsampled.csv'`, `'detailVolDownsampled.csv'` and `'detailTempDownsampled.csv'`
3. Apply `low pass filter` technique for noise removal on the data set for  `'detailVolDownsampled.csv'` and show  the distribution of the dataset through visualization, also provide explanation of the same.

4. Run profile for all the functions; use `cProfile` for Python for profiling of individual functions.

5. Run unit test on each function,i.e., write test cases for each function. Use `unittest` for the same.
6. Try to maintain Coding Style Guide **PEP-8**, and use `pylint` or `flake8` to check the code for PEP-8 violations.
7. 
