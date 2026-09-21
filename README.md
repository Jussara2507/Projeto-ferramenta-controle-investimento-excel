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
----

📊 App de Controle para Imposto de Renda
📝 Sobre o Projeto
Este projeto consiste em uma ferramenta desenvolvida em Microsoft Excel para auxiliar no controle e organização das informações financeiras necessárias para a declaração do Imposto de Renda.

O projeto foi construído como parte da resolução de um desafio prático da plataforma DIO (Digital Innovation One), aplicando conceitos de organização de dados, usabilidade e funções matemáticas para automação de rotinas administrativas e financeiras.

✨ Funcionalidades
A planilha foi estruturada com uma arquitetura de dados dividida em abas para separar responsabilidades e facilitar a manutenção:

👤 TITULAR: Interface para cadastro de dados pessoais utilizando validações lógicas booleanas (SIM/NÃO) para dependentes e residência no exterior.

🏦 INFORMES: Controle de rendimentos bancários com totalizadores automáticos e formatação contábil para facilitar a leitura.

🧾 NOTAS: Registro detalhado de entradas mês a mês (como Holerites, recebimentos de CNPJ e Freelance), contando com cálculo automático do Total de Entradas.

⚙️ TABELAS (Domínio): Aba dedicada a tabelas de domínio (como a lista oficial de bancos). Essa estrutura é utilizada para alimentar as listas suspensas (Validação de Dados) nas outras abas, garantindo a integridade dos dados inseridos e evitando erros de digitação.

🛠️ Tecnologias e Recursos Utilizados
Microsoft Excel:

* Fórmulas de soma e agregações.

* Validação de Dados (Listas Suspensas).

* Estruturação de dados relacionais entre abas.

* Formatação condicional e contábil.

🚀 Como Utilizar
1 - Faça o download do arquivo APP DE IMPOSTO DE RENDA - DIO.xlsx.

2 - Abra o arquivo no Microsoft Excel (ou similar).

3 - Preencha primeiramente a aba TITULAR com os dados principais.

4 - Utilize a aba INFORMES para adicionar os saldos e rendimentos bancários (selecionando as instituições financeiras na lista suspensa).

5 - Na aba NOTAS, lance suas receitas mensais detalhadas para que o totalizador calcule suas entradas automaticamente.

📸 Demonstração
<img width="1000" height="707" alt="Aba_Notas_IR" src="https://github.com/user-attachments/assets/91e20201-d07f-475a-bc4a-d262394aec9e" />


👩‍💻 Autora
Jussara Ferreira dos Santos
Estudante de Data Science e profissional de operações administrativas, comerciais e financeiras.

Seu LinkedIn: www.linkedin.com/in/jussara-ferreira-dos-santos-71903951

Seu GitHub: https://github.com/Jussara2507
