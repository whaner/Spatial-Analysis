# Spatial Analysis in python
## Objetivo
Replicar, em Python, os exemplos dados pelo prof. dr. Rafael de Freitas Souza, em R, na disciplina de Análise Espacial, do MBA em DSA, da USP-ESALQ.
## Estrutura
- Na pasta shapefiles estão os arquivos utilizados nos notebooks.
- Cada notebook contém uma parte da aula e, a medida do possível, tentei seguir a sequência utilizada pelo professor, inclusive com as saídas.
- Alguns comandos em R não têm um equivalente em python (pelo menos não conheço) e, nestes casos, foram substituídos por librarys que mais se aproximavam do resultdo esperado.
- No final de cada notebook, foram incluídos links para referências utilizadas na tentativa de se replicar os scripts em R.

## Bibliotecas utilizadas
### Pandas e Matplotlib
Bibliotecas usuais para data wrangling e visualization.

### Geopandas
Foi a principal biblioteca utilizada na análise espacial em python e é interessante, pois deriva do pandas, sendo possível a utilização de todos os métodos do panddas para a manipulação dos datasets, adicionando à biblioteca original a capacidade de se manipular dados espaciais.
### Pyreadr e Rddata
Foram usadas para a imporação de arquivos .Rdata. Dependendo da necessidade de usar encoddind nos dados, vc pode usar uma ou outra biblioteca.
### Libpysal
Usada na construção das matrizes W de distância

## Observações
- Os notebooks contém os comandos em python, sem as saídas, já que alguns outputs, como gráficos interativos, levariam o tamanho do arquivo a mais de 100mb, causando alguns problemas com o Github.
