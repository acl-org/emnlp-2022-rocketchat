```bash
virtualenv venv --python=python3 
source venv/bin/activate

pip install -r requirements

python make_paper_rooms.py --config config.yml --papers data/cl_papers.csv
python make_paper_rooms.py --config config.yml --papers data/tacl_papers.csv
```
