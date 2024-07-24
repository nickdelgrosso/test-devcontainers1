# Calculate a Mean (Devcontainer Experiment)

## Install

### Prerequisites

Docker should be installed on your machine before using it locally. 

### Setup

1. Install all dependencies
   - **In VSCode**: Just `git clone` the repo and open it with VSCode; VSCode should detect that there is a `devcontainer.json` file and suggest installing the required extensions.  Let VSCode install everything and then reload the project in a devcontainer.

   - **In GitHub Codespaces**: In the GitHub repo page, Click `Code`, then the plus symbol to make a codespace.  

2. Start a new terminal in the IDE.  The `first` conda environment should auto-activate and have everything already installed in it.


## Usage

After the container is done being built, you should be able to:


1. Run the `scripts/get_mean.py` function and see the result "3.5" get printed. This script uses numpy, which should  have been auto-installed when the dev container was built.
2. Play around in linux inside the terminal.
3. (if running on your local machine) Access your home directory at the `/host-home-folder` folder.
4. Be able to modify the `pyproject.toml` file or `environment.yaml` file, rebuild the devcontainer (`Ctrl-Shift-P -> Dev Containers: Rebuild Container`), and get your conda environment with the new dependencies intalled.
