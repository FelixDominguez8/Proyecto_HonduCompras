# Proyecto_HonduCompras

Para este proyecto se hizo un modelo y analitica de texto para un dataset del ONCAE que se puede encontrar en: https://oncae.gob.hn/datos-abiertos/ , en especifico: HonduCompras 1.0 – Módulo de Difusión de Compras y Contrataciones, la version de 2025 en su formato de csv. Este dataset incluye varios csv que se basan en las compras hechas por el gobierno y las contrataciones de dichas compras. Esto se realizo en dos workflows de Knime, uno para el modelo y el otro para el text analytics. En workflow del modelo se utilizo un isolation forrest para encontrar anomalias en el dataset, mientras que en el de text analytics se utilizaron diversas tecnicas de visualizacion como redes, nubes de palabras y lda. Del dataset entre ambos workflows se utilizaron solo 3 csvs de los varios que se descargaban en la version csv del dataset de ONCAE, estos son: awa_items, awa_suppliers y releases. Este proyecto se hizo en colaboracion con mi compañero de clase de Mineria de Datos, Joe Corrales

### Roles y Trabajo Colaborativo
- Felix Dominguez: Desarrollo del workflow de text analytics, dashboards de Power BI y parte del modelo
- Joe Corrales: Desarrollo del modelo

### Imagenes
- Dashboard
<img width="1167" height="657" alt="Dashboard" src="https://github.com/user-attachments/assets/5aa82c40-4520-487a-b2d9-6a9d3a77956f" />

- Modelo
<img width="1787" height="617" alt="Modelo1" src="https://github.com/user-attachments/assets/d697af66-624f-44c2-8772-f52e946fea5a" />
<img width="1207" height="740" alt="Modelo2" src="https://github.com/user-attachments/assets/8c4d9128-465c-462a-b256-09daec6b63ae" />
<img width="1112" height="827" alt="Modelo3" src="https://github.com/user-attachments/assets/89dd6a76-de33-4806-9268-41f5a0113b53" />


- Text Analytics
<img width="1762" height="656" alt="TextAnalytics1" src="https://github.com/user-attachments/assets/29f3476a-9705-49e0-aa8e-42c8e40379c6" />
<img width="1812" height="707" alt="TextAnalytics2" src="https://github.com/user-attachments/assets/02b43b29-00c8-48c7-bb71-83d41bdc17b4" />
<img width="1345" height="686" alt="TextAnalytics3" src="https://github.com/user-attachments/assets/fd567ba5-9940-468f-bdd1-4c6bde090da0" />

