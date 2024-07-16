# Análise de Organizações Mencionadas em Notícias do Primeiro Trimestre de 2015

Este projeto analisa as organizações mencionadas em notícias na categoria "Mercado" durante o primeiro trimestre de 2015. Utilizamos o modelo `monilouise/ner_pt_br` para reconhecimento de entidades nomeadas (NER) para identificar organizações mencionadas nos textos. Em seguida, geramos um ranking das organizações mais mencionadas e visualizamos os dados em um gráfico de barras horizontal e uma nuvem de palavras.

## Dependências

Certifique-se de instalar as seguintes bibliotecas antes de executar o código:

- pandas
- transformers
- torch
- seaborn
- matplotlib
- tqdm
- wordcloud

Você pode instalar as dependências executando:
```bash
pip install pandas transformers torch seaborn matplotlib tqdm wordcloud
