# 📊 Dashboard de Gestão de Estoque e Compras

> Projeto desenvolvido em **Power BI** com foco na otimização da gestão de estoque e apoio à tomada de decisão do setor de compras.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge\&logo=Power%20BI\&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data%20Analysis-blue?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power%20Query-Transform-green?style=for-the-badge)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge\&logo=microsoft-excel\&logoColor=white)

---

# 📑 Sumário

* Sobre o projeto
* Problema de negócio
* Objetivos
* Tecnologias utilizadas
* Metodologia
* Organização do projeto
* Modelagem de Dados
* Desenvolvimento do Dashboard
* Principais KPIs
* Resultados Obtidos
* Aprendizados

---

# 📖 Sobre o Projeto

Embora minha função atual seja **Auxiliar Administrativo**, meu objetivo profissional é atuar na área de **Análise de Dados**.

Ao iniciar minhas atividades relacionadas ao controle de estoque, percebi que a empresa possuía um ERP responsável pelo gerenciamento das movimentações, porém toda a análise era realizada através de tabelas e consultas pouco intuitivas.

Essa limitação dificultava:

* acompanhamento do estoque;
* planejamento das compras;
* identificação de produtos críticos;
* análise de consumo;
* tomada de decisões baseada em dados.

Percebendo essa oportunidade de melhoria, apresentei a ideia à gerente responsável pelo setor, propondo o desenvolvimento de um dashboard gerencial utilizando Power BI.

Após aprovação, obtive autorização para extrair os relatórios necessários do ERP e desenvolver o projeto fora do horário de trabalho, dedicando tempo ao estudo, modelagem dos dados e construção dos indicadores.

O resultado foi um dashboard capaz de transformar informações operacionais em indicadores visuais para apoiar o processo de decisão da gestão.

---

# 🎯 Problema de Negócio

O ERP utilizado pela empresa disponibilizava grande quantidade de informações, porém apresentava limitações quanto à visualização e análise dos dados.

As principais dificuldades identificadas foram:

* ausência de indicadores estratégicos;
* baixa visibilidade do consumo dos produtos;
* dificuldade para identificar necessidade de reposição;
* acompanhamento manual das movimentações;
* tomada de decisão baseada em consultas individuais.

---

# 🎯 Objetivos

O projeto teve como objetivo desenvolver uma solução de Business Intelligence capaz de:

* Centralizar informações do estoque;
* Facilitar o acompanhamento do consumo;
* Apoiar o planejamento de compras;
* Identificar produtos críticos;
* Disponibilizar indicadores em tempo real;
* Melhorar a tomada de decisão da gestão.

---

# 🛠 Tecnologias Utilizadas

* Microsoft Power BI
* Power Query
* DAX
* Excel
* Modelagem Dimensional
* Análise Exploratória de Dados (EDA)

---

# 🔎 Metodologia

## 1️⃣ Entendimento do Negócio

Antes de iniciar qualquer desenvolvimento técnico, foi realizada uma etapa de entendimento do processo de negócio.

Foram realizadas reuniões com a gerente responsável para compreender:

* principais dificuldades do setor;
* indicadores desejados;
* informações relevantes para compras;
* necessidades operacionais;
* regras de negócio.

Essa etapa foi fundamental para garantir que o dashboard resolvesse problemas reais da operação.

---

## 2️⃣ Análise Exploratória dos Dados (EDA)

Após compreender as necessidades do negócio, foi realizada uma análise exploratória dos dados disponíveis no ERP.

Nessa etapa foram avaliados:

* qualidade dos dados;
* estrutura dos relatórios;
* campos disponíveis;
* relacionamentos possíveis;
* consistência das informações;
* possíveis limitações do ERP.

Também foi elaborado um "mapa mental" do projeto para definir quais tabelas, métricas e indicadores fariam parte da solução.

---

## 3️⃣ Extração dos Dados

Com o planejamento concluído, iniciou-se a extração dos relatórios do ERP.

Os arquivos foram organizados em uma estrutura de diretórios para facilitar futuras atualizações do dashboard.

### Organização Inicial

```
Projeto/
│
├── Dashboard
├── Dados
├── Relatórios ERP
├── Imagens
└── Documentação
```

📷 *Inserir imagem da organização das pastas.*

---

## 4️⃣ Preparação dos Dados

Os relatórios foram importados para o Power BI.

Como os arquivos eram provenientes diretamente do ERP, não houve necessidade de um processo extenso de tratamento.

As principais atividades realizadas foram:

* remoção de colunas desnecessárias;
* ajuste de tipos de dados;
* padronização de nomes;
* melhoria de desempenho;
* organização das tabelas.

---

## 5️⃣ Modelagem Dimensional

Após a preparação dos dados, foi construída a modelagem dimensional do projeto.

As tabelas foram separadas em:

### Tabelas Dimensão

* dCalendario

### Tabelas Fato

* fMovimentacao
* fProduto
* demais tabelas operacionais

Essa organização permitiu um modelo mais escalável e melhor desempenho das consultas.

📷 *Inserir imagem da modelagem.*

---

## 6️⃣ Desenvolvimento do Dashboard

Com a modelagem finalizada, iniciou-se a construção das páginas do dashboard.

Como toda a etapa de levantamento de requisitos já havia sido realizada anteriormente, foi possível direcionar o desenvolvimento diretamente para os indicadores desejados.

Foram criadas diversas medidas utilizando DAX para atender às necessidades da gestão.

Entre elas:

* Estoque Atual;
* Consumo Médio;
* Cobertura de Estoque;
* Produtos abaixo do mínimo;
* Necessidade de Compra;
* Valor Total em Estoque;
* Indicadores comparativos.

---

# 📊 Principais KPIs

✔ Estoque Atual

✔ Valor Total em Estoque

✔ Consumo Médio

✔ Cobertura de Estoque

✔ Produtos Críticos

✔ Produtos abaixo do Estoque Mínimo

✔ Necessidade de Compra

✔ Movimentação de Entradas

✔ Movimentação de Saídas

✔ Giro de Estoque

---

# 📈 Dashboard

## Página Inicial

📷 *Inserir imagem.*

---

## Página de Estoque

📷 *Inserir imagem.*

---

## Página de Compras

📷 *Inserir imagem.*

---

# 📌 Resultados

O projeto proporcionou uma visão muito mais clara do estoque da empresa.

Entre os principais benefícios obtidos estão:

* maior agilidade na consulta das informações;
* visão consolidada dos produtos;
* apoio ao planejamento de compras;
* redução da necessidade de consultas manuais no ERP;
* centralização dos principais indicadores;
* suporte à tomada de decisão baseada em dados.

---

# 💡 Aprendizados

Durante o desenvolvimento deste projeto foi possível aplicar diversos conceitos estudados na área de Dados, incluindo:

* levantamento de requisitos;
* entendimento do problema de negócio;
* análise exploratória de dados (EDA);
* preparação e transformação de dados;
* modelagem dimensional;
* desenvolvimento de medidas em DAX;
* construção de dashboards;
* comunicação de indicadores para usuários de negócio.

Além da parte técnica, este projeto reforçou a importância de compreender o contexto operacional antes de iniciar qualquer desenvolvimento analítico, garantindo que a solução entregasse valor real ao usuário final.

---

# 🚀 Próximas Melhorias

* Automatização da atualização dos dados.
* Publicação no Power BI Service.
* Criação de alertas automáticos.
* Implementação de indicadores financeiros.
* Integração com novas bases do ERP.
* Evolução para análises preditivas de consumo.

---

## 👨‍💻 Autor

**Gabriel Lacerda**

Estudante de Big Data & Analytics | Power BI | SQL | Python | Excel

LinkedIn: *(Adicionar link)*

GitHub: *(Adicionar link)*
