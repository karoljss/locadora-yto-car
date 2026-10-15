# 🚗 Yto Car — Sistema de Locação de Veículos & Analytics

Este projeto foi desenvolvido como um estudo de caso prático / projeto acadêmico durante o curso de [Nome do Curso ou Instituição], com o objetivo de aplicar conceitos de Engenharia de Requisitos, Modelagem UML e Visualização de Dados / BI.

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![UML](https://img.shields.io/badge/UML-Modelagem-blue?style=for-the-badge)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-Business_Intelligence-green?style=for-the-badge)

## 📌 Visão Geral do Projeto
Este projeto une **Engenharia de Software (Modelagem de Requisitos com UML)** e **Business Intelligence / Data Analytics**. A solução aborda desde o levantamento das regras de negócio do minimundo operacional de uma locadora de veículos até a construção de dashboards interativos e análises preditivas para tomada de decisão gerencial.

---

## 🛠️ 1. Engenharia de Requisitos & Modelagem UML
A partir das entrevistas operacionais com a locadora, mapeou-se a arquitetura de processos e casos de uso do sistema:

### Atores e Casos de Uso (UML)
- **Cliente:** Consulta de veículos disponíveis (por categoria: Luxo, Normal e Popular) e solicitação remota de prorrogação de contrato.
- **Funcionário:** Realização do cadastro de novos veículos, controle presencial/sistêmico de locação e registro das devoluções.

### Especificação de Casos de Uso (Padrão Bezerra, 2015)
- `UC01` - Consultar Veículos Disponíveis
- `UC02` - Prorrogar Aluguel
- `UC03` - Registrar Aluguel de Veículo *(Regra: Limite de 1 veículo por cliente por vez)*
- `UC04` - Registrar Devolução de Veículo
- `UC05` - Cadastrar Veículo

---

## 📊 2. Dashboard de Business Intelligence & Preditiva

Com base nas transações do sistema, foi desenvolvido um painel interativo estruturado em visão gerencial e operacional:

### 📈 Indicadores Chave (KPIs)
- **Faturamento Total:** R$ 81,43 Mil
- **Ticket Médio por Cliente:** R$ 5,19 Mil
- **Média de KM:** 1,36 Mil
- **Total de Clientes Ativos:** 27 cadastrados (30 no total consultado)

### 🔍 Funcionalidades do Dashboard
1. **Controle Gerencial & Visão Financeira:**
   - Evolução anual e sazonal do faturamento (% e valor absoluto).
   - Análise por dia da semana (picos de locação/faturamento).
2. **Controle de Cadastro & Categorização:**
   - Proporção de locações por categoria (Luxo, Light/Popular, etc.).
   - Segmentação de clientes cadastrados vs. não cadastrados para identificação de inconsistências cadastrais.
3. **Análise Preditiva & Previsão de Vendas:**
   - Projeção de tendência de faturamento futuro utilizando técnicas de análise de séries temporais.
4. **Consulta e Filtros Dinâmicos:**
   - Segmentação por Ano, Modelo, Situação, Marca e Dia da Semana.
   - Ferramenta de busca e consulta por placas de veículos.

---

## 💻 Tecnologias Utilizadas
- **Modelagem de Sistemas:** UML, PlantUML, Engenharia de Requisitos (Bezerra, 2015)
- **BI & Visualização de Dados:** Power BI, DAX, Power Query
- **Análise Preditiva:** Recursos nativos de forecasting do Power BI
