# Library Characterization Environment (LiChEn)

## **Welcome to LiChEn Repository**
LiChEn provides electrical characterization support for asynchronous circuits.

To compile LiChEn, just run the provided Makefile with `make all`

## Requirements
LiChEn requires a electrical simulator installed in order to run the simulation files.
Currently, LiChEn only support Cadence SPECTRE simulator.

## Features

LiChEn internal shell supports the following commands:
* help
* devices
* config_devices
* set_library_name
* library_name
* print_library
* add_slope
* print_slopes
* remove_slope
* add_load
* print_loads
* remove_load
* add_cell
* add_schematic
* print_schematics
* print_cells
* remove_cells
* add_model_table
* print_model_table
* print_config
* set_process
* set_models
* set_vh
* set_vl
* set_vhtl
* set_vlth
* set_start_time
* set_sim_time
* set_sim_step
* set_load_unit
* set_time_unit
* set_resistance_unit
* set_voltage
* set_vdd
* set_gnd
* set_temp
* set_max_tran
* characterize_library
* export_library
* exit

**NOTE:** LiChEn also supports standard UNIX commands such as **ls** and **pwd**.

## Example

The repository contains a characterization example of a 2-input AND gate using a [predictive 45nm technology node](http://www.eda.ncsu.edu/wiki/FreePDK), which can be acquired without any restrictions.
