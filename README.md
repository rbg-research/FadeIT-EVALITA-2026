# FadeIT-EVALITA-2026
FadeIT: Fallacy Detection in Italian Social Media Texts

# Task A - Label Distribution
![Task A Distribution](figures/TaskA_Distribution%20of%20labels_a1.svg)

# Task B - Label Distribution
![Task B Distribution](figures/TaskB_Distribution%20of%20labels_a1.svg)

# Task A - Prompt Performance
![Task A Prompt Performance](figures/TaskA_Prompt_performance.svg)

# Task B - Prompt Performance
![Task B Prompt Performance](figures/TaskB_Prompt_performance.svg)

# Installation

#### Python and Libraries
```commandline
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install -y python3.10 python3.10-dev python3.10-distutils
wget https://bootstrap.pypa.io/get-pip.py
source ~/.bashrc
python3.10 get-pip.py
echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
pip3.10 install -U pip
rm get-pip.py
```

#### Virtual Environment
```commandline
pip3.10 install virtualenv
virtualenv --python=python3.10 "$HOME"/environments/fadeit
source "$HOME"/environments/fadeit/bin/activate
```

#### Jupyter Notebook
```commandline
pip install jupyter
pip install ipykernel
python -m ipykernel install --user --name=fadeit
```

#### Requirements
```commandline
pip install -r requirements.txt
```


