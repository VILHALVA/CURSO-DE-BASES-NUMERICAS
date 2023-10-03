# RELAÇÕES ENTRE SISTEMAS DE NUMERAÇÃO
## CONCEITO:
Existem várias relações entre sistemas de numeração, que são importantes de entender ao trabalhar com diferentes bases numéricas, como decimal (base 10), binário (base 2), octal (base 8) e hexadecimal (base 16). Aqui estão algumas das relações mais comuns:

1. **Decimal para Outras Bases:**
   - Para converter de decimal para binário, octal ou hexadecimal, você pode usar a divisão sucessiva e o método de restos para encontrar os dígitos na base desejada.
   - Decimal para Binário: Divida por 2 repetidamente e registre os restos (da direita para a esquerda).
   - Decimal para Octal: Divida por 8 repetidamente e registre os restos (da direita para a esquerda).
   - Decimal para Hexadecimal: Divida por 16 repetidamente e registre os restos (da direita para a esquerda), convertendo dígitos maiores que 9 em letras A, B, C, D, E ou F.

2. **Outras Bases para Decimal:**
   - Para converter de binário, octal ou hexadecimal para decimal, multiplique cada dígito pela potência da base correspondente e some os resultados.
   - Binário para Decimal: Cada dígito binário é multiplicado por 2 elevado à sua posição.
   - Octal para Decimal: Cada dígito octal é multiplicado por 8 elevado à sua posição.
   - Hexadecimal para Decimal: Cada dígito hexadecimal é multiplicado por 16 elevado à sua posição.

3. **Binário para Octal e Hexadecimal:**
   - Para converter de binário para octal ou hexadecimal, agrupe os dígitos binários em grupos de três ou quatro (respectivamente) da direita para a esquerda e converta cada grupo em seu equivalente na base desejada.
   - Binário para Octal: Agrupe em grupos de três e converta cada grupo em seu equivalente octal.
   - Binário para Hexadecimal: Agrupe em grupos de quatro e converta cada grupo em seu equivalente hexadecimal.

4. **Octal e Hexadecimal para Binário:**
   - Para converter de octal ou hexadecimal para binário, converta cada dígito em seu equivalente binário de três ou quatro dígitos (respectivamente).
   - Octal para Binário: Cada dígito octal é convertido em três dígitos binários.
   - Hexadecimal para Binário: Cada dígito hexadecimal é convertido em quatro dígitos binários.

5. **Hexadecimal para Octal:**
   - Para converter de hexadecimal para octal, primeiro converta de hexadecimal para binário e, em seguida, de binário para octal.

6. **Relações Numéricas:**
   - Em termos de representação numérica, uma base superior pode representar valores maiores com menos dígitos do que uma base inferior. Por exemplo, em decimal, 100 é representado por três dígitos, enquanto em binário, é representado por sete dígitos (1100100).

Compreender essas relações é fundamental ao trabalhar com diferentes sistemas de numeração, especialmente em programação e eletrônica, onde a conversão entre bases é comum. Elas permitem que você represente e manipule dados de forma eficaz em diferentes contextos.

## CONVERTER DECIMAL <> BINARIO <> OCTAL <> HEXADECIMAL:
A conversão entre diferentes sistemas de numeração, como decimal, binário, octal e hexadecimal, envolve a representação de um número em uma base e sua conversão para outra base. Vou explicar como fazer isso entre esses quatro sistemas:

**1. Converter de Decimal para Outras Bases:**

- **Decimal para Binário:** Para converter de decimal para binário, siga os passos abaixo:
   1. Divida o número decimal por 2 repetidamente e registre os restos (da direita para a esquerda).
   2. Os restos formam a representação binária do número.

- **Decimal para Octal:** Para converter de decimal para octal, siga os passos abaixo:
   1. Divida o número decimal por 8 repetidamente e registre os restos (da direita para a esquerda).
   2. Os restos formam a representação octal do número.

- **Decimal para Hexadecimal:** Para converter de decimal para hexadecimal, siga os passos abaixo:
   1. Divida o número decimal por 16 repetidamente e registre os restos (da direita para a esquerda).
   2. Converta os restos em dígitos hexadecimais (10 = A, 11 = B, 12 = C, 13 = D, 14 = E, 15 = F).
   3. Os dígitos hexadecimais formam a representação hexadecimal do número.

**2. Converter de Binário para Outras Bases:**

- **Binário para Decimal:** Para converter de binário para decimal, multiplique cada dígito binário pela potência de 2 correspondente à sua posição e some os resultados.

- **Binário para Octal e Hexadecimal:** Agrupe os dígitos binários em grupos de três (octal) ou quatro (hexadecimal), da direita para a esquerda, e converta cada grupo na base desejada.

**3. Converter de Octal e Hexadecimal para Outras Bases:**

- **Octal para Decimal:** Para converter de octal para decimal, multiplique cada dígito octal pela potência de 8 correspondente à sua posição e some os resultados.

- **Hexadecimal para Decimal:** Para converter de hexadecimal para decimal, multiplique cada dígito hexadecimal pelo valor da potência de 16 correspondente à sua posição e some os resultados.

- **Octal para Binário:** Converta cada dígito octal em seu equivalente binário de três dígitos.

- **Hexadecimal para Binário:** Converta cada dígito hexadecimal em seu equivalente binário de quatro dígitos.

**4. Converter entre Octal e Hexadecimal:**

- Para converter entre octal e hexadecimal, você pode usar a conversão intermediária para binário e, em seguida, converter de binário para a outra base.

Lembre-se de que a tabela de correspondência entre os sistemas de numeração (binário, octal, hexadecimal) e os valores decimais é fundamental para realizar essas conversões. Conhecer essas relações e os métodos de conversão é útil para trabalhar com diferentes bases numéricas em programação, eletrônica e ciência da computação.

## TABELA:

| Decimal |   Binário   |  Octal  |  Hexadecimal  |
|---------|-------------|---------|---------------|
|    0    |      0      |    0    |       0       |
|    1    |      1      |    1    |       1       |
|    2    |     10      |    2    |       2       |
|    3    |     11      |    3    |       3       |
|    4    |    100      |    4    |       4       |
|    5    |    101      |    5    |       5       |
|    6    |    110      |    6    |       6       |
|    7    |    111      |    7    |       7       |
|    8    |   1000      |   10    |       8       |
|    9    |   1001      |   11    |       9       |
|   10    |   1010      |   12    |       A       |
|   11    |   1011      |   13    |       B       |
|   12    |   1100      |   14    |       C       |
|   13    |   1101      |   15    |       D       |
|   14    |   1110      |   16    |       E       |
|   15    |   1111      |   17    |       F       |
|   16    |  10000      |   20    |      10       |
|   17    |  10001      |   21    |      11       |
|   18    |  10010      |   22    |      12       |
|   19    |  10011      |   23    |      13       |
|   20    |  10100      |   24    |      14       |
|   21    |  10101      |   25    |      15       |
|   22    |  10110      |   26    |      16       |
|   23    |  10111      |   27    |      17       |
|   24    |  11000      |   30    |      18       |
|   25    |  11001      |   31    |      19       |
|   26    |  11010      |   32    |      1A       |
|   27    |  11011      |   33    |      1B       |
|   28    |  11100      |   34    |      1C       |
|   29    |  11101      |   35    |      1D       |
|   30    |  11110      |   36    |      1E       |
|   31    |  11111      |   37    |      1F       |
|   32    | 100000      |   40    |      20       |
|   33    | 100001      |   41    |      21       |
|   34    | 100010      |   42    |      22       |
|   35    | 100011      |   43    |      23       |
|   36    | 100100      |   44    |      24       |
|   37    | 100101      |   45    |      25       |
|   38    | 100110      |   46    |      26       |
|   39    | 100111      |   47    |      27       |
|   40    | 101000      |   50    |      28       |
|   41    | 101001      |   51    |      29       |
|   42    | 101010      |   52    |      2A       |
|   43    | 101011      |   53    |      2B       |
|   44    | 101100      |   54    |      2C       |
|   45    | 101101      |   55    |      2D       |
|   46    | 101110      |   56    |      2E       |
|   47    | 101111      |   57    |      2F       |
|   48    | 110000      |   60    |      30       |
|   49    | 110001      |   61    |      31       |
|   50    | 110010      |   62    |      32       |
|   51    | 110011      |   63    |      33       |
|   52    | 110100      |   64    |      34       |
|   53    | 110101      |   65    |      35       |
|   54    | 110110      |   66    |      36       |
|   55    | 110111      |   67    |      37       |
|   56    | 111000      |   70    |      38       |
|   57    | 111001      |   71    |      39       |
|   58    | 111010      |   72    |      3A       |
|   59    | 111011      |   73    |      3B       |
|   60    | 111100      |   74    |      3C       |
|   61    | 111101      |   75    |      3D       |
|   62    | 111110      |   76    |      3E       |
|   63    | 111111      |   77    |      3F       |
|   64    |1000000      |  100    |      40       |
|   65    |1000001      |  101    |      41       |
|   66    |1000010      |  102    |      42       |
|   67    |1000011      |  103    |      43       |
|   68    |1000100      |  104    |      44       |
|   69    |1000101      |  105    |      45       |
|   70    |1000110      |  106    |      46       |
|   71    |1000111      |  107    |      47       |
|   72    |1001000      |  110    |      48       |
|   73    |1001001      |  111    |      49       |
|   74    |1001010      |  112    |      4A       |
|   75    |1001011      |  113    |      4B       |
|   76    |1001100      |  114    |      4C       |
|   77    |1001101      |  115    |      4D       |
|   78    |1001110      |  116    |      4E       |
|   79    |1001111      |  117    |      4F       |
|   80    |1010000      |  120    |      50       |
|   81    |1010001      |  121    |      51       |
|   82    |1010010      |  122    |      52       |
|   83    |1010011      |  123    |      53       |
|   84    |1010100      |  124    |      54       |
|   85    |1010101      |  125    |      55       |
|   86    |1010110      |  126    |      56       |
|   87    |1010111      |  127    |      57       |
|   88    |1011000      |  130    |      58       |
|   89    |1011001      |  131    |      59       |
|   90    |1011010      |  132    |      5A       |
|   91    |1011011      |  133    |      5B       |
|   92    |1011100      |  134    |      5C       |
|   93    |1011101      |  135    |      5D       |
|   94    |1011110      |  136    |      5E       |
|   95    |1011111      |  137    |      5F       |
|   96    |1100000      |  140    |      60       |
|   97    |1100001      |  141    |      61       |
|   98    |1100010      |  142    |      62       |
|   99    |1100011      |  143    |      63       |
|  100    |1100100      |  144    |      64       |
