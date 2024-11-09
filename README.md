# Tutorial sobre xarray
**Ponent:** Oriol Abril Pla
**Lloc:** PyDay BCN 2024

## Instal·lació de dependències

```
pip install -r requirements.txt
# o
conda env create --file environment.yml
```

Això instal·larà les dependències per tal d'executar la llibreta de jupyter,
pero no jupyter notebook ni jupyter lab. En cas que us calgui instal·lar-ho també:

```
pip install jupyterlab
# o
conda install jupyterlab
```

## Resum
Apren com utilitzar xarray per treballar amb arrays n-dimensionals a través d'etiquetes i indexs arbitraris.
Descobreix el model de dades d'xarray: DataArrays, Datasets, dimensions, coordenades, indexes.
Explora a través del tutorial les operacions més comunes en matrius n-dimensionals:
com especificar en quines dimensions han d'operar les funcions utilitzant noms enlloc d'indexs posicionals,
com definir subconjunts a través de coordenades,
com combinar el metode `.query` amb filtrar multiples dimensions,
com crear multiples indexs per a una mateixa dimensió,
les diferencies entre operacions d'indexatge exteriors o vectoritzades,
groupbys multidimensionals, i més.
