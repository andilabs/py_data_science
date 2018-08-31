# py_data_science

install python3 if needed with:

	brew install python3

python3 virtualenv

	virtualenv --python=/usr/local/bin/python3 venv

activate it:

	source venv/bin/activate

install libs

	pip3 install -r requirements.txt

setup kernel in jupyter to virtualenv python

	python -m ipykernel install --user --name=venv

run jupyter:
	
	jupyter notebook
	
pick new and `venv`