Claro — segue uma versão atualizada do `README.md`, já considerando a **Entrega 3 / MVP final**, modelos refinados e aprendizado não supervisionado.

````markdown
# Predição de Inadimplência de Clientes de Cartão de Crédito

Projeto desenvolvido para a disciplina **Projeto Integrador III** do curso de **Sistemas de Informação - FAESA**.

---

## Sobre o Projeto

Este projeto tem como objetivo analisar o comportamento financeiro e o perfil de clientes de cartão de crédito, identificando fatores associados à inadimplência e desenvolvendo modelos preditivos capazes de estimar o risco de não pagamento.

A partir de técnicas de **Ciência de Dados**, o trabalho busca gerar insights relevantes para apoiar a tomada de decisão em instituições financeiras, fintechs, pequenos negócios e demais organizações que trabalham com concessão de crédito.

O projeto foi desenvolvido em três fases: planejamento, protótipo analítico e MVP final.

---

## Vídeo de Apresentação

Assista à apresentação do projeto no YouTube:

**https://youtu.be/b8hkBnrUWQ0?si=e8OqNrtsZexq5Dpc**

---

## Integrantes

- Hellen Karla Costa Campos Moraes de Melo
- José Henrique Bessi Wolkers
- Kaio Soares Pacheco
- Yasmim Luiz dos Santos

---

## Objetivo Geral

Analisar dados de clientes de cartão de crédito para identificar fatores associados à inadimplência e desenvolver um MVP analítico capaz de estimar o risco de não pagamento.

---

## Problema de Pesquisa

Quais características dos clientes estão mais associadas à inadimplência e é possível prever quais clientes possuem maior risco de não pagamento?

---

## Metodologia

O desenvolvimento do projeto seguiu as seguintes etapas:

### 1. Análise Exploratória de Dados (EDA)

- Análise da distribuição da variável alvo
- Histogramas
- Boxplots
- Matriz de correlação
- Comparação entre clientes adimplentes e inadimplentes
- Identificação de padrões relacionados à inadimplência

### 2. Tratamento e Preparação dos Dados

- Verificação de valores nulos
- Tratamento de valores inconsistentes
- Padronização de variáveis
- Criação de novas variáveis, como dívida total e pagamento total

### 3. Estatística Inferencial

- Testes de hipótese
- Teste t
- Teste A/B
- Teste t pareado
- Interpretação de p-value
- Simulação de dados para reforçar conceitos estatísticos

### 4. Modelagem Supervisionada

Modelos utilizados:

- Regressão Logística
- Árvore de Decisão
- Random Forest
- Random Forest Refinado

O refinamento do modelo foi realizado com foco em melhorar o recall da classe inadimplente, considerando que, para o problema de risco de crédito, identificar corretamente clientes com risco de não pagamento é mais importante do que apenas obter a maior acurácia geral.

### 5. Modelagem Não Supervisionada

Também foi aplicada uma abordagem de aprendizado não supervisionado com:

- K-Means
- Avaliação com Silhouette Score
- Segmentação de clientes por perfis semelhantes
- Análise da taxa de inadimplência por cluster

Essa etapa permitiu identificar grupos de clientes com diferentes níveis de risco, complementando os modelos supervisionados.

### 6. Avaliação dos Modelos

Métricas utilizadas:

- Acurácia
- Precisão
- Recall
- F1-score
- Matriz de confusão

---

## Tecnologias Utilizadas

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

---

## Estrutura do Projeto

```bash
predicao-inadimplencia-cartao-credito/
│
├── data/
│   └── UCI_Credit_Card.csv
│
├── notebooks/
│   └── MVP_predicao_inadimplencia.ipynb
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

O dataset contém informações relacionadas ao perfil financeiro de clientes, incluindo:

* Limite de crédito
* Sexo
* Escolaridade
* Estado civil
* Idade
* Histórico de pagamentos
* Valores de faturas
* Pagamentos anteriores
* Indicação de inadimplência no mês seguinte

---

## Principais Análises Realizadas

* Perfil de clientes inadimplentes
* Relação entre limite de crédito e inadimplência
* Impacto do histórico de pagamentos no risco de inadimplência
* Comparação estatística entre grupos
* Correlação entre variáveis financeiras
* Construção e avaliação de modelos preditivos
* Refinamento do modelo com foco na classe inadimplente
* Segmentação de clientes com K-Means
* Demonstração de um MVP analítico para classificação de risco

---

## Principais Insights

* O histórico de pagamento foi o principal indicador de risco de inadimplência.
* Clientes com atraso recente apresentaram taxa de inadimplência muito maior do que clientes sem atraso.
* O limite de crédito apresentou diferença significativa entre clientes adimplentes e inadimplentes.
* O comportamento de pagamento, especialmente a relação entre valor da fatura e valor pago, mostrou-se relevante para entender o risco.
* A acurácia sozinha não é suficiente para avaliar o modelo, sendo necessário observar o recall da classe inadimplente.
* O Random Forest Refinado apresentou melhor capacidade de identificar clientes inadimplentes.
* A segmentação com K-Means permitiu identificar grupos de clientes com diferentes níveis de risco.
* O MVP final demonstra como os dados podem ser transformados em uma indicação inicial de risco de inadimplência.

---

## MVP Final

O MVP desenvolvido consiste em um pipeline analítico em Jupyter Notebook capaz de:

1. carregar e tratar os dados;
2. realizar análise exploratória;
3. aplicar testes estatísticos;
4. treinar e comparar modelos de machine learning;
5. refinar o modelo escolhido;
6. analisar a importância das variáveis;
7. segmentar clientes com aprendizado não supervisionado;
8. simular a classificação de risco de um cliente.

A demonstração final utiliza uma função que recebe os dados de um cliente e retorna:

* probabilidade estimada de inadimplência;
* classificação inicial de risco.

---

## Status do Projeto

✅ Entrega 1 — Relatório de escopo, justificativa, metodologia e plano de trabalho

✅ Entrega 2 — Protótipo funcional com análise preliminar e modelos aplicados

✅ Entrega 3 — MVP final, refinamento dos modelos e segmentação não supervisionada.

---

## Sociedade Impactada

O projeto impacta diretamente:

* Instituições financeiras
* Fintechs
* Pequenos negócios
* Consumidores
* Empresas que trabalham com análise de crédito

A solução pode apoiar decisões de crédito mais responsáveis, reduzindo riscos de inadimplência e evitando concessões inadequadas. Além disso, o projeto contribui para discussões sobre uso ético de dados, transparência em modelos preditivos e apoio à decisão humana.

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

Depois, abra o arquivo:

```bash
notebooks/MVP_predicao_inadimplencia.ipynb
```

---

## Disciplina

**Projeto Integrador III — Aplicações de Ciência de Dados**
Centro Universitário FAESA

---

## Licença

Projeto acadêmico desenvolvido exclusivamente para fins educacionais.

````

