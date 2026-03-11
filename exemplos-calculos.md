# Exemplos e Cálculos Práticos

## Relatividade Especial

### Exemplo 1: Dilatação do Tempo - Viagem Espacial

**Problema:** Um astronauta viaja em uma nave espacial a 80% da velocidade da luz (0.8c) por 5 anos segundo o relógio da nave. Quanto tempo passou na Terra?

**Solução:**

Fator de Lorentz:
```
γ = 1 / √(1 - v²/c²)
γ = 1 / √(1 - 0.8²)
γ = 1 / √(1 - 0.64)
γ = 1 / √0.36
γ = 1 / 0.6
γ ≈ 1.667
```

Tempo na Terra:
```
Δt_Terra = γ × Δt_nave
Δt_Terra = 1.667 × 5 anos
Δt_Terra ≈ 8.33 anos
```

**Resposta:** Enquanto 5 anos passaram na nave, aproximadamente 8.33 anos passaram na Terra.

---

### Exemplo 2: Contração do Comprimento

**Problema:** Uma nave espacial tem 100 metros de comprimento quando em repouso. Se ela viaja a 90% da velocidade da luz, qual seu comprimento observado da Terra?

**Solução:**

```
L' = L × √(1 - v²/c²)
L' = 100 × √(1 - 0.9²)
L' = 100 × √(1 - 0.81)
L' = 100 × √0.19
L' = 100 × 0.436
L' ≈ 43.6 metros
```

**Resposta:** A nave pareceria ter apenas 43.6 metros de comprimento para um observador na Terra.

---

### Exemplo 3: Energia Relativística

**Problema:** Qual é a energia total de um próton (massa = 1.673 × 10⁻²⁷ kg) em repouso?

**Solução:**

```
E = mc²
E = (1.673 × 10⁻²⁷ kg) × (3 × 10⁸ m/s)²
E = 1.673 × 10⁻²⁷ × 9 × 10¹⁶
E ≈ 1.506 × 10⁻¹⁰ Joules
E ≈ 938 MeV (mega-elétron-volts)
```

**Resposta:** A energia de repouso de um próton é aproximadamente 938 MeV.

---

### Exemplo 4: Velocidade Relativística

**Problema:** Se um elétron tem energia cinética igual à sua energia de repouso, qual sua velocidade?

**Solução:**

Energia total:
```
E_total = E_repouso + E_cinética = 2 × E_repouso
γ = E_total / E_repouso = 2
```

Resolver para v:
```
γ = 1 / √(1 - v²/c²) = 2
√(1 - v²/c²) = 0.5
1 - v²/c² = 0.25
v²/c² = 0.75
v = c × √0.75
v ≈ 0.866c
```

**Resposta:** O elétron está viajando a aproximadamente 86.6% da velocidade da luz.

---

## Relatividade Geral

### Exemplo 5: Desvio Gravitacional para o Vermelho

**Problema:** Calcule o desvio para o vermelho da luz que escapa da superfície do Sol.

**Dados:**
- Massa do Sol (M☉) = 1.989 × 10³⁰ kg
- Raio do Sol (R☉) = 6.96 × 10⁸ m
- G = 6.674 × 10⁻¹¹ N·m²/kg²
- c = 3 × 10⁸ m/s

**Solução:**

```
z = GM☉ / (R☉c²)
z = (6.674 × 10⁻¹¹ × 1.989 × 10³⁰) / (6.96 × 10⁸ × (3 × 10⁸)²)
z = (1.328 × 10²⁰) / (6.96 × 10⁸ × 9 × 10¹⁶)
z ≈ 2.12 × 10⁻⁶
```

**Resposta:** O desvio para o vermelho é aproximadamente 2.12 × 10⁻⁶, ou 2.12 partes por milhão.

---

### Exemplo 6: Raio de Schwarzschild (Buraco Negro)

**Problema:** Qual seria o raio de Schwarzschild da Terra se ela fosse comprimida em um buraco negro?

**Dados:**
- Massa da Terra (M⊕) = 5.972 × 10²⁴ kg
- G = 6.674 × 10⁻¹¹ N·m²/kg²
- c = 3 × 10⁸ m/s

**Solução:**

```
Rs = 2GM⊕ / c²
Rs = (2 × 6.674 × 10⁻¹¹ × 5.972 × 10²⁴) / (3 × 10⁸)²
Rs = (7.968 × 10¹⁴) / (9 × 10¹⁶)
Rs ≈ 8.87 × 10⁻³ metros
Rs ≈ 8.87 mm
```

**Resposta:** Se a Terra fosse comprimida em um buraco negro, seu raio de Schwarzschild seria aproximadamente 8.87 milímetros!

---

### Exemplo 7: Dilatação Gravitacional do Tempo (GPS)

**Problema:** Calcule a diferença de tempo entre um relógio em um satélite GPS (altitude ≈ 20.000 km) e um na superfície da Terra em um dia.

**Dados:**
- Massa da Terra (M⊕) = 5.972 × 10²⁴ kg
- Raio da Terra (R⊕) = 6.371 × 10⁶ m
- Altura do satélite (h) = 20.000 × 10³ m = 2 × 10⁷ m
- G = 6.674 × 10⁻¹¹ N·m²/kg²
- c = 3 × 10⁸ m/s

**Solução (aproximada):**

Na superfície:
```
Δt_sup/Δt = √(1 - 2GM⊕/(R⊕c²))
```

No satélite:
```
Δt_sat/Δt = √(1 - 2GM⊕/((R⊕+h)c²))
```

A diferença resulta em aproximadamente 45 microssegundos por dia.

**Resposta:** O relógio no satélite GPS "ganha" cerca de 45 microssegundos por dia devido ao efeito gravitacional (campo gravitacional mais fraco).

---

### Exemplo 8: Deflexão da Luz pelo Sol

**Problema:** Calcule o ângulo de deflexão da luz de uma estrela que passa tangencialmente à superfície do Sol.

**Solução:**

Fórmula de Einstein:
```
θ = 4GM☉ / (R☉c²)
θ = (4 × 6.674 × 10⁻¹¹ × 1.989 × 10³⁰) / (6.96 × 10⁸ × (3 × 10⁸)²)
θ = (5.312 × 10²⁰) / (6.264 × 10²⁵)
θ ≈ 8.48 × 10⁻⁶ radianos
```

Convertendo para segundos de arco:
```
θ ≈ 1.75 segundos de arco
```

**Resposta:** A luz é desviada por aproximadamente 1.75 segundos de arco, confirmado pela expedição de Eddington em 1919.

---

## Exercícios Propostos

### Relatividade Especial

1. Um múon cósmico viaja a 0.98c. Se sua vida média em repouso é 2.2 µs, quanto tempo ele vive do ponto de vista de um observador na Terra?

2. Quanto tempo levaria para viajar para Alpha Centauri (4.37 anos-luz) a 0.95c segundo: a) observadores na Terra? b) astronautas na nave?

3. Qual deve ser a velocidade de uma partícula para que sua massa relativística seja o dobro de sua massa de repouso?

### Relatividade Geral

4. Calcule o raio de Schwarzschild de um buraco negro com massa igual a 10 massas solares.

5. Se você caísse em direção a um buraco negro, quanto tempo você levaria para cruzar o horizonte de eventos do seu próprio ponto de vista comparado com um observador distante?

6. Estime a dilatação do tempo entre sua cabeça e seus pés enquanto está de pé na superfície da Terra.

## Respostas dos Exercícios

1. **~11 µs** (usando γ ≈ 5.03)
2. a) **~4.6 anos Terra**, b) **~1.4 anos nave**
3. **v ≈ 0.866c** (v = c√3/2)
4. **~29.5 km** (Rs = 2GM/c²)
5. **Tempo finito para você, infinito para observador distante**
6. **~1.6 × 10⁻¹⁶ segundos por segundo** (diferença muito pequena!)
