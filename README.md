# DeepEmotions
**Team:** Bartosz Brzoza, Magdalena Buszka, Martyna Firgolska

## Setup
```
conda env create  --file conda.yml
conda activate deepemotions
poetry install
```

### If your machine is stubborn
```
pip uninstall poetry
pip install poetry
poetry add aiohttp
pip uninstall poetry
pip install poetry
poetry add requests
pip uninstall poetry
pip install poetry
```