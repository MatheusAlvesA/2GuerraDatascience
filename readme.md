# Análize das batalhas da segunda guerra
Este projeto se dedica a analizar datasets a respeito das inúmeras batalhas ocorridas durante a segunda guerra mundia. As tecnologias usadas para a análize destes datasets são baseadas em Pyhton. Usaremos a biblioteca Pandas, para a leitura e manipulação dos arquivos de dataset, uma vez que estes estão em .csv, um formato adequado para se trabalhar com o Pandas. Utilizaremos a biblioteca Folium para plotar mapas de calor e de pontos.

A plataforma escolhida para execução das simulações foi um notebook Jupter, hospedado na núvem do Google(Google Colaboratory). O notebook está disponível neste repositório com o nome: "ListaBatalhas_Mapa.ipynb".

# Os datasets
Nosso projeto conta com 3 datasets, os links com as fontes de nossos dados estão disponíveis no final deste documento.

Abaixo vamos descrever cada um dos três datasets e sua aplicação no Notebook.

### ListaBatalhas.csv

Este dataset foi escrito a mão por nós mesmos. Possue 60 linhas contendo, cada uma, informações sobre decisivas batalhas ocorridas na segunda guerra, bem como sua localização geográfica em latitude e longitude. O dataset possue as seguintes colunas:

| Nome | Função |
| ------ | ------ |
| Nome | O nome da batalha em questão |
| Ano | O ano em que o conflito ocorreu ou foi iniciado |
| GeoLocalizacao | A Geo localização em latitude e longitude, separados por vírgula|
| Descricao | A descrção do conflito ocorrido |

### Geodata.csv

Este dataset é parecido com o anterior, mas possui mais de mil linhas. Ele contém os dados das localizações das batalhas dentre alguns outros, entretanto, usamos este dataset no nosso projeto apenas para criar um mapa de calor que indica os locais mais afetador elas batalhas da seguna guerra.

### operations.csv

Assim como o Geodata.csv, esse dataset é usado para plotar um maa de calor muito útil a respeito das batalhas aéres e como os aviões afetaram o curso da guerra.

# Autoria

[Nalbert Gabriel](https://nalbertleal.github.io/) - Análize do dataset e deselvolvimento do mapa das batalhas aéreas.

[Matheus Alves](https://matheusalves.com.br/) - Criação do dataset das batalhas e suas descrições bem como os mapas derivados.

[Yuri Reinaldo](https://github.com/Yuri-wrlk) - Pesquisa e fontes de dados. Código de limpeza dos dados dos datasets.

[Misael Batista](mailto://misael19972008@hotmail.com) - Auxiliou no desenvolvimento do mapa de calor das batalhas em geral e corrigiu bugs. 

# Fontes

>https://pt.wikipedia.org/wiki/Lista_de_batalhas_da_Segunda_Guerra_Mundial
>https://www.nationalww2museum.org/students-teachers/student-resources/research-starters/research-starters-worldwide-deaths-world-war
>https://www.historylearningsite.co.uk/world-war-two/famous-battles-of-world-war-two/the-battle-of-stalingrad/
>https://www.kaggle.com/domcastro/wars-and-fights-draft/code
>http://www.correlatesofwar.org/data-sets
