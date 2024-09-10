Welcome to the repository regarding the job application of Milan Slee for the rol of Economist-Statisticians (ESCB/IO) - Monetary and Economic Statistics at the ECB.
The information in this repository is intended solely for the addressee. If you receive access to this repository as a non-addressee, please inform me immediately at my emailadress (Milan2_slee@hotmail.com). 
Use of the information by unauthorized persons, disclosure, or reproduction is prohibited and may lead to liability.

The repository contains part of the compilation of the Dutch macroeconomic statistics for the Other financial intermediaries, except insurance corporations and pension funds (ESA Sector S.125) and Financial auxiliaries (ESA Sector S.126).
The compilation is mainly build in Python in the environnement Dataiku.
The reporting framework requires financial institutions to upload their balance sheets per quarter. The balance at the beginning of the period should be equal to the balance at the end of the previous reporting period.
It is nonetheless possible to report a difference between the balance at the end of the previous reporting period and the balance at the currenct reporting period.

The first two steps concern the cleaning of the dataset including the addition of rows with empty values in case a certain datapoint does not exist in the dataset.
This allows for the calculation of the differences between the lagged balance at the end of the period and the balance at the beginning of the period in step 3.
Finally, the dataset is transformed in order to create a macrocorrection recipe in step 4. The recipe is manually uploaded to the database to correct for the errors in the macroeconomic statistics.

The extracting of the data from the database to Dataiku, the other macroeconomic corrections, as well as the uploading of the recipes to the database,  are not included in this repository. 
