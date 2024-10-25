# EHRMLA_MayTreat

## Description
Repo and Documentation of the Multiomics Electronic-Health-Record (EHR) Machine Learning Analysis (MLA) May Treat KP via Plater.

## Repo structure
Contains following folder and codes:
1. 'version.yaml' : Minimal version file needed for Plater + Automat
2. 'infores_catalog_only_EHRMLA_part.yaml': Partial file of infores_catalog.yaml
3. Corresponding node & edge files can be find in the csv files folder of each KP

## Plater + Automat deployment procedure
Steps:
0. Make sure edge and node files are KGX format compliant (see current csv file's col)
1. Prepare node, edge, and version.yaml files
2. (Optional) Update infores_catalog yaml file if needed
3. Send to contact [Evan Morris](emorris@renci.org), [Karamarie Fecho](kfecho@copperlineprofessionalsolutions.com) and notify an update
4. (Optional) Be part of the Plater team’s planned monthly update / deployment
5. The running time of the automatic deployment script based on our current KG size ~15 mins
6. (Optional) Update the KP specific wiki page if needed

## For more detail:
1. Please check the [Multiomics EHRMLA May Treat KP wiki page](https://github.com/NCATSTranslator/Translator-All/wiki/Multiomics-EHRMLA-May-Treat-KP) for the explanation of the data, graph, resources, and how to use this KP.
2. Please check the [information-resouce-registry repo](https://github.com/biolink/information-resource-registry) for the latest infores of this KP.
