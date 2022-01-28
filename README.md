# Undoubling-of-real-estate-values

## The main objective of this project is to detect duplicate real estate ads in different avenues (social networks, website, etc.)

We do first clustering the properties using only the texts contained in the "DESCRIPTION" column of the dataframe. Then, for each cluster obtained previously, a micro-cluster is created using only certain columns (feature engineering) excluded from the "DESCRIPTION" column.

I got the following results:

- Number of properties without duplicates: 959

- Number of properties with duplicates: 357

### Restitution of results:

I generated a zip file which contains a set of files useful for the interpretation of the algorithmic results.

The link to the zip is: https://drive.google.com/file/d/1Ng2WbagNHM1y2vE8y9fCztCfLqKW-37k/view?usp=sharing

### Description of the files attached in the zip:

-  "duplicates.csv": It contains the properties present in duplicates. A set of duplicate assets is separated from the others by an empty line in the csv file

- "sans_doublons.csv": It contains the properties that are not duplicated

-  "project.ipynb": python notebook
