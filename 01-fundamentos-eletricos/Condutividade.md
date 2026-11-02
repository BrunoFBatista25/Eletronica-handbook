# 01.03 — Condutividade Elétrica, Resistividade, Condutores e Semicondutores

**Handbook de Eletrônica | Fundamentos Elétricos**

| Identificação | Descrição |
|---|---|
| Módulo | 01 — Fundamentos Elétricos |
| Nota | 01.03 |
| Nível | Introdutório a intermediário |
| Área | Materiais e propriedades elétricas |
| Aplicação | Componentes eletrônicos e diagnóstico de PCBs |
| Status | Em estudo |

> **Disclaimer — Conteúdo matemático e físico**
>
> Esta nota apresenta a relação entre estrutura eletrônica e condução elétrica, incluindo resistividade, condutividade, mobilidade, bandas de energia e dopagem de semicondutores.
>
> Serão utilizados cálculos de resistência, condutividade, densidade de corrente e conversões de unidades.

# 1. Introdução

A condução elétrica depende da capacidade de um material permitir o movimento de portadores de carga.

Esses portadores podem ser elétrons ou lacunas, dependendo do material e do mecanismo de condução.

A estrutura atômica e eletrônica determina a facilidade com que esses portadores podem participar do transporte de carga.

Por esse motivo, os materiais são classificados em:

- Condutores;
- Isolantes;
- Semicondutores.

# 2. Condutividade elétrica

A condutividade elétrica representa a capacidade de um material conduzir corrente elétrica.

É representada pela letra grega sigma:

```text
σ
```

Sua unidade no Sistema Internacional é:

```text
S/m
```

Onde S representa siemens e m representa metro.

Quanto maior a condutividade, maior tende a ser a capacidade de conduzir corrente sob condições equivalentes.

# 3. Resistividade elétrica

A resistividade representa a oposição característica de um material à condução elétrica.

É representada pela letra grega rho:

```text
ρ
```

Sua unidade no Sistema Internacional é:

```text
Ω·m
```

Condutividade e resistividade são grandezas inversamente relacionadas:

```text
σ = 1 / ρ
```

E:

```text
ρ = 1 / σ
```

Um material com alta condutividade possui baixa resistividade, enquanto um material com baixa condutividade apresenta alta resistividade.

# 4. Condutores elétricos

Condutores são materiais que permitem o movimento de cargas elétricas com relativa facilidade.

Nos metais, a condução ocorre principalmente pelo movimento dos elétrons de condução.

Exemplos:

| Material | Aplicação |
|---|---|
| Cobre | Trilhas de PCB e cabos |
| Alumínio | Cabos e dissipadores |
| Prata | Contatos especiais |
| Ouro | Conectores e contatos |

O cobre é amplamente utilizado em placas de circuito impresso devido à sua boa condutividade, facilidade de fabricação e custo em relação a outros metais de elevada condutividade.

# 5. Isolantes elétricos

Os isolantes apresentam elevada resistividade elétrica em condições normais.

Neles, os portadores de carga não possuem mobilidade suficiente para produzir uma corrente significativa nas condições usuais de operação.

Exemplos:

- Vidro;
- Borracha;
- Cerâmica;
- Plásticos;
- Materiais poliméricos.

Os isolantes são utilizados para impedir contatos elétricos indesejados e separar regiões condutoras.

Entretanto, nenhum isolante suporta qualquer intensidade de campo elétrico. Se o campo ultrapassar sua capacidade dielétrica, pode ocorrer ruptura.

# 6. Semicondutores

Semicondutores são materiais cuja condutividade elétrica pode ser controlada por fatores como:

- Temperatura;
- Iluminação;
- Dopagem;
- Campo elétrico;
- Composição do material.

Os materiais semicondutores mais conhecidos são:

- Silício (Si);
- Germânio (Ge);
- Arseneto de gálio (GaAs).

A característica mais importante dos semicondutores é a possibilidade de controlar a concentração e o comportamento dos portadores de carga.

Isso permite construir diodos, transistores, MOSFETs e circuitos integrados.

# 7. Teoria das bandas de energia

Para compreender os semicondutores, é necessário estudar a estrutura de bandas de energia dos sólidos.

Em um material sólido, os níveis de energia dos elétrons formam conjuntos de estados permitidos chamados bandas.

Duas bandas são especialmente importantes:

**Banda de valência:** região de energia associada aos estados eletrônicos ocupados que participam das ligações do material.

**Banda de condução:** região de energia na qual os elétrons podem participar da condução elétrica.

Entre essas bandas pode existir uma região sem estados eletrônicos permitidos, chamada banda proibida ou *band gap*.

A energia dessa região influencia o comportamento elétrico do material.

## 7.1. Condutores

Nos metais, existe uma estrutura de bandas que permite a disponibilidade de estados eletrônicos próximos para a condução.

Por isso, os elétrons podem responder ao campo elétrico e participar do transporte de carga.

## 7.2. Isolantes

Nos isolantes, a separação energética entre a banda de valência e a banda de condução costuma ser elevada.

Em condições normais, poucos elétrons conseguem atingir estados de condução.

## 7.3. Semicondutores

Nos semicondutores, a banda proibida é relativamente menor que em muitos isolantes.

Assim, fatores como temperatura, iluminação e dopagem podem aumentar a quantidade de portadores disponíveis para condução.

# 8. Elétrons e lacunas

Nos semicondutores, a condução elétrica pode ocorrer por meio de dois tipos de portadores:

**Elétrons:** portadores de carga negativa que participam da condução na banda de condução.

**Lacunas:** estados vazios na banda de valência que se comportam como portadores de carga positiva.

Uma lacuna não é uma partícula física independente equivalente ao próton. É uma representação do comportamento coletivo dos elétrons na estrutura do material.

Quando um elétron se desloca para preencher uma lacuna, deixa outra lacuna em sua posição anterior.

Esse processo permite descrever o movimento aparente das lacunas.

# 9. Dopagem de semicondutores

A dopagem é o processo de introduzir impurezas controladas em um semicondutor para modificar sua concentração de portadores de carga.

No silício, por exemplo, é possível produzir materiais do tipo N e do tipo P.

## 9.1. Semicondutor tipo N

É produzido pela introdução de impurezas doadoras, geralmente elementos pentavalentes, como fósforo.

Esses átomos possuem cinco elétrons de valência.

Na estrutura do silício, quatro participam das ligações covalentes, enquanto o elétron adicional pode ser disponibilizado para condução.

Os elétrons são os portadores majoritários.

## 9.2. Semicondutor tipo P

É produzido pela introdução de impurezas aceitadoras, geralmente elementos trivalentes, como boro.

Esses átomos possuem três elétrons de valência.

Ao participar da estrutura cristalina do silício, deixam uma ligação incompleta, associada à formação de uma lacuna.

As lacunas são os portadores majoritários.

## 9.3. Comparação

| Característica | Tipo N | Tipo P |
|---|---|---|
| Dopagem | Doadora | Aceitadora |
| Exemplo | Fósforo | Boro |
| Portador majoritário | Elétron | Lacuna |
| Portador minoritário | Lacuna | Elétron |

# 10. Mobilidade dos portadores

A mobilidade elétrica indica a facilidade com que um portador de carga se desloca em resposta a um campo elétrico.

É representada pela letra grega mi:

```text
μ
```

A relação simplificada entre velocidade de deriva e campo elétrico é:

```text
vᵈ = μ × E
```

Onde:

- vᵈ = velocidade de deriva (m/s);
- μ = mobilidade (m²/V·s);
- E = campo elétrico (V/m).

A mobilidade influencia diretamente a condutividade de um material.

Em um semicondutor com elétrons e lacunas:

```text
σ = q × (n × μₙ + p × μₚ)
```

Onde:

- q = módulo da carga elementar (C);
- n = concentração de elétrons (m⁻³);
- p = concentração de lacunas (m⁻³);
- μₙ = mobilidade dos elétrons (m²/V·s);
- μₚ = mobilidade das lacunas (m²/V·s).

Essa expressão demonstra que a condutividade depende da quantidade de portadores e da mobilidade de cada tipo.

# 11. Relação entre resistência, comprimento e área

A resistência de um condutor uniforme pode ser calculada por:

```text
R = ρ × (L / A)
```

Onde:

- R = resistência (Ω);
- ρ = resistividade (Ω·m);
- L = comprimento (m);
- A = área transversal (m²).

Consequências:

- Aumentar o comprimento aumenta a resistência.
- Aumentar a área transversal diminui a resistência.
- Aumentar a resistividade aumenta a resistência.

# 12. Condutividade e unidades adaptadas

No Sistema Internacional:

```text
σ = S/m
ρ = Ω·m
```

Em cálculos de fios, pode-se utilizar:

```text
ρ = Ω·mm²/m
```

A unidade recíproca correspondente é:

```text
σ = S·m/mm²
```

A conversão é:

```text
1 S/m = 10⁻⁶ S·m/mm²
```

E:

```text
1 S·m/mm² = 10⁶ S/m
```

Não confunda condutividade com condutância.

**Condutância:** propriedade elétrica de um componente ou elemento, medida em siemens (S).

**Condutividade:** propriedade física do material, medida em S/m no Sistema Internacional.

# 13. Cálculos resolvidos

## 13.1. Resistência de um fio de cobre

Dados:

```text
L = 10 m
A = 2,5 mm²
ρ = 0,0172 Ω·mm²/m
```

Fórmula:

```text
R = ρ × (L / A)
```

Substituindo:

```text
R = 0,0172 × (10 / 2,5)

R = 0,0172 × 4

R = 0,0688 Ω
```

Resultado:

```text
R = 0,0688 Ω
```

O valor é aproximado e considera a resistividade informada.

## 13.2. Efeito da redução da área

Considere agora:

```text
L = 10 m
A = 1,5 mm²
ρ = 0,0172 Ω·mm²/m
```

Aplicando:

```text
R = 0,0172 × (10 / 1,5)

R = 0,172 / 1,5

R ≈ 0,1147 Ω
```

A resistência aumentou porque a área transversal diminuiu.

## 13.3. Condutividade do cobre

Dados:

```text
ρ = 0,0172 Ω·mm²/m
```

Aplicando:

```text
σ = 1 / ρ

σ = 1 / 0,0172

σ ≈ 58,14 S·m/mm²
```

Convertendo para S/m:

```text
σ ≈ 58,14 × 10⁶ S/m

σ ≈ 5,814 × 10⁷ S/m
```

# 14. Influência da temperatura

A temperatura altera a condutividade dos materiais.

Nos metais, o aumento da temperatura geralmente aumenta a resistividade, pois a vibração da rede cristalina provoca maior dispersão dos elétrons.

Nos semicondutores, o aumento da temperatura tende a elevar a concentração de portadores intrínsecos, podendo aumentar a condutividade.

O comportamento real depende do material, da dopagem e das condições de operação.

# 15. Aplicação na manutenção eletrônica

O conhecimento sobre condutividade e resistividade permite interpretar situações como:

**Trilha interrompida:** perda da continuidade do caminho condutor.

**Oxidação:** aumento da resistência de contato.

**Curto-circuito:** existência de um caminho de baixa impedância não previsto pelo projeto.

**Semicondutor danificado:** comportamento elétrico fora das características esperadas.

**Aquecimento excessivo:** pode estar relacionado a corrente elevada, resistência de contato, perdas de condução ou defeito em componentes.

Nenhum desses diagnósticos deve ser confirmado apenas pela aparência. É necessário realizar testes adequados e seguros.

# 16. Exercícios de Fixação

1. O que é condutividade elétrica?
2. Qual é a diferença entre condutividade e resistividade?
3. Por que o cobre é um bom condutor?
4. Qual é a diferença entre condutores e isolantes?
5. O que caracteriza um semicondutor?
6. O que são bandas de energia?
7. Qual é a diferença entre banda de valência e banda de condução?
8. O que são elétrons e lacunas?
9. Qual é a diferença entre semicondutor tipo N e tipo P?
10. O que é dopagem?
11. O que representa a mobilidade dos portadores?
12. Como a temperatura influencia a condutividade de metais e semicondutores?

# 17. Resumo Técnico

A condutividade elétrica depende da disponibilidade e da mobilidade dos portadores de carga.

Os metais apresentam elevada capacidade de condução devido à estrutura de bandas e à presença de elétrons de condução.

Os isolantes apresentam baixa disponibilidade de portadores em condições normais.

Os semicondutores possuem propriedades controláveis por dopagem, temperatura, iluminação e campo elétrico.

A compreensão desses materiais é essencial para estudar diodos, transistores, MOSFETs e circuitos integrados.

---

**Próxima nota:** 01.04 — Grandezas Elétricas, Diferença de Potencial, Resistência e Potência.
