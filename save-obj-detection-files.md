### Instructions to create your own carla data

1. Install Carla (Need to elaborate instructions / refer to RL CARLA section for installation)
2. Run Carla from terminal and let it run in background
1. Open a new terminal and run each line
```sh
git clone https://github.com/sizhky/carla-dataset-runner`
cd carla-dataset-runner
jupyter notebook
```
2. Open create-hdf5-files.ipynb and run the cell
3. Wait for the code to finish executing and close the notebook
4. Open extract-images-from-hdf5 and run all the cells
5. You have the data stored in yolo format in the `DUMP_FOLDER` variable in the current folder
