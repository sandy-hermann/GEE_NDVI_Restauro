# GEE_NDVI_Restauro 
**Por: Sandy dos Reis Hermann**

26/05/2025

**Análise do monitoramento de 5 anos da cobertura vegetal em área de restauração com uso de imagens de satélite: uma abordagem usando Google Earth Engine e Google Colab**

Esse projeto tem como objetivo analisar por meio das geotecnologias, a cobertura vegetal da área de restauro ao entorno da PCH Anhanguera, localizada no município de São Joaquim da Barra - SP. Este script utiliza o Google Earth Engine para calcular o NDVI (Índice de Vegetação por Diferença Normalizada) de imagens do satélite Sentinel-2 na área de interesse com raio de 5 km, para os anos de 2018 a 2022. Os resultados são exportados automaticamente para o seu Google Drive, aonde você definiu a pasta.


✅ Requisitos

- Conta no Google Earth Engine (https://signup.earthengine.google.com)
- Biblioteca Python 'earthengine-api' instalada
- Autenticação feita com ee.Authenticate() e ee.Initialize()
- Permissão para gravar no seu Google Drive

Ao final do projeto você terá salvo em sua pasta do Google Drive, 5 arquivos em formato .tif, onde você poderá abrir-los em alguma ferramenta como o QGis para verificar a área, fazer as modificações de cores que achar necessário, e ver a tabela de atributos com todos os valores. 
