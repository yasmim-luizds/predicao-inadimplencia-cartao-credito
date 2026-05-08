# Predição de Inadimplência de Clientes de Cartão de Crédito

Projeto desenvolvido para a disciplina **Projeto Integrador III** do curso de **Sistemas de Informação - FAESA**.

---

## Sobre o Projeto

Este projeto tem como objetivo analisar o comportamento financeiro e o perfil de clientes de cartão de crédito, identificando fatores associados à inadimplência e desenvolvendo modelos preditivos capazes de estimar o risco de não pagamento.

A partir de técnicas de **Ciência de Dados**, o trabalho busca gerar insights relevantes para apoio à tomada de decisão em instituições financeiras e negócios que trabalham com concessão de crédito.

---

## Vídeo de Apresentação

Assista ao protótipo e à análise preliminar no YouTube:

**https://youtu.be/b8hkBnrUWQ0?si=e8OqNrtsZexq5Dpc**

---

## Integrantes

- Hellen Karla Costa Campos Moraes de Melo
- José Henrique Bessi Wolkers
- Kaio Soares Pacheco
- Yasmim Luiz dos Santos

---

## Objetivo Geral

Analisar dados de clientes de cartão de crédito para identificar fatores associados à inadimplência e desenvolver modelos preditivos capazes de estimar o risco de não pagamento.

---

## Problema de Pesquisa

Quais características dos clientes estão mais associadas à inadimplência e é possível prever quais clientes possuem maior risco de não pagamento?

---

## Metodologia

O desenvolvimento do projeto segue as seguintes etapas:

### 1. Análise Exploratória de Dados (EDA)

- Distribuição das variáveis
- Histogramas
- Boxplots
- Matriz de correlação
- Identificação de padrões e outliers

### 2. Tratamento e Preparação dos Dados

- Limpeza dos dados
- Tratamento de valores inconsistentes
- Padronização de variáveis
- Criação de novas variáveis relevantes

### 3. Estatística Inferencial

- Testes de hipótese
- Teste t
- Interpretação de p-value
- Comparação entre grupos

### 4. Modelagem Preditiva

Modelos utilizados:

- Regressão Logística
- Árvore de Decisão
- Random Forest

### 5. Avaliação dos Modelos

Métricas utilizadas:

- Acurácia
- Precisão
- Recall
- F1-score
- Matriz de confusão

---

## Tecnologias Utilizadas

<div align="left">

| Tecnologia | Finalidade |
|---|---|
| Python | Linguagem principal |
| Pandas | Manipulação de dados |
| NumPy | Operações numéricas |
| Matplotlib | Visualização de dados |
| Seaborn | Visualizações estatísticas |
| Scikit-learn | Machine Learning |
| SciPy | Testes estatísticos |
| Jupyter Notebook | Desenvolvimento das análises |

</div>

---

## Estrutura do Projeto

```bash
predicao-inadimplencia-cartao-credito/
│
├── data/
│   └── UCI_Credit_Card.csv
│
├── notebooks/
│   └── predicao_inadimplencia.ipynb
│
├── docs/
│   └── relatorio_projeto_integrador.pdf
│
├── images/
│
├── README.md
└── .gitignore
````

---

## Dataset Utilizado

Dataset: **Default of Credit Card Clients**

Contém informações relacionadas ao perfil financeiro de clientes, incluindo:

* Limite de crédito
* Sexo
* Escolaridade
* Estado civil
* Idade
* Histórico de pagamentos
* Valores de faturas
* Pagamentos anteriores

---

## Principais Análises Realizadas

Perfil de clientes inadimplentes
Relação entre limite de crédito e inadimplência
Impacto do histórico de pagamentos
Comparação estatística entre grupos
Correlação entre variáveis financeiras
Construção de modelos preditivos

---

## Status do Projeto

✅ Entrega 1 — Concluída
✅ Entrega 2 — Protótipo e análise preliminar concluídos
🔄 Entrega 3 — Em desenvolvimento

---

## Sociedade Impactada

O projeto impacta diretamente:

* Instituições financeiras
* Pequenos negócios
* Consumidores
* Empresas que trabalham com análise de crédito

Além disso, contribui para discussões relacionadas ao uso ético de dados e transparência em modelos preditivos.

---

## Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/yasmim-luizds/predicao-inadimplencia-cartao-credito.git
```

### 2. Acesse a pasta do projeto

```bash
cd predicao-inadimplencia-cartao-credito
```

### 3. Instale as dependências

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy notebook
```

### 4. Execute o Jupyter Notebook

```bash
jupyter notebook
```

---

## Disciplina

Projeto Integrador III — Aplicações de Ciência de Dados
Centro Universitário FAESA

---

## Licença

Projeto acadêmico desenvolvido exclusivamente para fins educacionais.

```
```
