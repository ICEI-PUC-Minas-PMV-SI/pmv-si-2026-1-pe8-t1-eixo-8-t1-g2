# 3 DESENVOLVIMENTO DE ALTERNATIVAS DE SOLUÇÕES DE SI

A análise do contexto organizacional evidenciou limitações significativas relacionadas à fragmentação dos dados, à predominância de processos manuais e à baixa utilização das informações como suporte à tomada de decisão.

Como alternativa de solução, propõe-se a implementação de uma arquitetura de BI, permitindo a transformação dos dados operacionais em informações estratégicas.

A solução de BI será responsável pela coleta, integração e tratamento dos dados, possibilitando a consolidação de informações provenientes de sistemas como ERP e planilhas. Além disso, permitirá a estruturação de dados relacionados a clientes, produtos, vendas e visitas comerciais, formando uma base confiável para análise.

Por meio dessa arquitetura, será possível a geração de relatórios analíticos e previsões de vendas com base em dados históricos, contribuindo para maior assertividade no planejamento.

A camada analítica do BI atuará na análise e visualização dos dados, por meio de dashboards e indicadores de desempenho, possibilitando análises como faturamento, Curva ABC, ranking de clientes e identificação de padrões de consumo.

A centralização e padronização dos dados garantem maior consistência das informações, promovendo eficiência no acesso e flexibilidade nas análises.

Como benefícios, destacam-se a centralização das informações, redução de processos manuais, maior confiabilidade dos dados e melhoria na tomada de decisão.

Dessa forma, a solução proposta permite a transição para um modelo de gestão orientado a dados, contribuindo para o aumento da eficiência operacional e estratégica da organização.

## 3.1 Conexão com o Plano de IC e Planejamento da Solução

Com base nas análises realizadas anteriormente, verificou-se que a empresa possui uma base relevante de dados comerciais armazenados no ERP Mercos, porém ainda enfrenta dificuldades para transformar essas informações em inteligência estratégica. Os principais gargalos identificados referem-se à ausência de previsibilidade comercial, controle descentralizado das visitas técnicas, dependência de planilhas manuais e baixa integração entre dados de vendas e relacionamento com clientes.

Diante desse cenário, a solução proposta consiste no desenvolvimento de um Sistema Complementar de Apoio à Gestão Comercial, integrado ao ERP existente, com foco em BI, CRM comercial e apoio à tomada de decisão.

A proposta do sistema está diretamente vinculada ao Key Intelligence Topic (KIT) definido na Etapa 2, que consiste na avaliação de desempenho do portfólio de produtos químicos visando otimização da oferta e direcionamento estratégico das vendas.

Para que esse objetivo seja alcançado, foram formuladas as Key Intelligence Questions (KIQs), que orientam quais informações estratégicas precisam ser respondidas pela solução tecnológica. Assim, o sistema funcionará como instrumento operacional do Plano de Inteligência Competitiva, convertendo dados históricos em indicadores claros e acionáveis.

Nesse contexto, cada KIQ será atendida da seguinte forma conforme o Quadro 11.

### Quadro 11 – Relação com o KIT e KIQs

| KIQ | Objetivo Analítico | Aplicação no BI |
|------|-------------------|----------------|
| KIQ 1 | Identificar os produtos responsáveis pela maior parcela do faturamento e comissões | Geração automática da Curva ABC, ranking de produtos e relatórios gerenciais |
| KIQ 2 | Verificar produtos menos sensíveis a preço | Cruzamento entre histórico de preços, volume vendido e frequência de compra |
| KIQ 3 | Detectar produtos com baixo giro e vendas lentas | Indicadores de rotatividade, tempo médio entre vendas e alertas automáticos |
| Complementar | Melhorar relacionamento comercial | Histórico estruturado de vendas e interações com clientes ativos/inativos |

**Fonte:** Elaborada pelos autores (2026).

Como consequência direta da necessidade de responder às KIQs e melhorar a inteligência comercial da empresa, alguns processos internos precisarão ser modernizados. Atualmente, muitas dessas rotinas dependem de controles paralelos e ações manuais, reduzindo produtividade e confiabilidade das informações.

Com a implantação do sistema proposto, os seguintes processos organizacionais serão aprimorados conforme apresentados no Quadro 12.

### Quadro 12 – Processos Organizacionais que Serão Melhorados

| Processo Organizacional | Situação Atual | Melhoria Esperada com o Sistema |
|------------------------|---------------|--------------------------------|
| Análise de vendas | Realizada manualmente em Excel | Indicadores automáticos e dashboards em tempo real |
| Previsão comercial | Baseada em experiência empírica | Projeções automatizadas de vendas |
| Gestão da carteira de clientes | Sem acompanhamento sistemático | Alertas de clientes inativos e oportunidades |
| Gestão de portfólio | Sem análise objetiva de rentabilidade | Curva ABC e relatórios estratégicos |
| Tomada de decisão gerencial | Reativa e intuitiva | Gestão orientada por dados |

**Fonte:** Elaborada pelos autores (2026).

Para que os processos apresentados sejam efetivamente melhorados, torna-se necessário definir as funcionalidades mínimas da primeira versão do sistema. Essas funcionalidades foram planejadas de modo a atacar os principais gargalos identificados no diagnóstico empresarial e são apresentadas no Quadro 13.

### Quadro 13 – Funcionalidades Iniciais do Sistema (MVP)

| Funcionalidade | Finalidade | Relação com os Processos Melhorados |
|---------------|------------|------------------------------------|
| Importação de planilhas do ERP | Consolidar dados históricos | Sustenta análise de vendas e previsões |
| Dashboard de vendas | Exibir KPIs e indicadores mensais | Apoia decisões gerenciais |
| Curva ABC automática | Classificar produtos por relevância | Otimiza gestão de portfólio |
| Ranking de clientes | Identificar maiores compradores | Apoia carteira comercial |
| Alertas de clientes inativos | Sinalizar perda de recorrência | Apoia reativação de clientes |
| Previsão de vendas | Estimar resultados futuros | Apoia planejamento mensal |

**Fonte:** Elaborada pelos autores (2026).

Considerando a relação entre necessidades estratégicas, processos internos e funcionalidades do sistema, apresenta-se no Quadro 14 a consolidação da solução proposta.

### Quadro 14 – Quadro-resumo da Solução

| Problema Mapeado | Consequência Atual | Como será resolvida no sistema |
|------------------|-------------------|-------------------------------|
| Dependência de planilhas manuais | Centralização e automação dos dados | Importação automática de dados integrada a dashboards |
| Falta de previsão comercial | Implementação de análise preditiva | Módulo de previsão de vendas baseado em histórico |
| Produtos sem priorização | Análise estratégica do portfólio | Curva ABC automática para classificação de produtos |
| Clientes sem acompanhamento | Monitoramento contínuo da carteira | Alertas automáticos de inatividade |
| Decisões intuitivas | Uso de inteligência analítica | Relatórios gerenciais e dashboards de BI |
| Informações descentralizadas | Integração das informações | Sistema único com base de dados centralizada |

**Fonte:** Elaborada pelos autores (2026).

## 3.2 Organização e Modelagem de Dados

A estruturação dos dados é um elemento central para o funcionamento do BI, pois garante que as análises apresentadas nos dashboards sejam consistentes e confiáveis. Conforme apresentado no Quadro 15, os dados estão organizados em quatro grupos principais: clientes, produtos, vendas e itens de venda. Essa organização permite não apenas armazenar informações, mas também relacioná-las entre si, possibilitando análises mais completas, como o cruzamento entre comportamento de compra e desempenho de produtos.

### Quadro 15 – Principais Entidades

| Entidade | Principais Variáveis |
|-----------|---------------------|
| Clientes | razao_social, nome_fantasia, CNPJ, cidade, estado, contato |
| Produtos | codigo, nome, categoria, preço, qtd_por_caixa, peso |
| Vendas | num_pedido, data, valor, CNPJ, vendedor |
| Produtos por Pedido | codigo, num_pedido, data, quantidade, valor, subtotal |

**Fonte:** Elaborada pelos autores (2026).

A partir dessa base estruturada, o sistema consegue, por exemplo, identificar quais produtos são mais vendidos por região ou quais clientes apresentam maior frequência de compra.

Complementando essa estrutura, o Quadro 16 demonstra como os dados poderão ser segmentados para análise. A utilização de categorias como tempo, cliente, produto e área comercial permite que os dashboards sejam dinâmicos, possibilitando ao usuário explorar diferentes perspectivas do negócio.

### Quadro 16 – Segmentação dos Dados (Filtros)

| Categoria | Filtros |
|------------|----------|
| Tempo | Ano, mês, trimestre |
| Cliente | Região, cidade |
| Produto | Categoria, nome |
| Comercial | Vendedor, porte da empresa |

**Fonte:** Elaborada pelos autores (2026).

Essa segmentação é essencial para identificar padrões, como sazonalidade de vendas, desempenho regional e comportamento de diferentes perfis de clientes.

Além da estrutura e segmentação, a qualidade dos dados é garantida por processos de validação. A padronização de formatos, a remoção de duplicidades e o tratamento de inconsistências asseguram que os indicadores apresentados nos dashboards reflitam a realidade do negócio. Dessa forma, os dados apresentados nos quadros não apenas organizam a informação, mas sustentam a confiabilidade de toda a solução de BI.

## 3.3 Planejamento dos Dashboards

O planejamento dos dashboards foi realizado com base nos dados estruturados apresentados anteriormente, garantindo que cada painel utilize informações consistentes e organizadas. Conforme o quadro de dashboards, cada painel possui um objetivo específico, alinhado às necessidades estratégicas da empresa, conforme sintetizado no Quadro 17.

### Quadro 17 – Planejamento dos Dashboards

| Dashboard | Objetivo | Principais Gráficos |
|------------|-----------|---------------------|
| Vendas | Monitorar desempenho | Faturamento mensal, evolução |
| Produtos | Avaliar portfólio | Curva ABC, ranking |
| Clientes | Analisar carteira | Ativos/inativos, frequência |

**Fonte:** Elaborada pelos autores (2026).

A partir desse quadro, observa-se que cada dashboard transforma os dados em informações visuais que facilitam a interpretação. Por exemplo, o dashboard de produtos utiliza a Curva ABC para evidenciar quais itens são mais relevantes para o faturamento, enquanto o dashboard de clientes permite identificar padrões de comportamento e possíveis perdas de receita.

Os filtros interativos apresentados complementam essa estrutura, permitindo ao usuário explorar os dados de forma dinâmica:

* **Período:** análise temporal e sazonalidade;
* **Região:** comparação geográfica;
* **Produto:** avaliação por categoria ou item;
* **Cliente:** análise individual ou segmentada.

Essa combinação entre dashboards e filtros possibilita análises mais profundas, tornando o BI uma ferramenta flexível e adaptável às necessidades do usuário. Além disso, a definição dos tipos de gráficos utilizados em cada painel foi realizada de forma estratégica, buscando facilitar a interpretação visual das informações e melhorar a compreensão dos indicadores apresentados conforme adiante.

A análise do Dashboard de Vendas (Ilustração 5) permite identificar padrões relevantes para a gestão comercial estratégica da empresa. Os indicadores posicionados no topo do painel — **Faturamento Total**, **Volume de Vendas**, **Ticket Médio** e **Pedidos Realizados** — fornecem uma visão consolidada do desempenho da operação, evidenciando crescimento consistente em relação ao ano anterior em todas as métricas apresentadas. O aumento de **12,4%** no faturamento total e de **8,7%** no volume de vendas, observados simultaneamente, indica expansão tanto em receita quanto em quantidade comercializada, sugerindo que o crescimento não decorre exclusivamente de reajustes de preços, mas reflete ganho real de demanda.

O gráfico de linha referente ao faturamento ao longo do tempo permite identificar o comportamento sazonal das vendas ao longo do ano. Observa-se uma tendência de crescimento gradual nos primeiros meses, com aceleração mais expressiva no segundo semestre, padrão coerente com a sazonalidade característica do setor de piscinas, no qual a demanda tende a se intensificar nos meses de primavera e verão, em função do aumento no uso e na manutenção das piscinas. Essa informação é estrategicamente relevante, pois possibilita o planejamento antecipado de estoques, ações comerciais e alocação da força de vendas nos períodos de maior procura, mitigando o risco de perda de oportunidades identificado no diagnóstico organizacional.

No que se refere à distribuição regional do faturamento, o gráfico de rosca evidencia uma concentração expressiva nas regiões Sudeste e Sul, que juntas representam aproximadamente **75%** da receita total. Esse dado corrobora a análise de mercado apresentada na Etapa 1, que identificou Minas Gerais como principal território de atuação da empresa. A participação das demais regiões — Nordeste (**14,3%**), Centro-Oeste (**6,2%**) e Norte (**4,6%**) — aponta para oportunidades de expansão geográfica ainda subexploradas, podendo orientar futuros direcionamentos estratégicos da força de vendas.

Por fim, o incremento de **9,1%** no número de pedidos realizados, aliado ao crescimento de **3,6%** no ticket médio, demonstra que a empresa ampliou tanto a frequência de transações quanto o valor médio por operação. Esse equilíbrio entre volume e valor indica maturidade comercial e reforça a eficácia das ações de relacionamento com a carteira de clientes. Tais informações, antes dependentes de tratamento manual em planilhas, passam a ser geradas de forma automática pelo sistema de BI, conforme proposto no presente projeto, reduzindo o tempo despendido na elaboração de relatórios e aumentando a confiabilidade das análises gerenciais.

### Ilustração 5 – Dashboard de Vendas

<img src="https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2026-1-pe8-t1-pmv-si-2026-1-pe8-t1-g2/blob/b667cd584bcbde69caa17be63335fa5ab6ea029c/docs/images/Ilustra%C3%A7%C3%A3o%205.jpg" alt="Ilustração 5 – Dashboard de Vendas" width="800"/>

**Fonte:** Elaborada pelos autores (2026).

A Ilustração 6 apresenta um **Dashboard de Produtos** que segue uma hierarquia analítica tradicional, iniciando com segmentadores de dados na parte superior. Esses filtros oferecem interatividade ao relatório, permitindo recortes temporais e mercadológicos.

Abaixo dos filtros, os dados consolidados são expostos por meio de cartões numéricos. Essa seção entrega um panorama rápido das métricas absolutas, como faturamento e total de itens. O corpo principal do dashboard é focado na priorização comercial. A aplicação de um gráfico de combinação (colunas e linha) foi a escolha metodológica para representar a Curva ABC. Essa visualização apoia-se no Princípio de Pareto para classificar o portfólio, demonstrando quais faixas de produtos concentram o maior impacto no faturamento acumulado.

Por fim, a análise do portfólio é complementada por um gráfico de barras horizontais, que elenca os cinco itens mais vendidos. A disposição horizontal é ideal para ranqueamentos, pois acomoda melhor os rótulos de texto e permite comparações objetivas entre o desempenho de cada produto listado.

### Ilustração 6 – Dashboard de Produtos

<img src="https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2026-1-pe8-t1-pmv-si-2026-1-pe8-t1-g2/blob/b667cd584bcbde69caa17be63335fa5ab6ea029c/docs/images/Ilustra%C3%A7%C3%A3o%206.jpg" alt="Ilustração 6 – Dashboard de Produtos" width="800"/>

**Fonte:** Elaborada pelos autores (2026).

Por sua vez, o Dashboard de Clientes na Ilustração 7 utiliza o gráfico de pizza para demonstrar a proporção entre clientes ativos e inativos, permitindo rápida percepção do nível de retenção da carteira. O gráfico de colunas foi aplicado na análise de frequência de compra, facilitando a comparação entre diferentes níveis de recorrência. Complementando a análise, o ranking de clientes foi representado por barras horizontais, destacando os clientes com maior relevância financeira para a empresa.

### Ilustração 7 – Dashboard de Clientes

<img src="https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2026-1-pe8-t1-pmv-si-2026-1-pe8-t1-g2/blob/b667cd584bcbde69caa17be63335fa5ab6ea029c/docs/images/Ilustra%C3%A7%C3%A3o%207.jpg" alt="Ilustração 7 – Dashboard de Clientes" width="800"/>

**Fonte:** Elaborada pelos autores (2026).

A escolha desses gráficos contribui para tornar os dashboards mais intuitivos e alinhados às práticas utilizadas em ferramentas de BI, como o Microsoft Power BI. Dessa forma, as visualizações facilitam a interpretação dos dados e fortalecem o uso das informações no apoio à tomada de decisão estratégica.

## 3.4 Início da Construção e Automação

O início da construção da solução de BI ocorreu a partir da consolidação das definições estabelecidas nas etapas anteriores, contemplando a modelagem de dados, o planejamento dos dashboards e os requisitos informacionais levantados. Essa fase marca a transição conceitual para a implementação prática da solução, com foco na automação do tratamento dos dados e na geração contínua de informações analíticas confiáveis.

A construção do BI seguiu um fluxo estruturado (Quadros 18 e 19) de etapas técnicas, garantindo consistência e rastreabilidade desde a origem dos dados até a visualização final nos dashboards.

### Quadro 18 – Etapas de Construção do BI

| Etapa | Descrição |
|---------|------------|
| Conexão de dados | Importação e integração das fontes |
| Modelagem | Relacionamento entre tabelas |
| KPIs | Criação dos indicadores |
| Visualização | Desenvolvimento dos dashboards |
| Testes | Validação das informações |

**Fonte:** Elaborada pelos autores (2026).

### Quadro 19 – Automação dos Processos Analíticos e Benefícios Operacionais

| Elemento Automatizado | Situação Anterior | Situação com BI Automatizado | Benefício Gerado |
|----------------------|------------------|-----------------------------|------------------|
| Atualização de dados | Manual em planilhas | Importação automática | Redução de erros |
| Padronização de dados | Ajustes manuais | Processos padronizados | Consistência analítica |
| Cálculo de KPIs | Cálculo manual | KPIs automáticos | Agilidade e uniformidade |
| Relatórios | Estáticos | Dashboards dinâmicos | Suporte à decisão |
| Acesso à informação | Arquivos dispersos | Base centralizada | Visão integrada |

**Fonte:** Elaborada pelos autores (2026).

A conexão dos dados foi realizada a partir da importação dos arquivos extraídos do sistema ERP Mercos, complementados por planilhas eletrônicas utilizadas nos controles comerciais da empresa. Esse procedimento possibilitou a centralização das informações em um único ambiente analítico, reduzindo a fragmentação anteriormente existente e estabelecendo uma base integrada para as análises gerenciais.

Na etapa de modelagem dos dados, foram definidos os relacionamentos entre as principais entidades — clientes, produtos, vendas e itens de venda — permitindo análises cruzadas e comparativas. Essa estrutura relacional viabiliza, por exemplo, análises de desempenho de produtos ao longo do tempo, comportamento de compra dos clientes e evolução do faturamento por período, conforme os filtros e dimensões planejados nos dashboards.

O tratamento e a padronização dos dados consistiram na adequação de formatos de datas, valores monetários, volumes e categorias de produtos, bem como na eliminação de registros duplicados e na correção de inconsistências geradas por processos manuais anteriores. Essa etapa é fundamental para garantir a integridade dos dados e a confiabilidade dos indicadores apresentados, atendendo aos princípios de qualidade da informação exigidos em soluções de BI.

A definição dos indicadores-chave de desempenho (KPIs) foi orientada diretamente pelas Key Intelligence Questions (KIQs), assegurando o alinhamento entre os objetivos estratégicos do projeto e os resultados analíticos produzidos. Entre os principais indicadores implementados destacam-se a Curva ABC de produtos, a evolução do faturamento, o volume de vendas por período, o ranking de clientes e a identificação de produtos com baixo giro. A automatização desses indicadores reduz a dependência de análises manuais e assegura a utilização de critérios uniformes.

Na fase de visualização, os dashboards foram desenvolvidos com o uso de gráficos e indicadores consolidados, proporcionando uma representação clara e sintética das informações. Esses painéis permitem a rápida interpretação dos dados e facilitam a identificação de padrões, tendências e sazonalidades, apoiando a tomada de decisão gerencial.

Por fim, foram conduzidos testes e validações com o objetivo de comparar os resultados apresentados nos dashboards com os dados originais das fontes utilizadas. Essa verificação assegura que os valores exibidos reflitam fielmente a realidade operacional da empresa, aumentando a confiabilidade do sistema e reduzindo o risco de interpretações equivocadas.

A automação implementada nesta etapa elimina a necessidade de atualizações manuais recorrentes, possibilitando a atualização periódica dos dados de forma padronizada. Assim, a solução de BI consolida-se como um sistema contínuo de apoio à gestão comercial, fornecendo informações consistentes, atualizadas e alinhadas às necessidades estratégicas da organização.

## 3.5 Análise das Informações Apresentadas nos Dashboards

Com os dashboards estruturados e os indicadores definidos, torna-se possível analisar as informações de forma estratégica, transformando dados em suporte para a tomada de decisão. As visualizações permitem identificar padrões, tendências e oportunidades relacionadas ao desempenho comercial, produtos e clientes.

Dessa forma, os dashboards apresentados nas Ilustrações 8, 9 e 10 permitem responder diretamente às KIQs definidas no Plano de Inteligência Competitiva, fornecendo informações estratégicas sobre desempenho de vendas, relevância dos produtos e comportamento dos clientes, cujas análises e interpretações serão apresentadas a seguir.

### Ilustração 8 – Volume de Vendas por Produto

<img src="https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2026-1-pe8-t1-pmv-si-2026-1-pe8-t1-g2/blob/b667cd584bcbde69caa17be63335fa5ab6ea029c/docs/images/Ilustra%C3%A7%C3%A3o%208.jpg" alt="Ilustração 8 – Volume de Vendas por Produto" width="800"/>

**Fonte:** Elaborada pelos autores (2026).

Com base no Dashboard da Ilustração 8, é possível identificar que os produtos **LE 3X1**, **Sulfato Alumínio**, **Genfloc** e **Genclor** concentram os maiores volumes de vendas da empresa por serem itens essenciais e recorrentes no tratamento e manutenção de piscinas. O LE 3X1 destaca-se como o produto mais vendido devido à sua praticidade e versatilidade, já que reúne múltiplas funções em uma única solução, o que aumenta sua procura pelos clientes.

O Sulfato Alumínio apresenta alto volume de vendas por ser amplamente utilizado nos processos de limpeza e decantação da água, tornando-se um produto de uso frequente e necessário para manutenção. Já o Genfloc possui forte participação por atuar como complemento no tratamento da água, sendo frequentemente utilizado em conjunto com outros produtos principais.

O Genclor, por sua vez, mantém relevância nas vendas devido à necessidade constante de cloração e higienização da piscina, representando um item de consumo recorrente. Dessa forma, o gráfico demonstra que os produtos mais vendidos são justamente aqueles ligados às etapas básicas e indispensáveis do tratamento da água, o que explica sua maior demanda em comparação aos demais itens do portfólio.

### Ilustração 9 – Análise de Clientes

<img src="https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2026-1-pe8-t1-pmv-si-2026-1-pe8-t1-g2/blob/b667cd584bcbde69caa17be63335fa5ab6ea029c/docs/images/Ilustra%C3%A7%C3%A3o%209.jpg" alt="Ilustração 9 – Análise de Clientes" width="800"/>

**Fonte:** Elaborada pelos autores (2026).

Infere-se da Ilustração 9 que a base total da empresa compreende **334 clientes**, com **212 ativos (63,47%)** e **122 inativos (36,53%)**, além de **45 novos clientes** captados no período. A taxa de inatividade de **37%** representa uma oportunidade significativa de recuperação de receita através de estratégias de reengajamento, enquanto a captação de novos clientes demonstra dinamismo comercial e capacidade de expansão da base.

O perfil da carteira é caracterizado pela predominância absoluta de clientes de pequeno porte, que respondem por **159 compras** - a maioria esmagadora do volume de transações. Esta concentração apresenta vantagens (diversificação de risco, capilaridade de mercado, relacionamento próximo) e desafios (ticket médio menor, maior custo relativo de atendimento, risco de inadimplência). Os pedidos destes clientes variam entre 1 e 9 transações, com o cliente mais ativo registrando 9 pedidos no período analisado.

Um paradoxo estratégico relevante emerge da análise: embora as distribuidoras registrem apenas **66 compras** (contra 159 do pequeno porte), este número supera significativamente médio porte (**39 compras**) e grande porte (**25 compras**) somados (**64 compras**). As distribuidoras operam com modelo baseado em alta rotatividade de estoque, comprando frequentemente para revender rapidamente, trabalhando com margens menores compensadas pelo giro acelerado. Sua capacidade de negociar preços melhores decorre do volume consolidado, pagamento ágil, relacionamento estratégico e recorrência previsível, permitindo-lhes girar mercadoria com maior competitividade no mercado. Este segmento merece atenção estratégica prioritária por demonstrar recorrência, capacidade de giro e modelo de negócio alinhado com fornecimento constante.

O baixo volume de médio e grande porte (**64 compras combinadas**) indica subaproveitamento deste segmento: médias empresas compram volumes maiores, mas menos frequentemente, mantendo estoque estratégico, enquanto grandes empresas podem ter fontes alternativas, negociação direta com fabricantes ou contratos de longo prazo com entregas programadas, resultando em menos transações, porém de maior valor unitário.

Recomendações estratégicas prioritárias: (1) Reativar 30% dos clientes inativos através de campanha segmentada com condições especiais; (2) Fortalecer canal de distribuidoras com programa de parceria exclusivo, condições diferenciadas e co-marketing, aproveitando seu desempenho superior; (3) Expandir penetração em médio/grande porte através de vendedores especializados, contratos anuais e serviços agregados, visando dobrar as 64 compras atuais; (4) Otimizar atendimento ao pequeno porte através de automação (e-commerce/app) e incentivo a compras consolidadas.

A empresa possui base diversificada que reduz risco de concentração, porém com oportunidades claras de otimização. O destaque positivo são as distribuidoras que, apesar de representarem menos transações que o pequeno porte, superam médio e grande porte combinados, demonstrando modelo de negócio superior para crescimento sustentável. Os 122 clientes inativos (37%) representam potencial de crescimento sem custo de aquisição, enquanto o segmento médio/grande porte está subexplorado.


### Ilustração 10 – Vendas em 2026

<img src="https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2026-1-pe8-t1-pmv-si-2026-1-pe8-t1-g2/blob/b667cd584bcbde69caa17be63335fa5ab6ea029c/docs/images/Ilustra%C3%A7%C3%A3o%2010.jpg" alt="Ilustração 10 – Vendas em 2026" width="800"/>

**Fonte:** Elaborada pelos autores (2026).

O Dashboard de Vendas em 2026 demonstra um cenário bastante positivo para a empresa, com as vendas apresentando desempenho significativamente superior à meta estabelecida para o período. Os dados indicam que o volume comercializado atingiu quase o dobro do valor projetado, evidenciando crescimento expressivo da operação e ampliação da participação da empresa no mercado.

Esse desempenho pode ser explicado, em parte, pelo enfraquecimento da concorrência, já que algumas empresas do setor vêm enfrentando dificuldades financeiras e até encerrando suas atividades. Esse cenário criou oportunidades de mercado importantes, permitindo a conquista de novos clientes, expansão da carteira e aumento da demanda pelos produtos comercializados pela empresa.

Em relação à distribuição regional das vendas, observa-se uma forte concentração na região da **Grande Belo Horizonte**, responsável pela maior parcela do faturamento apresentado no gráfico. Esse resultado demonstra a relevância estratégica da região para os negócios da empresa, evidenciando uma presença comercial consolidada e um mercado com elevado potencial de consumo.

O gráfico também apresenta uma participação significativa da categoria **Em Branco**. Nesse caso, esses registros correspondem a empresas que possuem matriz em Minas Gerais, mas operam com unidades localizadas fora do estado. Isso demonstra que, apesar do faturamento estar vinculado administrativamente a Minas Gerais, a atuação comercial da empresa possui alcance regional mais amplo, expandindo sua presença para além do mercado mineiro.
