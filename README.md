# Workbench-Acceptance-Experiment-R
Workbench Acceptance Experiment used in tests for the workbench with the R programming language.

## How to get started
To get started with your project, go into the src/ directory and run the command:
- `cd Workbench-Acceptance-Experiment-R/src`
- `packrat::restore()` in R to restore the packrat packages of this project.

## Project structure
```
── Workbench-Acceptance-Experiment-R
    ├── data		<- data folder
    ├── docs		<- docs folder
    ├── README.md	<- this file
    ├── reports		<- result reports
    ├── schema	
    │   └── schema.json	<- contains a schema description of the used data
    └── src		<- source files of this experiment
        ├── make_dataset.R
        └── packrat	<- packrat packages, autogenerated
```
