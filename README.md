# 📊 Ferramenta de Controle e Simulação de Investimentos em Excel

Projeto desenvolvido como parte do desafio prático da plataforma **DIO (Digital Innovation One)**, com foco em simulação de investimentos em Fundos Imobiliários (FIIs) e planejamento financeiro.

---

## 🎯 Objetivos do Projeto
* Criar uma ferramenta dinâmica de simulação de patrimônio acumulado ao longo do tempo.
* Calcular projeções de dividendos mensais com base em taxas de rendimento configuráveis.
* Automatizar a recomendação de alocação de carteira de FIIs por perfil de investidor (Conservador, Moderado, Agressivo).

---

## 🛠️ Recursos e Funções do Excel Utilizados
* **Funções Financeiras:** `=FV()` / `=VF()` para cálculo de valor futuro de aportes recorrentes.
* **Busca e Referência:** `=VLOOKUP()` / `=PROCV()` com chave composta (`Perfil-Tipo`) para busca dinâmica de percentuais.
* **Intervalos Nomeados:** Simplificação de fórmulas usando nomes amigáveis para células e limites.
* **Organização Estruturada:** Separação entre a camada visual de usuário (`APP`) e a tabela de dados (`Chave_Composta`).

---

## 📁 Estrutura do Repositório
* `DESAFIO DIO EXCEL.xlsx`: Planilha principal com simulações e cálculos automatizados.
* `README.md`: Documentação técnica do projeto.
