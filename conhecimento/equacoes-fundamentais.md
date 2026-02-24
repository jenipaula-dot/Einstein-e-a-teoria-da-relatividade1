# Equações Fundamentais da Relatividade

## 🎯 Introdução

Este documento apresenta as equações matemáticas fundamentais da Teoria da Relatividade, com explicações de cada termo e significado físico.

## ⚡ Relatividade Especial

### 1. Fator de Lorentz (γ)

**A Equação Mais Importante da Relatividade Especial**:
```
γ = 1 / √(1 - v²/c²)
```

**Termos**:
- γ (gama): Fator de Lorentz
- v: velocidade do objeto
- c: velocidade da luz (299.792.458 m/s)

**Significado Físico**:
Quantifica quão significativos são os efeitos relativísticos. Aparece em quase todas as equações da relatividade especial.

**Valores Típicos**:
| Velocidade | γ | Efeito |
|-----------|---|--------|
| v = 0 | 1,000 | Nenhum efeito relativístico |
| v = 0,1c | 1,005 | ~0,5% de efeito |
| v = 0,5c | 1,155 | ~15% de efeito |
| v = 0,866c | 2,000 | Tempo/comprimento × 2 |
| v = 0,99c | 7,089 | Tempo/comprimento × 7 |
| v = 0,999c | 22,366 | Efeitos dramáticos |
| v → c | ∞ | Impossível para massa |

---

### 2. Dilatação Temporal

**Equação**:
```
Δt = γ Δt₀
```

ou equivalentemente:
```
Δt = Δt₀ / √(1 - v²/c²)
```

**Termos**:
- Δt: intervalo de tempo medido por observador em repouso
- Δt₀: intervalo de tempo próprio (medido no referencial do objeto em movimento)
- v: velocidade relativa
- γ: fator de Lorentz

**Interpretação**:
"Relógios em movimento correm mais devagar"

**Exemplo Numérico**:
```
Nave a v = 0,866c (γ = 2)
Tempo próprio na nave: 1 ano
Tempo na Terra: 2 anos
```

**Paradoxo dos Gêmeos**:
```
t_viajante = t_Terra / γ
```

---

### 3. Contração do Comprimento

**Equação**:
```
L = L₀ / γ
```

ou:
```
L = L₀ √(1 - v²/c²)
```

**Termos**:
- L: comprimento medido por observador em repouso
- L₀: comprimento próprio (no referencial de repouso do objeto)
- v: velocidade do objeto
- γ: fator de Lorentz

**Interpretação**:
"Objetos em movimento são contraídos na direção do movimento"

**Características**:
- Apenas na direção paralela ao movimento
- Dimensões perpendiculares não são afetadas
- Efeito real, não ilusão óptica

**Exemplo**:
```
Nave de 100m a v = 0,6c (γ = 1,25)
Comprimento observado: 100m / 1,25 = 80m
```

---

### 4. Adição Relativística de Velocidades

**Problema**: Velocidades não se somam simplesmente em altas velocidades.

**Equação**:
```
u = (v + w) / (1 + vw/c²)
```

**Termos**:
- u: velocidade resultante (relativa ao observador)
- v: velocidade do objeto 1
- w: velocidade do objeto 2 relativa ao objeto 1
- c: velocidade da luz

**Propriedades**:
1. Se v, w << c: u ≈ v + w (soma clássica)
2. Se v = c ou w = c: u = c (luz sempre viaja a c)
3. u < c sempre (impossível ultrapassar c)

**Exemplo**:
```
Nave a v = 0,9c dispara projétil a w = 0,9c

Clássico: u = 0,9c + 0,9c = 1,8c (ERRADO!)

Relativístico:
u = (0,9c + 0,9c) / (1 + 0,9c×0,9c/c²)
u = 1,8c / (1 + 0,81)
u = 1,8c / 1,81
u ≈ 0,9945c ✓
```

---

### 5. Equivalência Massa-Energia

**A Equação Mais Famosa**:
```
E = mc²
```

**Termos**:
- E: energia total
- m: massa
- c: velocidade da luz

**Interpretação**:
Massa e energia são manifestações da mesma entidade fundamental.

**Forma Completa com Energia Cinética**:
```
E² = (pc)² + (m₀c²)²
```

**Termos**:
- E: energia total
- p: momento
- m₀: massa de repouso
- c: velocidade da luz

**Para partícula em repouso (p = 0)**:
```
E = m₀c²
```

**Para fóton (m₀ = 0)**:
```
E = pc = hf
```

**Energia Cinética Relativística**:
```
K = (γ - 1)m₀c²
```

**Limite não-relativístico** (v << c):
```
K ≈ ½m₀v² (energia cinética clássica)
```

---

### 6. Massa Relativística (conceito histórico)

**Equação**:
```
m = γm₀
```

**Termos**:
- m: "massa relativística" (termo em desuso)
- m₀: massa de repouso (invariante)
- γ: fator de Lorentz

**Nota Moderna**:
Físicos modernos preferem usar apenas massa invariante (m₀) e energia total.

---

### 7. Momento Relativístico

**Equação**:
```
p = γm₀v
```

**Termos**:
- p: momento relativístico
- m₀: massa de repouso
- v: velocidade
- γ: fator de Lorentz

**Conservação**:
O momento relativístico é conservado em todas as interações.

---

### 8. Transformações de Lorentz

**Coordenadas Espaciais e Temporais**:

Em movimento na direção x com velocidade v:

```
x' = γ(x - vt)
y' = y
z' = z
t' = γ(t - vx/c²)
```

**Inversas**:
```
x = γ(x' + vt')
y = y'
z = z'
t = γ(t' + vx'/c²)
```

**Termos**:
- (x, y, z, t): coordenadas no sistema original
- (x', y', z', t'): coordenadas no sistema em movimento
- v: velocidade relativa entre sistemas
- γ: fator de Lorentz

**Significado**:
Essas equações mostram como espaço e tempo se misturam quando mudamos de referencial.

---

### 9. Intervalo Espaço-Temporal (Invariante)

**Equação**:
```
s² = c²t² - x² - y² - z²
```

ou na notação de Minkowski:
```
s² = c²t² - r²
```

**Propriedade Fundamental**:
**s² é o mesmo em todos os referenciais inerciais** (invariante)

**Tipos de Intervalos**:

1. **Tipo Tempo** (s² > 0):
   - Eventos podem ser conectados por trajetória subluminal
   - Relação causal possível

2. **Tipo Luz** (s² = 0):
   - Eventos conectados por raio de luz
   - Cone de luz

3. **Tipo Espaço** (s² < 0):
   - Eventos causalmente desconectados
   - Nenhum sinal pode conectá-los

---

## 🌌 Relatividade Geral

### 10. Equação de Campo de Einstein

**A Equação Mais Bela da Física**:
```
Rμν - ½gμνR + Λgμν = (8πG/c⁴)Tμν
```

**Forma Compacta**:
```
Gμν + Λgμν = (8πG/c⁴)Tμν
```

**Termos**:
- **Rμν**: Tensor de Ricci (curvatura do espaço-tempo)
- **gμν**: Tensor métrico (geometria do espaço-tempo)
- **R**: Escalar de curvatura (contração de Rμν)
- **Gμν**: Tensor de Einstein (= Rμν - ½gμνR)
- **Λ**: Constante cosmológica (energia escura)
- **G**: Constante gravitacional de Newton
- **c**: Velocidade da luz
- **Tμν**: Tensor energia-momento (matéria e energia)

**Significado em Palavras**:
```
[Geometria do Espaço-Tempo] = [Distribuição de Matéria e Energia]

ou

"Matéria diz ao espaço-tempo como curvar;
 Espaço-tempo curvo diz à matéria como mover"
```

**Características**:
- 10 equações diferenciais parciais não-lineares acopladas
- Soluções exatas são raras
- Maioria requer métodos numéricos

---

### 11. Métrica de Schwarzschild

**Solução para Buraco Negro Esférico Não-Rotativo**:

```
ds² = -(1 - rs/r)c²dt² + (1 - rs/r)⁻¹dr² + r²dΩ²
```

**Termos**:
- ds²: elemento de linha (intervalo espaço-temporal)
- rs: raio de Schwarzschild = 2GM/c²
- r: distância radial do centro
- t: tempo
- dΩ²: elemento angular (= dθ² + sin²θ dφ²)

**Raio de Schwarzschild**:
```
rs = 2GM/c²
```

**Valores**:
- Terra: rs ≈ 9 mm
- Sol: rs ≈ 3 km
- Buraco negro estelar típico: rs ≈ 10-30 km

**Horizonte de Eventos**:
Superfície em r = rs onde o tempo "para" para observador distante.

---

### 12. Dilatação Temporal Gravitacional

**Equação Aproximada** (campo fraco):
```
Δt₂/Δt₁ ≈ √(1 - 2GM/r₁c²) / √(1 - 2GM/r₂c²)
```

**Aproximação de Campo Fraco**:
```
Δt₂/Δt₁ ≈ 1 + (GM/c²)(1/r₁ - 1/r₂)
```

**ou em termos de potencial gravitacional Φ**:
```
Δt₂/Δt₁ ≈ 1 + ΔΦ/c²
```

**Termos**:
- Δt₁, Δt₂: intervalos de tempo em posições 1 e 2
- G: constante gravitacional
- M: massa do objeto gravitante
- r₁, r₂: distâncias radiais
- Φ: potencial gravitacional

**Interpretação**:
Relógios em campos gravitacionais mais fortes correm mais devagar.

**Exemplo GPS**:
```
h ≈ 20.000 km (altitude satélite)
ΔΦ/c² ≈ 5 × 10⁻¹⁰
Efeito: ~45 microsegundos/dia mais rápido
```

---

### 13. Desvio Gravitacional da Luz

**Ângulo de Deflexão**:
```
θ = 4GM/bc²
```

**Termos**:
- θ: ângulo de deflexão
- G: constante gravitacional
- M: massa do objeto deflector
- b: parâmetro de impacto (distância mínima)
- c: velocidade da luz

**Para Luz Passando Tangente ao Sol**:
```
θ ≈ 1,75 segundos de arco
```

**Comparação**:
- Newton (luz como partícula): 0,875"
- Einstein (geometria do espaço-tempo): 1,75"
- Observado (1919): 1,75" ✓

---

### 14. Redshift Gravitacional

**Mudança de Frequência**:
```
ν₂/ν₁ = √(1 - rs/r₁) / √(1 - rs/r₂)
```

**Aproximação de Campo Fraco**:
```
Δν/ν ≈ -ΔΦ/c²
```

**Termos**:
- ν₁, ν₂: frequências em posições 1 e 2
- rs: raio de Schwarzschild
- Φ: potencial gravitacional

**Interpretação**:
Luz perde energia (frequência diminui) ao subir em campo gravitacional.

**Redshift** quando sobe (Δν < 0)
**Blueshift** quando desce (Δν > 0)

---

### 15. Precessão do Periélio

**Taxa de Precessão**:
```
ε = 6πGM/c²a(1-e²)
```

**Termos**:
- ε: precessão por órbita (radianos)
- G: constante gravitacional
- M: massa do corpo central
- a: semi-eixo maior da órbita
- e: excentricidade da órbita
- c: velocidade da luz

**Para Mercúrio**:
```
ε ≈ 43" de arco por século
```

Concordância perfeita com observações!

---

### 16. Ondas Gravitacionais

**Equação de Onda Linearizada**:
```
□hμν = -(16πG/c⁴)Tμν
```

**Termos**:
- □: operador d'Alembertiano (∂²/∂t² - ∇²)
- hμν: perturbação métrica
- Tμν: tensor energia-momento
- G: constante gravitacional

**Amplitude de Onda**:
```
h ~ (G/c⁴)(M/r)
```

**Para Sistema Binário**:
```
h ~ (2G²/c⁴r)(M₁M₂/a)
```

**Termos**:
- h: amplitude da onda
- M: massa total
- M₁, M₂: massas individuais
- r: distância do observador
- a: separação orbital

**Detecção LIGO** (2015):
```
h ~ 10⁻²¹
Distorção: 1/10.000 do raio de um próton!
```

---

### 17. Métrica de Friedmann-Lemaître-Robertson-Walker (FLRW)

**Para o Universo como um Todo**:
```
ds² = -c²dt² + a(t)²[dr²/(1-kr²) + r²dΩ²]
```

**Termos**:
- a(t): fator de escala (tamanho do universo)
- k: curvatura espacial
  - k = +1: universo fechado (esférico)
  - k = 0: universo plano
  - k = -1: universo aberto (hiperbólico)

**Equações de Friedmann**:
```
(ȧ/a)² = (8πG/3)ρ - kc²/a² + Λc²/3

ä/a = -(4πG/3)(ρ + 3p/c²) + Λc²/3
```

**Termos**:
- ȧ: derivada temporal de a(t)
- ä: segunda derivada de a(t)
- ρ: densidade de energia
- p: pressão
- Λ: constante cosmológica

**Lei de Hubble**:
```
v = H₀d
```

onde H₀ = ȧ/a é a constante de Hubble.

---

## 🔢 Constantes Fundamentais

**Velocidade da Luz**:
```
c = 299.792.458 m/s (exato, por definição)
```

**Constante Gravitacional**:
```
G = 6,674 × 10⁻¹¹ m³/(kg·s²)
```

**Constante de Planck**:
```
h = 6,626 × 10⁻³⁴ J·s
ℏ = h/2π = 1,055 × 10⁻³⁴ J·s
```

**Escalas Naturais (Planck)**:
```
Comprimento de Planck: lₚ = √(ℏG/c³) ≈ 1,6 × 10⁻³⁵ m
Tempo de Planck: tₚ = √(ℏG/c⁵) ≈ 5,4 × 10⁻⁴⁴ s
Massa de Planck: mₚ = √(ℏc/G) ≈ 2,2 × 10⁻⁸ kg
Energia de Planck: Eₚ = √(ℏc⁵/G) ≈ 1,2 × 10¹⁹ GeV
```

---

## 🎓 Unidades Naturais

Em física teórica, frequentemente usamos:
```
c = 1 (velocidade da luz)
ℏ = 1 (constante de Planck reduzida)
G = 1 (constante gravitacional)
```

**Conversões**:
- Massa = Energia: E = m
- Tempo = Distância: t = x
- Força = 1/Área: F = 1/L²

---

## 📊 Tabela Resumo: Efeitos Relativísticos

| Velocidade | γ | Tempo (relativo) | Comprimento (relativo) |
|-----------|---|------------------|----------------------|
| 0,001c | 1,0000005 | ~1,0 | ~1,0 |
| 0,01c | 1,00005 | ~1,0 | ~1,0 |
| 0,1c | 1,005 | 1,005 | 0,995 |
| 0,5c | 1,155 | 1,155 | 0,866 |
| 0,9c | 2,294 | 2,294 | 0,436 |
| 0,99c | 7,089 | 7,089 | 0,141 |
| 0,999c | 22,366 | 22,366 | 0,045 |
| 0,9999c | 70,712 | 70,712 | 0,014 |

---

## 🔗 Conexões

**Conceitos Teóricos**:
- [Conceitos Fundamentais](../docs/conceitos-fundamentais.md)
- [Teoria da Relatividade Especial](../docs/teoria-relatividade-especial.md)
- [Teoria da Relatividade Geral](../docs/teoria-relatividade-geral.md)

**Visualização**:
- [Experimentos Mentais](experimentos-mentais.md)

**Aplicações**:
- [Aplicações Práticas](../docs/aplicacoes-praticas.md)

---

*"Deus não se importa com nossas dificuldades matemáticas. Ele integra empiricamente." - Albert Einstein*
