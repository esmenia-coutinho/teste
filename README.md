Neste projeto, 

Abordamos o negocio de Financas e produzimos um pipeline com aplicacao de arquitetura Medallion.

A fonte de dados de origem seriam arquivos csv:
- pessoas.csv 
- fcx.csv

Utilizamos:
- Python
- VsCode

Organizacão de arquivos:
- Pandas_1: Processo de Ingestão de dados. Limpeza de dados. Produzindo uma saída de dados tratados a partir da leitura de dados da origem em arquivos csv.
- Pandas_2: Configuracão da arquitetura Medallion, organizando o processo em camadas Bronze, Silver e Gold. Produzindo saída de dados em formato de arquivo parquet,
particionados por Mês/Ano.

Utilizacao da biblioteca Pandas, para realizar a tratativa e Manipulacao de dados, como:
- Limpeza de dados
- Dados duplicados
- Dados faltantes
- Dados errados

  Utilizando a Arquitetura Medallian, para producao do pipeline:

  ![Esmenia LakeHouse](https://github.com/user-attachments/assets/e3c97f53-c3f4-4cbf-9c6b-596a0e8519f4)
