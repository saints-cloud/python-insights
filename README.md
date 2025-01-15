# Python Insights - Analisando Dados com Python

## Case: Cancelamento de Clientes

Este projeto aborda a análise de dados em Python para identificar os principais motivos de cancelamento de clientes em uma base de dados com mais de 800 mil registros. O objetivo é entender os fatores que influenciam o cancelamento de clientes e propor ações que possam reduzir essa taxa, otimizando os resultados da empresa.

---

## Estrutura do Projeto

### Passos Realizados:
1. **Importação da Base de Dados**  
   Carregamos os dados de cancelamento em um arquivo CSV para análise.

2. **Visualização da Base de Dados**  
   Examinamos a estrutura dos dados para entender as colunas disponíveis e o tipo de informações que podemos analisar.

3. **Tratamento de Dados**  
   Realizamos a limpeza dos dados, removendo valores vazios e colunas irrelevantes para a análise.

4. **Análise Inicial**  
   Identificamos o número e o percentual de clientes que cancelaram o serviço.

5. **Análise Detalhada das Causas de Cancelamento**  
   Exploramos as colunas disponíveis, correlacionando-as com o cancelamento de clientes para identificar padrões.

---

## Resultados Obtidos

### Insights Principais:
1. **Duração do Contrato**  
   - Todos os clientes com assinatura mensal cancelaram.  
   - Ação recomendada: Incentivar contratos anuais e trimestrais, oferecendo descontos.

2. **Número de Ligações ao Call Center**  
   - Clientes que ligaram mais de 4 vezes cancelaram o serviço.  
   - Ação recomendada: Implementar um sistema de alerta ao atingir 3 ligações.

3. **Atrasos no Pagamento**  
   - Clientes com atraso superior a 20 dias cancelaram.  
   - Ação recomendada: Contatar clientes ao atingir 15 dias de atraso.

---

### Impacto das Ações Propostas:
1. **Evitar Contratos Mensais:**  
   Redução da taxa de cancelamento de **53% para 46%**.

2. **Gerenciar Ligações ao Call Center:**  
   Redução adicional de **46% para 23%**.

3. **Reduzir Atrasos no Pagamento:**  
   Redução final de **23% para 18%**.

---

## Ferramentas Utilizadas

- **Linguagem:** Python  
- **Bibliotecas:**
  - `pandas` para manipulação de dados.
  - `numpy` para cálculos numéricos.
  - `plotly` para visualização de dados.
  - `openpyxl` para suporte a arquivos Excel.
- **Ambiente:** Jupyter Notebook

---

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/saints-cloud/python-insights-cancelamento-clientes.git
