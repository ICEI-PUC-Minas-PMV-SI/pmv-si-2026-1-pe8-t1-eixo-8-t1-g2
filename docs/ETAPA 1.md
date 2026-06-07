# 1 Apresentação da Empresa, Mercado, Processos e Sistemas

## 1.1 Apresentação da Empresa

A empresa selecionada para este estudo de caso é uma empresa de Representação Comercial voltada para a venda de produtos químicos para tratamento de água de piscinas. A empresa opera no modelo B2B (*Business to Business*), intermediando a venda entre a fábrica e as revendas (lojas de piscinas, materiais de construção, produtos de limpeza e distribuidoras).

A empresa é uma organização de pequeno porte sediada em Belo Horizonte, Minas Gerais, e possui três colaboradores, sendo constituída pelo proprietário e dois vendedores. Com mais de trinta e cinco anos de atuação no mercado, a empresa possui amplo conhecimento sobre grande parte das lojas que trabalham com produtos para piscinas no estado de Minas Gerais.

O processo da empresa envolve a negociação de vendas com os clientes, bem como a realização de visitas recorrentes. Nessas visitas são conduzidos treinamentos sobre os produtos, avaliadas as necessidades das lojas, sugeridas melhorias, verificado o nível de estoque e analisadas as condições do mercado. Além disso, essas interações contribuem para o fortalecimento da parceria com os clientes.

A empresa utiliza um sistema SaaS (*Software as a Service*) de terceiros para realizar o controle das vendas. O sistema foi contratado em julho de 2014 e, desde então, todo o fluxo de vendas da organização vem sendo armazenado em sua base de dados.

### Justificativa da Escolha

Uma empresa do ramo de Representação Comercial foi escolhida por apresentar oportunidades relevantes para implementação de soluções tecnológicas voltadas à otimização e automação de processos de negócio. Entre os benefícios esperados destacam-se:

* Maior controle sobre os dados de vendas;
* Automação de processos operacionais;
* Melhor acompanhamento do desempenho comercial;
* Apoio à tomada de decisões baseada em dados.

---

## 1.2 Análise de Mercado

Atualmente o Brasil ocupa a segunda posição mundial no mercado de piscinas, ficando atrás apenas dos Estados Unidos. Esse cenário evidencia um mercado de grande potencial e elevada competitividade.

O mercado de distribuição e representação de produtos químicos para piscinas e limpeza caracteriza-se pela presença de:

* Grandes distribuidoras nacionais;
* Representantes regionais de médio porte;
* Pequenos representantes comerciais;
* Plataformas especializadas de comércio eletrônico.

A competição ocorre principalmente por meio dos seguintes fatores:

* Preço;
* Prazo de entrega;
* Disponibilidade de estoque;
* Suporte técnico.

Além da concorrência entre estabelecimentos que comercializam os mesmos produtos, existe também a concorrência entre representantes que atuam com marcas diferentes na mesma região.

Dessa forma, os principais diferenciais competitivos observados são:

* Qualidade dos produtos comercializados;
* Proximidade com os clientes;
* Agilidade no atendimento;
* Capacidade de oferecer suporte técnico consultivo.

Para analisar os ambientes interno e externo da organização foi realizada uma Análise SWOT.

> **Ilustração 1 – Matriz SWOT**
>
> Inserir imagem:
>
> ```text
> imagens/ilustracao-01-matriz-swot.png
> ```
>
> Fonte: Elaborada pelos autores (2026).

---

## 1.3 Análise de Processos e Sistemas

O desenvolvimento deste projeto permitirá a transição de uma gestão predominantemente descritiva para uma cultura orientada a dados, possibilitando previsões de vendas mais precisas e a atualização de processos atualmente executados de forma manual.

### 1.3.1 Mapeamento de Processos (BPMN)

O processo atual do fluxo de vendas é composto pelas seguintes etapas:

1. Contato da empresa com o cliente para levantamento de necessidades;
2. Recebimento do orçamento solicitado;
3. Consulta de tabelas de preços e descontos;
4. Registro do orçamento no ERP;
5. Confirmação do pedido pelo cliente;
6. Envio do pedido para a fábrica;
7. Acompanhamento pós-venda.

> **Ilustração 2 – Processo de Vendas**
>
> Inserir imagem:
>
> ```text
> imagens/ilustracao-02-processo-vendas.png
> ```
>
> Fonte: Elaborada pelos autores (2026).

### Processo de Previsão de Vendas Futuras

O fluxo atualmente utilizado para previsão de vendas segue as seguintes etapas:

1. Extração das vendas do último ano no ERP;
2. Tratamento dos dados em planilhas Excel;
3. Atualização da tabela de projeções;
4. Alimentação da planilha de previsão de vendas.

> **Ilustração 3 – Processo de Previsão de Vendas Futuras**
>
> Inserir imagem:
>
> ```text
> imagens/ilustracao-03-previsao-vendas.png
> ```
>
> Fonte: Elaborada pelos autores (2026).

### Processo de Registro e Previsão de Visitas

O fluxo atual de visitas comerciais compreende:

1. Planejamento anual das rotas;
2. Definição semanal das visitas;
3. Realização das visitas aos clientes;
4. Registro das informações em grupo corporativo do WhatsApp.

> **Ilustração 4 – Processo de Registro e Previsão de Visitas**
>
> Inserir imagem:
>
> ```text
> imagens/ilustracao-04-visitas-comerciais.png
> ```
>
> Fonte: Elaborada pelos autores (2026).

### 1.3.2 Sistemas de Informação e Maturidade

A empresa utiliza o ERP Mercos, uma plataforma SaaS voltada para representantes comerciais que centraliza:

* Gestão de clientes;
* Gestão de pedidos;
* Emissão de orçamentos;
* Relatórios comerciais.

Entre os principais relatórios disponíveis destacam-se:

#### Carteira de Clientes

Contém informações como:

* Nome;
* CNPJ;
* Cidade;
* Estado;
* Dados cadastrais complementares.

#### Relatório de Vendas

Disponibiliza informações relacionadas a:

* Data da venda;
* Cliente comprador;
* Valor total da venda.

#### Produtos por Pedido

Apresenta:

* Código do produto;
* Nome do produto;
* Quantidade vendida;
* Valor unitário;
* Valor total.

Apesar dessas funcionalidades, os recursos analíticos e preditivos ainda são limitados, exigindo o uso complementar de planilhas eletrônicas.

Outro ponto crítico refere-se ao registro das visitas comerciais, atualmente realizado apenas por meio de mensagens em grupos do WhatsApp, dificultando a rastreabilidade e recuperação histórica das informações.


### 1.3.3 Informações Técnicas

* **ERP utilizado:** Mercos ERP;
* **Armazenamento de dados:** banco de dados em nuvem do Mercos e armazenamento local.


### 1.3.4 Gargalos Operacionais

Os principais gargalos identificados foram:

* Atualização manual de planilhas;
* Tratamento manual dos dados;
* Ausência de modelos preditivos;
* Dificuldade em antecipar demandas sazonais;
* Dependência de conhecimento tácito para planejamento comercial.


### 1.3.5 Potencial de Melhoria

A implementação de soluções de Business Intelligence permitirá:

* Automatização da análise de vendas;
* Previsão de demanda futura;
* Definição automática de metas;
* Centralização das informações de visitas;
* Redução de atividades manuais.

Entre os benefícios esperados destacam-se:

* **Medição da Eficiência Comercial,** avaliação da frequência de visitas e seus resultados;
* **Gestão de Clientes Inativos,** identificação de clientes com potencial de compra que não recebem acompanhamento adequado;
* **Histórico de Relacionamento,** centralização das informações discutidas durante visitas comerciais;
* **Roteirização Logística,** otimização dos deslocamentos por meio do agrupamento geográfico de clientes.

A maturidade digital da empresa pode ser classificada como **intermediária**, pois já existe utilização de sistemas informatizados para gestão operacional. Entretanto, ainda há espaço significativo para evolução no uso estratégico dos dados, especialmente em análises preditivas, planejamento comercial e gestão estruturada das visitas.
