CTRL-ALT-L   - formatting
CTRL-/       - duplicating


pip install flake8
pip install pytest
pip install coverage
pip install pytest-cov
pip install isort

pytest .
pytest -s .
pytest -v .
pytest --cov . 
pytest --cov . --cov-report=html        - creating HTML

isort --check .     - just checking
isort  .            - fixing