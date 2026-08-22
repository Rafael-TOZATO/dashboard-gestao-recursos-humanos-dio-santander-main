# Dashboard de Gestão de Recursos Humanos

Projeto desenvolvido em Power BI no contexto do desafio da DIO em parceria com o Santander.

O projeto tem como objetivo transformar dados estruturados de Recursos Humanos em indicadores e análises visuais para apoio à tomada de decisão.

---

## 🛠️ Jornada de Desenvolvimento e Configuração do Ambiente

Este repositório documenta não apenas a entrega técnica do painel, mas também a resolução autônoma de desafios de infraestrutura e versionamento:

**Organização Inicial:** Estruturação local dos diretórios e artefatos do projeto em pastas para garantir a integridade dos arquivos.

**Adaptação de Ferramentas:** Utilização do editor integrado IBM Bob para conduzir a estruturação do código e dos fluxos de trabalho.

**Superação de Barreiras de Permissão:** Identificação de restrições de escrita no sistema de arquivos e ajuste de permissões para desbloquear a edição direta do arquivo de documentação (`README.md`).

**Instalação e Configuração de Controle de Versão:** 

Instalação autônoma do utilitário Git for Windows, configuração de identidade de usuário e e-mail via terminal integrado, realização de commits e publicação estruturada diretamente para o GitHub.

---

## Objetivo

Desenvolver um dashboard de Gestão de Recursos Humanos utilizando Power BI, contemplando tratamento, modelagem, relacionamento e análise dos dados.

O projeto demonstra a aplicação prática de conceitos de Business Intelligence, modelagem de dados, Power Query, DAX e visualização de informações.

---

## Dashboard

O dashboard foi desenvolvido em página única, com foco em uma apresentação objetiva dos principais indicadores de Recursos Humanos.

### Indicadores principais

- Total de empregados
- Total de departamentos
- Total de projetos
- Total de dependentes
- Total de horas trabalhadas

### Análises desenvolvidas

- Empregados por departamento
- Horas trabalhadas por projeto
- Dependentes por empregado
- Salário por departamento e sexo

---

## Modelo de dados

O projeto utiliza um modelo relacional estruturado a partir de tabelas de Recursos Humanos.

Entre as entidades utilizadas estão:

- Employee
- Department
- Department Locations
- Project
- Works
- Dependent

Os relacionamentos foram configurados no modelo do Power BI para permitir a integração das informações e a construção das análises.

---

## Tratamento dos dados

O tratamento dos dados foi realizado utilizando o Power Query.

Foram executadas etapas como:

- verificação das estruturas das tabelas;
- definição dos tipos de dados;
- conversão de campos numéricos;
- configuração de campos de texto;
- configuração de campos de data;
- verificação de identificadores;
- preparação das tabelas para o modelo;
- validação dos relacionamentos;
- aplicação das alterações no modelo.

---

## 💡 Próximos Passos

- Implementação de medidas DAX avançadas para indicadores preditivos.
- Criação de documentação complementar de validação de dados (QA).

## Modelagem

A modelagem foi estruturada considerando as relações entre empregados, departamentos, projetos, atividades e dependentes.

Entre os principais relacionamentos utilizados estão:

- Employee → Works
- Department → Employee
- Department → Department Locations
- Project → Works
- Employee → Dependent

A configuração dos relacionamentos permitiu utilizar as informações de diferentes tabelas de forma integrada no dashboard.

---

## Indicadores apresentados

| Indicador | Resultado |
|---|---:|
| Total de empregados | 8 |
| Total de departamentos | 3 |
| Total de projetos | 6 |
| Total de dependentes | 7 |
| Total de horas trabalhadas | 2 mil |

---

## Visualizações

### Empregados por Departamento

Apresenta a distribuição dos empregados entre os departamentos da organização.

### Horas Trabalhadas por Projeto

Apresenta a quantidade de horas registradas para cada projeto.

### Dependentes por Empregado

Apresenta a distribuição dos dependentes associados aos empregados.

### Salário por Departamento e Sexo

Permite comparar a distribuição salarial entre departamentos e segmentos por sexo.

---

## Tecnologias e ferramentas

- Power BI Desktop
- Power Query
- DAX
- MySQL
- XAMPP
- phpMyAdmin
- Excel
- GitHub

---

## Contexto do projeto

Projeto desenvolvido como parte de uma atividade prática da plataforma DIO, em parceria com o Santander.

A atividade teve como foco o desenvolvimento de uma solução de análise de dados utilizando Power BI, envolvendo preparação dos dados, modelagem, relacionamentos, indicadores e visualização.

---

## Resultado

O resultado é um dashboard interativo de Gestão de Recursos Humanos, estruturado para apresentar indicadores e análises de forma objetiva, permitindo uma visão consolidada das informações disponíveis na base de dados.

O projeto também demonstra a importância da preparação e da modelagem dos dados antes da construção dos indicadores e visualizações.

---

## Arquivos do projeto

- `Dashboard_Gestao_Recursos_Humanos_DIO_Santander.pbix` — arquivo-fonte editável do Power BI.
- `Dashboard_Gestao_Recursos_Humanos_DIO_Santander.pdf` — versão final do dashboard para visualização.

---

## Autor

**Rafael Ornelas Tozato**

Engenharia Química | Qualidade & P&D | Dados | Power BI

### Contato

- E-mail: [ornelas.tozato@gmail.com](mailto:ornelas.tozato@gmail.com)
- LinkedIn: [Rafael Ornelas Tozato](https://linkedin.com/in/rafaeltozato81)
- Medium: [Rafael Ornelas Tozato](https://medium.com/@ornelas.tozato)
- GitHub: [Rafael-TOZATO](https://github.com/Rafael-TOZATO)
