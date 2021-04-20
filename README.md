# Mesures de protecció en acords de pau

Aquest treball pretén mostrar el procés d'elaboració d'una visualització de dades a partir de la informació dels acords de pau a tot el món proporcionada pel projecte [Peace Agreements](https://www.peaceagreements.org/) de la Universitat d'Edimburg.

## Visualització de dades

La visualització global es pot consultar a [Tableau Public - DataViz global](https://public.tableau.com/profile/mvilaboa#!/vizhome/pax_measures_DataViz/Mesuresdeproteccialsacordsdepau). 

El seu objectiu és representar el nombre d'acords de pau que mencionin mesures de protecció en l'ambit d'igualtat i drets humans. Dins la exploració, anàlisi i transformació de les dades, s'han realitzat un seguit de visualitzacions a les diferents fases que es poden consultar a [Tableau Public - DataViz](https://public.tableau.com/profile/mvilaboa#!/vizhome/mesuresdeproteccioalspax/1_7_Acordsdeproteccicivilsperregions)


[![Visualization](./img/mesures_protecció_acords_pau.png)](https://public.tableau.com/profile/mvilaboa#!/vizhome/pax_measures_DataViz/Mesuresdeproteccialsacordsdepau)

## Dades

Les dades utilitzades formen part del conjunt de dades obertes del projecte Peace Agreements de la Universitat 
d'Edimburg i contenen informació sobre els acords de pau signats a tot el món des de 1990.

- [data](./data): fitxers CSV utilitzats per a la construcció de la visualització.
  - [pax_327_agreements.csv](./data/pax_data_327_agreements.csv)
  - [pax_measures_data.csv](./data/pax_measures_data.csv)
- [docs](./docs): document PDF amb l'informe. 
  - [FernandezVilaboaMarcos_VD_PAC2.pdf](.docs/FernandezVilaboaMarcos_VD_PAC2.pdf)
- [img](./img): captures de la visualització
  - [mesures_protecció_acords_pau.png](./img/mesures_protecció_acords_pau.png)
- [src](./src): fitxers amb el codi per a la neteja i transformació de les dades.
  - [transformation.ipynb](.src/transformation.ipynb)


----
