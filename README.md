RM98607 Lucas Vassão Braga
RM551305 Bryan Willian Messias Barbosa
# cp2-datascience
📊 Gerador de Relatórios de Análise de Dados
Um projeto Python para gerar relatórios detalhados de análise de dados em formato HTML, inspirado no Pandas Profiling.
📝 Descrição
Este projeto oferece uma ferramenta para análise automática de datasets, gerando relatórios HTML interativos com informações detalhadas sobre os dados, incluindo estatísticas básicas, análise de colunas e visualizações.
🚀 Funcionalidades

✨ Análise básica do DataFrame (número de linhas, colunas, memória utilizada)
📈 Análise detalhada de cada coluna

Tipo de dados
Contagem de valores nulos
Estatísticas descritivas para colunas numéricas
Contagem de valores únicos


🔄 Matriz de correlação para variáveis numéricas
📱 Relatório HTML responsivo e bem formatado

🛠️ Tecnologias Utilizadas

Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
Plotly

📦 Requisitos
bashCopypip install pandas numpy matplotlib seaborn plotly
💻 Como Usar

Clone o repositório:

bashCopygit clone [URL_DO_SEU_REPOSITORIO]

Instale as dependências:

bashCopypip install -r requirements.txt

Use o código em seu Jupyter Notebook ou script Python:

pythonCopyimport pandas as pd
from data_analysis_reporter import generate_data_analysis_report

# Carregue seus dados
df = pd.read_csv('seu_arquivo.csv')

# Gere o relatório
generate_data_analysis_report(df, 'relatorio.html')
📊 Exemplo de Uso com Atlantic Dataset
pythonCopyimport pandas as pd
from data_analysis_reporter import generate_data_analysis_report

# Carregando o dataset Atlantic
df = pd.read_csv('atlantic.csv')

# Gerando o relatório
resultado = generate_data_analysis_report(df, 'atlantic_report.html')
print(resultado)
🎯 Estrutura do Projeto
Copy📦 projeto-analise-dados
 ┣ 📜 data_analysis_reporter.py   # Código principal
 ┣ 📜 requirements.txt            # Dependências do projeto
 ┣ 📜 README.md                   # Este arquivo
 ┗ 📜 exemplo_notebook.ipynb      # Notebook com exemplos de uso
👥 Equipe

[Nome do Aluno 1] - [Função/Responsabilidade]
[Nome do Aluno 2] - [Função/Responsabilidade]
[Nome do Aluno 3] - [Função/Responsabilidade]

