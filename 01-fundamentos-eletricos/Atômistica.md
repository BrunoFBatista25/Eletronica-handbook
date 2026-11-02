# 01.01 — Estrutura Atômica, Elétrons e Condutividade Elétrica

**Handbook de Eletrônica | Fundamentos Elétricos**

| Identificação | Descrição |
|---|---|
| Módulo | 01 — Fundamentos Elétricos |
| Aula | 01.01 |
| Nível | Introdutório |
| Área | Eletricidade e Eletrônica |
| Aplicação | Análise de circuitos e diagnóstico de PCBs |
| Status | Em estudo |

> **Disclaimer — Conteúdo com cálculos matemáticos**
>
> Esta aula apresenta conceitos físicos e elétricos acompanhados de fórmulas, conversões de unidades e exercícios matemáticos. Para acompanhar o conteúdo, é necessário compreender operações básicas, potências de 10, frações e manipulação de equações.
>
> Os cálculos serão apresentados passo a passo, com identificação das grandezas, substituição dos valores e interpretação dos resultados.

---

# 1. Introdução

Para compreender o funcionamento de qualquer circuito eletrônico, precisamos começar pela estrutura da matéria.

Todos os componentes eletrônicos são constituídos por materiais formados por átomos. O comportamento das partículas presentes nesses átomos influencia diretamente as propriedades elétricas dos materiais, como sua capacidade de conduzir ou dificultar a passagem da corrente elétrica.

Essa característica permite classificar os materiais em três grandes grupos:

- Condutores;
- Isolantes;
- Semicondutores.

A diferença entre esses materiais está relacionada principalmente à estrutura eletrônica e à disponibilidade de portadores de carga capazes de participar da condução elétrica.

Compreender esses fenômenos é fundamental para estudar fios, resistores, diodos, transistores, MOSFETs e circuitos integrados.

# 2. Estrutura Atômica

## 2.1. O que é um átomo?

O átomo é a unidade básica da estrutura química de um elemento.

Sua estrutura pode ser dividida em duas regiões principais:

**Núcleo atômico:** região central que concentra praticamente toda a massa do átomo. É formado por prótons e nêutrons.

**Eletrosfera:** região ao redor do núcleo na qual se encontram os elétrons, distribuídos em estados de energia.

As três partículas fundamentais são:

| Partícula | Carga elétrica | Localização |
|---|---|---|
| Próton | Positiva (+) | Núcleo |
| Nêutron | Neutra (0) | Núcleo |
| Elétron | Negativa (-) | Eletrosfera |

Em um átomo eletricamente neutro, a quantidade de prótons é igual à quantidade de elétrons.

Por exemplo, um átomo de cobre eletricamente neutro possui 29 prótons e 29 elétrons.

## 2.2. Cargas elétricas

As cargas elétricas são propriedades físicas das partículas que determinam suas interações eletromagnéticas.

Existem dois tipos de carga elétrica:

- Positiva: associada aos prótons.
- Negativa: associada aos elétrons.

O comportamento entre corpos eletricamente carregados segue uma regra fundamental:

- Cargas de mesmo sinal se repelem.
- Cargas de sinais opostos se atraem.

Essa interação é uma das bases para compreender os fenômenos elétricos.

## 2.3. O que acontece quando um átomo perde ou ganha elétrons?

Um átomo pode ganhar ou perder elétrons por meio de processos de transferência de carga.

Quando isso acontece, deixa de ser eletricamente neutro e passa a ser chamado de íon.

**Cátion:** átomo ou grupo de átomos que perde elétrons e apresenta carga positiva.

**Ânion:** átomo ou grupo de átomos que ganha elétrons e apresenta carga negativa.

Exemplo:

| Situação | Prótons | Elétrons | Resultado |
|---|---:|---:|---|
| Átomo neutro | 11 | 11 | Carga neutra |
| Perda de 1 elétron | 11 | 10 | Carga positiva (+1) |
| Ganho de 1 elétron | 11 | 12 | Carga negativa (-1) |

Observe que a quantidade de prótons não precisa mudar para que o átomo adquira uma carga elétrica.

# 3. Elétrons e Camada de Valência

## 3.1. O que são camadas eletrônicas?

Os elétrons ocupam estados de energia ao redor do núcleo atômico.

Em modelos introdutórios, esses estados são representados por camadas eletrônicas, identificadas pelas letras K, L, M, N e assim por diante.

Cada camada está associada a determinados níveis de energia.

Os elétrons mais externos são especialmente importantes para compreender as ligações químicas e as propriedades elétricas dos materiais.

## 3.2. O que é a camada de valência?

A camada de valência é a camada eletrônica mais externa ocupada por elétrons em um átomo.

Os elétrons presentes nessa região são chamados de elétrons de valência.

Eles desempenham um papel importante na formação de ligações químicas e no comportamento elétrico dos materiais.

**Exemplo: cobre (Cu)**

O cobre possui número atômico 29 e configuração eletrônica:

```text
1s² 2s² 2p⁶ 3s² 3p⁶ 3d¹⁰ 4s¹
```

Seu elétron mais externo ocupa o orbital 4s.

Essa característica contribui para seu comportamento como excelente condutor elétrico.

## 3.3. Elétrons livres e elétrons de condução

Em determinados materiais, alguns elétrons podem se movimentar pelo material com relativa facilidade.

Nos metais, os elétrons de condução não ficam rigidamente associados a um único átomo. Eles podem participar do transporte de carga elétrica através da estrutura metálica.

Quando uma diferença de potencial é aplicada, um campo elétrico estabelece condições para o movimento médio orientado desses elétrons.

Esse comportamento permite a condução da corrente elétrica.

**Importante:** nem todo elétron presente em um átomo está disponível para conduzir corrente. A condução depende da estrutura eletrônica e das propriedades do material.

# 4. Condutividade Elétrica

## 4.1. O que é condutividade elétrica?

A condutividade elétrica é uma propriedade física que indica a capacidade de um material permitir o transporte de cargas elétricas.

Quanto maior a condutividade elétrica, maior tende a ser a capacidade do material de conduzir corrente sob condições equivalentes.

A condutividade é representada pela letra grega sigma: **σ**.

Sua unidade no Sistema Internacional é o siemens por metro: **S/m**.

Onde:

- S = siemens;
- m = metro.

O siemens é a unidade de condutância elétrica e corresponde ao inverso do ohm:

```text
1 S = 1 / Ω
```

## 4.2. O que é corrente elétrica?

A corrente elétrica representa a taxa de transporte de carga elétrica através de uma seção de um material ou circuito.

Sua representação matemática é:

```text
I = ΔQ / Δt
```

Onde:

- I = corrente elétrica (A);
- ΔQ = quantidade de carga elétrica transferida (C);
- Δt = intervalo de tempo (s).

A unidade de corrente elétrica é o ampère (A).

No caso dos condutores metálicos, os principais portadores de carga são os elétrons.

**Atenção:** o sentido convencional da corrente elétrica é definido como o sentido em que cargas positivas se moveriam. Nos metais, o movimento médio dos elétrons ocorre no sentido oposto.

## 4.3. Por que os metais conduzem eletricidade?

Os metais apresentam uma estrutura eletrônica que permite a existência de elétrons de condução com mobilidade relativamente elevada.

Quando uma diferença de potencial é aplicada ao material, estabelece-se um campo elétrico que provoca uma velocidade média orientada desses elétrons.

Esse movimento resulta na corrente elétrica.

Exemplos:

| Material | Aplicação |
|---|---|
| Cobre | Fios, cabos e trilhas de PCB |
| Alumínio | Cabos elétricos e dissipadores |
| Prata | Contatos e aplicações especiais |
| Ouro | Contatos elétricos e conectores |

O cobre é amplamente utilizado na fabricação de trilhas de placas de circuito impresso devido à sua elevada condutividade elétrica.

# 5. Classificação dos Materiais

Os materiais podem ser classificados de acordo com suas propriedades de condução elétrica.

## 5.1. Condutores

São materiais que permitem o transporte de cargas elétricas com relativa facilidade.

Exemplos:

- Cobre;
- Alumínio;
- Prata;
- Ouro.

**Aplicação:** trilhas de PCB, conectores, terminais e cabos.

## 5.2. Isolantes

São materiais que apresentam elevada resistência à passagem de corrente elétrica em condições normais de utilização.

Exemplos:

- Borracha;
- Vidro;
- Cerâmica;
- Plásticos isolantes.

**Aplicação:** revestimento de fios, isolamento de componentes e separação de trilhas.

Um isolante não impede a corrente elétrica em qualquer circunstância. Sob tensões suficientemente elevadas, pode ocorrer ruptura dielétrica.

## 5.3. Semicondutores

Os semicondutores possuem propriedades elétricas controláveis, dependendo de fatores como temperatura, iluminação, composição química e dopagem.

Exemplos:

- Silício (Si);
- Germânio (Ge);
- Arseneto de gálio (GaAs).

**Aplicação:**

- Diodos;
- LEDs;
- Transistores;
- MOSFETs;
- Circuitos integrados;
- Microcontroladores;
- Processadores.

Sua principal característica é permitir o controle das propriedades elétricas do material, tornando possível desenvolver dispositivos capazes de retificar, amplificar, chavear e processar sinais.

## 5.4. Comparação entre materiais

| Característica | Condutores | Isolantes | Semicondutores |
|---|---|---|---|
| Condução elétrica | Elevada | Muito baixa em condições normais | Controlável |
| Resistividade | Baixa | Elevada | Variável |
| Exemplos | Cobre e alumínio | Borracha e vidro | Silício e germânio |
| Aplicação | Conexões elétricas | Isolamento | Dispositivos eletrônicos |

# 6. Resistividade Elétrica

## 6.1. O que é resistividade?

A resistividade elétrica é uma propriedade física que indica o quanto um material oferece oposição à passagem da corrente elétrica.

Sua representação é feita pela letra grega rho: **ρ**.

Sua unidade no Sistema Internacional é **ohm-metro (Ω·m)**.

A resistividade é uma propriedade característica do material em determinadas condições de temperatura e composição.

Quanto maior a resistividade, maior tende a ser a resistência elétrica de um corpo com as mesmas dimensões.

## 6.2. Relação entre resistividade e resistência

A resistência elétrica de um condutor depende de três fatores principais:

- Resistividade do material;
- Comprimento do condutor;
- Área da seção transversal.

A relação matemática é:

```text
R = ρ × (L / A)
```

Onde:

| Símbolo | Grandeza | Unidade no SI |
|---|---|---|
| R | Resistência elétrica | Ω |
| ρ | Resistividade | Ω·m |
| L | Comprimento | m |
| A | Área transversal | m² |

Essa equação permite compreender três situações:

1. Quanto maior o comprimento, maior será a resistência.
2. Quanto maior a área transversal, menor será a resistência.
3. Quanto maior a resistividade do material, maior será a resistência.

**Atenção às unidades:** se a resistividade for fornecida em Ω·m, use comprimento em metros e área em m². Se for fornecida em Ω·mm²/m, use comprimento em metros e área em mm².

# 7. Condutividade e Resistividade: Relação Matemática

A condutividade e a resistividade são propriedades inversamente relacionadas:

```text
σ = 1 / ρ
```

Onde:

- σ = condutividade elétrica (S/m, no SI);
- ρ = resistividade elétrica (Ω·m, no SI).

Portanto:

- Alta condutividade corresponde a baixa resistividade.
- Baixa condutividade corresponde a alta resistividade.

## 7.1. Entendendo o Siemens

O siemens (S) é a unidade de condutância elétrica.

A condutância representa a facilidade com que um elemento ou componente permite a passagem da corrente elétrica.

Sua relação com a resistência é:

```text
G = 1 / R
```

Onde:

- G = condutância (S);
- R = resistência (Ω).

Exemplo:

Se um resistor apresenta resistência de 10 Ω, sua condutância é:

```text
Dados:
R = 10 Ω

Fórmula:
G = 1 / R

Substituindo:
G = 1 / 10

Resultado:
G = 0,1 S
```

Isso significa que a condutância do resistor é de 0,1 siemens.

**Não confunda:** condutância é uma grandeza associada a um elemento ou componente elétrico; condutividade é uma propriedade física do material.

# 8. Unidades de Condutividade e Conversões

A unidade de condutividade no Sistema Internacional é **S/m**.

Em cálculos de condutores, também é comum encontrar a resistividade do cobre expressa em **Ω·mm²/m**. Quando usamos essa unidade de resistividade, sua recíproca fica expressa em **S·m/mm²**.

```text
Resistividade: ρ = Ω·mm²/m

Condutividade correspondente:
σ = 1 / ρ = S·m/mm²
```

Essa unidade adaptada é útil quando o comprimento é informado em metros e a seção transversal em milímetros quadrados.

## 8.1. Conversão entre m² e mm²

Sabemos que:

```text
1 m = 1.000 mm
```

Como estamos tratando de área, precisamos elevar essa relação ao quadrado:

```text
1 m² = (1.000 mm)²
1 m² = 1.000.000 mm²
```

Portanto:

```text
1 m² = 10⁶ mm²
```

Essa conversão é importante para evitar erros nos cálculos elétricos.

## 8.2. Conversão entre S/m e S·m/mm²

A relação entre as unidades é:

```text
1 S/m = 0,000001 S·m/mm²
1 S/m = 10⁻⁶ S·m/mm²
```

No sentido inverso:

```text
1 S·m/mm² = 1.000.000 S/m
1 S·m/mm² = 10⁶ S/m
```

**Como interpretar:** o valor numérico em S·m/mm² é um milhão de vezes menor que o valor correspondente em S/m. As duas unidades expressam a mesma propriedade física, mas usam unidades de área diferentes na representação.

Não confunda **S** (siemens, unidade de condutância) com **S/m** (unidade SI de condutividade).

# 9. Cálculos Resolvidos

## 9.1. Cálculo da resistência de um condutor de cobre

Considere um fio de cobre com as seguintes características:

| Grandeza | Valor |
|---|---:|
| Comprimento (L) | 10 m |
| Área (A) | 2,5 mm² |
| Resistividade (ρ) | 0,0172 Ω·mm²/m |
| Temperatura de referência | 20 °C |

Como a resistividade está em Ω·mm²/m, podemos usar o comprimento em metros e a área em mm².

**Fórmula:**

```text
R = ρ × (L / A)
```

**Passo 1 — Substituir os valores:**

```text
R = 0,0172 × (10 / 2,5)
```

**Passo 2 — Resolver a divisão:**

```text
10 / 2,5 = 4
```

**Passo 3 — Multiplicar:**

```text
R = 0,0172 × 4
R = 0,0688 Ω
```

**Resultado:**

```text
R = 0,0688 Ω
```

O fio apresenta resistência aproximada de 0,0688 ohm, considerando os valores e as condições informados.

## 9.2. Calculando a resistência com outra seção transversal

Agora considere o mesmo fio, com o mesmo comprimento e material, mas com seção transversal de 1,5 mm².

Dados:

- L = 10 m;
- A = 1,5 mm²;
- ρ = 0,0172 Ω·mm²/m.

Aplicando a fórmula:

```text
R = ρ × (L / A)

R = 0,0172 × (10 / 1,5)

R = 0,172 / 1,5

R ≈ 0,1147 Ω
```

Observe que a resistência aumentou quando a área transversal diminuiu.

Isso acontece porque, mantendo o material e o comprimento, uma seção transversal menor resulta em maior resistência elétrica.

## 9.3. Calculando a condutividade do cobre

Considere a resistividade:

```text
ρ = 0,0172 Ω·mm²/m
```

A relação entre condutividade e resistividade, usando essas unidades, é:

```text
σ = 1 / ρ

σ = 1 / 0,0172

σ ≈ 58,14 S·m/mm²
```

Esse resultado corresponde à condutividade expressa na unidade adaptada para área em mm².

Para expressar o resultado na unidade do Sistema Internacional (S/m), convertemos:

```text
58,14 S·m/mm² × 1.000.000
≈ 58.140.000 S/m

σ ≈ 5,814 × 10⁷ S/m
```

O valor é aproximado e depende da temperatura e das características do cobre considerado.

# 10. Influência da Temperatura na Condutividade

A temperatura pode alterar o comportamento elétrico dos materiais.

Nos metais, o aumento da temperatura geralmente provoca maior vibração da estrutura cristalina, aumentando a dispersão dos elétrons de condução e, consequentemente, a resistividade.

Nos semicondutores, o aumento da temperatura pode aumentar a quantidade de portadores de carga disponíveis, modificando sua condutividade.

Essa diferença é importante para compreender:

- Termistores;
- Sensores de temperatura;
- Circuitos de proteção térmica;
- Aquecimento de componentes;
- Diagnóstico de falhas em placas eletrônicas.

# 11. Aplicação na Eletrônica e Diagnóstico de PCBs

O conhecimento sobre estrutura atômica, condutividade e resistividade permite compreender por que diferentes materiais são utilizados na fabricação de componentes eletrônicos.

| Componente ou estrutura | Material ou propriedade relacionada | Função |
|---|---|---|
| Trilha de PCB | Cobre | Condução elétrica |
| Isolamento de cabos | Polímeros isolantes | Evitar contatos indesejados |
| Diodo | Junção semicondutora | Condução preferencial |
| Transistor | Material semicondutor | Controle de corrente |
| MOSFET | Estrutura semicondutora | Controle de condução por campo elétrico |
| Circuito integrado | Estruturas semicondutoras | Processamento e controle |

## 11.1. Exemplos de falhas

Durante o diagnóstico de uma placa eletrônica, esses conceitos ajudam a compreender diferentes situações:

**Trilha interrompida:** uma ruptura física no cobre pode interromper a continuidade elétrica.

**Conexão oxidada:** pode apresentar resistência de contato elevada.

**Solda defeituosa:** pode provocar mau contato ou interrupção elétrica.

**Semicondutor danificado:** pode apresentar comportamento elétrico diferente do esperado.

Entretanto, uma medição isolada de resistência ou continuidade não é suficiente para confirmar a causa de uma falha. É necessário considerar o circuito, as condições de medição e os possíveis caminhos elétricos em paralelo.

# 12. Exercícios de Fixação

Resolva os exercícios utilizando os conceitos e as fórmulas estudadas.

### Questão 01 — Estrutura atômica

Quais são as três partículas fundamentais que constituem um átomo? Identifique suas respectivas cargas elétricas.

### Questão 02 — Cargas elétricas

O que acontece com um átomo quando ele perde elétrons? E quando ganha elétrons?

### Questão 03 — Camada de valência

O que é a camada de valência e qual sua importância para compreender o comportamento elétrico dos materiais?

### Questão 04 — Condutividade

Por que o cobre é utilizado na fabricação de trilhas de placas de circuito impresso?

### Questão 05 — Classificação dos materiais

Qual é a diferença entre condutores, isolantes e semicondutores?

### Questão 06 — Resistividade

O que significa dizer que um material possui alta resistividade elétrica?

### Questão 07 — Relação matemática

Qual é a relação matemática entre condutividade e resistividade?

### Questão 08 — Resistência elétrica

Um fio de cobre possui comprimento de 20 metros, área transversal de 2,5 mm² e resistividade de 0,0172 Ω·mm²/m.

Calcule sua resistência elétrica.

### Questão 09 — Condutância

Um componente apresenta resistência de 20 Ω.

Calcule sua condutância em siemens.

### Questão 10 — Análise de condutores

Dois fios são fabricados com o mesmo material e possuem o mesmo comprimento. O primeiro possui seção transversal de 1,5 mm² e o segundo de 2,5 mm².

Qual deles apresenta maior resistência elétrica? Justifique matematicamente.

---

# 13. Atividade Prática de Observação

**Objetivo:** relacionar os conceitos de condutividade elétrica com a construção de uma placa de circuito impresso.

Utilizando uma placa eletrônica desenergizada e em condições seguras, identifique visualmente:

1. Uma região de trilha de cobre.
2. Uma região de material isolante da placa.
3. Um componente semicondutor, como um diodo ou transistor.
4. Um ponto de conexão entre componentes.

Registre as observações e explique a função de cada elemento.

Não é necessário realizar soldagem, remover componentes ou energizar a placa nesta atividade.

---

# 14. Resumo Técnico

A estrutura atômica determina propriedades fundamentais dos materiais, incluindo seu comportamento elétrico.

Os elétrons desempenham um papel essencial na condução elétrica, especialmente quando possuem condições para se movimentar através de um material.

A partir dessas propriedades, os materiais são classificados em condutores, isolantes e semicondutores.

A condutividade representa a facilidade de transporte de cargas elétricas, enquanto a resistividade representa a oposição característica do material à condução.

A resistência elétrica de um condutor depende da resistividade do material, de seu comprimento e de sua área transversal.

A relação matemática entre condutividade e resistividade permite compreender como diferentes materiais se comportam eletricamente.

Esses conceitos são fundamentais para compreender a construção e o funcionamento de circuitos eletrônicos, desde uma simples conexão de cobre até estruturas complexas de transistores e circuitos integrados.

---

# 15. Referências de Estudo

- Curso: Eletrônica Geral do Zero — Charles Henrique Santos.
- Livro: Fundamentos de Análise de Circuitos.
- Sistema Internacional de Unidades (SI).
- Documentação técnica de fabricantes de componentes.

---

# 16. Registro de Aprendizagem

| Indicador | Registro |
|---|---|
| Data de estudo | ____/____/____ |
| Compreensão teórica | 0 a 5 |
| Exercícios concluídos | ____/10 |
| Atividade prática | Pendente / Concluída |
| Dúvidas identificadas | A preencher |
| Próxima etapa | Tensão elétrica e diferença de potencial |

**Critério de domínio:** o conteúdo somente será considerado dominado quando houver compreensão demonstrada, capacidade de resolver exercícios e aplicação prática segura, quando aplicável.

---

**Próxima aula:** 01.02 — Tensão Elétrica, Diferença de Potencial e Campo Elétrico.
