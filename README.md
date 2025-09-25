# Análise de Dados de Seguros - Projeto de Portfólio

![Status](https://img.shields.io/badge/status-concluído-brightgreen)

Uma análise exploratória de dados (EDA) sobre uma base de dados fictícia de uma companhia de seguros, com o objetivo de extrair insights sobre o perfil dos clientes, a performance financeira dos produtos e os padrões de sinistros.

---

### 📂 Tabela de Conteúdos
1. [Objetivo do Projeto](#objetivo-do-projeto)
2. [Sobre o Dataset](#sobre-o-dataset)
3. [Ferramentas Utilizadas](#ferramentas-utilizadas)
4. [Estrutura da Análise](#estrutura-da-análise)
5. [Principais Análises e Insights](#principais-análises-e-insights)
6. [Como Executar o Projeto](#como-executar-o-projeto)
7. [Conclusão e Próximos Passos](#conclusão-e-próximos-passos)
8. [Autor](#autor)

---

### 🎯 Objetivo do Projeto
O objetivo principal deste projeto é realizar uma análise exploratória para identificar o perfil dos clientes, entender a performance financeira das apólices e investigar os padrões de sinistros (claims) para encontrar potenciais áreas de risco e oportunidade para a seguradora.

---

### 📊 Sobre o Dataset
O dataset utilizado é um ficheiro `InsuranceData.csv` fictício que contém informações sobre apólices de seguro. As principais colunas incluem:
* **Informações do Cliente:** `CustomerID`, `Gender`, `Age`
* **Detalhes da Apólice:** `Policy Type`, `Policy Start Date`, `Policy End Date`, `Premium Amount`, `Coverage Amount`
* **Detalhes do Sinistro:** `Claim Number`, `Claim Date`, `Claim Amount`, `Claim Status`

---

### 🛠️ Ferramentas Utilizadas
* **Linguagem de Programação:** Python
* **Bibliotecas de Análise:** Pandas, NumPy
* **Bibliotecas de Visualização:** Matplotlib, Seaborn
* **Ambiente:** Jupyter Notebook

---

### 📈 Estrutura da Análise
A análise foi dividida em três etapas principais, seguindo um roteiro lógico para extrair insights progressivamente mais profundos:

1.  **Limpeza e Pré-processamento:** Tratamento de dados ausentes, correção de tipos de dados e padronização dos nomes das colunas.
2.  **Análise do Perfil do Cliente:** Investigação sobre as características demográficas (idade, gênero) e as preferências de produtos dos clientes.
3.  **Análise Financeira:** Avaliação da receita (prêmios) e custos (sinistros) para determinar a lucratividade de cada tipo de apólice.
4.  **Análise de Sinistros:** Análise da distribuição dos status de sinistros e investigação sobre as taxas de rejeição por tipo de produto.

---

### 💡 Principais Análises e Insights

#### 1. Perfil do Cliente
A análise demográfica revelou um público diversificado. A distribuição de gênero é bastante equilibrada, e a faixa etária dos clientes concentra-se principalmente entre os 30 e 60 anos.

<img width="854" height="549" alt="Image" src="https://github.com/user-attachments/assets/e73a3ca7-bc5c-4454-b3cb-3f50df469a8b" />

O tipo de apólice mais popular é a de **Viagem (Travel)**, seguida de perto pela de **Saúde (Health)**. Ao analisar por gênero, não foram observadas diferenças significativas nas preferências, indicando um apelo de produto similar para ambos os públicos.

<img width="1025" height="628" alt="Image" src="https://github.com/user-attachments/assets/c4bc6b45-e94a-48ec-aedf-ba0e8d43d5d3" />
<img width="1025" height="628" alt="Image" src="https://github.com/user-attachments/assets/4633dc5b-93fc-4e9c-8e38-57eaa905204d" />]*

#### 2. Análise Financeira e de Lucratividade
Embora a apólice de **Viagem** seja a que gera mais **receita** bruta, a análise de **lucratividade** (Receita - Custos) revelou que a apólice de **Saúde** é a mais lucrativa para a empresa. Isso ocorre porque, proporcionalmente, os custos com sinistros de viagem são mais elevados.

<img width="999" height="656" alt="Image" src="https://github.com/user-attachments/assets/c580d547-7719-4471-81af-a36e79884c98" />
<img width="988" height="656" alt="Image" src="https://github.com/user-attachments/assets/8d442354-4ae0-4753-8bc3-6c3fb17dc03d" />
<img width="1001" height="656" alt="Image" src="https://github.com/user-attachments/assets/74a8d9ac-c9b2-445c-af8e-13c37fcb5c50" />

Este insight é crucial, pois sugere que a empresa poderia focar em estratégias para aumentar as vendas de apólices de Saúde ou revisar a estrutura de preços e riscos das apólices de Viagem.

#### 3. Análise de Sinistros e Risco
A maioria dos sinistros são pagos (`Settled`), o que indica uma boa eficiência operacional. No entanto, a análise aprofundada revelou um ponto de atenção: a **taxa de rejeição (`Rejected`) para apólices de Viagem é desproporcionalmente maior** em comparação com outros produtos.

<img width="1160" height="733" alt="Image" src="https://github.com/user-attachments/assets/0863814d-9a7a-43ce-8d2a-6f1ad22f20e8" />
<img width="794" height="660" alt="Image" src="https://github.com/user-attachments/assets/ea0b7f1c-98bf-4e6f-a108-af2baf6246e4" />

Isso pode indicar uma de duas coisas: ou os critérios para sinistros de viagem são excessivamente rigorosos, gerando insatisfação nos clientes, ou este produto atrai um número maior de tentativas de fraude. Esta é uma área que merece uma investigação mais aprofundada pela equipe de risco.

---

🚀 Como Executar o Projeto
Existem algumas maneiras de interagir com este projeto:

1. Visualizar o Notebook no GitHub
Você pode visualizar o código e todos os resultados diretamente no GitHub, que renderiza os ficheiros Jupyter Notebook de forma interativa.

➡️ Visualizar o Notebook de Análise

2. Executar no Google Colab
Para uma experiência totalmente interativa onde você pode executar o código, modificar e experimentar sem precisar de qualquer instalação, use o link abaixo para abrir o projeto no Google Colab.
Link: https://colab.research.google.com/drive/1785ZrW6L9ER5m3Vkh-byrsLninGiEwgz?usp=sharing
3. Fazer um Fork do Repositório
Se você quiser criar a sua própria versão deste projeto, modificá-lo ou contribuir, a melhor forma é fazer um "fork". Um fork é uma cópia do repositório para a sua própria conta do GitHub.

🍴 Fazer um Fork deste Projeto

---

### 🏁 Conclusão e Próximos Passos
Esta análise exploratória forneceu uma visão 360º do negócio de seguros, gerando insights acionáveis sobre clientes, produtos e riscos.

**Como próximos passos, sugere-se:**
* **Análise Preditiva:** Criar um modelo de Machine Learning para prever a probabilidade de um sinistro ser rejeitado.
* **Análise de Churn:** Investigar os fatores que levam um cliente a não renovar a sua apólice.
* **Segmentação de Clientes:** Utilizar algoritmos de clusterização para encontrar diferentes perfis de clientes e criar estratégias de marketing personalizadas.

---

### 👨‍💻 Autor

**[Camila Merli**

* **LinkedIn:** [https://www.linkedin.com/in/camila-merli-pedrosa/]
* **GitHub:** [https://github.com/CamilaMerli]
* **Email:** [millamerli@gmail.com]
