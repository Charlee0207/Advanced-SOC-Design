### Build `hls_userdma`

```
cd ./vivado/vitis_prj/hls_userdma/
vitis_hls script.tcl
```

### Run Simulation

```
cd ./vivado
./run_vivado_fsic_sim
```

### Check Simulation Result
```
cd ./vivado
vim ./updma_input.log
vim ./updma_output_gold.log
vim ./updma_output.log
```

### Run Synthesis

```
cd ./vivado
./run_vivado_fsic
```

### Run Jupyter Notebook

Upload files to the board

`/vivado/jupyter_notebook/caravel_fpga_fsic.ipynb`
`/vivado/jupyter_notebook/caravel_fpga.bit`
`/vivado/jupyter_notebook/caravel_fpga.hwh`
`/vivado/jupyter_notebook/fsic.hex`
