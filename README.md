# Project Nextflow Microcredential
Nextflow project to be developed for the micro-credential VIB/UGent - Reproducble analysis

In this project you will create a Nextflow pipeline based on some data analysis from your research field or following an example provided by the lecturers.

This project should adhere to the following requirements to succeed:

# Requirements Nextflow project

- Should be on Github (Please add the link to [`projects.md`](projects.md))
- Docker and Apptainer compatibility (bonus points if also conda compatible) of all modules. This means that at least each process should be able to run using a container engine. See the [docs](https://www.nextflow.io/docs/latest/container.html) for more information.
- Should contain at least 3 modules from tools that weren't covered during the training
    - at least 1 module should contain a custom script written by the student
    - at least 1 module should contain an existing tool not written by the student
- Should contain at least 1 config profile
- Should not need any prior setup (the pipeline should work out-of-the-box on the infrastructure used during the training) with minimal test data
- Should output relevant files to an output directory
- Should contain at least 3 different [operators](https://www.nextflow.io/docs/latest/reference/operator.html#operators)

# Nice to haves
- Process resources should be managed in the nextflow.config using process labels
- Follow the nf-core best practice guidelines
- The pipeline contains a subworkflow
