#create a virtaul env
python3 -m venv venv

#activate virtual env
source venv/bin/activate

#install dependencies
pip install -r req.txt


#run the project
mkdocs serve     -> it serves in 8000 port
mkdocs serve -a 0.0.0.0:8001    -> you can specify port in this way

