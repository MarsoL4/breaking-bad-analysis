
# Análise dos Episódios de Breaking Bad

Este projeto apresenta uma análise exploratória e aplicação de clusterização nos episódios da popular série **Breaking Bad**. Através da análise de variáveis como avaliações no IMDb e audiência nos Estados Unidos, buscamos identificar padrões e agrupar episódios com características semelhantes.

## Objetivos do Projeto
- Realizar uma análise exploratória detalhada dos episódios de Breaking Bad.
- Aplicar um modelo de aprendizado não supervisionado (K-Means) para agrupar episódios semelhantes.
- Interpretar os clusters para fornecer insights sobre a recepção do público e popularidade dos episódios.

## Descrição dos Dados
O conjunto de dados inclui informações sobre:
- **Temporada e Episódio**: Números da temporada e do episódio.
- **Título**: Título de cada episódio.
- **Duração**: Duração do episódio em minutos.
- **Avaliação IMDb**: Avaliações de usuários do IMDb.
- **Audiência nos EUA (em milhões)**: Tamanho da audiência nos Estados Unidos.

## Etapas da Análise
1. **Análise Exploratória (EDA)**: Exploração inicial dos dados para entender a estrutura e estatísticas principais do conjunto de dados.
2. **Limpeza de Dados**: Tratamento de valores ausentes e padronização dos dados para análise.
3. **Visualização**: Gráficos de barras, dispersão e histogramas para ilustrar distribuições e relações entre as variáveis.
4. **Clusterização**: Aplicação de K-Means nas variáveis de avaliação IMDb e audiência para agrupar episódios semelhantes.

## Tecnologias Utilizadas
- **Python**: Linguagem de programação principal.
- **pandas**: Manipulação e análise de dados.
- **matplotlib** e **seaborn**: Visualização de dados.
- **scikit-learn**: Pré-processamento e clusterização K-Means.

## Executando o Projeto
Para rodar este projeto localmente:
1. Verifique que você possui Python e Jupyter Notebook instalados.
2. Clone o repositório e navegue até a pasta do projeto.
3. Abra o arquivo do Jupyter Notebook (`AnaliseExploratoria_BreakingBad.ipynb`) e execute as células em sequência.

Alternativamente, você pode utilizar o [Google Colab](https://colab.research.google.com/) para executar o notebook diretamente no navegador.

---

Explore o notebook e sinta-se à vontade para modificar a análise e descobrir novos insights!
