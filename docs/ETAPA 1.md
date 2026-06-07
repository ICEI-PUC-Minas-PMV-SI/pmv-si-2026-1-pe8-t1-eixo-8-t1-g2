# 1 Apresentação da Empresa, Mercado, Processos e Sistemas

## 1.1 Apresentação da Empresa

A empresa selecionada para este estudo de caso é uma empresa de Representação Comercial voltada para a venda de produtos químicos para tratamento de água de piscinas. A empresa opera no modelo B2B (Business to Business), intermediando a venda entre a fábrica e as revendas (lojas de piscinas, materiais de construção, produtos de limpeza e distribuidoras).

A empresa é uma organização de pequeno porte sediada em Belo Horizonte, Minas Gerais e possui 3 colaboradores, sendo constituída pelo proprietário e dois vendedores. Com mais de trinta e cinco anos de atuação no mercado, a empresa possui conhecimento sobre grande parte das lojas que trabalham com produtos de piscinas no estado de Minas Gerais. 

O processo da empresa envolve a negociação de vendas com os clientes, bem como a realização de visitas recorrentes. Nessas visitas são conduzidos treinamentos sobre os produtos, avaliadas as necessidades das lojas, sugeridas possíveis melhorias, verificado o nível de estoque e analisadas as condições do mercado. 

Além disso, essas interações contribuem para o fortalecimento e estreitamento da parceria com os clientes.
A empresa possui um SaaS (Software as a Service) de terceiros para fazer o controle das vendas, que foi contratado em julho de 2014, sendo que, a partir desta data, todo o fluxo de vendas da empresa vem sendo armazenado na base de dados do software. 

**Justificativa da Escolha:** Uma empresa do ramo da Representação Comercial é uma escolha estratégica para o projeto, tendo em vista a possibilidade de implementar soluções assertivas e tecnológicas voltadas à otimização e automação do modelo de negócio, trazendo vantagens competitivas para a empresa, como o maior controle dos dados de vendas e fluxos operacionais internos.

---


## 1.2 Análise de Mercado

Atualmente o Brasil é o segundo maior mercado de piscinas do mundo, ficando atrás somente dos Estados Unidos (ANAPP, 2025). Assim, o mercado de piscinas brasileiro demanda alta competência e desperta atenção dos muitos lojistas. Dessa forma, torna-se desafiador para as empresas que atuam nesse mercado tanto se organizarem adequadamente quanto atender, com excelência, a todo o seu potencial de demanda.

O mercado de distribuição e representação de produtos químicos para piscinas e limpeza no Brasil é fragmentado, com a presença de grandes distribuidoras nacionais, representantes regionais de médio e pequeno porte e, cada vez mais, plataformas de e-commerce especializadas. A competição se dá principalmente em preço, prazo de entrega, disponibilidade de estoque e suporte técnico.

Além da concorrência entre lojas que vendem o mesmo produto, também existe a concorrência entre representantes da mesma localidade que trabalham com outras marcas de produtos químicos para piscinas. Dessa forma, o diferencial competitivo reside, além do principal que é a qualidade do produto vendido, na proximidade com o cliente, na agilidade de atendimento e no suporte técnico consultivo. 

Com o objetivo de analisar o ambiente interno e externo da empresa, foi realizada uma Análise SWOT. Os resultados dessa análise são apresentados na Ilustração 1, por meio da matriz SWOT elaborada para o contexto da empresa estudada.


**Ilustração 1 – Matriz SWOT**

<img src="https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2026-1-pe8-t1-pmv-si-2026-1-pe8-t1-g2/blob/272e4a2e715ec9c08e8d6652d30177c4f2cbe88c/docs/images/Ilustra%C3%A7%C3%A3o%201.jpg" alt="Ilustração 1 – Matriz SWOT"/>

Fonte: Elaborada pelos autores (2026).

---


## 1.3 Análise de Processos e Sistemas

O desenvolvimento deste projeto permitirá a transição de uma gestão predominantemente descritiva para uma cultura orientada a dados, possibilitando previsões de vendas mais precisas e a atualização de processos atualmente executados de forma manual.


### 1.3.1 Mapeamento de Processos (BPMN)

O processo atual do fluxo de vendas é representado na Ilustração 2, e suas etapas são descritas a seguir:

*	**Contato da Empresa ao Cliente:** A empresa entra em contato com o cliente para verificação de possível orçamento via e-mail ou Whatsapp;
*	**Recebimento Orçamento:** O cliente envia os itens e quantidades que deseja orçamento;
*	**Consulta de Tabela:** O vendedor consulta planilhas de Excel para verificar preços do cliente e descontos vigentes;
*	**Registro do Orçamento:** Lançamento do orçamento no sistema Mercos (ERP utilizado pela empresa);
*	**Confirmação do pedido pelo Cliente:** O cliente envia por Whatsapp ou e-mail a confirmação do pedido / ordem de compra;
*	**Envio à Fábrica:** O pedido é repassado ao sistema do fabricante para faturamento;
*	**Acompanhamento do pós-venda:** Verificação de data de faturamento do pedido e se todas as mercadorias foram faturadas, e se a mercadoria chegou de forma correta ao cliente.


**Ilustração 2 – Processo de Vendas**

<img src="https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2026-1-pe8-t1-pmv-si-2026-1-pe8-t1-g2/blob/272e4a2e715ec9c08e8d6652d30177c4f2cbe88c/docs/images/Ilustra%C3%A7%C3%A3o%202.jpg" alt="Ilustração 2 – Processo de Vendas" width="600"/>

Fonte: Elaborada pelos autores (2026).

O processo atual do fluxo de previsão de vendas futuras é apresentado na Ilustração 3, e suas etapas são descritas a seguir:

*	**Extração de vendas do último ano no Mercos:** Através do ERP, é extraído um arquivo .xlsx com os dados de vendas passadas;
*	**Tratamento do arquivo:** O arquivo é tratado e por meio de tabelas dinâmicas do Excel, é possível ver a progressão de compra de cada cliente;
*	**Atualização da tabela de vendas:** A partir da frequência de compra do cliente e potencial de compra, é determinado quanto é esperado que ele compre no mês futuro;
*	**Alimentação da planilha de previsão de vendas:** A partir das compras realizadas no mês previsto, a planilha de previsão vai sendo preenchidas com as vendas realizadas.


**Ilustração 3 – Processo de Previsão de Vendas Futuras**

<img src="https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2026-1-pe8-t1-pmv-si-2026-1-pe8-t1-g2/blob/272e4a2e715ec9c08e8d6652d30177c4f2cbe88c/docs/images/Ilustra%C3%A7%C3%A3o%203.jpg" alt="Ilustração 3 – Processo de Previsão de Vendas Futuras" width="600"/>

Fonte: Elaborada pelos autores (2026).

O processo atual do fluxo de registro e previsão de visitas futuras é apresentado na Ilustração 4, e suas etapas são descritas a seguir:

*	**Planejamento das Rotas de Visitas do Ano:** No início de cada ano, é feita uma previsão de visita às regiões do estado, para que a cada 2 meses os lojistas sejam visitados para firmar relacionamentos e novas parcerias;
*	**Definição da Rota de Visita da Semana:** Uma semana antes, o vendedor define as lojas da região que será atendida, fazendo o agendamento da visita com os clientes;
*	**Realização das visitas:** Durante a semana o vendedor (representante) visita os lojistas da região determinada pela rota;
*	**Registro de visitas:** Após a visita é registrado em um grupo no whatsapp o que ocorreu na visita, quais são os pontos que o representante precisa dar um retorno da loja, e o que foi apresentado de novidade ao lojista.


**Ilustração 4 – Processo de Registro e Previsão de Visitas**

<img src="https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2026-1-pe8-t1-pmv-si-2026-1-pe8-t1-g2/blob/272e4a2e715ec9c08e8d6652d30177c4f2cbe88c/docs/images/Ilustra%C3%A7%C3%A3o%204.jpg" alt="Ilustração 4 – Processo de Registro e Previsão de Visitas" width="800"/>

Fonte: Elaborada pelos autores (2026).


### 1.3.2 Sistemas de Informação e Maturidade

A empresa utiliza o sistema ERP Mercos ERP, uma plataforma SaaS (Software as a Service) voltada para representantes comerciais que centraliza a gestão de pedidos, clientes e relatórios em um único ambiente acessível via web. A ferramenta permite a elaboração de orçamentos, o registro de pedidos de clientes e a geração de relatórios comerciais, contribuindo para a organização das operações de vendas.

Além dessas funcionalidades operacionais, o sistema também possibilita a extração de alguns dados relacionados às vendas, que podem ser utilizados para análise e acompanhamento do desempenho comercial. Entre os principais relatórios disponíveis, destacam-se:

*	**Carteira de clientes:** contém informações sobre as lojas presentes na carteira da empresa, incluindo dados como nome, CNPJ, cidade, estado e informações adicionais relevantes sobre cada cliente;
*	**Relatório de vendas:** apresenta informações detalhadas das vendas realizadas, como data da venda, loja que realizou a compra e valor total vendido;
*	**Produtos por pedido:** relatório que detalha os itens comercializados em cada pedido, contendo dados como código do produto, nome do produto, quantidade adquirida, valor unitário e valor total.

Apesar dessas funcionalidades, observa-se que os recursos gerenciais voltados à análise estratégica e à previsão de vendas ainda são limitados. Dessa forma, embora o ERP seja utilizado para registrar e organizar as transações comerciais, os dados disponíveis não são plenamente explorados para subsidiar a tomada de decisões e o planejamento comercial.

Outro ponto relevante diz respeito ao registro das visitas comerciais. Atualmente, essas informações não são armazenadas em um sistema estruturado ou planilha de controle. Os registros são realizados apenas em um grupo de WhatsApp, que funciona informalmente como um bloco de notas. Como consequência, muitos desses registros acabam se perdendo ao longo do tempo, dificultando o acompanhamento histórico das interações com os clientes. Essa situação evidencia a necessidade de maior controle e organização dessas informações, incluindo o registro estruturado de dados como a data das visitas realizadas e os principais pontos discutidos em cada atendimento.


### 1.3.3 Informações Técnicas

* **ERP utilizado:** mercos.com;
* **Armazenamento de dados:** Banco de dados em nuvem do Mercos e armazenamento local em computador.


### 1.3.4 Gargalos Operacionais

O principal gargalo identificado está relacionado à atualização e ao tratamento das tabelas utilizadas para análise das vendas. Atualmente, a ausência de um sistema preditivo impede que a empresa se antecipe a variações sazonais de demanda, como o aumento da procura por aquecedores durante o período de inverno. Como consequência, podem ocorrer perdas de oportunidades comerciais decorrentes da falta de planejamento antecipado. 


### 1.3.5 Potencial de Melhoria

Existe uma oportunidade clara de melhoria por meio da utilização de bibliotecas de manipulação de dados e modelos estatísticos para automatizar processos de análise, como o cálculo de metas e a previsão anual de vendas. Além disso, torna-se recomendável a implementação de um módulo estruturado para coleta e armazenamento de dados de visitas comerciais, permitindo a centralização dessas informações.

A adoção desse tipo de solução possibilitaria diversos benefícios gerenciais, tais como:

* **Medição da eficiência comercial,** por meio do acompanhamento da frequência e dos resultados das visitas;
* **Gestão da carteira de clientes inativos,** permitindo identificar clientes que compram regularmente, mas que não recebem visitas há um longo período;
* **Histórico de relacionamento com clientes,** centralizando informações relevantes discutidas durante as visitas, como feedbacks sobre preços, marcas ou níveis de estoque;
* **Roteirização logística das visitas,** possibilitando otimizar deslocamentos dentro do estado de Minas Gerais por meio do agrupamento de clientes por proximidade geográfica, reduzindo custos de viagem e tempo de deslocamento.

Nesse contexto, a maturidade digital da empresa pode ser classificada como intermediária, pois já existe a utilização de um sistema informatizado para gestão de pedidos e clientes. No entanto, ainda há espaço significativo para evolução no uso estratégico dos dados, especialmente no que se refere à análise preditiva, ao planejamento comercial e à gestão estruturada das visitas aos clientes.
