## AIS data visualization for port congestion project

### Notice
> Ships without /data! Not sure if we're licensed to redistribute these files. Acquire them on your own.

### Where to get /data
- coastline dataset: https://www.naturalearthdata.com/downloads/10m-physical-vectors/10m-coastline/
- AIS dataset (Awake): redacted

### Setup
```bash
# clone repo
git clone https://github.com/Magnuswlange/port_congestion_proj.git
cd port_congestion_proj

# create venv, activate and install requirements
python -m venv venv
source /venv/bin/activate
pip install -r requirements.txt

# install jupyter kernel for .ipynb
python -m ipykernel install --user --name=port_congestion --display-name="Port Congestion (venv)"

# verify deps installed successfully
python -c "import pandas, geopandas, matplotlib; print('deps successfully installed!')"
```

### Showcase
Open the "Awake_Data_Exploration.ipynb" in e.g. VS Code.
