# Snakemake Usecases

Snakemake is a pipeline software, a cross-over of GNU make and python.
<https://bitbucket.org/johanneskoester/snakemake/wiki/Home>

Here some useful testcases are described:
  
## Test cases
 
**Minimal:**  snakemake-minimal-test 

The simpliest case: Two input files create one output file 

**Minimal Pattern:** snakemake-minimal-pattern-test

A very simple test case consisting of two (or more) input files which are processed 
to two (or more) output files. These output files are summarized in a statistic file.
 
**Cluster:** snakemake-cluster-test

The simple test case consisting of many input files which are processed 
to output files. These are summarized in a stats file.
 
**Two input two output:** snakemake-two-input-two-output-test

A more complex setup where for a generic processing step two (or more)
input files are needed and two (ore more) output files are created.

## Contact
Author: Thomas Schwarzl <schwarzl@embl.de>

Licence: MIT

