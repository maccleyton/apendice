# Guia Completo de Fórmulas com Explicações Detalhadas

## 📋 ÍNDICE
1. Matemática
2. Física
3. Química
4. Biologia
5. Ciência da Computação
6. Engenharia
7. Economia e Finanças
8. Astronomia
9. Farmacologia
10. Geografia
11. Música e Acústica

---

## 📐 MATEMÁTICA

### Álgebra Básica - Produtos Notáveis

**Quadrado da soma:**
- `(a + b)² = a² + 2ab + b²`
- a, b = quaisquer números/expressões

**Quadrado da diferença:**
- `(a - b)² = a² - 2ab + b²`

**Produto da soma pela diferença:**
- `(a + b)(a - b) = a² - b²`

**Cubo da soma:**
- `(a + b)³ = a³ + 3a²b + 3ab² + b³`

**Cubo da diferença:**
- `(a - b)³ = a³ - 3a²b + 3ab² - b³`

### Equação do 2º Grau

**Fórmula de Bhaskara:**
- `x = (-b ± √(b² - 4ac)) / 2a`
- x = raízes da equação
- a = coeficiente de x²
- b = coeficiente de x
- c = termo independente
- Equação: ax² + bx + c = 0

**Discriminante (Δ):**
- `Δ = b² - 4ac`
- Δ > 0: duas raízes reais distintas
- Δ = 0: duas raízes reais iguais
- Δ < 0: raízes complexas

**Relações de Girard:**
- Soma: `x₁ + x₂ = -b/a`
- Produto: `x₁ · x₂ = c/a`

### Geometria Plana - Áreas

**Quadrado:** `A = l²`
- A = área, l = lado

**Retângulo:** `A = b × h`
- b = base, h = altura

**Triângulo:** `A = (b × h) / 2`
- b = base, h = altura perpendicular

**Triângulo (Herão):** `A = √[s(s-a)(s-b)(s-c)]`
- s = (a+b+c)/2 = semiperímetro
- a, b, c = lados

**Círculo:** `A = πr²`
- π ≈ 3,14159, r = raio

**Trapézio:** `A = [(B + b) × h] / 2`
- B = base maior, b = base menor, h = altura

**Losango:** `A = (D × d) / 2`
- D = diagonal maior, d = diagonal menor

**Perímetro do círculo:** `C = 2πr = πd`
- d = diâmetro = 2r

**Teorema de Pitágoras:** `a² + b² = c²`
- a, b = catetos, c = hipotenusa

### Geometria Espacial - Volumes

**Cubo:** `V = a³`
- a = aresta

**Paralelepípedo:** `V = a × b × c`
- a, b, c = dimensões

**Prisma:** `V = Ab × h`
- Ab = área da base, h = altura

**Pirâmide:** `V = (Ab × h) / 3`

**Cilindro:** `V = πr²h`
- r = raio da base, h = altura

**Cone:** `V = (πr²h) / 3`

**Esfera:** `V = (4πr³) / 3`

**Áreas de superfície:**
- Cubo: `A = 6a²`
- Esfera: `A = 4πr²`
- Cilindro: `A = 2πr² + 2πrh`

### Trigonometria

**Relação fundamental:** `sen²θ + cos²θ = 1`

**Tangente:** `tan θ = sen θ / cos θ`

**Lei dos Senos:** `a/sen A = b/sen B = c/sen C = 2R`
- a, b, c = lados
- A, B, C = ângulos opostos
- R = raio da circunferência circunscrita

**Lei dos Cossenos:** `a² = b² + c² - 2bc·cos A`

**Valores notáveis:**
- sen 30° = 1/2, cos 30° = √3/2, tan 30° = √3/3
- sen 45° = √2/2, cos 45° = √2/2, tan 45° = 1
- sen 60° = √3/2, cos 60° = 1/2, tan 60° = √3

### Matemática Financeira

**Juros simples:**
- `J = C × i × t`
- `M = C(1 + it)`
- J = juro, C = capital, i = taxa, t = tempo, M = montante

**Juros compostos:** `M = C(1 + i)ⁿ`
- n = número de períodos

**Desconto simples:** `D = N × i × t`
- D = desconto, N = valor nominal

### Estatística

**Média aritmética:** `x̄ = Σx / n`
- x̄ = média, Σx = soma dos valores, n = quantidade

**Média ponderada:** `x̄ = Σ(x·p) / Σp`
- p = pesos

**Variância:** `σ² = Σ(x - x̄)² / n`
- σ² = variância

**Desvio padrão:** `σ = √[Σ(x - x̄)² / n]`

**Coeficiente de variação:** `CV = (σ / x̄) × 100%`

### Análise Combinatória

**Arranjo:** `Aₙ,ₚ = n! / (n-p)!`
- n = total, p = escolhidos, ordem importa

**Combinação:** `Cₙ,ₚ = n! / [p!(n-p)!]`
- ordem NÃO importa

**Permutação:** `Pₙ = n!`

**Permutação com repetição:** `Pₙ^(a,b,c) = n! / (a!·b!·c!)`

### Progressões

**PA - Termo geral:** `aₙ = a₁ + (n-1)r`
- aₙ = n-ésimo termo, a₁ = primeiro termo, r = razão, n = posição

**PA - Soma:** `Sₙ = n(a₁ + aₙ) / 2`

**PG - Termo geral:** `aₙ = a₁ · qⁿ⁻¹`
- q = razão

**PG - Soma finita:** `Sₙ = a₁(qⁿ - 1) / (q - 1)`

**PG - Soma infinita:** `S∞ = a₁ / (1 - q)` (|q| < 1)

### Cálculo - Derivadas

**Potência:** `d/dx(xⁿ) = n·xⁿ⁻¹`

**Produto:** `(f·g)' = f'g + fg'`

**Quociente:** `(f/g)' = (f'g - fg') / g²`

**Regra da cadeia:** `d/dx[f(g(x))] = f'(g(x))·g'(x)`

**Exponencial:** `d/dx(eˣ) = eˣ`

**Logaritmo:** `d/dx(ln x) = 1/x`

**Seno:** `d/dx(sen x) = cos x`

**Cosseno:** `d/dx(cos x) = -sen x`

### Cálculo - Integrais

**Potência:** `∫xⁿ dx = xⁿ⁺¹/(n+1) + C` (n ≠ -1)

**1/x:** `∫(1/x) dx = ln|x| + C`

**Exponencial:** `∫eˣ dx = eˣ + C`

**Integral definida:** `∫ₐᵇ f(x)dx = F(b) - F(a)`
- F(x) = primitiva de f(x)

---

## ⚛️ FÍSICA

### Cinemática - MRU

**Velocidade média:** `v = Δs / Δt`
- v = velocidade, Δs = deslocamento, Δt = tempo

**Função horária:** `s = s₀ + vt`
- s = posição, s₀ = posição inicial, t = tempo

### Cinemática - MRUV

**Aceleração:** `a = Δv / Δt`
- a = aceleração, Δv = variação de velocidade

**Velocidade:** `v = v₀ + at`
- v₀ = velocidade inicial

**Posição:** `s = s₀ + v₀t + at²/2`

**Torricelli:** `v² = v₀² + 2aΔs`

**Queda livre:**
- `h = gt²/2` (velocidade inicial zero)
- `v = √(2gh)` (velocidade final)
- g ≈ 9,8 m/s² ou 10 m/s²

### Movimento Circular

**Velocidade angular:** `ω = Δθ / Δt = 2π/T`
- ω = velocidade angular (rad/s)
- θ = ângulo (rad), T = período

**Velocidade linear:** `v = ωr`
- r = raio

**Aceleração centrípeta:** `acp = v²/r = ω²r`

**Frequência:** `f = 1/T` (Hz)

### Dinâmica

**2ª Lei de Newton:** `F = ma`
- F = força (N), m = massa (kg), a = aceleração (m/s²)

**Peso:** `P = mg`
- g = gravidade

**Atrito:** `Fat = μN`
- μ = coeficiente de atrito, N = força normal

**Lei de Hooke:** `F = kx`
- k = constante elástica (N/m), x = deformação (m)

**Impulso:** `I = FΔt = Δ(mv)`

**Quantidade de movimento:** `Q = mv`

**Conservação:** `m₁v₁ + m₂v₂ = m₁v₁' + m₂v₂'`

### Trabalho e Energia

**Trabalho:** `W = F·d·cos θ`
- W = trabalho (J), F = força (N), d = deslocamento (m), θ = ângulo

**Potência:** `P = W/t` ou `P = F·v`
- P = potência (W = watt)

**Energia cinética:** `Ec = mv²/2`

**Energia potencial gravitacional:** `Epg = mgh`
- h = altura

**Energia potencial elástica:** `Epe = kx²/2`

**Teorema do trabalho:** `W = ΔEc`

**Conservação:** `Em = Ec + Ep = constante`

### Gravitação

**Lei da Gravitação:** `F = G(m₁m₂)/r²`
- G = 6,67×10⁻¹¹ N·m²/kg²

**Aceleração gravitacional:** `g = GM/R²`
- M = massa do planeta, R = raio

**Velocidade orbital:** `v = √(GM/r)`

**3ª Lei de Kepler:** `T²/R³ = constante`
- T = período, R = raio da órbita

### Hidrostática

**Pressão:** `P = F/A`
- P = pressão (Pa), A = área (m²)

**Pressão hidrostática:** `P = ρgh`
- ρ = densidade (kg/m³), h = profundidade

**Stevin:** `P₂ = P₁ + ρgh`

**Pascal:** `F₁/A₁ = F₂/A₂`

**Empuxo:** `E = ρ_fluido · V_deslocado · g`

### Hidrodinâmica

**Continuidade:** `A₁v₁ = A₂v₂`
- A = área da seção, v = velocidade

**Bernoulli:** `P + ρgh + ρv²/2 = constante`

### Termodinâmica

**Dilatação linear:** `ΔL = L₀·α·ΔT`
- α = coeficiente de dilatação linear, ΔT = variação temperatura

**Dilatação superficial:** `ΔA = A₀·β·ΔT` (β = 2α)

**Dilatação volumétrica:** `ΔV = V₀·γ·ΔT` (γ = 3α)

**Calor sensível:** `Q = mcΔT`
- Q = calor (J ou cal), m = massa, c = calor específico

**Calor latente:** `Q = mL`
- L = calor latente

**1ª Lei:** `ΔU = Q - W`
- ΔU = variação energia interna

**Gases ideais:** `PV = nRT`
- P = pressão, V = volume, n = mols, R = 8,31 J/(mol·K) ou 0,082 atm·L/(mol·K), T = temperatura (K)

**Energia interna (gás monoatômico):** `U = (3/2)nRT`

**Rendimento:** `η = W/Q_quente = 1 - Q_frio/Q_quente`

**Carnot:** `η_Carnot = 1 - T_fria/T_quente` (K)

### Ondas

**Equação fundamental:** `v = λf`
- v = velocidade (m/s), λ = comprimento de onda (m), f = frequência (Hz)

**Período:** `T = 1/f`

**Frequência fundamental (corda):** `f₁ = v/(2L)`

**Harmônicos:** `fₙ = nf₁`

**Efeito Doppler:** `f' = f·(v ± v_obs)/(v ∓ v_fonte)`
- + no numerador: observador aproxima
- - no denominador: fonte aproxima

**Intensidade sonora:** `I = P/A` (W/m²)

**Nível sonoro:** `β = 10·log(I/I₀)` dB
- I₀ = 10⁻¹² W/m²

**Batimento:** `f_bat = |f₁ - f₂|`

### Óptica

**Reflexão:** `θᵢ = θᵣ`

**Snell:** `n₁·sen θ₁ = n₂·sen θ₂`
- n = índice de refração

**Espelhos/Lentes:** `1/f = 1/p + 1/p'`
- f = foco, p = objeto, p' = imagem

**Aumento:** `A = -p'/p = i/o`

**Vergência:** `V = 1/f` (di = dioptria)
- f em metros

### Eletrostática

**Coulomb:** `F = k·q₁q₂/r²`
- k = 9×10⁹ N·m²/C²

**Campo elétrico:** `E = F/q` ou `E = k·Q/r²`

**Potencial:** `V = k·Q/r`

**Trabalho:** `W = q·ΔV`

**Energia potencial:** `Ep = k·q₁q₂/r`

**Capacitância:** `C = Q/V` (F = farad)

**Energia no capacitor:** `E = QV/2 = CV²/2`

**Capacitores:**
- Série: `1/Ceq = 1/C₁ + 1/C₂ + ...`
- Paralelo: `Ceq = C₁ + C₂ + ...`

### Eletrodinâmica

**Corrente:** `i = Q/Δt` (A = ampère)

**Lei de Ohm:** `V = R·i`
- V = tensão (V), R = resistência (Ω), i = corrente (A)

**2ª Lei de Ohm:** `R = ρ·L/A`
- ρ = resistividade

**Potência:** `P = V·i = Ri² = V²/R` (W)

**Energia:** `E = P·t`

**Resistores:**
- Série: `Req = R₁ + R₂ + ...`
- Paralelo: `1/Req = 1/R₁ + 1/R₂ + ...`

**Kirchhoff:**
- Nós: `Σi_entrada = Σi_saída`
- Malhas: `Σε = ΣR·i`

### Eletromagnetismo

**Força em carga:** `F = qvB·sen θ`
- B = campo magnético (T = tesla)

**Força em condutor:** `F = BiL·sen θ`

**Campo em fio:** `B = μ₀i/(2πr)`
- μ₀ = 4π×10⁻⁷ T·m/A

**Campo em espira:** `B = μ₀i/(2R)`

**Campo em solenoide:** `B = μ₀ni`
- n = espiras/comprimento

**Fluxo magnético:** `Φ = B·A·cos θ` (Wb = weber)

**Lei de Faraday:** `ε = -ΔΦ/Δt` ou `ε = -N·ΔΦ/Δt`

### Física Moderna

**Energia do fóton:** `E = hf = hc/λ`
- h = 6,63×10⁻³⁴ J·s (constante de Planck)
- c = 3×10⁸ m/s

**Efeito fotoelétrico:** `Ec_máx = hf - Φ`
- Φ = função trabalho

**Einstein:** `E = mc²`

**Energia relativística:** `E² = (pc)² + (mc²)²`

**Dilatação temporal:** `Δt' = Δt/√(1 - v²/c²)`

**Contração espacial:** `L' = L·√(1 - v²/c²)`

**De Broglie:** `λ = h/(mv)`

---

## 🧪 QUÍMICA

### Estequiometria

**Número de mols:** `n = m/M`
- n = mols, m = massa (g), M = massa molar (g/mol)

**Avogadro:** `n = N/Nₐ`
- N = número de partículas, Nₐ = 6,02×10²³ mol⁻¹

**Volume molar (CNTP):** `V = 22,4n` L

**Clapeyron:** `PV = nRT`

**Densidade de gases:** `d = m/V = PM/(RT)`

### Soluções

**Molaridade:** `M = n/V` (mol/L)

**Concentração comum:** `C = m/V` (g/L)

**Título:** `T = m_soluto/m_solução`

**ppm:** `ppm = (m_soluto/m_solução) × 10⁶`

**Fração molar:** `X = n_componente/n_total`

**Diluição:** `C₁V₁ = C₂V₂`

**Molalidade:** `W = n_soluto/m_solvente` (mol/kg)

### Termoquímica

**Entalpia:** `ΔH = H_produtos - H_reagentes`
- ΔH < 0: exotérmica
- ΔH > 0: endotérmica

**Lei de Hess:** `ΔH_total = ΔH₁ + ΔH₂ + ...`

**Energia de ligação:** `ΔH = Σ(quebradas) - Σ(formadas)`

**Entalpia de formação:** `ΔH°_reação = ΣΔH°f(produtos) - ΣΔH°f(reagentes)`

**Gibbs:** `ΔG = ΔH - TΔS`
- ΔG < 0: espontânea

### Cinética

**Velocidade:** `v = Δ[concentração]/Δt`

**Lei de velocidade:** `v = k[A]ᵃ[B]ᵇ`
- k = constante, a,b = ordens

**Arrhenius:** `k = A·e^(-Ea/RT)`
- Ea = energia de ativação

**Meia-vida (1ª ordem):** `t₁/₂ = 0,693/k`

### Equilíbrio

**Constante:** `Kc = [C]ᶜ[D]ᵈ / [A]ᵃ[B]ᵇ`
- Para: aA + bB ⇌ cC + dD

**Relação Kp e Kc:** `Kp = Kc(RT)^Δn`

**Quociente:** `Q` (mesma forma, qualquer momento)
- Q < K: → produtos
- Q > K: → reagentes
- Q = K: equilíbrio

**Grau de ionização:** `α = n_ionizado/n_inicial`

**Ostwald:** `α = √(Ka/M)`

### Equilíbrio Iônico

**Produto iônico da água:** `Kw = [H⁺][OH⁻] = 10⁻¹⁴` (25°C)

**pH:** `pH = -log[H⁺]`

**pOH:** `pOH = -log[OH⁻]`

**Relação:** `pH + pOH = 14`

**Ka:** `Ka = [H⁺][A⁻]/[HA]`

**Kb:** `Kb = [HB⁺][OH⁻]/[B]`

**Relação:** `Ka × Kb = Kw`

**Henderson-Hasselbalch:** `pH = pKa + log([A⁻]/[HA])`

**Kps:** `Kps = [cátion]ᵃ[ânion]ᵇ`

### Eletroquímica

**Potencial padrão:** `E°_célula = E°_cátodo - E°_ânodo`

**Nernst:** `E = E° - (0,059/n)·log Q` (25°C)

**Energia livre:** `ΔG° = -nFE°`
- F = 96500 C/mol

**Faraday:** `m = (M·i·t)/(n·F)`

### Radioatividade

**Desintegração:** `N = N₀·e^(-λt)`
- λ = constante de desintegração

**Meia-vida:** `t₁/₂ = 0,693/λ`

**Atividade:** `A = λN = A₀·e^(-λt)`

---

## 🧬 BIOLOGIA

### Genética

**Mendel 1ª Lei:** 3:1 (fenotípico), 1:2:1 (genotípico)

**Mendel 2ª Lei:** 9:3:3:1

**Hardy-Weinberg:**
- Alelos: `p + q = 1`
- Genótipos: `p² + 2pq + q² = 1`

**Recombinação:** `VR = (n_recombinantes/n_total) × 100%`

### Bioquímica

**Respiração:** `C₆H₁₂O₆ + 6O₂ → 6CO₂ + 6H₂O + 38 ATP`

**Fotossíntese:** `6CO₂ + 6H₂O + luz → C₆H₁₂O₆ + 6O₂`

**Fermentação alcoólica:** `C₆H₁₂O₆ → 2C₂H₅OH + 2CO₂ + 2 ATP`

**Fermentação láctica:** `C₆H₁₂O₆ → 2C₃H₆O₃ + 2 ATP`

**Código genético:** 3 nucleotídeos = 1 códon = 1 aminoácido

### Ecologia

**Taxa de natalidade:** `n = (nascimentos/população) × 1000`

**Taxa de mortalidade:** `m = (mortes/população) × 1000`

**Crescimento exponencial:** `dN/dt = rN`

**Crescimento logístico:** `dN/dt = rN(K-N)/K`
- K = capacidade de suporte

**Densidade:** `D = N/A`

**PPL:** `PPL = PPB - R`
- PPL = produtividade primária líquida
- PPB = bruta, R = respiração

**Eficiência energética:** `E = (energia_nível_n / energia_nível_n-1) × 100%`
- Geralmente 10%

### Fisiologia

**Débito cardíaco:** `DC = FC × VS`
- FC = frequência cardíaca (bpm)
- VS = volume sistólico (mL)

**PAM:** `PAM = PAD + (PAS - PAD)/3`
- PAM = pressão arterial média
- PAD = diastólica, PAS = sistólica

**IMC:** `IMC = massa / altura²` (kg/m²)

---

Este é o final da Parte 1. Continue para ver Ciência da Computação e demais áreas...
# Guia Completo de Fórmulas (Parte 2)

## 💻 CIÊNCIA DA COMPUTAÇÃO

### Complexidade Computacional

**Notações Big O:**
- `O(1)` = Constante: tempo independe do tamanho da entrada
- `O(log n)` = Logarítmica: busca binária
- `O(n)` = Linear: percorre todos elementos uma vez
- `O(n log n)` = Linearítmica: merge sort, quick sort médio
- `O(n²)` = Quadrática: bubble sort, dois loops aninhados
- `O(n³)` = Cúbica: três loops aninhados
- `O(2ⁿ)` = Exponencial: força bruta combinatória
- `O(n!)` = Fatorial: todas permutações
- n = tamanho da entrada

### Teoria da Informação

**Entropia de Shannon:**
- `H(X) = -Σ p(x)·log₂ p(x)`
- H(X) = entropia (bits)
- p(x) = probabilidade de x
- Σ = somatório sobre todos x
- Mede incerteza/informação

**Capacidade do Canal (Shannon-Hartley):**
- `C = B·log₂(1 + S/N)`
- C = capacidade (bits/segundo)
- B = largura de banda (Hz)
- S/N = relação sinal-ruído

**Informação Mútua:**
- `I(X;Y) = H(X) - H(X|Y)`
- Quanto Y informa sobre X

**Taxa de Compressão:**
- `RC = tamanho_comprimido / tamanho_original`
- RC < 1: houve compressão
- Exemplo: 0,5 = redução de 50%

### Estruturas de Dados

**Fator de Carga (Hash Table):**
- `α = n/m`
- α = fator de carga
- n = elementos armazenados
- m = tamanho da tabela
- Ideal: α < 0,7

**Altura de Árvore Binária Completa:**
- `h = log₂(n+1)` (arredondar para cima)
- h = altura, n = nós

**Nós em Árvore Binária Completa:**
- `n = 2^h - 1`

**Busca Binária:**
- Complexidade: `O(log₂ n)`
- Cada passo elimina metade

### Algoritmos de Ordenação

**Bubble Sort:**
- Melhor: O(n), Médio: O(n²), Pior: O(n²)
- Espaço: O(1)

**Selection Sort:**
- Todos casos: O(n²)
- Espaço: O(1)

**Insertion Sort:**
- Melhor: O(n), Médio: O(n²), Pior: O(n²)
- Espaço: O(1)

**Merge Sort:**
- Todos casos: O(n log n)
- Espaço: O(n)

**Quick Sort:**
- Melhor/Médio: O(n log n), Pior: O(n²)
- Espaço: O(log n)

**Heap Sort:**
- Todos casos: O(n log n)
- Espaço: O(1)

### Redes de Computadores

**Taxa de Transferência:**
- `T = Tamanho_dados / Tempo`
- T = taxa (bps, Mbps, Gbps)
- 1 byte = 8 bits

**Latência Total:**
- `L = L_propagação + L_transmissão + L_processamento + L_fila`
- L = latência total (ms)

**Tempo de Propagação:**
- `Tp = Distância / Velocidade_propagação`
- Velocidade ≈ 2×10⁸ m/s (cabo) ou 3×10⁸ m/s (vácuo)

**Tempo de Transmissão:**
- `Tt = Tamanho_dados / Taxa_transmissão`

**Utilização do Canal:**
- `U = Tt / (Tt + 2·Tp)`
- U = eficiência (0 a 1)
- Para protocolos stop-and-wait

**Throughput:**
- Quantidade real de dados transferidos/tempo

### Machine Learning

**Erro Quadrático Médio (MSE):**
- `MSE = (1/n)Σ(yᵢ - ŷᵢ)²`
- n = amostras
- yᵢ = valor real
- ŷᵢ = valor previsto

**Raiz do MSE:**
- `RMSE = √MSE`
- Mesma unidade dos dados

**Erro Absoluto Médio (MAE):**
- `MAE = (1/n)Σ|yᵢ - ŷᵢ|`
- Menos sensível a outliers

**Métricas de Classificação:**

**Acurácia:**
- `Acurácia = (VP + VN) / (VP + VN + FP + FN)`
- VP = verdadeiros positivos
- VN = verdadeiros negativos
- FP = falsos positivos
- FN = falsos negativos

**Precisão:**
- `Precisão = VP / (VP + FP)`
- Dos previstos como positivo, quantos eram

**Recall (Sensibilidade):**
- `Recall = VP / (VP + FN)`
- Dos realmente positivos, quantos acertou

**F1-Score:**
- `F1 = 2 × (Precisão × Recall) / (Precisão + Recall)`
- Média harmônica

**Regressão Linear:**
- `y = β₀ + β₁x + ε`
- β₀ = intercepto
- β₁ = coeficiente angular
- ε = erro

**Gradiente Descendente:**
- `θ = θ - α·∇J(θ)`
- θ = parâmetros
- α = taxa de aprendizado (learning rate)
- ∇J(θ) = gradiente da função custo

**Função Sigmóide:**
- `σ(x) = 1 / (1 + e⁻ˣ)`
- Saída entre 0 e 1
- Usada em redes neurais

**Função ReLU:**
- `f(x) = max(0, x)`
- Popular em redes neurais profundas

**Entropia Cruzada:**
- `H(p,q) = -Σ p(x)·log q(x)`
- p(x) = distribuição real
- q(x) = distribuição prevista
- Função de perda para classificação

**Perplexidade:**
- `PP = 2^H`
- H = entropia
- Métrica para modelos de linguagem

### Computação Gráfica

**Translação 2D:**
- `x' = x + tx`
- `y' = y + ty`
- tx, ty = deslocamentos

**Rotação 2D:**
- `x' = x·cos θ - y·sen θ`
- `y' = x·sen θ + y·cos θ`
- θ = ângulo de rotação

**Escala 2D:**
- `x' = sx·x`
- `y' = sy·y`
- sx, sy = fatores de escala

**Taxa de Quadros:**
- `FPS = Número_frames / Tempo_segundos`
- 60 FPS = padrão para jogos

**Resolução:**
- `Total_pixels = Largura × Altura`
- Full HD = 1920×1080 = 2.073.600 pixels

**Profundidade de Cor:**
- `Cores = 2^bits`
- 24 bits = 2²⁴ = 16.777.216 cores

**Razão de Aspecto:**
- `Aspecto = Largura / Altura`
- 16:9 = 1,78
- 4:3 = 1,33

### Processamento de Imagens

**Limiarização:**
- `g(x,y) = 1 se f(x,y) > T, senão 0`
- T = limiar (threshold)
- Converte em preto e branco

**Filtro de Média (3×3):**
- `g(x,y) = (1/9)Σf(x+i, y+j)`
- Suaviza/reduz ruído

**Gradiente (Sobel):**
- `G = √(Gx² + Gy²)`
- Detecção de bordas

**SNR (Sinal-Ruído):**
- `SNR = 10·log₁₀(P_sinal/P_ruído)` dB
- Maior = melhor qualidade

**PSNR:**
- `PSNR = 10·log₁₀(MAX²/MSE)` dB
- MAX = 255 para 8 bits
- Qualidade de compressão

---

## 🏗️ ENGENHARIA

### Resistência dos Materiais

**Tensão Normal:**
- `σ = F/A`
- σ = tensão (Pa, MPa)
- F = força (N)
- A = área (m²)

**Tensão de Cisalhamento:**
- `τ = V/A`
- τ = cisalhamento
- V = força cortante

**Deformação:**
- `ε = ΔL/L₀`
- ε = deformação (adimensional)
- ΔL = variação comprimento
- L₀ = comprimento original

**Lei de Hooke:**
- `σ = E·ε`
- E = módulo de Young (Pa)
- Válida na região elástica

**Coeficiente de Poisson:**
- `ν = -ε_transversal/ε_longitudinal`
- 0 ≤ ν ≤ 0,5

**Módulo de Cisalhamento:**
- `G = τ/γ`
- G = módulo de cisalhamento
- γ = deformação angular (rad)

**Relação entre Módulos:**
- `E = 2G(1 + ν)`

**Momento de Inércia:**
- Retângulo: `I = bh³/12`
- Círculo: `I = πr⁴/4`
- b = base, h = altura, r = raio

**Tensão de Flexão:**
- `σ = M·y/I`
- M = momento fletor (N·m)
- y = distância do eixo neutro
- I = momento de inércia

### Mecânica dos Fluidos

**Número de Reynolds:**
- `Re = ρvD/μ = vD/ν`
- Re < 2000: laminar
- 2000 < Re < 4000: transição
- Re > 4000: turbulento
- ρ = densidade, v = velocidade
- D = diâmetro, μ = viscosidade dinâmica
- ν = viscosidade cinemática = μ/ρ

**Número de Froude:**
- `Fr = v/√(gL)`
- Forças inerciais vs gravitacionais

**Número de Mach:**
- `Ma = v/c`
- c = velocidade do som
- Ma < 1: subsônico
- Ma = 1: sônico
- Ma > 1: supersônico

**Perda de Carga:**
- `hf = f·(L/D)·(v²/2g)`
- hf = perda (m)
- f = fator de atrito
- L = comprimento, D = diâmetro

**Fator de Atrito (Laminar):**
- `f = 64/Re`
- Válido Re < 2000

**Vazão:**
- `Q = A·v` (m³/s)

**Potência de Bomba:**
- `P = ρgQH/η`
- H = altura manométrica
- η = eficiência

### Termodinâmica de Engenharia

**Carnot:**
- `η_Carnot = 1 - T_fria/T_quente` (K)
- Eficiência máxima teórica

**COP Refrigerador:**
- `COP_ref = Q_frio/W`
- Quanto maior, melhor

**COP Bomba de Calor:**
- `COP_bc = Q_quente/W`

**Relação:**
- `COP_bc = COP_ref + 1`

**Entalpia:**
- `H = U + PV`
- U = energia interna
- P = pressão, V = volume

**Entropia:**
- `dS ≥ dQ/T`
- = para reversível
- > para irreversível

**Relação de Mayer:**
- `cp - cv = R`
- cp = calor específico pressão constante
- cv = calor específico volume constante
- R = constante do gás

**Razão de Calores:**
- `γ = cp/cv`
- γ ≈ 1,4 para ar
- γ = 1,67 para monoatômicos

### Eletrotécnica

**Potência Aparente:**
- `S = V·I` (VA)
- V = tensão eficaz (RMS)
- I = corrente eficaz

**Potência Ativa:**
- `P = V·I·cos φ` (W)
- cos φ = fator de potência

**Potência Reativa:**
- `Q = V·I·sen φ` (VAR)

**Triângulo:**
- `S² = P² + Q²`

**Fator de Potência:**
- `FP = cos φ = P/S`
- 0 ≤ FP ≤ 1
- FP = 1 ideal

**Impedância:**
- `Z = √(R² + X²)` (Ω)
- R = resistência
- X = reatância

**Reatância Indutiva:**
- `XL = ωL = 2πfL` (Ω)
- L = indutância (H)
- f = frequência (Hz)

**Reatância Capacitiva:**
- `XC = 1/(ωC) = 1/(2πfC)` (Ω)
- C = capacitância (F)

**Ressonância:**
- `f₀ = 1/(2π√(LC))`
- XL = XC em ressonância

**Transformador Ideal:**
- `V₁/V₂ = N₁/N₂ = I₂/I₁`
- N = número de espiras

### Circuitos CA

**Valor Eficaz (RMS):**
- `V_ef = V_máx/√2`
- `I_ef = I_máx/√2`
- √2 ≈ 1,414

**Valor Médio:**
- `V_méd = 2V_máx/π`
- Retificação onda completa

**Impedância Complexa:**
- `Z = R + jX`
- j = unidade imaginária

**Lei de Ohm (Fasores):**
- `V̅ = Z̅·I̅`
- Notação fasorial

---

## 💰 ECONOMIA E FINANÇAS

### Microeconomia

**Elasticidade-Preço:**
- `Ep = (ΔQ/Q) / (ΔP/P)`
- |Ep| > 1: elástica
- |Ep| < 1: inelástica
- |Ep| = 1: unitária

**Receita Total:**
- `RT = P × Q`
- P = preço, Q = quantidade

**Receita Marginal:**
- `RMg = ΔRT/ΔQ`
- Receita adicional por unidade

**Custo Marginal:**
- `CMg = ΔCT/ΔQ`
- Custo adicional por unidade

**Lucro:**
- `L = RT - CT`
- CT = custo total

**Maximização:**
- `RMg = CMg`
- Lucro máximo

### Macroeconomia

**PIB:**
- `PIB = C + I + G + (X - M)`
- C = consumo
- I = investimento
- G = governo
- X = exportações
- M = importações

**Taxa de Crescimento:**
- `g = [(PIB_final - PIB_inicial)/PIB_inicial] × 100%`

**PIB per Capita:**
- `PIB_pc = PIB/População`

**Inflação:**
- `Inflação = [(IPC_final - IPC_inicial)/IPC_inicial] × 100%`
- IPC = índice de preços

**Fisher (Taxa Real):**
- Aproximada: `r ≈ i - π`
- Exata: `1 + r = (1 + i)/(1 + π)`
- r = taxa real
- i = taxa nominal
- π = inflação

### Finanças

**VPL (Valor Presente Líquido):**
- `VPL = Σ[FC_t/(1+i)^t] - Investimento`
- FC_t = fluxo de caixa período t
- i = taxa de desconto
- VPL > 0: viável

**TIR (Taxa Interna de Retorno):**
- TIR torna VPL = 0
- TIR > custo capital: viável

**Índice de Lucratividade:**
- `IL = VPL/Investimento`
- IL > 0: viável

**CAPM:**
- `E(R) = Rf + β[E(Rm) - Rf]`
- E(R) = retorno esperado
- Rf = taxa livre risco
- β = beta (sensibilidade ao mercado)
- E(Rm) = retorno mercado

**Índice de Sharpe:**
- `S = (Rp - Rf)/σp`
- Rp = retorno portfólio
- σp = desvio padrão (risco)
- Maior = melhor

**Beta:**
- `β = Cov(Ri, Rm) / Var(Rm)`
- β = 1: igual ao mercado
- β > 1: mais volátil
- β < 1: menos volátil

### Investimentos

**Valor Futuro:**
- `VF = VP(1 + i)^n`

**Valor Presente:**
- `VP = VF/(1 + i)^n`

**Perpetuidade:**
- `VP = PMT/i`
- Série infinita pagamentos

**Anuidade:**
- `VP = PMT × [1 - (1+i)^(-n)] / i`
- Série finita pagamentos

**Taxa Equivalente:**
- `(1 + i_a) = (1 + i_p)^n`

**Retorno Total:**
- `R = (P_final - P_inicial + Dividendos) / P_inicial`

---

## 🌟 ASTRONOMIA

**Velocidade Orbital:**
- `v = √(GM/r)`
- G = 6,67×10⁻¹¹ N·m²/kg²

**Velocidade de Escape:**
- `v_e = √(2GM/R)`

**Energia Orbital:**
- `E = -GMm/(2a)`
- a = semieixo maior

**Magnitude:**
- `m - M = 5·log(d/10)`
- m = aparente
- M = absoluta
- d = distância (parsecs)

**Lei de Stefan-Boltzmann:**
- `L = 4πR²σT⁴`
- L = luminosidade (W)
- R = raio estrela
- σ = 5,67×10⁻⁸ W/(m²·K⁴)
- T = temperatura (K)

**Lei de Wien:**
- `λ_máx·T = 2,898×10⁻³` m·K
- Cor vs temperatura

**Lei de Hubble:**
- `v = H₀·d`
- v = velocidade recessão
- H₀ ≈ 70 km/s/Mpc
- Expansão do universo

**Redshift:**
- `z = Δλ/λ = v/c` (aproximado)

**Idade Universo:**
- `t ≈ 1/H₀ ≈ 13,8` bilhões anos

---

## 🏥 FARMACOLOGIA

**Biodisponibilidade:**
- `F = (AUC_oral × Dose_IV) / (AUC_IV × Dose_oral)`
- AUC = área sob curva
- F = 1: 100% biodisponível

**Volume Distribuição:**
- `Vd = Dose / C₀`
- Vd em litros

**Clearance:**
- `Cl = k·Vd = Dose/AUC` (L/h)

**Meia-Vida:**
- `t₁/₂ = 0,693/k` (h)

**Concentração:**
- `C = C₀·e^(-kt)`

**Dose Manutenção:**
- `DM = Cl·Css·τ/F`
- Css = concentração estado estacionário
- τ = intervalo doses

**Taxa Infusão:**
- `R = Cl·Css`

**Índice Terapêutico:**
- `IT = DL₅₀/DE₅₀`
- Alto = mais seguro

**Superfície Corporal:**
- `SC = √[(altura_cm × peso_kg)/3600]` m²

**Filtração Glomerular:**
- Homem: `ClCr = [(140-idade) × peso] / (72 × Creatinina)`
- Mulher: × 0,85

**Osmolaridade:**
- `Osm = 2Na + Glicose/18 + Ureia/6` mOsm/L

---

## 🏃 FISIOLOGIA DO EXERCÍCIO

**VO₂ máx (Cooper):**
- `VO₂máx = (Distância_m - 504,9)/44,73` mL/kg/min
- Distância em 12 minutos

**FC Máxima:**
- `FC_máx ≈ 220 - idade` bpm

**FC Reserva:**
- `FC_res = FC_máx - FC_repouso`

**Zona Treino:**
- `FC_treino = FC_repouso + (FC_res × intensidade%)`

**MET:**
- 1 MET = 3,5 mL O₂/kg/min
- Metabolismo basal

**Gasto Calórico:**
- `Cal = METs × peso_kg × tempo_h`

**IMC:**
- `IMC = massa_kg / altura_m²`
- < 18,5: baixo peso
- 18,5-24,9: normal
- 25-29,9: sobrepeso
- ≥ 30: obesidade

**RCQ:**
- `RCQ = cintura / quadril`
- Homem > 0,90: risco
- Mulher > 0,85: risco

---

## 🌍 GEOGRAFIA

**Escala:**
- `E = d_mapa/d_real`
- Ex: 1:50.000
- 1 cm mapa = 500 m real

**Distância Real:**
- `D = d_mapa/E`

**Declividade:**
- `i = (Δh/Δd) × 100%`
- Ou: `α = arctan(Δh/Δd)` graus

**Conversão Coordenadas:**
- `Decimal = Graus + Min/60 + Seg/3600`

**Distância Latitudes:**
- `d ≈ 111 km × Δlatitude`
- 1° ≈ 111 km

---

## 🎵 MÚSICA

**Velocidade Som:**
- `v ≈ 331 + 0,6T` m/s
- T = temperatura °C
- 20°C: v ≈ 343 m/s

**Intervalos:**
- Oitava: 2:1
- Quinta: 3:2
- Quarta: 4:3
- Terça maior: 5:4

**Temperamento Igual:**
- `f_n = f₀ × 2^(n/12)`
- n = semitons
- Lá = 440 Hz

**Cents:**
- `cents = 1200 × log₂(f₂/f₁)`
- 1 semitom = 100 cents

---

## 🎨 DESIGN

**Razão Áurea:**
- `φ = (1 + √5)/2 ≈ 1,618`

**Luminosidade RGB:**
- `Y = 0,299R + 0,587G + 0,114B`

**Contraste:**
- `Contraste = (L₁ + 0,05)/(L₂ + 0,05)`
- WCAG: ≥ 4,5:1 para texto

**Papel A-Series:**
- Razão: √2:1
- A4 = 210×297 mm

---

## 🔬 QUÍMICA AVANÇADA

**Schrödinger:**
- `Ĥψ = Eψ`
- Ĥ = Hamiltoniano
- ψ = função onda
- E = energia

**Energia Hidrogênio:**
- `E_n = -13,6/n²` eV
- n = 1, 2, 3...

**Heisenberg:**
- `Δx·Δp ≥ ℏ/2`
- ℏ = 1,055×10⁻³⁴ J·s
- Incerteza

**Rydberg:**
- `1/λ = R(1/n₁² - 1/n₂²)`
- R = 1,097×10⁷ m⁻¹

**Beer-Lambert:**
- `A = ε·c·l`
- A = absorbância
- ε = extinção molar
- c = concentração
- l = caminho óptico

**Transmitância:**
- `T = I/I₀`
- `A = -log T`

**Van der Waals:**
- `(P + a/V²)(V - b) = RT`
- Gases reais

---

## 📊 CONVERSÕES

**Temperatura:**
- K = °C + 273,15
- °F = (9/5)°C + 32
- °C = (5/9)(°F - 32)

**Energia:**
- 1 J = 0,239 cal
- 1 cal = 4,184 J
- 1 eV = 1,602×10⁻¹⁹ J
- 1 kWh = 3,6×10⁶ J

**Pressão:**
- 1 atm = 101.325 Pa = 760 mmHg
- 1 bar = 10⁵ Pa

**Velocidade:**
- 1 m/s = 3,6 km/h
- 1 km/h = 0,278 m/s

---

## 🎲 ESTATÍSTICA E PROBABILIDADE

### Distribuições de Probabilidade

**Distribuição Normal:**
- `f(x) = (1/σ√(2π))·e^(-(x-μ)²/2σ²)`
- μ = média, σ = desvio padrão
- 68% no intervalo [μ-σ, μ+σ]
- 95% no intervalo [μ-2σ, μ+2σ]
- 99,7% no intervalo [μ-3σ, μ+3σ]

**Distribuição Normal Padrão:**
- `Z = (X - μ)/σ`
- Tabela Z para probabilidades

**Distribuição Binomial:**
- `P(X=k) = C(n,k)·p^k·(1-p)^(n-k)`
- μ = np, σ² = np(1-p)

**Distribuição Poisson:**
- `P(X=k) = (e^(-λ)·λ^k)/k!`
- μ = λ, σ² = λ

**Distribuição Exponencial:**
- `f(x) = λe^(-λx)` (x ≥ 0)
- μ = 1/λ, σ² = 1/λ²

### Testes de Hipóteses

**Teste Z (média, σ conhecida):**
- `Z = (x̄ - μ₀)/(σ/√n)`
- Z > Z_α/₂: rejeita H₀

**Teste t (média, σ desconhecida):**
- `t = (x̄ - μ₀)/(s/√n)`
- gl = n-1 graus de liberdade

**Teste Qui-quadrado:**
- `χ² = Σ[(Obs-Esp)²/Esp]`
- Para independência de variáveis

**Intervalo de Confiança (média):**
- IC = x̄ ± t_(α/2,n-1)·(s/√n)

### Correlação e Regressão

**Correlação de Pearson:**
- `r = Σ[(x-x̄)(y-ȳ)] / √[Σ(x-x̄)²·Σ(y-ȳ)²]`
- -1 ≤ r ≤ 1

**Regressão Linear Múltipla:**
- `y = β₀ + β₁x₁ + β₂x₂ + ... + βₖxₖ + ε`

**R² (Coeficiente de Determinação):**
- `R² = 1 - SSE/SST`
- SSE = soma dos quadrados do erro
- SST = soma total dos quadrados

### Análise de Variância (ANOVA)

**ANOVA (uma via):**
- `F = MSB/MSW`
- MSB = média dos quadrados entre grupos
- MSW = média dos quadrados dentro dos grupos

---

## 🧪 QUÍMICA ORGÂNICA

### Hidrocarbonetos

**Alcanos (CₙH₂ₙ₊₂):**
- Fórmula geral
- n = 1: CH₄ (metano)
- n = 2: C₂H₆ (etano)
- n = 3: C₃H₈ (propano)

**Alcenos (CₙH₂ₙ):**
- Dupla ligação C=C
- n = 2: C₂H₄ (eteno)

**Alcinos (CₙH₂ₙ₋₂):**
- Tripla ligação C≡C
- n = 2: C₂H₂ (etino)

### Funções Orgânicas

**Álcoois:**
- R-OH
- nomenclatura: sufixo -ol
- exemplos: metanol, etanol

**Éteres:**
- R-O-R'
- exemplos: éter dietílico

**Aldeídos:**
- R-CHO
- sufixo -al
- exemplo: formaldeído

**Cetonas:**
- R-CO-R'
- sufixo -ona
- exemplo: acetona

### Reações Orgânicas

**Substituição Nucleofílica (SN2):**
- Taxa: depende de ambos os reagentes
- Mecanismo: ataque direto
- Inverte configuração

**Substituição Nucleofílica (SN1):**
- Taxa: depende apenas do substrato
- Mecanismo: carbocátion intermediário
- Formação de mistura racêmica

**Adição Eletrofílica:**
- Alcenos + H₂O → álcoois
- Alcenos + Br₂ → dibrometos

**Eliminação (E1/E2):**
- E1: carbocátion intermediário
- E2: concerted, um passo

---

## 🔬 CIÊNCIA DOS MATERIAIS

### Propriedades Mecânicas

**Módulo de Young:**
- `E = σ/ε`
- σ = tensão, ε = deformação
- Aço: ~200 GPa
- Alumínio: ~70 GPa

**Lei de Hooke (Tridimensional):**
- `σ₁ = E₁·ε₁ + ν(E₂·ε₂ + E₃·ε₃)`

**Módulo de Cisalhamento:**
- `G = τ/γ`
- τ = tensão de cisalhamento
- γ = deformação angular

**Tensão de Ruptura:**
- `σ_r = F_r/A₀`
- F_r = força de ruptura
- A₀ = área original

### Propriedades Térmicas

**Condutividade Térmica:**
- `k = -q·dT/dx`
- q = fluxo de calor
- Aço: ~50 W/m·K
- Cobre: ~400 W/m·K

**Expansão Térmica Linear:**
- `ΔL = L₀·α·ΔT`
- α = coeficiente de expansão

**Capacidade Térmica:**
- `C = dQ/dT`
- Aço: ~500 J/kg·K
- Água: ~4186 J/kg·K

### Diagramas de Fase

**Regra das Fases de Gibbs:**
- `F = C - P + 2`
- F = graus de liberdade
- C = componentes
- P = fases

**Regra do Braço de Alavanca:**
- `%A = (l₂)/(l₁ + l₂) × 100%`
- Para composição de fases

### Corrosão

**Equação de Nernst:**
- `E = E° - (0,059/n)·log Q`
- Para potenciais de eletrodo

**Taxa de Corrosão:**
- `CR = (K·W)/(D·A·T)`
- W = perda de massa
- D = densidade
- A = área, T = tempo

---

## 📡 PROCESSAMENTO DE SINAIS

### Transformada de Fourier

**Transformada de Fourier Contínua:**
- `X(ω) = ∫₋∞^∞ x(t)·e^(-jωt) dt`

**Transformada de Fourier Discreta (DFT):**
- `X(k) = Σ[n=0 to N-1] x(n)·e^(-j2πkn/N)`

**Transformada Inversa:**
- `x(t) = (1/2π)∫₋∞^∞ X(ω)·e^(jωt) dω`

### Convolução

**Convolução Contínua:**
- `y(t) = x(t) * h(t) = ∫₋∞^∞ x(τ)·h(t-τ) dτ`

**Convolução Discreta:**
- `y[n] = x[n] * h[n] = Σ[k=-∞^∞] x[k]·h[n-k]`

### Filtros

**Filtro Passa-Baixa (1ª ordem):**
- `H(jω) = 1/(1 + jω/ω_c)`

**Filtro Passa-Alta (1ª ordem):**
- `H(jω) = jω/(ω_c + jω)`

**Filtro Passa-Faixa:**
- `H(jω) = (jω/Q)/[(jω/ω₀)² + (jω/ω₀) + 1]`

### Modulação

**Modulação AM:**
- `s(t) = [1 + m·cos(ω_mt)]·cos(ω_ct)`
- m = índice de modulação

**Modulação FM:**
- `θ(t) = ω_ct + k_f∫m(τ)dτ`
- k_f = sensibilidade

**Modulação PM:**
- `θ(t) = ω_ct + k_p·m(t)`
- k_p = sensibilidade de fase

---

## 🎛️ CONTROLE AUTOMÁTICO

### Função de Transferência

**Função de Transferência:**
- `G(s) = Y(s)/U(s)`
- Y = saída, U = entrada

**Pólos e Zeros:**
- Pólos: raizes do denominador
- Zeros: raizes do numerador

### Estabilidade

**Critério de Routh-Hurwitz:**
- Sistema estável se todos coeficientes > 0
- E linhas de Routh positivas

**Margem de Ganho:**
- MG = 1/|G(jω_180)| (dB)
- ω_180 = frequência onde fase = -180°

**Margem de Fase:**
- MP = 180° + φ(ω_gc)
- ω_gc = frequência onde |G(jω)| = 1

### Controladores PID

**PID:**
- `C(s) = K_p + K_i/s + K_d·s`
- K_p = ganho proporcional
- K_i = ganho integral
- K_d = ganho derivativo

**Método Ziegler-Nichols:**
- Regras empíricas para ajuste

---

## 🧬 GENÉTICA MOLECULAR

### DNA e RNA

**Estrutura DNA:**
- Dupla hélice antiparalela
- A pareia com T (2 H)
- C pareia com G (3 H)

**Transcrição:**
- DNA → RNA mensageiro
- U substitui T

**Tradução:**
- RNA mensageiro → proteína
- 3 nucleotídeos = 1 códon
- 1 códon = 1 aminoácido

### Lei de Hardy-Weinberg

**Equilíbrio:**
- `p² + 2pq + q² = 1`
- `p + q = 1`
- p, q = frequências alélicas

**Frequência Genotípica:**
- p² = homozigoto dominante
- 2pq = heterozigoto
- q² = homozigoto recessivo

### Cálculo de Frequências

**Frequência Alélica:**
- `p = (2×AA + Aa)/(2×N)`
- N = total de indivíduos

**Frequência Genotípica:**
- Frequência esperada vs observada

---

## 🌊 GEOLOGIA

### Escala de Tempo Geológico

**Períodos Geológicos:**
- Cambriano: ~541-485 Ma
- Ordoviciano: ~485-444 Ma
- Siluriano: ~444-419 Ma
- Devoniano: ~419-359 Ma
- Carbonífero: ~359-299 Ma
- Permiano: ~299-252 Ma

### Isótopos Radiométricos

**Meia-vida:**
- Carbono-14: 5730 anos
- Urânio-238: 4,47 bilhões anos
- Potássio-40: 1,25 bilhões anos

**Datação:**
- `t = (1/λ)·ln(N₀/N)`
- λ = constante de decaimento

### Escala Richter

**Magnitude:**
- `M = log A - log A₀`
- A = amplitude sismógrafo
- A₀ = amplitude padrão

**Energia Liberada:**
- `log E = 1,5M + 4,8`
- E em ergs

### Intemperismo

**Equação de Meyer:**
- `E = K·(σ-σ₀)·T^n`
- K = constante
- σ = tensão aplicada

---

## 🌤️ METEOROLOGIA

### Atmosfera

**Equação de Estado:**
- `P = ρRT`
- P = pressão, ρ = densidade, T = temperatura

**Gradiente Adiabático Seco:**
- `Γ_d = -g/cp ≈ 9,8°C/km`
- g = gravidade, cp = calor específico

**Gradiente Adiabático Úmido:**
- `Γ_m ≈ 6,5°C/km`
- Menor que o seco devido à liberação de calor

### Umidade

**Pressão de Vapor:**
- `e = ρ_v·R_v·T`
- R_v = constante específica do vapor

**Umidade Relativa:**
- `RH = e/e_s × 100%`
- e = pressão de vapor atual
- e_s = pressão de vapor saturada

**Ponto de Orvalho:**
- Temperatura onde UR = 100%

### Balanço Radiativo

**Radiação Solar:**
- `Q* = (1-α)·S₀·sin(h)`
- α = albedo, S₀ = constante solar
- h = ângulo de elevação

**Fluxo de Calor Latente:**
- `LE = ρ·L·E`
- L = calor latente, E = evaporação

### Circulação Atmosférica

**Equação do Gradiente:**
- `(1/ρ)·∇P = f·V_g`
- V_g = vento geostrófico

**Força de Coriolis:**
- `F_c = 2Ω·V·sin(φ)`
- Ω = velocidade angular Terra
- φ = latitude

---

## 🔬 MICROBIOLOGIA

### Crescimento Microbiano

**Crescimento Exponencial:**
- `N = N₀·e^(kt)`
- N₀ = população inicial
- k = taxa específica de crescimento

**Tempo de Geração:**
- `t_g = ln(2)/k`
- Tempo para duplicar a população

**Modelo de Monod:**
- `μ = μ_máx·S/(K_s + S)`
- μ = velocidade específica
- S = concentração substrato

### Contagem Microbiana

**CFU (Colônia Formando Unidades):**
- `CFU/mL = (colônias × diluição)/volume`

**Método do Número Mais Provável (NMP):**
- Para microorganismos não cultiváveis

### Inativação Térmica

**Equação de Arrhenius:**
- `k = A·e^(-Ea/RT)`
- A = fator pré-exponencial

**D-Value:**
- `D = ln(10)/k`
- Tempo para reduzir 90% da população

**Z-Value:**
- Variação de temperatura para reduzir D em 90%

---

## 🧪 ENZIMOLOGIA

### Cinética Enzimática

**Equação de Michaelis-Menten:**
- `v = (V_máx·[S])/(K_m + [S])`
- v = velocidade da reação
- [S] = concentração substrato
- K_m = constante de Michaelis

**Constante de Michaelis:**
- `K_m = (k₋₁ + k₂)/k₁`
- Afinidade enzyme-substrato

**V_max:**
- `V_max = k₂·[E]t`
- [E]t = concentração total enzyme

### Inibição Enzimática

**Inibição Competitiva:**
- K_m aumenta, V_max constante
- `v = V_max·[S]/(K_m(1 + I/K_i) + [S])`

**Inibição Não-Competitiva:**
- V_max diminui, K_m constante
- `v = (V_max/[S])·[S]/(K_m + [S]/(1 + I/K_i))`

**Inibição Irreversível:**
- Enzyme inativada permanentemente
- Taxa depende da concentração do inibidor

---

## 🧠 NEUROCIÊNCIA

### Potencial de Ação

**Equação de Goldman-Hodgkin-Katz:**
- `V_m = (RT/F)·ln((P_K[K+]o + P_Na[Na+]o + P_Cl[Cl-]i)/(P_K[K+]i + P_Na[Na+]i + P_Cl[Cl-]o))`

**Velocidade do Potencial:**
- `v = √(d/4ρi)`
- d = diâmetro da fibra
- ρi = resistividade interna

### Potencial Sináptico

**Potencial Pós-Sináptico (PSP):**
- Depende do tipo de canal iônico
- PSP excitatório ou inibitório

**Soma Temporal:**
- Múltiplos PSPs se somam

**Soma Espacial:**
- Múltiplos inputs simultâneos

### Condução Nervosa

**Constante de Tempo:**
- `τ_m = R_m·C_m`
- R_m = resistência da membrana
- C_m = capacitância da membrana

**Constante de Comprimento:**
- `λ = √(d·r_i/4r_m)`
- d = diâmetro, r_i = resistividade interna
- r_m = resistência da membrana

---

## 🧬 BIOQUÍMICA AVANÇADA

### Fosforilação Oxidativa

**Equação Total:**
- `C₆H₁₂O₆ + 6O₂ + 38ADP + 38Pi → 6CO₂ + 6H₂O + 38ATP`

**Relação P/O:**
- NADH: P/O = 2,5
- FADH₂: P/O = 1,5

**Força Protônica:**
- `Δp = Δψ - (2,3RT/F)·ΔpH`

### Ciclo de Krebs

**Ciclo Completo:**
- `Acetil-CoA + 3NAD⁺ + FAD + GDP + Pi + 2H₂O → 2CO₂ + 3NADH + FADH₂ + GTP + CoA`

**Rendimento Energético:**
- Por molécula de glicose: 2 ATP (ciclo) + 30 ATP (fosforilação)

### Glicólise

**Reação Limitante:**
- Fosfofrutoquinase (PFK)
- Ponto de regulação

**Rendimento:**
- 2 ATP net por glicose
- 2 NADH por glicose

### Fotossíntese

**Equação de Hill:**
- `2H₂O + 2A → O₂ + 2AH₂`
- A = aceptor de elétrons

**Eficiência Fotossintética:**
- Máxima teórica: 11%
- Típica em plantas: 3-6%

---

## 🔬 QUÍMICA ANALÍTICA

### Análise Gravimétrica

**Fator Gravimétrico:**
- `F = (massa do substância procurada)/(massa do precipitado)`

**Análise Volumétrica:**

**Molaridade:**
- `M = n/V` (mol/L)

**Normalidade:**
- `N = eq/V` (eq/L)

**Equivalente:**
- `eq = n/fator`
- Fator = número de H⁺ ou OH⁻

### Espectrofotometria

**Lei de Beer-Lambert:**
- `A = ε·c·l`
- A = absorbância
- ε = coeficiente de extinção molar
- c = concentração, l = caminho óptico

**Transmitância:**
- `T = I/I₀`
- `A = -log T`

### Cromatografia

**Fator de Retenção:**
- `k' = (t_R - t₀)/t₀`
- t_R = tempo de retenção
- t₀ = tempo morto

**Resolução:**
- `R = 2(t_R₂ - t_R₁)/(w₁ + w₂)`
- w = largura do pico

**Eficiência:**
- `N = 16(t_R/w)²`
- N = número de pratos teóricos

---

## 📊 ANÁLISE NUMÉRICA

### Interpolação

**Polinômio de Lagrange:**
- `P(x) = Σ[i=0^n] y_i·L_i(x)`
- `L_i(x) = Π[j≠i] (x-x_j)/(x_i-x_j)`

**Interpolação de Newton:**
- `P(x) = a₀ + a₁(x-x₀) + a₂(x-x₀)(x-x₁) + ...`

### Integração Numérica

**Regra do Trapézio:**
- `∫ab f(x)dx ≈ (b-a)/2·[f(a) + f(b)]`

**Regra de Simpson:**
- `∫ab f(x)dx ≈ (b-a)/6·[f(a) + 4f((a+b)/2) + f(b)]`

**Quadratura Gaussiana:**
- `∫₋₁¹ f(x)dx ≈ Σ[i=1^n] w_i·f(x_i)`
- Pontos e pesos gaussianos

### Derivação Numérica

**Derivada Primeira:**
- `f'(x) ≈ [f(x+h) - f(x-h)]/(2h)`

**Derivada Segunda:**
- `f''(x) ≈ [f(x+h) - 2f(x) + f(x-h)]/h²`

### Equações Diferenciais

**Euler:**
- `y_{n+1} = y_n + h·f(t_n, y_n)`

**Runge-Kutta 4ª ordem:**
- `k₁ = h·f(t_n, y_n)`
- `k₂ = h·f(t_n + h/2, y_n + k₁/2)`
- `k₃ = h·f(t_n + h/2, y_n + k₂/2)`
- `k₄ = h·f(t_n + h, y_n + k₃)`
- `y_{n+1} = y_n + (k₁ + 2k₂ + 2k₃ + k₄)/6`

---

## 🎯 PESQUISA OPERACIONAL

### Programação Linear

**Problema Padrão:**
- Minimizar: `z = c₁x₁ + c₂x₂ + ... + cₙxₙ`
- Sujeito a: Ax ≤ b, x ≥ 0

**Método Simplex:**
- Solução básica inicial
- Variáveis de folga
- Iteração até otimalidade

### Otimização

**Gradiente Descendente:**
- `x_{k+1} = x_k - α·∇f(x_k)`
- α = tamanho do passo

**Método de Newton:**
- `x_{k+1} = x_k - [∇²f(x_k)]⁻¹·∇f(x_k)`

### Teoria dos Jogos

**Estratégia Mista:**
- Jogador A: p₁, p₂, ..., pₘ
- Jogador B: q₁, q₂, ..., qₙ

**Valor do Jogo:**
- `v = max_p min_q p^T A q`

---

## 🧪 FÍSICO-QUÍMICA

### Cinética Química Avançada

**Colisão Molecular:**
- `k = Z·ρ·e^(-Ea/RT)`
- Z = frequência de colisões
- ρ = fator estérico

**Equação de Arrhenius:**
- `k = A·e^(-Ea/RT)`
- A = fator pré-exponencial

### Superfícies

**Isoterma de Langmuir:**
- `θ = KP/(1 + KP)`
- θ = fração da superfície ocupada

**Adsorção:**
- `V = V_m·bP/(1 + bP)`

### Soluções

**Atividade:**
- `a = γ·m`
- γ = coeficiente de atividade
- m = molalidade

**Força Iônica:**
- `I = 1/2 Σ(c_i·z_i²)`
- c_i = concentração iônica
- z_i = carga iônica

---

## 🌊 HIDROLOGIA

### Balanço Hídrico

**Equação do Balanço:**
- `P = ET + R + ΔS`
- P = precipitação
- ET = evapotranspiração
- R = escoamento superficial
- ΔS = variação de armazenamento

### Escoamento

**Método Racional:**
- `Q = C·i·A`
- C = coeficiente de runoff
- i = intensidade da chuva
- A = área da bacia

**Equação de Manning:**
- `V = (1/n)·R^(2/3)·S^(1/2)`
- V = velocidade
- n = rugosidade de Manning
- R = raio hidráulico
- S = declividade

### Infiltração

**Equação de Horton:**
- `f(t) = f_c + (f₀ - f_c)·e^(-kt)`
- f(t) = capacidade de infiltração
- f₀ = capacidade inicial
- f_c = capacidade final

---

## 🏗️ GEOTECNIA

### Mecânica dos Solos

**Peso Específico:**
- `γ = W/V`
- W = peso, V = volume

**Índice de Vazios:**
- `e = V_v/V_s`
- V_v = volume de vazios
- V_s = volume de sólidos

**Porosidade:**
- `n = V_v/V_total`

**Grau de Saturação:**
- `Sr = V_w/V_v`
- V_w = volume de água

### Compressão

**Compressibilidade:**
- `a_v = -dε_v/dp`
- ε_v = deformação volumétrica
- p = pressão

**Coeficiente de Compressão:**
- `C_c = Δe/log(σ₂/σ₁)`

### Resistência

**Lei de Coulomb:**
- `τ = c + σ·tan(φ)`
- τ = resistência ao cisalhamento
- c = coesão
- σ = tensão normal
- φ = ângulo de atrito interno

---

## 🔧 ENGENHARIA DE PRODUÇÃO

### Pesquisa Operacional

**Teoria das Filas:**

**Modelo M/M/1:**
- `ρ = λ/μ`
- λ = taxa de chegada
- μ = taxa de serviço
- ρ < 1 para estabilidade

**Tempo Médio de Espera:**
- `W_q = λ/(μ(μ-λ))`

**Número Médio de Clientes:**
- `L = λ/(μ-λ)`

### PCP (Planejamento e Controle da Produção)

**Capacidade:**
- `Capacidade = Taxa × Tempo`

**Lead Time:**
- `LT = TP + TR + TQ`
- TP = tempo de preparação
- TR = tempo de processamento
- TQ = tempo de fila

### Controle de Qualidade

**Limites de Controle:**
- LSC = X̄ + 3σ
- LIC = X̄ - 3σ
- X̄ = média das amostras

**Capacidade do Processo:**
- `C_p = (USL - LSL)/(6σ)`
- C_p > 1,33 é adequado

---

## 📊 ECONOMETRIA

### Modelos Econométricos

**Regressão Linear Múltipla:**
- `y = β₀ + β₁x₁ + β₂x₂ + ... + βₖxₖ + u`

**Estimador de Mínimos Quadrados:**
- `β̂ = (X'X)⁻¹X'y`

**Teste F:**
- `F = (RSS_R - RSS_U)/q / (RSS_U/(n-k-1))`
- RSS = soma dos quadrados residuais

### Séries Temporais

**Modelo AR(p):**
- `y_t = c + φ₁y_{t-1} + φ₂y_{t-2} + ... + φₚy_{t-p} + ε_t`

**Modelo MA(q):**
- `y_t = c + ε_t + θ₁ε_{t-1} + ... + θₑε_{t-q}`

**Modelo ARMA(p,q):**
- Combinação AR e MA

### Testes Econométricos

**Teste de Dickey-Fuller Aumentado:**
- Testa estacionariedade
- H₀: raiz unitária presente

**Teste de Engle-Granger:**
- Testa cointegração
- Relaciona séries não estacionárias

---

## 🎲 TEORIA DOS JOGOS

### Jogos de Soma Zero

**Matriz de Payoff:**
- A = matriz de payoff do jogador A
- B = -A (jogador B)

**Estratégia Mista:**
- `x` para jogador A
- `y` para jogador B

**Equilíbrio de Nash:**
- Nenhum jogador melhora unilateralmente

### Jogos Cooperativos

**Coalition Games:**
- Valor de Shapley
- Núcleo (core) do jogo

**Negociação:**
- Modelo de Nash
- Solução de Pareto

---

## 🧠 PSICOLOGIA EXPERIMENTAL

### Estatísticas Psicológicas

**Tamanho do Efeito:**
- `d = (M₁ - M₂)/SD_pooled`
- Cohen's d

**Poder Estatístico:**
- `Poder = 1 - β`
- β = erro tipo II

### Medidas Psicométricas

**Confiabilidade:**
- `α = (k/(k-1))·(1 - Σσ²_i/σ²_total)`
- Alfa de Cronbach

**Validade:**
- Correlação com critério externo
- Análise fatorial

---

## 🌊 OCEANOGRAFIA

### Propriedades da Água do Mar

**Densidade:**
- `ρ = ρ₀ + α(T-T₀) + β(S-S₀) + γ(P-P₀)`
- T = temperatura, S = salinidade, P = pressão

**Salinidade Total:**
- `S = (1,80655)·Cl`
- Cl = cloridade

### Correntes Marítimas

**Equação de Ekman:**
- `v(z) = V₀·e^(kz)·cos(π/4 + kz)`
- V₀ = velocidade superficial
- k = número de onda

**Transporte de Ekman:**
- `T = (τ/f)`
- τ = tensão do vento
- f = parâmetro de Coriolis

### Marés

**Constituinte Principal:**
- M₂ = 12,42 horas
- Período da maré semi-diurna

**Equação Harmônica:**
- `h(t) = h₀ + Σ H_i·cos(ω_i·t - φ_i)`
- h(t) = altura da maré
- H_i = amplitude da constituinte i

---

## 🌱 BOTÂNICA

### Fotossíntese Avançada

**Equação de Fick:**
- `J = -D·(dC/dx)`
- J = fluxo difusivo
- D = coeficiente de difusão

**Eficiência Quântica:**
- `Φ = CO₂ fixado/fótons absorvidos`
- Máximo teórico: 0,125

### Transpiração

**Equação de Penman-Monteith:**
- `ET = [0,408Δ(Rn-G) + γ(900/(T+273))u₂(es-ea)]/[Δ + γ(1+0,34u₂)]`
- ET = evapotranspiração
- Rn = radiação líquida

### Crescimento Vegetal

**Taxa de Crescimento Relativo:**
- `RGR = (1/W)·(dW/dt)`
- W = biomassa seca

**Área Foliar Específica:**
- `SLA = LA/LAW`
- LA = área foliar
- LAW = massa seca da folha

---

## 🦴 ANATOMIA E FISIOLOGIA

### Sistema Cardiovascular

**Equação de Fick:**
- `VO₂ = Q·(CaO₂ - CvO₂)`
- VO₂ = consumo de oxigênio
- Q = débito cardíaco
- CaO₂ = conteúdo arterial de O₂
- CvO₂ = conteúdo venoso de O₂

**Índice Cardíaco:**
- `CI = CO/BSA`
- CO = débito cardíaco
- BSA = superfície corporal

### Sistema Respiratório

**Capacidade Vital:**
- `VC = IRV + Vt + ERV`
- IRV = volume de reserva inspiratório
- Vt = volume corrente
- ERV = volume de reserva expiratório

**Compliance:**
- `C = ΔV/ΔP`
- ΔV = mudança de volume
- ΔP = mudança de pressão

### Sistema Renal

**Taxa de Filtração Glomerular:**
- `GFR = (U_in × V)/P_in`
- U_in = concentração inulina urina
- V = fluxo urinário
- P_in = concentração inulina plasma

**Clearance:**
- `Cl = (U × V)/P`
- U = concentração urinária
- P = concentração plasmática
- V = fluxo urinário

---

## 🧪 PATOLOGIA

### Oncologia

**Lei de Gompertz (crescimento tumoral):**
- `dN/dt = rN·ln(K/N)`
- N = número de células
- r = taxa de crescimento
- K = capacidade de suporte

**Modelo de Armitage-Doll:**
- Múltiplas mutações necessárias
- Risco aumenta com idade

### Epidemiologia

**Taxa de Incidência:**
- `IR = casos novos/população em risco`

**Risco Relativo:**
- `RR = [a/(a+b)]/[c/(c+d)]`
- a = expostos com doença
- b = expostos sem doença
- c = não expostos com doença
- d = não expostos sem doença

**Odds Ratio:**
- `OR = (a·d)/(b·c)`

---

## 🔬 NANOTECNOLOGIA

### Mecânica Quântica em Nanoescala

**Princípio da Incerteza:**
- `Δx·Δp ≥ ℏ/2`
- ℏ = h/2π

**Energia do Oscilador Harmônico:**
- `E = ℏω(n + 1/2)`
- n = número quântico

### Efeitos Superficiais

**Tensão Superficial:**
- `γ = F/L`
- F = força, L = comprimento

**Energia Superficial:**
- `E_s = γ·A`
- A = área superficial

### Transporte em Nanoescala

**Lei de Fick (1D):**
- `J = -D·∂C/∂x`
- D = coeficiente de difusão

**Mobilidade:**
- `μ = q·τ/m`
- q = carga, τ = tempo de relaxamento
- m = massa efetiva

---

## 🎯 ROBÓTICA

### Cinemática

**Matriz de Transformação Homogênea:**
- `T = [R t; 0 1]`
- R = matriz de rotação
- t = vetor de translação

**Equações de Denavit-Hartenberg:**
- θ = ângulo de junta
- d = distância ao longo do eixo z
- a = distância ao longo do eixo x
- α = ângulo de rotação

### Dinâmica

**Equação de Euler-Lagrange:**
- `d/dt(∂L/∂q̇) - ∂L/∂q = τ`
- L = Lagrangiano
- q = coordenadas generalizadas
- τ = torques generalizados

**Jacobiano:**
- `J = ∂f/∂q`
- Relaciona velocidades

### Controle

**Matriz de Inércia:**
- `M(q)·q̈ + C(q,q̇)·q̇ + G(q) = τ`
- M = inércia
- C = forças centrífugas/Coriolis
- G = gravidade

---

## 📡 COMUNICAÇÕES DIGITAIS

### Modulação Digital

**Taxa de Bits:**
- `R_b = R_s·log₂(M)`
- R_s = taxa de símbolos
- M = níveis de modulação

**Energia por Bit:**
- `E_b = E_s/log₂(M)`
- E_s = energia por símbolo

### BER (Bit Error Rate)

**Canal AWGN:**
- `BER = Q(√(2E_b/N₀))`
- Q = função Q
- N₀ = densidade espectral de ruído

**Modulação BPSK:**
- `BER = Q(√(2E_b/N₀))`

**Modulação QPSK:**
- `BER = Q(√(2E_b/N₀))`

### Capacidade de Canal

**Shannon-Hartley:**
- `C = B·log₂(1 + S/N)`
- C = capacidade (bits/s)
- B = largura de banda
- S/N = relação sinal-ruído

---

## 🎮 TEORIA DOS JOGOS COMPUTACIONAIS

### Algoritmos Minimax

**Valor Minimax:**
- `V(node) = max(min(V(child₁), V(child₂), ...))`
- Para jogos de soma zero

**Poda Alfa-Beta:**
- α = melhor valor para MAX
- β = melhor valor para MIN
- poda quando α ≥ β

### Aprendizado por Reforço

**Q-Learning:**
- `Q(s,a) ← Q(s,a) + α[r + γ max Q(s',a') - Q(s,a)]`
- α = taxa de aprendizado
- γ = fator de desconto
- r = recompensa

**Equação de Bellman:**
- `V(s) = max_a Σ P(s'|s,a)[r(s,a,s') + γV(s')]`

---

## 🧬 BIOINFORMÁTICA

### Sequenciamento

**Algoritmo de Smith-Waterman:**
- Score local entre sequências
- Matriz de pontuação

**BLAST:**
- Basic Local Alignment Search Tool
- Busca similaridade em bancos de dados

### Alinhamento

**Score de Alinhamento:**
- `S = Σ match_score + Σ mismatch_penalty + Σ gap_penalty`

**Matriz PAM:**
- Point Accepted Mutation
- Probabilidades de substituição

### Filogenia

**Distância Genética:**
- `d = -ln(1 - p)`
- p = proporção de diferenças

**Método Neighbor-Joining:**
- Algoritmo de reconstrução filogenética

---

## 🌍 CIÊNCIAS AMBIENTAIS

### Balanço de Carbono

**Sequestro de Carbono:**
- `C_sequestrado = C_Entrada - C_Saída`

**Emissões de CO₂:**
- `Emissões = Atividade × Fator de Emissão`

### Qualidade da Água

**Índice de Qualidade da Água (IQA):**
- `IQA = Π[w_i·q_i^(1/w_i)]`
- w_i = peso do parâmetro
- q_i = qualidade do parâmetro

**Demanda Bioquímica de Oxigênio (DBO):**
- `DBO_t = DBO_∞(1 - e^(-k·t))`

### Poluição Atmosférica

**Concentração de Poluentes:**
- `C = (E × P)/(u × H)`
- E = emissão
- P = fator de persistência
- u = velocidade do vento
- H = altura da mistura

---

## 🎯 LOGÍSTICA E TRANSPORTE

### Otimização de Rotas

**Problema do Caixeiro Viajante (TSP):**
- Minimizar distância total
- Visitou todas as cidades uma vez

**Algoritmo de Dijkstra:**
- Menor caminho entre vértices
- Grafo com pesos não negativos

### Gerenciamento de Estoque

**Modelo EOQ:**
- `Q* = √(2DS/H)`
- Q = quantidade econômica de pedido
- D = demanda anual
- S = custo de setup
- H = custo de manutenção

**Ponto de Pedido:**
- `ROP = d × L + SS`
- d = demanda diária
- L = lead time
- SS = estoque de segurança

### Cadeia de Suprimentos

**Ciclo de Cash-to-Cash:**
- `C2C = I + P - R`
- I = dias em estoque
- P = dias em contas a receber
- R = dias em contas a pagar

---

## 🔬 CIÊNCIA DE MATERIAIS AVANÇADA

### Nanomateriais

**Densidade de Estados (1D):**
- `D(E) = (1/π)√(m*/2ℏ²E)`

**Efeito de Tamanho Quântico:**
- Bandgap aumenta com redução do tamanho
- Efeito quântico de confinamento

### Materiais Inteligentes

**Memória de Forma:**
- Transformação martensítica
- Temperatura de Austenita (A_s)

**Materiais Piezoelétricos:**
- `P = d·σ`
- P = polarização
- d = coeficiente piezoelétrico
- σ = tensão aplicada

### Compósitos

**Regra das Misturas:**
- `E_c = V_f·E_f + V_m·E_m`
- E_c = módulo do compósito
- V_f = fração volumétrica da fibra
- E_f = módulo da fibra
- V_m = fração volumétrica da matriz
- E_m = módulo da matriz

**Teoria de Halpin-Tsai:**
- `E = E_m[(1 + ξ·η·V_f)/(1 - η·V_f)]`
- `η = (E_f/E_m - 1)/(E_f/E_m + ξ)`

---

## 🧠 NEUROCIÊNCIA COMPUTACIONAL

### Neurônio Artificial

**Função de Ativação Sigmoidal:**
- `σ(x) = 1/(1 + e^(-x))`

**ReLU (Rectified Linear Unit):**
- `f(x) = max(0, x)`

### Redes Neurais

**Backpropagation:**
- `Δw = -η·∂E/∂w`
- η = taxa de aprendizado
- E = função de erro

**Gradiente Descendente:**
- `w_{t+1} = w_t - η·∇E`

### Redes Convolucionais

**Convolução 2D:**
- `Y[i,j] = Σ[m,n] X[m,n]·K[i-m,j-n]`

**Pooling:**
- Max pooling: `Y = max(X_window)`
- Average pooling: `Y = mean(X_window)`

---

## 📊 BIG DATA E ANALYTICS

### Lei de Zipf

**Distribuição de Frequência:**
- `f(r) = C/r^s`
- r = ranking
- C = constante normalizadora
- s = expoente (tipicamente ~1)

### Lei de Pareto

**Regra 80/20:**
- `P(X > x) = (x/x_min)^(-α)`
- α = expoente de Pareto
- Tipicamente α ≈ 1,16

### Algoritmos de Clustering

**K-Means:**
- Minimizar: `J = Σ[i=1 to k] Σ[x∈C_i] ||x - μ_i||²`

**DBSCAN:**
- Densidade de pontos
- eps = raio de vizinhança
- minPts = pontos mínimos

---

## 🎯 CRIPTOGRAFIA

### Criptografia Simétrica

**AES (Advanced Encryption Standard):**
- Tamanhos de chave: 128, 192, 256 bits
- Blocos de 128 bits

**RC4:**
- Stream cipher
- Chave variável

### Criptografia Assimétrica

**RSA:**
- `n = p × q`
- `φ(n) = (p-1)(q-1)`
- `e × d ≡ 1 (mod φ(n))`

**Elliptic Curve Cryptography:**
- `y² ≡ x³ + ax + b (mod p)`
- Maior segurança com chaves menores

### Funções Hash

**SHA-256:**
- Saída: 256 bits
- Padrão atual para blockchain

**MD5:**
- Saída: 128 bits
- Considerado quebrado

---

## 🌐 BLOCKCHAIN

### Mineração de Bitcoin

**Proof of Work:**
- Hash SHA-256 < target
- Target = dificuldade ajustada

**Nonce:**
- Número que varia para encontrar hash válido

**Dificuldade:**
- `D = D_min × (T_target/T_actual)`
- T_target = 10 minutos
- T_actual = tempo médio dos últimos blocos

### Smart Contracts

**Gas Limit:**
- Limite de computação
- Prevenção de loops infinitos

**Gas Price:**
- Custo por unidade de gas
- Determina prioridade da transação

---

## 📱 INTERNET DAS COISAS (IoT)

### Protocolos de Comunicação

**MQTT:**
- Protocolo leve para IoT
- Publish/Subscribe

**CoAP:**
- Constrained Application Protocol
- Para dispositivos limitados

### Edge Computing

**Latência:**
- `L = T_processamento + T_transmissão + T_propagação`

**Throughput:**
- `R = Dados/Tempo`

**Bandwidth:**
- `B = log₂(1 + S/N)`
- Capacidade máxima teórica

---

## 🤖 INTELIGÊNCIA ARTIFICIAL

### Algoritmos Genéticos

**Seleção:**
- Roleta: `P_i = f_i/Σf_i`
- Torneio: seleção dos melhores

**Crossover:**
- One-point: corte único
- Multi-point: múltiplos cortes

**Mutação:**
- Probabilidade p_m << 1
- Alteração aleatória de genes

### Lógica Fuzzy

**Função de Pertinência:**
- `μ_A(x) = [0, 1]`
- Grau de pertencimento

**Inferência Fuzzy:**
- Mínimo: `μ_out = min(μ_in₁, μ_in₂)`
- Produto: `μ_out = μ_in₁ × μ_in₂`

### Algoritmos de Busca

**A* (A Estrela):**
- `f(n) = g(n) + h(n)`
- g(n) = custo do início até n
- h(n) = heurística (n até objetivo)

**Algoritmo Genético:**
- População → Seleção → Crossover → Mutação → Nova população

---

## 🌍 SUSTENTABILIDADE

### Pegada Ecológica

**Pegada de Carbono:**
- `CO₂_eq = Σ(Atividade_i × Fator_i)`
- i = diferentes atividades

**Ciclo de Vida (LCA):**
- `Impact = Σ(Processos × Fatores)`

### Energias Renováveis

**Eficiência Fotovoltaica:**
- `η = (P_out/P_in) × 100%`
- Típico: 15-22%

**Eficiência Eólica:**
- `η = (P_capturada/P_disponível)`
- Limite de Betz: 59,3%

### Economia Circular

**Taxa de Reciclagem:**
- `R = (Massa_reciclada/Massa_total) × 100%`

**Eficiência de Recursos:**
- `E = Output_valioso/Input_total`

---

## 🎯 MÉTODOS NUMÉRICOS AVANÇADOS

### Elementos Finitos

**Função de Forma (elemento linear):**
- `N₁ = (1-ξ)/2`
- `N₂ = (1+ξ)/2`
- ξ ∈ [-1,1]

**Matriz de Rigidez:**
- `K = ∫ B^T D B dΩ`
- B = matriz de deformação
- D = matriz constitutiva

### Diferenças Finitas

**Equação do Calor (1D):**
- `T_i^{n+1} = T_i^n + α·(T_{i+1}^n - 2T_i^n + T_{i-1}^n)·Δt/Δx²`

**Equação da Onda (1D):**
- `u_i^{n+1} = 2u_i^n - u_i^{n-1} + c²·(u_{i+1}^n - 2u_i^n + u_{i-1}^n)·Δt²/Δx²`

### Monte Carlo

**Estimação de π:**
- `π ≈ 4 × (pontos_dentro/pontos_total)`

**Integração:**
- `∫ab f(x)dx ≈ (b-a) × f(x_rand)`

---

## 📊 ANÁLISE DE SINAIS AVANÇADA

### Wavelet

**Transformada Wavelet Contínua:**
- `W(a,b) = (1/√a) ∫ x(t)ψ*((t-b)/a) dt`

**Espectrograma:**
- `S(t,f) = |X(t,f)|²`
- X = transformada de Fourier de curto prazo

### Análise Espectral

**Período:**
- `T = 1/f`
- f = frequência

**Frequência Angular:**
- `ω = 2πf`

**Densidade Espectral:**
- `S(f) = lim(T→∞) E[|X(f)|²]/T`

### Processamento de Imagens

**Filtro de Sobel:**
- Gx = [-1 0 1; -2 0 2; -1 0 1]
- Gy = [-1 -2 -1; 0 0 0; 1 2 1]

**Filtro de Laplace:**
- `L = [0 -1 0; -1 4 -1; 0 -1 0]`

**Thresholding:**
- `g(x,y) = 255 se f(x,y) > T, senão 0`

---

## 🧪 QUÍMICA COMPUTACIONAL

### Métodos Ab Initio

**Hartree-Fock:**
- `F = H + 2J - K`
- H = operador de um elétrons
- J = operador de Coulomb
- K = operador de troca

**Teoria do Funcional da Densidade (DFT):**
- `E[ρ] = T[ρ] + V_ne[ρ] + V_ee[ρ] + E_xc[ρ]`

### Mecânica Molecular

**Força de van der Waals:**
- `F = -dU/dr`
- `U = -C/r^6`

**Campo de Força Lennard-Jones:**
- `U(r) = 4ε[(σ/r)^12 - (σ/r)^6]`

### Dinâmica Molecular

**Equação de Newton:**
- `F = ma = -∇U`

**Algoritmo de Verlet:**
- `r(t+Δt) = 2r(t) - r(t-Δt) + a(t)Δt²`

---

## 📚 FIM - VERSÃO EXPANDIDA

**Total: Mais de 800 fórmulas completas com explicações detalhadas!**

### 📋 Disciplinas Incluídas (Total: 25+ áreas):

1. ✅ **Matemática** - Completa com análise avançada
2. ✅ **Física** - Completa com física moderna
3. ✅ **Química** - Completa com química orgânica e analítica
4. ✅ **Biologia** - Expandida com genética molecular e bioquímica
5. ✅ **Ciência da Computação** - Expandida com IA e algoritmos
6. ✅ **Engenharia** - Expandida com controle e processamento
7. ✅ **Economia e Finanças** - Completa com econometria
8. ✅ **Astronomia** - Expandida
9. ✅ **Farmacologia** - Expandida
10. ✅ **Geografia** - Expandida
11. ✅ **Música e Acústica** - Mantida
12. ✅ **Design** - Mantida
13. ✅ **Estatística e Probabilidade** - Nova seção completa
14. ✅ **Química Orgânica** - Nova seção completa
15. ✅ **Ciência dos Materiais** - Nova seção completa
16. ✅ **Processamento de Sinais** - Nova seção completa
17. ✅ **Controle Automático** - Nova seção completa
18. ✅ **Genética Molecular** - Nova seção completa
19. ✅ **Geologia** - Nova seção completa
20. ✅ **Meteorologia** - Nova seção completa
21. ✅ **Microbiologia** - Nova seção completa
22. ✅ **Enzimologia** - Nova seção completa
23. ✅ **Neurociência** - Nova seção completa
24. ✅ **Bioquímica Avançada** - Nova seção completa
25. ✅ **Química Analítica** - Nova seção completa
26. ✅ **Análise Numérica** - Nova seção completa
27. ✅ **Pesquisa Operacional** - Nova seção completa
28. ✅ **Físico-Química** - Nova seção completa
29. ✅ **Hidrologia** - Nova seção completa
30. ✅ **Geotecnia** - Nova seção completa
31. ✅ **Engenharia de Produção** - Nova seção completa
32. ✅ **Econometria** - Nova seção completa
33. ✅ **Teoria dos Jogos** - Nova seção completa
34. ✅ **Psicologia Experimental** - Nova seção completa
35. ✅ **Oceanografia** - Nova seção completa
36. ✅ **Botânica** - Nova seção completa
37. ✅ **Anatomia e Fisiologia** - Nova seção completa
38. ✅ **Patologia** - Nova seção completa
39. ✅ **Nanotecnologia** - Nova seção completa
40. ✅ **Robótica** - Nova seção completa
41. ✅ **Comunicações Digitais** - Nova seção completa
42. ✅ **Teoria dos Jogos Computacionais** - Nova seção completa
43. ✅ **Bioinformática** - Nova seção completa
44. ✅ **Ciências Ambientais** - Nova seção completa
45. ✅ **Logística e Transporte** - Nova seção completa
46. ✅ **Ciência de Materiais Avançada** - Nova seção completa
47. ✅ **Neurociência Computacional** - Nova seção completa
48. ✅ **Big Data e Analytics** - Nova seção completa
49. ✅ **Criptografia** - Nova seção completa
50. ✅ **Blockchain** - Nova seção completa
51. ✅ **Internet das Coisas (IoT)** - Nova seção completa
52. ✅ **Inteligência Artificial** - Nova seção completa
53. ✅ **Sustentabilidade** - Nova seção completa
54. ✅ **Métodos Numéricos Avançados** - Nova seção completa
55. ✅ **Análise de Sinais Avançada** - Nova seção completa
56. ✅ **Química Computacional** - Nova seção completa

### 🎯 **Características da Versão Expandida:**
- ✅ **Mais de 800 fórmulas** com explicações detalhadas
- ✅ **56+ disciplinas** abrangendo todas as áreas científicas
- ✅ **Fórmulas avançadas** de cada área
- ✅ **Estrutura organizada** e didática
- ✅ **Referências completas** para uso acadêmico e profissional

**Use este guia expandido como referência completa para todas as suas necessidades científicas e técnicas!**