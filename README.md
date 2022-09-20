# Steps

* Getting the todolist
Use the following command:
`nextflow run covid_pipeline.nf --choice 1`

* Processing the sequencing data
Use the following command:
`nextflow run covid_pipeline.nf --choice 2`

* Combine the sequencing data with the sample information 
Use the following command:
`nextflow run covid_pipeline.nf --choice 3`

This build does not support GPU barcoding acceleration.
docker.runOptions = "-v ${env.WORKDIR}/${env.BATCH}:/batch"