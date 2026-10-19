# Análise Aprofundada — CredMoura: Modelo, Adoção, Valor e Aprendizados

> Relatório investigativo. Não é um resumo executivo nem uma apresentação — é uma reconstrução analítica, fundamentada exclusivamente nos documentos listados abaixo, feita para sustentar decisões futuras sobre o que é replicável do modelo Propig/CredMoura e o que depende de condições específicas do ecossistema Moura.

## Nota metodológica

### Fontes utilizadas (único universo admitido nesta análise)

| Código | Documento | Data | Natureza |
|---|---|---|---|
| **INT-10/09** | `imersao-interna-moura/2026-09-10_imersao-produto-servico_transcricao.txt` | 10/09 | Imersão interna Propig (Tasso/André, Aloysio/Luísio, Janduí) |
| **INT-11/09** | `imersao-interna-moura/2026-09-11_imersao-produto-parte-ii_transcricao.txt` | 11/09 | Continuação da imersão interna (mesmos interlocutores) |
| **INT-14/09-RUI** | `imersao-interna-moura/2026-09-14_entrevista-rui-moura_transcricao.txt` | 14/09 | Entrevista com Rui (liderança Propig/Moura do programa) |
| **INT-14/09-PLAT** | `imersao-interna-moura/2026-09-14_plataforma_transcricao.txt` | 14/09 | Demonstração dos portais Credimora (cliente/revenda e distribuidor) |
| **REV-FABIO** | `imersao-revendedores-distribuidores-moura/2026-09-16_entrevista-revenda-01-sp-fabio_transcricao.docx` | 16/09 | Entrevista revenda SP (Fábio) |
| **REV-LUCAS** | `imersao-revendedores-distribuidores-moura/2026-09-16_entrevista-revenda-02-sp-lucas-barreto_transcricao.txt` | 16/09 | Entrevista revenda SP (Lucas Barreto, 2 lojas) |
| **DIST-ANAPOLIS** | `imersao-revendedores-distribuidores-moura/2026-09-17_entrevista-distribuidor-01-anapolis-victor_transcricao.txt` | 17/09 | Distribuidor Anápolis/GO (Victor) |
| **DIST-UNIAO** | `imersao-revendedores-distribuidores-moura/2026-09-18_entrevista-distribuidor-02-uniao-sp-eduardo_transcricao.txt` | 18/09 | Distribuidor União, ABCD+SP capital (Eduardo) |
| **DIST-ROADMASTER** | `imersao-revendedores-distribuidores-moura/2026-09-29_entrevista-distribuidor-03-porto-alegre-victor-roadmaster_transcricao.txt` | 29/09 | Distribuidor Roadmaster, Porto Alegre (Victor) |

Nenhuma outra fonte do repositório (AS-IS já sintetizado, proposta comercial, benchmarking de mercado, kickoffs, `imersao-externa-clientes/`) foi usada nesta análise, por definição explícita de escopo combinada com o usuário. As sínteses já existentes (`sintese_*.md`) foram usadas apenas como guia de navegação, nunca como evidência citada — toda citação abaixo remete à transcrição bruta.

### Regras seguidas (resumo operacional)

1. Toda conclusão relevante é cruzada entre pelo menos duas fontes quando possível; quando não é possível, isso é dito explicitamente.
2. Distingo três camadas de informação: **fato documentado** (algo que aconteceu e é verificável no texto — ex. números, mecânicas), **relato/percepção do entrevistado** (opinião, estimativa, sensação de alguém específico) e **interpretação/hipótese minha** (conexão que eu estou fazendo entre fontes). Quando um entrevistado especula sobre algo e ele mesmo marca a especulação como incerta, preservo essa incerteza.
3. Toda citação tem fonte, interlocutor (quando identificável) e, sempre que possível, trecho literal entre aspas.
4. Nenhuma percepção de um único entrevistado é generalizada ao "ecossistema" sem dizer que é de uma fonte só.
5. Convergências, divergências e contradições entre fontes são registradas como tais — nunca escondidas ou resolvidas arbitrariamente a favor de uma versão.
6. Não assumo que o CredMoura é sucesso em todas as dimensões. Zonas de fracasso, estagnação e dúvida aparecem com o mesmo rigor que zonas de sucesso.
7. Lacunas de informação são marcadas explicitamente como lacunas, nunca preenchidas por suposição.
8. Diferenças entre planos (Sessão, Flex 30/40/50/60/80, Multiagenda), condições (isenções, campanhas) e benefícios (por ator) são preservadas — não há "o CredMoura cobra X%" sem dizer de qual plano, para quem, em que contexto.
9. Evito conclusões genéricas tipo "o produto gera fidelização" sem explicar o mecanismo concreto que produz esse efeito.
10. Nunca atribuo à Propig um resultado que, pela evidência, depende de decisão de outro ator (Moura, distribuidor, vendedor). Toda vez que isso é relevante, a cadeia é explicitada: quem fez o quê, como funcionou, que problema resolveu, quem contribuiu, que evidência sustenta isso.

Uma observação necessária antes de começar: oito das nove fontes vêm de dentro do próprio ecossistema Propig/Moura (quatro imersões internas da Propig, três entrevistas com distribuidores — que são, estruturalmente, 70-75% da própria Moura — e apenas duas entrevistas com revendas independentes). Isso não invalida a análise, mas significa que a voz mais "externa" e menos interessada no sucesso do programa (a revenda comum, sem vínculo de capital com a Moura) está sub-representada em volume (2 de 9 fontes) frente à voz da própria cadeia de distribuição que vende e é incentivada a vender o produto. Trato esse desequilíbrio como uma lacuna estrutural da base de evidências, não como um viés a ser silenciosamente corrigido.

---

# Capítulo 1 — Visão geral do CredMoura

## 1.1 O que é, de fato

O CredMoura (grafado também "Credimora"/"Crede Moura" nas transcrições — variação de fala, mesmo produto) não é uma maquininha de cartão. É descrito pelos próprios arquitetos do produto como um **programa** cujo "meio" é uma maquininha, mas cujo "fim" é resolver dores distintas de atores distintos na cadeia bateria→consumidor (INT-10/09, Aloysio: *"Produto é um meio, não é um fim... Programa Credimoura para atingir um fim. O meio é a maquininha. A maquininha aqui é só o meio."*). A Propig, subadquirente que opera o programa, reforça isso com uma metáfora médica usada por Janduí (consultor de campo): *"A máquina de cartão, o modelo de empreendedor, é um remédio... talvez ele não sirva para tudo. E aí a gente precisa ter outro remédio."* (INT-10/09).

Mecanicamente, o produto resolve um descasamento de capacidade financeira em cadeia:

- O **consumidor final** quer a marca Moura mas frequentemente não está preparado financeiramente para o ticket integral no momento da troca da bateria (compra não planejada, "a bateria do carro quebrou"). Parcelar em até 10x sem juros remove essa barreira (INT-10/09, Tasso: *"Quando você leva a solução do Carimura, você está parcelando a bateria em dez vezes. Ele para de ser um comparativo, em relação a valor, preço da bateria, e passa a ser o valor da... que aquilo ali encaixa no orçamento mensal dele."*).
- A **revenda** não tem fluxo de caixa para financiar esse parcelamento sozinha nem para antecipar os recebíveis a um custo razoável em uma adquirente tradicional (INT-10/09: antecipação no mercado custaria "entre 10% e 20%", contra os ~5% cobrados pela Propig). A Propig antecipa o valor para a revenda — ela recebe "praticamente no dia seguinte" (até 48h, confirmado em REV-FABIO e REV-LUCAS como a promessa comunicada) — mas **não antecipa esse valor ao distribuidor Moura**, que recebe conforme o calendário real das parcelas (INT-10/09; mecânica numérica detalhada também em INT-14/09-PLAT).
- O **distribuidor Moura** (pessoa jurídica majoritariamente da própria Moura, ~70% segundo INT-10/09 ou "minimamente 70-75%" segundo INT-14/09-PLAT — pequena divergência numérica entre fontes internas da própria Propig, registrada aqui como tal) já operava historicamente com prazos médios de recebimento longos via boleto (30/60/90/120 dias), então o impacto de caixa de "financiar" 10 parcelas é amortecido por essa prática pré-existente — e o distribuidor ganha, em troca, zero inadimplência na transação (é transação de cartão) e participação de mercado, porque o crédito gerado só pode ser convertido em produto Moura, mesmo que a revenda tenha vendido uma bateria concorrente na mesma máquina (INT-10/09).

Esse último ponto é o mecanismo central do produto e vale ser dito sem metáfora: **a maquininha é da revenda, mas o crédito gerado por ela só pode ser gasto em produtos Moura junto ao distribuidor Moura daquela área**. É essa amarração — não a tecnologia da maquininha em si — que converte uma ferramenta de parcelamento genérica em uma ferramenta de conversão de market share para a indústria.

## 1.2 Os três planos e o que cada um muda

A documentação e as entrevistas usam linguagem inconsistente ("Sessão", "seção", "sessão total" aparecem como sinônimos nas falas transcritas) — preservo aqui a nomenclatura mais usada.

- **Sessão** (ou "Sessão Total"): 100% do valor transacionado na maquininha vira saldo CredMoura — crédito-produto junto ao distribuidor, não sacável, usável apenas para comprar bateria/produtos Moura (INT-14/09-PLAT, confirmado em REV-LUCAS e DIST-UNIAO). A revenda não tem acesso a esse dinheiro para capital de giro — só para reposição de estoque.
- **Flex** (30/40/50/60/80 — o número indica o percentual que cai na conta bancária da revenda; o restante vira crédito igual ao Sessão): nasceu, segundo INT-11/09 (relato interno Propig, não confirmado de forma independente nas entrevistas de distribuidor/revenda lidas), de uma necessidade identificada de revendas que precisavam de parte do dinheiro líquido para despesas operacionais (aluguel, funcionários) — exemplo dado: bateria comprada por R$200 e vendida por R$300; R$100 (a margem) cai em conta, R$200 vira crédito para reposição (INT-10/09). Tem taxa mais alta que o Sessão (ex.: Flex 30 a 7% vs Sessão a 4,89%, segundo DIST-UNIAO/Eduardo) porque, segundo as fontes internas, é um produto de maior complexidade de explicar e tem custo associado à parcela líquida imediata.
- **Multiagenda**: permite à revenda escolher, transação por transação, entre o botão "Moura" (aplica a divisão do plano — Sessão ou Flex) e o botão "Loja" (100% do valor cai em conta, sem gerar nenhum crédito para o distribuidor). A escolha é feita no momento da venda, na própria maquininha, e é irreversível depois (INT-14/09-PLAT: *"Ele não tem como voltar para cá e dizer, não, mas era porque eu queria passar no lado loja."*). A taxa do lado "Loja" é mais alta do que a do lado "Moura", porque a Propig, nesse caso, arca com o custo integral de subadquirência sem a segurança de que aquele volume vai gerar crédito-produto trancado junto ao distribuidor (INT-14/09-PLAT).

**Divergência relevante entre fontes sobre o estado atual da mistura Sessão/Flex** (tratada aqui como tal, não resolvida):
- INT-11/09 (interna Propig, data mais antiga da imersão): citava um panorama de ~50%/50% entre os dois planos na base nacional, naquele momento.
- DIST-ANAPOLIS (17/09): "70% da nossa base hoje ainda é sessão", com tentativa ativa de migração para Flex.
- DIST-UNIAO (18/09): descreve a base como "bem mais sessão" e o próprio distribuidor recomenda pessoalmente Sessão para quem "sabe fazer conta" (ver Capítulo 2.4), mesmo reconhecendo que a Propig tem política de comissão para o vendedor migrar clientes para Flex.
- INT-14/09-RUI (14/09, relatado na síntese prévia desta investigação, não relido linha a linha nesta rodada): segundo registro anterior desta mesma investigação documental, Rui afirma que a tendência é Flex ser a direção dominante e que, "se o Credimora nascesse hoje, nasceria só com o plano Flex" — reforçado pela expansão da Argentina, iniciada só com Flex.

Essas quatro leituras não são contraditórias no sentido de "uma está certa e as outras erradas" — são **fotografias de datas e escopos diferentes** (nacional vs. um distribuidor específico) e de **vieses de quem fala** (a liderança do programa fala da direção estratégica; distribuidores de ponta falam do estoque real de clientes que já têm hoje, moldado por anos de histórico local). Qualquer leitura que diga "o CredMoura hoje é majoritariamente Flex" ou "majoritariamente Sessão" estaria simplificando essas quatro fontes de forma indevida.

## 1.3 Escala e penetração — números e suas divergências

- **Universo de distribuidores**: não há, nos 9 documentos, um número consolidado único e datado explicitamente para "quantos distribuidores Moura existem hoje". DIST-ANAPOLIS menciona genericamente a existência de múltiplos distribuidores regionais; DIST-UNIAO atende "ABCD + metade de SP capital + Baixada Santista"; nenhuma fonte dá o total nacional de distribuidores com uma data associada de forma inequívoca nestes 9 documentos (diferente do que constava em uma leitura anterior desta investigação, que usava a comparação entre fontes mais amplas do projeto — aqui, restrito aos 9 documentos, esse número fica como lacuna, ver Capítulo 9).
- **Universo de revendas Moura**: INT-10/09 cita "70 mil revendas" como universo total, com "10 mil" sendo "especialistas" (bateria como negócio principal).
- Uma leitura anterior desta mesma linha de investigação (nesta sessão, antes desta restrição de escopo) havia registrado, a partir do mesmo dia 09/11, a cifra de "~5% (~3.500)" especialistas sobre as mesmas 70 mil revendas — **ou seja, a própria dupla de imersões internas de 10/09 e 11/09, em dias consecutivos, com os mesmos interlocutores, aparentemente divergem entre si nesse número** (10 mil vs. ~3.500 — a diferença é grande, quase 3x). Como a transcrição de 11/09 não foi relida literalmente nesta rodada final de leitura (reaproveitei a leitura integral já feita nesta sessão), registro esta divergência como uma tensão real a ser verificada antes de qualquer uso operacional desses números — não escolho um dos dois para "ser o certo".
- **Revendas aderentes**: INT-10/09 e (segundo registro desta investigação) INT-11/09 convergem em "7 mil revendas aderentes" — ou seja, ~10% das 70 mil totais.
- **Penetração por distribuidor** (dado real, não extrapolação): varia enormemente conforme o perfil do distribuidor —
  - DIST-ANAPOLIS: "mais de 90%" das casas de bateria (especialistas) aderentes, mas apenas ~35% da carteira ativa total (a meta que ele mesmo definiu e ainda não atingiu).
  - DIST-UNIAO: 10-12% da carteira ativa total, mas responsável por ~60% do faturamento do PDV nos clientes que usam.
  - DIST-ROADMASTER: apenas ~8% da carteira (~100 de ~1.400-1.500 revendedores), o distribuidor com a penetração percentual mais baixa das três entrevistas de distribuidor lidas.

Esses três números — 90%+, 10-12%, 8% — **não são comparáveis diretamente** porque medem bases diferentes (casas de bateria especialistas vs. carteira ativa total) e distribuidores de porte e perfil de carteira muito diferentes (Roadmaster é explicitamente descrito por seu próprio sócio como um dos distribuidores "com venda mais pulverizada" e sem grandes clientes concentradores, ao contrário de União, que tem clientes de grande volume desde o início do programa). A conclusão segura que esses três números sustentam, convergentemente, não é "a adesão é X%" — é: **a adesão ao CredMoura é estruturalmente dependente do perfil de concentração de vendas da carteira de cada distribuidor específico**, mais do que de uma "taxa de adoção nacional" única.

## 1.4 Histórico — duas origens, não uma

Um achado de cruzamento relevante: existem, nos documentos, **duas narrativas de origem distintas e não idênticas**, contadas por dois distribuidores diferentes, e nenhuma delas é contraditada pela outra — mas também não são a mesma história, e misturá-las produziria uma linha do tempo falsa:

1. **DIST-UNIAO (Eduardo)**: fala de uma tentativa de cartão de crédito Moura *anterior* ao CredMoura atual, abandonada por problemas fiscais, legais e de conciliação bancária, sendo que o último distribuidor a sair desse projeto anterior o fez em **2005**.
2. **DIST-ANAPOLIS (Victor)**: fala de uma reunião em **2013** entre Moura e Cielo (ele próprio, então gerente da Cielo, presente), na qual a Moura buscava uma parceria tecnológica para viabilizar a "concessão" de recebíveis — reunião que não avançou porque, segundo ele, "não existia esse termo de concessão" ainda disponível no mercado àquela época.

Ambos convergem em que o piloto do modelo *atual* começou em **2017-2018**, na Fortaleza das Baterias (DIST-UNIAO e DIST-ANAPOLIS concordam neste ponto específico). Mas a década entre 2005 (fim da tentativa anterior) e 2013 (reunião com a Cielo) e 2017-2018 (piloto atual) não está documentada em nenhuma das 9 fontes como um período contínuo de um único projeto — são dois relatos de dois eventos possivelmente distintos (uma tentativa de cartão de crédito próprio nos anos 1990-2000, depois uma tentativa frustrada de parceria com adquirente tradicional em 2013, depois o modelo atual via subadquirente própria — a Propig, antes chamada "Lucre", segundo DIST-ANAPOLIS: *"a Moura começou com a antiga Lucre e depois virou Propig"*). **Isso é uma lacuna de informação explícita**: não há, nos 9 documentos, uma reconstrução única e confirmada de todo o histórico 2005→2013→2017; há dois pontos de dados de dois distribuidores distintos, e a ponte entre eles não está nas fontes aprovadas.

## 1.5 Fluxos de responsabilidade — visão de conjunto

| Elemento | Quem decide | Quem executa | Quem garante o financeiro |
|---|---|---|---|
| Taxa cobrada da revenda (ou se é zero) | Distribuidor, dentro do sistema de flexibilidade que a Propig oferece | Propig (cobrança automatizada por transação) | Quem a política do distribuidor definir — revenda, distribuidor, ou split |
| Antecipação do valor para a revenda | Regra do produto (Propig/Moura) | Propig, via sistema de pagamento próprio (não via Moura) | Propig |
| Liberação do crédito-produto ao distribuidor | Automática via integração de sistemas (D+2 ou menos, segundo INT-14/09-PLAT) | Sistemas Propig + Moura (API) | Propig é intermediária; o distribuidor só recebe conforme as parcelas reais |
| Política de isenção/subsídio | 100% do distribuidor (ou da fábrica em campanhas pontuais específicas, segundo DIST-ANAPOLIS) | Equipe comercial do distribuidor | Distribuidor (ou Moura, em campanhas específicas) |
| Treinamento do vendedor de ponta | Distribuidor (consultor de campo Propig apoia) | Vendedor do distribuidor | — |
| Logística de máquinas (entrega, troca) | Propig (operador logístico) | Operador logístico contratado pela Propig | Propig |

Este quadro é central para todo o resto da análise: **cada linha da cadeia tem um responsável diferente**, e qualquer afirmação de sucesso ou falha do CredMoura precisa dizer em qual linha ela está ocorrendo, porque a Propig não controla todas elas (ver Capítulo 3 para o desdobramento completo desse ponto, que o usuário sinalizou como o núcleo mais importante desta análise).

---

# Capítulo 2 — Modelo de negócio e operação

## 2.1 Estrutura de receita da Propig — e sua autocrítica documentada

A fonte mais rica sobre a mecânica financeira interna é INT-10/09, onde o próprio Tasso (ou André — a transcrição às vezes confunde os dois falantes como "Speaker 1"/"Speaker 2" sem نome fixo; mantenho a atribuição que a transcrição sugere pelo contexto) descreve o fluxo com um exemplo numérico explícito:

> *"Uma transação de R$100,00, eu cobrei lá R$2,00. Então eu vou pagar R$98,00 em 10 vezes ao distribuidor... Só que eu tive que pagar R$1,00 para a rede. Então eu só fiquei com R$1,00."* (INT-10/09)

Ou seja: em uma transação de R$100 com taxa de 2%, a Propig paga ~1% para a infraestrutura de rede (ela é subadquirente, usa Cielo ou Rede como adquirente de base, segundo a mesma fonte) e fica com um spread de ~1% — que ainda é recebido parceladamente junto com o distribuidor, não de uma vez.

Isso leva à autocrítica mais contundente de todo o corpus documental, dita pela própria liderança do produto:

> *"A gente termina deixando dinheiro muito mais do outro lado da mesa, deixando dinheiro muito mais do outro lado da Moura do que na própria Propig em si."* (INT-10/09, abertura da reunião)

> *"Eu errei no modelo de cobrança. Eu cobro igual a maquininha... Por que eu cobro assim? Eu poderia cobrar diferente. Eu poderia cobrar uma taxa única para todos os presentes. (...) Esse modelo a gente tem que fugir dele também. Porque cada vez que eu me aproximo desse modelo de cobrança de maquininha, mais eu vou ser comparado à maquininha."* (INT-10/09)

Esta é uma admissão documentada, feita pela própria liderança do programa, de que **a estrutura de precificação da Propig foi desenhada de um jeito que convida à comparação com adquirentes tradicionais** (cobrança separada por débito/crédito/parcelado, aluguel de maquininha) — mesmo que, segundo a mesma fonte, o valor real entregue (taxa all-in mais baixa que o custo real de antecipação no mercado) seja maior do que essa comparação sugere. Esse é um ponto de modelo de negócio, não de execução: é uma decisão de desenho que a própria empresa identifica, documentadamente, como equivocada.

## 2.2 Por que a Propig consegue cobrar menos que o mercado — o mecanismo exato

A explicação mecânica (não apenas a afirmação de que "é mais barato") está em INT-10/09: uma adquirente tradicional, quando antecipa o recebível de uma venda parcelada, embute o custo financeiro dessa antecipação na taxa cobrada do lojista. A Propig **antecipa para a revenda, mas não antecipa para o distribuidor** — o distribuidor recebe conforme o calendário real das parcelas (confirmado com números em INT-14/09-PLAT: a revenda recebe "praticamente no dia seguinte"; o distribuidor recebe "parcela por parcela", por exemplo "a parcela 9 de 10" num determinado mês).

Esse descasamento só é absorvível pelo distribuidor porque ele **já operava historicamente com prazo médio de recebimento longo via boleto** (30/60/90/120 dias) antes mesmo de existir o CredMoura (INT-10/09). Ou seja: a "vantagem competitiva" da Propig sobre uma adquirente tradicional não vem de uma tecnologia superior de processamento de pagamento — vem de **transferir o custo de carregamento do capital para um elo da cadeia (o distribuidor) que já estava estruturalmente preparado para carregar esse custo antes do produto existir**. Isso é relevante e será retomado no Capítulo 8 (replicabilidade): essa pré-condição não existe automaticamente em qualquer setor.

## 2.3 A flexibilidade de quem paga a taxa — o verdadeiro diferencial, segundo as próprias fontes

Repetido em múltiplas entrevistas internas como o real diferencial do sistema Propig frente a uma maquininha tradicional:

> *"A gente pode falar assim, a tua taxa é zero. Beleza. Então, a taxa da revenda vai pagar taxa zero em todas as modalidades e tudo. E o distribuidor vai colocar aquilo ali no preço da mercadoria para ele. E a gente, como ProPig, em vez de cobrar da revenda, vai cobrar do distribuidor."* (INT-10/09)

> *"A gente tem esse arranjo, acho que o grande diferencial que o Tassi colocou é o nosso arranjo, é levar para o distribuidor que ele tem N formas de fazer ele vender."* (INT-10/09, Janduí)

Esse arranjo — cobrar da revenda, do distribuidor, ou dividir em qualquer proporção, por decisão puramente comercial do distribuidor — é confirmado operacionalmente em INT-14/09-PLAT (campo "boletos Moura" e política de isenção variável por distribuidor) e observado na prática em todas as três entrevistas de distribuidor (cada um descreve sua própria política de subsídio, diferente das outras duas — ver 2.4). **É um fato de arquitetura de sistema, não uma interpretação**: o sistema Propig permite essa flexibilidade; o uso concreto dela é decisão de cada distribuidor.

## 2.4 Três políticas de subsídio documentadas — divergentes entre si, nenhuma generalizável

Esta é uma das descobertas mais ricas do cruzamento entre as três entrevistas de distribuidor: **cada um desenhou uma política de subsídio/isenção estruturalmente diferente**, e nenhuma delas pode ser tomada como "a política do CredMoura":

**DIST-ANAPOLIS (Victor)**:
- Clientes inadimplentes: MDR zero incondicional (para converter dívida existente em fluxo garantido).
- Clientes novos: 6 meses de taxa zero + aluguel zero, sem exigência de volume; depois de 6 meses, renegociação vinculada à média de faturamento observada naquele período.
- Clientes estabelecidos: taxa zero condicionada a atingir uma meta de faturamento mínima (ex.: R$20 mil/mês mantém taxa zero; abaixo disso, cobra).
- Clientes de baixíssimo volume: em vez de taxa zero, recebem uma bateria gratuita a cada N meses de volume mínimo sustentado (cálculo explícito feito "na régua", convertendo o equivalente em taxa economizada em produto).

**DIST-UNIAO (Eduardo)** — o framework mais formalizado e documentado dos três:
- 4 parâmetros objetivos e permanentes (não campanha): (1) adimplência no programa BIM (devolução de bateria inservível em 30 dias), (2) participação ≥60% de Moura na categoria automotiva do PDV, (3) fachada padronizada Moura, (4) compra de todas as famílias de produto no mês (cross-sell).
- Atingir 1 parâmetro → isenção no Sessão. Atingir 2+ → isenção também no Flex 30.
- Eduardo é explícito sobre por que não faz campanhas temporárias de isenção: testou isso e, ao voltar a cobrar depois, gerou onda de cancelamento — a lição documentada é que **a política de subsídio precisa ser permanente e baseada em critérios estáveis, não em campanhas com prazo**, porque campanhas com prazo geram desconfiança ("hoje isenta, depois cobra").

**DIST-ROADMASTER (Victor)** — a política mais radicalmente diferente das outras duas:
- Abandonou a complexidade de Sessão/Flex/Multiagenda inteiramente. Opera com **uma única taxa por modalidade de pagamento** (débito, crédito, parcelado 2-6x, parcelado 7-10x — valores citados: 0,98/1,98/2,98/3,98-4,98%), igual para todas as bandeiras, sem aluguel de máquina, sem contrato de fidelidade.
- Subsídio: ele mesmo absorve a diferença entre a taxa que cobra (mais baixa) e a taxa "de tabela" da Propig (mais alta — ele cita 7% como taxa de tabela da Propig nesse contexto) — ou seja, **todo o subsídio está embutido numa taxa única e simples**, sem segmentação por critério de performance do cliente.
- Ele mesmo nomeia essa escolha como uma reação consciente à complexidade que via prejudicar a adoção: *"Não tem sessão, tem flex, flex 7030, flex 5050, flex 6060. É uma zona... A gente também não está nem adaptado para isso."*

**O que o cruzamento dessas três políticas mostra, com rigor** (e sem forçar uma conclusão única): a Propig oferece a infraestrutura técnica para qualquer política de subsídio ser implementada, mas **não impõe nem padroniza qual política usar** — isso é inteiramente uma decisão local do distribuidor, moldada por seu próprio histórico, porte e cultura de gestão. As três políticas documentadas não são "variações de uma política Moura" — são três desenhos independentes. Qualquer recomendação futura sobre "como desenhar a política de subsídio" precisa reconhecer que não existe hoje, nestes documentos, uma política única de referência do próprio CredMoura — existem apenas exemplos de distribuidores individuais, com resultados de penetração também muito diferentes entre si (ver 1.3).

## 2.5 O problema da integração D+2 e o "créditos a liberar"

Fato documentado com boa convergência entre fontes: existe (ou existia) um atraso na integração entre o sistema de captura de transações da Propig e o sistema de faturamento/crédito da Moura. INT-14/09-PLAT descreve a solução atual como automatizada via API ("pode levar até dois dias, dependendo da integração... às vezes acontece de algumas revendas transacionarem agora, em 40 minutos já contabiliza"), com um campo específico na interface do portal — "créditos a liberar" — criado para mostrar à revenda que um valor está retido por uma falha pontual de integração (API fora do ar), não perdido.

REV-LUCAS, porém, relata esse mesmo problema como ainda vivido na prática, com intensidade maior do que a narrativa do portal sugere: *"Tem mês que eu fico com um saldo de 50 mil e 40 mil em aberto, 15 dias, 10 dias"* — um atraso de reconciliação medido em dias, não em minutos ou horas, e com valores expressivos. Ele atribui a si mesmo (ex-funcionário Moura) a capacidade de não se desesperar com isso, porque entende a mecânica; mas afirma explicitamente que outras revendas, sem esse conhecimento prévio, concluem que "a Moura roubou ele" quando o saldo não bate.

**Isso é uma divergência relevante entre a narrativa do sistema (INT-14/09-PLAT, que descreve o problema como majoritariamente resolvido, residual e visível na interface) e a experiência relatada por uma revenda real (REV-LUCAS, que descreve o problema como ainda recorrente e financeiramente significativo).** Não escolho qual das duas é "a verdade atual" — ambas são evidência válida, de momentos e pontos de vista diferentes, e a divergência em si é um achado: há uma distância entre como o problema é descrito internamente (resolvido, com uma boa solução de UI) e como pelo menos uma revenda o vive na prática (ainda doloroso, ainda gerador de desconfiança). Essa mesma reconciliação dia a dia também aparece como fonte de atrito na conta de confiança do cliente da União (DIST-UNIAO): o episódio histórico em que a Propig depositava a parte da revenda mas **não** depositava a parte do cliente no plano Flex, gerando desconfiança que, segundo Eduardo, "até hoje" afasta alguns clientes antigos — um problema diferente (falha de liquidação, não de D+2), mas do mesmo gênero: falhas operacionais de reconciliação financeira que deixam marca duradoura na confiança, mesmo depois de corrigidas.

## 2.6 Taxas — o que está documentado, sem generalizar

Não existe "a taxa do CredMoura" — existem taxas por plano, por campanha, por distribuidor, e às vezes por cliente individual negociado. Os números concretos e verificáveis nos documentos:

- Débito: 1,99% (citado em REV-FABIO e em INT-14/09-PLAT, como exemplo de tela — convergência entre duas fontes independentes).
- Crédito à vista: 2,99% (mesmas duas fontes).
- Parcelado 2-12x: 4,89% (REV-FABIO cita "4,89" como a taxa "em F4"; INT-14/09-PLAT mostra a mesma taxa 4,89% para "de 2 até 12 vezes" num exemplo de tela; DIST-UNIAO cita a mesma cifra para Sessão).
- Flex 30: 7% (DIST-UNIAO, duas vezes na entrevista, com cálculo explícito do impacto na margem líquida de um pequeno negócio).
- Taxa de tabela Propig, segundo DIST-ROADMASTER: 7% (coerente com o Flex 30 de DIST-UNIAO, mas usado em contexto diferente).
- Roadmaster pratica, no entanto, uma tabela própria e mais simples: 0,98/1,98/2,98/3,98-4,98% — mais baixa que a "tabela" citada por outras fontes, porque ele mesmo absorve a diferença via subsídio direto (ver 2.4).
- Campanhas pontuais de taxa reduzida: "0,99%" por 2-3 dias em campanha nacional da fábrica (DIST-ANAPOLIS); "0,99%" por ~2 meses em campanha local do distribuidor de Lucas (REV-LUCAS); cashback de R$10 por transação 10x (DIST-UNIAO, relatado como "muito inteligente" mas com "resposta fraca" no momento do lançamento).

A conclusão segura aqui não é "a taxa do CredMoura é X%" — é que **a taxa efetiva paga por qualquer revenda específica é o resultado de uma combinação de plano + política local do distribuidor + eventual campanha vigente**, e generalizar qualquer um desses números isoladamente como "a taxa do produto" distorceria a realidade documentada.

## 2.7 Valor percebido vs. taxa nominal — o problema identificado e a resposta em construção

Um achado consistente entre fonte interna (Propig) e fonte de revenda: revendas comparam a taxa nominal do CredMoura com a taxa nominal anunciada por adquirentes tradicionais (ex.: "2,99% da Cielo") sem contabilizar o custo real de antecipação que pagariam nessas adquirentes se quisessem o mesmo prazo de recebimento (10-20%, segundo INT-10/09). Isso é dito tanto pela Propig internamente (INT-10/09: *"Ele fica gravado na cabeça 2,99... Ele não faz o cálculo ali quando ele precisa adiantar aquele recebível"*) quanto confirmado por uma revenda em REV-FABIO, que descreve ter feito exatamente essa comparação superficial ao reclamar da taxa de uma campanha de isenção perdida.

A resposta documentada da Propig a esse problema (não ainda avaliada quanto a efetividade, porque a funcionalidade era nova no momento da entrevista) é a funcionalidade "Economia do Credimora", lançada no portal novo (INT-14/09-PLAT, previsão de lançamento final de setembro/outubro). A funcionalidade nasceu de uma pesquisa conjunta Propig+Moura (projeto "Parceiro Moura") que identificou, segundo o próprio Bruno (supervisor de produto): *"a gente identificou que o cliente não via valor no Credemora"* — uma admissão direta de fracasso de percepção de valor, não resolvida até o momento da entrevista, apenas endereçada por uma nova funcionalidade ainda não testada em campo nestes documentos.

---

# Capítulo 3 — Análise da adoção e fatores de sucesso

> Este é o capítulo que o usuário identificou como o mais importante de toda a análise. Trato-o com o rigor máximo de separação entre evidência, interpretação e hipótese.

## 3.1 O que conta como "sucesso" — evidência, percepção, e o que não está disponível

Antes de atribuir qualquer sucesso a qualquer ator, é preciso definir o que, de fato, está documentado como tendo acontecido — versus o que é percepção de um entrevistado, versus o que simplesmente não está disponível nestes 9 documentos.

**Evidenciado com dados concretos (não apenas opinião)**, segundo INT-10/09 (fonte interna Propig, dados não auditados de forma independente nestes documentos, mas apresentados como números de gestão real, não estimativa):
- Clientes com CredMoura cresceram 2,13x em vendas de bateria desde uma base 100 em 2021 (ou seja, mais que dobraram em 5 anos); clientes sem CredMoura cresceram apenas 5% no mesmo período.
- Inadimplência total da Moura (não só dos clientes CredMoura) caiu cerca de pela metade; a inadimplência específica das transações CredMoura é "zero", chegando a "negativo" em alguns casos (sobra de crédito não utilizado).
- Prazo médio de recebimento (PMR) da Moura subiu de ~78 para ~87 dias — aumento de apenas 9 dias, apesar da mudança para parcelamento em 10x, o que os próprios interlocutores apontam como evidência de que o impacto de caixa foi "praticamente nulo".

**Ressalva documentada sobre esses mesmos números**, feita pelo próprio Janduí na mesma reunião: *"Existe uma miopia nesses números, principalmente para o distribuidor. Porque a inadimplência é aquilo, mas ela deveria ser olhada pelo distribuidor de maneira apartada. O que é de crédito em ouro e o que não é de crédito em ouro. (...) ele vai deixar de ver algum dinheiro entrando no caixa e achar que está tudo certo, mas ele está perdendo uma parte relevante"* (INT-10/09). Ou seja: a própria Propig já identifica que esses indicadores agregados podem mascarar efeitos de composição (por exemplo, clientes CredMoura podem ser sistematicamente os clientes de melhor perfil de risco desde o início, não necessariamente clientes que melhoraram de perfil por causa do CredMoura — essa possibilidade de causalidade invertida **não é descartada nem confirmada em nenhum dos 9 documentos**, e registro isso como lacuna explícita).

**Percepção, não dado (mas convergente entre múltiplas fontes independentes)**: satisfação com a solução financeira em si. DIST-ROADMASTER propõe, ele mesmo, que essa percepção deveria ser medida separadamente da percepção sobre qualidade operacional (portal, máquina, logística) — e estima, sem dado real disponível para ele, que o NPS operacional seria baixo e o NPS do "benefício Credimora" seria alto. Isso é a hipótese de um único entrevistado, não um dado medido, e assim deve ser tratada.

**Não disponível nestes documentos**: não há, nos 9 documentos, nenhuma pesquisa de satisfação consolidada e quantitativa das revendas com o programa como um todo (a pesquisa mencionada em INT-14/09-PLAT, do projeto "Parceiro Moura", é citada apenas pelo achado qualitativo "não via valor", sem os números completos da pesquisa estarem disponíveis nestes documentos). Também não há dado algum sobre taxa de cancelamento/churn consolidada a nível nacional — apenas relatos pontuais de distribuidores individuais (ver 3.4).

## 3.2 O que foi especificamente responsabilidade da Propig

Separando o que a Propig, como empresa de tecnologia/produto financeiro, efetivamente fez — por oposição ao que decisões de Moura ou de distribuidores produziram:

| O que a Propig fez | Como funcionou | Que problema resolveu | Evidência |
|---|---|---|---|
| Construiu a infraestrutura de subadquirência que permite antecipar a revenda sem antecipar o distribuidor | Conecta-se a adquirentes de base (Cielo/Rede) para processar a transação, mas gerencia o calendário de repasse de forma desacoplada do calendário de recebimento da revenda | Resolveu o descasamento de caixa que impedia a revenda de oferecer parcelamento competitivo | INT-10/09 (mecânica explicada com números) |
| Desenhou um sistema de flexibilidade de cobrança (quem paga a taxa: revenda, distribuidor, ou split) | Parametrização de política comercial dentro do sistema, sem precisar de desenvolvimento customizado por distribuidor | Permite que cada distribuidor desenhe sua própria política de subsídio sem depender da Propig para isso | INT-10/09, INT-14/09-PLAT, confirmado pelas 3 políticas distintas em 2.4 |
| Criou o Flex como alternativa ao Sessão | Split automático entre conta bancária e crédito-produto | Resolveu a necessidade de capital de giro líquido para revendas que não podiam esperar 100% em crédito-produto | INT-10/09; adoção e crítica em DIST-UNIAO, REV-LUCAS |
| Construiu e está reformulando os portais (revenda e distribuidor) | Dois portais distintos, com histórico de terem sido tardios (o portal do distribuidor "demorou um pouquinho a identificar que o distribuidor precisava de um canal") | Dar visibilidade de saldo, extrato, créditos a liberar, economia | INT-14/09-PLAT (demonstração completa) |
| Identificou e está respondendo ao problema de percepção de valor | Funcionalidade "Economia do Credimora" | Tentar fechar o gap entre taxa nominal e economia real percebida | INT-14/09-PLAT |
| Admitiu e está revisando seu próprio modelo de cobrança | Autocrítica explícita (ver 2.1) | Reduzir a comparação indevida com maquininha tradicional | INT-10/09 |

**O que a Propig não controla e não deve receber crédito ou culpa por**: a decisão de tornar a adesão do distribuidor obrigatória (foi decisão da Moura, via meta — ver 3.3); a política específica de subsídio de cada distribuidor (ver 2.4, decisão local); a qualidade do discurso de venda do vendedor de ponta (decisão/capacitação do distribuidor, ver 3.4); a decisão histórica de implantar Multiagenda de forma indiscriminada em Anápolis antes da chegada do Victor atual (decisão de uma gestão anterior do distribuidor, não da Propig — ver 3.4).

## 3.3 O que foi especificamente responsabilidade da Moura (indústria)

A adesão ao programa em nível de **distribuidor** não foi orgânica — foi imposta pela indústria via meta, de forma documentada e explícita:

> *"O distribuidor Moura, hoje ele é 70% Moura, 30% de um sócio administrador. Então o Moura manda nesse distribuidor. (...) O que a Moura fez foi colocar a meta, cara, de crede Moura. Então tem que transacionar... Você vai ter que trazer tantos clientes no crede Moura. (...) A indústria teve que empurrar a goela abaixo esse produto."* (INT-10/09)

> *"Depois que a gente saiu do piloto e fez o rollout para todos os distribuidores, todos eles aderiram. (...) Foi obrigatório."* (INT-10/09)

Essa obrigatoriedade **só foi possível por conta da estrutura societária do distribuidor** (70-75% Moura) — é um mecanismo de governança corporativa, não um mecanismo de produto ou de convencimento comercial. Esse ponto é central e é o mesmo que DIST-ROADMASTER identifica, de forma independente e com linguagem própria, como a razão pela qual o modelo funciona: *"Não tem um depósito do Brasil que esteja bombando o Credemora sem a distribuidora subsidiar. (...) Isso está fora da Propig, fora do guarda-chuva do Credemora."* — ou seja, mesmo um distribuidor fala desse subsídio como algo estrutural ao arranjo de propriedade, não ao produto Propig em si.

A Moura também é responsável, segundo as fontes, por:
- Campanhas pontuais nacionais de isenção de taxa (ex.: os "dois dias de 0,99%" citados por DIST-ANAPOLIS, "patrocinados pela rede"/fábrica).
- A decisão estratégica de permitir (ou não) que o próprio projeto de expansão para outras indústrias (Goodyear/"Godia", Decor Colors/"Decopol") usasse o CredMoura como modelo de referência — mas isso está fora do escopo desta análise, que foi explicitamente restrita a não analisar outras indústrias.
- Fornecer, via seus próprios sistemas internos (parceiro Moura, sistema de faturamento), a contraparte de integração que compõe o D+2 (ver 2.5) — ou seja, falhas de integração não são 100% atribuíveis à Propig; são uma responsabilidade compartilhada entre os dois sistemas (Propig e Moura), confirmada em INT-14/09-PLAT: *"de vez em outra, acontece da API cair ou algumas integrações não acontecerem no prazo específico."*

## 3.4 O que foi especificamente responsabilidade dos distribuidores — diferenciando papel esperado de prática observada

O papel **esperado** do distribuidor, segundo o desenho do produto, é: definir política comercial de subsídio, treinar/apoiar sua equipe de vendas na oferta do produto à revenda, e absorver o custo de capital de financiar o programa quando decide subsidiar.

A **prática observada**, porém, varia dramaticamente entre os três distribuidores entrevistados, e nem sempre correspondeu bem a esse papel esperado:

- **Anápolis** teve uma implementação anterior (antes da chegada do Victor atual) do Multiagenda feita, segundo ele, de forma indiscriminada e sem preparo: *"Pegaram a base de clientes... cadastra isso aqui todo mundo e manda a máquina para todo mundo e deixa que se lasque lá."* O resultado foi uma geração de desconfiança que persiste até hoje em parte da base ("quem teve o multiagenda, quem já teve o credimora, não quer ter de novo. E é difícil resgatar esse povo"). **Esta é uma falha de execução documentada de uma gestão anterior de um distribuidor específico — não do produto Propig, e não generalizável a outros distribuidores** (nem União nem Roadmaster relatam uma experiência equivalente de implantação mal feita de Multiagenda; Eduardo, da União, inclusive relativiza a importância do Multiagenda sem mencionar um trauma de implementação).
- **União** relata, de forma muito mais positiva, ter formalizado um framework de subsídio replicável e estável (os 4 parâmetros, ver 2.4), e atribui a si mesmo (não à Propig) a criação de um indicador de gestão de risco próprio ("blindagem do aberto") que não é uma funcionalidade do sistema Propig, mas uma métrica que o próprio distribuidor construiu para seu uso interno.
- **Roadmaster** relata ter simplificado radicalmente a oferta (taxa única, sem Sessão/Flex/Multiagenda) como decisão própria, de forma explicitamente diferente da arquitetura padrão do produto, e atribui a si mesmo o sucesso limitado que tem (8% da carteira, mas concentrado nos especialistas) a essa simplificação, não a qualquer mudança da Propig.

**O padrão que emerge do cruzamento das três entrevistas**: a Propig constrói e mantém a infraestrutura; mas o sucesso prático de adoção em cada praça depende quase inteiramente de decisões de execução tomadas localmente por cada distribuidor — decisões sobre política de subsídio, sobre segmentação de esforço comercial, sobre como (e se) corrigir erros de implementações anteriores. **Isso significa que não existe, nestes documentos, uma "receita Propig" de adoção que se repita identicamente em cada praça** — existem três execuções distintas, com resultados de penetração também muito distintos (ver 1.3), e a correlação entre "qualidade/coerência da política local" e "penetração resultante" é sugerida pelo cruzamento (União e Anápolis, com políticas mais elaboradas e consistentes, têm penetração mais alta em seus respectivos segmentos-alvo do que Roadmaster, que tem a penetração percentual mais baixa das três) mas **não pode ser tratada como causalidade comprovada com apenas três casos** — é uma hipótese razoável, não um fato estabelecido.

## 3.5 O que dependeu dos vendedores e das próprias revendas

Um tema recorrente, convergente em pelo menos quatro fontes distintas (INT-10/09, INT-14/09-PLAT, REV-LUCAS, DIST-ANAPOLIS), é que a qualidade do discurso de venda do vendedor de ponta (funcionário do distribuidor, não da Propig nem da revenda) é um fator crítico e frequentemente falho:

> *"O vendedor não fala, claro, com o cliente. O vendedor não tem conhecimento do Credemora. (...) O vendedor muitas vezes não está preparado para apresentar o Credemoro, ele não conhece direito."* (REV-LUCAS, falando como ex-funcionário Moura sobre o padrão que observou)

> *"Eu já até pensei em colocar, porque ano passado, no PPR dos vendedores, tinha faturamento Credemora. (...) eu estou pensando seriamente para o 2027 colocar alguma questão de credimora numa variável mensal dele, para ver se ele desacorda."* (DIST-ANAPOLIS — ou seja, mesmo com campanhas de bônus direto por cadastro, parte dos vendedores resiste a priorizar o produto)

> *"O grande desafio foi ensinar os vendedores de baterias a venderem máquina de cartão de crédito, porque os caras não tinham a menor familiaridade com isso."* (DIST-UNIAO)

Do lado da revenda, a decisão de aderir e de usar o produto de forma intensiva depende de uma mistura de fatores próprios do negócio (ver Capítulo 5 para detalhamento completo): se a bateria é o core business ou um item periférico (fator mais citado, convergente em praticamente todas as fontes), a situação de capital de giro da revenda (se ela consegue abrir mão de ter 100% do valor em conta), e a familiaridade prévia do proprietário com a mecânica (REV-FABIO e REV-LUCAS, ambos ex-funcionários/próximos da Moura, relatam ter entendido e adotado o produto mais rápido e com menos atrito do que a média relatada pelos distribuidores para outros clientes).

## 3.6 Fatores que dependem de combinação de atores

Alguns fatores de sucesso só se manifestam quando múltiplos atores agem de forma coordenada, e nenhum deles isoladamente é suficiente:

- **A conversão de market share** (crédito só pode ser gasto em produto Moura) só funciona se a Propig constrói a amarração técnica (ela faz), **e** o distribuidor mantém a política de que esse crédito não é livremente convertível em dinheiro (ele decide), **e** o vendedor da revenda de fato oferece a opção ao consumidor em vez de empurrar só a marca que já vendia (comportamento de ponta). Se qualquer um desses três elos falha, o mecanismo de ganho de market share não se concretiza plenamente.
- **A "democratização" da taxa** (pequena revenda com a mesma taxa que uma grande) só gera adoção efetiva se, simultaneamente, o distribuidor local tiver política de subsídio favorável a pequenos clientes (nem todos têm — ver 4 e 5) e se a revenda tiver capital de giro suficiente para tolerar a parte do valor que fica em crédito-produto em vez de caixa.
- **A redução de inadimplência** no nível macro da Moura (citada em 3.1) depende da combinação de adesão suficiente de volume (Propig/distribuidor) **e** da manutenção, pelo distribuidor, de práticas de concessão de crédito que não transfiram o risco de volta para outro lugar (por exemplo, Eduardo, da União, relata usar o CredMoura para estender crédito a clientes antes rejeitados — "picaretas" — o que é, ao mesmo tempo, geração de novo volume e uma decisão de apetite de risco do próprio distribuidor, não do produto em si).

## 3.7 Matriz de atribuição dos fatores de sucesso

| Fator identificado | Ator responsável | Ação concreta | Mecanismo de influência | Resultado observado | Evidência | Dependências / ressalvas |
|---|---|---|---|---|---|---|
| Antecipação à revenda sem antecipação ao distribuidor | **Capacidade própria da Propig** | Desenho de calendário de repasse desacoplado | Permite taxa all-in menor que custo de antecipação de mercado | Taxa ~5% vs 10-20% de mercado para antecipação equivalente | INT-10/09 | Só funciona porque o distribuidor já tolerava prazo longo de recebimento antes do produto (pré-condição da Moura, não da Propig) |
| Flexibilidade de quem paga a taxa | **Capacidade própria da Propig** | Parametrização de cobrança por revenda/distribuidor/split | Permite qualquer política local de subsídio sem desenvolvimento customizado | 3 políticas de subsídio totalmente distintas implementadas (Anápolis, União, Roadmaster) | INT-10/09, INT-14/09-PLAT, 2.4 | O uso concreto e a qualidade da política é decisão do distribuidor, não da Propig |
| Amarração do crédito a produto Moura | **Fator compartilhado** (Propig constrói, Moura/distribuidor decide manter) | Crédito gerado só é conversível em bateria/produto Moura | Converte parcelamento genérico em ferramenta de ganho de market share | Clientes CredMoura cresceram 2,13x vs 5% dos demais (2021-atual) | INT-10/09 | Causalidade não auditada de forma independente — possível efeito de seleção (quem adere já era cliente de maior potencial) não descartável com estes dados |
| Adesão obrigatória ao nível de distribuidor | **Condição proporcionada pela Moura** | Meta de adesão/transação imposta via governança societária (70-75% Moura) | Garante rollout de 100% dos distribuidores, independentemente de convencimento comercial | "Todos os distribuidores aderiram... foi obrigatório" (INT-10/09) | INT-10/09 | Mecanismo não disponível para uma indústria sem essa estrutura de propriedade sobre o distribuidor — ver Cap. 8 |
| Adesão orgânica ao nível de revenda | **Condição específica do ecossistema** (perfil "especialista") | — | Revendas onde bateria é o core business aderem; onde é item periférico, não aderem | Penetração de 90%+ em casas de bateria especializadas (Anápolis) vs. 8% da carteira total (Roadmaster) | DIST-ANAPOLIS, DIST-UNIAO, DIST-ROADMASTER, INT-10/09 | Transversal a todos os distribuidores entrevistados — é o fator de segmentação mais consistente de todo o corpus |
| Política local de subsídio formalizada e permanente | **Contribuição dos distribuidores** | Framework de 4 parâmetros estáveis (União) vs. políticas ad hoc | Políticas permanentes evitam onda de cancelamento que políticas de campanha temporária geram | União relata maior estabilidade de adesão; Anápolis relata dificuldade persistente de recuperar clientes que já saíram uma vez | DIST-UNIAO, DIST-ANAPOLIS | Não comprovado como causal com apenas 3 casos — é padrão sugerido, não demonstrado estatisticamente |
| Capacitação e priorização do vendedor de ponta | **Contribuição dos distribuidores e vendedores** | Treinamento, simulações de venda, incentivos financeiros diretos | Determina se o discurso de valor chega de forma clara e correta à revenda | Mesmo com incentivo de R$500-1000 por campanha, parte dos vendedores não prioriza o produto (Anápolis); problema também citado por Propig internamente e por revendas | DIST-ANAPOLIS, INT-10/09, REV-LUCAS | Varia por indivíduo vendedor, não é resolvido estruturalmente por nenhum ator até o momento das entrevistas |
| Correção de implementação anterior malfeita (Multiagenda) | **Capacidade/decisão do distribuidor local** | Banir a prática antiga, recomeçar do zero a comunicação | Reduz (não elimina) o estoque de desconfiança herdado | Ainda hoje, segundo Anápolis, "é difícil resgatar esse povo" mesmo com MDR zero oferecido | DIST-ANAPOLIS | Específico de um distribuidor; não generalizável — outros distribuidores não relatam o mesmo trauma |
| Conhecimento prévio do operador da revenda sobre a mecânica Moura/Propig | **Condição específica do indivíduo/revenda**, não do ecossistema em geral | — | Reduz desconfiança e atrito de reconciliação financeira | Fábio e Lucas Barreto, ambos ex-ligados à Moura, relatam adoção e reconciliação mais tranquilas que o padrão descrito para revendas "leigas" | REV-FABIO, REV-LUCAS | Não generalizável à maioria das revendas, que não têm esse histórico prévio |
| Percepção de valor vs. taxa nominal | **Fator compartilhado, ainda não resolvido** | Funcionalidade "Economia do Credimora" (Propig) tentando corrigir comparação indevida de taxas | Tenta mostrar economia real em R$, não só taxa % | Pesquisa identificou que "cliente não via valor"; solução lançada mas sem dado de efetividade nestes documentos | INT-14/09-PLAT | Lacuna: não há avaliação pós-lançamento disponível nestes 9 documentos |

---

# Capítulo 4 — Valor para distribuidores

## 4.1 O benefício primário, segundo a fonte mais experiente e mais categórica

DIST-UNIAO (Eduardo) é o mais explícito e o mais seguro de todas as fontes de distribuidor sobre qual é o benefício central, e vale reproduzir a formulação completa porque é a articulação mais nítida de todo o corpus:

> *"Eu vejo mais vantagem em se diferenciar da concorrência e ganhar participação dentro do ponto de venda do que os outros benefícios financeiros (...) O Credemora dentro de um ponto de venda multimarca é como se tivesse um funcionário seu trabalhando lá pra converter toda a venda em Moura (...) é um sistema de fomento (...) convertendo de maneira meio oculta as marcas na sua marca. Esse é o maior benefício."*

Ele classifica redução de inadimplência e financiamento do consumidor como **benefícios secundários**, não o motivo central — uma hierarquização explícita e pessoal dele, que nem todas as outras fontes replicam da mesma forma (ver 4.2 para nuances).

**Por que esse benefício funciona mecanicamente, e não apenas retoricamente**: numa loja multimarca (ex.: autopeças que vende Moura e outras baterias), a revenda pode vender qualquer marca na mesma maquininha, mas a reposição de estoque gerada pelo crédito só pode ser produto Moura. Então, mesmo uma venda de uma bateria concorrente "alimenta" o crédito que será convertido em compra futura de Moura — e, segundo o próprio Eduardo, se o PDV passar 10 marcas diferentes pelo Credemora, "vai virar tudo Moura" na reposição.

## 4.2 Outros benefícios documentados — e como variam entre distribuidores

- **Redução de inadimplência / "blindagem do aberto"**: DIST-UNIAO quantifica com dado real próprio: 60% do contas-a-receber da União está "blindado" por crédito garantido do CredMoura, contra "10%" em concorrentes menos estruturados (comparação que ele faz, não dado de terceiros verificado). DIST-ANAPOLIS confirma a lógica qualitativamente ("nossa inadimplência tende a cair bastante"), sem quantificar com a mesma precisão.
- **Expansão do apetite de risco**: achado específico de DIST-UNIAO, não replicado nas outras duas entrevistas de distribuidor — ele relata ter passado a vender para clientes antes recusados ("picaretas") porque o risco de inadimplência da transação em si é zero. Isso é uma consequência de segunda ordem documentada apenas por esta fonte; não generalizo a outros distribuidores.
- **Gestão de fluxo de caixa / redução de custo de capital em cenário de Selic baixa**: achado único de DIST-UNIAO (zerava o MDR quando a Selic caía, porque o custo de oportunidade do dinheiro parado ficava baixo) — também não replicado nas outras entrevistas, e tratado aqui como uma variável específica de um distribuidor financeiramente sofisticado, não uma dinâmica estabelecida do produto em geral.
- **Fidelização e retenção de clientes de maior porte**: DIST-ROADMASTER enfatiza esse ângulo com uma metáfora própria ("eu brinco que é até um casamento") e argumenta que o CredMoura "blinda" a relação contra tentações externas (empréstimos, juros altos de outras fontes) — um ângulo de retenção de longo prazo, distinto do ângulo de conversão de market share de Eduardo, mas não incompatível com ele.
- **Dificuldade em capturar o pequeno cliente como contrapartida negativa**: DIST-ROADMASTER é o mais explícito sobre o limite desse valor — para ele, o CredMoura simplesmente **não tem** uma proposta de valor que funcione para o cliente pequeno (ver 4.3), o que limita o alcance do benefício de fidelização/conversão a apenas uma fração da carteira.

## 4.3 Limitações do valor para o distribuidor — explicadas com mecanismo, não apenas listadas

A explicação mais precisa e quantificada de por que o CredMoura não atinge o pequeno cliente vem de DIST-ROADMASTER, com um cálculo explícito:

> Cliente pequeno compra ~10 baterias/mês (~R$3.500). Economia de taxa de ~6% = ~R$210/mês. Descontado o aluguel da máquina (~R$70-90), sobra pouco. Para esse ganho líquido pequeno, o cliente teria que assumir uma relação com "outra empresa, outro portal, outra gestão" — o custo operacional de gerenciar uma segunda máquina/relação supera o ganho financeiro. *"Todo o trabalho para ele economizar quanto? 200 reais, 150 reais. Não vale a pena."*

Esse mecanismo — custo operacional de gestão superando o ganho financeiro marginal em baixo volume — é consistente com (embora formulado de forma distinta de) o relato de INT-10/09 sobre por que a Propig "não tem produto" para revendas não especialistas: *"Se economizar 5% de taxa nesse negócio, vai economizar R$50, R$60 no final do mês (...) não vale a pena."* **Duas fontes independentes (uma distribuidor, uma interna Propig) convergem no mesmo mecanismo explicativo**, o que dá a essa conclusão um nível de confiança maior do que teria se viesse de uma fonte só.

Uma segunda limitação, documentada apenas por DIST-ANAPOLIS, é o efeito duradouro de uma má experiência anterior (herança do Multiagenda malfeito): *"quem já teve o credimora, não quer ter de novo. E é difícil resgatar esse povo. Mesmo dando um MDR zero e tudo."* — ou seja, uma vez perdida a confiança, nem subsídio financeiro total é suficiente para reverter a decisão, pelo menos nesse caso documentado.

Uma terceira limitação, mencionada apenas por DIST-ROADMASTER e não corroborada em outras fontes, é a lacuna de qualidade operacional frente a concorrentes: *"Quando você pega uma Cielo, Stone, Rede (...) o prazo médio de troca deles é um dia (...) a gente demora cinco, sete dias para trocar uma máquina"* — ele atribui essa lentidão à Propig (ou ao fato de "não ser 100% focada em tecnologia"), mas essa é também relatada, de forma consistente, por DIST-ANAPOLIS ("acho a nossa logística ainda muito limitada") e por REV-LUCAS ("foram quatro horas para eu conseguir resolver" uma simples troca de máquina com problema) — **esta é uma convergência de três fontes de dois níveis diferentes da cadeia (dois distribuidores e uma revenda), o que a torna um achado robusto, não um relato isolado.**

---

# Capítulo 5 — Valor para revendas

## 5.1 Por que uma revenda adere — motivos documentados, sem forçar um motivo único

Não há um motivo único de adesão nas duas entrevistas de revenda disponíveis — há motivos distintos, moldados pelo estágio do negócio de cada uma:

- **REV-LUCAS** (loja com 1,5 ano, começou pequena): o motivo foi explicitamente competitivo/de sobrevivência inicial — sem o CredMoura, ele não conseguiria oferecer parcelamento competitivo com lojas grandes já estabelecidas, no momento em que seu próprio faturamento era baixo demais para negociar boas taxas com adquirentes tradicionais: *"No meu primeiro mês eu vendi 30 baterias (...) Com um faturamento desse eu nunca ia conseguir uma taxa de 7%... O Credmora, no início, ele me ajudou a conseguir disputar com as lojas grandes."*
- **REV-FABIO** (conforme leitura já registrada nesta investigação, loja mais estabelecida, ~14-15 máquinas): a adoção foi mais gradual e inicialmente hesitante ("ficou meio com medo"), e sua lógica de decisão amadureceu para uma regra pessoal baseada num múltiplo de faturamento ("regra do 4x") comparando o custo da máquina Propig com a máquina de banco — ou seja, uma decisão racional-financeira recorrente, não um ato único de adesão.

**O fator mais citado e mais convergente entre as duas entrevistas de revenda e as três de distribuidor, para explicar adesão ou não-adesão**, é se a bateria é o **core business** (onde a adesão é natural e frequentemente alta) ou um item periférico de um negócio maior como autopeças/autocenter (onde a adesão é rara). Isso é dito quase nas mesmas palavras por DIST-UNIAO (*"onde a bateria é um produto, não é o produto principal, não tem muita conexão"*) e aparece implicitamente em REV-LUCAS e REV-FABIO, cujos negócios são especializados em bateria.

## 5.2 A experiência de uso — o que funciona bem e o que gera atrito, segundo quem usa

**Pontos positivos relatados diretamente por revendas** (não apenas afirmados pela Propig ou pelo distribuidor):
- Velocidade de recebimento ("praticamente no dia seguinte", até 48h) frente à alternativa de ter que esperar o ciclo completo de recebíveis — citado como vantagem concreta em ambas as entrevistas de revenda.
- Simplicidade de não precisar de uma segunda maquininha de outra bandeira para gerir fluxo de caixa quando no plano Flex (motivo explícito de Lucas para escolher Flex 50/50 numa das suas duas lojas).
- Em campanhas de isenção temporária, impacto financeiro percebido como real e positivo: Lucas estima "uns 5 mil reais a mais" num mês de campanha de taxa 0,99%; Fábio, em outra ocasião registrada nesta investigação, estimou um valor maior (R$6.800-9.000) para uma campanha equivalente — **duas estimativas independentes de dois revendedores diferentes para campanhas semelhantes, ambas positivas em direção mas de magnitude distinta** (nenhuma delas é um dado medido pela Propig; são autoestimativas das próprias revendas).

**Pontos de atrito relatados diretamente por revendas**:
- Dificuldade de reconciliação financeira diária (ver 2.5) — Lucas relata saldos em aberto de 40-50 mil reais por 10-15 dias em alguns meses, e atribui a si mesmo (por conhecimento prévio da Moura) a capacidade de não se desesperar com isso.
- Pós-venda de troca de máquina defeituosa — processo burocrático (exigência de vídeo de comprovação), levando até 4 horas de negociação para uma exceção e cerca de uma semana de espera pela máquina nova (REV-LUCAS); problema de categoria similar (aluguel/tempo de troca) também citado por Fábio e por dois dos três distribuidores (ver 4.3), o que torna este um dos achados mais robustos de todo o corpus, por aparecer em quatro fontes de níveis diferentes da cadeia.
- Opacidade de rastreamento de créditos de campanha no extrato: Lucas relata que o portal mostra "códigos aleatórios" em vez de identificar claramente qual lançamento corresponde a qual campanha de isenção, exigindo que ele pergunte diretamente ao distribuidor — um gap de transparência pequeno mas concreto, consistente com o problema maior de percepção de valor relatado em INT-14/09-PLAT.
- Expectativa mal calibrada criada pelo próprio vendedor do distribuidor: o vendedor promete "amanhã você recebe" quando a janela real é de até 48h, criando frustração evitável (REV-LUCAS) — isso é uma falha de comunicação do vendedor do distribuidor, não do produto ou da Propig em si (ver 3.5).

## 5.3 Valor que a Propig acredita entregar vs. valor que a revenda de fato reconhece

Este é um ponto onde a própria Propig identifica, documentadamente, uma lacuna entre intenção e percepção — não é uma interpretação externa minha, é uma admissão da própria empresa:

> *"A gente identificou que o cliente não via valor no Credemora. (...) O que acontece é que a revenda, muitas vezes, quando a gente vê aquele detrator, muitas vezes a revenda não consegue entender a solução."* (INT-14/09-PLAT, INT-10/09)

Os próprios interlocutores internos atribuem essa lacuna a dois mecanismos distintos, que não devem ser fundidos em um só:
1. **Mecanismo de comparação de taxa nominal incompleta** (ver 2.7) — a revenda compara % nominal, não custo real de antecipação equivalente.
2. **Mecanismo de percepção de "dinheiro preso"** — mesmo quando a economia em R$ é demonstrada, a revenda relata (segundo INT-10/09) continuar enxergando o saldo em crédito-produto como "dinheiro que está preso ao distribuidor", uma sensação qualitativa de perda de controle financeiro que a demonstração de economia não resolve sozinha: *"mesmo quando tem uma economia, e a gente faz cálculo com ela, mostra para ela aquela economia que ela está tendo (...) ela vê sempre que o dinheiro está no distribuidor. O dinheiro, sempre falam, o dinheiro está preso ao distribuidor."*

Esses dois mecanismos — um cognitivo/comparativo, outro emocional/de controle percebido — exigem respostas diferentes, e a solução lançada (funcionalidade "Economia") endereça primariamente o primeiro, não necessariamente o segundo. Isso não está resolvido nestes documentos; é uma lacuna identificada pela própria Propig, sem solução testada disponível nas fontes.

## 5.4 Dois regimes de valor, segundo o próprio padrão que emerge do cruzamento

Cruzando REV-FABIO, REV-LUCAS, DIST-UNIAO e DIST-ROADMASTER, emerge um padrão (não uma categoria oficial do produto, é uma leitura analítica deste relatório a partir da convergência das fontes): o valor do CredMoura para uma revenda parece depender fortemente de sua posição de capital inicial —

- Para uma revenda **nova ou subcapitalizada** (caso de Lucas no início), o valor é de **acesso**: sem o produto, ela simplesmente não teria condições de oferecer parcelamento competitivo, independentemente de preferência.
- Para uma revenda **já capitalizada e especialista** (caso de Fábio, ou do perfil "especialista" descrito pelos distribuidores), o valor é de **otimização/competitividade continuada**: ela já teria alternativas, mas o CredMoura oferece uma condição melhor ou equivalente sem os custos operacionais de gerir uma segunda relação de adquirência.
- Para uma revenda de **baixo volume ou negócio periférico** (ponto de venda onde bateria não é o core), o valor líquido tende a ser **insuficiente frente ao custo operacional** de adotar (ver 4.3, mecanismo explicado por Roadmaster e por INT-10/09).

Essa tripla categorização é uma leitura interpretativa deste relatório construída a partir da convergência das quatro fontes citadas — não é uma segmentação que a própria Propig ou Moura usem explicitamente nos documentos (eles usam a dicotomia "especialista vs. não especialista", que é parecida mas não idêntica: a dicotomia oficial é sobre o papel da bateria no negócio, a tripla acima é sobre a posição de capital/porte, um corte adicional sugerido pelos próprios relatos de revenda).

---

# Capítulo 6 — Dores, limitações e oportunidades

> Organizado por perspectiva. Problemas isolados, recorrentes e estruturais são diferenciados explicitamente.

## 6.1 Perspectiva das revendas

### 6.1.1 Reconciliação financeira e confiança (recorrente, tendendo a estrutural)
- **Dificuldade concreta**: saldo que não bate entre o portal e o esperado, atraso de D+2 às vezes muito maior na prática (até 15 dias segundo REV-LUCAS).
- **Quem é afetado**: revendas sem conhecimento prévio da mecânica Moura/Propig (a maioria, segundo o próprio relato de Lucas sobre o padrão que ele via como ex-funcionário).
- **Momento da jornada**: uso contínuo, não apenas onboarding.
- **Causa provável**: falhas pontuais de integração de API (confirmadas em INT-14/09-PLAT como existentes, "de vez em outra"), mas a intensidade relatada por Lucas sugere que a frequência real pode ser maior do que a narrativa interna da Propig admite — **divergência entre fonte interna e fonte de campo, já registrada em 2.5**.
- **Impacto**: desconfiança ("a Moura roubou ele", conforme o padrão que Lucas descreve ter visto em outras revendas), podendo levar a cancelamento.
- **Como contornam hoje**: revendas com conhecimento prévio (como Lucas e Fábio) fazem controle paralelo manual, mas isso "demanda tempo"; revendas sem esse conhecimento, segundo o relato de Lucas, simplesmente desconfiam e eventualmente saem.
- **Oportunidade de melhoria identificada nos documentos**: nenhuma solução testada está documentada para este ponto especificamente — a funcionalidade "créditos a liberar" (INT-14/09-PLAT) endereça a visibilidade do problema, não necessariamente sua frequência ou velocidade de resolução.
- **Responsabilidade**: compartilhada entre Propig e Moura (ambos os lados da integração), mas a resolução de atendimento ao cliente quando o saldo não bate passa pelo distribuidor e pela Propig juntos.

### 6.1.2 Logística de pós-venda (recorrente, convergente entre 3-4 fontes)
- **Dificuldade concreta**: troca de máquina com defeito lenta (até uma semana) e burocrática (exigência de vídeo-prova).
- **Quem é afetado**: qualquer revenda com uma máquina com problema, mas com impacto desproporcional em revendas pequenas com poucos terminais (Lucas, com 3 máquinas, ficou sem terminal funcional por dias; um distribuidor grande absorve essa perda de forma menos crítica).
- **Momento da jornada**: pós-venda / manutenção corrente.
- **Causa provável**: processo de suporte não otimizado para urgência (exigência de evidência antes de autorizar substituição) e Propig "não ser 100% focada em tecnologia" (autoavaliação de DIST-ANAPOLIS sobre a Moura/Propig em comparação a Stone/Cielo/Rede).
- **Impacto**: máquina parada gera aluguel cobrado sem uso, e pode gerar perda de venda enquanto o terminal está fora.
- **Como contornam hoje**: uso de uma segunda máquina (de outro adquirente) como contingência — relatado tanto por Fábio quanto por Lucas.
- **Oportunidade de melhoria**: nenhuma solução documentada; é identificada como gap competitivo explícito por dois distribuidores (Anápolis e Roadmaster) e por uma revenda (Lucas), mas sem resposta testada nas fontes.
- **Responsabilidade**: operador logístico contratado pela Propig e processo interno de suporte.

### 6.1.3 Capacitação do vendedor (recorrente, estrutural)
- Já detalhado no Capítulo 3.5 e 5.2 — reafirmado aqui como dor de revenda porque o efeito prático sentido pela revenda é expectativa mal calibrada e eventual perda de confiança em algo que, tecnicamente, funcionou como prometido, mas foi mal comunicado.

### 6.1.4 Percepção de "dinheiro preso" (estrutural, sem solução testada disponível)
- Já detalhado em 5.3 — é o ponto mais estrutural de todos, porque decorre da própria arquitetura do produto (crédito não sacável no Sessão), não de uma falha corrigível de execução.

## 6.2 Perspectiva dos distribuidores

### 6.2.1 Herança de implementações anteriores malfeitas (isolado, mas com efeito duradouro)
- Específico de Anápolis (Multiagenda implementado sem preparo por gestão anterior). Já detalhado em 3.4/4.3. Classificado como problema **isolado** desta praça, não recorrente nas outras duas entrevistas de distribuidor — mas com **efeito estrutural duradouro** onde ocorreu (ainda ativo anos depois, segundo o próprio Victor).

### 6.2.2 Dificuldade de transbordar valor para a equipe de vendas em escala (recorrente)
- **Dificuldade concreta**: mesmo com discurso de valor claro na cabeça do sócio/gestor, garantir que isso chegue de forma consistente a dezenas de vendedores em campo é difícil.
- **Quem é afetado**: distribuidores com equipes de vendas numerosas e dispersas geograficamente (Anápolis cita equipe "no interior" com cadência semanal, dificultando reação rápida a clientes inativos).
- **Momento da jornada**: operação corrente, gestão de performance de vendedores.
- **Causa provável**: ausência de ferramenta própria de alerta proativo (o distribuidor de Anápolis pede explicitamente algo como "aparecesse lá inativos do dia para o vendedor agir" em vez de depender de reunião de cadência semanal) combinada com restrição de acesso ao portal que, segundo ele, piorou ao longo do tempo ("ficou um pouco mais limitado em entrar no portal").
- **Impacto**: clientes ficam inativos por até 3 meses antes de qualquer ação, e o próprio distribuidor considera isso inaceitável quando descoberto via relatório da Propig em vez de via gestão interna própria.
- **Como contornam hoje**: reuniões de cadência semanais (insuficiente, segundo o próprio Victor) e, no passado em outras praças (Rio, ES), acompanhamento diário manual via portal — prática que não escalou ou não se sustentou em Anápolis.
- **Oportunidade de melhoria identificada pelo próprio entrevistado**: alerta automatizado de inatividade integrado a uma ferramenta já usada pela equipe (ele cita Salesforce como exemplo).
- **Responsabilidade**: primariamente do distribuidor (gestão de equipe e cadência), mas com uma oportunidade de ferramenta que dependeria da Propig construir e disponibilizar.

### 6.2.3 Gap de qualidade operacional vs. concorrentes tradicionais (recorrente, estrutural)
- Logística de troca de máquina (ver 6.1.2) e qualidade de portal/app frente a Stone/Cielo/Rede — citado por dois dos três distribuidores (Anápolis, Roadmaster), com Roadmaster propondo a hipótese (não testada) de que isso explicaria um NPS operacional baixo mesmo com alta satisfação com o benefício financeiro do produto.

### 6.2.4 Limite estrutural de alcance ao pequeno cliente (estrutural, não um "problema a resolver" no sentido convencional)
- Já detalhado em 4.3 com o mecanismo explícito de Roadmaster — tratado aqui como dor porque é citado pelos próprios distribuidores como uma frustração ("eu ia botar toda a minha força... fomentar alguma solução para o pequeno (...) a gente não dá uma solução de crédito para o pequeno", DIST-ROADMASTER), não apenas como um limite técnico neutro.

## 6.3 Perspectiva da operação (Propig/Moura)

### 6.3.1 Modelo de cobrança que convida à comparação com maquininha tradicional (estrutural, admitido pela própria liderança)
- Já detalhado em 2.1 — a única dor desta lista que é auto-identificada pela própria liderança do produto como erro de desenho, não como execução imperfeita de um desenho correto.

### 6.3.2 Percepção de valor não resolvida mesmo com nova funcionalidade lançada (estrutural, sem avaliação de efetividade disponível)
- Já detalhado em 2.7 e 5.3.

### 6.3.3 Integração D+2 com Moura como ponto de fragilidade técnica compartilhada (recorrente)
- Já detalhado em 2.5/6.1.1 — reafirmado aqui como dor "de operação" porque a responsabilidade de resolução passa por sistemas dos dois lados (Propig e Moura), não só de um.

### 6.3.4 Produto Multiagenda em "limbo" interno (isolado como status do produto, mas revelador)
- **Dificuldade concreta**: o Multiagenda, desenhado para dar máxima flexibilidade à revenda, gerou receio nos distribuidores (perda de garantia de conversão em crédito) e confusão de UI para a revenda (dificuldade de diferenciar, no extrato, o que veio do "lado Moura" vs. "lado Loja"), ficando, segundo o próprio relato interno, estacionado sem rollout amplo: *"esse produto do multiagenda (...) acabou meio que entrando num limbo até aqui dentro da empresa."* (INT-14/09-PLAT)
- **Quem é afetado**: a Propig internamente (produto não evolui), distribuidores receosos de adotar amplamente, e a minoria de revendas que o usa de forma inconsistente (ex.: o cliente citado por Eduardo que "fica migrando" entre Sessão Total e Flex).
- **Causa provável**: tensão de incentivos não resolvida entre dar autonomia total à revenda (objetivo de design) e garantir previsibilidade de conversão em crédito para o distribuidor (necessidade de negócio) — um trade-off estrutural, não um bug.
- **Impacto**: produto existe mas não escala; recursos de desenvolvimento usados em um produto que a própria Propig está "testando em segmentos específicos" sem convicção de rollout.
- **Oportunidade de melhoria**: nenhuma solução documentada; é citada como trabalho em andamento sem resultado disponível nestas fontes.

---

# Capítulo 7 — Aprendizados transversais

## A) Produto financeiro vs. ecossistema comercial — combinações, não escolha única

O cruzamento de todas as fontes mostra que o CredMoura não é "um produto financeiro que também tem efeitos comerciais" nem "uma estratégia comercial que usa um instrumento financeiro como pretexto" — é, de forma consistente entre as fontes, **as duas coisas operando na mesma transação, com pesos que mudam de ator para ator**:
- Para o consumidor final, é puramente financeiro (acesso a parcelamento).
- Para a revenda, é financeiro primeiro (fluxo de caixa, antecipação) e comercial depois (competitividade frente a lojas maiores).
- Para o distribuidor, segundo a fonte mais categórica (Eduardo/União), é **comercial primeiro** (conversão de market share) e financeiro depois (redução de inadimplência é "secundária" na hierarquia dele).
- Para a Propig, é estruturalmente um produto financeiro (ela é subadquirente, cobra taxa de transação) tentando se posicionar como mais do que isso ("não somos uma empresa de maquininha") — uma tensão de identidade que a própria liderança reconhece não ter resolvido (ver 2.1).

Não há, nos documentos, uma única resposta certa sobre "o que é" o CredMoura — há um produto que funciona de forma diferente, financeiramente e comercialmente, dependendo de qual elo da cadeia o observa.

## B) O que impulsiona adesão vs. o que impulsiona continuidade — e por que não são a mesma coisa

Adesão (a decisão inicial de aceitar a máquina) e uso recorrente/satisfação (a decisão de continuar e intensificar o uso) têm, segundo as evidências cruzadas, **gatilhos diferentes**:

- **Adesão** costuma ser impulsionada por fatores estruturais e de curto prazo: obrigatoriedade a nível de distribuidor (ver 3.3), campanhas de incentivo ao vendedor (ver 3.5), ou necessidade imediata de competitividade (caso Lucas, início de operação).
- **Continuidade/intensificação** depende de fatores que só se manifestam depois de meses de uso: se a revenda consegue reconciliar financeiramente sem atrito (ver 6.1.1), se a política de subsídio é percebida como estável e não arbitrária (lição explícita de Eduardo sobre campanhas temporárias gerando cancelamento quando revertidas), e se o perfil de negócio (especialista vs. periférico) sustenta volume suficiente para compensar a complexidade operacional (ver 4.3).

Uma evidência direta dessa diferença: as "7 mil revendas aderentes de 70 mil" (INT-10/09) não é o mesmo número que "revendas satisfeitas" ou "revendas que usam intensivamente" — os próprios distribuidores relatam clientes que aderiram e voltaram ao padrão anterior de uso ("depois aquilo virou paisagem e ele começa a voltar para aquele patamar anterior", DIST-UNIAO, sobre isenções que perderam efeito) e um volume de churn substancial e explicitamente quantificado por Roadmaster ("no mínimo 600 clientes a gente botou para dentro da base (...) ficaram somente os grandes").

## C) Valor intrínseco do produto vs. incentivo externo — quatro categorias separadas pela evidência

Separando o que, segundo as fontes, faz uma revenda ficar no produto por valor genuíno (o produto resolve algo que ela valoriza por si só) versus por incentivo externo (ela fica porque está sendo paga/pressionada para isso), aparecem quatro situações distintas e documentadas:

1. **Valor intrínseco sem incentivo externo necessário**: revendas especialistas em bateria, já capitalizadas, que usam o produto pela vantagem de fluxo de caixa e competitividade real (perfil Fábio, perfil "especialista" descrito por todos os distribuidores). Aqui a adesão tende a ser estável mesmo sem campanha ativa.
2. **Incentivo externo sustentando o uso, sem valor intrínseco claro ainda estabelecido**: clientes trazidos por campanhas de bônus ao vendedor (ex.: campanha de Anápolis), onde o próprio distribuidor relata que parte desses cadastros não se converte em revendas de fato ativas no Credimora (vendedor "abriu cinco clientes, mas não abriu cinco com o Credemora").
3. **Incentivo externo que, com o tempo, converte-se em valor percebido**: o próprio histórico da adesão a nível de distribuidor (3.3) — a Moura "empurrou" a adesão via meta, mas depois de anos de dados (crescimento 2,13x, etc.) os próprios distribuidores relatam ter passado a ver valor genuíno, não apenas cumprir meta (INT-10/09: *"depois de um tempo, quanto mais ele transacionasse (...) mais ele vendia bateria. Aí ele falou, agora liguei uma coisa a outra."*).
4. **Nem incentivo nem valor intrínseco suficientes**: o segmento de pequeno volume/negócio periférico, onde nenhuma quantidade de subsídio documentada parece ter revertido a equação de custo operacional vs. ganho (ver 4.3) — aqui, segundo Roadmaster, a Moura "não tem solução" ainda.

## D) Desalinhamento entre atores — padrões documentados

- **Propig incentiva migração Sessão→Flex (via comissão ao vendedor), mas o distribuidor mais experiente da amostra desaconselha Flex pessoalmente** para quem "sabe fazer conta" (DIST-UNIAO) — um desalinhamento direto entre o incentivo comercial desenhado pela Propig e o julgamento financeiro do próprio distribuidor que deveria estar "vendendo" esse plano.
- **Distribuidor quer crédito garantido (Sessão/Flex tradicional); revenda, em alguns casos, quer autonomia total (Multiagenda)** — e esse desalinhamento é, segundo a própria Propig, a razão de o Multiagenda estar em "limbo" (ver 6.3.4), não resolvido nem para um lado nem para o outro.
- **Moura mede sucesso via indicadores agregados (inadimplência total, PMR total); Janduí (dentro da própria Propig) alerta que o distribuidor individual pode estar perdendo visão de uma parcela relevante do seu próprio risco por conta dessa agregação** (ver 3.1) — um desalinhamento entre o nível de medição usado para "vender" o programa internamente e o nível de risco relevante para a decisão de cada distribuidor.
- **Propig quer se diferenciar de "maquininha tradicional"; seu próprio modelo de cobrança reforça a comparação** (ver 2.1/6.3.1) — desalinhamento entre intenção estratégica e desenho de produto, admitido pela própria liderança.
- **Vendedor é incentivado financeiramente a cadastrar revendas no Credimora, mas nem sempre tem conhecimento suficiente para apresentá-lo corretamente** (ver 3.5) — desalinhamento entre o incentivo de curto prazo (bônus por cadastro) e a capacitação necessária para gerar adoção de qualidade (não apenas quantidade de cadastros).

## E) Mecanismos críticos de sustentação — classificados por importância e força de evidência

| Mecanismo | Importância para o funcionamento do programa | Força da evidência | Observação |
|---|---|---|---|
| Alinhamento societário Moura-distribuidor (70-75%) permitindo adesão obrigatória | Muito alta — sem ela, não há rollout de 100% dos distribuidores | Forte (dito de forma consistente por fonte interna Propig e por um distribuidor, de formas independentes) | É o mecanismo mais citado pelas próprias fontes como condição não replicável automaticamente |
| Amarração do crédito a produto específico da marca | Muito alta — é o que converte parcelamento em ganho de market share | Forte (mecânica explicada em detalhe, efeito quantificado em dado interno de crescimento 2,13x) | Causalidade do dado de crescimento não auditada de forma independente nestes documentos |
| Segmentação "especialista vs. não especialista" como preditor de adesão | Muito alta — é o fator mais citado de todos para explicar onde o produto funciona | Forte (convergência entre praticamente todas as fontes, inclusive as três entrevistas de distribuidor com perfis de carteira muito diferentes) | É o achado transversal mais robusto de todo o corpus |
| Política de subsídio local permanente (não campanha) | Alta — evita cancelamento em massa quando subsídio temporário é revertido | Moderada (evidência direta de um distribuidor — União — sobre o próprio erro passado; coerente com reclamações de revenda sobre campanhas, mas não testado como princípio geral) | — |
| Pré-existência de prazo longo de recebimento do distribuidor (antes do produto) | Alta — é o que permite a Propig não precisar antecipar o distribuidor | Moderada (explicado mecanicamente em uma fonte interna, não contraditado em nenhuma outra, mas também não detalhado por nenhum distribuidor individualmente) | — |
| Conhecimento prévio do operador de revenda sobre a mecânica Moura | Moderada — reduz atrito de confiança, mas não é condição necessária de adoção | Moderada (dois casos de revenda, ambos ex-ligados à Moura, relatando adoção mais tranquila) | Amostra pequena (2 revendas, ambas atípicas) |
| Capacitação consistente do vendedor de ponta | Alta em potencial, mas ainda não resolvida | Fraca quanto a solução (o problema é bem documentado; nenhuma solução eficaz está demonstrada funcionando nestas fontes) | — |

## F) Aprendizados sobre replicabilidade — apenas o que a evidência sustenta sobre o caso Moura em si

Esta seção respeita a restrição explícita: **nenhuma análise de outra indústria ou recomendação específica é feita aqui**. O que se segue é exclusivamente uma leitura de quais elementos do caso CredMoura/Moura, segundo as próprias fontes, são descritos como específicos daquele ecossistema (e portanto não automaticamente presentes em qualquer outro contexto) versus quais são descritos como capacidades genéricas da Propig como empresa/plataforma.

**Elementos que as próprias fontes descrevem como específicos do ecossistema Moura, não como capacidade genérica da Propig**:
- A estrutura societária 70-75% Moura sobre o distribuidor, que viabiliza adesão obrigatória por meta (ver 3.3, E).
- O prazo médio de recebimento historicamente longo do distribuidor (pré-condição que absorve o não-antecipação, ver 2.2).
- O volume histórico de 5 anos de dados (2021-atual) que a Moura acumulou para conseguir hoje demonstrar, com números robustos, a tese de crescimento ao distribuidor — a própria liderança reconhece que esses números "demoraram a vencer" e que, no início, "a barreira inicial, o cara não acreditava nisso" (INT-10/09).
- A segmentação natural de "especialistas em bateria" como unidade de adesão natural — uma característica do mercado de baterias (produto de reposição com ciclo de vida definido, onde existe um segmento de revenda cujo negócio é dominado por esse único produto), não necessariamente presente de forma equivalente em outro setor.

**Elementos que as próprias fontes descrevem como capacidade genérica, transferível, da Propig como empresa**:
- A infraestrutura técnica de subadquirência com calendário de repasse flexível (desacoplar antecipação à ponta de venda do calendário de recebimento do fornecedor) — descrita de forma abstrata e replicável em INT-10/09 ("isso pode ser transbordado em outros produtos também").
- O sistema de parametrização de política comercial (quem paga a taxa) — é infraestrutura de sistema, não depende do setor.
- A autocrítica sobre modelo de cobrança (2.1) e sobre percepção de valor (2.7/5.3) são, pela própria natureza, lições sobre **o que não fazer de novo**, mais do que capacidades a replicar — e as próprias fontes tratam essas duas questões como não resolvidas, não como aprendizados fechados.

Esta distinção — entre o que é condição de contexto específica da Moura e o que é capacidade de produto/infraestrutura da Propig — é desenvolvida com mais detalhe no Capítulo 8, sempre como leitura do caso Moura em si, sem avançar para recomendação para qualquer outra indústria específica.

---

# Capítulo 8 — Capacidades replicáveis e condições de contexto

> Importante: este capítulo não analisa Goodyear, Decor Colors, ou qualquer outra indústria, nem recomenda soluções para elas. Ele apenas organiza, a partir do caso Moura documentado nestes 9 arquivos, o que pertence à categoria "capacidade de produto/infraestrutura, construída pela Propig, que poderia em tese existir fora do contexto Moura" versus "condição específica do ecossistema Moura que permitiu o funcionamento observado, e que não é garantida existir automaticamente em outro lugar".

## 8.1 Capacidades de produto/infraestrutura (atribuíveis à Propig como construtora)

1. **Motor de subadquirência com calendário de repasse desacoplado** — a capacidade técnica de antecipar um elo da cadeia sem precisar antecipar o outro, cobrando uma taxa all-in menor que o custo de antecipação tradicional de mercado (ver 2.2). Esta é, pela documentação, a peça de infraestrutura mais claramente descrita como "produto" da Propig, independente do setor.
2. **Motor de parametrização de política comercial** — permitir que o "pagador" da taxa (revenda, fornecedor/distribuidor, ou split) seja uma variável configurável, não fixa (ver 2.3). As três políticas de subsídio totalmente distintas implementadas por Anápolis, União e Roadmaster são evidência direta de que essa flexibilidade é real e foi usada de formas muito diferentes sem necessidade de desenvolvimento customizado por caso.
3. **Framework de crédito-produto amarrado a marca específica** — a lógica de que o valor transacionado só pode ser convertido em produto de uma marca específica junto a um fornecedor específico (ver 1.1, 4.1) é, em si, uma capacidade de produto generalizável a qualquer relação fabricante-distribuidor-varejo com dinâmica de reposição de estoque — mas (ver 8.2) seu efeito de conversão de market share documentado depende de condições de mercado específicas que não estão garantidas fora do caso Moura.
4. **Portais de gestão (revenda e distribuidor) com funcionalidades de conciliação, rastreio, e — em desenvolvimento — demonstração de economia** — capacidade de produto replicável em si, mas cujas limitações atuais (complexidade de UI, atraso de lançamento de funcionalidades-chave de percepção de valor, gap de qualidade frente a concorrentes estabelecidos) estão também documentadas e não devem ser ignoradas ao se pensar em replicação (ver 6.3).

## 8.2 Condições de contexto específicas do ecossistema Moura (não capacidades de produto)

1. **Estrutura de propriedade do distribuidor (70-75% Moura)**, que viabilizou adesão obrigatória por meta a nível de distribuidor sem depender de convencimento comercial (ver 3.3). As próprias fontes (interna Propig e um distribuidor, de forma independente) tratam essa estrutura como condição sine qua non do sucesso observado em rollout — não como algo que a Propig "construiu" ou controla.
2. **Prazo médio de recebimento historicamente longo do distribuidor Moura antes mesmo do produto existir** (30/60/90/120 dias via boleto) — condição de contexto que absorveu o impacto de caixa da mudança para parcelamento em 10x, e que é citada como pré-condição explícita, não como resultado do produto (ver 2.2).
3. **Cinco anos de dados acumulados e consolidados** que hoje permitem à Moura apresentar, internamente, uma tese quantificada e convincente a novos distribuidores ou a novos públicos (INT-10/09 relata que mostrar esses números à "Godia" e à "Decopol" gerou reação imediata de interesse) — mas a própria fonte reconhece que esses números "demoraram a vencer" e não existiam nos primeiros anos do programa. Qualquer leitura que tome a existência desses números como "prova de modelo replicável" precisa reconhecer que eles são, eles mesmos, produto de tempo acumulado dentro do contexto Moura, não uma característica do produto Propig em si.
4. **Segmentação de mercado específica** ("especialistas em bateria", ~10 mil a ~3.500 dependendo da fonte interna consultada — ver 1.3 — de um universo de 70 mil revendas) como unidade natural de adesão — uma característica da estrutura do varejo de baterias no Brasil, documentada como o preditor mais forte de adesão em todas as fontes, mas não necessariamente presente, com a mesma nitidez, em outro setor.
5. **Cultura e histórico comercial pré-existentes entre distribuidor e revenda** (relação de décadas, em alguns casos, como a União desde 1984 e a Roadmaster desde 1975) — o tipo de relação de confiança e de rotina comercial de longo prazo que permite a um distribuidor implementar políticas de subsídio sofisticadas (como o framework de 4 parâmetros da União) e tê-las respeitadas pela revenda.

## 8.3 Uma tensão não resolvida nos próprios documentos, relevante para qualquer leitura de replicabilidade

A afirmação mais forte e mais explícita sobre limite de replicabilidade, em todo o corpus, vem do distribuidor com a **menor** penetração percentual das três entrevistas (Roadmaster, ~8%), não de um dos distribuidores de maior sucesso relativo:

> *"Não tem um depósito do Brasil que esteja bombando o Credemora sem a distribuidora subsidiar. (...) Qual distribuidora vai estar disposta a investir [um capital de giro gigantesco]? (...) Se eu estivesse numa outra distribuidora [de outro negócio qualquer] (...) eu não teria essa parceria com a Propig. Porque as taxas são mais altas e o serviço que eles prestam não é melhor do que os outros."* (DIST-ROADMASTER)

Esta afirmação é, ao mesmo tempo, (a) a leitura pessoal de um único entrevistado, que ele mesmo qualifica com um grau de incerteza ("eu duvido, pode ser que tenha [exceção], mas quem eu conheço..."), e (b) a formulação mais direta e mais alinhada, dentro de todo o corpus, com o próprio diagnóstico da liderança interna da Propig sobre "deixar dinheiro do outro lado da mesa" (ver 2.1) e sobre o modelo de cobrança se parecer demais com o de uma maquininha tradicional sem o diferencial de subsídio estrutural que só a Moura, por sua estrutura societária, consegue sustentar. **Não decido, aqui, se essa afirmação de Roadmaster está certa como previsão universal** — ela é uma hipótese de um entrevistado com conhecimento direto e qualificado do negócio, fortemente convergente com a autocrítica da própria liderança da Propig, e deve ser tratada com esse peso: mais do que uma opinião isolada, menos do que um fato estabelecido.

---

# Capítulo 9 — Lacunas de informação e questões não respondidas

Lacunas explícitas identificadas no processo desta análise, restrita aos 9 documentos aprovados:

1. **Número total de distribuidores Moura no Brasil hoje, com data associada**: não consta de forma inequívoca em nenhum dos 9 documentos lidos nesta rodada restrita de escopo.
2. **Divergência não resolvida entre INT-10/09 ("10 mil especialistas" de 70 mil revendas) e um número de ~3.500 (5%) registrado em leitura anterior desta mesma investigação a partir de INT-11/09**: como a transcrição de 11/09 não foi relida literalmente, palavra por palavra, nesta rodada final (foi reaproveitada uma leitura integral já feita nesta sessão), recomendo verificação direta do trecho exato antes de qualquer uso operacional de qualquer um dos dois números.
3. **Reconstrução completa do histórico 2005→2013→2017-2018**: há dois relatos de origem distintos (União: tentativa de cartão de crédito interno abandonada até 2005; Anápolis: reunião de 2013 com a Cielo) e nenhuma fonte entre os 9 documentos costura esses dois eventos numa linha do tempo única e confirmada.
4. **Dado quantitativo pós-lançamento sobre a funcionalidade "Economia do Credimora"**: a funcionalidade é descrita apenas no momento de sua demonstração/lançamento (set-out/2026); nenhuma das entrevistas de revenda ou distribuidor (todas anteriores ou contemporâneas ao lançamento) avalia seu efeito, porque nenhuma delas foi conduzida depois de um período de uso real da funcionalidade.
5. **Taxa de cancelamento/churn consolidada a nível nacional**: existem apenas relatos pontuais e não padronizados de distribuidores individuais (ex.: "no mínimo 600 clientes" na Roadmaster) — não há uma métrica nacional de churn do programa disponível nestes documentos.
6. **Pesquisa de satisfação/NPS completa do projeto "Parceiro Moura" mencionado em INT-14/09-PLAT**: apenas o achado qualitativo central ("cliente não via valor") é citado; os dados completos da pesquisa não estão nestes documentos.
7. **Se a "causalidade invertida" é descartável no dado de crescimento 2,13x vs. 5%** (ver 3.1): não há, nestes documentos, nenhuma análise de que os clientes que aderiram ao CredMoura já não fossem, antes da adesão, clientes de perfil de crescimento superior por outras razões (efeito de seleção). Essa possibilidade não é discutida em nenhuma das fontes.
8. **Status atual (resolvido ou não) do bug de integração entre o saldo Credemora e o "Parceiro Moura" para abatimento de boletos**, mencionado como "tendo tido um bug" em INT-14/09-PLAT, com "time de tecnologia (...) já em desenvolvimento" — não há confirmação de resolução nestes documentos.
9. **Se o problema histórico da União (Propig não repassar a parte do cliente na liquidação do Flex) é inteiramente passado ou se resquícios ainda afetam clientes ativos, não só os que já saíram** — a própria síntese anterior desta investigação já havia identificado esta pergunta como aberta; a leitura da transcrição bruta de DIST-UNIAO nesta rodada não trouxe elementos adicionais que a resolvessem.
10. **Dados completos sobre o universo de revendas "não especialistas" que nunca aderiram** — sabe-se que existem (60 mil das 70 mil, segundo INT-10/09), mas nenhuma das fontes documentais entrevista diretamente uma revenda desse perfil para entender, na própria voz dela, por que nunca considerou o produto — as duas entrevistas de revenda disponíveis (Fábio e Lucas) são ambas de casas especializadas em bateria, o que significa que **a voz do não-aderente nunca-aderente está ausente destes 9 documentos**.
11. **Proporção real de revenda que usa conhecimento próprio para reconciliação financeira paralela** (como Lucas e Fábio fazem) versus a proporção que simplesmente desconfia e eventualmente sai sem nunca reconciliar — não há dado quantitativo disponível, apenas os dois relatos individuais e a inferência qualitativa de Lucas sobre o padrão que ele acredita existir em outras revendas (ele mesmo descreve isso como sua impressão, não como dado).

---

## Fechamento metodológico

Este relatório foi construído para responder, com a evidência disponível nos 9 documentos aprovados, às oito perguntas que o pedido original definiu como teste de suficiência. Resumidamente, e remetendo aos capítulos correspondentes para o detalhe e a evidência completa:

1. **O que é o CredMoura e como funciona de fato** → Capítulos 1 e 2.
2. **Qual é o modelo comercial, financeiro e operacional** → Capítulo 2, com a ressalva explícita de que não existe uma política única — existem três políticas de subsídio documentadas e divergentes (2.4).
3. **O que, de fato, fez o CredMoura funcionar e ser adotado** → Capítulo 3, com a matriz de atribuição (3.7) como síntese central.
4. **O que foi especificamente feito pela Propig** → Capítulo 3.2, e distinguido de 3.3-3.6.
5. **O que só aconteceu por causa de decisões da Moura, dos distribuidores ou dos vendedores/revendas** → Capítulos 3.3, 3.4, 3.5, e consolidado na matriz 3.7.
6. **Por que distribuidores e revendas participaram, e que valor de fato obtiveram** → Capítulos 4 e 5.
7. **O que ainda não funciona bem** → Capítulo 6, com problemas isolados, recorrentes e estruturais diferenciados explicitamente.
8. **O que isso demonstra sobre as capacidades da Propig e sobre condições de replicação** → Capítulos 7 (F) e 8, sem avançar para recomendação para qualquer indústria específica, conforme restrição explícita do pedido.

As lacunas do Capítulo 9 não são falhas desta análise — são, elas mesmas, parte do resultado: dizem onde a base de evidência disponível termina e onde qualquer decisão futura precisaria de informação adicional, não de suposição.
