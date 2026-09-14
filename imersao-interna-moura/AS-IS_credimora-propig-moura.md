# AS IS — Credimora (Propig + Moura)

> Síntese elaborada a partir das transcrições da imersão interna: repasse
> interno, kickoff oficial, Kickoff Parte II / imersão no produto, entrevista
> com Rui (Moura) e demonstração da Plataforma (portais).

---

## 1. Como o modelo foi pensado e implementado

- O **Credimora** nasceu dentro da Moura por volta de **2018/2019** como
  ferramenta para **reduzir a inadimplência** dos revendedores. Em 2020,
  quando Rui entrou na Moura, o TPV (volume transacionado) era de ~R$100 mil
  reais/mês; hoje gira em torno de **R$1,3–1,4 bilhão/ano**, com CAGR de
  ~**36% ao ano** desde 2021.
- A **Propig** é a fintech operadora, hoje **100% do grupo Moura** (no
  passado era uma sociedade com outra empresa/fintech).
- O produto evoluiu em **três fases de maturidade**, sentidas de forma
  desigual entre os distribuidores:
  1. **Redução de inadimplência** — "coloco a maquininha nos clientes
     problemáticos".
  2. **Aceleração de vendas** — o parcelamento em 10x faz o consumidor
     comprar a marca que realmente queria, não a mais barata.
  3. **Fidelização / ferramenta de gestão financeira** — plano Flex, em que
     parte do valor cai em conta e vira "insubstituível" no dia a dia da
     revenda.
- **A adoção não foi espontânea — foi empurrada pela indústria.** A Moura
  colocou **metas de adesão e de volume transacionado no Credimora** para os
  distribuidores (não só metas de venda de bateria), porque muitos não
  enxergavam valor de imediato. Como a Moura detém 70–75% do capital de cada
  distribuidor, conseguiu tornar a adesão **obrigatória** no nível do
  distribuidor — mas não da revenda, onde a adoção seguiu sendo orgânica.
- **Evolução dos planos:**
  - **Sessão** (original): 100% do valor transacionado vira crédito para
    comprar produto Moura — sem liquidez em conta.
  - **Flex** (criado ~2 anos depois): parte do valor (30/40/50/60/70/80%)
    cai direto na conta bancária da revenda; o resto vira crédito-produto.
    Nasceu porque revendas reclamavam que "o dinheiro fica preso na Moura".
  - **Multiagenda** (mais recente, ainda em rollout/ajuste): a revenda
    escolhe *na hora da venda*, via botão na maquininha ("Moura" ou
    "Loja"), o destino do valor — pensado para revendas multimarcas.
- Hoje ~**42–50% do TPV** já está em Flex. Rui é categórico: **"se o
  Credimora nascesse hoje, nasceria só com o plano Flex."**
- Um **novo portal** (lançamento previsto para final de outubro/2026) está
  sendo criado para atacar um achado de pesquisa (feita em parceria com a
  Moura): **clientes não enxergavam valor no Credimora**, porque comparavam
  taxa nominal com o mercado. A resposta é uma página de **"Economia"**,
  mostrando quanto a revenda economizou frente a uma cesta de taxas de
  mercado (Stone, PagBank, Cielo etc.).

---

## 2. Como funciona hoje

**Cadeia:** Indústria (Moura) → Distribuidor (pessoa jurídica regional, ~70–75%
capital Moura + sócio local) → Revenda (PDV) → Consumidor final.

- A revenda recebe uma maquininha Propig; o consumidor passa o cartão de
  crédito e parcela em até **10x, sem juros aparentes ao consumidor, sem
  valor mínimo e sem fidelização** (o revendedor pode passar produto de
  qualquer marca na máquina).
- **A Propig não antecipa dinheiro ao distribuidor** — só antecipa o
  *crédito/direito de compra* para a revenda. O distribuidor recebe
  conforme as parcelas do consumidor realmente vencem. Isso é o que
  permite à Propig **não cobrar o custo de antecipação** que encarece
  outras adquirentes (10–20% a.a.) — sendo o principal diferencial de custo
  do modelo.
- **Delay de integração:** a transação leva **D+1 a D+2** para virar saldo
  Credemora (integração automática via API entre sistemas Propig↔Moura).
  Falhas pontuais de integração geram um saldo temporário de "créditos a
  liberar".
- **Portais/App:**
  - *Portal do cliente (revenda):* saldo Credemora, recebimentos, vendas,
    boletos Moura, cobrança de aluguel da máquina, extrato/análise de
    crédito. Em breve, página de "Economia".
  - *Portal do distribuidor:* pagamentos recebidos, transações das
    revendas, chamados (via Pipefy/CRM), rastreio de entrega de máquinas,
    indicadores de nível de serviço (SLA/NPS), gestão da base de clientes
    ativos/inativos.
  - **43% dos usuários** já preferem o **app** (mais simples que o portal
    web) — achado usado para justificar simplificação da experiência.

---

## 3. Atores envolvidos e seus papéis

| Ator | Papel |
|---|---|
| **Indústria (Moura)** | Dona da marca; define metas/incentivos para adesão dos distribuidores; parceira estratégica e financeira; no caso da Moura, também é sócia majoritária da Propig e dos distribuidores. |
| **Propig** | Subadquirente/fintech operadora: conecta-se a um adquirente real (ex. Cielo) para processar o cartão, cobra a taxa, faz a conciliação, opera portal e logística de máquinas. Fica com um spread pequeno sobre a transação. |
| **Distribuidor** | PJ regional, "patrocinador" do programa — frequentemente subsidia taxa e/ou aluguel da revenda; concede o crédito-produto; gerencia sua carteira de revendas; ganha com redução de inadimplência e aumento de sell-in. |
| **Revenda/PDV** | Vende ao consumidor final via a maquininha; recebe crédito (Sessão) ou parte em dinheiro (Flex) para repor estoque; é quem mais sente a dor de entender taxas e gerir saldo. |
| **Vendedor do distribuidor** | Agente de campo que apresenta, treina e dá suporte à revenda — ponto crítico: se não domina o "linguajar de adquirência", a adoção falha. |
| **Consumidor final** | Parcela a compra em até 10x e tem acesso à marca que prefere, mesmo sem capital imediato. |
| **Time interno Propig** (produto, marketing, CX, comercial, tecnologia) | Mantém e evolui produto, portal e materiais de treinamento/venda. |

---

## 4. Modelo e fluxo financeiro

- **Cobrança:** taxa única "tudo incluso" (ex.: 4,89% em até 12x), já
  embutindo MDR + custo de antecipação parcial. O distribuidor pode, por
  política própria, subsidiar parte/total da taxa e/ou do aluguel da
  maquininha — **não existe padrão, cada distribuidor decide sua própria
  estratégia comercial**.
- **Fluxo:** revenda transaciona → Propig processa via adquirente real →
  Propig cobra a taxa da revenda → repassa o valor líquido ao distribuidor
  em forma de crédito-produto (Sessão) e/ou deposita parte em conta da
  revenda (Flex) → distribuidor recebe de forma **parcelada** (não
  antecipada) conforme os vencimentos do consumidor.
- **Receita da Propig:** concentrada quase inteiramente numa **única linha**
  — a taxa transacional — com uma receita secundária pequena de aluguel de
  máquina. O próprio time reconhece isso como uma fragilidade estrutural.
- **Desbalanceamento de valor, reconhecido pelo próprio Tasso (diretor):**
  > *"a gente termina deixando dinheiro muito mais do outro lado da mesa
  > [...] o nosso projeto gera muito mais valor para a Moura do que para a
  > Propig."*
  A indústria captura a maior parte do ganho (menos inadimplência, mais
  venda, fidelização), mas a Propig não consegue cobrar por esse valor
  gerado sem "assustar" o cliente comparando com taxas de mercado.
- **Autocrítica de modelo de cobrança:**
  > *"Eu errei no modelo de cobrança. Eu cobro igual a maquininha [...] cada
  > vez que eu me aproximo desse modelo de cobrança de maquininha, mais eu
  > vou ser comparado à maquininha."*
  Esse é um dos pontos centrais que o projeto precisa resolver para as
  novas indústrias.

---

## 5. Proposta de valor (por elo da cadeia)

- **Consumidor final:** parcela a compra e passa a comparar a *parcela que
  cabe no orçamento* em vez do preço à vista — compra a marca que
  realmente prefere.
- **Revenda:** parcelamento de até 10x **sem impacto no próprio fluxo de
  caixa** (recebe o crédito quase imediatamente, sem esperar as parcelas do
  consumidor); taxa **"democrática"** — mesma taxa para o pequeno e o
  grande revendedor (diferente de negociações bilaterais tradicionais); no
  Flex, ganho adicional de gestão financeira via dinheiro em conta.
- **Distribuidor:** redução de inadimplência (a transação em cartão de
  crédito zera o risco); aumento de vendas e fidelização de market share
  (o crédito só compra produto da própria marca). Dados que a Moura usa
  para convencer novos parceiros:
  - Clientes Credimora **cresceram 2,13x em vendas de bateria desde 2021**,
    contra apenas **+5% dos clientes fora do programa**.
  - Inadimplência da base Moura caiu **quase pela metade**; no Credimora
    especificamente, é praticamente zero.
  - Impacto no PMR (prazo médio de recebimento) foi pequeno: foi de **78
    para 87 dias**, apesar do salto para parcelamento em 10x.
- **Indústria:** sell-out consolidado, fidelização de marca, redução de
  inadimplência sistêmica na cadeia.
- **Mensagem central que a Propig quer transmitir:**
  > *"Não somos uma empresa de maquininha, a maquininha é só o meio."*
  O grande desafio declarado do projeto é resumir 20 minutos de explicação
  em um pitch de **~30 segundos**, sem cair na comparação por taxa/MDR.

---

## 6. Desafios e barreiras

- **Comparação com "mais uma maquininha":** o cliente compara a taxa
  nominal (ex.: 2,99% Cielo) sem considerar o custo embutido de
  antecipação em outras adquirentes (10–20% a.a.) — mercado de taxas é
  descrito como uma "caixa preta" que gera desconfiança generalizada.
- **Complexidade do produto:** múltiplos planos (Sessão / Flex 30–80 /
  Multiagenda), dois portais, nomenclatura confusa ("lado Moura" x "lado
  Loja"), dificuldade até do próprio time interno em explicar.
- **Delay de integração (D+1/D+2):** gera desconfiança/"cadê meu dinheiro"
  na ponta, mesmo sem complexidade operacional real por trás.
- **Capacitação do vendedor de campo:** é especialista em bateria, não em
  produtos financeiros — barreira relevante e recorrente na adoção.
- **Resistência inicial do distribuidor:** receio de aumento do PMR e
  impacto no caixa — só foi vencida ao longo de anos, com dados.
- **Saldo "preso" no plano Sessão:** sem liquidez em conta, problemático
  para revendas pequenas que precisam de capital de giro — motivou a
  criação do Flex.
- **Dependência da saúde financeira da revenda:** revendas endividadas
  preferem recebimento 100% em conta, mesmo pagando taxa maior em outra
  maquininha, porque não podem prescindir de liquidez imediata.
- **Concentração de receita numa única linha** + modelo de cobrança que
  "imita" adquirência tradicional — reforça a comparação indesejada.
- **Churn concentrado em revendas não especializadas** (bateria não é o
  core business) — praticamente 100% do churn está nesse perfil.
- **Falha em cascata de comunicação:** distribuidor nem sempre consegue
  "traduzir" o valor para seu próprio vendedor/revenda.
- **Falta de padronização de entendimento:** de 10 revendas, ~7 entendem o
  valor bem, ~3 não enxergam valor mesmo com números de economia
  apresentados.
- **Multiagenda ainda não resolvido:** gerou receio nos distribuidores
  (perdem garantia de que o crédito vira produto), e confusão operacional
  nas revendas (erro ao escolher o botão errado na maquininha).

---

## 7. Gaps em aberto a levar para a imersão com revendas e distribuidores Moura

Tudo abaixo é conhecido hoje **só pela ótica interna da Propig/Moura** — a
imersão com quem de fato usa a solução (revendas e distribuidores) precisa
validar, contestar ou aprofundar cada ponto, para então alimentar com mais
segurança as investigações com Goodyear e Decor Colors.

1. **Causas reais de "amor" e "ódio" (NPS)** — o time interno tem hipóteses
   sobre promotores/detratores, mas não a voz direta do usuário: por que
   uns veem valor e outros não, nos mesmos atributos (taxa, liquidez,
   complexidade)?
2. **Efeito real da percepção de taxa** — confirmar se a comparação
   "taxa nominal vs. mercado" é de fato a principal barreira, e testar a
   reação a um comparativo tipo a futura página "Economia".
3. **Uso real da "Máquina Livre" do distribuidor** — o próprio Rui não
   tinha certeza se os 3 sócios entrevistados a usam e para quê; pergunta
   pendente de campo.
4. **O que realmente funciona (ou não) na abordagem do vendedor de campo**
   — quais argumentos convertem e quais afastam a revenda, na prática.
5. **Peso real da "complexidade operacional"** — quanto pesa, de fato, ter
   mais um terminal/EC para gerir frente ao ganho percebido.
6. **Lógica real de escolha entre Sessão, Flex e Multiagenda** — o que
   pesa na decisão de revendas pequenas vs. grandes.
7. **Por que revendas com Multiagenda habilitado usam só o lado "Moura"**
   — o próprio time Propig ainda não sabe a resposta e planeja entrevistar
   essas revendas.
8. **Impacto real do delay de integração (D+1/D+2)** no dia a dia e na
   confiança da revenda.
9. **Lógica de decisão do distribuidor como "patrocinador"** — cada um
   subsidia taxa/aluguel do seu próprio jeito; entender os critérios reais
   por trás dessa decisão.
10. **Validação da tese de "ferramenta democrática"** — se a mesma taxa
    para pequeno e grande é percebida como vantagem por todos, ou se
    revendas grandes se sentem prejudicadas (há relato de um grande
    cliente que "odeia" a Propig por ter perdido diferencial competitivo).
11. **Perfil das revendas que não entendem o produto** (as ~3 em 10) —
    características em comum, para desenhar uma comunicação melhor desde
    o dia 1 com Goodyear/Decor.
12. **Quantificação de churn e seus gatilhos** — hoje só se sabe que está
    concentrado em revendas não especializadas; falta detalhar o padrão.

### Por que isso importa para Goodyear e Decor Colors

Os dois novos parceiros têm estruturas de cadeia **diferentes** da Moura
(Goodyear: relação inicial só indústria↔distribuidor, sem revenda associada
diretamente; Decor Colors: modelo de franquia). Isso significa que conceitos
como "distribuidor patrocinador", delay de integração, Sessão/Flex/Multiagenda
e a própria régua de comunicação **precisam ser primeiro bem entendidos e
validados no modelo Moura** (que já opera há anos e tem dado/histórico) antes
de serem adaptados e testados nas entrevistas com as revendas e distribuidores
de Goodyear e Decor — para não repetir, desde o início, as mesmas barreiras de
comunicação e complexidade que a Moura levou anos para resolver.
