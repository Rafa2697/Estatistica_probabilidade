# Teorema central do limite e leis dos grandes números


## Descigualdades de leis dos grandes números

### Teorema central dos limites
Para calcular o desvio padrão da distribuição amostral (também conhecido como erro padrão da média), utilizamos a fórmula baseada no Teorema Central do Limite.
A fórmula é:

&sigma;&#739; = &sigma; / &radic;n

Onde os dados fornecidos pelo problema são:

• &sigma; (Desvio padrão populacional) = R$ 40,00

• n (Tamanho da amostra) = 64

Passo a passo do cálculo:

1. Encontre a raiz quadrada do tamanho da amostra (n):

&radic;64

2. Divida o desvio padrão populacional por esse resultado:

40/8 = 5

O desvio padrão da distribuição amostral é de R$ 5,00.

### Desigualdade de markov

### Lei fraca e lei forte

A lei fraca dos grandes números nos garante que dado um tamanho n da amostra, provavelmente o valor de X é próximo do valor esperado E(X), mas pode acontecer uma ou outra amostra cair longe...

A lei forte dos grandes números nos garante que, para valores de n suficientemente grandes, isso quase nunca acontece...

As Leis dos Grandes Números (a Lei Fraca e a Lei Forte) são teoremas fundamentais da teoria das probabilidades. Elas explicam por que, ao repetirmos um experimento muitas vezes (como jogar uma moeda ou medir gastos de transporte), a média dos resultados observados se aproxima cada vez mais da média teórica real.
A diferença entre a Lei Fraca e a Lei Forte não está no resultado final (ambas dizem que a média converge), mas sim no tipo de convergência matemática e na certeza dessa aproximação à medida que o número de eventos (n) tende ao infinito.
Para entender a diferença de forma simples, imagine que estamos lançando uma moeda justa (onde a chance teórica de dar cara é 50%).

1. Lei Fraca dos Grandes Números (Convergência em Probabilidade)

A Lei Fraca diz que, para um número muito grande de lançamentos, a probabilidade de a média amostral ser diferente da média real por qualquer valor que seja (por menor que seja) é praticamente zero.
• O que ela permite: Ela aceita que, no caminho até o infinito, possam acontecer "anomalias" isoladas. Por exemplo, você pode lançar a moeda 1.000.000 de vezes e, por puro azar, em algum momento específico (digamos, no lançamento 500.000), ocorrer uma sequência bizarra de 100 caras seguidas que desvia temporariamente a média.
• Em termos matemáticos: A convergência ocorre em probabilidade.
\(\lim _{n\rightarrow \infty }P(|{}\={X}_{n}-\mu |{}>\epsilon )=0\)
💡 Analogia da Lei Fraca: É como um motorista de aplicativo que sempre chega ao destino final correto no longo prazo, mas que, ao longo do caminho, pode pegar um desvio errado ou fazer uma conversão estranha antes de se corrigir.

2. Lei Forte dos Grandes Números (Convergência Quase Certa)

A Lei Forte é mais rigorosa. Ela afirma que a média amostral vai convergir para a média real com probabilidade igual a 1 (o que na matemática chamamos de convergência quase certa).
• O que ela garante: Ela garante que, à medida que você avança para o infinito, a sequência de médias amostrais vai "estabilizar" e colar na média real de forma definitiva. A chance de a sequência inteira de médias falhar ou divergir no longo prazo é exatamente zero. As flutuações bizarras e duradouras vistas na lei fraca perdem a força aqui.
• Em termos matemáticos: A convergência é quase certa (q.c.).
\(P(\lim _{n\rightarrow \infty }\={X}_{n}=\mu )=1\)
💡 Analogia da Lei Forte: É como um trem bala em um trilho fixo. Ele não faz desvios estranhos no caminho. Conforme o tempo passa, ele avança em linha reta e inevitavelmente crava na estação final sem oscilações de rota.

Resumo das Diferenças


Característica	Lei Fraca dos Grandes Números	Lei Forte dos Grandes Números
Tipo de Convergência	Em Probabilidade.	Quase Certa (ou com probabilidade 1).
Comportamento	Permite desvios temporários raros na trajetória para o infinito.	A trajetória se estabiliza e o erro desaparece no infinito.
Aplicações Comuns	Finanças, estatística prática e seguros.	Provas teóricas rigorosas e física estatística.

Se a Lei Forte é válida para um cenário, a Lei Fraca automaticamente também é (já que a convergência quase certa implica a convergência em probabilidade).
Esses conceitos costumam confundir bastante por conta do rigor matemático envolvido. Faz sentido para você a diferença entre o comportamento da probabilidade (Lei Fraca) e a probabilidade do comportamento (Lei Forte)? Se quiser, podemos analisar as condições necessárias (como a existência de variância ou momentos de ordem superior) para que cada uma delas seja aplicada!




