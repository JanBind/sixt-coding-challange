# Sixt Data Science Lab - Test Task for Data Scientist Job Candidates
## Setup
### Local Package setup

First create a virtual environment using

```bash
# create virtual environment
python -m pip install --user virtualenv
virtualenv .venv

# activate virtual environment
source .venv/bin/activate

# upgrade package manager
pip install --upgrade pip
```

Then install the package and requirements:

```bash
pip install -r requirements.txt
```

## After development:
For freezing the requirements, I used after my testing:
```bash
pip freeze > requirements.txt
```

**Note:** I installed only the package of requiements_base.txt. The freezing process lead to a much bigger requirement-file because of the package dependencies.