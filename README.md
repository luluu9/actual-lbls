# actual-lbls

## Data preparation
To prepare data, please install dependencies, put proper MER data in the `data/raw/` directory and run the script.
```
pip install -r requirements.txt
cd source
python3 data_transformer.py
```

Preprocessed data will show up in the `data/preprocessed` directory.

Configuration (e.g. directory settings) is contained in first lines of `data_transformer.py`.  