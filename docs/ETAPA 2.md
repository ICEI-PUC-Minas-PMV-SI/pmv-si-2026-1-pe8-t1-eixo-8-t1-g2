# 2. PLANO DE INTELIGÊNCIA COMPETITIVA (IC)

## 2.1 Identificação das Necessidades de IC

A organização em análise enfrenta gargalos operacionais e estratégicos relacionados à defasagem na adoção tecnológica, à subutilização de dados gerados por sistemas SaaS (Software as a Service) e à dificuldade de antever tendências de consumo.

Diante do cenário de transformação digital e da necessidade de mitigação de riscos mercadológicos, o corpo diretivo da organização necessita deliberar sobre as seguintes questões estratégicas:

**Adoção Tecnológica e Maturidade Analítica:** Avaliar a viabilidade e o retorno sobre o investimento (ROI) da implementação de ferramenta de análise preditiva.

**Gestão de Portfólio e Otimização da Oferta:** Determinar a viabilidade de uma reestruturação do catálogo de produtos, embasada na análise de dados históricos, com o objetivo de concentrar os esforços comerciais da força de vendas nos itens de maior rentabilidade e suprimir a oferta de ativos de baixo giro.

**Mitigação de Impactos Sazonais:** Estruturar diretrizes para campanhas de vendas e gestão de inventário nos canais de distribuição durante os períodos de retração de demanda (sazonalidade de inverno), utilizando a modelagem de dados históricos de vendas.

Considerando a escassez de recursos humanos dedicados à frente comercial, a alocação eficiente de tempo e esforço apresenta-se como o fator crítico de sucesso mais urgente para a sustentabilidade da empresa. Dessa forma, a decisão-chave priorizada refere-se à Gestão de Portfólio e Otimização da Oferta.

**Key Intelligence Topic (KIT):** Avaliação de desempenho do portfólio de produtos químicos, visando à otimização da oferta e ao direcionamento estratégico de vendas no estado de Minas Gerais, fundamentada no cruzamento de dados históricos extraídos de sistemas SaaS.

Para subsidiar a resolução do KIT proposto e promover uma transição de um modelo de gestão intuitivo para um modelo fundamentado em evidências (*data-driven*), o processo de coleta e mineração de dados deverá ser norteado pelas seguintes perguntas investigativas:

**Análise de Pareto (Curva ABC):** Quais produtos do catálogo atual compõem o percentual correspondente a 80% do faturamento bruto e das comissões auferidas pela representação comercial?

**Sensibilidade de Mercado:** Quais itens do portfólio apresentam a menor elasticidade-preço da demanda, permitindo maior margem de manobra em negociações B2B?

**Giro de Inventário e Obsolescência:** Quais mercadorias exibem o ciclo de vendas mais extenso, caracterizando estagnação no inventário das revendas (capital imobilizado) há um período prolongado?

A definição deste KIT e a consequente investigação de suas respectivas KIQs são importantes para a consolidação da vantagem competitiva da organização. Em estruturas organizacionais enxutas, a dispersão do esforço de vendas em produtos de baixo valor agregado configura ineficiência operacional.

A resposta às questões formuladas viabilizará o embasamento empírico necessário para a tomada de decisão. Ao mapear os ativos de maior rentabilidade e giro (Curva ABC), compreender a elasticidade-preço da demanda e identificar produtos com ciclo de venda mais lento, a empresa poderá reconfigurar seu posicionamento no mercado.

Esse movimento estratégico não apenas otimiza o tempo da força de vendas, mas também maximiza a geração de receita, reduz custos transacionais e fortalece o papel da representação comercial como um parceiro analítico e consultivo perante as revendas, transcendendo a mera função de intermediação.

---

## 2.2 Mapeamento de Dados e Identificação das Necessidades de Informação

A análise das KIQs permitiu identificar três frentes principais para avaliação do desempenho do portfólio:

- Curva ABC;
- Análise de elasticidade-preço;
- Estudo do giro de produtos.

Essas abordagens orientam a definição das informações necessárias para apoiar a tomada de decisão comercial.

### Quadro 1 — KIQs

| KIQ | Objetivo da Análise | Abordagem Analítica | Principais Dados Necessários |
|------|------|------|------|
| KIQ 1: Quais produtos compõem aproximadamente 80% do faturamento e das comissões? | Identificar os produtos com maior representatividade no faturamento | Curva ABC | Faturamento por produto, volume vendido, participação percentual |
| KIQ 2: Quais produtos apresentam menor sensibilidade a variações de preço? | Analisar a sensibilidade das vendas em relação ao preço | Elasticidade-preço da demanda | Histórico de preços, volume de vendas, comportamento de clientes |
| KIQ 3: Quais produtos possuem baixo giro ou ciclo de vendas prolongado? | Identificar itens com baixa rotatividade | Giro de produtos | Frequência de vendas, intervalo entre pedidos, histórico de movimentação |

**Fonte:** Elaborada pelos autores (2026).

Os dados requeridos para essas análises são predominantemente provenientes do sistema ERP, que se apresenta como a principal fonte estruturada e confiável. No entanto, também são utilizados dados complementares oriundos de planilhas eletrônicas e registros informais, como comunicações em aplicativos de mensagens (WhatsApp).

Essa combinação evidencia a coexistência de dados estruturados, semiestruturados e não estruturados, com diferentes níveis de qualidade e confiabilidade.

### Quadro 2 — Caracterização da Fonte dos Dados

| Tipo de Dado | Fonte | Característica | Confiabilidade |
|-------------|--------|----------------|---------------|
| Estruturado | ERP Mercos | Dados organizados e padronizados | Alta |
| Semiestruturado | Planilhas Excel | Dados manipulados manualmente | Média |
| Não estruturado | WhatsApp | Registros informais | Baixa |

**Fonte:** Elaborada pelos autores (2026).

A seguir, apresentam-se os principais dados necessários, bem como suas fontes, níveis de prioridade e confiabilidade.

### Quadro 3 — KIQ 1: Curva ABC

| Necessidade de Informação | Fonte de Dados | Prioridade | Confiabilidade | Observações |
|--------------------------|---------------|------------|---------------|-------------|
| Faturamento por produto | ERP Mercos | Alta | Alta | Base da classificação ABC |
| Quantidade vendida | ERP Mercos | Alta | Alta | Complementa análise de faturamento |
| Margem/comissão | ERP Mercos / Planilhas | Média | Média | Possíveis inconsistências |
| Participação percentual | ERP Mercos | Alta | Alta | Essencial para Curva ABC |
| Ranking de produtos | ERP Mercos / Planilhas | Alta | Alta | Apoia priorização |

**Fonte:** Elaborada pelos autores (2026).

### Quadro 4 — KIQ 2: Sensibilidade de Mercado

| Necessidade de Informação | Fonte de Dados | Prioridade | Confiabilidade | Observações |
|--------------------------|---------------|------------|---------------|-------------|
| Histórico de preços | ERP Mercos / Planilhas | Média | Média | Falta padronização |
| Volume de vendas por período | ERP Mercos | Alta | Alta | Base analítica |
| Variação de preços | ERP Mercos / Planilhas | Média | Média | Requer tratamento |
| Relação preço x demanda | ERP Mercos / Planilhas | Alta | Média | Necessita BI |
| Perfil de compra do cliente | ERP Mercos | Média | Alta | Suporte à segmentação |

**Fonte:** Elaborada pelos autores (2026).

### Quadro 5 — KIQ 3: Giro de Inventário e Obsolescência

| Necessidade de Informação | Fonte de Dados | Prioridade | Confiabilidade | Observações |
|--------------------------|---------------|------------|---------------|-------------|
| Frequência de vendas | ERP Mercos | Alta | Alta | Indicador de giro |
| Intervalo entre vendas | ERP Mercos | Alta | Alta | Mede ciclo de venda |
| Volume vendido por período | ERP Mercos | Alta | Alta | Complementa análise |
| Produtos sem movimentação | ERP Mercos | Alta | Alta | Indica obsolescência |
| Histórico de pedidos | ERP Mercos | Alta | Alta | Base comportamental |

**Fonte:** Elaborada pelos autores (2026).

### Quadro 6 — Informações Complementares

| Necessidade de Informação | Fonte de Dados | Prioridade | Confiabilidade | Observações |
|--------------------------|---------------|------------|---------------|-------------|
| Registros de visitas | WhatsApp | Baixa | Baixa | Dados não estruturados |
| Análises complementares | Planilhas Excel | Média | Média | Dependência manual |
| Dados operacionais internos | Cadastros internos | Baixa | Média | Sem padronização |

**Fonte:** Elaborada pelos autores (2026).

A inclusão do Quadro 6 justifica-se pela existência de fontes de dados complementares ao ERP que, embora menos estruturadas e confiáveis, influenciam o processo comercial, reforçando a necessidade de integração e tratamento dos dados.

A priorização das informações demonstra que os dados transacionais de vendas, como faturamento, volume e frequência de vendas, possuem maior relevância estratégica, enquanto informações relacionadas a preços, margens e perfil de clientes apresentam importância intermediária. Já os dados não estruturados e externos possuem menor prioridade, sendo utilizados como suporte complementar às análises.

Complementarmente, a avaliação das fontes reforça que, embora o ERP ofereça alta disponibilidade e confiabilidade, as demais fontes apresentam limitações, especialmente devido à dependência de processos manuais, à ausência de padronização e à maior propensão a inconsistências. Esse cenário evidencia lacunas como a falta de integração entre sistemas, a dispersão das informações e a baixa rastreabilidade dos dados.

Diante disso, observa-se que, apesar da existência de um volume significativo de dados, sua utilização ainda é limitada pela fragmentação e pela qualidade heterogênea das fontes.
Nesse contexto, justifica-se a implementação de uma solução de BI, baseada em processos de ETL e na consolidação dos dados em um data warehouse, possibilitando a padronização, integração e confiabilidade das informações. Como resultado, espera-se maior eficiência na geração de indicadores e dashboards, promovendo suporte mais ágil e assertivo à tomada de decisão estratégica.

---

## 2.3 Especificação de Requisitos Informacionais

**Objetivo:** Este item tem como objetivo especificar os requisitos informacionais necessários para subsidiar a construção da solução de Business Intelligence, a partir das necessidades estratégicas identificadas no Key Intelligence Topic (KIT) e nas Key Intelligence Questions (KIQs).

A definição desses requisitos visa garantir que os dados coletados e estruturados sejam suficientes, consistentes e adequados para suportar análises relacionadas ao desempenho do portfólio de produtos, ao comportamento de compra dos clientes e à eficiência das atividades comerciais.

**Identificação das Entidades Informacionais:** Com base nos processos organizacionais e nas KIQs levantadas, foram identificadas as seguintes entidades informacionais:

- Clientes;
- Produtos;
- Vendas;
- Produtos por pedido;
- Visitas comerciais.

Essas entidades constituem a base para a estruturação dos dados necessários à análise estratégica.

**Especificação dos Dados Necessários:** A seguir, são detalhados os principais atributos informacionais requeridos para cada entidade.

#### Quadro 7 — Atributos por Entidades

| Entidade | Atributos |
|-----------|------------|
| Clientes | ID do cliente; Nome Fantasia; Razão Social; CNPJ; Cidade; Estado; Região do Estado; Data de cadastro |
| Produtos | Código do Produto; Código Auxiliar; Código Atual; Nome do Produto; Quantidade por Caixa; Quantidade por Caixa Atual; Volume; Tipo de Volume; Volume/Peso Unidade; Volume/Peso Caixa/Balde; Categoria; Subcategoria; Situação; Disponibilidade; Preço de venda |
| Vendas | ID do pedido; Data de emissão; CNPJ; Valor total do pedido; Condição de pagamento |
| Produtos por Pedido | ID do item; Produto; Quantidade vendida; Valor unitário; Valor total |
| Visitas Comerciais | ID da visita; Data da visita; Cliente visitado; Vendedor responsável; Observações; Status (realizada/pendente) |

**Fonte:** Elaborada pelos autores (2026).

**Especificação dos Requisitos Funcionais:** Para a execução do aplicativo de BI, foram definidos como base os seguintes requisitos funcionais.

#### Quadro 8 — Requisitos Funcionais

| ID | Descrição do Requisito |
|----|------------------------|
| RF-001 | Permitir a importação de planilhas eletrônicas |
| RF-002 | Permitir a inserção manual de dados complementares |
| RF-003 | Gerar relatórios de faturamento total, participação percentual e volume de vendas por período |
| RF-004 | Classificar automaticamente os produtos com base na Curva ABC |
| RF-005 | Identificar produtos com baixo giro de venda |
| RF-006 | Calcular frequência de compra, tempo médio entre pedidos e perfil de consumo |
| RF-007 | Gerar relatórios que cruzem os registros informais de visitas com a efetivação de vendas |
| RF-008 | Permitir identificar a origem dos dados |
| RF-009 | Padronizar os dados provenientes de diferentes fontes |

**Fonte:** Elaborada pelos autores (2026).

Essas variáveis são essenciais para responder às KIQs e apoiar a tomada de decisão estratégica.

A especificação dos requisitos informacionais apresentada estabelece a base estruturante para o desenvolvimento da solução proposta. Ao definir de forma clara as entidades, atributos e critérios de qualidade dos dados, a organização estará apta a consolidar um ambiente informacional confiável e orientado à análise estratégica.

Essa estrutura permitirá não apenas responder às KIQs definidas, mas também ampliar a capacidade analítica da empresa, promovendo maior eficiência operacional e suporte qualificado à tomada de decisão.

---

## 2.4 Levantamento de Fontes de Dados Existentes

Com base no diagnóstico organizacional realizado, foram identificadas quatro fontes de dados com potencial de contribuição para a solução proposta, descritas a seguir.

**Sistema ERP Mercos:** Constitui a principal fonte de dados estruturados da empresa. Trata-se de uma plataforma SaaS voltada à gestão comercial de representantes, adotada pela organização desde julho de 2014. O sistema armazena, em banco de dados relacional em nuvem, o histórico completo das transações comerciais realizadas no período, incluindo cadastro de clientes, pedidos, itens de pedido, valores e datas.

A plataforma disponibiliza funcionalidade de exportação dos dados em formato de planilha eletrônica (.xlsx), o que possibilita a extração periódica das informações para tratamento analítico externo. Dentre os relatórios exportáveis, destacam-se a carteira de clientes, o relatório de vendas consolidado e o detalhamento de produtos por pedido. Esse conjunto de dados cobre diretamente os atributos informacionais requeridos pelas três KIQs formuladas no plano de inteligência competitiva.

**Planilhas Eletrônicas (Microsoft Excel):** As planilhas eletrônicas representam a segunda fonte de dados mais relevante para o projeto. São utilizadas pelos vendedores para fins de controle de preços, aplicação de descontos e elaboração de previsões de vendas mensais. O processo de previsão, conforme descrito na seção 1.3, envolve a extração de dados do ERP, seguida de tratamento manual por meio de tabelas dinâmicas, e posterior atualização da planilha de acompanhamento.

Embora esse mecanismo permita algum grau de análise comercial, apresenta limitações importantes: a ausência de padronização entre os arquivos produzidos por diferentes usuários compromete a consistência dos dados, e a natureza manual do processo introduz riscos de erro e dificulta a rastreabilidade das informações. Os arquivos são armazenados localmente nos computadores dos colaboradores, sem controle de versão ou repositório centralizado.

**Registros em Aplicativo de Mensagens (WhatsApp):** Os registros de visitas comerciais são realizados, atualmente, por meio de um grupo criado na plataforma WhatsApp, que funciona informalmente como canal de comunicação e anotação entre os vendedores e o proprietário. Após cada visita, o representante registra em mensagem de texto os principais pontos discutidos, os produtos apresentados e os encaminhamentos necessários.
 
 Do ponto de vista analítico, essa fonte apresenta as limitações mais significativas entre as identificadas. Os dados são não estruturados, de difícil recuperação histórica e sujeitos a perda em caso de exclusão de mensagens ou troca de dispositivo. A ausência de campos padronizados impede qualquer forma de consulta sistemática, inviabilizando a utilização direta dessas informações em análises quantitativas sem a adoção prévia de um processo de estruturação.

**Armazenamento Local:** Compõem ainda o inventário de dados os arquivos armazenados nos computadores dos colaboradores, que incluem relatórios exportados do ERP em versões históricas, planilhas auxiliares de acompanhamento e documentos diversos. Essa fonte apresenta confiabilidade variável e carece de centralização, o que eleva o risco de inconsistências decorrentes do uso simultâneo de versões diferentes de um mesmo arquivo.

## 2.4.1 Avaliação da Qualidade e Estrutura dos Dados

A análise das fontes identificadas permitiu avaliar os dados quanto à estrutura, confiabilidade, atualização e acessibilidade.

### Quadro 9 — Qualidade e Estrutura dos Dados

| Fonte | Formato | Tipo de Dados | Responsável | Qualidade |
|---------|----------|----------------|-------------|------------|
| ERP Mercos | Banco de Dados / Excel | Estruturados (vendas, clientes, produtos) | Equipe interna | Alta |
| Planilhas Excel | Excel | Semiestruturados | Vendedores | Média |
| WhatsApp | Texto | Não estruturados | Vendedores | Baixa |
| Armazenamento Local | Diversos | Variável | Equipe interna | Média |

**Fonte:** Elaborada pelos autores (2026).

## 2.4.2 Lacunas Identificadas e Necessidades Futuras

Durante o levantamento das informações, foram identificadas lacunas importantes que impactam diretamente a capacidade analítica da empresa:

- Ausência de sistema estruturado para registro de visitas;
- Falta de padronização nas planilhas;
- Inexistência de base consolidada de dados;
- Dificuldade de rastreabilidade das informações;
- Ausência de dados históricos organizados sobre interações com clientes.

## 2.4.3 Recomendações para Coleta de Novos Dados

Para viabilizar plenamente a solução proposta, será necessário implementar, de forma concomitante ao desenvolvimento do sistema, rotinas estruturadas de coleta de dados relativos às visitas comerciais. O módulo de registro de visitas a ser desenvolvido deverá contemplar, no mínimo, os seguintes atributos: data da visita, cliente visitado, vendedor responsável, principais pontos discutidos, encaminhamentos definidos e status da visita (realizada ou pendente). A adoção desse módulo, aliada à centralização dos dados em repositório único e à implementação do processo de ETL, constitui condição necessária para que a aplicação proposta alcance os objetivos estratégicos definidos no plano de inteligência competitiva.

## 2.4.4 Conclusão

O levantamento das fontes de dados evidencia que a empresa já possui uma base relevante de dados operacionais, principalmente por meio do ERP. No entanto, há limitações significativas relacionadas à fragmentação, falta de padronização e ausência de estrutura em algumas fontes.

A consolidação e o tratamento adequado desses dados serão fundamentais para viabilizar a solução proposta, permitindo a transição para uma gestão orientada a dados e apoiando a tomada de decisão estratégica.

---

## 2.5 Compliance de TI e Segurança da Informação

### 2.5.1 Introdução

O presente item tem por finalidade identificar os aspectos legais e normativos aplicáveis ao uso de Tecnologia da Informação no processo de Inteligência Competitiva (IC) desenvolvido pela empresa de representação comercial de produtos químicos para piscinas, bem como propor políticas e procedimentos que assegurem a conformidade contínua, a proteção de dados e a segurança da informação.

Embora a empresa seja de pequeno porte, com apenas três colaboradores, ela lida diariamente com dados de pessoas jurídicas clientes (CNPJ, razão social, localização, histórico de compras e informações comerciais sensíveis), o que a sujeita ao cumprimento da legislação vigente sobre proteção de dados e segurança da informação. A coleta, o armazenamento e o tratamento desses dados ocorrem em múltiplas plataformas — sistema ERP Mercos (SaaS em nuvem), planilhas eletrônicas armazenadas localmente e registros informais via WhatsApp — o que reforça a necessidade de uma abordagem estruturada de compliance.

### 2.5.2 Mapeamento de Normas e Regulamentações Aplicáveis

A seguir são apresentadas as principais normas e regulamentações identificadas como aplicáveis ao contexto da empresa e ao sistema de informação a ser desenvolvido.

#### a) Lei Geral de Proteção de Dados Pessoais — LGPD (Lei nº 13.709/2018)

A LGPD é a principal norma brasileira que regula o tratamento de dados pessoais por pessoas físicas ou jurídicas, de direito público ou privado. Embora o modelo de negócio da empresa seja B2B (*Business to Business*), há situações em que dados de pessoas físicas são tratados indiretamente, como nome e contato de sócios, responsáveis de compra e vendedores das lojas clientes. Nesses casos, a LGPD é plenamente aplicável.

Os princípios fundamentais da LGPD que devem nortear o desenvolvimento da solução de BI são:

* **Finalidade:** os dados devem ser coletados e tratados apenas para finalidades legítimas, específicas e informadas ao titular;
* **Adequação:** o tratamento deve ser compatível com as finalidades informadas;
* **Necessidade:** a coleta deve ser limitada ao mínimo necessário para a realização das finalidades;
* **Segurança:** o controlador deve adotar medidas técnicas e administrativas para proteger os dados de acessos não autorizados e situações acidentais;
* **Prevenção:** adoção de medidas para prevenir a ocorrência de danos em virtude do tratamento;
* **Responsabilização e prestação de contas:** demonstração de conformidade com a legislação.

A empresa atua como agente de tratamento na condição de controlador dos dados que processa para fins de análise comercial e inteligência competitiva, e como operador dos dados que transitam pelo ERP Mercos, cuja infraestrutura é gerida por terceiro.

#### b) Regulamento Geral de Proteção de Dados — GDPR (Regulamento UE 2016/679)

Ainda que a empresa opere exclusivamente no mercado brasileiro, a adoção das diretrizes do GDPR é recomendada como referência de boas práticas internacionais, especialmente nos aspectos relacionados ao princípio de *privacy by design* (privacidade desde a concepção), à minimização de dados e à obrigação de notificação em caso de incidentes. A observância dessas diretrizes fortalece a maturidade de segurança da organização e prepara a empresa para eventuais expansões de mercado.

#### c) ISO/IEC 27001 — Sistema de Gestão de Segurança da Informação (SGSI)

A norma ISO/IEC 27001 estabelece requisitos para implementação, manutenção e melhoria contínua de um Sistema de Gestão de Segurança da Informação. Embora a certificação formal não seja mandatória para empresas de pequeno porte, os controles previstos na norma — organizados em domínios como políticas de segurança, controle de acesso, criptografia, segurança física, gestão de incidentes e continuidade de negócios — devem servir como referencial técnico para as políticas a serem adotadas.

Em especial, destacam-se:

* **Controle de acesso (Domínio A.9):** concessão de acesso às informações com base no princípio do menor privilégio;
* **Criptografia (Domínio A.10):** uso de mecanismos criptográficos para proteção de dados em trânsito e em repouso;
* **Segurança nas relações com fornecedores (Domínio A.15):** gestão de riscos associados ao uso de soluções SaaS de terceiros, como o ERP Mercos.

#### d) Marco Civil da Internet (Lei nº 12.965/2014)

O Marco Civil da Internet regula o uso da internet no Brasil e estabelece diretrizes sobre responsabilidade civil de provedores, guarda de registros de conexão e acesso a aplicações. Como a empresa utiliza sistemas SaaS e comunicação via aplicativos de mensagens (WhatsApp) para fins comerciais, as disposições sobre guarda e proteção de registros de acesso tornam-se relevantes.

#### e) Lei Complementar nº 155/2016 e regulamentações do Simples Nacional

Do ponto de vista fiscal e regulatório complementar, a empresa deve observar as normativas aplicáveis às microempresas e empresas de pequeno porte no que tange ao armazenamento seguro de documentos fiscais e registros comerciais por prazos determinados em lei, o que impõe requisitos mínimos de integridade e disponibilidade dos dados.

### 2.5.3 Políticas de Proteção de Dados e Segurança da Informação

Com base no mapeamento regulatório realizado, propõem-se as seguintes políticas e diretrizes para a empresa, adequadas à sua realidade de pequeno porte e ao sistema de informação a ser desenvolvido.

#### a) Política de Classificação e Inventário de Dados

Todos os dados tratados pela empresa devem ser classificados conforme seu grau de sensibilidade e criticidade:

* **Dados públicos:** informações disponíveis abertamente, como nome fantasia e endereço de clientes;
* **Dados internos:** histórico de vendas, tabelas de preços, previsões comerciais e análises de portfólio;
* **Dados confidenciais:** CNPJ, dados de contato de responsáveis, margens de negociação, estratégias comerciais e resultados de análises de IC;
* **Dados sensíveis (LGPD):** quaisquer dados de pessoas físicas identificáveis presentes na base de clientes ou nos registros de visitas.

O inventário de dados deve ser mantido atualizado, identificando para cada categoria: a finalidade do tratamento, a base legal utilizada, o local de armazenamento e o responsável pelo dado.

#### b) Política de Controle de Acesso

O acesso às informações e sistemas da empresa deve obedecer ao princípio do menor privilégio, garantindo que cada usuário acesse apenas os dados estritamente necessários ao exercício de suas funções:

* Criação de perfis de acesso diferenciados para o proprietário e para os vendedores no sistema de BI a ser desenvolvido;
* Uso de autenticação por credenciais individuais, vedado o compartilhamento de senhas;
* Adoção de autenticação de dois fatores (2FA) para acesso ao ERP Mercos e às plataformas em nuvem;
* Revisão periódica semestral dos perfis de acesso e revogação imediata em caso de desligamento de colaboradores;
* Registro (*log*) de acessos ao sistema, permitindo rastreabilidade das consultas e alterações realizadas.

#### c) Política de Anonimização e Pseudonimização

Para fins de análise de inteligência competitiva e geração de relatórios e dashboards internos, os dados de clientes devem, sempre que possível, ser anonimizados ou pseudonimizados:

* Análises agregadas de desempenho de portfólio (Curva ABC, giro de produtos) devem ser realizadas sobre dados consolidados, sem necessidade de identificação individual do cliente;
* Quando a identificação do cliente for necessária para análises de comportamento de compra ou planejamento de visitas, deve ser utilizada a pseudonimização, com a chave de identificação armazenada separadamente e com acesso restrito;
* Dados exportados para análise em planilhas eletrônicas não devem conter dados pessoais de pessoas físicas em texto claro.

#### d) Política de Segurança de Dispositivos e Armazenamento Local

Considerando que a empresa mantém dados em computadores locais (planilhas, relatórios exportados do ERP), as seguintes medidas são recomendadas:

* Uso de senhas fortes e bloqueio automático de tela nos dispositivos utilizados pelos colaboradores;
* Criptografia do disco local ou das pastas que contenham dados sensíveis, utilizando recursos nativos do sistema operacional (ex.: BitLocker no Windows);
* Realização de backups periódicos dos dados locais em mídia segura ou em serviço de armazenamento em nuvem com controle de acesso;
* Proibição do uso de dispositivos pessoais não gerenciados para armazenamento de dados da empresa sem que medidas de segurança equivalentes estejam implementadas.

#### e) Política de Uso de Aplicativos de Mensagens para Fins Comerciais

O uso do WhatsApp como canal de registro de visitas comerciais, embora prático, representa risco à segurança e à conformidade, pois dados de clientes e informações estratégicas trafegam em plataforma de terceiros sem controle corporativo.
Recomenda-se:

*	Migrar gradualmente o registro de visitas para o módulo estruturado a ser desenvolvido no sistema de BI, eliminando a dependência do WhatsApp para este fim;
*	Enquanto o processo de migração não for concluído, orientar os colaboradores a não incluírem dados sensíveis (CNPJ, valores, estratégias) em mensagens de texto no aplicativo;
*	Não utilizar grupos de WhatsApp para armazenamento de decisões estratégicas ou informações confidenciais da empresa.

#### f) Política de Gestão de Fornecedores e Terceiros

O ERP Mercos é um sistema SaaS gerido por terceiro, o que implica que dados da empresa - incluindo cadastro de clientes e histórico completo de vendas - estão armazenados na infraestrutura do fornecedor. Nesse sentido, recomenda-se:

*	Verificar e manter atualizado o contrato com a Mercos, assegurando cláusulas de proteção de dados, confidencialidade e conformidade com a LGPD;
*	Solicitar ao fornecedor informações sobre sua política de privacidade, localização dos servidores e procedimentos em caso de incidentes de segurança;
*	Manter exportações periódicas dos dados do ERP como cópia de segurança independente, reduzindo o risco de perda de dados em caso de descontinuidade do serviço.

### 2.5.4 Diretrizes para o Sistema a Ser Desenvolvido

O sistema planejado para a etapa seguinte do projeto deve ser desenvolvido incorporando os requisitos de conformidade e segurança desde sua concepção (privacy by design). As seguintes diretrizes devem ser observadas durante o desenvolvimento:

*	**Minimização de dados:** importar do ERP apenas os campos estritamente necessários para as análises previstas nas KIQs, evitando a replicação desnecessária de dados cadastrais completos;
*	**Controle de acesso baseado em papéis (RBAC):** implementar perfis de usuário com permissões diferenciadas (administrador, analista, visualizador);
*	**Rastreabilidade:** registrar logs de acesso e de operações realizadas no sistema;
*	**Segurança dos dados em repouso e em trânsito:** utilizar conexões criptografadas (HTTPS/TLS) para acesso ao sistema e, se aplicável, criptografia dos dados armazenados;
*	**Exclusão e retenção de dados:** definir política de retenção, estabelecendo por quanto tempo os dados serão mantidos no sistema e como será realizada sua exclusão segura ao término do prazo.

### 2.5.5 Procedimentos de Auditoria e Conformidade

Para garantir a conformidade contínua com as normas identificadas, propõem-se os seguintes mecanismos de monitoramento e avaliação:

#### a) Auditoria Interna Periódica

Recomenda-se a realização de auditorias internas semestrais, conduzidas pelo proprietário com apoio da equipe do projeto, abrangendo:

*	Revisão do inventário de dados e bases legais de tratamento;
*	Verificação do cumprimento das políticas de controle de acesso;
*	Análise dos logs de acesso ao sistema de BI para identificação de acessos não autorizados ou irregulares;
*	Avaliação da atualização dos backups e integridade dos dados armazenados localmente;
*	Verificação do cumprimento das cláusulas contratuais com fornecedores (em especial o ERP Mercos).

#### b) Gestão de Incidentes de Segurança

A empresa deve estabelecer um procedimento básico para resposta a incidentes de segurança da informação, contemplando:

*	Identificação e notificação interna imediata do incidente ao proprietário;
*	Avaliação da extensão e impacto do incidente sobre os dados tratados;
*	Comunicação aos titulares afetados e à Autoridade Nacional de Proteção de Dados (ANPD), quando o incidente envolver dados pessoais e representar risco ou dano relevante, conforme exige a LGPD (art. 48);
*	Registro documentado de todos os incidentes e das medidas corretivas adotadas.

#### c) Capacitação e Conscientização

A conformidade com as normas de segurança da informação depende, em grande medida, do comportamento dos colaboradores. Recomenda-se:

*	Realização de treinamento inicial sobre LGPD e boas práticas de segurança da informação para todos os colaboradores, incluindo os vendedores;
*	Atualização anual do treinamento, incorporando eventuais mudanças na legislação e nos procedimentos internos;
*	Disponibilização de um documento resumido das políticas de segurança (manual do usuário) de forma acessível a todos.

#### d) Indicadores de Conformidade

Para monitorar o nível de conformidade ao longo do tempo, sugerem-se os seguintes indicadores conforme no Quadro 10 a seguir.

### Quadro 10 — Indicadores de Conformidade

| Indicador | Frequência de Verificação | Meta |
|------------|--------------------------|------|
| Percentual de colaboradores treinados em LGPD | Anual | 100% |
| Backups realizados conforme periodicidade definida | Mensal | 100% de conformidade |
| Revisão de perfis de acesso ao sistema | Semestral | Sem perfis desatualizados |
| Incidentes de segurança registrados e tratados | Contínuo | 100% registrados e tratados |
| Contrato com fornecedor SaaS revisado | Anual | Cláusulas de proteção de dados vigentes |

**Fonte:** Elaborada pelos autores (2026).

### 2.5.6 Considerações Finais

O planejamento de compliance de TI e segurança da informação aqui apresentado é proporcional à realidade de uma empresa de pequeno porte, mas suficientemente robusto para assegurar a conformidade com a LGPD e com as melhores práticas de mercado referenciadas pela ISO/IEC 27001. A adoção dessas diretrizes é condição prévia ao desenvolvimento do sistema previsto na Etapa 3, garantindo que a solução seja construída sobre bases legais e seguras, protegendo tanto a empresa quanto seus clientes. O conjunto de políticas, diretrizes e procedimentos aqui definidos deverá ser revisado e atualizado à medida que o sistema evolua e que o arcabouço regulatório brasileiro em proteção de dados continue a se consolidar.
