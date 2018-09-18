# clustering-project

This repository contains data for a clustering project.

## Structure
The data is provided as comma-separated values. The separator is the comma ",", newline is CRLF and the rest of the characters are alphanumeric (a-zA-Z0-9). The first row of every file is the header.

## Files

```dependencies.csv``` contains two columns: TC and DependsOn. Note that dependencies written in this file should be considered in either direction. If TC002 depends on TC004, then TC004 depends on TC002 as well.

```vectors*.csv``` contain N+1 columns where N is the number of dimensions for the given file. We have provided you with files for 16, 64, and 256 dimensions. The first column (```label```) is the test case label. The rest of the columns represent a vector associated with that label.