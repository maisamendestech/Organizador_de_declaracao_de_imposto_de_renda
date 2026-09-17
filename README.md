# 🦁 LION — Organizador de Declaração de Imposto de Renda

[![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/microsoft-365/excel)
[![DIO](https://img.shields.io/badge/DIO-Desafio%20de%20Código-7B2CBF?style=for-the-badge)](https://www.dio.me/)
[![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)](#)

> 📊 Uma ferramenta de organização e conferência de informações para auxiliar na preparação dos dados necessários à declaração de Imposto de Renda, desenvolvida em Excel.

---

## 📖 Sobre o projeto

O **LION** é uma ferramenta desenvolvida durante o desafio **"Criando um Organizador de Declaração de Imposto de Renda"**, da formação **Análise de Dados com Excel e IA da DIO (Digital Innovation One)**.

O projeto foi desenvolvido com o objetivo de praticar a utilização do Excel na organização de informações financeiras e pessoais, criando uma estrutura centralizada para reunir dados do titular, informes de rendimentos bancários, entradas financeiras e documentos relacionados.

Além da proposta original do desafio, a ferramenta recebeu uma **organização visual própria**, incluindo um **Painel de Conferência**, indicadores automáticos de preenchimento, validações de dados, verificações  e elementos gráficos para facilitar a identificação de informações pendentes e tornar a utilização mais organizada e intuitiva.

---

## 🎯 Objetivo

O objetivo do LION é facilitar a **organização, conferência e visualização das informações** utilizadas como base para a preparação da declaração de Imposto de Renda.

A ferramenta permite reunir em um único arquivo informações como:

* Dados pessoais do titular;
* Informações bancárias;
* Valores atuais de diferentes bancos;
* Documentos e anexos relacionados aos informes;
* Entradas financeiras mensais;
* Categorias das receitas;
* Status de preenchimento das informações.

> ⚠️ O LION é uma ferramenta de organização e conferência de dados. Ele não substitui a declaração oficial do Imposto de Renda, orientações da Receita Federal ou a análise de um profissional especializado.

---

## 🚀 Funcionalidades

* 👤 Cadastro dos dados do titular;
* 🧾 Registro de CPF, data de nascimento, título de eleitor e endereço;
* 📱 Cadastro de telefone, celular e e-mail;
* 👥 Registro de informações sobre cônjuge e dependente;
* 🌎 Indicação de residência no exterior;
* 🔄 Indicação de alterações em relação à entrega anterior;
* 🏦 Cadastro de até 3 bancos;
* 💰 Registro do valor atual informado por cada banco;
* 📎 Identificação dos documentos anexados aos informes;
* 🧮 Cálculo automático do total dos valores bancários;
* 📅 Registro de entradas financeiras por data;
* 🗂️ Classificação das entradas por categoria;
* 💵 Cálculo automático do total das entradas;
* 📊 Contagem das entradas cadastradas;
* 📄 Contagem dos documentos informados;
* ✅ Verificação automática do preenchimento das informações;
* 🔎 Identificação de campos que precisam ser conferidos;
* 📋 Listas suspensas para padronização dos dados;
* 📌 Tabela de apoio com instituições bancárias.

---

### ✅ Verificação automática

Foram adicionadas fórmulas utilizando funções como:

* `IF()`
* `AND()`
* `COUNTA()`
* `COUNT()`
* `SUM()`

Essas funções permitem verificar automaticamente determinadas condições do preenchimento e apresentar mensagens como:

**OK**
ou
**VERIFICAR**

### 📋 Validação de dados

Foram utilizadas listas suspensas para reduzir erros de preenchimento e manter os dados padronizados.

Entre elas estão:

* `SIM / NÃO` para informações do titular;
* `HOLERITE / CNPJ / FREELANCE` para classificação das entradas.

### 🧮 Resumos automáticos

Além da estrutura original, foram criados cálculos automáticos para consolidar os dados inseridos pelo usuário.

Dessa forma, alterações realizadas nas abas de cadastro são refletidas automaticamente no painel de conferência.

---

## 📊 Estrutura do projeto

O LION está dividido nas seguintes abas:

| Aba             | Função                                         |
| --------------- | ---------------------------------------------- |
| 👤 **TITULAR**  | Cadastro das informações pessoais              |
| 🏦 **INFORMES** | Registro dos informes de rendimentos bancários |
| 💰 **NOTAS**    | Registro das entradas financeiras              |
| 📊 **PAINEL**   | Conferência automática das informações         |
| 📋 **TABELAS**  | Base de dados utilizada nas listas de seleção  |

---

## 🛠️ Tecnologias e recursos utilizados

* Microsoft Excel
* Fórmulas e funções do Excel
* Validação de dados
* Listas suspensas
* Tabelas de apoio
* Cálculos automáticos
* Organização e tratamento de dados
* Formatação personalizada
* Painel de conferência
* Fórmulas condicionais

### Principais funções utilizadas

* `SUM()`
* `COUNT()`
* `COUNTA()`
* `IF()`
* `AND()`

---

## 💻 Conceitos praticados

Durante o desenvolvimento do projeto foram aplicados conceitos de **Excel, organização de dados e automação de informações**, incluindo:

* Cadastro estruturado de informações;
* Organização de dados pessoais e financeiros;
* Cálculos automáticos;
* Consolidação de informações;
* Validação de dados;
* Criação de listas suspensas;
* Utilização de tabelas de apoio;
* Verificação automática de preenchimento;
* Criação de indicadores;
* Utilização de funções condicionais;
* Construção de um painel de conferência;
* Organização visual de uma ferramenta em Excel;
* Melhoria da experiência de utilização da planilha.

---

### Visão geral

O LION possui uma estrutura organizada para centralizar informações necessárias à preparação dos dados do Imposto de Renda.

O usuário pode preencher as informações nas diferentes etapas e utilizar o **Painel de Conferência** para verificar automaticamente o preenchimento dos principais campos.

> 💡 Para visualizar a ferramenta em funcionamento, abra o arquivo Excel disponível neste repositório.

---

## 🧮 Fluxo de utilização

O funcionamento da ferramenta pode ser resumido da seguinte forma:

**Dados do Titular → Informes Bancários → Entradas Financeiras → Painel de Conferência**

Após o preenchimento das informações, o painel consolida os principais dados e realiza verificações automáticas para indicar possíveis pendências.

---

## 📚 Aprendizados

O desenvolvimento deste projeto contribuiu para o aprofundamento dos conhecimentos em **Excel aplicado à organização e análise de dados**.

Durante o projeto, pratiquei a criação de cálculos automáticos, validação de dados, utilização de listas suspensas, organização de tabelas e construção de verificações condicionais.

compreendi como diferentes recursos do Excel podem ser combinados para transformar uma planilha em uma ferramenta mais interativa e funcional.

Também foi possível trabalhar conceitos de **usabilidade, organização visual e automação**, buscando melhorar a experiência de utilização em relação à estrutura inicial fornecida no desafio.

---

## ⭐ Diferenciais do projeto

Além da implementação proposta no desafio, o LION recebeu algumas personalizações:

* 🦁 Identidade visual própria;
* 📊 Criação de um Painel de Conferência;
* ✅ Verificação automática do preenchimento;
* 🔎 Identificação de informações que precisam ser conferidas;
* 📄 Contagem automática de documentos informados;
* 💰 Totalização automática das entradas;
* 🏦 Totalização dos valores dos informes bancários;
* 📋 Listas suspensas para padronização dos dados;
* 🗂️ Organização própria das informações;
* 🎨 Personalização visual da ferramenta;
* 🔄 Integração entre as abas através de fórmulas.

Essas adaptações foram realizadas com o objetivo de ampliar a proposta original do desafio e transformar a planilha em uma ferramenta mais completa para **organização e conferência das informações**.

---

## 👨‍🏫 Créditos

Projeto desenvolvido como exercício prático durante o desafio **"Criando um Organizador de Declaração de Imposto de Renda"**, da formação **Análise de Dados com Excel e IA da DIO (Digital Innovation One)**.

🔗 Acesse o desafio na DIO: https://web.dio.me/lab/criando-um-organizador-de-declaracao-de-imposto-de-renda/learning/90d084ed-a8d3-4b51-bd8e-fa6b605f7d91

> 💡 A estrutura de organização, Painel de Conferência, validações, verificações automáticas e demais personalizações foram desenvolvidos como parte da resolução e aprimoramento do desafio.

---

## 📄 Licença

Este projeto foi desenvolvido para fins de **estudo, aprendizado e desenvolvimento de portfólio**.

---

## 🌐 Acesse o projeto

🦁 **LION — Organizador de Declaração de Imposto de Renda com Excel**

O arquivo Excel está disponível neste repositório.

---

### 👩‍💻 Desenvolvido por Maisa Mendes

[![GitHub](https://img.shields.io/badge/GitHub-maisamendestech-181717?style=for-the-badge&logo=github)](https://github.com/maisamendestech)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Maisa%20Mendes-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/maisa-mendes-1316a3394/)

