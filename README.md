# SLI_Galician_DBpedia
## DBpedia data and DBpedia Spotlight for Galician language

|File|Size|Description|
|----|-----|-------|     
|SLI_Galician_DBpedia_RDF_20151201.tar.gz|150M|_SLI Galician DBpedia_ at version 20151201 (http://gl.dbpedia.org) in RDF (Resource Description Framework) format|
|SLI_Galician_DBpedia_Spotlight_1.0.tar.gz|37M|_DBpedia Spotlight_ (http://www.dbpedia-spotlight.org/) SLI model for Galician language at version 1.0 (http://sli.uvigo.gal/spotlight/) built using Quickstarter for DBpedia Spotlight models (https://github.com/dbpedia-spotlight/model-quickstarter)|

These resources are made available under the terms of Creative Commons Attribution 4.0 International Public License (CC BY 4.0) (which you can find at https://creativecommons.org/licenses/by/4.0/), and are distributed without any warranty.

Information and contact: Xavier Gómez Guinovart (xgg2021@gmail.com)

***
## Note

Both files (**SLI_Galician_DBpedia_RDF_20151201.tar.gz** and **SLI_Galician_DBpedia_Spotlight_1.0.tar.gz**) has been split into 25MB parts with the split command. For instance:

```console
$ split -b 25M -d SLI_Galician_DBpedia_RDF_20151201.tar.gz SLI_Galician_DBpedia_RDF_20151201.tar.gz.part
```

To rejoin these parts, you can use the cat command:

```console
$ cat SLI_Galician_DBpedia_RDF_20151201.tar.gz.part* > SLI_Galician_DBpedia_RDF_20151201.tar.gz
```
