---

# Desafio Prático 2: Inteligência Artificial - Aprendizagem de Máquina

> **📌 Informação Importante para o Grupo:**
> O dataset designado para o nosso grupo neste trabalho é o **HCV data**.

Bem-vindos(as) ao segundo grande desafio prático da disciplina de Inteligência Artificial.

Neste trabalho, o foco será a **Aprendizagem de Máquina clássica**, com ênfase em modelagem experimental, comparação de algoritmos e análise crítica dos resultados. A proposta é que vocês avancem além da simples execução de exemplos prontos e passem a tratar o problema como uma atividade de engenharia: compreender os dados, decidir como representá-los, escolher modelos, definir métricas e interpretar resultados com cuidado.

Ao longo das aulas, discutimos que aprendizagem de máquina não se resume a “treinar um modelo”. Há decisões importantes antes, durante e depois do treinamento: definição do problema, escolha das features, pré-processamento, separação dos dados, escolha dos hiperparâmetros, avaliação e interpretação. É esse conjunto que este trabalho pretende exercitar.

Desta vez, cada grupo trabalhará com um dataset real e deverá explorá-lo sob duas perspectivas complementares:
* **Aprendizagem supervisionada:** para construir modelos capazes de prever o rótulo das instâncias.
* **Aprendizagem não supervisionada:** para investigar se há estrutura natural nos dados por meio de agrupamento.

A ideia não é tratar essas duas abordagens como rivais, mas como formas diferentes de olhar para o mesmo conjunto de dados. Como nos demais trabalhos da disciplina, ética e transparência continuam valendo em todas as etapas. Ferramentas de IA generativa podem ser usadas como apoio pontual, mas não substituem o entendimento do grupo. Todas as decisões relevantes devem ser compreendidas e defendidas por vocês na apresentação oral.

---

## 🎯 Objetivos de Aprendizagem

Ao final deste trabalho, espera-se que os grupos sejam capazes de:
* **Compreender um dataset real**, identificando corretamente instâncias, atributos e rótulos.
* **Avaliar a qualidade dos dados** e justify decisões de pré-processamento, como limpeza, normalização, codificação e seleção de atributos.
* **Treinar e comparar** diferentes algoritmos de aprendizagem supervisionada para um mesmo problema.
* **Implementar uma rede neural artificial simples** e compará-la com algoritmos clássicos.
* **Aplicar um método de aprendizagem não supervisionada** ao mesmo dataset e interpretar seus resultados.
* **Definir e executar um protocolo experimental coerente**, separando adequadamente treino, validação e teste.
* **Utilizar métricas adequadas** para avaliar e comparar modelos.
* **Analisar criticamente os resultados**, discutindo limitações, diferenças de desempenho e possíveis causas.
* **Comunicar com clareza** a metodologia adotada, os resultados obtidos e as conclusões do grupo.

---

## 👥 Organização da Turma e Datasets

* A turma será organizada em **6 grupos**.
* Neste semestre, o T2 será desenvolvido a partir de **3 datasets**, com 2 grupos trabalhando em cada dataset. O sorteio dos datasets será feito em sala.
* Cada grupo deverá desenvolver seu trabalho de forma independente, mesmo quando outro grupo estiver trabalhando com o mesmo dataset. Isso inclui decisões de pré-processamento, modelagem, ajuste de hiperparâmetros, interpretação dos resultados e apresentação.

---

## 🏗️ Estrutura Geral do Trabalho

Cada grupo deverá desenvolver duas trilhas no mesmo dataset:

### 1. Trilha Supervisionada
O grupo deverá treinar e comparar, no mínimo, os seguintes modelos:
* **KNN**
* **Árvore de Decisão**
* **Rede Neural Artificial**

> **Nota sobre implementação:** A implementação poderá ser feita com bibliotecas como `scikit-learn`, `keras` e `tensorflow`, ou outras equivalentes, desde que seja **formalmente solicitada autorização** para usá-las ANTECIPADAMENTE e com JUSTIFICATIVA técnica.

### 2. Trilha Não Supervisionada
O grupo deverá aplicar **K-Means** ao mesmo dataset, ignorando os rótulos durante o agrupamento.
* **Objetivo:** Investigar se os dados apresentam alguma estrutura natural e discutir em que medida os agrupamentos encontrados dialogam, ou não, com os rótulos conhecidos do problema.

---

## 📅 Datas e Prazos

| Etapa | Data |
| :--- | :--- |
| **Especificação do trabalho** | 14/05 |
| **Entrega** (Relatório, Código e Slides) | 01/06 até as 23:59 |
| **Apresentações orais** | 02/06 e 09/06 |

---

## 🤖 Observação sobre Uso de IA Generativa

Ferramentas de IA generativa podem ser usadas como apoio pontual, por exemplo:
* Para revisar texto;
* Sugerir organização de código;
* Discutir alternativas de pré-processamento;
* Levantar hipóteses para interpretar resultados.

No entanto, **o grupo continua responsável por tudo o que entregar**. Não basta o código funcionar. É necessário compreender o que foi feito e saber explicar as escolhas tomadas. 

No relatório, o grupo deve incluir um pequeno item final informando se utilizou ferramentas de IA generativa e, em caso positivo, em que etapa elas foram usadas.