
# Análise dos Episódios de Breaking Bad

Este repositório apresenta uma análise exploratória e modelo de clusterização aplicado aos episódios da série de TV **Breaking Bad**. Através da análise de variáveis como avaliações no IMDb e audiência nos EUA, este projeto busca identificar padrões, agrupar episódios com características semelhantes e interpretar a recepção do público.

## Objetivos do Projeto
- Realizar uma análise exploratória detalhada dos episódios de Breaking Bad.
- Aplicar um modelo de aprendizado não supervisionado (K-Means) para agrupar episódios semelhantes.
- Interpretar os clusters para fornecer insights sobre a recepção do público e popularidade dos episódios.

## Descrição dos Dados
O conjunto de dados inclui as seguintes informações:
- **Temporada e Episódio**: Números correspondentes à temporada e ao episódio.
- **Título**: Título de cada episódio.
- **Duração**: Duração do episódio em minutos.
- **Avaliação IMDb**: Avaliações dos usuários do IMDb para cada episódio.
- **Audiência nos EUA (em milhões)**: Tamanho da audiência nos Estados Unidos.

## Estrutura do Projeto
- **`Enhanced_AnaliseExploratoria_BreakingBad.ipynb`**: Notebook Jupyter contendo EDA, visualizações, limpeza de dados, clusterização e interpretação dos clusters.
- **`breaking_bad_tv_show_all_seasons_episodes_data.csv`**: Arquivo de dados com informações detalhadas sobre cada episódio de Breaking Bad.
- **README.md**: Visão geral dos objetivos do projeto, descrição dos dados e instruções para execução da análise.

## Etapas da Análise
1. **Análise Exploratória (EDA)**: Exploração inicial dos dados para entender a estrutura e as principais estatísticas.
2. **Limpeza de Dados**: Tratamento de valores ausentes e padronização dos dados.
3. **Visualização**: Representações gráficas, incluindo gráficos de barras, dispersão e histogramas, ilustram distribuições e relações entre variáveis.
4. **Clusterização**: Aplicação do algoritmo K-Means nas variáveis de avaliação IMDb e audiência para agrupar episódios semelhantes.

## Tecnologias Utilizadas
- **Python**: Linguagem de programação utilizada para análise e modelagem.
- **pandas**: Manipulação e análise de dados.
- **matplotlib** e **seaborn**: Visualização de dados.
- **scikit-learn**: Pré-processamento e clusterização K-Means.

## Executando o Projeto
Para rodar este projeto localmente:
1. **Clone este repositório**: Use `git clone https://github.com/MarsoL4/breaking-bad-analysis.git`.
2. **Configure o ambiente**:
   - Certifique-se de ter Python e Jupyter Notebook instalados.
   - Instale as bibliotecas necessárias com o comando:
     ```bash
     pip install pandas matplotlib seaborn scikit-learn
     ```
3. **Abra e execute o Notebook**: Abra o arquivo `Enhanced_AnaliseExploratoria_BreakingBad.ipynb` no Jupyter Notebook ou Google Colab e execute cada célula na sequência.

Alternativamente, você pode utilizar [Google Colab](https://colab.research.google.com/) para executar o notebook diretamente no navegador.

---

Explore o notebook e sinta-se à vontade para personalizar a análise e descobrir novos insights!
