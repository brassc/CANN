Versions:
python 3.11.6

!pip install matplotlib==3.2.2
!pip install tensorflow==2.12.0
!pip install numpy==1.23.5
!pip install scikit-learn==1.3.0
!pip install tensorflow==2.12.0
!pip install keras==2.12.0
!pip install pandas==1.5.3
!pip install openpyxl==3.1.2





How to [create new env, use in VS Code with Jupyter notebook]:
- to create new python env, navigate to directory where you want the env to be stored e.g. mkdir python_envs and run 'python -m venv <pyenv_name>'

- The environment for this repo I have called 'CANN_ME233_env'

- to set up this environment suitable for use with jupyter notebook, activate the new environment 'source path/to/env/bin/activate' then  run 'pip install ipykernel'.
- Check this has installed using 'pip show ipykernel'.
- Install kernelspec, run:  python -m ipykernel install --user --name=<pyenv_name>
- Navigate to repo, open VS code using % code .
- open command palette (cmd + shift + P) and select path of activated python environment. 
- Click on jupyter kernel (top right) and select same python environment. 
 
