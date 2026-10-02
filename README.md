# 📊 Análise de Impacto Logístico e Satisfação do Cliente em E-commerce

Projeto de portfólio desenvolvido para simular a resolução de um problema real de negócio na área de **Ciência e Análise de Dados**, aplicando manipulação de dados com Pandas, engenharia de atributos e visualizações estatísticas.

---

## 🎯 1. O Problema de Negócio
No ecossistema de e-commerce, a experiência do cliente está diretamente ligada à eficiência logística. A diretoria de operações identificou reclamações recorrentes sobre prazos de entrega e precisa responder às seguintes perguntas:
* Qual é o impacto real dos dias de atraso nas notas de avaliação (*review scores*) dadas pelos clientes?
* Como os atrasos logísticos afetam drasticamente a retenção e a satisfação do consumidor?

---

## 🛠️ 2. Tecnologias Utilizadas
* **Python 3.13**
* **Pandas & NumPy:** Para simulação, tratamento, limpeza e cruzamento (*merge*) das bases de dados relacionais de pedidos e avaliações.
* **Matplotlib & Seaborn:** Para criação de gráficos estatísticos e análise exploratória de dados (EDA).

---

## 📈 3. Metodologia e Desenvolvimento
1. **Simulação de Dados Corporativos:** Criação de datasets relacionais simulando pedidos (`orders`) e avaliações de clientes (`reviews`), contendo custos de frete, valores de pedidos, dias de atraso e notas de 1 a 5.
2. **Cruzamento de Tabelas (Merge):** União das bases de dados utilizando chaves relacionais (`order_id`) para consolidar a visão do cliente.
3. **Análise Descritiva e Agrupamentos:** Cálculo das médias de notas por dias de atraso, evidenciando a queda abrupta na satisfação conforme o prazo de entrega falha.

---

## 📊 4. Principais Insights de Negócio
* **Entregas no Prazo ou Adiantadas:** Mantêm uma nota média excelente, variando entre **4.6 e 4.7 estrelas**.
* **Atrasos Leves (1 a 2 dias):** Causam uma queda brusca na satisfação, despencando para cerca de **2.8 estrelas**.
* **Atrasos Críticos (5 a 10 dias):** Levam a insatisfação ao limite, com notas médias despencando para **1.0 a 1.2 estrelas**.

---

## 🚀 5. Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone [https://github.com/pmiqueta-oss/seu-repositorio.git](https://github.com/pmiqueta-oss/seu-repositorio.git)
