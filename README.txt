FLUXO DE PROCEDIMENTOS - EXPLORAÇÃO DE DADOS

1-Identificação do número de linhas e colunas
    df.shape
2-Identificação das caracteristicas: categóricas ou numéricas
3-Identificação da ausnêcia de dados
4-Verificação de valores exclusivos
    df.['column'].nunique()
5-listagem de valores explusivos e sua frequência
    contagem_valores = df.['ID'].value_counts()
6-listagem de valores duplicados e sua frequência
    contagem_valores.value_couts()
7-aplicação de mascaras booleana para identificação dos dados de acordo com a frequência
    mascara_fre = contagem_valores == frequencia de ocorrência
8-usa a mascaralógica como seleção
    contagem_mascarada = contagem_valores.index[mascara_fre]
9-converte contagem_mascara em uma lista
    contagem_mascarada =list(contagem_mascarada)
    

