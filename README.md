# Running the note book

## Running the OpenNPL Java server

1. Go to the folder containg the OpenNLP tools and run the command:

`
java -mx4g -cp "*" edu.stanford.nlp.pipeline.StanfordCoreNLPServer -port 9000 -timeout 15000
`

This starts the OpenNLP server at port 9000

## Setting up python environment

Clone the github repository and navigate into it. Please follow the below-mentioned steps:

1. Make a python virtual environment with the following command:

`
$ virtualenv py_openie
`

2. Activate the virtual environment

`
$ source py_openie/bin/activate
`

3. Install requirements in virtual environment

`
(py_openie)$ pip install -r path/to/requirements.txt
`

**requirements.txt** is in the repository.
4. Run jupyter notebook

`
(py_openie)$ jupyter notebook
`


