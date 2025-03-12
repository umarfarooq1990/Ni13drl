
### DRL Framework for Ni13 Nanocluster's Global Minimum Search 


### How to Run the Code

1. **Set Up the Environment:**
   - Install the required Conda environment using the provided YAML file:
     ```bash
     conda env create -f env_clusgym.yml
     ```

2. **Configure the Nanocluster Composition:**
     ```
   - For simulating a cluster of Nickel (Ni) 13 atoms:
     eleNames = ['Ni']
     eleNums = [13]
     ```

3. **Run the Simulation:**
   - Execute the script using Python.
     ```bash
     python gym_trpo_single.py   
     ```
