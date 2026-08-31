# CP1_SERS-Analise_Database_Energia_API-
# 📊 Análise de Dados Aplicada ao Setor Energético

## Ciência da Computação — Soluções em Energias Renováveis e Sustentáveis - 1CCPJ
integrantes:
André Fujinaga - RM569158
Arthur Machado - RM569919
Conrado Gracie - RM569157
Guilherme Belo - RM570079
Renato Sandreschi - RM569156

Este projeto reúne dois desafios desenvolvidos com o objetivo de aplicar conceitos de **análise de dados, tratamento de informações, estatística e visualização gráfica** em problemas relacionados ao consumo e à geração de energia.

Durante o desenvolvimento, foram utilizadas bases de dados públicas provenientes de repositórios como **UCI Machine Learning Repository** e **Kaggle**, além de dados oficiais disponibilizados pelo **Operador Nacional do Sistema Elétrico (ONS)** por meio de sua API pública.

A proposta foi transformar dados brutos em informações que possam ser interpretadas de maneira clara, permitindo identificar padrões de consumo, valores mínimos e máximos, períodos de maior demanda, relações entre variáveis e outros indicadores importantes para a análise energética.

---

# 🎯 Objetivos do Projeto

O projeto teve como principais objetivos:

* Trabalhar com conjuntos de dados reais relacionados ao setor energético;
* Desenvolver a capacidade de interpretar diferentes estruturas de dados;
* Realizar tratamento e organização de dados utilizando Python;
* Utilizar **Pandas** para manipulação, filtragem e análise de tabelas;
* Utilizar **Matplotlib** para criação de gráficos e visualizações;
* Calcular medidas estatísticas como média, mediana, mínimo e máximo;
* Trabalhar com dados temporais, incluindo datas e horários;
* Identificar períodos de maior e menor consumo;
* Criar critérios para classificação de níveis de demanda;
* Consumir dados disponibilizados por uma API pública;
* Construir DataFrames a partir de dados JSON;
* Interpretar os resultados de maneira técnica e, ao mesmo tempo, compreensível;
* Relacionar a análise de dados com situações reais do setor energético.

---

# 🛠️ Tecnologias e Ferramentas Utilizadas

## Python

A linguagem **Python** foi utilizada como principal ferramenta para o desenvolvimento das análises.

Sua utilização permitiu trabalhar desde a organização dos dados até os cálculos estatísticos e a criação das visualizações.

## Pandas

A biblioteca **Pandas** foi utilizada principalmente para trabalhar com os dados em formato de tabela.

Com ela foram realizadas atividades como:

* criação e manipulação de DataFrames;
* leitura e organização dos dados;
* seleção de colunas;
* filtragem de registros;
* tratamento de datas;
* cálculos estatísticos;
* identificação de valores mínimos e máximos;
* cálculo de média e mediana;
* criação de condições para classificação dos registros;
* comparação entre diferentes conjuntos de dados.

O Pandas foi, portanto, a principal ferramenta utilizada para transformar os dados brutos em informações estruturadas e analisáveis.

## Matplotlib

A biblioteca **Matplotlib** foi utilizada para criar os gráficos do projeto.

A visualização gráfica é importante porque nem sempre uma tabela permite perceber facilmente um comportamento nos dados.

Por meio dos gráficos foi possível visualizar tendências, variações, picos de consumo e diferenças entre períodos.

Entre as possibilidades utilizadas estão:

* gráficos de linha;
* gráficos de barras;
* comparação de variáveis;
* evolução temporal;
* representação visual dos valores de consumo.

---

# 📁 Desafio 1 — Análise de Bases de Dados Energéticas

## 📌 Objetivo

O primeiro desafio teve como foco trabalhar com diferentes conjuntos de dados relacionados à **energia elétrica, consumo energético e fontes renováveis**.

Foram analisadas bases disponíveis publicamente, permitindo conhecer diferentes tipos de informações utilizadas em estudos relacionados à eficiência energética, consumo residencial, consumo industrial e geração de energia renovável.

A utilização de diferentes bases também possibilita perceber que os dados de energia podem assumir formatos bastante diferentes dependendo do contexto analisado.

---

# 🗃️ Bases de Dados Utilizadas como Referência

## 1. Appliances Energy Prediction — UCI

**Descrição:**
Conjunto de dados relacionado ao consumo de eletrodomésticos em uma residência, associado a informações de temperatura, umidade e outras condições ambientais.

A base possui dados temporais e variáveis relacionadas ao ambiente interno e externo da residência. Segundo o UCI, os dados foram registrados em intervalos de 10 minutos durante aproximadamente 4,5 meses.

**Fonte:**

[Appliances Energy Prediction — UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/374/appliances%2Benergy%2Bprediction?utm)

---

## 2. Steel Industry Energy Consumption — UCI

**Descrição:**
Conjunto de dados relacionado ao consumo energético de uma indústria siderúrgica.

Entre as informações disponíveis estão:

* consumo de energia;
* potência reativa;
* fator de potência;
* emissão de CO₂;
* informações temporais;
* classificação do tipo de carga.

Esse conjunto permite estudar o comportamento energético de um ambiente industrial e observar como diferentes variáveis elétricas estão relacionadas ao consumo.

**Fonte:**

[Steel Industry Energy Consumption — UCI Machine Learning Repository](https://archive.ics.uci.edu/?utm)

---

## 3. Power Consumption of Tetouan City — UCI

**Descrição:**
Conjunto de dados referente ao consumo elétrico de três zonas de distribuição da cidade de Tétouan, no Marrocos.

Além do consumo das três zonas, a base apresenta variáveis meteorológicas, possibilitando analisar a relação entre condições ambientais e consumo de energia.

Entre as variáveis estão informações como:

* temperatura;
* umidade;
* velocidade do vento;
* fluxo solar;
* consumo das três zonas.

**Fonte:**

[Power Consumption of Tetouan City — UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/849/power%2Bconsumption%2Bof%2Bteto?utm)

---

## 4. Solar Power Generation Data — Kaggle

**Descrição:**
Conjunto de dados sobre geração de energia solar de duas usinas fotovoltaicas localizadas na Índia.

A base apresenta informações coletadas nos inversores e também dados provenientes de sensores ambientais.

Entre as informações disponíveis estão:

* geração de energia;
* potência DC;
* potência AC;
* rendimento diário;
* rendimento acumulado;
* temperatura ambiente;
* temperatura dos módulos;
* irradiância;
* identificação dos inversores.

Os dados possuem medições realizadas em intervalos de 15 minutos, permitindo análises detalhadas do comportamento da geração solar.

**Fonte:**

[Solar Power Generation Data — Kaggle](https://www.kaggle.com/anikannal/solar-power-generation-data?utm)

---

## 5. Wind & Solar Energy Production Dataset — Kaggle

**Descrição:**
Conjunto de dados voltado à produção de energia eólica e solar.

A base permite comparar o comportamento das duas fontes renováveis e analisar como a produção de energia varia ao longo do tempo.

Esse tipo de conjunto de dados é especialmente interessante para estudos relacionados à **transição energética e integração de fontes renováveis**, pois permite observar diferenças entre os padrões de geração solar e eólica.

**Fonte:**

[Wind & Solar Energy Production Dataset — Kaggle](https://www.kaggle.com/datasets/ahmeduzaki/wind-and-solar-energy-production-dataset?utm)

---

## 6. Individual Household Electric Power Consumption — UCI

**Descrição:**
Conjunto de dados contendo medições de consumo elétrico de uma residência.

Os registros possuem uma frequência de medição de aproximadamente um minuto e abrangem um período de quase quatro anos.

Entre as informações estão:

* potência ativa;
* potência reativa;
* tensão;
* corrente;
* consumo global;
* submedições de diferentes equipamentos.

A grande quantidade de registros permite realizar análises temporais e estatísticas mais detalhadas sobre o comportamento do consumo residencial.

**Fonte:**

[Individual Household Electric Power Consumption — UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/235/individual%2Bhousehold%2Belectric%2Bpower-consumption?utm)

---

# 🔎 Abordagem de Análise do Desafio 1

A análise das bases foi realizada considerando principalmente a estrutura das tabelas, os tipos das variáveis e o contexto energético representado por cada conjunto.

Uma etapa importante foi compreender **o que cada coluna representa antes de realizar os cálculos**.

Isso evita interpretar um valor de maneira incorreta. Por exemplo, uma coluna pode representar potência, energia, temperatura, umidade ou simplesmente uma identificação.

Também foi dada atenção às variáveis temporais, já que dados energéticos normalmente apresentam forte relação com o horário e a data da medição.

A partir disso, o Pandas foi utilizado para:

1. carregar os dados;
2. verificar a quantidade de registros;
3. identificar as colunas existentes;
4. verificar os tipos de dados;
5. analisar valores ausentes;
6. selecionar as variáveis relevantes;
7. realizar filtros;
8. calcular estatísticas;
9. identificar valores extremos;
10. organizar os dados para visualização.

Depois da preparação, o **Matplotlib** foi utilizado para transformar os resultados em gráficos.

---

# 📈 Importância da Visualização

A utilização de gráficos teve um papel importante na análise.

Uma tabela pode mostrar centenas ou milhares de valores, mas isso não significa que seja fácil perceber um comportamento.

Um gráfico de linha, por exemplo, permite observar rapidamente se o consumo está aumentando ou diminuindo ao longo do tempo.

Da mesma forma, gráficos de barras podem facilitar a comparação entre diferentes zonas, períodos ou fontes de geração.

Assim, o projeto não se limitou a calcular valores: os resultados também foram apresentados de forma visual para facilitar sua interpretação.

---

# ⚡ Desafio 2 — Análise de Dados de Energia com API Pública

## Situação-problema

Uma equipe de planejamento energético precisa analisar o comportamento da carga elétrica de uma região atendida pelo **Sistema Interligado Nacional (SIN)**.

Os dados são obtidos diretamente de uma **API pública do Operador Nacional do Sistema Elétrico (ONS)**.

A conexão com a API e a preparação inicial do JSON foram fornecidas. A partir dessas informações, foi necessário construir o DataFrame, organizar os dados, criar recortes, calcular indicadores, produzir gráficos e elaborar um relatório técnico.

O ONS disponibiliza publicamente dados do setor elétrico brasileiro por meio de seu Portal de Dados Abertos. Entre os conjuntos disponíveis estão dados de carga de energia verificada e programada.

### Fontes oficiais

[Portal de Dados Abertos do ONS](https://dados.ons.org.br/dataset/?utm)

[Dados de Carga do ONS](https://dados.ons.org.br/dataset/?res_format=API&tags=Carga&utm)

[Portal de documentação das APIs do ONS](https://portal-integra.ons.org.br/api-docs?utm)

---

# 🔄 Fluxo de Tratamento dos Dados

O processo realizado no desafio pode ser resumido da seguinte maneira:

```text
API Pública do ONS
        ↓
Dados em JSON
        ↓
Organização das informações
        ↓
Criação do DataFrame
        ↓
Tratamento das datas e horários
        ↓
Seleção da região de São Paulo
        ↓
Análise estatística
        ↓
Criação dos critérios de demanda
        ↓
Identificação do pico
        ↓
Gráficos com Matplotlib
        ↓
Relatório técnico
```

---

# 🐼 Construção e Análise do DataFrame

Depois que os dados foram obtidos pela API, eles foram organizados utilizando o **Pandas**.

O DataFrame permitiu trabalhar com os registros de forma semelhante a uma planilha, porém com recursos de programação que tornam possível realizar filtros e cálculos automaticamente.

Entre as operações realizadas estão:

* organização dos registros;
* seleção da região analisada;
* tratamento da data;
* tratamento do horário;
* seleção da variável de carga;
* cálculo da carga mínima;
* cálculo da carga máxima;
* cálculo da média;
* cálculo da mediana;
* criação de condições de classificação;
* identificação do momento de maior carga.

Essa etapa foi fundamental para transformar o JSON fornecido pela API em uma estrutura adequada para análise.

---

# 📊 Critérios de Análise

Foram utilizados dois critérios principais para avaliar os níveis de demanda.

## Critério 1 — Alta Demanda

Foi considerado como alta demanda o período em que a carga atingiu pelo menos **90% da carga máxima registrada**.

A partir desse critério foi possível identificar os momentos em que o sistema estava operando próximo de seu maior nível de carga.

## Critério 2 — Acima da Média

O segundo critério considerou todos os registros cuja carga estivesse acima da média do período analisado.

Esse critério é mais abrangente, pois não procura apenas os momentos próximos ao pico, mas todos os momentos em que a demanda ficou acima do comportamento médio.

A comparação entre os dois critérios permitiu compreender melhor a distribuição da carga durante o período.

---

# 📈 Visualização dos Resultados

Os gráficos foram produzidos utilizando **Matplotlib**.

A principal finalidade foi representar visualmente a evolução da carga elétrica ao longo do período analisado.

A visualização facilita a identificação de:

* tendências;
* variações;
* momentos de maior demanda;
* momentos de menor demanda;
* proximidade do pico;
* diferenças entre a carga e os critérios estabelecidos.

Dessa forma, o gráfico funciona como uma ponte entre os cálculos realizados pelo código e a interpretação humana dos resultados.

---

# 📝 Relatório Técnico de Análise de Carga Elétrica — Estado de São Paulo

## 1. Caracterização do Conjunto Analisado

A análise foi realizada sobre a **carga elétrica da região de São Paulo (SP)** entre **01/08/2025 e 07/08/2025**.

Foram analisados **336 registros oficiais**, obtidos por meio da API do Operador Nacional do Sistema Elétrico (ONS).

Os dados representam a carga elétrica registrada durante o período analisado, permitindo observar como a demanda se comportou ao longo dos dias e horários.

A utilização de dados provenientes diretamente do ONS proporciona uma análise baseada em dados oficiais do setor elétrico brasileiro.

---

## 2. Principais Indicadores

A análise estatística apresentou os seguintes resultados:

| Indicador        |         Resultado |
| ---------------- | ----------------: |
| **Carga mínima** | **12.139,253 MW** |
| **Carga máxima** | **23.185,312 MW** |
| **Carga média**  | **17.870,829 MW** |
| **Mediana**      | **18.199,128 MW** |

A diferença entre a carga máxima e a mínima resultou em uma **amplitude de 11.046,059 MW**.

Esse valor mostra que houve uma variação significativa na carga durante o período analisado.

Outro ponto importante é que a carga permaneceu **acima da média em 54,76% do tempo analisado**.

Isso significa que, apesar de existirem momentos de demanda mais baixa, uma parcela ligeiramente superior à metade dos registros apresentou valores acima da média calculada.

---

# 🔺 3. Alta Demanda e Pico

Para identificar os períodos de maior pressão sobre a carga elétrica, foi utilizado um limite correspondente a **90% da carga máxima**.

O valor utilizado como limiar foi:

**20.866,781 MW**

A partir desse critério, os períodos classificados como de alta demanda representaram **14,88% do período analisado**.

Esse resultado mostra que os momentos de demanda extremamente elevada foram relativamente pontuais quando comparados ao total de observações.

### Pico absoluto

O maior valor de carga registrado ocorreu em:

**01/08/2025 às 22:00 (UTC)**

Esse momento corresponde ao pico absoluto observado no conjunto de dados analisado.

É importante destacar que a identificação do pico representa um **fato observado nos dados**. A análise, por si só, não permite afirmar qual foi a causa desse aumento.

---

# ⚖️ 4. Comparação dos Critérios

A comparação entre os dois critérios apresentou um resultado importante.

Foi observado que **100% dos registros classificados como alta demanda pelo Critério 1 também estavam presentes no conjunto de registros acima da média pelo Critério 2**.

Isso acontece porque o critério de 90% da carga máxima representa uma condição muito mais restritiva.

Enquanto o primeiro critério procura apenas os valores próximos ao maior nível de carga registrado, o segundo considera qualquer valor que esteja acima da média.

Dessa maneira:

### Critério 1 — 90% da carga máxima

Representa uma visão mais restritiva e concentrada nos momentos de maior demanda.

### Critério 2 — Acima da média

Representa uma visão mais ampla do comportamento do sistema.

Por isso, o Critério 2 cobriu **mais da metade das observações**, enquanto o Critério 1 identificou apenas **14,88%** do período.

Essa comparação ajuda a demonstrar que "estar acima da média" não significa necessariamente estar próximo do pico.

---

# 💡 5. Interpretação dos Resultados

Os resultados indicam que o comportamento da carga elétrica de São Paulo apresentou variações consideráveis durante a semana analisada.

A amplitude de mais de 11 mil MW demonstra uma diferença expressiva entre os momentos de menor e maior demanda.

Ao mesmo tempo, a média e a mediana apresentaram valores relativamente próximos:

* Média: **17.870,829 MW**
* Mediana: **18.199,128 MW**

A mediana ligeiramente superior à média indica que a distribuição dos valores não é perfeitamente simétrica e que alguns valores mais baixos influenciam o cálculo da média.

Também foi possível observar que a maior parte do tempo não correspondeu a uma situação de demanda extrema. O critério de 90% da carga máxima identificou alta demanda em apenas **14,88% dos registros**.

Portanto, o pico representa uma situação de maior demanda que ocorre de maneira pontual em relação ao período total observado.

---

# 📌 6. Conclusão

A análise demonstrou que o sistema elétrico de São Paulo apresentou um comportamento variável durante o período de **01/08/2025 a 07/08/2025**.

A carga mínima registrada foi de **12.139,253 MW**, enquanto a máxima chegou a **23.185,312 MW**, resultando em uma amplitude de **11.046,059 MW**.

A carga média foi de **17.870,829 MW** e a mediana foi de **18.199,128 MW**.

A aplicação do critério de 90% da carga máxima permitiu identificar os momentos de maior demanda, que representaram **14,88% dos registros**.

O pico absoluto aconteceu em **01/08/2025 às 22:00 (UTC)**.

A comparação entre os critérios também demonstrou que todos os registros de alta demanda estavam contidos no grupo de registros acima da média. Isso reforça que o critério baseado na média é mais abrangente, enquanto o critério de 90% da carga máxima é mais específico.

Por fim, é importante diferenciar **observação de hipótese**. O pico identificado no início do período é um resultado diretamente observado nos dados. Entretanto, não é possível afirmar apenas com essa base qual foi a causa dessa elevação.

Para explicar as razões das variações seria necessário complementar a análise com outras informações, como:

* condições climáticas;
* temperatura;
* umidade;
* comportamento de consumo;
* características do período;
* informações operacionais;
* eventos específicos que possam ter afetado a demanda.

Assim, o projeto demonstra como dados públicos podem ser transformados em informações úteis para compreender o comportamento do sistema elétrico.

---

# 🧠 Conclusão Geral dos Dois Desafios

Os dois desafios permitiram trabalhar diferentes etapas de um processo de **análise de dados aplicada ao setor energético**.

No primeiro desafio, o foco esteve na exploração de diferentes bases públicas, permitindo conhecer conjuntos de dados relacionados ao consumo residencial, consumo industrial, distribuição de energia e geração de fontes renováveis.

No segundo desafio, o trabalho avançou para uma situação mais próxima de um cenário profissional, utilizando dados obtidos diretamente de uma **API pública do ONS**.

Essa evolução foi importante porque demonstrou que análise de dados não significa apenas criar gráficos.

É necessário primeiro compreender o problema, conhecer a origem dos dados, organizar as informações, tratar as variáveis, realizar os cálculos e somente depois interpretar os resultados.

Nesse processo, o **Pandas** foi utilizado como principal ferramenta para manipulação e análise dos dados em formato de tabela, enquanto o **Matplotlib** foi utilizado para transformar os resultados em visualizações gráficas.

O projeto também mostrou a importância de utilizar dados públicos e fontes confiáveis. Bases como as disponibilizadas pelo UCI e Kaggle permitem desenvolver análises e estudos acadêmicos, enquanto o Portal de Dados Abertos do ONS disponibiliza informações oficiais sobre o setor elétrico brasileiro.

Mais do que encontrar números, o objetivo foi aprender a **interpretar o que esses números representam**.

A análise de dados aplicada à energia pode contribuir para compreender padrões de consumo, identificar períodos de maior demanda, acompanhar a geração renovável e fornecer informações que podem apoiar decisões relacionadas à eficiência e ao planejamento energético.

---

# 📚 Fontes de Dados

### UCI Machine Learning Repository

* Appliances Energy Prediction
* Power Consumption of Tetouan City
* Individual Household Electric Power Consumption
* Steel Industry Energy Consumption

### Kaggle

* Solar Power Generation Data
* Wind & Solar Energy Production Dataset

### ONS

* Portal de Dados Abertos
* Dados de Carga de Energia
* API pública do ONS

Todas as fontes utilizadas são públicas e foram escolhidas por apresentarem dados relacionados ao consumo, geração ou comportamento do sistema energético.

---

# 👨‍💻 Ferramentas Principais

| Ferramenta     | Utilização                                      |
| -------------- | ----------------------------------------------- |
| **Python**     | Desenvolvimento das análises                    |
| **Pandas**     | Manipulação e análise de tabelas                |
| **Matplotlib** | Criação dos gráficos                            |
| **API do ONS** | Obtenção de dados públicos                      |
| **JSON**       | Estrutura inicial dos dados provenientes da API |
| **UCI**        | Fonte de conjuntos de dados                     |
| **Kaggle**     | Fonte de conjuntos de dados                     |

---

# 📌 Resultado Final

Ao final dos dois desafios, foi possível desenvolver um fluxo completo de análise de dados:

**Dados → Tratamento → Organização → Análise → Estatística → Visualização → Interpretação → Relatório**

Esse fluxo representa uma das etapas fundamentais do trabalho com dados e demonstra, na prática, como ferramentas de programação podem ser utilizadas para transformar grandes quantidades de informações em resultados compreensíveis e úteis para a tomada de decisões no setor energético.
