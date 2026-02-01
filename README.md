📊 Dashboard de Salários na Área de Dados

Este projeto é um dashboard interativo desenvolvido com Streamlit para explorar e visualizar tendências salariais globais na área de dados. Através de filtros dinâmicos e gráficos interativos, é possível analisar como a senioridade, o tipo de contrato e o tamanho da empresa influenciam a remuneração em dólares (USD).
🚀 Funcionalidades

    Filtros Dinâmicos: Filtre os dados por ano, nível de senioridade, tipo de contrato e tamanho da empresa.

    KPIs em Tempo Real: Visualização instantânea da média salarial, salário máximo, total de registros e o cargo mais frequente com base nos filtros aplicados.

    Visualizações Interativas:

        🏆 Top 10 cargos: Ranking dos cargos com as maiores médias salariais.

        📉 Distribuição Salarial: Histograma para entender a concentração das faixas de renda.

        🍩 Proporção de Trabalho Remoto: Gráfico de rosca mostrando a distribuição entre presencial, híbrido e remoto.

        🌍 Mapa Global: Visão geográfica do salário médio para Cientistas de Dados por país.

    Tabela de Dados: Acesso aos dados brutos filtrados para inspeção detalhada.

🛠️ Tecnologias Utilizadas

    Python

    Streamlit (Interface web)

    Pandas (Manipulação de dados)

    Plotly Express (Gráficos interativos)

🔧 Como Executar o Projeto

Para rodar este dashboard localmente, siga os passos abaixo:
1. Clone o repositório
Bash

git clone https://github.com/paula-maria/dashboard-streamlit.git
cd dashboard-streamlit

2. Crie um ambiente virtual (Opcional, mas recomendado)
Bash

python -m venv venv
# No Windows:
.\venv\Scripts\activate
# No macOS/Linux:
source venv/bin/activate

3. Instale as dependências
Bash

pip install streamlit pandas plotly

4. Execute a aplicação
Bash

streamlit run app.py

📂 Estrutura de Dados

O dashboard consome um arquivo CSV hospedado remotamente, contendo colunas como:

    ano: Ano da coleta.

    senioridade: Nível de experiência (ex: Júnior, Pleno, Sênior).

    contrato: Tipo de vínculo empregatício.

    usd: Salário anual convertido para dólares.

    residencia_iso3: Código do país para o mapeamento geográfico.
