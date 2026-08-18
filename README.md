# Comparação Radiométrica entre Plataformas de Processamento de Imagens VANT

Ferramenta para avaliação da consistência radiométrica de ortomosaicos e índices de vegetação gerados por diferentes plataformas de processamento fotogramétrico (Pix4D Fields, DroneDeploy, Agisoft Metashape) a partir das mesmas imagens multiespectrais de VANT.

## Funcionalidades
- Leitura, reprojeção e **co-registro espacial** de rasters GeoTIFF entre plataformas
- Máscaras vetoriais de área de interesse (`rasterio.mask`)
- Métricas de concordância pixel a pixel: correlação de Pearson, R², RMSE, viés
- Figuras comparativas para publicação

## Stack
`Python` · `rasterio` · `geopandas` · `scipy` · `numpy` · `matplotlib` · Google Colab

## Contexto
Pipeline vinculado a manuscrito científico sobre inconsistência radiométrica entre plataformas de processamento de imagens de VANT em agricultura de precisão (em revisão).
