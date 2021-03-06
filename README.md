# Repository Title: ODE_Python
_About_: Numerical solver for ODE's for simulated flying insect
___

# TODO: 
1. Run simulations to generate more training data for Neural Networks (parallel sims)
2. Use newly generated training data to train NNet
3. *Build a bigger ball for control parameters.
4. *Penalize high values for controls or speeds. – sift through training and test data to take out “bad” controls.
5. *Try Mixture Density Network
6. *Tru reinforcement learning












___
# Git instructions: 
## Get this repository onto your local computer: 
- a. Open terminal and navigate to a directory where you want this folder (ex. .../Documents/GitRepos)
- b. clone this repository (download it onto your local computer) 

    ```git clone https://github.com/nifti-coe/ODE_Python.git```
    

## When you want to get the most recent version from github
- a. Open terminal and navigate to the folder where this repository is stored (ex. .../Documents/GitRepos/ODE_Python)
- b. "pull" the most recent version 

    ``` git pull ```

## When you want to upload your changes to github
- a. Open terminal and navigate to the folder where this repository is stored (ex. .../Documents/GitRepos/ODE_Python)
- b. "add" your changes (stage changes).  Note that the "." means to add everything in the folder 

    ``` git add . ```
- c. "commit" your changes. This will create a checkpoint on your local computer. include a commmit message with the "-m" flag. 

    ``` git commit -m "short commit message" ```
- d. "push" your changes to the web.

    ``` git push ```
