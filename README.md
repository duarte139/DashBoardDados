# DashBoardDados
# 📊 Data Analysis & Interactive Dashboard

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-1.28-FF4B4B)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458)
![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow)

Um projeto de análise de dados completo que transforma datasets brutos em insights visuais. Esta aplicação utiliza **Python** para processamento de dados e **Streamlit** para criar uma interface interativa web, permitindo a exploração dinâmica de gráficos gerados com **Plotly**, **Seaborn** e **Matplotlib**.

[🚀 Clique aqui para acessar o Dashboard em tempo real](https://dashboarddados-alura2026.streamlit.app/)

---

## 🚀 Funcionalidades

- **Upload de Dados:** Suporte para carregamento de arquivos CSV ou Excel.
- **Filtragem Interativa:** Sidebar lateral para filtrar dados por categorias, datas ou valores.
- **Visualização Estática:** Gráficos exploratórios detalhados com Seaborn e Matplotlib.
- **Visualização Interativa:** Gráficos dinâmicos (zoom, hover) utilizando Plotly.
- **Relatórios Automatizados:** Exibição de estatísticas descritivas (média, mediana, desvio padrão) em tempo real.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes bibliotecas:

- **[Python](https://www.python.org/):** Linguagem base.
- **[Pandas](https://pandas.pydata.org/):** Manipulação e limpeza de dados.
- **[Streamlit](https://streamlit.io/):** Framework para criação do dashboard interativo.
- **[Plotly](https://plotly.com/python/):** Criação de gráficos interativos.
- **[Seaborn](https://seaborn.pydata.org/) & [Matplotlib](https://matplotlib.org/):** Visualizações estatísticas estáticas.

---

## 📂 Estrutura do Projeto

```text
├── data/                   # Diretório para armazenar datasets (ex: .csv, .xlsx)
├── notebooks/              # Jupyter Notebooks para análise exploratória preliminar
├── src/                    # Código fonte
│   ├── app.py              # Arquivo principal da aplicação Streamlit
│   └── utils.py            # Funções auxiliares de processamento
├── requirements.txt        # Lista de dependências
├── README.md               # Documentação do projeto
└── .gitignore              # Arquivos ignorados pelo Git
⚙️ Instalação e Configuração
Siga os passos abaixo para rodar o projeto localmente:

1. Clone o repositório
Bash
git clone [https://github.com/seu-usuario/nome-do-projeto.git](https://github.com/seu-usuario/nome-do-projeto.git)
cd nome-do-projeto
2. Crie um ambiente virtual (Opcional, mas recomendado)
Bash
# Windows
python -m venv venv
.\venv\Scripts\activate

# Linux/Mac
python3 -m venv venv
source venv/bin/activate
3. Instale as dependências
Bash
pip install -r requirements.txt
Nota: Certifique-se de que o arquivo requirements.txt contenha: pandas, streamlit, seaborn, matplotlib, plotly

🖥️ Como Executar
Para iniciar o dashboard no seu navegador, execute o comando:

Bash
streamlit run src/app.py
O terminal exibirá o endereço local (geralmente http://localhost:8501) onde você pode acessar a aplicação.

📊 Exemplos de Uso
Carregue seu arquivo: Clique no botão "Upload" e selecione seu dataset .csv.

Selecione as colunas: Escolha quais colunas deseja analisar no menu lateral.

Escolha o tipo de gráfico: Alterne entre histogramas, gráficos de dispersão ou linhas.

Exportar: Baixe os dados filtrados ou os gráficos gerados.

🤝 Contribuição
Contribuições são bem-vindas! Siga os passos:

Faça um Fork do projeto.

Crie uma Branch para sua feature (git checkout -b feature/nova-feature).

Faça o Commit (git commit -m 'Adicionando nova feature').

Faça o Push (git push origin feature/nova-feature).

Abra um Pull Request.

📝 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.


