# NÚMEROS BINÁRIOS
## CONCEITO:
O sistema binário é um sistema de numeração que utiliza apenas dois dígitos: 0 e 1. Ele é fundamental na computação e na eletrônica digital, pois os computadores operam internamente com circuitos eletrônicos que têm dois estados, geralmente representados como "ligado" (1) e "desligado" (0). Aqui estão os principais conceitos relacionados ao sistema binário:

1. **Base 2**: O sistema binário é chamado de "base 2" porque utiliza dois dígitos. Isso contrasta com o sistema decimal, que é base 10, e o sistema octal (base 8) e o sistema hexadecimal (base 16), que utilizam 8 e 16 dígitos, respectivamente.

2. **Dígitos Binários**: Os únicos dígitos usados no sistema binário são 0 e 1. Cada dígito binário representa um valor específico, onde 0 representa a ausência de algo (desligado) e 1 representa a presença de algo (ligado).

3. **Posicionamento**: Cada posição em um número binário tem um valor posicional, semelhante ao sistema decimal. A posição mais à direita representa 2^0 (1), a próxima posição representa 2^1 (2), a seguinte 2^2 (4), e assim por diante. Isso permite que números maiores sejam representados com combinações de dígitos binários.

4. **Conversão**: A conversão entre números binários e decimais envolve a atribuição de valores às posições de acordo com as potências de 2 e a multiplicação dos dígitos binários pelos valores posicionais correspondentes.

5. **Aplicação na Computação**: Os computadores internamente utilizam o sistema binário para representar e processar informações, como números, texto, imagens e outros tipos de dados. Todos os dados são representados em formato binário no nível mais baixo da computação.

6. **Linguagem de Máquina**: Os programas e instruções que um computador executa são expressos em linguagem de máquina, que consiste em sequências de números binários que representam operações e dados.

7. **Lógica Booleana**: O sistema binário é fundamental para a lógica booleana, que é amplamente usada na eletrônica digital para projetar circuitos lógicos e realizar operações lógicas, como "E" lógico, "OU" lógico e "NÃO" lógico.

8. **Armazenamento e Transmissão de Dados**: Os dados são frequentemente armazenados e transmitidos em formato binário em dispositivos de armazenamento, comunicações e redes de computadores.

Em resumo, o sistema binário é a base fundamental da computação digital e desempenha um papel crucial na representação e processamento de informações em dispositivos eletrônicos e computadores.

Aqui estão alguns números em binário, de 1 a 20:

1. 1 em binário: 1
2. 2 em binário: 10
3. 3 em binário: 11
4. 4 em binário: 100
5. 5 em binário: 101
6. 6 em binário: 110
7. 7 em binário: 111
8. 8 em binário: 1000
9. 9 em binário: 1001
10. 10 em binário: 1010
11. 11 em binário: 1011
12. 12 em binário: 1100
13. 13 em binário: 1101
14. 14 em binário: 1110
15. 15 em binário: 1111
16. 16 em binário: 10000
17. 17 em binário: 10001
18. 18 em binário: 10010
19. 19 em binário: 10011
20. 20 em binário: 10100

Esses são os números de 1 a 20 em representação binária, onde cada dígito binário (0 ou 1) representa um valor específico de potência de 2. Por exemplo, o número binário "101" representa 1 * 2^2 + 0 * 2^1 + 1 * 2^0, que é igual a 5 em decimal. Você pode usar essa lógica para converter qualquer número binário em decimal e vice-versa.

## CONVERSÃO DE DECIMAL PARA BINÁRIO:
A conversão de números decimais para binários envolve a representação de um número na base decimal (base 10) como seu equivalente na base binária (base 2). Para fazer essa conversão, você pode seguir os passos abaixo:

**Passo 1:** Comece com o número decimal que você deseja converter para binário.

**Passo 2:** Divida o número decimal por 2 (a base binária) e registre o quociente e o resto da divisão.

**Passo 3:** Anote o resto como o dígito binário mais à direita.

**Passo 4:** Use o quociente como o novo número decimal e repita os passos 2 e 3 até que o quociente seja igual a 0.

**Passo 5:** Leia os dígitos binários da direita para a esquerda para obter a representação binária completa.

Aqui está um exemplo:

Vamos converter o número decimal 19 em binário:

**Passo 1:** Comece com 19.

**Passo 2:** Divida 19 por 2: 19 ÷ 2 = 9, com um resto de 1.

**Passo 3:** Anote o resto (1) como o dígito binário mais à direita.

**Passo 4:** Use o quociente (9) como o novo número decimal e repita o processo.

**Passo 2:** Divida 9 por 2: 9 ÷ 2 = 4, com um resto de 1.

**Passo 3:** Anote o resto (1) como o próximo dígito binário à esquerda do anterior.

**Passo 4:** Use o quociente (4) como o novo número decimal e repita o processo.

**Passo 2:** Divida 4 por 2: 4 ÷ 2 = 2, com um resto de 0.

**Passo 3:** Anote o resto (0) como o próximo dígito binário à esquerda dos anteriores.

**Passo 4:** Use o quociente (2) como o novo número decimal e repita o processo.

**Passo 2:** Divida 2 por 2: 2 ÷ 2 = 1, com um resto de 0.

**Passo 3:** Anote o resto (0) como o próximo dígito binário à esquerda dos anteriores.

**Passo 4:** Use o quociente (1) como o novo número decimal e repita o processo.

**Passo 2:** Divida 1 por 2: 1 ÷ 2 = 0, com um resto de 1.

**Passo 3:** Anote o resto (1) como o próximo dígito binário à esquerda dos anteriores.

Agora, leia os dígitos binários da direita para a esquerda: 10011.

Portanto, o número decimal 19 é igual a 10011 em binário.

## CONVERTENDO DE BINÁRIO PARA DECIMAL:
A conversão de números binários para decimais envolve a transformação de um número na base binária (base 2) em seu equivalente na base decimal (base 10). Para fazer essa conversão, você deve entender o valor posicional dos dígitos binários. Aqui está um passo a passo para converter um número binário em decimal:

1. **Escreva o número binário**: Comece com o número binário que você deseja converter em decimal. Por exemplo, vamos converter o número binário 10101.

2. **Atribua uma posição de potência**: Comece da direita para a esquerda no número binário, atribuindo potências de 2 a cada dígito binário. A posição mais à direita recebe a potência de 2^0 (que é 1), a próxima à esquerda recebe 2^1 (que é 2), a próxima 2^2 (que é 4), a próxima 2^3 (que é 8) e assim por diante.

   Número Binário:  1  0  1  0  1
   Posição de Potência: 2^4  2^3  2^2  2^1  2^0

3. **Calcule o valor de cada posição**: Para cada dígito binário, multiplique o dígito pelo valor da potência atribuída a essa posição. Anote os resultados.

   Valor Posicional: 16  0  4  0  1

4. **Some os valores calculados**: Some todos os valores calculados na etapa anterior para obter o valor decimal equivalente.

   Valor Decimal = 16 + 0 + 4 + 0 + 1 = 21

Portanto, o número binário 10101 é igual a 21 em decimal.

Aqui estão mais alguns exemplos para ilustrar o processo:

- Binário 1101 em Decimal:
   - 1 * 2^3 + 1 * 2^2 + 0 * 2^1 + 1 * 2^0 = 8 + 4 + 0 + 1 = 13

- Binário 11110000 em Decimal:
   - 1 * 2^7 + 1 * 2^6 + 1 * 2^5 + 1 * 2^4 + 0 * 2^3 + 0 * 2^2 + 0 * 2^1 + 0 * 2^0 = 128 + 64 + 32 + 16 + 0 + 0 + 0 + 0 = 240

Agora você sabe como converter números binários em decimais. É um processo direto, desde que você atribua as potências de 2 corretamente às posições dos dígitos binários e realize os cálculos.

## MÉTODO DE SUBTRAÇÃO SUCESSIVA:
Esse metodo é um atalho útil para converter números entre binário e decimal mentalmente. Ele envolve representar o número em sua forma binária e realizar uma série de subtrações sucessivas para encontrar os dígitos binários.

Aqui está uma explicação mais detalhada do método:

**Para Converter de Decimal para Binário:**

1. Comece com o número decimal que você deseja converter em binário.

2. Escreva as potências de 2 em ordem decrescente à esquerda do número decimal (começando com 1).

3. Subtraia a maior potência de 2 possível do número decimal sem excedê-lo. Coloque um "1" na posição correspondente e subtraia esse valor do número decimal original.

4. Repita o passo 3 para as potências de 2 restantes, preenchendo com "0s" nas posições em que você não coloca "1s".

5. Continue até que o número decimal seja reduzido a zero.

**Exemplo: Converter 19 em Binário usando o Método de Subtração Sucessiva:**

1. Comece com 19.

2. Escreva as potências de 2 à esquerda do número decimal: 16 (2^4), 8 (2^3), 4 (2^2), 2 (2^1), 1 (2^0).

3. Subtraia a maior potência de 2 possível sem exceder 19: 19 - 16 = 3. Coloque um "1" na posição correspondente (2^4) e continue com 3.

4. Agora, subtraia a próxima maior potência de 2 possível: 3 - 2 = 1. Coloque um "1" na posição correspondente (2^1) e continue com 1.

5. Subtraia a próxima maior potência de 2 possível: 1 - 1 = 0. Coloque um "1" na posição correspondente (2^0).

Agora, leia os dígitos binários da esquerda para a direita: 10011.

Portanto, 19 em binário é igual a 10011.

**Para Converter de Binário para Decimal:**

1. Comece com o número binário que você deseja converter em decimal.

2. Escreva as potências de 2 em ordem decrescente à esquerda do número binário (começando com 1).

3. Multiplique cada dígito binário pelo valor da potência de 2 correspondente à sua posição e some esses valores.

**Exemplo: Converter 10011 em Decimal:**

1. Comece com 10011.

2. Escreva as potências de 2 à esquerda do número binário: 16 (2^4), 8 (2^3), 4 (2^2), 2 (2^1), 1 (2^0).

3. Multiplique os dígitos binários pelas potências de 2 correspondentes e some-os: 1 * 16 + 0 * 8 + 0 * 4 + 1 * 2 + 1 * 1 = 16 + 0 + 0 + 2 + 1 = 19.

Portanto, 10011 em binário é igual a 19 em decimal.

Este método é eficaz para números pequenos e pode ser uma maneira conveniente de fazer conversões mentais entre binário e decimal, desde que você esteja confortável com as potências de 2. Para números maiores, a divisão sucessiva ou métodos computacionais são geralmente mais práticos.

## TABELA BINÁRIA:
| Decimal | Binário |
|---------|---------|
|   1     |   1     |
|   2     |   10    |
|   3     |   11    |
|   4     |   100   |
|   5     |   101   |
|   6     |   110   |
|   7     |   111   |
|   8     |   1000  |
|   9     |   1001  |
|   10    |   1010  |
|   11    |   1011  |
|   12    |   1100  |
|   13    |   1101  |
|   14    |   1110  |
|   15    |   1111  |
|   16    |   10000 |
|   17    |   10001 |
|   18    |   10010 |
|   19    |   10011 |
|   20    |   10100 |
|   21    |   10101 |
|   22    |   10110 |
|   23    |   10111 |
|   24    |   11000 |
|   25    |   11001 |
|   26    |   11010 |
|   27    |   11011 |
|   28    |   11100 |
|   29    |   11101 |
|   30    |   11110 |
|   31    |   11111 |
|   32    |   100000|
|   33    |   100001|
|   34    |   100010|
|   35    |   100011|
|   36    |   100100|
|   37    |   100101|
|   38    |   100110|
|   39    |   100111|
|   40    |   101000|
|   41    |   101001|
|   42    |   101010|
|   43    |   101011|
|   44    |   101100|
|   45    |   101101|
|   46    |   101110|
|   47    |   101111|
|   48    |   110000|
|   49    |   110001|
|   50    |   110010|
|   51    |   110011|
|   52    |   110100|
|   53    |   110101|
|   54    |   110110|
|   55    |   110111|
|   56    |   111000|
|   57    |   111001|
|   58    |   111010|
|   59    |   111011|
|   60    |   111100|
|   61    |   111101|
|   62    |   111110|
|   63    |   111111|
|   64    |   1000000|
|   65    |   1000001|
|   66    |   1000010|
|   67    |   1000011|
|   68    |   1000100|
|   69    |   1000101|
|   70    |   1000110|
|   71    |   1000111|
|   72    |   1001000|
|   73    |   1001001|
|   74    |   1001010|
|   75    |   1001011|
|   76    |   1001100|
|   77    |   1001101|
|   78    |   1001110|
|   79    |   1001111|
|   80    |   1010000|
|   81    |   1010001|
|   82    |   1010010|
|   83    |   1010011|
|   84    |   1010100|
|   85    |   1010101|
|   86    |   1010110|
|   87    |   1010111|
|   88    |   1011000|
|   89    |   1011001|
|   90    |   1011010|
|   91    |   1011011|
|   92    |   1011100|
|   93    |   1011101|
|   94    |   1011110|
|   95    |   1011111|
|   96    |   1100000|
|   97    |   1100001|
|   98    |   1100010|
|   99    |   1100011|
|   100   |   1100100|

