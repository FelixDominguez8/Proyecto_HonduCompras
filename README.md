# Proyecto_HonduCompras

Para este proyecto se hizo un modelo y analitica de texto para un dataset del ONCAE que se puede encontrar en: https://oncae.gob.hn/datos-abiertos/ , en especifico: HonduCompras 1.0 – Módulo de Difusión de Compras y Contrataciones, la version de 2025 en su formato de csv. Este dataset incluye varios csv que se basan en las compras hechas por el gobierno y las contrataciones de dichas compras. Esto se realizo en dos workflows de Knime, uno para el modelo y el otro para el text analytics. En workflow del modelo se utilizo un isolation forrest para encontrar anomalias en el dataset, mientras que en el de text analytics se utilizaron diversas tecnicas de visualizacion como redes, nubes de palabras y lda. Del dataset entre ambos workflows se utilizaron solo 3 csvs de los varios que se descargaban en la version csv del dataset de ONCAE, estos son: awa_items, awa_suppliers y releases. Este proyecto se hizo en colaboracion con mi compañero de clase de Mineria de Datos, Joe Corrales

### Roles y Trabajo Colaborativo
- Felix Dominguez: Desarrollo del workflow de text analytics, dashboards de power bi y parte del modelo
- Joe Corrales: Desarrollo del modelo

### Imagenes
- Dashboard
![Primera pagina del PowerBI](img/Dashboard.png)

- Modelo
![Worflow del modelo](img/Modelo.svg)

- Text Analytics
![Workflow del Text Analytics](img/TextAnalytics.svg)

