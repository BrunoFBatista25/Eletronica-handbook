
# 01.04 — Grandezas Elétricas, Diferença de Potencial, Resistência e Potência

**Handbook de Eletrônica | Fundamentos Elétricos**

| Identificação | Descrição |
|---|---|
| Módulo | 01 — Fundamentos Elétricos |
| Nota | 01.04 |
| Nível | Básico a intermediário |
| Área | Análise de circuitos |
| Aplicação | Medições, manutenção e diagnóstico de PCBs |
| Status | Em estudo |

> **Disclaimer — Conteúdo matemático**
>
> Esta nota apresenta as principais grandezas elétricas e suas relações matemáticas. Serão estudadas tensão, diferença de potencial, corrente, resistência, potência, energia, Lei de Ohm, associação de resistores e princípios de medição.
>
> Os cálculos incluem operações básicas, conversões de unidades e manipulação algébrica.

# 1. Introdução às grandezas elétricas

Para compreender o funcionamento de um circuito, precisamos conhecer as grandezas físicas que descrevem seu comportamento.

As principais são:

| Grandeza | Símbolo | Unidade |
|---|---|---|
| Carga elétrica | Q | Coulomb (C) |
| Corrente elétrica | I | Ampère (A) |
| Tensão elétrica | V ou U | Volt (V) |
| Resistência elétrica | R | Ohm (Ω) |
| Potência elétrica | P | Watt (W) |
| Energia elétrica | E | Joule (J) |
| Capacitância | C | Farad (F) |
| Condutância | G | Siemens (S) |

Essas grandezas permitem analisar o comportamento de componentes e circuitos.

# 2. Carga elétrica

A carga elétrica é uma propriedade física da matéria.

Sua unidade é o coulomb (C).

A carga elementar possui módulo aproximado de:

```text
e = 1,602176634 × 10⁻¹⁹ C
```

A carga total associada a um número N de elétrons é:

```text
Q = -N × e
```

O sinal negativo indica que se trata de elétrons.

# 3. Corrente elétrica

A corrente elétrica representa a quantidade de carga que atravessa uma seção de um condutor por unidade de tempo.

Sua definição é:

```text
I = ΔQ / Δt
```

Onde:

- I = corrente elétrica (A);
- ΔQ = variação da carga elétrica (C);
- Δt = intervalo de tempo (s).

Um ampère corresponde a um coulomb por segundo:

```text
1 A = 1 C/s
```

## 3.1. Exemplo de cálculo

Se 12 coulombs atravessam uma seção de um condutor durante 4 segundos:

```text
I = ΔQ / Δt

I = 12 / 4

I = 3 A
```

A corrente elétrica média é de 3 ampères.

## 3.2. Sentido convencional da corrente

O sentido convencional da corrente é definido como o sentido do movimento de cargas positivas.

Nos condutores metálicos, os elétrons se deslocam em sentido médio oposto ao sentido convencional da corrente.

Essa convenção é utilizada nos diagramas e na análise de circuitos.

# 4. Tensão elétrica e diferença de potencial (DDP)

A tensão elétrica está relacionada à diferença de potencial elétrico entre dois pontos.

A diferença de potencial representa a variação da energia potencial elétrica por unidade de carga entre esses pontos.

Sua definição é:

```text
ΔV = ΔU / q
```

Onde:

- ΔV = diferença de potencial (V);
- ΔU = variação da energia potencial elétrica (J);
- q = carga elétrica (C).

A unidade é o volt:

```text
1 V = 1 J/C
```

Isso significa que uma diferença de potencial de 1 volt corresponde a uma variação de 1 joule de energia potencial por coulomb de carga.

## 4.1. Exemplo de cálculo

Considere uma carga de 2 C que apresenta uma variação de energia potencial elétrica de 24 J entre dois pontos.

```text
ΔV = ΔU / q

ΔV = 24 / 2

ΔV = 12 V
```

A diferença de potencial entre os pontos é de 12 volts, considerando a convenção de sinais adotada para a variação de energia.

## 4.2. Por que a tensão é importante?

A diferença de potencial estabelece as condições para que exista corrente elétrica em um circuito fechado.

Em um condutor, a tensão aplicada produz um campo elétrico que influencia o movimento dos portadores de carga.

Entretanto, tensão não é corrente.

- Tensão representa diferença de potencial.
- Corrente representa fluxo de carga por unidade de tempo.

Pode existir tensão entre dois pontos sem que exista corrente significativa, por exemplo, em um circuito aberto.

# 5. Resistência elétrica

A resistência elétrica representa a oposição que um elemento oferece à passagem da corrente elétrica.

Sua unidade é o ohm:

```text
Ω
```

Em um resistor ôhmico, sob condições físicas aproximadamente constantes, a relação entre tensão e corrente é:

```text
R = V / I
```

Onde:

- R = resistência (Ω);
- V = tensão (V);
- I = corrente (A).

## 5.1. Exemplo de cálculo

Um resistor apresenta tensão de 12 V e corrente de 2 A.

```text
R = V / I

R = 12 / 2

R = 6 Ω
```

A resistência é de 6 ohms.

## 5.2. Resistência e resistividade não são a mesma coisa

**Resistência:** característica elétrica de um componente ou elemento com dimensões específicas.

**Resistividade:** propriedade física do material.

A resistência de um condutor uniforme depende de:

```text
R = ρ × (L / A)
```

Onde:

- ρ = resistividade;
- L = comprimento;
- A = área transversal.

# 6. Lei de Ohm

A Lei de Ohm estabelece que, para um elemento ôhmico em condições físicas constantes, a tensão é proporcional à corrente.

Sua expressão é:

```text
V = R × I
```

Podemos reorganizar:

```text
I = V / R
```

E:

```text
R = V / I
```

Essas três expressões permitem calcular tensão, corrente ou resistência quando as outras duas grandezas são conhecidas.

## 6.1. Exemplo — Calculando corrente

Um resistor de 100 Ω está submetido a uma tensão de 12 V.

```text
I = V / R

I = 12 / 100

I = 0,12 A
```

Convertendo para miliampères:

```text
0,12 A × 1.000 = 120 mA
```

Resultado:

```text
I = 120 mA
```

**Importante:** nem todos os componentes eletrônicos são ôhmicos. Diodos, LEDs e transistores possuem relações entre tensão e corrente que não são lineares em toda a faixa de operação.

# 7. Potência elétrica

A potência elétrica representa a taxa de transferência ou transformação de energia elétrica.

Sua expressão geral é:

```text
P = V × I
```

Onde:

- P = potência (W);
- V = tensão (V);
- I = corrente (A).

A unidade é o watt.

```text
1 W = 1 J/s
```

Para um resistor ôhmico, podemos combinar a Lei de Ohm com a expressão de potência.

Substituindo V = R × I:

```text
P = (R × I) × I

P = R × I²
```

Também podemos utilizar:

```text
P = V² / R
```

Assim, temos três expressões:

```text
P = V × I

P = R × I²

P = V² / R
```

## 7.1. Exemplo de cálculo

Um resistor de 10 Ω recebe uma corrente de 2 A.

```text
P = R × I²

P = 10 × 2²

P = 10 × 4

P = 40 W
```

A potência dissipada é de 40 W.

**Atenção:** em aplicações reais, a potência nominal do resistor deve ser adequada à dissipação prevista, respeitando também temperatura, ventilação e condições de montagem.

# 8. Energia elétrica

A energia elétrica representa a quantidade de energia transferida ou transformada durante determinado intervalo de tempo.

Para potência constante:

```text
E = P × t
```

Onde:

- E = energia (J);
- P = potência (W);
- t = tempo (s).

## 8.1. Exemplo

Um equipamento de 100 W funciona durante 10 segundos.

```text
E = P × t

E = 100 × 10

E = 1.000 J
```

A energia consumida é de 1.000 joules.

# 9. Associação de resistores

Os resistores podem ser associados em série, em paralelo ou em combinações mistas.

## 9.1. Resistores em série

Em uma associação em série, os resistores estão conectados em sequência, formando um único caminho para a corrente.

A corrente é a mesma em todos os resistores.

A resistência equivalente é:

```text
Req = R1 + R2 + R3 + ...
```

Exemplo:

```text
R1 = 100 Ω
R2 = 200 Ω
R3 = 300 Ω

Req = 100 + 200 + 300

Req = 600 Ω
```

## 9.2. Resistores em paralelo

Em uma associação em paralelo, os resistores estão conectados aos mesmos dois nós.

A tensão é a mesma em todos os ramos.

A resistência equivalente é:

```text
1 / Req = 1 / R1 + 1 / R2 + 1 / R3 + ...
```

Para dois resistores em paralelo:

```text
Req = (R1 × R2) / (R1 + R2)
```

Exemplo:

```text
R1 = 100 Ω
R2 = 100 Ω

Req = (100 × 100) / (100 + 100)

Req = 10.000 / 200

Req = 50 Ω
```

A resistência equivalente é de 50 Ω.

# 10. Leis de Kirchhoff

As Leis de Kirchhoff são fundamentais para analisar circuitos elétricos.

## 10.1. Lei dos Nós — LKC

A Lei das Correntes de Kirchhoff estabelece que a soma algébrica das correntes em um nó é igual a zero.

Em outras palavras, a soma das correntes que entram em um nó é igual à soma das correntes que saem.

```text
Σ I = 0
```

Exemplo:

Um nó recebe uma corrente de 5 A. Duas correntes saem: 2 A e 3 A.

```text
5 A = 2 A + 3 A
```

A conservação da carga elétrica é a base física dessa lei.

## 10.2. Lei das Malhas — LKT

A Lei das Tensões de Kirchhoff estabelece que a soma algébrica das tensões em uma malha fechada é igual a zero.

```text
Σ V = 0
```

Exemplo:

Uma fonte de 12 V alimenta dois resistores em série, com quedas de tensão de 5 V e 7 V.

```text
+12 V - 5 V - 7 V = 0 V
```

A soma algébrica das tensões da malha é zero.

# 11. Conversão de unidades e prefixos

As grandezas elétricas são frequentemente expressas com prefixos do Sistema Internacional.

| Prefixo | Símbolo | Fator |
|---|---|---:|
| Pico | p | 10⁻¹² |
| Nano | n | 10⁻⁹ |
| Micro | µ | 10⁻⁶ |
| Mili | m | 10⁻³ |
| Quilo | k | 10³ |
| Mega | M | 10⁶ |
| Giga | G | 10⁹ |

Exemplos:

```text
1 kΩ = 1.000 Ω

1 MΩ = 1.000.000 Ω

1 mA = 0,001 A

1 µA = 0,000001 A

1 µF = 0,000001 F
```

Atenção: letras maiúsculas e minúsculas podem representar fatores completamente diferentes.

# 12. Medições com multímetro

O multímetro permite medir diferentes grandezas elétricas.

As funções mais comuns são:

| Função | O que mede |
|---|---|
| V⎓ | Tensão contínua |
| V~ | Tensão alternada |
| Ω | Resistência |
| Continuidade | Verificação de caminho elétrico |
| A ou mA | Corrente elétrica |
| Teste de diodo | Queda de tensão direta do componente |

## 12.1. Medição de tensão

A tensão é medida entre dois pontos do circuito.

O instrumento é conectado em paralelo com o elemento ou entre os pontos de interesse.

É necessário selecionar a função e a faixa corretas, além de estabelecer uma referência de medição adequada.

## 12.2. Medição de corrente

A corrente é medida em série com o caminho pelo qual ela circula.

O circuito precisa ser aberto no ponto apropriado para inserir o instrumento.

**Nunca conecte o multímetro configurado para medir corrente diretamente em paralelo com uma fonte de tensão.** Isso pode provocar curto-circuito, danificar o instrumento e causar acidentes.

## 12.3. Medição de resistência

A resistência deve ser medida com o circuito desenergizado e sem energia residual.

Capacitores podem permanecer carregados mesmo após o desligamento do equipamento.

A medição em circuito também pode sofrer influência de caminhos paralelos e de componentes semicondutores.

Por isso, uma leitura de resistência na placa não representa necessariamente o valor nominal do componente.

# 13. Aplicação no diagnóstico de PCBs

As grandezas elétricas são utilizadas durante todo o processo de diagnóstico.

Exemplos:

**Tensão ausente:** pode indicar interrupção na alimentação, falha de proteção ou defeito no estágio de conversão.

**Corrente excessiva:** pode indicar sobrecarga ou curto-circuito, mas exige investigação.

**Resistência inesperada:** pode resultar de defeito, caminhos paralelos ou características do circuito.

**Aquecimento:** pode estar relacionado à dissipação de potência, corrente elevada ou falha de componente.

O diagnóstico precisa considerar o circuito completo, o esquema elétrico, o datasheet e as condições de medição.

# 14. Exercícios de Fixação

1. O que representa a corrente elétrica?
2. Qual é a unidade de diferença de potencial?
3. Qual é a diferença entre tensão e corrente?
4. O que representa a resistência elétrica?
5. Qual é a expressão matemática da Lei de Ohm?
6. Um resistor de 220 Ω recebe uma tensão de 11 V. Calcule a corrente.
7. Um componente recebe 12 V e conduz 0,5 A. Calcule a potência.
8. Dois resistores de 100 Ω estão em série. Calcule a resistência equivalente.
9. Dois resistores de 200 Ω estão em paralelo. Calcule a resistência equivalente.
10. Qual é a diferença entre a Lei das Correntes e a Lei das Tensões de Kirchhoff?
11. Por que a corrente é medida em série?
12. Por que a resistência deve ser medida com o circuito desenergizado?

# 15. Resumo Técnico

A análise de circuitos depende da compreensão das grandezas elétricas fundamentais.

A tensão representa a diferença de potencial entre dois pontos, enquanto a corrente representa a taxa de transporte de carga elétrica.

A resistência descreve a oposição à corrente e a potência representa a taxa de transformação de energia.

A Lei de Ohm relaciona tensão, corrente e resistência para elementos ôhmicos.

As Leis de Kirchhoff permitem analisar correntes nos nós e tensões nas malhas.

Esses conhecimentos são indispensáveis para realizar medições, interpretar esquemas elétricos e desenvolver diagnósticos técnicos confiáveis.

# 16. Registro de Aprendizagem

| Indicador | Registro |
|---|---|
| Data de estudo | ____/____/____ |
| Compreensão teórica | 0 a 5 |
| Exercícios concluídos | ____/12 |
| Cálculos realizados | Pendente / Concluído |
| Medições práticas | Pendente / Concluídas |
| Dúvidas identificadas | A preencher |
| Próxima etapa | Componentes eletrônicos e instrumentação |

**Critério de domínio:** o conteúdo somente será considerado dominado quando houver compreensão demonstrada, capacidade de resolver exercícios e aplicação prática segura.

---

**Próximo módulo:** 02 — Componentes Eletrônicos e Instrumentação.
