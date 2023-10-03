# NOTAÇÃO POSICIONAL
## CONCEITO:
A notação posicional é um sistema de representação de números que depende da posição dos dígitos em relação a uma base específica. Esse sistema é amplamente utilizado em matemática e computação para representar números em diferentes bases, como a base decimal (base 10), base binária (base 2), base octal (base 8), base hexadecimal (base 16), entre outras. A notação posicional é fundamental para compreender como diferentes bases numéricas funcionam.

Aqui estão os principais conceitos relacionados à notação posicional:

1. **Base Numérica (Radix)**: A base numérica, também conhecida como "radix," é o número de dígitos diferentes que são usados em um sistema de numeração. Por exemplo, a base decimal tem 10 dígitos (0 a 9), enquanto a base binária tem 2 dígitos (0 e 1).

2. **Dígitos**: Os dígitos são os símbolos usados para representar números em um sistema de numeração. Na base decimal, os dígitos são 0, 1, 2, 3, 4, 5, 6, 7, 8 e 9. Na base binária, os dígitos são 0 e 1, e assim por diante.

3. **Posição de Dígitos**: A posição dos dígitos em um número é crítica para o seu valor. Cada posição representa uma potência da base. Na base decimal, por exemplo, a posição mais à direita representa a potência de 10^0 (1), a próxima à esquerda representa a potência de 10^1 (10), a próxima representa a potência de 10^2 (100), e assim por diante.

4. **Valor de um Número**: O valor de um número em notação posicional é calculado somando-se o produto de cada dígito pelo valor da base elevado à sua posição. Por exemplo, na base decimal, o número 123 é calculado como 1*10^2 + 2*10^1 + 3*10^0, o que resulta em 100 + 20 + 3 = 123.

5. **Conversão entre Bases**: Você pode converter números de uma base para outra alterando a base de representação e reescrevendo os dígitos nas novas posições. Existem algoritmos específicos para realizar essas conversões.

6. **Representação de Ponto Flutuante**: Além de números inteiros, a notação posicional também é usada para representar números reais (números de ponto flutuante) em computação, onde se utiliza uma mantissa e um expoente.

A notação posicional é uma ferramenta fundamental para entender como os números são representados e manipulados em sistemas de numeração diferentes. À medida que você avança em seu curso de bases numéricas na computação, você provavelmente estudará esses conceitos em mais detalhes e aprenderá a realizar operações aritméticas, conversões e outras manipulações em várias bases numéricas.

## SISTEMA DE UNIDADES:
Os sistemas de unidades numéricas, como centenas, dezenas e unidades, são uma parte fundamental da notação posicional usada na base decimal (base 10). Eles são usados para representar números inteiros de forma clara e organizada, permitindo que você compreenda facilmente o valor de cada dígito em um número. Vamos explorar essas unidades numéricas em detalhes:

1. **Unidade (ou Ones)**: A unidade é a posição mais à direita em um número decimal. Ela representa a quantidade de unidades individuais. Por exemplo, no número 123, a unidade é 3, o que significa que há três unidades individuais.

2. **Dezena (ou Tens)**: A dezena é a posição à esquerda da unidade. Ela representa a quantidade de grupos de dez. No número 123, a dezena é 2, o que significa que há duas dezenas, ou seja, 20 unidades.

3. **Centena (ou Hundreds)**: A centena é a posição à esquerda da dezena. Ela representa a quantidade de grupos de cem. No número 123, a centena é 1, o que significa que há uma centena, ou seja, 100 unidades.

4. **Milhar (ou Thousands)**: Além das unidades, dezenas e centenas, a notação decimal continua com o milhar, que é a posição à esquerda da centena. Ela representa a quantidade de grupos de mil. No número 1234, o milhar é 1, o que significa que há um milhar, ou seja, 1.000 unidades.

Essas unidades numéricas se estendem ainda mais à esquerda, com dezenas de milhar, centenas de milhar, milhões, bilhões e assim por diante, seguindo uma sequência que cresce em potências de 10. Isso permite que números muito grandes sejam representados de maneira clara e fácil de entender.

É importante notar que o sistema de unidades numéricas é específico para a base decimal (base 10) e não se aplica diretamente a outras bases numéricas, como a base binária (base 2), onde as posições representam potências de 2. No entanto, o conceito de posicionalidade ainda se aplica, e os sistemas de unidades em outras bases seguem um padrão semelhante, mas com valores diferentes.

Dominar o sistema de unidades numéricas é fundamental para a compreensão de números inteiros e para realizar operações aritméticas em notação decimal, como adição, subtração, multiplicação e divisão.

## BASE DECIMAL:
A base decimal, também conhecida como base 10, é o sistema numérico mais comum usado no dia a dia. Neste sistema, temos dez dígitos diferentes, que são 0, 1, 2, 3, 4, 5, 6, 7, 8 e 9. A base decimal é chamada de "base 10" porque cada posição de dígito representa uma potência de 10. Aqui estão alguns conceitos importantes relacionados à base decimal:

1. **Dígitos**: Os dígitos são os símbolos usados para representar números na base decimal. Os números são formados combinando esses dígitos em diferentes ordens. Por exemplo, o número 123 usa os dígitos 1, 2 e 3.

2. **Posição de Dígitos**: A posição dos dígitos em um número decimal é crítica para o seu valor. Cada posição representa uma potência de 10. A posição mais à direita representa a potência de 10^0 (que é 1), a próxima à esquerda representa a potência de 10^1 (que é 10), a próxima representa a potência de 10^2 (que é 100), e assim por diante.

3. **Valor de um Número**: O valor de um número na base decimal é calculado somando-se o produto de cada dígito pelo valor da base (10) elevado à sua posição. Por exemplo, o número 123 é calculado como 1 * 10^2 + 2 * 10^1 + 3 * 10^0, o que resulta em 100 + 20 + 3 = 123.

4. **Conversão para Outras Bases**: Para converter números da base decimal para outras bases numéricas, como a base binária (base 2), base octal (base 8) ou base hexadecimal (base 16), é necessário dividir o número repetidamente pela base de destino e registrar os restos. Os restos formam a representação na base desejada.

5. **Operações Aritméticas**: A base decimal é usada para realizar operações aritméticas padrão, como adição, subtração, multiplicação e divisão. As regras dessas operações são aplicadas da mesma forma em qualquer base numérica.

A base decimal é amplamente usada em nossa vida cotidiana, em transações financeiras, medições, cálculos matemáticos e muitas outras áreas. É o sistema numérico com o qual a maioria das pessoas está mais familiarizada, e é fundamental para compreender a matemática e a ciência em geral.

## POTENCIAÇÃO:
A potenciação é uma operação matemática que envolve a elevação de um número, chamado de "base," a uma potência, que é um número que indica quantas vezes a base deve ser multiplicada por si mesma. A potenciação é representada por um símbolo chamado de "expoente" ou "potência." A notação padrão para potenciação é a seguinte:

**Base^Expoente**

Aqui estão os principais conceitos relacionados à potenciação:

1. **Base**: A base é o número que está sendo elevado a uma potência. É o número que você deseja multiplicar consigo mesmo várias vezes.

2. **Expoente**: O expoente é um número que indica quantas vezes a base deve ser multiplicada por si mesma. Ele diz quantos fatores da base estão sendo multiplicados juntos.

3. **Potência**: O resultado da operação de potenciação é chamado de "potência" e é o valor numérico resultante da multiplicação da base por ela mesma, de acordo com o expoente.

A fórmula geral para a potenciação é a seguinte:

**Base^Expoente = Resultado**

Por exemplo:

- 2^3 = 2 * 2 * 2 = 8
- 5^2 = 5 * 5 = 25
- 10^4 = 10 * 10 * 10 * 10 = 10,000

A potenciação é uma operação fundamental em matemática e é usada em muitos contextos diferentes, incluindo:

1. **Cálculos de Área e Volume**: A potenciação é usada para calcular áreas de figuras geométricas tridimensionais (por exemplo, o volume de um cubo) e bidimensionais (por exemplo, a área de um quadrado).

2. **Crescimento Exponencial**: A potenciação é fundamental para entender o crescimento exponencial, que ocorre quando uma quantidade aumenta ou diminui rapidamente à medida que o tempo passa.

3. **Notação Científica**: Números muito grandes ou muito pequenos são frequentemente expressos em notação científica, que usa a potenciação para representar esses valores de forma mais compacta e compreensível.

4. **Matemática Financeira**: A potenciação é usada em cálculos financeiros, como juros compostos, que envolvem crescimento exponencial ao longo do tempo.

5. **Ciência e Engenharia**: A potenciação é usada em muitas equações e modelos matemáticos em disciplinas científicas e de engenharia.

6. **Programação**: A potenciação é uma operação comum em programação, e as linguagens de programação geralmente fornecem operadores para realizar potenciação.

Lembre-se de que as regras de potenciação incluem propriedades importantes, como a propriedade do produto de potências de mesma base, a propriedade do quociente de potências de mesma base e a propriedade da potência de uma potência. Essas regras ajudam a simplificar cálculos envolvendo potências.

## DIFERENÇA ENTRE SISTEMA DECIMAL E BINARIO:
O sistema decimal e o sistema binário são dois sistemas numéricos diferentes usados para representar números. Eles diferem na base numérica em que estão fundamentados, bem como nos dígitos disponíveis para representação. Aqui estão as principais diferenças entre o sistema decimal e o sistema binário:

**Sistema Decimal (Base 10):**

1. **Base Numérica**: O sistema decimal é base 10, o que significa que tem 10 dígitos diferentes, de 0 a 9.

2. **Dígitos**: Os dígitos no sistema decimal são 0, 1, 2, 3, 4, 5, 6, 7, 8 e 9.

3. **Posicionamento**: Cada posição em um número decimal representa uma potência de 10. A posição mais à direita é 10^0 (1), a próxima à esquerda é 10^1 (10), a próxima é 10^2 (100) e assim por diante.

4. **Uso Comum**: O sistema decimal é o sistema numérico padrão usado em nosso dia a dia. A maioria das calculadoras e dispositivos eletrônicos que usamos utiliza o sistema decimal.

5. **Representação de Frações**: O sistema decimal é usado para representar números racionais (números inteiros e frações), tornando-o apropriado para cálculos financeiros e de medição.

**Sistema Binário (Base 2):**

1. **Base Numérica**: O sistema binário é base 2, o que significa que tem apenas 2 dígitos diferentes, 0 e 1.

2. **Dígitos**: Os dígitos no sistema binário são 0 e 1. Eles representam o estado ligado (1) e desligado (0) em sistemas eletrônicos.

3. **Posicionamento**: Cada posição em um número binário representa uma potência de 2. A posição mais à direita é 2^0 (1), a próxima à esquerda é 2^1 (2), a próxima é 2^2 (4) e assim por diante.

4. **Uso em Computação**: O sistema binário é amplamente usado em computação e eletrônica digital. Os computadores usam o sistema binário internamente para processar dados e armazenar informações.

5. **Compactação de Dados**: O sistema binário é eficaz para representar informações usando apenas dois estados (0 e 1), o que é útil para armazenamento e transmissão eficiente de dados.

6. **Conversão**: A conversão entre decimal e binário é comum em programação e eletrônica. Ela envolve dividir repetidamente um número por 2 e registrar os restos até que o quociente seja 0 para converter de decimal para binário e vice-versa.

Embora o sistema decimal seja mais familiar para a maioria das pessoas e seja usado em situações cotidianas, o sistema binário é essencial para a computação moderna e a eletrônica digital. É a base para a representação interna de informações em computadores, onde tudo é eventualmente convertido em sequências de 0s e 1s para processamento.

## COMO CONTAR EM BINARIO?
Contar em binário é um processo de representação numérica usando apenas dois dígitos: 0 e 1. Cada posição em um número binário representa uma potência de 2, assim como em nosso sistema decimal, onde cada posição representa uma potência de 10. Aqui está um guia passo a passo sobre como contar em binário:

1. **Comece com 0**: O primeiro número binário é sempre 0. Isso é semelhante ao sistema decimal, onde começamos com 0 e depois contamos até 9 antes de passar para a próxima posição.

2. **Incremente a posição da direita para a esquerda**: Assim como no sistema decimal, quando você atinge o maior dígito (1), você incrementa a próxima posição à esquerda. No binário, você só tem dois dígitos disponíveis, 0 e 1.

3. **Contagem de 0 a 1**: A contagem binária de 0 a 1 é simples. Basta começar com 0 e, em seguida, mudar para 1:

   - 0
   - 1

4. **Contagem de 1 a 2**: Quando você alcança 1 e precisa contar até 2, você muda o dígito da direita para 0 e incrementa o dígito da esquerda:

   - 10
   - 11

5. **Contagem de 2 a 3**: Quando você alcança 2 e precisa contar até 3, você muda o dígito da direita para 1:

   - 10
   - 11
   - 100
   - 101

6. **Continue o processo**: Você continua esse processo, mudando os dígitos da direita para a esquerda sempre que necessário, assim como fazemos no sistema decimal. Aqui está uma contagem binária de 0 a 15:

   - 0
   - 1
   - 10
   - 11
   - 100
   - 101
   - 110
   - 111
   - 1000
   - 1001
   - 1010
   - 1011
   - 1100
   - 1101
   - 1110
   - 1111

Você pode continuar esse padrão para contar em binário para números maiores, adicionando dígitos à esquerda conforme necessário. A contagem binária é fundamental na programação e na eletrônica digital, onde é usada para representar números, endereços de memória e estados em sistemas binários.

## CONTAGEM BINARIA COM PONTUAÇÃO:
Para realizar a contagem binária com pontuação (ou seja, usando vírgulas ou pontos para separar grupos de dígitos binários em unidades mais gerenciáveis), você pode usar a mesma lógica de contagem binária simples, mas agrupar os dígitos binários em conjuntos de tamanho específico. Isso pode tornar a leitura de números binários mais longos mais fácil e organizada.

Vamos supor que você queira contar em binário com grupos de 4 dígitos binários separados por vírgulas. Aqui está um exemplo de como fazer isso:

1. **Contagem de 0 a 15 em grupos de 4 dígitos**:

   - 0000
   - 0001
   - 0010
   - 0011
   - 0100
   - 0101
   - 0110
   - 0111
   - 1000
   - 1001
   - 1010
   - 1011
   - 1100
   - 1101
   - 1110
   - 1111

Neste exemplo, os dígitos binários estão agrupados em conjuntos de quatro, separados por vírgulas, para facilitar a leitura. Cada grupo representa um número decimal diferente. À medida que você continua contando, os grupos de quatro dígitos vão se repetindo.

Você pode ajustar o tamanho dos grupos de acordo com suas necessidades. Por exemplo, se preferir grupos de 8 dígitos binários, a contagem binária ficaria assim:

1. **Contagem de 0 a 255 em grupos de 8 dígitos**:

   - 00000000
   - 00000001
   - 00000010
   - ...
   - 11111110
   - 11111111

Essa notação com pontuação é especialmente útil ao trabalhar com endereços binários ou números binários longos em eletrônica digital e programação, pois ajuda a manter a clareza e a organização ao lidar com números binários extensos.

## CONVERTER DE DECIMAL PARA BINÁRIO:
Converter números decimais para binários envolve a representação do número decimal em seu equivalente na base binária (base 2). Para fazer isso, você pode seguir os passos a seguir:

**Passo 1**: Divisão Sucessiva por 2

1. Comece com o número decimal que deseja converter para binário.

2. Divida o número decimal por 2 (a base binária) e registre o quociente e o resto.

3. Anote o resto como o dígito binário mais à direita.

4. Use o quociente como o novo número decimal e repita o processo até que o quociente seja igual a 0.

**Passo 2**: Leia os Dígitos Binários de Trás para Frente

5. Os dígitos binários que você anotou ao longo do processo, lidos da direita para a esquerda, formam a representação binária do número decimal.

Aqui está um exemplo:

Vamos converter o número decimal 19 em binário:

**Passo 1**:
```
19 ÷ 2 = 9, resto 1 (anote 1)
9 ÷ 2 = 4, resto 1 (anote 1)
4 ÷ 2 = 2, resto 0 (anote 0)
2 ÷ 2 = 1, resto 0 (anote 0)
1 ÷ 2 = 0, resto 1 (anote 1)
```

**Passo 2**:
Lendo os dígitos binários de trás para frente, obtemos 10011.

Portanto, o número decimal 19 em binário é igual a 10011.

Aqui estão mais alguns exemplos para ilustrar:

- Decimal 10 em binário:  
```
10 ÷ 2 = 5, resto 0
5 ÷ 2 = 2, resto 1
2 ÷ 2 = 1, resto 0
1 ÷ 2 = 0, resto 1
```
Lendo os dígitos binários de trás para frente: 1010

- Decimal 30 em binário:
```
30 ÷ 2 = 15, resto 0
15 ÷ 2 = 7, resto 1
7 ÷ 2 = 3, resto 1
3 ÷ 2 = 1, resto 1
1 ÷ 2 = 0, resto 1
```
Lendo os dígitos binários de trás para frente: 11110

Agora você sabe como converter números decimais em binários usando a divisão sucessiva por 2. Este método é bastante simples e eficaz para realizar essa conversão.