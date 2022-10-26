# DESAFIO DE PROCESSAMENTO DE DADOS DE SUPERMERCADO
1. Uma rede de supermercados viu a necessidade de criar uma maneira de entender 
e conhecer melhor o seu público-alvo. Diante desse desafio, a rede precisa criar um 
processo de Big Data para auxiliar essa análise. A rede quer conhecer seu cliente 
como um todo, das compras que foram realizadas aos produtos mais vendidos e 
dessa forma criar uma estrutura que permita tomar decisões mais assertivas. 

### PASSO 1. OBTER OS DADOS.
1. OS DADOS DE COMPRA, CLIENTE E ESTADOS FORAM OBTIDOS A PARTIR DE UMA URL DO GIT HUB
2. OS DADOS DE PRODUTOS FORAM OBTIDOS A PARTIR DE UMA MINERAÇÃO NO SITE INDICADO
3. [OS DADOS COLETADOS DE FORMA BRUTA PODEM SER OBTIDOS AQUI](https://github.com/Antonio-Borges-Rufino/Big_Data_clientes_supermecado/blob/main/Desafio_Final_1_GetData.ipynb)
4. [O CÓDIGO PARA OTENÇÃO DOS DADOS DO GITHUB E DA MINERAÇÃO PODE SER OBTIDO AQUI](https://github.com/Antonio-Borges-Rufino/Big_Data_clientes_supermecado/blob/main/Desafio_Final_1_GetData.ipynb)
5. O SITE A BAIXO CONTEM A ESTRUTURA QUE FOI MINERADA PARA OBTENÇÃO DAS INFORMAÇÕES
![SITE](https://github.com/Antonio-Borges-Rufino/Big_Data_clientes_supermecado/blob/main/1.PNG)

### PASSO 2. PROCESSAMENTO.
1. ALGUNS DADOS DO DATASET DE COMPRAS ESTAVAM NULOS, NO CASO, PARTE DESSES DADOS PODERIAM SER TRATADOS E OUTRA PARTE NÃO.
2. TRATOU-SE OS DADOS VALOR_UNITARIO E VALOR_TOTAL_COMPRA, APESAR DE O COD_PRODUTO EM TESE PODER SER TRATADO, NÃO EXISTE GARANTIA QUE UM PRODUTO É ELE MESMO
A PARTIR DO SEU PREÇO, POR ISSO FOI APAGADO.
3. DEPOIS OS 4 DATASET FORAM UNIDOS EM UM ÚNICO DATASET GRANDE PARA OS PROCESSOS SEGUINTES
4. [CÓDIGO DE TRATAMENTO](https://github.com/Antonio-Borges-Rufino/Big_Data_clientes_supermecado/blob/main/transformacoes_1_df.ipynb)
5. [OS DATASETS TRATADOS PODEM SER OBTIDOS AQUI](https://github.com/Antonio-Borges-Rufino/Big_Data_clientes_supermecado/tree/main/df_tranformados)
