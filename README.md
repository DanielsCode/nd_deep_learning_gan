# nd_deep_learning_gan
Project 4

Windows CPU
conda env create -f requirements_conda-cpu.yml
activate gan-project-cpu
pip install -r requirements_pip-cpu.txt
python -m ipykernel install --user --name gan-project-cpu --display-name "gan-project-cpu"

Windows GPU
conda env create -f requirements_conda-gpu.yml
activate gan-project
pip install -r requirements_pip-gpu.txt
python -m ipykernel install --user --name gan-project --display-name "gan-project"