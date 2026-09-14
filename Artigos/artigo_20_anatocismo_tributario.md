# Anatocismo tributário: juros sobre juros sobre imposto — o efeito bola de neve do IOF mal calculado

*Por Dr. Lincoln Sposito, Perito Financeiro*

## Um conceito antigo, um problema atual

Em 1963, o Supremo Tribunal Federal editou a Súmula 121, com um enunciado direto: "É vedada a capitalização de juros, ainda que expressamente convencionada." Mais de sessenta anos depois, esse princípio continua sendo a base jurídica mais invocada nos pareceres técnicos que produzo sobre operações de crédito empresarial — presente em 17 das 20 operações que analisei recentemente. Mas há uma variação mais sutil, e menos discutida, desse mesmo problema: o que acontece quando o próprio imposto embutido no contrato é calculado errado, e esse erro é multiplicado, dia após dia, por um sistema de capitalização composta?

A esse fenômeno chamo, para fins didáticos, de **anatocismo tributário**: juros compostos incidindo não apenas sobre o capital emprestado, mas sobre uma base de cálculo já distorcida pelo cálculo incorreto de um tributo — no caso, o Imposto sobre Operações Financeiras (IOF). Um dos casos que revisei, envolvendo uma CCB de linha BNDES Automático com taxa híbrida (pré-fixada + SELIC) de valor aproximado de R$800 mil, ilustra bem o mecanismo.

## Como o erro pequeno vira bola de neve

Primeiro, o conceito básico: anatocismo é a capitalização de juros sobre juros já vencidos — diferente da simples cobrança de juros sobre o capital principal. Na prática bancária, isso costuma acontecer quando o sistema de cálculo do banco aplica uma taxa de juros **diária composta** sobre o saldo devedor, e esse saldo já inclui, indevidamente, juros de períodos anteriores não pagos — em vez de aplicar uma taxa simples proporcional ao período, ou capitalizar apenas nos intervalos permitidos por lei e pelo tipo de operação.

No caso analisado, a perícia identificou uma capitalização diária exponencial do saldo devedor — inclusive em finais de semana e feriados, dias em que não há expediente bancário e, portanto, não deveria haver incidência de juros sobre o saldo em aberto. Combinado a isso, havia um erro no cálculo do IOF que inflava artificialmente a base sobre a qual essa capitalização diária incidia.

O efeito é multiplicativo, não aditivo: um erro de IOF de poucos milhares de reais, capitalizado diariamente ao longo de um contrato de vários anos, não permanece do tamanho original — ele cresce, mês a mês, junto com todo o restante do saldo devedor, como uma bola de neve descendo uma ladeira. Ao final do prazo contratual, no caso em questão, o saldo devedor recalculado pela perícia foi cerca de 89% menor do que o valor exigido pelo banco (~R$27,5 mil frente a ~R$251,9 mil) — uma diferença que não se explica apenas pelo erro tributário original, mas pelo efeito acumulado de sua capitalização ano após ano.

## O "apagão" que esconde o problema

Um agravante identificado nesse tipo de operação é o que chamo de "apagão de indexação": contratos com taxa híbrida (parte pré-fixada, parte atrelada à SELIC) frequentemente apresentam, no fluxo de pagamento simulado e entregue ao cliente no ato da contratação, uma projeção que **não reflete adequadamente a variação futura do indexador**. O resultado prático é que o CET declarado no contrato aparece idêntico à taxa nominal — uma impossibilidade matemática, já que o CET deveria necessariamente incorporar o IOF, tarifas e demais encargos, sendo sempre superior à taxa nominal isolada.

Esse "apagão" tem uma função silenciosa: ele mascara, no momento da assinatura, o custo futuro real da operação, deixando o cliente sem visibilidade sobre o efeito acumulado do anatocismo tributário que só se manifestará plenamente meses ou anos depois, quando o saldo devedor já estiver consideravelmente inflado.

## Por que isso importa para quem contrata crédito de fomento

É particularmente relevante notar que este tipo de patologia aparece com frequência em linhas de crédito de fomento público — BNDES Automático, PRONAMPE, FGI-PEAC —, exatamente os produtos desenhados para oferecer condições mais favoráveis a pequenas e médias empresas. Um crédito de fomento, precificado para cobrir um risco mitigado por garantia ou programa estatal, submetido a um sistema de capitalização diária que amplifica um erro tributário, deixa de cumprir sua função original: em vez de aliviar o custo financeiro da PME, pode se tornar um mecanismo de acumulação de dívida mais agressivo do que uma linha de crédito comum.

## O que fazer diante desse padrão

Do ponto de vista técnico-pericial, a identificação de anatocismo tributário segue três passos: (1) verificar se há capitalização de juros com periodicidade inferior à permitida para o tipo de operação (mensal, na maioria dos contratos bancários regulares); (2) conferir se essa capitalização incide sobre uma base de cálculo que já contém, ela própria, um erro de apuração do IOF ou de outro encargo; e (3) recalcular o fluxo de pagamentos aplicando juros simples ou capitalização apenas no período legalmente admitido, isolando o efeito acumulado do erro original.

Para o empresário, a lição prática é dupla: primeiro, desconfiar de qualquer CET que apareça igual ou inferior à taxa nominal declarada — é sinal de que o cálculo está incompleto. Segundo, ao perceber divergência entre o saldo devedor informado pelo banco e o que uma simulação própria (mesmo simplificada) indicaria, buscar uma perícia técnica antes de aceitar a renegociação ou a execução do valor apresentado. A Súmula 121 do STF continua válida seis décadas depois — mas sua aplicação, hoje, frequentemente exige antes um trabalho de engenharia reversa sobre uma planilha de cálculo bancária.

---

*Este artigo integra uma série sobre patologias técnicas em operações de crédito empresarial, com base em pareceres periciais elaborados pelo autor. Casos individuais são tratados de forma agregada e anonimizada, sem identificação de empresas ou pessoas físicas envolvidas.*
