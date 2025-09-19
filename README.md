### How to create a Conda environment ?

1.	conda create --name env python=3.11
2.	conda env list
3.	conda env export > environment.yml
4.	conda activate env
5.	cd project_folder
6.	conda env create --prefix ./env -f ../environment.yml ( downloads all the tools )
7.	jupyter notebook
