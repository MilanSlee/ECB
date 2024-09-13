Welcome to the repository regarding the job application of Milan Slee for the rol of Economist-Statisticians (ESCB/IO) - Monetary and Economic Statistics at the ECB.

The information in this repository is intended solely for the addressee. If you receive access to this repository as a non-addressee, please inform me immediately at my emailadress (Milan2_slee@hotmail.com).

The repository contains part of the compilation of the Dutch macroeconomic statistics for the Other financial intermediaries, except insurance corporations and pension funds (ESA Sector S.125) and Financial auxiliaries (ESA Sector S.126). The compilation is primarily build in Python in the Dataiku environnment. The reporting framework requires financial institutions to upload their balance sheets quarterly. The balance at the beginning of the period should match the balance at the end of the previous reporting period. However, it is possible to report a discrepancy between the balance at the end of the previous reporting period and the balance at the currenct reporting period.

The first two steps involve cleaning the dataset, including adding rows with empty values if a certain data point does not exist in the dataset. This allows for the calculation of differences between the lagged balance at the end of the period and the balance at the beginning of the period in step 3. Finally, the dataset is transformed to create a macrocorrection recipe in step 4. The recipe is manually uploaded to the database to correct errors in the macroeconomic statistics.

The extraction of data from the database to Dataiku, other macroeconomic corrections, and the uploading of recipes to the database are not included in this repository.
