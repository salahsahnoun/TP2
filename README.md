# TP2 : Étude de cas Road Crash avec PySpark

Reproduction de l'étude « Big Data Analysis of Road Crash Data using PySpark with PySpark Tutorial » (Rakesh Nain) :
https://medium.com/rakesh-nain/big-data-analysis-of-road-crash-data-using-pyspark-with-pyspark-tutorial-c78ff2c35588

## Contenu

- `Road_Crash_PySpark.ipynb` : le notebook (RDD, DataFrames, Spark SQL).
- `crash_data/`, `units_data/` : données des accidents de la route en Australie-Méridionale, 2012 à 2019 (DPTI, https://data.sa.gov.au).
- `log4j2.properties` : configuration des logs de Spark utilisée par le notebook.
- `severe.png` : graphique de la gravité des accidents selon l'alcool et les drogues.

## Exécution

Prérequis : Python 3, Java 11 ou 17, `pyspark` 3.5, `pandas`, `matplotlib`, Jupyter.

```bash
pip install "pyspark==3.5.*" pandas matplotlib notebook
jupyter notebook Road_Crash_PySpark.ipynb
```

Le notebook s'exécute depuis ce dossier (chemins relatifs vers les données).
