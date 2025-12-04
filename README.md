## AIS data visualization for port congestion project

### Notice
> Ships without /data! Not sure if we're licensed to redistribute these files. Acquire them on your own.

### Where to get /data
- Coastline dataset:
    - src: https://www.naturalearthdata.com/downloads/10m-physical-vectors/10m-coastline/
    - dst: /data/ne_10m_coastline/
- AIS dataset (Awake):
    - src: redacted
    - dst: /data/mission-voyage-examples/
- SPIRE AIS dataset:
    - src: redacted
    - dst: /data/SPIRE_VesselData_Sample

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
