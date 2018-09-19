# clustering-project

This repository contains data for a clustering project.

## Structure
The data is provided as comma-separated values. The separator is the comma ",", newline is CRLF and the rest of the characters are alphanumeric (a-zA-Z0-9). The first row of every file is the header.

## Files

```dependencies.csv``` contains two columns: TC and DependsOn. Note that dependencies written in this file should be considered in either direction. If TC002 depends on TC004, then TC004 depends on TC002 as well.

```vectors.dbow_numnoisewords.2_vecdim.64_batchsize.32_lr.0.001000_epoch.99_loss.0.670579.csv``` contain 65 columns, one column of test case names, and 64 columns specifying a vector for each test case. 