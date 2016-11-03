# Library Characterization Environment (LiChEn) Version 1.0

LiChEn is a program that provides support to the electrical characterization of standard cells, with special support for components devised to design asynchronous circuits, such as special sequential components. It enables the characterization C-elements and NCL gates but is not limited to these components. In this sense, LiChEn complements functionalities of commercial tools devised for circuit characterization, such as the Cadence ELC environment.

To compile LiChEn, just run the provided Makefile with `make all`

## Requirements
LiChEn requires an electrical simulator installed in order to run the simulation files it generates.
Currently, LiChEn only supports the Cadence SPECTRE simulator.

## Example

The LiChEn distribution contains a characterization example for a 2-input AND gate cell. This cell was taken from the NanGate FreePDK45 Open Cell Library (http://www.nangate.com/?page_id=2325) that employs the NCSU FreePDK45 predictive 45nm technology node design kit (http://www.eda.ncsu.edu/wiki/FreePDK45:Contents). All these resources are open access. Also, our research group has available an open access asynchronous cell library based on this PDK and compatible with the NanGate FreePDK45 Open Cell Library. This is the ASCEnD-FreePDK45, available at https://corfu.pucrs.br/ascend-freepdk45/.

## Example

The current version of LiChEn (V1.0) is limited to characterize single-output cells only. This prevents its use to process some components that usually appear in several asynchronous design, such as mutual exclusion elements (mutexes) or cells supporting pseudo-static templates such as PCHB. A new version of LiChEn (V2.0) is under development to address such issues. This release is expected for early 2017.
