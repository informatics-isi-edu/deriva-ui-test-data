# Plot

In this folder, we have included the test data for fetching the data from file for plot app

The following are the included files:

## violin.json

Test data for violin plot in json format

## violin.csv

Test data for violin plot in csv format

```
https://dev.gudmap.org/ermrest/catalog/2/attributegroup/M:=RNASeq:Replicate_Expression/(Study=14-3PXT)&NCBI_GeneID=1/exp:=(Experiment)=(RNASeq:Experiment:RID)/$M/Anatomical_Source,Experiment,Experiment_Internal_ID:=exp:Internal_ID,NCBI_GeneID,Replicate,Sex,Species,Specimen,Specimen_Type,Stage,Age,Starts_At,Ends_At,TPM
```
(url for this test data. Use `?accept=csv` at the end of url to download test data in csv format)

## gudmap.json (This file has no test data as of now)

Commmon test data for `gudmap-todate-bar plot`,`gudmap-todate-pie`,`gudmap-todate-bar-swapped` & `gudmap-todate-summary-responsive` in json format

## gudmap.csv (This file has no test data as of now)

Commmon test data for `gudmap-todate-bar plot`,`gudmap-todate-pie`,`gudmap-todate-bar-swapped` & `gudmap-todate-summary-responsive` in csv format

```
https://dev.gudmap.org/ermrest/catalog/2/entity/M:=Dashboard:Release_Status/Consortium=GUDMAP/!(%23_Released=0)/!(Data_Type=Antibody)/!(Data_Type::regexp::Study%7CExperiment%7CFile)/$M@sort(ID::desc::)?limit=26
```
(url for this test data. Use `?accept=csv` at the end of url to download test data in csv format)

## scatter.json

Test data for `scatter` plot in json format

## scatter.csv

Test data for `scatter` plot in csv format

```
https://dev.gudmap.org/ermrest/catalog/2/attributegroup/M:=Gene_Expression:Specimen/stage:=left(Stage_ID)=(Vocabulary:Developmental_Stage:ID)/$M/Assay_Type,stage:Name
```
(url for this test data. Use `?accept=csv` at the end of url to download test data in csv format)

## histogram.json

Test data for `specimen-histogram-vertical` & `specimen-histogram-horizontal` plot in json format

## histogram.csv

Test data for `specimen-histogram-vertical` & `specimen-histogram-horizontal` plot in csv format

```
https://dev.gudmap.org/ermrest/catalog/2/entity/Gene_Expression:Specimen@sort(RCT::desc::)?limit=10000
```
(url for this test data. Use `?accept=csv` at the end of url to download test data in csv format)

## heatmap.json

Test data for `heatmap` plot in json format

## heatmap.csv

Test data for `heatmap` plot in csv format

```
https://dev.gudmap.org/ermrest/catalog/2/entity/Gene_Expression:Array_Data_view/NCBI_GeneID=12267&Section_Ordinal=3
```
(url for this test data. Use `?accept=csv` at the end of url to download test data in csv format)