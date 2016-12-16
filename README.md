# WEBMAPPING COM PYTHON

- Exemplo da utilização da biblioteca [**folium**][0]
- Conversão de shapefiles para o formato GeoJSON.


### Como desenvolver?

1. Clone o repositório.
2. Crie um virtualenv com Python 3.5.0
3. Ative o virtualenv.
4. Instale as dependências.
5. Abra o arquivo [webmapping_folium.ipynb][1] no jupyter notebook

```bash
git clone git@github.com:marcellobenigno/webmapping.git webmapping
cd webmapping
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```


[0]: https://github.com/python-visualization/folium
[1]: https://github.com/marcellobenigno/webmapping/blob/master/webmapping_folium.ipynb