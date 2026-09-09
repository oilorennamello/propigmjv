# Roteiro — sessão de trabalho: Propig explica o Credmoura

> Preparado a partir de (1) `kickoff/repasse-interno-mjv_transcricao.txt`,
> (2) `kickoff/kickoff-oficial-cliente_transcricao.txt`, e (3) os dois
> materiais oficiais enviados pelo cliente em
> `produto-credmoura/apresentacao-propig-2026-industria.pdf` e
> `produto-credmoura/credmoura-pesquisa-nps-jun2026.pdf`.
>
> Ainda não há, no repositório, um documento de proposta comercial do
> projeto (`proposta-comercial/` está vazia) — este roteiro se baseia
> apenas nos três materiais acima.

## Como usar

Os materiais que a Propig já mandou respondem boa parte do "o que é o
produto". Não vale a pena gastar tempo da sessão perguntando o que já está
nos slides — a seção **"O que já sabemos"** existe justamente para revisar
isso rápido no início e liberar tempo para o que os slides **não**
respondem: como o modelo se sustenta economicamente, quem faz o quê no
dia a dia, e — o mais importante para o projeto — o que a Propig já sabe
(ou hipotetiza) sobre Goodyear e Decor Colors, os dois mercados-piloto.

Cada bloco de pergunta traz entre parênteses a razão de perguntar — a
lacuna ou a inconsistência que motivou a pergunta.

---

## O que já sabemos (revisar em ~5 min, não perguntar de novo)

- **O que é a Propig**: "plataforma de soluções financeiras inovadoras que
  transforma a cadeia de valor do negócio, trazendo impactos positivos na
  gestão dos estabelecimentos comerciais e benefícios exclusivos para
  varejistas e consumidores." Sede em Recife (PE), presença nacional.
- **Escala atual**: +10.000 clientes · +170.000 transações/mês ·
  +R$1,35 bi em transações/ano · CAGR de 36%/ano desde 2021.
- **Infraestrutura**: certificada GPTW, auditada anualmente por uma Big
  Four, certificada PCI DSS, infraestrutura 100% em nuvem (AWS).
- **O que é o Credmoura**: "Programa de Mercado que aumenta as vendas
  através do parcelamento para o consumidor final, em até 10x sem juros,
  **sem impacto no fluxo de caixa da Revenda**." Benefícios anunciados:
  aumento das vendas, aumento da margem de lucro, melhores taxas do
  mercado.
- **Plataforma de atendimento**: Portal do Distribuidor, Portal do
  Cliente/App (CREDMOURA), integrações API, integrações ERP em D+1, time
  dedicado de atendimento, WhatsApp.
- **Logística e hardware**: Smart POS próprio (Wi-Fi, conexão inteligente,
  impressão rápida), chips, infraestrutura de software — tudo licenciado
  pela Propig.
- **Ecossistema Credmoura (diagrama oficial)**: a Propig se posiciona
  como o centro que "disponibiliza sistema integrado, fortalecendo a
  cadeia de valor de todo o ecossistema", conectando três atores:

  | Ator | Ganhos, segundo a Propig |
  |---|---|
  | **Consumidor final** | Parcelamento para compra não planejada; liberdade de escolher a marca de preferência |
  | **Revendedor** | Parcelamento maior sem impacto no caixa; aumento das vendas (3x); redução de custos financeiros; maior limite de crédito no fornecedor |
  | **Indústria / Distribuição** | Redução da inadimplência; ganho de market share; facilidade de crédito para revendedores; pulverização do mercado; alta fidelização |

  → Note que o diagrama oficial trata **"Indústria" e "Distribuição" como
  um único ator**, diferente da cadeia de 4 elos (fábrica → distribuidor →
  revenda → consumidor) que apareceu no kickoff e na pesquisa de mercado.
  Isso é uma pergunta do Bloco 3.

- **Resultados comprovados (gráficos do deck)**:
  - Sell-in indexado (2021=100): **com** Credmoura sobe a 213 em 2026;
    **sem** Credmoura fica estável em ~105 — ou seja, o Credmoura é
    apresentado como responsável por dobrar o crescimento de vendas.
  - Inadimplência de PDV: cai de 5,8% (2021) para 3,3% (2025) — melhoria
    de 43% em 4 anos.
  - PMR dos distribuidores: oscila entre 78 e 93 dias, sem tendência de
    piora — "baixo impacto do PMR da distribuição".
  - Churn das revendas: 0,3%.
- **NPS do programa**: 81 pontos ("zona de excelência"), subindo de 68
  (dez/22) para 81 (jun/26), com queda pontual a 61 em jun/23. Perfil:
  85% promotores, 11% neutros, 4% detratores.
  - **O que mais agrada** (promotores): parcelamento (34%), taxas (20%),
    modelo de recebimento (19%).
  - **O que mais incomoda** (detratores): taxas (47%), modelo de
    recebimento (18%), app/portal do cliente (18%), maquininha (12%).
  - **Pedido de melhoria nº1 dos detratores**: redução das taxas
    cobradas (44%).

---

## Objetivos da sessão

1. Entender a mecânica econômica do Credmoura no nível que os slides não
   mostram (quem paga o quê, como a Propig ganha dinheiro nisso).
2. Mapear com precisão quem faz o quê — dentro da Propig e nas pontas da
   cadeia (Moura, distribuidor, revenda).
3. Extrair o que a Propig **já sabe ou já hipotetiza** sobre a estrutura
   de mercado da Goodyear e da Decor Colors, antes das entrevistas de
   campo de 21–25/09.

---

## Bloco 1 — Abertura (5 min)

Script sugerido: "Vocês já nos mandaram um material muito completo sobre
o Credmoura e os números da Moura — já revisamos e queremos aproveitar o
tempo de hoje para ir num nível mais profundo: como o modelo se sustenta
financeiramente, quem faz o quê no dia a dia, e principalmente entender o
que vocês já sabem sobre Goodyear e Decor Colors, já que é para lá que a
gente vai em duas semanas."

---

## Bloco 2 — A mecânica econômica do Credmoura

*(o deck mostra o benefício, mas não mostra como ele é financiado — este
bloco existe para preencher essa lacuna, central para o desafio de
posicionamento citado no kickoff: "o projeto gera muito mais valor para a
Moura do que para a Propig")*

- O slide diz que o parcelamento em até 10x sem juros acontece **"sem
  impacto no fluxo de caixa da revenda"**. Quem paga, então, o custo
  financeiro desse parcelamento — a Moura (indústria), a Propig, ou é
  dividido? Existe uma regra fixa ou isso varia por campanha?
- Qual é hoje a fonte de receita e a margem da Propig por transação
  Credmoura? É MDR sobre a maquininha, é rebate da Moura, é spread do
  crédito, ou uma combinação?
- O NPS mostra que **taxas** é o principal motivo de detração (47%) e o
  pedido nº1 de melhoria (44%). Como a Propig hoje decide o quanto pode
  reduzir taxa sem inviabilizar a própria margem?
- O gráfico de Sell-in mostra que o efeito do Credmoura é visível desde
  2022 e acelera a partir de 2023/2024. O que mudou no produto ou na
  operação nesse período que explica a virada de inclinação da curva?
- "Acesso a maior limite de crédito no fornecedor" (benefício citado para
  o revendedor) — esse limite é calculado com base em quê (histórico de
  vendas, tempo de relacionamento, score de crédito)? Quem decide?
- O PMR do distribuidor variou de 78 para 93 dias entre 2021 e 2023 e
  depois caiu para 85–87. O que causou a alta e o que causou a queda
  depois?

---

## Bloco 3 — Atores e responsabilidades

*(reconciliar o diagrama oficial — que trata "Indústria/Distribuição" como
um ator só — com a cadeia de 4 elos que apareceu no kickoff e na pesquisa
pública de mercado)*

- No diagrama do "Ecossistema Credmoura", Indústria e Distribuição
  aparecem como um único bloco. Na prática, o distribuidor regional e a
  fábrica (Moura) têm o mesmo tipo de relação com a Propig, ou existem
  papéis, contratos e riscos diferentes entre eles?
- Quem, dentro da Propig, é responsável por cada parte da operação que
  aparece no slide "Atendimento e Plataforma de Gestão" — Portal do
  Distribuidor, Portal do Cliente/App, integrações API, gestão de
  chamados? São times diferentes ou a mesma equipe cobre tudo?
- A pesquisa de mercado que fizemos aponta uma joint venture entre a
  fintech **Lucree** e o Grupo Moura por trás da criação da Propig em
  2019 — mas o material institucional de vocês não menciona a Lucree em
  nenhum momento. Essa relação ainda existe hoje? Vale a pena entendermos
  isso para não repetir uma informação desatualizada em qualquer material
  nosso.
- Quem, na Moura, aprova/patrocina o Credmoura hoje — é a mesma
  governança de quando o produto foi criado, ou já mudou de mãos?
- Como funciona a decisão de "quem entra e quem não entra" no programa:
  todo PDV da rede Moura pode aderir, ou existe algum critério de seleção
  ou aprovação de crédito antes de instalar a maquininha?

---

## Bloco 4 — Números que sustentam o case (reconciliar com o que já ouvimos)

*(alguns números do deck não batem exatamente com o que foi dito no
kickoff — vale reconciliar em voz alta para não carregar um número errado
para a proposta)*

| Métrica | Kickoff (09/09) disse | Deck oficial (2026) diz | Pergunta |
|---|---|---|---|
| TPV/ano | ~R$1,3 bi | +R$1,35 bi | Bate certo — só confirmar se "transações/ano" é TPV ou receita. |
| Crescimento | ~30%/ano | CAGR 36%/ano desde 2021 | Qual é o número mais atual/correto para usarmos? |
| Base de clientes | "50 mil revendedores" (fonte pública/pesquisa) | "+10.000 clientes" no deck | Essa diferença é penetração (10 mil ativos de um universo de 50 mil PDVs) ou são bases diferentes (ex.: só quem usa Credmoura vs. toda a rede Moura)? Esse número de penetração é importante para estimar o ritmo de adoção em Goodyear/Decor Colors. |
| Inadimplência | citada como problema histórico do setor | cai de 5,8% para 3,3% (2021→2025) | Essa métrica é medida por quem — Propig, Moura, ou terceiro? Existe algo parecido hoje para os PDVs fora do Credmoura, para servir de baseline de comparação? |
| Churn | não mencionado | 0,3% | Isso é churn de revendas ativas no programa, ou de PDVs cadastrados na Moura em geral? |

---

## Bloco 5 — O que a Propig já sabe sobre Goodyear e Decor Colors

*(este é o bloco mais importante da sessão — nenhum dos dois materiais
enviados fala de Goodyear ou Decor Colors; tudo aqui é para extrair o
conhecimento que só existe na cabeça do time Propig/Moura antes das
entrevistas de campo de 21–25/09)*

### Sobre a estrutura de mercado

- No kickoff, vocês descreveram a Goodyear como tendo só a camada
  "distribuidor", sem uma relação formal com revendas — é isso que
  esperam confirmar nas entrevistas, ou já têm mais clareza hoje sobre se
  existe uma camada de sub-revenda?
- Quem, hoje, é o contato "dono" da relação comercial Propig/Moura com a
  Goodyear e com a Decor Colors — é uma relação nova, ou já existe algum
  histórico comercial entre os grupos?
- A Decor Colors opera como rede de franquia (temos essa hipótese, a
  confirmar em campo) ou como distribuidora tradicional multimarcas?
  Vocês já sabem disso, ou essa é justamente uma das perguntas que
  querem responder nas visitas?
- Quem decide, hoje, a compra de pneu e de tinta na ponta — o próprio
  consumidor, o dono da revenda, ou (no caso de tinta) o pintor
  profissional que compra em nome do cliente? Isso muda quem seria o
  "tomador" natural de um crédito tipo Credmoura.

### Sobre a transferência do modelo

- O parcelamento padrão do Credmoura é em até 10x sem juros. Pneu e tinta
  têm ticket médio e frequência de compra muito diferentes de bateria —
  esse "10x" é um número que pretendem manter, ou já sabem que vai
  precisar ser recalibrado por indústria?
- O benefício "sem impacto no fluxo de caixa da revenda" depende de
  alguém (hoje, a Moura) absorver o custo financeiro. A Goodyear e a
  Decor Colors já sinalizaram disposição a fazer o mesmo tipo de aporte,
  ou isso ainda é uma incógnita a validar nas entrevistas?
- Em qual fase de maturidade (das três descritas no kickoff — redução de
  inadimplência, aceleração de vendas, fidelização/gestão financeira) a
  Propig pretende entrar em Goodyear e Decor Colors: começar do zero ou
  já oferecer o produto na maturidade que a Moura tem hoje?
- Quais métricas de sucesso (das que vimos no Bloco 4 — sell-in,
  inadimplência, PMR, churn, NPS) a Propig pretende usar para avaliar o
  piloto em cada uma das duas indústrias? Já existe uma meta ou um prazo
  definido para essa avaliação?

### Sobre o que já foi levantado nas visitas agendadas

- Do distribuidor de pneus em São José dos Campos (citado no kickoff): o
  que já foi levantado sobre o volume de vendas dele, se ele representa
  só a Goodyear ou também outras marcas, e se ele já demonstrou interesse
  real no produto?
- Da Decor Colors: os contatos de revenda já confirmados até agora — o
  que esses primeiros contatos já revelaram sobre como a empresa opera
  (loja própria, franquia, distribuidor)?
- Existe algum risco ou objeção que a Goodyear ou a Decor Colors já
  colocaram na mesa, mesmo informalmente, sobre entrar num programa como
  o Credmoura?

---

## Bloco 6 — Encerramento e próximos passos (5 min)

- Recapitular o que ficou pendente de resposta e quem vai trazer (ex.:
  detalhamento do modelo de custo/receita, definição de "clientes" no
  número de +10.000, contato mais atualizado sobre Lucree).
- Confirmar se algum material adicional (ex.: contrato-modelo com
  distribuidor, roteiro de entrevista já preparado pelo Rui) pode ser
  compartilhado antes das visitas de 21–25/09.
- Alinhar quem, do lado Propig/Moura, vai acompanhar as entrevistas em
  Goodyear e Decor Colors, e se algum desses aprendizados deste bloco 5
  muda o roteiro de entrevista já planejado.
