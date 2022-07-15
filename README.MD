This is demo MMLFLOW PROJECT file.

Create a an conda environment using below command.
```bash
conda craete -n <env_name> python=3.7.11
```
Now activate the conda environment using below command.
```bash
conda activate <env_name>
        or
source activate <env_name>
```
Install the requirements
```bash
pip install -r requirements.txt
```
Now create gitignore file to ignore the some files when pushing into github repository.
```bash
touch .gitignore
````

Create a demo.py and then write a code
```bash
touch demo.py
```
Run the demo file
```bash
python demo.py
```
Create runs.py file
```bash
touch runs.py
```
To see the UI of the mlfow project
```bash
mlfow ui
```
Use this link to see the UI of the mlfow project (source)http://127.0.0.1:5000/
Create MLproject file
```bash
touch MLproject
```
Export environment to conda.yaml file
```bash
conda env export > conda.yaml
```