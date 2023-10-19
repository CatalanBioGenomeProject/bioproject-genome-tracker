# bioproject-genome-tracker
Retrieve all the INSDC assemblies under the [Catalan Initiative for the Earth BioGenome Project](https://www.biogenoma.cat) umbrella

It uses a scheduled github action to install the [NCBI datasets CLI](https://www.ncbi.nlm.nih.gov/datasets/docs/v2/reference-docs/command-line/) and pull the data from there.

Variables as the BioProject accession number are inject via a .env file

Assemblies are stored in a tsv file
