# Mapeamento de zonas de alta periculsidade na metropole de Belo Horizonte

 Este trabalho tem como objetivo identificar zonas onde há uma taxa de crimes acima da média na Metropole de Belo Horizonte, para a coleta de dados foi se utilizado de um documento disponibilizado gartuitamente pelo Sinesp (Sistema Nacional de Informações de Segurança Pública), documento identificado na pasta ```dataset```, documento: indicadoressegurancapublicamunic.xlsx; no documento é identificado o numeros de vitmas de crimes variados entre: Estupro, roubo de veículo,roubo de veículo seguido de morte, homicídio doloso,etc; por ano, de 2018 até 2022 em todos os municipios do Brasil. Além desse arquivo, há o arquivo identificando todos os municípios da região metropolitana de Belo Horizonte e seus municípios limítrofes.
 O dados foram estruturalizados em um grafo não direcionado, e logo após o tratamento e estruturalização, o programa é capaz de identificar regiões entre cidades onde as taxas de crimes são acimas da média dos ultimos 5 anos na região da metropole mineira.

# Execução

 Para a excução do código é necessário algum programa com suporte para a execução de arquivos .ipynb como o google collab ou visual studio code com a extensão jupyter, além disso é necessário importar os arquivos da pasta ```dataset``` para a execução correta do programa. Caso queira executar o programa no google collab não é necessário baixar as bibliotecas: NetworkX,Matplotlib e Pandas; porém caso utilize de outro programa, essas bibliotecas podem ser baixadas através dos seguintes comandos:

|Biblioteca | Comando | 
|----------|----------|
| NetworkX   | pip install networkx[default]  |
| Matplotlib  | pip install -U matplotlib   |
| Pandas   | pip install pandas   |

## Logo após a instalação das bibliotecas o programa já é capaz de ser executado nos Notebooks.

# Código no Google Collab
<a href="https://colab.research.google.com/drive/1SZiC3Cq7CSK48XOg5SKxPqXS1dXLyknN?usp=sharing"> TP3_AEDS2</a>  , para o funcionomento completo do codigo, é necessário baixar os arquivos da pasta ```dataset```, ir no canto esquerdo do Google colab na aba de arquivos:

<img src="img\exemplo_arquivos.png" width="10%">
</div>

Ir na opção de Fazer upload para o armazenamento da sessão:

<img src="img\exemplo_arquivos2.png" width="20%">

E carregar os 2 arquivos da pasta ```dataset```. Logo após esses passos o usuario pode executar os notebooks.

# Autor
E-mail: joaopedrofdpd2205@gmail.com</br>
3° Período-2023-Engenharia de Computação-CEFET-MG