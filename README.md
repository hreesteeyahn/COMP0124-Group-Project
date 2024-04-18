# COMP0124-Group-Project

### Overview
This repository contains two Jupyter notebooks that are part of a simulation project involving Q-learning agents in a cleanup game environment. The simulation demonstrates how agents can learn and interact within a virtual environment to perform tasks like collecting items and navigating spaces.

### Files
1. **cleanup.ipynb** - This notebook sets up a basic simulation environment where agents can perform tasks without learning capabilities. It primarily focuses on the mechanics of agent movements and interactions within the game grid.

2. **cleanup-with-q-agent.ipynb** - This notebook extends the basic cleanup simulation by introducing Q-learning agents. These agents use reinforcement learning to improve their decision-making processes over time based on rewards received from the environment.

### System Requirements
- **Python 3.8** or higher
- **Jupyter Notebook** or **JupyterLab**
- Libraries:
  - **NumPy**
  - **Matplotlib** (optional, for visualization)
  - **imageio** (optional, for creating visual outputs of the simulation)

### Setup Instructions
1. **Install Python**: Ensure Python 3.8 or later is installed on your system. You can download it from the [official Python website](https://www.python.org/downloads/).

2. **Install Jupyter**: If you don't have Jupyter installed, you can install it using pip:
   ```
   pip install notebook
   ```

3. **Install Required Libraries**: Install the necessary Python libraries using pip:
   ```
   pip install numpy matplotlib imageio
   ```

4. **Download the Notebooks**: Download the `cleanup.ipynb` and `cleanup-with-q-agent.ipynb` from this repository to your local machine.

### Running the Notebooks
1. **Open Jupyter Notebook**: Navigate to the directory containing the notebooks and run:
   ```
   jupyter notebook
   ```

2. **Open the Desired Notebook**: In the Jupyter interface, click on the notebook file you wish to open (`cleanup.ipynb` or `cleanup-with-q-agent.ipynb`).

3. **Run the Notebook**: Execute the cells sequentially by pressing `Shift + Enter` on each cell or using the "Run All" option from the toolbar to execute all cells in the notebook.

### Additional Notes
- **cleanup.ipynb**: This notebook is useful for understanding the basic framework and mechanics before adding complexity with learning algorithms. It includes agent initialization, environment setup, and basic movement logic.

- **cleanup-with-q-agent.ipynb**: This notebook is more advanced and includes implementations of Q-learning. It's crucial to understand the flow of states, actions, and rewards as these are fundamental to how the learning process is simulated.

### Support
For any issues or further questions, please open an issue in this repository or contact the maintainers directly. Or contact the contributors.

### Contributors
- **Yipeng Qu**: [yipeng.qu.20@ucl.ac.uk](mailto:yipeng.qu.20@ucl.ac.uk)
- **Hristijian Bosilkovski**: [hristijan.bosilkovski.23@ucl.ac.uk](mailto:hristijan.bosilkovski.23@ucl.ac.uk)