# NUMEROS OCTAIS E HEXADECIMAIS
## CONCEITO
Os números octais e hexadecimais são sistemas de numeração usados em computação e matemática para representar números de forma mais compacta e legível do que o sistema decimal. Eles são baseados em potências de 8 (octal) e 16 (hexadecimal) e são amplamente usados em programação e eletrônica digital.

Aqui estão os conceitos básicos de números octais e hexadecimais:

**Números Octais (Base 8):**
- **Dígitos:** Os números octais usam os dígitos de 0 a 7.
- **Base:** Base 8 significa que cada posição em um número octal representa uma potência de 8.
- **Representação:** Assim como em sistemas de numeração, os números octais podem ser representados em notação posicional. Por exemplo, 14 em octal é representado como 16 em decimal.
- **Uso:** Os números octais são usados em programação e eletrônica, especialmente em sistemas legados ou em sistemas de permissões de arquivos no Unix/Linux.

**Números Hexadecimais (Base 16):**
- **Dígitos:** Os números hexadecimais usam os dígitos de 0 a 9 e as letras de A a F (ou a-f) para representar os números de 10 a 15.
- **Base:** Base 16 significa que cada posição em um número hexadecimal representa uma potência de 16.
- **Representação:** Da mesma forma que os números octais, os números hexadecimais podem ser representados em notação posicional. Por exemplo, 1A em hexadecimal é igual a 26 em decimal.
- **Uso:** Os números hexadecimais são amplamente usados em programação, eletrônica digital e representação de cores em sistemas de computador. São especialmente úteis para representar endereços de memória, valores de registros e representações compactas de dados binários.

Comparação entre Decimal, Octal e Hexadecimal:

- **Decimal (Base 10):** Usado em matemática cotidiana e é o sistema numérico padrão. Dígitos de 0 a 9.

- **Octal (Base 8):** Usado em programação Unix/Linux e sistemas legados. Dígitos de 0 a 7.

- **Hexadecimal (Base 16):** Usado em programação, eletrônica digital e representação de cores em computação. Dígitos de 0 a 9 e letras A a F (ou a-f).

A conversão entre decimal, octal e hexadecimal envolve a representação de números em suas respectivas bases e a manipulação de dígitos de acordo com as potências apropriadas. Essas bases são importantes na programação de computadores, onde a manipulação eficiente de números binários é comum.

## CONVERTENDO OCTAL <> DECIMAL:
A conversão entre números octais (base 8) e números decimais (base 10) envolve a representação de um número em uma base e sua conversão para outra base. Vou explicar como fazer isso nos dois sentidos: de octal para decimal e de decimal para octal.

**De Octal para Decimal:**

Para converter um número octal em decimal, siga os seguintes passos:

1. Comece do dígito mais à direita do número octal.

2. Atribua a cada dígito octal um valor posicional, começando por 1 para o dígito à direita e dobrando o valor posicional para cada dígito subsequente.

3. Multiplique cada dígito octal pelo valor posicional atribuído e some esses produtos.

4. Continue somando os produtos para cada dígito octal, indo da direita para a esquerda.

**Exemplo: Converter o octal 345 para decimal:**

```
5 * 1 = 5
4 * 8 = 32
3 * 64 = 192
```

Agora, some os produtos: 5 + 32 + 192 = 229.

Portanto, o octal 345 é igual a 229 em decimal.

**De Decimal para Octal:**

Para converter um número decimal em octal, você pode usar o método de divisão sucessiva por 8. Siga os seguintes passos:

1. Divida o número decimal por 8 e registre o quociente e o resto.

2. Anote o resto como o dígito mais à direita do número octal.

3. Use o quociente como o novo número decimal e repita os passos 1 e 2 até que o quociente seja igual a zero.

4. Leia os dígitos octais da direita para a esquerda para obter o número octal completo.

**Exemplo: Converter o decimal 229 para octal:**

```
229 ÷ 8 = 28, resto 5
28 ÷ 8 = 3, resto 4
3 ÷ 8 = 0, resto 3
```

Agora, leia os dígitos octais da direita para a esquerda: 345.

Portanto, o decimal 229 é igual a 345 em octal.

Esses são os métodos para converter números entre as bases octal e decimal. Eles são úteis em programação e eletrônica, especialmente quando se lida com sistemas que usam base 8, como o Unix/Linux, ou para representações compactas de dados.

## CONVERTENDO HEXADECIMAL <> DECIMAL:
A conversão entre números hexadecimais (base 16) e números decimais (base 10) envolve a representação de um número em uma base e sua conversão para outra base. Vou explicar como fazer isso nos dois sentidos: de hexadecimal para decimal e de decimal para hexadecimal.

**De Hexadecimal para Decimal:**

Para converter um número hexadecimal em decimal, siga os seguintes passos:

1. Comece do dígito mais à direita do número hexadecimal.

2. Atribua a cada dígito hexadecimal um valor posicional, começando por 1 para o dígito à direita e multiplicando o valor posicional por 16 para cada dígito subsequente.

3. Converta os dígitos hexadecimais A, B, C, D, E e F para os valores decimais correspondentes: A = 10, B = 11, C = 12, D = 13, E = 14 e F = 15.

4. Multiplique cada dígito hexadecimal pelo valor posicional atribuído e some esses produtos.

5. Continue somando os produtos para cada dígito hexadecimal, indo da direita para a esquerda.

**Exemplo: Converter o hexadecimal 1A3 para decimal:**

```
3 * 1 = 3
A * 16 = 10 * 16 = 160
1 * 256 = 256
```

Agora, some os produtos: 3 + 160 + 256 = 419.

Portanto, o hexadecimal 1A3 é igual a 419 em decimal.

**De Decimal para Hexadecimal:**

Para converter um número decimal em hexadecimal, você pode usar o método de divisão sucessiva por 16. Siga os seguintes passos:

1. Divida o número decimal por 16 e registre o quociente e o resto.

2. Se o resto for um valor entre 10 e 15, substitua-o pelas letras A, B, C, D, E ou F, respectivamente.

3. Anote o resto como o dígito mais à direita do número hexadecimal.

4. Use o quociente como o novo número decimal e repita os passos 1 a 3 até que o quociente seja igual a zero.

5. Leia os dígitos hexadecimais da direita para a esquerda para obter o número hexadecimal completo.

**Exemplo: Converter o decimal 419 para hexadecimal:**

```
419 ÷ 16 = 26, resto 3
26 ÷ 16 = 1, resto 10 (que é A em hexadecimal)
1 ÷ 16 = 0, resto 1
```

Agora, leia os dígitos hexadecimais da direita para a esquerda: 1A3.

Portanto, o decimal 419 é igual a 1A3 em hexadecimal.

Esses são os métodos para converter números entre as bases hexadecimal e decimal. Eles são úteis em programação, eletrônica e na representação de cores em sistemas de computador.

## CONVERTER HEXADECIMAL <> BINARIO:
A conversão entre números binários (base 2) e números hexadecimais (base 16) envolve uma representação intermediária em números decimais (base 10). Aqui estão os passos para converter de binário para hexadecimal e vice-versa:

**De Binário para Hexadecimal:**

1. Primeiro, agrupe os dígitos binários em grupos de quatro, começando pela direita. Se o número de dígitos binários não for um múltiplo de quatro, adicione zeros à esquerda para fazer grupos de quatro.

2. Em seguida, converta cada grupo de quatro dígitos binários em seu equivalente decimal.

3. Em seguida, converta os valores decimais em seus equivalentes hexadecimais. Use a tabela a seguir para essa conversão:

   ```
   Decimal   Hexadecimal
   0         0
   1         1
   2         2
   3         3
   4         4
   5         5
   6         6
   7         7
   8         8
   9         9
   10        A
   11        B
   12        C
   13        D
   14        E
   15        F
   ```

4. Escreva os valores hexadecimais resultantes de cada grupo, da esquerda para a direita, para obter o número hexadecimal completo.

**Exemplo: Converter o binário 110110101 em hexadecimal:**

```
1. Agrupe os dígitos binários em grupos de quatro: 1101 1010 1000.
2. Converta cada grupo para decimal: 13 10 8.
3. Converta os valores decimais em hexadecimais: D A 8.
4. Combine os valores hexadecimais: DA8.
```

Portanto, o binário 110110101 é igual a DA8 em hexadecimal.

**De Hexadecimal para Binário:**

1. Converta cada dígito hexadecimal em seu equivalente decimal usando a tabela mencionada anteriormente.

2. Em seguida, converta os valores decimais resultantes em binários. Para fazer isso, represente cada valor decimal como uma sequência de quatro dígitos binários, preenchendo com zeros à esquerda, se necessário.

3. Junte os dígitos binários resultantes de cada dígito hexadecimal, da esquerda para a direita, para obter o número binário completo.

**Exemplo: Converter o hexadecimal DA8 em binário:**

```
D = 13 em decimal = 1101 em binário (4 dígitos)
A = 10 em decimal = 1010 em binário (4 dígitos)
8 = 8 em decimal = 1000 em binário (4 dígitos)
```

Combine os dígitos binários: 110110101000.

Portanto, o hexadecimal DA8 é igual a 110110101000 em binário.

Esses são os passos para converter entre números binários e hexadecimais. Esse tipo de conversão é frequentemente usado em programação e eletrônica, onde representações compactas e legíveis são necessárias.

## CONVERTER OCTAL <> BINARIO:
A conversão entre números octais (base 8) e números binários (base 2) é direta, pois o octal é uma base que pode ser facilmente convertida para binário devido à relação entre as bases. Cada dígito octal pode ser representado por três dígitos binários. Aqui estão os passos para converter de octal para binário e vice-versa:

**De Octal para Binário:**

1. Para converter um número octal em binário, mapeie cada dígito octal para seu equivalente binário de três dígitos. Use a seguinte correspondência:

   ```
   Octal   Binário (3 dígitos)
   0       000
   1       001
   2       010
   3       011
   4       100
   5       101
   6       110
   7       111
   ```

2. Aplique essa correspondência a cada dígito do número octal, da esquerda para a direita, para obter sua representação em binário.

3. Combine os dígitos binários resultantes para formar o número binário completo.

**Exemplo: Converter o octal 753 para binário:**

```
7 -> 111
5 -> 101
3 -> 011
```

Combine os dígitos binários: 111101011.

Portanto, o octal 753 é igual a 111101011 em binário.

**De Binário para Octal:**

1. Para converter um número binário em octal, divida os dígitos binários em grupos de três, começando pela direita. Se o número de dígitos binários não for um múltiplo de três, adicione zeros à esquerda para criar grupos de três.

2. Em seguida, mapeie cada grupo de três dígitos binários para seu equivalente octal de um dígito usando a tabela de correspondência fornecida acima.

3. Combine os dígitos octais resultantes para formar o número octal completo.

**Exemplo: Converter o binário 1101011101 para octal:**

```
11 010 111 01
11 -> 3 em octal
010 -> 2 em octal
111 -> 7 em octal
01 -> 1 em octal
```

Combine os dígitos octais: 3271.

Portanto, o binário 1101011101 é igual a 3271 em octal.

Esses são os passos para converter entre números octais e binários. A representação octal é útil quando se lida com grupos de bits em programação ou eletrônica, e a conversão para binário permite manipular esses grupos de bits de maneira mais eficaz.

## CONVERTER OCTAL <> HEXADECIMAL:
A conversão entre números octais (base 8) e números hexadecimais (base 16) pode ser feita através de uma conversão intermediária para a base decimal (base 10). Aqui estão os passos para converter de octal para hexadecimal e vice-versa:

**De Octal para Decimal e de Decimal para Hexadecimal:**

1. Primeiro, converta o número octal para decimal. Para fazer isso, você pode usar o método de conversão descrito anteriormente.

2. Uma vez que você tenha o número em decimal, você pode convertê-lo para hexadecimal. Isso é feito dividindo o número decimal por 16 repetidamente e registrando os restos. Em seguida, converta os restos em dígitos hexadecimais usando a tabela de correspondência.

**De Hexadecimal para Decimal e de Decimal para Octal:**

1. Primeiro, converta o número hexadecimal para decimal. Você pode fazer isso convertendo cada dígito hexadecimal em seu equivalente decimal usando a tabela de correspondência e somando os valores resultantes.

2. Depois de obter o número em decimal, você pode convertê-lo para octal. Isso é feito dividindo o número decimal por 8 repetidamente e registrando os restos. Em seguida, converta os restos em dígitos octais usando a tabela de correspondência.

Aqui está um exemplo de conversão de octal para hexadecimal e vice-versa:

**De Octal para Hexadecimal:**

Vamos converter o octal 765 para hexadecimal.

1. Primeiro, converta 765 para decimal. 765 em octal é igual a 501 em decimal.

2. Em seguida, converta 501 para hexadecimal. Dividindo 501 por 16 repetidamente, obtemos os restos: 5, 1. Agora, converta esses restos em dígitos hexadecimais: 5 -> 5, 1 -> 1.

Portanto, o octal 765 é igual a 51 em hexadecimal.

**De Hexadecimal para Octal:**

Vamos converter o hexadecimal 2A3 para octal.

1. Primeiro, converta 2A3 para decimal. 2A3 em hexadecimal é igual a 675 em decimal.

2. Em seguida, converta 675 para octal. Dividindo 675 por 8 repetidamente, obtemos os restos: 3, 0, 4. Agora, converta esses restos em dígitos octais: 3 -> 3, 0 -> 0, 4 -> 4.

Portanto, o hexadecimal 2A3 é igual a 304 em octal.

Esses são os passos para converter entre números octais e hexadecimais, com uma conversão intermediária para decimal. Esses métodos são úteis quando você precisa trabalhar com diferentes bases numéricas em programação ou eletrônica.