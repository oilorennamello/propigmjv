# Análise Transversal — Ecossistema Goodyear e Oportunidades para a Propig

> Baseado nas 5 entrevistas da imersão externa Goodyear (ver transcrições
> completas nesta pasta):
> - **Lubpar** (Barra Funda/SP) — distribuidor puro-B2B de pneus Goodyear
>   e lubrificantes Shell/Raízen. 115 min.
> - **Peregrina** (Vila Formosa, SP capital) — revenda oficial monomarca,
>   6 lojas. 53 min.
> - **Menezes Pneus** (São José dos Campos) — revenda oficial, 4 lojas.
>   65 min.
> - **Encruzilhada** (Recife) — revenda oficial, 5 lojas, entrevistado
>   Lucas. 63 min.
> - **JF** (Santo André/ABC) — revenda oficial, 5 lojas. 83 min.
>
> Convenção usada neste documento: **Evidência** = relatado ou mostrado
> explicitamente na entrevista. **Interpretação** = conclusão construída
> cruzando evidências. **Hipótese** = plausível, mas não validado —
> precisa de investigação adicional. Toda afirmação que não seja uma
> citação direta é rotulada com um destes três níveis.

---

## 1. Síntese executiva

**Evidência central**: as 5 entrevistas revelam não um ecossistema
homogêneo, mas **dois modelos de negócio Goodyear estruturalmente
distintos** operando em paralelo, com muito pouca sobreposição entre
eles — (a) o distribuidor B2B puro (Lubpar), que nunca toca o consumidor
final e carrega 100% do risco de crédito de sua carteira de revendas; e
(b) a revenda oficial monomarca (as 4 outras entrevistas), que compra
direto da fábrica, vende quase exclusivamente ao consumidor final (85%
a 98% dos casos), e só residualmente atende B2B. **Interpretação**: isso
significa que qualquer proposta de valor única para "o canal Goodyear"
provavelmente vai falhar, porque as dores financeiras desses dois grupos
são de natureza diferente — o distribuidor sofre com risco de crédito
concedido a terceiros; a revenda sofre com o custo de bancar
parcelamento ao consumidor final.

Dentro do grupo de revendas oficiais — que é onde está a maior parte da
evidência coletada — encontramos, ainda assim, uma **heterogeneidade de
sofisticação financeira e de abertura ao conceito de crédito estruturado
muito maior do que o esperado**. De um lado, Peregrina resiste à ideia de
antecipação por princípio ("somos tradicionais") mesmo pedindo
ativamente prazo maior da fábrica. Do outro, JF Santo André e Menezes
Pneus fazem gestão financeira sofisticada (cálculo de taxa efetiva,
antecipação automática, DDA bancário) e cocriam ativamente variações do
conceito de crédito estruturado, chegando a propor eles mesmos uma taxa
fixa independente do número de parcelas como argumento de venda.
Encruzilhada fica no meio — curioso, mas com o pai (sócio fundador)
explicitamente cético sobre a necessidade da ferramenta.

O problema mais estruturalmente compartilhado por **todas** as 5
entrevistas, sem exceção, não é de crédito — é **pressão de margem e
volume causada pelo pneu importado/chinês**, hoje entre 40% e 60% do
mercado nacional segundo os relatos, corroendo tanto o preço quanto a
margem de forma que nenhuma solução financeira resolve sozinha
(**hipótese**: pode ser um problema fora do escopo de qualquer fintech,
mas que precisa ser reconhecido no discurso para não soar descolado da
realidade do setor).

O segundo problema mais compartilhado — e o mais diretamente conectado à
lógica de crédito/pagamento — é o **descasamento estrutural entre o
prazo que a Goodyear concede à revenda (7 a 60 dias) e o prazo que a
revenda concede ao consumidor final (6 a 12 parcelas, ou seja, 6 a 12
meses)**. Esse desencaixe é citado, com palavras diferentes, por Lubpar,
Peregrina, Menezes e JF — é a evidência mais forte e mais recorrente de
toda a pesquisa e é estruturalmente equivalente ao problema que o
Credimora resolve para a Moura.

Onde o modelo Credimora **não** responde diretamente: (1) na revenda que
já não sente necessidade de liquidez e prefere fluxo de caixa
conservador (Peregrina, e parcialmente o pai de Lucas em Encruzilhada);
(2) no distribuidor puro-B2B (Lubpar), cuja dor não é "vender mais
parcelado ao consumidor" — ele não vende ao consumidor — mas sim
"conseguir lastrear crédito concedido à sua própria carteira de
revendas", um problema de estrutura de capital, não de parcelamento; (3)
na pressão de importados, que é um problema de preço/origem de produto,
não de forma de pagamento.

Oportunidades relevantes que aparecem fora do core financeiro da Propig:
tecnologia de auto-atendimento B2B com crédito pré-aprovado (Menezes),
previsibilidade de faturamento/logística da fábrica (Lubpar, Encruzilhada,
JF), e ferramentas de geração de demanda/marketing de performance
(citado por praticamente todas as revendas como a dor nº 1 do dia a
dia, mas fora do escopo financeiro da Propig).

Principais incertezas que permanecem: se a taxa-alvo de 5-6% em 10x
identificada por Menezes é economicamente viável para a Propig replicar
com a margem que a Goodyear/distribuidor poderiam subsidiar; se o padrão
"distribuidor 100% B2B" da Lubpar é regra geral do modelo Goodyear ou uma
particularidade dela; e qual proporção real da rede de revendas oficiais
se parece mais com o perfil "Peregrina" (resistente) versus o perfil
"JF/Menezes" (sofisticado e aberto) — a amostra de 4 revendas não permite
estimar essa proporção com confiança.

Decisões que precisam ir para o workshop: qual ator da cadeia priorizar
(revenda oficial vs. distribuidor vs. sub-revenda multimarca atendida
pelo distribuidor); se existe uma ou múltiplas propostas de valor
necessárias; e como lidar com o fato de que, ao contrário da Moura, a
Goodyear não tem hoje nenhum mecanismo de subsídio financeiro ativo na
cadeia — o que muda fundamentalmente quem pagaria a conta de qualquer
solução nova.

---

## 2. Entendimento do ecossistema Goodyear

### Configurações de cadeia efetivamente identificadas

**Evidência.** As entrevistas revelam pelo menos três configurações
distintas, não uma única cadeia linear:

**Configuração 1 — Revenda oficial monomarca, compra direta da fábrica**
(Peregrina, Menezes, Encruzilhada, JF — as 4 revendas entrevistadas):

```
Goodyear (fábrica) → Revenda oficial (via portal Gcom/SAP,
sem intermediário) → Consumidor final (85–98% do volume)
                   ↳ B2B/atacado residual (2–6%, esporádico,
                     não estratégico)
```

Todas as 4 revendas confirmam comprar **direto** da fábrica via portal
próprio (chamado "Gcom" em algumas entrevistas), sem passar pelo
distribuidor, mesmo estando em regiões onde existe distribuidor Goodyear
ativo (ex.: JF e Encruzilhada mencionam o distribuidor regional apenas
como um ator paralelo, não como seu fornecedor).

**Configuração 2 — Distribuidor B2B puro, atende revendas menores/multimarca**
(Lubpar):

```
Goodyear (fábrica) → Distribuidor (Lubpar) → Revenda
multimarca pequena/sub-revenda (sem volume para ser
revendedor oficial) → Consumidor final
```

Lubpar declara explicitamente **não vender a CPF e não ter operação de
varejo** — ele é 100% B2B. Atende revendas que não têm volume suficiente
para se qualificar como "revendedor oficial" direto da fábrica.

**Configuração 3 — Canais especiais paralelos, fora das duas cadeias acima**:

- **Locadoras de frota** (ex.: Localiza, citada por Lubpar e Encruzilhada)
  compram direto de importadores a preços abaixo até do custo do
  distribuidor — cadeia de suprimento e de preço completamente
  desconectada da cadeia Goodyear tradicional.
- **E-commerce/marketplace** (Mercado Livre, sites próprios) — citado por
  Encruzilhada, JF e Menezes como canal em que todos querem crescer, mas
  travado por regime fiscal (ICMS) que favorece players sediados em
  estados com benefício fiscal (ex.: Espírito Santo), exigindo CD e
  estoque segregado por estado para competir — nenhuma das revendas
  entrevistadas resolveu isso.
- **"Distribuidor espelho"** — Lubpar relata que a Goodyear permite mais
  de um distribuidor na mesma área geográfica ("distribuidor espelho"),
  gerando concorrência interna entre distribuidores da própria marca —
  configuração que não tem paralelo relatado no modelo Moura.

**Interpretação**: a hipótese de trabalho herdada das entrevistas
internas de kickoff Moura — de que "o distribuidor Goodyear em dado
momento também atende o cliente final" (modelo híbrido) — **não se
confirma nas 5 entrevistas**. O que se confirma é a coexistência de dois
circuitos praticamente paralelos (revenda oficial direto-da-fábrica vs.
distribuidor-para-sub-revenda), com pouquíssima sobreposição. **Hipótese
não resolvida**: pode existir, em outras regiões ou outros distribuidores
Goodyear não entrevistados, um modelo híbrido — a amostra (1 distribuidor)
não permite generalizar que todo distribuidor Goodyear seja 100% B2B como
a Lubpar.

### Quem financia quem, e onde fica o risco

**Evidência**: em nenhuma das 5 entrevistas há relato de a Goodyear
antecipar capital, dar carência estendida, subsidiar taxa de parcelamento
ao consumidor, ou lastrear crédito de forma ativa e sistemática — a
única exceção é a JF, que recebe **90 dias nos 3 primeiros pedidos** ao
abrir uma loja nova (benefício pontual de expansão, não uma política de
crédito contínua), e Lubpar, que recebe **descontos comerciais
proporcionais** vinculados a campanhas (verba cooperada, rebate por
volume), que **não é** crédito ou capital, mas desconto de preço.

Em todos os casos, **o risco de conceder prazo ao elo seguinte da cadeia
é sempre absorvido por quem concede** — a Goodyear concede prazo de
pagamento (7 a 60 dias) sem checar quanto risco isso implica para a
revenda; a revenda, por sua vez, concede parcelamento de 6-12x ao
consumidor final e absorve integralmente o custo da adquirente/antecipação
(quando antecipa) ou o risco de recebimento diluído no tempo (quando não
antecipa). Não existe, em nenhum relato, um mecanismo formal de
compartilhamento de risco entre elos.

**Interpretação**: essa é a diferença estrutural mais importante frente
ao modelo Moura. O Credimora nasceu justamente para a fábrica (Moura)
assumir parte ativa do subsídio/risco de crédito na cadeia. No
ecossistema Goodyear hoje, **nenhum ator da cadeia desempenha esse papel
— cada elo se vira sozinho**. Isso não invalida a oportunidade, mas muda
fundamentalmente a pergunta: no modelo Moura, a Propig entra numa cadeia
que já tinha um "doador" de subsídio (a fábrica); no modelo Goodyear, a
Propig precisaria construir esse papel do zero, ou convencer a Goodyear a
assumi-lo — isso é uma mudança de proposta de valor, não um ajuste
cosmético.

### Como as diferentes configurações alteram dores e oportunidades

**Interpretação**, cruzando as evidências acima: a Configuração 1
(revenda oficial) tem uma dor financeira nítida e recorrente
(descasamento de prazo compra-vs-venda) que é estruturalmente parecida
com a dor original da Moura. A Configuração 2 (distribuidor B2B) tem uma
dor financeira de natureza diferente — não é sobre parcelar ao
consumidor, é sobre **lastrear/garantir o limite de crédito que ele
mesmo concede às revendas menores**, o que se aproximaria mais de um
produto de garantia/seguro de crédito do que de um produto de
parcelamento ao consumidor final. A Configuração 3 (locadoras,
e-commerce) parece estruturalmente fora do escopo financeiro core da
Propig — são problemas de canal e de regime fiscal, não de crédito.

---

## 3. Perfis / arquétipos das empresas

A partir das evidências, emergem **três arquétipos**, não quatro ou
cinco — porque as 4 revendas, apesar de terem porte e localização
diferentes, compartilham o mesmo modelo econômico fundamental. A
diferença relevante entre elas não é de arquétipo, mas de **grau de
sofisticação financeira e de abertura ao risco/inovação**, tratado
separadamente na Seção 11 (tensões).

### Arquétipo A — Distribuidor B2B puro (Lubpar)

- **Modelo de negócio**: revenda por atacado para uma carteira de
  milhares de clientes B2B (10.000+), nunca toca consumidor final.
- **Papel na cadeia**: intermediário entre fábrica e revenda
  multimarca/sub-revenda de menor porte.
- **Para quem vende**: pequenas e médias revendas multimarca que não
  atingem volume para comprar direto da fábrica.
- **Receita**: markup sobre pneu (mais alta escala, margem mais
  apertada — meta de inadimplência de 0,25%, hoje em 2%) e sobre
  lubrificante (linha paralela via Shell/Raízen).
- **Relação com consumidor final**: nenhuma, explicitamente.
- **Relação com revendas**: extremamente sofisticada — motor de crédito
  próprio (parametrizado, rodando em plataforma terceirizada NeoCrédito),
  comitê de crédito para clientes grandes, gestão de portfólio por
  cluster.
- **Relação com a Goodyear**: sofre com falta de suporte financeiro
  (60 dias fixos, zero antecipação, zero garantia), e com concorrência
  interna (distribuidor espelho na mesma área).
- **Dinâmica de estoque**: ~300 SKUs, ~100 dias de capital de giro
  amarrado (60 dias a receber + 40 dias de estoque).
- **Dinâmica financeira**: 100% do risco de crédito concedido é próprio,
  sem nenhuma garantia externa — carteira de R$70 milhões sem garantia
  real.
- **Objetivos**: crescer ~20% represados por limitação de crédito;
  já busca ativamente uma solução de lastreamento de crédito no mercado
  financeiro por conta própria.
- **Principais dores**: limite de crédito autoimposto (risco máximo já
  atingido), pressão do importado, inadimplência de PJs de médio porte
  altamente alavancados em antecipação de cartão.
- **Alavancas de crescimento**: mais crédito lastreado por terceiro =
  mais vendas, segundo estimativa própria do entrevistado.

### Arquétipo B — Revenda oficial monomarca, consumidor-final-first (Peregrina, Menezes, Encruzilhada, JF)

- **Modelo de negócio**: varejo especializado (pneu + serviços
  automotivos complementares: suspensão, freio, alinhamento,
  balanceamento), monomarca por contrato de revendedor oficial.
- **Papel na cadeia**: ponto de venda final, compra direto da fábrica.
- **Para quem vende**: 85%–98% consumidor final (pessoa física); resto é
  B2B/atacado esporádico e de baixo volume, tratado como relação
  comercial ("venda casada"), não como linha de negócio estratégica.
- **Receita**: mix de pneu (50-70% do faturamento) + serviços/peças
  (30-50%) — todas as 4 revendas relatam estar deslocando o mix para
  serviços porque a margem de pneu caiu estruturalmente.
- **Relação com consumidor final**: direta, via tráfego pago (Google,
  Instagram, WhatsApp) — canal de aquisição dominante em todas as 4.
- **Relação com revendas**: marginal — não é o núcleo do negócio.
- **Relação com a Goodyear**: assessor comercial dedicado (ou
  compartilhado entre poucas contas), portal de pedidos self-service,
  verba cooperada de marketing (trimestral, limitada), políticas de
  preço únicas (sem diferenciação por volume/porte).
- **Dinâmica de estoque**: 60–90 dias, sujeito a falta de previsibilidade
  de faturamento da fábrica (relatado por 3 das 4 revendas).
- **Dinâmica financeira**: paga a fábrica em 7–60 dias; vende ao
  consumidor em 6–12x — descasamento estrutural relatado por todas.
- **Objetivos**: expandir número de lojas, crescer em serviços
  (margem maior que pneu), eventualmente entrar em e-commerce/B2B
  (JF cogita "terceiro braço" de distribuição, mas reconhece ser outro
  negócio).
- **Principais dores**: pneu importado corroendo margem e volume;
  concorrência desleal de franquias de baixa reputação ("Impacto Prime"
  e afins); geração de demanda/tráfego pago cada vez mais caro e
  competitivo; imprevisibilidade de reposição de estoque da fábrica.
- **Alavancas de crescimento**: mix de serviços, fidelização via
  CRM/pós-venda, equipamento original (recompra garantida por troca de
  pneu original).

### Arquétipo C — Locadora/frota de alto volume (mencionado, não entrevistado)

- Citado por Lubpar e Encruzilhada como um ator que compra direto de
  importadores a preço abaixo do custo do distribuidor oficial, com
  desconto CV pela fábrica que funciona quase como subsídio.
- **Hipótese** (não evidência direta, pois este ator não foi
  entrevistado): esse canal provavelmente tem dinâmica de crédito e
  volume completamente diferente das revendas de varejo, e merece
  investigação própria antes de qualquer conclusão.

### Por que essas diferenças de arquétipo importam para o desenho de uma solução

**Interpretação**: os Arquétipos A e B têm modelos de receita, relação
com risco e necessidade de capital tão diferentes que uma única proposta
de valor dificilmente serve aos dois simultaneamente. O Arquétipo A
precisa de um instrumento de **garantia/lastreamento de crédito
concedido a terceiros** (mais próximo de um seguro de crédito ou linha
de capital de giro garantida). O Arquétipo B precisa de um instrumento
de **parcelamento ao consumidor final com custo/prazo melhor do que o
hoje disponível via adquirente tradicional** — estruturalmente mais
parecido com o Credimora original da Moura. Tratar os dois como a "rede
Goodyear" de forma unificada arrisca desenhar uma solução que não serve
bem a nenhum dos dois.

---

## 4. O que essas empresas querem alcançar

**Objetivos recorrentes na amostra** (aparecem em 3+ das 5 entrevistas):

- **Crescer margem via mix de serviços**, não mais via volume de pneu —
  relatado por Peregrina (mix mudando), Menezes, Encruzilhada e JF, todas
  de forma independente e não induzida.
- **Reduzir dependência de tráfego pago caro** — todas as 4 revendas
  citam geração de demanda digital como o maior desafio operacional do
  dia a dia, e todas gostariam de mecanismos de fidelização/recompra
  mais fortes que não dependam 100% de mídia paga.
- **Obter prazo maior ou taxa menor da fábrica** — Peregrina pede
  30/60/90 explicitamente; Lubpar já busca isso no mercado por conta
  própria; Menezes calcula uma taxa-alvo específica; JF já otimiza o
  prazo disponível via antecipação bancária própria.
- **Crescer em canais novos (e-commerce, B2B, marketplace)** — citado por
  Encruzilhada, JF e Menezes, mas travado estruturalmente por regime
  fiscal, não por falta de vontade.

**Objetivos específicos de determinados perfis**:

- **Lubpar** (único do Arquétipo A na amostra): quer lastrear
  parcialmente seu limite de crédito concedido via instituição
  financeira terceira — objetivo estratégico de estrutura de capital,
  não de vendas no dia a dia.
- **JF**: cogita, no médio prazo, expandir para um "terceiro braço" de
  distribuição/atacado (atender frotas, caminhões), mas reconhece que
  isso exige estrutura logística e comercial diferente — não é uma
  aspiração imediata.
- **Encruzilhada**: quer mais apoio de marketing/mídia da fábrica,
  especificamente reclamando que a Goodyear reduziu recentemente o
  espaço de uso da marca em campanhas de serviço (só permite associar a
  marca a campanhas de pneu) — um objetivo de relacionamento de marca,
  não financeiro.
- **Menezes**: quer parceria de marca cruzada (ex.: seguradoras como
  Porto Seguro indicando oficinas credenciadas Goodyear) — objetivo de
  geração de demanda via ecossistema de parceiros, não financeiro.

**Interpretação**: nenhuma das 5 empresas, quando perguntada
espontaneamente sobre "o que ajudaria a vender mais", cita crédito ou
parcelamento como primeira resposta — a primeira resposta é quase sempre
**marketing/geração de demanda** ou **previsibilidade de abastecimento**.
O tema financeiro só emerge com força quando o entrevistador o introduz
diretamente. **Isso não invalida a oportunidade financeira**, mas indica
que ela não é a dor mais "top of mind" — precisa ser apresentada
conectada a um benefício de vendas tangível (como já é a intuição do
bloco de prova de conceito), não como um produto financeiro abstrato.

---

## 5. Principais desafios da cadeia

### Pneu importado/chinês corroendo margem e volume

**Qual é o problema?** Pneus importados, principalmente chineses,
representam hoje entre 40% (JF) e 60% (JF, segundo dado que a própria
Goodyear apresenta em workshops internos) do mercado nacional, contra
~35% um ano antes — avanço muito rápido. Vendidos a preços
significativamente mais baixos (ex.: metade do preço, segundo Encruzilhada
e Lubpar), inclusive por vezes abaixo do próprio custo do distribuidor
oficial, atraindo consumidores sensíveis a preço.

**Por que acontece?** Mudança tributária (fim de um imposto anti-dumping
citado por JF), câmbio, e estratégia comercial agressiva de fabricantes
chineses que também começaram a alongar prazo de parcelamento para
compensar imagem/desconfiança.

**Quem é afetado?** Todas as 5 empresas, sem exceção — é o único tema
verdadeiramente unânime da pesquisa.

**Que impacto gera?** Margem de pneu caiu de patamares históricos de
6% (Lubpar) para o teto atual de ~2%; volume de pneus vendidos caiu
(JF relata volume e preço em queda simultânea); revendas estão
deslocando o mix para serviços para compensar.

**Como resolvem hoje?** Argumentação de produto/qualidade/reputação,
programas de fidelização (equipamento original), deslocamento de foco
para serviços de maior margem.

**Essa solução é suficiente?** Parcialmente — todas relatam que está
"ficando mais difícil", que a solução via argumentação de venda tem
limite, e que uma parcela relevante do consumidor "só quer preço".

**Interpretação**: este é um problema **estrutural e fora do alcance de
qualquer solução financeira de parcelamento** — nenhuma taxa ou prazo
melhor resolve a diferença de preço de 50% entre pneu nacional e
importado. É importante reconhecer isso explicitamente no discurso da
Propig para não parecer descolada da dor real do setor.

### Descasamento entre prazo de compra (fábrica) e prazo de venda (consumidor)

**Qual é o problema?** A fábrica concede 7–60 dias de prazo; a revenda
concede 6–12 parcelas (meses) ao consumidor final. Esse hiato precisa ser
bancado com capital próprio ou com custo de adquirente/antecipação.

**Por que acontece?** O parcelamento ao consumidor virou padrão
competitivo de mercado (relatado por Peregrina, Menezes e JF como algo
que "todo mundo faz, senão fica pra trás"), mas a fábrica não alongou
seu próprio prazo de venda na mesma proporção.

**Quem é afetado?** Todas as 4 revendas oficiais, e o distribuidor
(Lubpar) na relação com sua própria carteira.

**Que impacto gera?** Necessidade de capital de giro para bancar o
hiato; custo de adquirente/antecipação (6–9% conforme a revenda);
restrição de crescimento quando o capital de giro próprio não é
suficiente (relatado explicitamente por Lubpar como o principal freio a
20% de crescimento adicional).

**Como resolvem hoje?**
- Peregrina: não antecipa, recebe parcela por parcela (aceita o hiato
  como custo de operação conservadora).
- Menezes: antecipação automática total, taxa 8-9% em 10x.
- JF: antecipação automática D+1 via InfinityPay, mais otimização do
  lado da compra (antecipa boleto de 45 dias via DDA para capturar
  desconto proporcional a 7 dias).
- Encruzilhada: não antecipa (GetNet 1,89% em 10x, fluxo normal), mas
  também não bancou capital extra para 10x — manteve 6x como padrão.
- Lubpar: 100% capital próprio, já no limite de risco máximo.

**Essa solução é suficiente?** Não uniformemente — Menezes e JF
resolveram de forma sofisticada, mas pagando um custo alto (8-9%) que
eles mesmos identificam como caro; Peregrina e Encruzilhada evitam o
problema simplesmente não expandindo o parcelamento tanto quanto
poderiam, o que é uma forma de deixar vendas na mesa (hipótese, não
confirmada diretamente por elas).

**Que consequência ou novo problema gera?** Um ciclo onde quem antecipa
mais paga mais caro, e quem não antecipa potencialmente vende menos —
sem meio-termo estruturado disponível hoje no mercado, segundo as
evidências coletadas.

**Interpretação**: este é o problema mais estruturalmente equivalente à
dor original que o Credimora resolveu para a Moura, e o que mais
justifica investigação aprofundada de uma solução Propig para o canal
Goodyear.

### Imprevisibilidade de faturamento/logística da fábrica

**Qual é o problema?** Pedido feito hoje pode ser faturado no dia
seguinte ou só no fim do mês, sem cronograma confiável — relatado por
Lubpar, Encruzilhada e JF.

**Por que acontece?** Segundo Encruzilhada, falta de coordenação
regional/nacional de estoque entre fábricas e CDs ("Goodyear tem um
problema danado de faturamento"); segundo Lubpar, decisão logística
interna da Goodyear sobre origem de despacho (São Paulo vs. outras
fábricas).

**Quem é afetado?** Distribuidor e revendas que dependem de reposição
recorrente.

**Que impacto gera?** Estoque de segurança inflado (60-100 dias em vez
do necessário), capital imobilizado em estoque maior do que o ideal.

**Como resolvem hoje?** Aumentam o estoque de segurança — não é uma
solução, é uma forma de absorver o problema com mais capital parado.

**Interpretação**: problema operacional/logístico da fábrica, fora do
escopo financeiro direto da Propig, mas relevante porque **agrava** a
necessidade de capital de giro discutida no problema anterior — os dois
problemas se somam.

### Concorrência desleal / franquias de baixa reputação

**Qual é o problema?** Relatado de forma quase idêntica por Peregrina,
Menezes e JF: redes de baixo custo (apelidadas "Impacto Prime" e
similares) atraem clientes com preço de pneu artificialmente baixo e
depois "inventam" problemas no carro para vender serviços desnecessários
ou substituir peças por peças de qualidade inferior sem avisar o cliente.

**Por que acontece?** Modelo de negócio baseado em engano ao consumidor
combinado com falta de informação/maturidade do comprador de pneu
(citado por Menezes).

**Quem é afetado?** Revendas oficiais que competem por tráfego e preço
contra esses players.

**Impacto**: perda de clientes por preço de entrada mais baixo (mesmo
que a experiência final seja pior); desgaste de confiança no setor como
um todo.

**Interpretação**: problema de reputação de mercado e de educação do
consumidor, não de crédito ou parcelamento — fora do escopo financeiro
da Propig, mas relevante para entender por que a "confiança" e o "selo
de revendedor oficial" aparecem como argumento de venda tão forte nas
entrevistas (ponto retomado na Seção 10).

### Crédito e limite (assimétrico entre Arquétipos A e B)

**Qual é o problema?** Para Lubpar (distribuidor), o limite de crédito
que pode conceder às suas revendas é o principal fator limitante de
crescimento — ele mesmo estima 20% de vendas represadas por essa causa.
Para as revendas oficiais (Arquétipo B), o "limite de crédito" não é tema
relevante na relação com a fábrica (Goodyear tem política de crédito
única, não diferenciada por porte, segundo relato de JF e Encruzilhada) —
a única exceção é JF, que recebeu análise de DRE ao abrir novas lojas.

**Interpretação**: crédito/limite é uma dor de primeira ordem só para o
Arquétipo A (distribuidor). Para o Arquétipo B, o tema financeiro
relevante não é limite de crédito da fábrica, é custo/estrutura do
parcelamento ao consumidor final — dois problemas de crédito
completamente diferentes, que merecem soluções diferentes.

---

## 6. Análise da dinâmica financeira

### Onde existe descasamento entre vender, receber, pagar e voltar a comprar

**Evidência cruzada**: o ciclo "vender → receber → pagar → recomprar"
está desencaixado em pontos diferentes dependendo do arquétipo:

- **Lubpar** (Arquétipo A): recebe do cliente em prazo médio de 42 dias
  (variável 28-84 dias conforme negociação do vendedor), mas paga a
  Goodyear em prazo fixo de 45-60 dias. O desencaixe aqui é mais
  equilibrado no nível "fábrica-distribuidor", mas o verdadeiro
  desencaixe está entre o distribuidor e SUA carteira de clientes, cujo
  ciclo real de conversão em dinheiro (considerando os 12x no cartão que
  os clientes finais de Lubpar praticam) é muito mais longo que os 42
  dias nominais — Lubpar relata explicitamente que grandes clientes de
  pneu dependem fortemente de antecipação de cartão para sustentar 12x.
- **Peregrina**: compra em 45 dias, vende em até 10x (10 meses) sem
  antecipar — o desencaixe é absorvido 100% com capital próprio, sem
  custo de antecipação, mas também sem giro acelerado.
- **Menezes**: compra em 4-7 dias (à vista, com desconto), vende 80% em
  10-12x, com antecipação automática total — desencaixe resolvido via
  custo financeiro explícito (8-9%), não via capital parado.
- **Encruzilhada**: compra em 60 dias (opção escolhida, não a mais
  barata disponível — 7 dias teria desconto maior, mas mantêm o fluxo
  histórico), vende majoritariamente em 6x sem antecipar.
- **JF**: compra em 45 dias mas antecipa o próprio boleto via DDA para
  capturar desconto — otimização do lado da COMPRA; vende em 6x (praxe)
  com antecipação automática D+1 do lado da VENDA. É a gestão mais
  sofisticada e bidirecional encontrada na amostra.

**Esse descasamento realmente limita alguma decisão?**
- Para Lubpar: **sim, explicitamente** — ele mesmo quantifica 20% de
  vendas represadas pelo limite de crédito que consegue conceder com
  capital próprio.
- Para Menezes: **sim, mas já mitigado a um custo alto** — a decisão de
  ir para 10-12x já foi tomada, mas o custo de 8-9% é percebido como
  caro; uma taxa mais barata (5-6%) "traria ganho", segundo o próprio
  entrevistado, implicando que hoje o alto custo restringe margem, não
  necessariamente volume.
- Para Peregrina: **não claramente** — eles preferem não expandir o
  parcelamento ou antecipar, por escolha de gestão conservadora, não por
  restrição de capital relatada.
- Para Encruzilhada: **ambíguo** — mantiveram 6x como padrão e testaram
  10x sem ganho de conversão proporcional ao custo extra, decisão
  racional baseada em teste próprio, não em restrição de capital.
- Para JF: **não** — já otimizou os dois lados do ciclo com ferramentas
  disponíveis no mercado (DDA, antecipação automática), e mantém 6x como
  padrão para não sacrificar margem desnecessariamente, exceto em uma
  loja específica (Praia Grande) onde o mercado local exige 10x.

**Quem precisa de liquidez?** Evidência mais forte: Lubpar. Entre as
revendas, nenhuma relata estar restrita por falta de liquidez imediata —
todas gerenciam o ciclo com ferramentas já disponíveis (antecipação via
adquirente, ou simplesmente não antecipando).

**Quem consegue financiar a própria operação?** Todas as 4 revendas
conseguem, com maior ou menor grau de sofisticação/custo. Lubpar também
consegue, mas no limite do risco máximo que se permite assumir.

**Quem antecipa recebíveis? Por quê?** Menezes e JF antecipam
sistematicamente, porque o volume de vendas parceladas em 10-12x tornou
inviável não antecipar (ficariam com capital de giro insuficiente).
Quem não antecipa (Peregrina, Encruzilhada) o faz porque **mantém o
parcelamento mais curto ou porque prioriza fluxo de caixa estável sobre
crescimento de vendas via parcelamento agressivo** — escolha
deliberada, não incapacidade.

**Onde o problema é liquidez?** Lubpar, primariamente.

**Onde o problema é custo financeiro/margem?** Menezes (explicitamente:
quer taxa menor, não mais prazo) e, por extensão, qualquer revenda que
hoje antecipa a taxas de 6-9%.

**Onde o problema é prazo?** Peregrina (pede prazo maior da fábrica,
mas não fala em taxa) e Lubpar (quer lastreamento, que é uma forma de
estender prazo/risco).

**Onde o problema é risco/inadimplência?** Lubpar, com clareza — cita
inadimplência controlada mas presente, e um caso concreto de calote de
R$1 milhão. As revendas relatam inadimplência baixa e concentrada
(Menezes: <1% geral, 3-4% no segmento PJ de crédito direto).

**Onde praticamente não existe dor financeira relevante?** Peregrina e,
em menor grau, Encruzilhada — ambas descrevem operação financeira
estável e deliberadamente conservadora, sem urgência de capital.

**Onde melhores condições financeiras poderiam efetivamente aumentar
vendas?** Evidência direta e quantificada só existe para Lubpar (20%) e,
indiretamente, para qualquer revenda cujo teto de parcelamento hoje é
limitado por custo (a própria Menezes sugere que taxa mais baixa
"traria ganho", mas não afirma que aumentaria volume, apenas margem).

**Onde melhores condições poderiam aumentar compras (da fábrica)?**
Não há evidência direta disso em nenhuma entrevista — nenhuma revenda
relata comprar menos da fábrica por causa de prazo de pagamento; JF
inclusive afirma explicitamente que sua forma de pagar "não afeta" suas
decisões de compra.

**Onde uma solução financeira provavelmente teria baixo impacto?**
Peregrina (resistência filosófica à antecipação) e, para o problema de
importados/margem, todas as 5 — nenhuma solução de parcelamento resolve
concorrência de preço com pneu chinês.

### Interpretação consolidada da dinâmica financeira

Diferente do que uma leitura superficial sugeriria, **a "aderência" à
lógica Credimora não se explica por antecipar ou não recebíveis hoje** —
Peregrina não antecipa por escolha filosófica de caixa conservador;
Encruzilhada não antecipa porque manteve o parcelamento mais curto
propositalmente; Menezes e JF antecipam porque já são operações mais
agressivas em parcelamento. O critério que realmente diferencia
receptividade ao conceito Propig é **o grau de sofisticação/abertura
financeira do gestor**, não o estado atual do fluxo de caixa — Menezes e
JF, os dois perfis mais quantitativos e proativos, são também os dois
que mais cocriam com o conceito, independente de hoje já antecipar ou
não.

---

## 7. Tabela comparativa financeira

| Aspecto | Lubpar (distribuidor) | Peregrina (Vila Formosa) | Menezes (SJC) | Encruzilhada (Recife) | JF (Santo André) |
|---|---|---|---|---|---|
| Perfil/modelo de negócio | Distribuidor B2B puro | Revenda oficial, consumidor final | Revenda oficial, consumidor final | Revenda oficial, consumidor final | Revenda oficial, consumidor final |
| Papel na cadeia | Fábrica → distribuidor → sub-revenda | Fábrica → revenda oficial → consumidor | Fábrica → revenda oficial → consumidor | Fábrica → revenda oficial → consumidor | Fábrica → revenda oficial → consumidor |
| Para quem vende | Revendas multimarca menores (B2B) | 90-95% consumidor final | 95% consumidor final | 98% consumidor final | 94-99% consumidor final (varia por loja) |
| % consumidor final x B2B/revenda | 0% consumidor final / 100% B2B | ~90-95% CF / 5-10% B2B esporádico | 95% CF / 5% B2B esporádico | 98% CF / ~2% B2B (funcionários) | 94-99% CF / 1-6% B2B esporádico |
| Condição de pagamento à Goodyear | Não é cliente direto da fábrica (compra insumo via cadeia própria) | 45 dias boleto (opção 60 e 7 à vista existem) | 4-7 dias à vista (1% desconto vs. 45) | 60 dias direto (opção 7/30/45 também disponíveis) | 45 dias direto, antecipa via DDA p/ capturar desconto de 7 dias |
| Prazo efetivamente utilizado | Concede 42 dias médios (28-84) aos seus clientes | 45 dias | 4-7 dias | 60 dias | 45 dias (efetivo ~7 via DDA) |
| Frequência de compra | Contínua, diária/semanal (B2B) | 2x/mês | ~2x/mês (quinzenal) | 2x/mês (pedido maior + ajustes) | Contínua (~15 dias entre pedidos) |
| Volume de compra | ~12 mil pneus/mês (meta 20 mil) | Não identificado na entrevista | Não identificado na entrevista | Não identificado na entrevista | Não identificado na entrevista |
| Estoque | ~40 dias (100 dias de capital de giro total) | Não identificado na entrevista | 90 dias | Variável, ajustado por promoção | ~90 dias |
| Prazo de reposição | Não identificado na entrevista | 1 semana faturar + 1 semana entregar | 12-15 dias | 7-8 dias (variável, "danado") | 4-5 dias |
| Condições oferecidas ao cliente | 6-12x no cartão (cliente do cliente) | Até 10x sem juros | 10-12x | 6x padrão (10x em 1 loja específica) | 6x padrão (10x em 1 loja específica) |
| Parcelamento mais utilizado | 12x (grandes clientes) | 10x | 10-12x (80% das vendas parceladas) | 6x e 10x (mix) | 6x (17%) e 10x (16%), 12x (8%) |
| Taxa mencionada | Não identificado na entrevista (nível revenda) | 2,75% em 10x | 8-9% (MDR + antecipação) em 10x | 1,89% em 10x (GetNet) | ~6% em 6x (cartão); antecipação D+1 via InfinityPay |
| Antecipa recebíveis? | Não aplicável (não é o que vende ao CF) | Não | Sim, automática (pacote fechado) | Não | Sim, D+1 automático |
| Como recebe as vendas | Boleto, prazo negociado por cliente | Fluxo normal (parcela a parcela) | Antecipação total do pacote 10x+ | Fluxo normal | D+1 (exceto quando quer economizar, não antecipa manualmente) |
| Principal tensão financeira | Limite de crédito concedido a clientes | Prazo da fábrica vs. prazo dado ao cliente | Custo da taxa de antecipação (8-9%) | Ambivalência entre prazo maior vs. desconto à vista | Fiscal/DRE de um possível crédito não-caixa |
| Capital de giro é um problema? | Sim, explicitamente (100 dias de ciclo) | Não relatado como problema | Não relatado como problema (já resolvido via antecipação) | Não relatado como problema | Não relatado como problema |
| Crédito/limite é um problema? | Sim — principal restrição de crescimento (~20%) | Não | Não | Não | Não |
| Inadimplência é um problema? | Sim, controlada mas presente (~2%, meta 0,25%) | Não mencionada como problema relevante | Baixa (<1% geral, 3-4% no PJ) | Não mencionada como problema relevante | Não mencionada como problema relevante |
| Impacto financeiro no crescimento | Alto — 20% de vendas represadas (estimativa própria) | Baixo/não quantificado | Médio — margem, não volume | Baixo/não quantificado | Baixo/não quantificado |
| Mecanismo financeiro potencialmente relevante | Lastreamento/garantia de crédito concedido a terceiros | Prazo maior da fábrica (30/60/90) | Taxa única fixa 5-6% em 10x via fornecedor | Taxa fixa independente do nº de parcelas, como argumento de venda | Crédito de venda virando crédito de recompra (like Credimora), com ressalva fiscal |
| Condições/ressalvas | Já busca isso sozinho no mercado — validação espontânea | Resistência filosófica à antecipação; abertura só a prazo, não a taxa/antecipação | Alta abertura, mas taxa precisa ficar abaixo de 8% para valer a pena | Pai/sócio fundador cético sobre necessidade da ferramenta | Preocupação com tratamento contábil/DRE do crédito não-caixa |

### Análise comparativa

**Interpretação**: a tabela evidencia que **a necessidade financeira
mais forte e mais quantificada (Lubpar) está no arquétipo que a lógica
Credimora original menos serve diretamente** — Lubpar não precisa de uma
ferramenta de parcelamento ao consumidor, precisa de uma ferramenta de
garantia/lastreamento de crédito concedido a terceiros. Entre as
revendas, que são o arquétipo mais parecido com o modelo original Moura,
a dor financeira existe mas é **mais moderada e mais heterogênea** do
que a dor histórica que motivou o Credimora — nenhuma das 4 revendas
relata estar deixando de vender por falta de crédito ou prazo, ao
contrário de Lubpar. Isso sugere que, se a Propig decidir priorizar o
Arquétipo B (revenda), a proposta de valor precisa ser primariamente
sobre **redução de custo/complexidade** (a taxa-alvo de 5-6% de Menezes,
o "argumento de venda" de JF), não sobre "viabilizar vendas que hoje não
acontecem" — um discurso mais parecido com otimização do que com
resgate de vendas perdidas.

---

## 8. Percepção sobre os conceitos/mecanismos apresentados

Nas entrevistas de Encruzilhada e JF, o entrevistador introduziu
explicitamente o conceito de crédito estruturado / crédito de venda
virando crédito de recompra (equivalente ao Flex/Sessão do Credimora).
Nas de Peregrina e Menezes, o conceito foi testado de forma mais
implícita, via perguntas sobre antecipação e taxa-alvo. Na de Lubpar, o
tema emergiu organicamente, sem que o entrevistador precisasse
apresentá-lo — o próprio entrevistado chegou à ideia de "consignação
disfarçada" sozinho.

### O que gerou interesse

- **JF**: interesse alto e explícito — cocriou variações (taxa fixa
  independente do parcelamento, usada como argumento de venda ativo, não
  só como mecanismo de back-office).
- **Menezes**: interesse alto, mas condicionado a uma taxa específica
  (5-6% em 10x) — ele mesmo calculou o valor que tornaria a proposta
  vantajosa.
- **Lubpar**: interesse alto e espontâneo — identificou sozinho a lógica
  de "consignação" e a lógica de conversão de share via facilidade de
  parcelamento, sem que o entrevistador tivesse introduzido esses termos.
- **Encruzilhada**: interesse moderado e qualificado — reconhece a lógica
  ("faz muito mais sentido que a bateria"), mas precisa de números
  concretos antes de se comprometer, e o cofundador mais velho é
  cético.

### O que gerou pouco interesse ou resistência

- **Peregrina**: resistência explícita à antecipação como mecanismo —
  "somos tradicionais", preferem prazo maior da fábrica a qualquer
  esquema de antecipação com taxa embutida.
- Todas as revendas foram uniformemente **desinteressadas ou neutras**
  em relação a mudar de adquirente/maquininha apenas por causa de taxa
  marginalmente menor — o custo de troca (gestão, conciliação,
  relacionamento histórico) supera o ganho, segundo Menezes e
  Encruzilhada.

### O que foi percebido como valor

- Taxa fixa e previsível, independente do número de parcelas (JF, Lubpar
  espontaneamente).
- Prazo maior de pagamento à fábrica, mesmo sem mudança de taxa
  (Peregrina, Lubpar).
- Possibilidade de usar a condição de pagamento como argumento de venda
  ativo perante o cliente final, não apenas como otimização de
  back-office (JF explicita isso com muita clareza).

### O que foi percebido como pouco relevante

- Antecipação isolada sem redução de taxa (Peregrina não vê valor nisso;
  Encruzilhada já testou e recuou por achar caro demais no passado,
  embora reconheça que hoje o custo de antecipação caiu).

### Dúvidas espontâneas e resistências específicas

- **Taxa**: recorrente em todas — "qual seria a taxa" é sempre a
  primeira pergunta de quem se interessa (Menezes, JF).
- **Fiscal/tributário**: JF levanta explicitamente a dúvida sobre como um
  "pagamento gerado em crédito" (não em caixa) entraria no DRE — dúvida
  não resolvida na própria entrevista, aponta para necessidade de
  clareza contábil/fiscal na proposta de valor.
- **Conciliação/controle**: Menezes valoriza a facilidade de conciliação
  da "Rede" (adquirente atual) mais do que economia marginal de taxa —
  sinaliza que qualquer solução nova precisa ser tão simples de
  conciliar quanto o que já existe, ou melhor.
- **Percentual direcionado ao crédito**: JF cocria a ideia de poder
  escolher/configurar quanto da venda vira crédito para recompra vs.
  quanto fica em caixa próprio — mecanismo de flexibilidade não
  antecipado no bloco de prova de conceito atual, mas que surgiu
  espontaneamente na conversa.
- **"Excedente" que nunca bate 100%**: tanto Encruzilhada quanto JF
  levantam, de forma independente, que a lógica de "todo crédito vira
  compra futura" nunca vai ser 100% eficiente porque a venda inclui pneu
  + serviço + peças, e o crédito gerado provavelmente será maior do que
  o necessário para recompra de pneu — ponto técnico real que qualquer
  desenho de produto precisa endereçar.

**Interpretação**: essas dúvidas/resistências não são objeções
genéricas — são **requisitos de design específicos** que emergiram
organicamente: (1) taxa competitiva e clara (referência: 5-6% em 10x);
(2) tratamento fiscal/contábil explicado desde o início; (3) conciliação
tão simples quanto a adquirente atual; (4) flexibilidade de percentual
direcionado a crédito vs. caixa; (5) mecanismo para lidar com o
"excedente" estrutural entre venda total (pneu+serviço) e capacidade de
recompra (só pneu).

---

## 9. Fit entre os problemas encontrados e as capacidades da Propig

### Prazo maior de pagamento à fábrica (30/60/90 em vez de padrão atual)

- **Qual problema resolveria?** Alívio parcial do descasamento de fluxo
  de caixa entre compra e venda.
- **Para qual ator?** Revenda oficial (Arquétipo B), especialmente
  Peregrina.
- **Para qual perfil?** Revendas que já compram direto da fábrica e
  hoje pagam em prazos curtos (7-60 dias).
- **Evidência**: Peregrina pede isso explicitamente e de forma
  espontânea; Lubpar também, mas no nível fábrica-distribuidor.
- **Condição para funcionar**: exige que algum ator (Goodyear, Propig,
  ou uma instituição financeira parceira) esteja disposto a financiar
  esse alongamento — hoje ninguém na cadeia faz isso.
- **Risco/efeito colateral**: se o financiamento do prazo maior vier com
  taxa embutida, pode reproduzir exatamente a resistência que Peregrina
  já demonstrou contra "antecipação com taxa".
- **Para quais perfis não é relevante?** Menezes e JF já resolveram esse
  problema por conta própria (antecipação de boleto via DDA, compra à
  vista com desconto) — pouco incremental para eles.

### Taxa única fixa, independente do número de parcelas, lastreada por terceiro

- **Qual problema resolveria?** Custo alto e variável de MDR +
  antecipação (hoje 6-9% conforme a revenda).
- **Para qual ator?** Revenda oficial.
- **Para qual perfil?** Revendas que já parcelam agressivamente (Menezes,
  JF) e sentem o custo da antecipação atual como caro.
- **Evidência**: Menezes calcula sozinho a taxa-alvo (5-6%); JF propõe
  esse mecanismo como argumento de venda espontaneamente.
- **Condição para funcionar**: taxa efetivamente abaixo do custo atual
  de mercado (Menezes: abaixo de 8-9%); conciliação tão simples quanto a
  atual (requisito explícito de Menezes).
- **Risco/efeito colateral**: se a Propig ou a Goodyear tiverem que
  subsidiar a diferença entre a taxa oferecida e o custo real de capital,
  isso reproduz a mesma questão que já existe hoje no Credimora Moura
  (quem paga o subsídio) — mas, diferente da Moura, a Goodyear hoje não
  tem nenhum histórico de participar desse tipo de subsídio.
- **Para quais perfis não é relevante?** Peregrina (resistência a
  qualquer antecipação) e, com ressalvas, Encruzilhada (cofundador
  cético).

### Venda gerando crédito para recompra (mecanismo tipo Flex/Sessão)

- **Qual problema resolveria?** Alinhamento entre o dinheiro que entra
  parcelado do consumidor final e a necessidade de repor estoque junto à
  fábrica.
- **Para qual ator?** Revenda oficial, na relação direta com a
  Goodyear.
- **Para qual perfil?** Revendas monomarca, cujo principal insumo
  recorrente é o próprio pneu Goodyear (diferente da Moura, onde bateria
  é quase o único insumo — aqui pneu é só parte do ticket, junto com
  serviço e peças).
- **Evidência**: JF cocria ativamente essa ideia; Lubpar chega à mesma
  lógica de forma independente ("consignação disfarçada").
- **Condição para funcionar**: mecanismo de flexibilidade de percentual
  (nem toda venda deveria virar 100% crédito, porque inclui serviço,
  não só pneu) — requisito explícito de JF.
- **Risco/efeito colateral**: geração de "excedente" de crédito não
  utilizável (mais crédito gerado do que capacidade/necessidade de
  recompra de pneu) — problema técnico levantado por Encruzilhada e JF,
  ainda sem solução clara nas entrevistas.
- **Para quais perfis não é relevante?** Lubpar não compra pneu
  "no varejo" da fábrica — esse mecanismo, tal como desenhado para
  revenda, não se aplica a ele; para o distribuidor, faria mais sentido
  um mecanismo de garantia sobre o crédito que ELE concede aos clientes
  dele, não sobre a compra dele à Goodyear.

### Apoio/garantia de crédito e ampliação de limite (lastreamento de terceiro)

- **Qual problema resolveria?** Restrição de crescimento por limite de
  crédito autoimposto.
- **Para qual ator?** Distribuidor (Arquétipo A).
- **Para qual perfil?** Especificamente Lubpar, e por extensão qualquer
  distribuidor Goodyear com estrutura similar (hipótese, não confirmada
  para outros distribuidores).
- **Evidência**: Lubpar estima 20% de crescimento represado e já busca
  essa solução ativamente no mercado por conta própria.
- **Condição para funcionar**: exige um parceiro financeiro disposto a
  assumir parte do risco de crédito da carteira de um distribuidor —
  modelo de produto totalmente diferente (mais próximo de um seguro de
  crédito ou linha de garantia do que de um parcelamento ao consumidor).
- **Risco/efeito colateral**: é um produto financeiro mais complexo,
  regulatoriamente mais pesado, e potencialmente fora do escopo/core
  atual da Propig (**hipótese**, precisa validação com o time jurídico e
  de produto da Propig).
- **Para quais perfis não é relevante?** As 4 revendas — nenhuma relatou
  restrição de crédito da fábrica como problema.

### Redução de risco/inadimplência para distribuidor

- **Qual problema resolveria?** Exposição a calotes de clientes PJ de
  médio porte altamente alavancados.
- **Para qual ator?** Distribuidor.
- **Evidência**: Lubpar relata caso concreto de calote de R$1 milhão e
  menciona inadimplência controlada mas presente.
- **Condição para funcionar**: acesso a dados financeiros/de score do
  cliente final da carteira do distribuidor — Lubpar já tem motor
  próprio (NeoCrédito) sofisticado, então uma solução Propig precisaria
  agregar valor além do que ele já tem, não duplicar.
- **Para quais perfis não é relevante?** Revendas — inadimplência
  relatada como baixa e não problemática nelas.

### Apoio à relação distribuidor-revenda / crédito B2B pré-aprovado digital

- **Qual problema resolveria?** Fricção de compra B2B entre multimarca
  pequena e distribuidor (hoje via telefone, sem autoatendimento).
- **Para qual ator?** Distribuidor e sua carteira de sub-revendas.
- **Evidência**: Menezes cita, como benchmark, distribuidoras de
  autopeças que já têm portal self-service com crédito pré-aprovado.
- **Condição para funcionar**: integração tecnológica com o ERP do
  distribuidor.
- **Interpretação**: essa é mais uma oportunidade de produto/tecnologia
  do que estritamente financeira — fit indireto, vale registrar mas não
  é core.

---

## 10. Oportunidades que não são necessariamente Propig

### Geração de demanda / marketing de performance

**Necessidade**: citada por todas as 4 revendas como o desafio nº 1 do
dia a dia — custo crescente de tráfego pago, dependência de Google/Meta,
dificuldade de conversão de leads em agendamento (JF relata processo
elaborado de triagem via WhatsApp + comissionamento por agendamento
convertido).

**Para quais perfis?** Todas as revendas oficiais.

**Impacto no crescimento**: alto, segundo o próprio relato — é a
variável que mais preocupa os gestores no dia a dia, mais do que
crédito ou taxa.

**Recorrente ou pontual?** Recorrente e estrutural.

**Qual ator poderia atuar?** Goodyear (marca/mídia institucional,
citada com crítica por Encruzilhada — "a marca não ajuda a vender, só
fortalece institucional") ou agências especializadas — não é natural
para uma fintech.

**Por que entra ou não no workshop?** Não deveria ser responsabilidade
da Propig resolver, mas **deveria ser reconhecida no discurso** — se a
proposta de valor financeira vier acompanhada de qualquer elemento de
geração de demanda (ex.: "condição de pagamento como argumento de
venda", already citado por JF), o interesse tende a ser maior, porque
conecta com a dor mais sentida.

### Fortalecimento de marca / posicionamento

**Necessidade**: Peregrina relata gap geracional de reconhecimento de
marca entre consumidores mais jovens; Encruzilhada relata que a Goodyear
recentemente restringiu o uso da marca em campanhas de serviço (só
permite em campanhas de pneu), o que frustra a revenda porque ela vive
mais de serviço do que de pneu hoje.

**Para quais perfis?** Todas as revendas.

**Impacto**: indireto no financeiro, mas relatado como relevante para
atração de novos clientes.

**Ator responsável**: Goodyear (marca/marketing institucional).

**Por que não é Propig**: fora do escopo de uma fintech; mas relevante
como contexto para entender por que "confiança"/"selo oficial" é
recorrente como argumento de venda nas entrevistas — uma eventual
solução financeira poderia reforçar essa confiança (ex.: "compre com
quem tem o apoio financeiro oficial da marca"), mas não deveria tentar
substituir investimento de marca.

### Previsibilidade de abastecimento/logística

**Necessidade**: relatada por Lubpar, Encruzilhada e JF — falta de
cronograma confiável de faturamento gera estoque de segurança inflado.

**Para quais perfis?** Distribuidor e revendas.

**Impacto**: capital imobilizado desnecessariamente em estoque —
conecta indiretamente com a dor de capital de giro, mas a causa raiz é
logística/operacional da fábrica, não financeira.

**Ator responsável**: Goodyear (operações/supply chain).

**Por que entra no workshop**: vale mencionar porque **agrava** o
problema de capital de giro que a Propig poderia endereçar — uma solução
financeira de crédito ajudaria a mitigar o sintoma, mas não resolve a
causa.

### E-commerce e regime fiscal

**Necessidade**: JF, Encruzilhada e Menezes querem crescer em
e-commerce/marketplace, mas o regime de ICMS que favorece concorrentes
sediados em estados com benefício fiscal (Espírito Santo, citado
nominalmente) trava a competitividade das revendas regionais.

**Impacto**: relatado como perda de competitividade estrutural, não
pontual.

**Ator responsável**: nenhum ator da cadeia controla isso — é regulação
tributária estadual.

**Por que não é Propig**: completamente fora do escopo de uma fintech;
mencionar apenas como contexto de mercado.

### Tecnologia de autoatendimento B2B

Já descrita na Seção 9 — fit indireto/tecnológico, não estritamente
financeiro, mas conectável a um produto de crédito pré-aprovado.

---

## 11. Tensões e contradições entre as empresas

### Tensão 1 — Antecipação como alívio vs. antecipação como custo desnecessário

**Menezes/JF → necessidade**: antecipar é indispensável porque já
venderam a maior parte em 10-12x; sem antecipação, ficariam sem capital
de giro suficiente.

**Peregrina/Encruzilhada → necessidade diferente**: antecipar é um custo
evitável; preferem manter parcelamento mais curto (6x) ou não antecipar,
aceitando o hiato de caixa como parte da operação conservadora.

**O que essa diferença significa para o desenho da proposta**: não existe
uma resposta única sobre "a revenda Goodyear precisa de antecipação" — a
resposta depende de uma decisão de gestão anterior (quão agressivo é o
parcelamento oferecido ao consumidor), que por sua vez parece estar
ligada ao perfil do gestor e à dinâmica competitiva local (Encruzilhada
testou 10x, mediu resultado, e recuou; JF fez o mesmo mas manteve 10x
só numa loja onde o mercado local exige).

### Tensão 2 — Prazo maior vs. taxa menor como prioridade

**Peregrina/Lubpar → necessidade**: mais prazo (30/60/90), mesmo que a
taxa não mude — querem "ganhar tempo", não "pagar menos".

**Menezes → necessidade diferente**: taxa menor é o critério decisivo,
prazo já está resolvido via antecipação automática — quer "pagar
menos", não necessariamente "ganhar mais tempo".

**Encruzilhada → posição intermediária/cética**: discutiu com a própria
Goodyear a alternativa de desconto à vista maior em vez de prazo maior
financiado — ou seja, prefere "pagar menos agora" a "pagar depois",
terceira lógica diferente das duas anteriores.

**O que isso significa**: confirma que **não existe uma única proposta
de valor financeira que sirva a toda a rede** — pelo menos três lógicas
de valor diferentes (mais tempo, menos taxa, mais desconto à vista)
aparecem como prioritárias para gestores diferentes, sem que nenhuma
seja unanimemente "a melhor".

### Tensão 3 — Crédito para recompra automática vs. necessidade de flexibilidade

**JF/Lubpar → necessidade**: mecanismo de crédito de venda virando
crédito de recompra é bem-vindo e cocriado ativamente.

**Encruzilhada/JF → ressalva simultânea**: ambos, mesmo entusiasmados,
alertam que o mecanismo "nunca vai bater 100%" porque a venda inclui
serviço e peças, não só pneu — não é uma rejeição, mas uma condição de
design que, se ignorada, pode gerar excedente de crédito não utilizável
e frustração.

**O que isso significa**: mesmo dentro do grupo mais receptivo ao
conceito, há uma tensão entre "automatizar 100%" e "dar controle/
flexibilidade de percentual" — a segunda opção parece ser a mais alinhada
com o que os próprios entrevistados pedem.

### Tensão 4 — Dor de capital (distribuidor) vs. dor de custo (revenda)

**Lubpar → necessidade**: mais crédito disponível para conceder a
terceiros (problema de volume/limite).

**Revendas oficiais → necessidade diferente**: menos custo sobre o
crédito que elas mesmas já conseguem conceder ao consumidor (problema de
margem/taxa, não de limite).

**O que isso significa**: reforça a conclusão da Seção 3 — Arquétipo A e
Arquétipo B não competem pela mesma solução; uma proposta de valor
desenhada para "aliviar custo de parcelamento" não vai mover a agulha
para Lubpar, e uma proposta desenhada para "ampliar limite de crédito
concedido a terceiros" não é relevante para nenhuma das 4 revendas.

**Interpretação geral desta seção**: os dados sustentam fortemente a
ideia de que **não existe uma única proposta de valor para toda a rede
Goodyear** — existe, no mínimo, uma bifurcação clara entre Arquétipo A
(distribuidor) e Arquétipo B (revenda), e dentro do próprio Arquétipo B,
pelo menos três "modos" de necessidade financeira (mais prazo, menos
taxa, mais desconto à vista) que provavelmente exigem comunicação e
configuração de produto diferentes, mesmo que o mecanismo de back-end
possa ser o mesmo.

---

## 12. Territórios de oportunidade

### Território 1 — Taxa única de parcelamento, lastreada por terceiro, abaixo do custo atual de mercado

**Problema observado**: custo de MDR + antecipação hoje entre 6% e 9% em
parcelamentos de 10-12x nas revendas mais agressivas.

**Quem sofre com ele**: revendas que já parcelam agressivamente (Menezes,
JF, e potencialmente qualquer revenda no mesmo padrão de mercado — 80%
das vendas parceladas em 10x+ segundo Menezes).

**Evidências**: Menezes calcula taxa-alvo de 5-6%; JF propõe usar taxa
fixa como argumento de venda.

**Por que é relevante**: é o único território com uma referência
numérica concreta e validada por dois entrevistados independentes
(Menezes calcula, JF cocria a lógica).

**Oportunidade existente**: diferença entre custo atual (8-9%) e
taxa-alvo percebida como atrativa (5-6%) — uma margem de ~3 pontos
percentuais que poderia viabilizar tanto adoção quanto um modelo de
receita para a Propig, se o custo real de capital permitir.

**Possível papel da Propig**: originar e operar o mecanismo de crédito,
possivelmente com parceria de instituição financeira para o funding.

**Possível papel da Goodyear**: subsidiar parte da diferença (como a
Moura faz hoje no Credimora) — mas **não há evidência de que a Goodyear
tenha histórico ou apetite para isso** hoje; é uma pergunta em aberto
central para o workshop.

**O que ainda precisa ser validado**: se a taxa-alvo de 5-6% é
economicamente viável sem subsídio da fábrica; se esse número se
confirma numa amostra maior de revendas, ou é específico do perfil
Menezes.

### Território 2 — Prazo maior de pagamento à fábrica (mecanismo de "empréstimo" de prazo, não de desconto)

**Problema observado**: descasamento entre prazo de pagamento à fábrica
(7-60 dias) e prazo de recebimento do consumidor (6-12 meses).

**Quem sofre com ele**: Peregrina explicitamente, Lubpar por extensão.

**Evidências**: pedido espontâneo e repetido por Peregrina; busca ativa
de Lubpar por solução similar no mercado.

**Por que é relevante**: resolve o problema sem exigir que o gestor mude
sua filosofia de antecipação (ao contrário do Território 1, que depende
de aceitar antecipação/taxa).

**Oportunidade existente**: um produto de "prazo estendido lastreado",
sem necessariamente envolver antecipação de recebíveis do consumidor —
mais parecido com uma linha de capital de giro do que com um
parcelamento.

**Possível papel da Propig**: originar/lastrear esse prazo estendido.

**Possível papel da Goodyear**: aceitar prazo mais longo de recebimento
dela mesma (o que hoje ela não faz — trabalha com prazos fixos de 7 a
60 dias) — exige mudança de política comercial da própria fábrica, não
apenas um produto financeiro acoplado.

**O que ainda precisa ser validado**: se a Goodyear tem apetite/margem
para alongar seus próprios prazos de recebimento, ou se esse alongamento
precisaria ser 100% bancado por um terceiro financeiro (o que mudaria a
natureza econômica da proposta).

### Território 3 — Garantia/lastreamento de crédito concedido pelo distribuidor a terceiros

**Problema observado**: limite de crédito autoimposto por Lubpar como
principal freio de crescimento (~20% represado).

**Quem sofre com ele**: distribuidor (Arquétipo A).

**Evidências**: Lubpar quantifica o impacto e já busca essa solução
ativamente no mercado por conta própria.

**Por que é relevante**: é a dor financeira mais quantificada e mais
urgente de toda a pesquisa — mas também a mais distante do modelo de
produto atual da Propig (Credimora é sobre parcelamento ao consumidor,
não sobre garantia de crédito B2B).

**Oportunidade existente**: produto de garantia de crédito ou linha de
capital de giro lastreada, com potencial de replicar para outros
distribuidores Goodyear (não só Lubpar) e para o modelo de distribuidor
que também existe, hipoteticamente, em outras indústrias fora do escopo
deste projeto.

**Possível papel da Propig**: hipótese em aberto — pode estar fora do
core de produto atual; precisa avaliação de viabilidade regulatória e de
modelo de negócio (**hipótese, não conclusão**).

**Possível papel da Goodyear ou de outro ator**: instituição financeira
parceira especializada em garantia de crédito B2B, dado que é um produto
de natureza diferente do parcelamento ao consumidor.

**O que ainda precisa ser validado**: se esse território está dentro do
apetite estratégico da Propig, e se a amostra de 1 distribuidor é
representativa de outros distribuidores Goodyear.

### Território 4 — Mecanismo de venda gerando crédito configurável para recompra (tipo Flex/Sessão, com percentual ajustável)

**Problema observado**: falta de mecanismo que conecte automaticamente o
recebimento parcelado do consumidor final à necessidade de repor
estoque junto à fábrica.

**Quem sofre com ele**: revendas oficiais, de forma mais aguda nas mais
sofisticadas (JF, e, por analogia espontânea, Lubpar, embora ele não
compre pneu "no varejo" da fábrica).

**Evidências**: JF cocria ativamente essa ideia, incluindo a
possibilidade de configurar o percentual da venda que vira crédito;
Lubpar chega à mesma lógica de forma independente.

**Por que é relevante**: é o território mais próximo do mecanismo
Credimora original (Flex/Sessão), mas com uma diferença de design já
sinalizada pelos próprios entrevistados: precisa de **flexibilidade de
percentual**, porque a venda de uma revenda de pneu inclui serviço e
peças, não só o produto que seria "recomprado" (pneu), diferente da
Moura, onde bateria é o item quase único.

**Possível papel da Propig**: adaptar o mecanismo Flex/Sessão, incluindo
um controle de percentual configurável pelo gestor da revenda.

**Possível papel da Goodyear**: aceitar receber o crédito gerado como
forma de pagamento (mesma lógica do Credimora atual) — tecnicamente
viável, dado que a Goodyear já opera um sistema de crédito
comercial/rebate (DealerCorp, citado por Lucas em Encruzilhada) que
poderia servir de base de integração.

**O que ainda precisa ser validado**: tratamento fiscal/contábil do
crédito gerado (dúvida explícita de JF sobre DRE); como lidar com o
excedente estrutural entre valor total vendido (pneu+serviço) e
capacidade de recompra (só pneu).

---

## 13. Gaps da pesquisa

### 13.1 Gaps de amostra

- **Só um distribuidor entrevistado (Lubpar)**. Impacto: não sabemos se
  o padrão "100% B2B, sem varejo" é regra geral do modelo Goodyear ou
  particularidade da Lubpar — outros distribuidores podem ter operação
  de varejo própria (modelo híbrido), o que mudaria significativamente
  a Seção 2.
- **Nenhum distribuidor com operação de varejo próprio (modelo híbrido)
  foi entrevistado**. Impacto: a Configuração 1 (revenda direto-fábrica)
  domina a amostra (4 de 5 entrevistas); não sabemos como um distribuidor
  híbrido navegaria as duas dores simultaneamente (crédito concedido a
  terceiros + parcelamento ao consumidor final).
- **Nenhuma sub-revenda multimarca (cliente do distribuidor) foi
  entrevistada**. Impacto: conhecemos a relação distribuidor→sub-revenda
  apenas pela perspectiva do distribuidor (Lubpar) — não temos a
  perspectiva de quem está do outro lado dessa relação, que é
  provavelmente o perfil mais parecido com a "revenda pequena Moura" já
  estudada em outras entrevistas do projeto.
- **Concentração geográfica/de porte**: 4 das 5 entrevistas são revendas
  de porte médio-grande (4-6 lojas cada) em regiões metropolitanas (SP
  capital x2, Recife, ABC). Impacto: não sabemos como uma revenda pequena
  (1 loja, cidade menor) se comporta — pode ter dinâmica financeira e
  necessidade de crédito bem diferente.
- **Nenhuma locadora/frota entrevistada**. Impacto: esse canal foi citado
  como relevante (Lubpar, Encruzilhada) mas permanece uma caixa-preta —
  não sabemos sua dinâmica de crédito/parcelamento.
- **Consumidor final conhecido só pela percepção das empresas**. Impacto:
  toda leitura sobre "o que o consumidor valoriza" (ex.: parcelamento vs.
  preço) vem de intermediários, não de entrevista direta com quem
  compra — risco de viés de interpretação do lojista.

### 13.2 Gaps de investigação

- **Margem e formação de preço**: parcialmente respondido (Lubpar dá
  cadeia de markup completa: 60% Goodyear / 15% distribuidor / 25%
  trade; JF detalha um caso de venda real com ~60-75% indo para a
  Goodyear) — mas não sistematizado para todas as 5 empresas, então não
  dá para comparar margem líquida real entre elas com confiança.
- **Custo financeiro total**: bem respondido para Menezes e JF (números
  concretos), pouco ou nada respondido para Peregrina e Encruzilhada
  (dizem que não antecipam, mas não detalham o custo de oportunidade de
  manter capital parado).
- **Necessidade real de capital de giro**: bem quantificada só para
  Lubpar (100 dias de ciclo) — nas revendas, o tema aparece mas sem
  números específicos de capital de giro necessário.
- **Comportamento de compra do consumidor final**: não investigado
  diretamente — sabemos como as revendas descrevem o comportamento
  (ex.: "o consumidor faz a conta da parcela, não do total"), mas isso
  não foi validado com consumidores reais.
- **Sell-in vs. sell-out**: mencionado explicitamente só por Lubpar e
  Menezes (que usa o termo) — não sistematizado nas outras.

### 13.3 Gaps para avaliar uma oportunidade para a Propig

- **Gap**: não sabemos se a Goodyear tem, hoje, qualquer apetite ou
  budget para subsidiar uma solução financeira na cadeia (como a Moura
  faz). → **Por que é importante**: toda a viabilidade econômica dos
  Territórios 1, 2 e 4 depende de haver algum subsídio, porque a amostra
  mostra reiteradamente que "taxa mais baixa que o mercado" é a condição
  de adoção, e taxa mais baixa sem subsídio de alguém implica margem
  menor para quem opera o produto. → **O que não conseguimos concluir**:
  se a proposta é economicamente viável sem participação ativa da
  fábrica. → **Quem poderia responder**: contato comercial/estratégico
  direto com a Goodyear (não capturado nestas 5 entrevistas, que foram
  todas do lado do canal, não da fábrica). → **Como investigar**:
  entrevista ou reunião exploratória com a área comercial/financeira da
  Goodyear. **Classificação: Crítico para decisão.**

- **Gap**: não sabemos a proporção real de revendas "perfil Peregrina"
  (resistentes) vs. "perfil Menezes/JF" (abertas) na rede Goodyear como
  um todo. → **Por que é importante**: define se a proposta de valor
  deve ser desenhada para o público mais receptivo (nicho, mais fácil de
  converter, mas menor TAM) ou se precisa de uma versão "leve" que
  também sirva ao perfil resistente. → **O que não conseguimos
  concluir**: tamanho de mercado endereçável por tipo de proposta. →
  **Quem poderia responder**: mais entrevistas, ou dados quantitativos da
  própria Goodyear sobre perfil de parcelamento médio da rede. → **Como
  investigar**: survey quantitativo complementar à pesquisa qualitativa.
  **Classificação: Importante aprofundar.**

- **Gap**: não sabemos como o Território 3 (garantia de crédito B2B para
  distribuidor) se encaixaria no modelo de negócio/regulatório da
  Propig. → **Por que é importante**: é a dor mais quantificada da
  pesquisa, mas potencialmente a mais distante do produto atual. → **O
  que não conseguimos concluir**: viabilidade de produto/regulatória. →
  **Quem poderia responder**: time de produto e jurídico da própria
  Propig. → **Como investigar**: sessão interna de viabilidade, não mais
  pesquisa externa. **Classificação: Crítico para decisão.**

- **Gap**: não sabemos como resolver o "excedente" de crédito gerado
  quando a venda inclui serviço/peças além de pneu. → **Por que é
  importante**: é um requisito técnico de design levantado por dois
  entrevistados independentes (Encruzilhada, JF), sem o qual o
  Território 4 pode gerar frustração na adoção. → **O que não
  conseguimos concluir**: qual desenho de produto resolve isso de forma
  elegante. → **Quem poderia responder**: workshop interno de produto,
  com eventual validação posterior com as próprias revendas. → **Como
  investigar**: prototipagem e novo ciclo de validação. **Classificação:
  Importante aprofundar.**

---

## 14. O que sabemos x o que ainda é hipótese

### O que já sabemos (evidência suficiente)

- Existem pelo menos duas configurações de cadeia Goodyear
  estruturalmente diferentes: revenda oficial direto-da-fábrica (4 de 5
  entrevistas) e distribuidor B2B puro (1 de 5 entrevistas), com pouca
  sobreposição entre elas.
- O descasamento entre prazo de pagamento à fábrica e prazo de
  parcelamento ao consumidor final é real, recorrente, e citado
  espontaneamente por praticamente todos os perfis de revenda.
- Não existe, hoje, nenhum mecanismo ativo de subsídio ou participação
  financeira da Goodyear na cadeia, ao contrário do que ocorre com a
  Moura.
- A receptividade ao conceito de crédito estruturado varia fortemente
  por perfil de gestor, não pelo estado atual de antecipação/fluxo de
  caixa da empresa.
- O problema de pneu importado/chinês é unânime e não é resolvido por
  nenhuma solução financeira de parcelamento.
- Existe pelo menos uma referência numérica concreta de taxa-alvo (5-6%
  em 10x) validada de forma independente por um entrevistado
  quantitativo.

### O que parece ser verdade (padrão relevante, mas precisa de mais validação)

- O padrão "distribuidor 100% B2B" pode ser a regra geral do modelo
  Goodyear, não uma particularidade da Lubpar — mas isso só foi
  observado em 1 caso.
- A proporção de revendas "abertas" (perfil Menezes/JF) vs. "resistentes"
  (perfil Peregrina) pode não ser maioria/minoria clara — a amostra de 4
  é pequena demais para generalizar.
- O território de "taxa única fixa lastreada por terceiro" (Território
  1) parece o mais promissor entre as revendas, mas depende de validação
  de viabilidade econômica sem subsídio da fábrica.

### O que ainda não sabemos (sem evidência suficiente)

- Se a Goodyear teria apetite comercial/financeiro para participar como
  parceira de subsídio em qualquer solução.
- Como um distribuidor híbrido (que também atende consumidor final)
  navegaria as duas dores identificadas.
- Qual a real dinâmica financeira e de crédito de sub-revendas
  multimarca atendidas por distribuidores.
- Qual a real percepção do consumidor final sobre parcelamento/crédito
  no setor de pneus (só temos a visão do lojista).
- Se o território de garantia de crédito B2B (Território 3) é viável
  dentro do modelo de produto/regulatório atual da Propig.

### O que pode mudar a direção da solução

- Se a Goodyear **não tiver apetite** para subsidiar, os Territórios 1,
  2 e 4 (todos dependentes, em algum grau, de taxa mais barata que o
  mercado) perdem viabilidade econômica, e a Propig precisaria considerar
  se entra na cadeia sem subsídio (modelo de receita diferente) ou
  reconsiderar a priorização do Território 3 (garantia B2B), que
  depende menos de subsídio de terceiros e mais de um modelo de
  seguro/garantia.
- Se a amostra ampliada mostrar que a maioria das revendas Goodyear se
  parece mais com o perfil Peregrina (resistente) do que com Menezes/JF
  (aberto), isso reduziria o TAM endereçável do Território 1 e
  reforçaria a prioridade do Território 2 (prazo, não taxa/antecipação),
  que teve menos resistência filosófica.
- Se outros distribuidores Goodyear (não entrevistados) tiverem modelo
  híbrido, isso mudaria completamente a Seção 2 (estrutura da cadeia) e
  poderia revelar um arquétipo intermediário não capturado nesta
  pesquisa.

---

## 15. Implicações para o workshop

### A. Decisões que o workshop precisa ajudar a tomar

- Qual arquétipo priorizar primeiro: revenda oficial (Arquétipo B, mais
  evidência, mais parecido com o modelo Moura original) ou distribuidor
  (Arquétipo A, dor mais quantificada, mas produto mais distante do core
  atual)?
- Dentro do Arquétipo B, a proposta deve ser desenhada para o perfil
  "aberto" (Menezes/JF) como early adopter, ou precisa nascer já
  acessível ao perfil "resistente" (Peregrina)?
- Quem pagaria o subsídio necessário para viabilizar uma taxa
  competitiva (5-6%) — a Propig sozinha, a Goodyear, ou uma instituição
  financeira parceira? Essa pergunta não tem resposta nas entrevistas e
  precisa de uma conversa estratégica direta com a Goodyear antes de
  qualquer compromisso de produto.
- O Território 3 (garantia de crédito B2B para distribuidor) deve entrar
  no escopo deste projeto, ou é uma oportunidade adjacente a ser tratada
  separadamente, fora do timing atual?

### B. Tensões que precisam ser discutidas

- Prazo maior vs. taxa menor vs. desconto à vista maior — três lógicas
  de valor diferentes identificadas (Seção 11, Tensão 2) que
  provavelmente não podem ser resolvidas por um único produto sem
  configuração/flexibilidade.
- Automação total vs. flexibilidade de percentual no mecanismo de
  crédito para recompra — JF e Encruzilhada pedem controle, não
  automação cega.
- Foco em "resgatar vendas perdidas" (mensagem forte para Lubpar) vs.
  foco em "otimizar custo/margem" (mensagem mais adequada às revendas) —
  provavelmente exige discursos de valor diferentes por arquétipo.

### C. Hipóteses que vale explorar

- Hipótese de problema: distribuidores Goodyear fora desta amostra podem
  ter modelo híbrido (varejo + B2B), mudando a estrutura da cadeia
  mapeada.
- Hipótese de comportamento: revendas mais "quantitativas"/profissionais
  na gestão (BI próprio, CRM avançado, DRE detalhado) são
  sistematicamente mais receptivas a mecanismos financeiros novos,
  independente de porte ou região — vale testar se esse padrão se
  sustenta numa amostra maior.
- Hipótese de negócio: a Goodyear pode ter mais apetite para participar
  de um subsídio se a proposta vier conectada a geração de demanda (a
  dor nº 1 relatada) e não apenas como produto financeiro isolado.
- Hipótese de proposta de valor: talvez não exista uma "proposta
  Credimora para Goodyear" única, e sim dois produtos distintos — um
  para revenda (parcelamento/crédito ao consumidor) e outro para
  distribuidor (garantia de crédito B2B) — cada um com seu próprio
  caminho de validação e timing.
- Hipótese de mecanismo: um percentual configurável de "quanto da venda
  vira crédito para recompra" pode ser o desenho que resolve tanto a
  adesão (dá controle ao gestor) quanto o problema técnico do excedente
  (pneu vs. pneu+serviço).

### D. Perguntas ainda sem resposta

- A Goodyear tem histórico, apetite ou budget para subsidiar qualquer
  mecanismo financeiro na cadeia?
- Qual a proporção real de revendas "abertas" vs. "resistentes" na rede
  Goodyear nacional?
- Existe modelo híbrido de distribuidor (varejo + B2B) em alguma região?
- Qual seria o tratamento fiscal/contábil correto para um mecanismo de
  "crédito de venda virando crédito de recompra" (dúvida levantada por
  JF, não resolvida)?
- Qual a dinâmica de crédito e parcelamento de sub-revendas multimarca
  atendidas por distribuidores (não entrevistadas)?

### E. Evidências que deveriam estar visíveis no workshop

- **Quote de Lubpar** sobre "consignação disfarçada" — ilustra como um
  interlocutor de fora do projeto, sem indução, chega sozinho à mesma
  leitura estratégica que a Propig tem sobre o próprio Credimora — forte
  para validar a tese central perante o time.
- **Quote e cálculo de Menezes** sobre a taxa-alvo de 5-6% em 10x —
  única referência numérica concreta e validada da pesquisa, âncora para
  qualquer discussão de precificação.
- **Contraste direto Peregrina vs. JF/Menezes** sobre antecipação — bom
  gatilho de discussão para a pergunta "existe um único produto ou
  produtos configuráveis por perfil?".
- **Dado quantificado de Lubpar** (20% de vendas represadas por limite de
  crédito) — caso extremo que mostra o teto de oportunidade do
  Território 3, mesmo que ele não seja priorizado agora.
- **Tabela comparativa completa (Seção 7)** — para visualizar de forma
  rápida a heterogeneidade financeira entre os 5 casos.
- **A ausência total de subsídio Goodyear na cadeia hoje** — contraponto
  direto ao modelo Moura, útil para forçar a discussão sobre quem
  pagaria a conta antes de avançar no desenho de produto.

### F. O que não deveríamos decidir ainda

- **Decisão prematura**: comprometer-se com um desenho final de produto
  (ex.: "vamos replicar Flex/Sessão tal como é na Moura") antes de saber
  se a Goodyear tem apetite de subsídio. → **Informação que falta**:
  posição estratégica da própria Goodyear, que não foi capturada nesta
  pesquisa (todas as 5 entrevistas foram do lado do canal).
- **Decisão prematura**: escolher definitivamente entre priorizar
  Arquétipo A (distribuidor) ou Arquétipo B (revenda) com base apenas
  nesta amostra. → **Informação que falta**: amostra maior e mais
  representativa por tipo de ator, especialmente mais distribuidores e
  ao menos uma sub-revenda multimarca.
- **Decisão prematura**: fixar a taxa-alvo de 5-6% como meta de produto
  para toda a rede. → **Informação que falta**: validação com mais
  revendas — é uma referência de um único entrevistado, ainda que
  bem fundamentada.

---

## 16. Conclusões estratégicas

### Sobre o negócio

Aprendemos que o ecossistema Goodyear, ao contrário do que a hipótese
inicial (herdada do kickoff Moura) sugeria, não é uma cadeia única com
um distribuidor híbrido no meio — é, pelo menos na amostra coletada,
duas cadeias paralelas com pouca sobreposição: revenda oficial
direto-da-fábrica (consumidor final) e distribuidor B2B puro
(sub-revenda). Cada uma ganha dinheiro de forma diferente e tem uma
relação de risco/crédito diferente com o elo anterior e seguinte da
cadeia.

### Sobre os problemas

O problema mais estrutural e universal (pneu importado corroendo
margem/volume) está fora do alcance de qualquer solução financeira. O
problema mais diretamente conectado à lógica Credimora (descasamento de
prazo compra-vs-venda) é real e recorrente, mas **menos agudo e menos
uniforme** do que a dor original que motivou o Credimora na Moura — as
revendas já desenvolveram, cada uma a seu modo, formas de conviver com
esse descasamento (antecipação, prazo mais curto, otimização bancária),
com graus de eficiência e custo diferentes.

### Sobre os perfis

A diferença mais relevante entre as empresas não é porte, região ou
faturamento — é o **grau de sofisticação e abertura financeira do
gestor**. Esse fator explica melhor a receptividade ao conceito Propig
do que qualquer variável estrutural do negócio (número de lojas, mix de
produto, se antecipa ou não hoje).

### Sobre a Propig

As capacidades atuais da Propig (mecanismo tipo Flex/Sessão, crédito de
venda virando crédito de recompra) respondem bem ao Território 4 e,
parcialmente, ao Território 1 (taxa única) — mas exigem adaptação de
design (percentual configurável) para lidar com a diferença estrutural
entre o ticket da Moura (bateria, item único) e o ticket Goodyear
(pneu + serviço + peças, item composto).

### Sobre os limites da Propig atual

O problema mais quantificado e urgente da pesquisa (limite de crédito do
distribuidor, Lubpar) exige um tipo de produto — garantia/lastreamento de
crédito B2B — estruturalmente diferente do parcelamento ao consumidor
final que é o core reconhecível do Credimora. Perseguir esse território
provavelmente exige uma proposta de valor nova, não uma adaptação da
proposta existente.

### Sobre a Goodyear

Diferente da Moura, a Goodyear hoje não desempenha nenhum papel ativo de
subsídio ou participação financeira na cadeia — todo o risco de crédito é
absorvido individualmente por cada elo. Isso significa que qualquer
solução financeira competitiva (taxa abaixo de mercado) provavelmente
depende de convencer a Goodyear a assumir, pela primeira vez, um papel
que ela não tem hoje — o que é tanto o maior risco quanto a maior
oportunidade estratégica identificada nesta pesquisa.

### Sobre a pesquisa

Ainda precisamos descobrir: a posição da própria Goodyear (não
capturada, pesquisa foi 100% do lado do canal); a representatividade dos
perfis "abertos" vs. "resistentes" numa amostra maior; a existência ou
não de distribuidores híbridos; e a perspectiva de sub-revendas
multimarca atendidas por distribuidores.

### Sobre o workshop — as discussões mais importantes

1. A Goodyear tem apetite/budget para subsidiar uma solução financeira
   na cadeia, como a Moura faz hoje?
2. Priorizamos o Arquétipo A (distribuidor, dor mais aguda, produto mais
   distante) ou o Arquétipo B (revenda, dor mais moderada, produto mais
   próximo do core atual)?
3. Existe uma única proposta de valor para a rede Goodyear, ou
   precisamos de, no mínimo, duas propostas configuráveis (mais prazo
   vs. menos taxa)?
4. Como desenhar o mecanismo de "crédito para recompra" com
   flexibilidade de percentual, dado que o ticket Goodyear é composto
   (pneu + serviço + peças), diferente do ticket único da Moura
   (bateria)?
5. Vale a pena investigar comercialmente, antes de qualquer decisão de
   produto, o apetite real da Goodyear para um papel de subsídio ativo?
6. O território de garantia de crédito B2B para distribuidor (Território
   3) entra no escopo deste projeto ou fica para uma fase/frente
   separada?
7. Como o discurso de venda deveria conectar a proposta financeira à dor
   nº 1 relatada (geração de demanda/marketing), já que nenhuma empresa
   citou crédito como primeira resposta espontânea?
8. Que amostra adicional (mais distribuidores, sub-revendas multimarca,
   revendas menores/regiões diferentes) precisamos antes de convergir
   para um desenho final de produto?
9. Qual tratamento fiscal/contábil o mecanismo de crédito não-caixa
   precisa ter, e isso muda a viabilidade ou a comunicação do produto?
10. Dado que a receptividade parece mais ligada ao perfil do gestor do
    que ao estado financeiro da empresa, como o discurso comercial e o
    processo de venda devem se adaptar para identificar e priorizar os
    "perfis abertos" primeiro?
