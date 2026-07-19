# PROJETO GRÁFICO PREMIUM

> Navegacao: [Home da documentacao](../README.md) • [README do repositorio](../../README.md) • [PROJECT_INDEX](../../PROJECT_INDEX.md)

<a id="topo"></a>
## Documento Mestre de Design Editorial

### Coleção: Engenharia de Sistemas Inteligentes
### Volume I — Plataformas UNIHIKER: Da DFRobot à Edge AI

---

**Diretor de Arte:** Z.ai Design Board
**Data:** 18 de julho de 2026
**Status:** Aprovado para produção gráfica
**Classificação:** Briefing técnico definitivo

---

## ETAPA 1 — Conceito Visual da Obra

### 1.1 Personalidade Visual

A personalidade visual da obra é definida por quatro atributos:

| Atributo | Descrição | Manifestação Gráfica |
|----------|-----------|---------------------|
| **Precisão** | Engenharia sem ambiguidade; cada elemento tem função | Grid rígido, linhas retas, sem curvas decorativas |
| **Hierarquia** | Informação organizada por importância; leitor nunca se perde | Escala tipográfica clara, contraste cromático controlado |
| **Elegância** | Sofisticação sem ornamento; menos é mais | Espaço negativo generoso, paleta restrita, tipografia serifada clássica |
| **Tecnologia** | Modernidade sem datar; futurismo atemporal | Acentos em azul ciano (#2381b0), diagramas em estilo flat-design |

### 1.2 Estilo

O estilo editorial combina elementos de três referências:

1. **Springer Nature** (livros acadêmicos): rigor tipográfico, serifas clássicas, tabelas densas, legendas técnicas
2. **O'Reilly Media** (livros técnicos): caixas destacadas, ícones funcionais, diagramação limpa, capas minimalistas
3. **IDEO Design Thinking** (design de informação): diagramas em camadas, mapas conceituais, fluxogramas elegantes

### 1.3 Linguagem Gráfica

A linguagem gráfica da obra baseia-se em cinco princípios:

1. **Less is more:** cada elemento visual deve ter função. Ornamento sem propósito é proibido.
2. **Color as semantics:** cor comunica significado, não decoração. Azul = destaque técnico; vermelho = limitação/risco; verde = sucesso/sustentabilidade; âmbar = atenção.
3. **White space is content:** o espaço vazio é tão importante quanto o texto. Margens generosas evitam saturação visual.
4. **Consistency over creativity:** 500 páginas com a mesma identidade visual são mais profissionais que 50 páginas com estilos variados.
5. **Print-first, digital-aware:** o projeto é otimizado para impressão A4, mas funciona em tela (PDF interativo com hyperlinks).

### 1.4 Posicionamento Editorial

| Dimensão | Posicionamento |
|----------|---------------|
| Categoria | Livro técnico profissional (não didático, não acadêmico puro) |
| Nível | Pós-graduação profissional / consultor sênior |
| Concorrência direta | Springer Lecture Notes, IEEE Press, O'Reilly |
| Diferencial visual | 45 tipos de caixas editoriais; 100+ diagramas técnicos; paleta cascade proprietária |
| Percepção desejada | "Este livro foi projetado por engenheiros para engenheiros — cada detalhe tem propósito." |

### 1.5 Percepção Desejada no Leitor

Ao abrir o livro pela primeira vez, o leitor deve perceber:

- **Confiança:** a organização visual transmite competência técnica
- **Profundidade:** a densidade de informação (tabelas, diagramas, caixas) sugere conteúdo substantivo
- **Acessibilidade:** a hierarquia clara permite navegar sem se perder
- **Modernidade:** a paleta cromática e os diagramas flat-design são contemporâneos sem ser efêmeros
- **Permanência:** a tipografia clássica e o acabamento premium sugerem obra de referência duradoura

---

## ETAPA 2 — Tipografia

### 2.1 Sistema Tipográfico Completo

A obra utiliza dois sistemas tipográficos: um para corpo de texto (serif) e um para títulos e elementos funcionais (sans-serif). Esta combinação dual é padrão em publicações técnicas premium (Springer, IEEE Press).

#### 2.1.1 Famílias Tipográficas

| Função | Família | Justificativa |
|--------|---------|---------------|
| Corpo de texto | **Source Serif Pro** | Serifa moderna de alta legibilidade; projetada pela Adobe para telas e impressão; distinguishable de Times New Roman; suporta acentos portugueses |
| Títulos e elementos funcionais | **Inter** | Sans-serif de geometria neutra; excelente em tamanhos pequenos (legendas, cabeçalhos); peso variável (300 a 900); contemporânea sem datar |
| Código e mono | **DejaVu Sans Mono** | Monoespaçada com suporte completo a símbolos técnicos; disponível em todos os sistemas; fallback de Source Code Pro |
| Fallback corpo | **FreeSerif** | Disponível em todos os sistemas Linux; métricas similares a Source Serif Pro |
| Fallback títulos | **FreeSans** | Disponível em todos os sistemas Linux; métricas similares a Inter |

#### 2.1.2 Escala Tipográfica

A escala tipográfica segue proporção 1.2 (terça maior) com ajustes para legibilidade em A4:

| Nível | Função | Família | Peso | Tamanho | Entrelinha | Cor | Alinhamento |
|-------|--------|---------|------|---------|------------|-----|-------------|
| **Parte** | Divisória de parte | Inter | 300 (Light) | 48pt | 56pt | #4a5f6a | Centralizado |
| **Parte (número)** | "PARTE II" | Inter | 900 (Black) | 14pt | 18pt | #2381b0 | Centralizado, tracking 4pt |
| **Capítulo (capa)** | Título do capítulo na página de abertura | Source Serif Pro | 700 (Bold) | 42pt | 50pt | #232527 | Esquerda |
| **Capítulo (num.)** | "CAPÍTULO 3" | Inter | 700 (Bold) | 10pt | 12pt | #72787b | Esquerda, tracking 2pt |
| **H1** | Título de seção (12.1) | Inter | 700 (Bold) | 22pt | 28pt | #4a5f6a | Esquerda |
| **H2** | Título de subseção (12.1.1) | Inter | 700 (Bold) | 15pt | 20pt | #2381b0 | Esquerda |
| **H3** | Título de sub-subseção | Inter | 700 (Bold) | 12pt | 16pt | #4a5f6a | Esquerda |
| **Body** | Texto corrido | Source Serif Pro | 400 (Regular) | 10.5pt | 16pt | #232527 | Justificado |
| **Body (lead)** | Parágrafo de abertura | Source Serif Pro Italic | 400 Italic | 11pt | 17pt | #72787b | Justificado |
| **Caption** | Legenda de figura/tabela | Source Serif Pro Italic | 400 Italic | 9pt | 12pt | #72787b | Centralizado |
| **Table header** | Cabeçalho de tabela | Inter | 700 (Bold) | 9pt | 11pt | #FFFFFF | Centralizado |
| **Table cell** | Célula de tabela | Source Serif Pro | 400 (Regular) | 9pt | 11pt | #232527 | Esquerda |
| **Box title** | Título de caixa editorial | Inter | 700 (Bold) | 10pt | 13pt | Cor da categoria | Esquerda |
| **Box body** | Corpo de caixa editorial | Source Serif Pro | 400 (Regular) | 10pt | 14pt | #232527 | Justificado |
| **Ref** | Referência bibliográfica | Source Serif Pro | 400 (Regular) | 9.5pt | 13pt | #232527 | Justificado, indent. francesa 24pt |
| **Footer** | Rodapé | Inter | 400 (Regular) | 8.5pt | 11pt | #72787b | Esquerda/Direita |
| **Header** | Cabeçalho | Inter | 400 (Regular) | 8.5pt | 11pt | #72787b | Esquerda/Direita |
| **Watermark** | Marca d'água na capa | Inter | 900 (Black) | 280pt | 0.85 | #4a5f6a a 4% | — |
| **Code** | Bloco de código | DejaVu Sans Mono | 400 (Regular) | 8.5pt | 12pt | #232527 | Esquerda |
| **Manifesto** | Texto do manifesto (Cap. 12) | Source Serif Pro Bold | 700 (Bold) | 12pt | 18pt | #4a5f6a | Esquerda, indent. 20pt |
| **Letter** | Carta ao leitor (Cap. 12) | Source Serif Pro Italic | 400 Italic | 11pt | 17pt | #232527 | Justificado, indent. 30pt |

### 2.2 Justificativas

**Por que Source Serif Pro e não Times New Roman?**
Times New Roman é a fonte padrão de processadores de texto; sua uso transmite "documento de escritório", não "livro publicado". Source Serif Pro foi projetada especificamente para leitura prolongada em tela e impressão, com altura-x maior e aberturas mais largas que Times, melhorando legibilidade em tamanhos pequenos (9-10.5pt).

**Por que Inter e não Helvetica ou Arial?**
Helvetica é icônica mas datada (1957); Arial é considerada inferior tipograficamente. Inter (2017) é contemporânea, possui peso variável (permite ajuste fino de 100 a 900), foi projetada para telas de computador e tem excelente renderização em tamanhos pequenos (8-10pt) — crítico para cabeçalhos, rodapés e legendas.

**Por que não usar a mesma fonte para tudo?**
A combinação serif (corpo) + sans-serif (títulos) cria contraste visual que facilita a navegação. O leitor distingue instantaneamente "isto é um título" de "isto é texto" sem precisar ler. Monofonte para código é padrão universal em livros técnicos.

---

## ETAPA 3 — Paleta Cromática

### 3.1 Sistema Cascade

A paleta segue o sistema cascade: cores organizadas em tiers por área de uso, com saturação inversamente proporcional à área. Cores de大面积 têm saturação baixa; cores de pequena área têm saturação alta.

### 3.2 Paleta Completa

#### Tier XL — Fundos (área maior que 50% da página)

| Nome | HEX | RGB | CMYK | Uso |
|------|-----|-----|------|-----|
| PAGE_BG | #f2f3f3 | 242, 243, 243 | 0, 0, 0, 5 | Fundo de página (capa) |
| SECTION_BG | #ecedee | 236, 237, 238 | 0, 0, 0, 7 | Fundo de seção (raro) |

#### Tier L — Superfícies (área 20-50%)

| Nome | HEX | RGB | CMYK | Uso |
|------|-----|-----|------|-----|
| CARD_BG | #e7e9ea | 231, 233, 234 | 0, 0, 0, 9 | Fundo de caixas editoriais |
| TABLE_STRIPE | #eaecee | 234, 236, 238 | 0, 0, 0, 7 | Linhas alternadas de tabelas |

#### Tier M — Preenchimento Estrutural (área 5-20%)

| Nome | HEX | RGB | CMYK | Uso |
|------|-----|-----|------|-----|
| HEADER_FILL | #4a5f6a | 74, 95, 106 | 30, 10, 0, 58 | Títulos H1, cabeçalhos de tabela |
| COVER_BLOCK | #46555c | 70, 85, 92 | 24, 7, 0, 64 | Blocos de capa, elementos estruturais |

#### Tier S — Bordas e Ícones (área 1-5%)

| Nome | HEX | RGB | CMYK | Uso |
|------|-----|-----|------|-----|
| BORDER | #c2cfd6 | 194, 207, 214 | 10, 3, 0, 16 | Bordas de tabela, linhas de grade, separadores |
| ICON | #3f7088 | 63, 112, 136 | 54, 18, 0, 47 | Ícones, elementos secundários |

#### Tier XS — Ênfase (área menor que 1%)

| Nome | HEX | RGB | CMYK | Uso |
|------|-----|-----|------|-----|
| ACCENT | #2381b0 | 35, 129, 176 | 80, 27, 0, 31 | Destaque principal (azul ciano) |
| ACCENT_2 | #b73f53 | 183, 63, 83 | 0, 65, 55, 28 | Destaque secundário (vermelho) |

#### Texto

| Nome | HEX | RGB | CMYK | Uso |
|------|-----|-----|------|-----|
| TEXT_PRIMARY | #232527 | 35, 37, 39 | 0, 0, 0, 85 | Corpo de texto (não preto puro) |
| TEXT_MUTED | #72787b | 114, 120, 123 | 0, 0, 0, 52 | Legendas, metadados, rodapés |

#### Semânticas

| Nome | HEX | RGB | CMYK | Uso |
|------|-----|-----|------|-----|
| SEM_SUCCESS | #3e8656 | 62, 134, 86 | 54, 0, 36, 47 | Sucesso, positivo, sustentabilidade |
| SEM_WARNING | #9a7b3d | 154, 123, 61 | 0, 20, 60, 40 | Aviso, atenção, cuidado |

### 3.3 Combinações Aprovadas

| Combinação | Fundo | Texto | Contraste (WCAG) | Uso |
|------------|-------|-------|------------------|-----|
| Padrão | Branco (#FFFFFF) | #232527 | 15.8:1 ✓ AAA | Corpo de texto |
| Caixa | #e7e9ea | #232527 | 13.2:1 ✓ AAA | Caixas editoriais |
| Header tabela | #4a5f6a | #FFFFFF | 6.9:1 ✓ AAA | Cabeçalho de tabela |
| Destaque | Branco | #2381b0 | 4.8:1 ✓ AA | Texto de destaque |
| Limitação | Branco | #b73f53 | 4.9:1 ✓ AA | Texto de alerta |
| Muted | Branco | #72787b | 4.6:1 ✓ AA | Legendas |
| Sucesso | Branco | #3e8656 | 4.5:1 ✓ AA | Texto de sucesso |

### 3.4 Regras de Acessibilidade

- Todo texto atende WCAG 2.1 nível AA (contraste mínimo 4.5:1)
- Texto grande (acima de 18pt) atende AAA (contraste mínimo 3:1)
- Não usar cor como único diferenciador (sempre accompanying ícone ou texto)
- Em diagramas, texto sobre fundo colorido deve ter contraste mínimo 4.5:1

---

## ETAPA 4 — Grid Editorial

### 4.1 Dimensões e Margens

| Parâmetro | Valor | Justificativa |
|-----------|-------|---------------|
| Formato | A4 (210 × 297 mm) | Padrão internacional; compatível com impressão e leitura digital |
| Margem superior | 24 mm | Espaço para cabeçalho + respiro visual |
| Margem inferior | 24 mm | Espaço para rodapé + respiro |
| Margem interna | 22 mm | Menor que externa para otimizar área útil na lombada |
| Margem externa | 22 mm | Suficiente para thumb sem遮挡 texto |
| Área útil | 166 × 249 mm | Largura × altura de texto |
| Área segura | 156 × 239 mm | 10mm de margem interna adicional para elementos que não podem ser cortados |

### 4.2 Sistema de Colunas

| Layout | Colunas | Largura coluna | Gutter | Uso |
|--------|---------|----------------|--------|-----|
| **Principal** | 1 | 166 mm | — | Texto corrido, parágrafos, caixas |
| **Tabela larga** | 1 | 166 mm | — | Tabelas que usam largura total |
| **Figura + texto** | 2 | 80 mm cada | 6 mm | Raramente usado; figuras são full-width por padrão |
| **Comparativo** | 2 | 80 mm cada | 6 mm | Tabelas comparativas lado a lado (raro) |

**Regra:** o livro é predominantemente de coluna única. Layouts de duas colunas são exceção, usados apenas em comparações diretas autorizadas pelo editor.

### 4.3 Linha Base (Baseline Grid)

| Parâmetro | Valor |
|-----------|-------|
| Linha base | 4 pt |
| Múltiplo para body | 4 linhas base = 16 pt (entrelinha) |
| Múltiplo para H1 | 7 linhas base = 28 pt |
| Múltiplo para H2 | 5 linhas base = 20 pt |
| Múltiplo para H3 | 4 linhas base = 16 pt |
| Múltiplo para caption | 3 linhas base = 12 pt |
| Espaçamento antes de H1 | 18 pt |
| Espaçamento depois de H1 | 10 pt |
| Espaçamento antes de H2 | 14 pt |
| Espaçamento depois de H2 | 8 pt |
| Espaçamento antes de figura | 8 pt |
| Espaçamento depois de figura | 4 pt |
| Espaçamento antes de legenda | 4 pt |
| Espaçamento depois de legenda | 10 pt |
| Espaçamento antes de tabela | 10 pt |
| Espaçamento depois de tabela | 4 pt |
| Espaçamento antes de caixa | 10 pt |
| Espaçamento depois de caixa | 10 pt |

### 4.4 Alinhamentos

| Elemento | Alinhamento | Justificativa |
|----------|-------------|---------------|
| Corpo de texto | Justificado | Aparência profissional; evita borda irregular direita |
| Títulos | Esquerda | Leitura natural ocidental; mas simples que centralizado |
| Legendas | Centralizado | Distingue do corpo; associa à figura |
| Cabeçalho tabela | Centralizado | Simetria com células |
| Células de tabela (1ª col) | Centralizado | Rótulos curtos |
| Células de tabela (demais) | Esquerda | Texto longo justificado ou esquerda |
| Caixas editoriais (título) | Esquerda | Mesmo alinhamento do corpo |
| Caixas editoriais (corpo) | Justificado | Consistência com corpo |
| Listas | Esquerda | Itens curtos não justificam |

### 4.5 Espaçamento Entre Parágrafos

| Situação | Espaçamento |
|----------|-------------|
| Entre parágrafos do mesmo bloco | 8 pt (spaceAfter) |
| Entre parágrafos após título | 8 pt |
| Indentação de primeira linha | 14 pt (3.5 mm) |
| Sem indentação após título | — |
| Sem indentação após figura/tabela | — |
| Sem indentação após caixa | — |

---

## ETAPA 5 — Identidade dos Capítulos

### 5.1 Página de Abertura de Capítulo

Cada capítulo inicia com uma página de abertura que contém os seguintes elementos na ordem:

```
┌─────────────────────────────────────────┐
│                                         │
│  [Linha de grade sutil em toda página]  │
│                                         │
│  [Canto superior esquerdo: marca em L]  │
│                                         │
│  CAPÍTULO 3                             │ ← Inter 10pt, #72787b, tracking 2pt
│                                         │
│  Arquitetura Completa do                │ ← Source Serif Pro 42pt Bold, #232527
│  UNIHIKER K10                           │
│                                         │
│  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━     │ ← Linha horizontal 1.8pt, #2381b0
│                                         │
│  Datasheet comentado do hardware,       │ ← Source Serif Pro Italic 13pt, #2381b0
│  arquitetura e capacidades da plataforma│
│                                         │
│  ┌─────────────────────────────────┐    │
│  │ OBJETIVO                        │    │ ← Box de ficha técnica
│  │ Compreender profundamente o     │    │
│  │ hardware, arquitetura e         │    │
│  │ capacidades do K10.             │    │
│  │                                 │    │
│  │ COMPETÊNCIAS                    │    │
│  │ • Análise de arquitetura        │    │
│  │ • Seleção de subsistemas        │    │
│  │ • Benchmark de plataformas      │    │
│  │                                 │    │
│  │ PALAVRAS-CHAVE                  │    │
│  │ ESP32-S3 · Xtensa · TinyML      │    │
│  │ · Edge AI · GPIO · ADC · I²C   │    │
│  └─────────────────────────────────┘    │
│                                         │
│  [Canto inferior direito: marca em L]   │
│                                         │
│  [Watermark: "K10" a 4% opacidade]      │
│                                         │
└─────────────────────────────────────────┘
```

### 5.2 Elementos da Página de Abertura

| Elemento | Especificação |
|----------|---------------|
| Marca de canto (TL e BR) | L invertido, 120×120mm, 2pt, cor #2381b0 |
| Linha de grade | Padrão quadriculado 40×40mm, 0.05pt, #2381b0 a 5% |
| Barra de acento | 4pt largura, 280pt altura, gradiente #2381b0 → #b73f53 |
| Tag "CAPÍTULO N" | Inter Bold 10pt, #72787b, tracking 2pt, uppercase |
| Título | Source Serif Pro Bold 42pt, #232527, 2-3 linhas máx. |
| Subtítulo | Source Serif Pro Italic 13pt, #2381b0 |
| Linha separadora | HRFlowable 1.8pt, #2381b0, 100% largura |
| Box de ficha técnica | CARD_BG, borda 0.5pt #c2cfd6, padding 12pt |
| Watermark | Inter Black 280pt, #4a5f6a a 4% opacidade, canto inferior direito |

### 5.3 Continuação de Capítulo (páginas internas)

A partir da segunda página de cada capítulo, o cabeçalho e rodapé padrão são ativados:

**Página par (esquerda):**
```
┌─────────────────────────────────────────┐
│ Plataformas UNIHIKER · Capítulo 3       │ ← Header, Inter 8.5pt, #72787b
│ ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━     │ ← Linha 0.6pt, #c2cfd6
│                                         │
│ [conteúdo]                              │
│                                         │
│ ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━     │ ← Linha 0.4pt, #c2cfd6
│ Capítulo 3 · Edição Brasileira    Pág.5 │ ← Footer, Inter 8.5pt, #72787b
└─────────────────────────────────────────┘
```

**Página ímpar (direita):**
```
┌─────────────────────────────────────────┐
│          Arquitetura do UNIHIKER K10    │ ← Header, Inter 8.5pt, #72787b
│ ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━     │ ← Linha 0.6pt, #c2cfd6
│                                         │
│ [conteúdo]                              │
│                                         │
│ ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━     │ ← Linha 0.4pt, #c2cfd6
│ Capítulo 3 · Edição Brasileira    Pág.6 │ ← Footer, Inter 8.5pt, #72787b
└─────────────────────────────────────────┘
```

---

## ETAPA 6 — Páginas de Abertura das Partes

### 6.1 Layout da Divisória de Parte

```
┌─────────────────────────────────────────┐
│                                         │
│                                         │
│                                         │
│                                         │
│              PARTE II                   │ ← Inter Black 14pt, #2381b0
│                                         │    tracking 6pt, uppercase
│         Arquitetura                     │ ← Inter Light 48pt, #4a5f6a
│            e Projeto                   │
│                                         │
│         ━━━━━━━━━━━━━━━━               │ ← Linha 2pt, #2381b0, 40mm
│                                         │
│    "A arquitetura vale mais que         │ ← Source Serif Pro Italic 14pt,
│     o código."                          │    #72787b, centralizado
│     — Manifesto, Cap. 12               │
│                                         │
│                                         │
│    Capítulo 3 — Arquitetura do K10      │ ← Inter Regular 11pt, #72787b
│    Capítulo 4 — Arquitetura do M10      │
│    Capítulo 5 — Guia de Escolha         │
│    Capítulo 6 — Sistemas Inteligentes   │
│                                         │
│                                         │
│    Promessa: ao final da Parte II,      │ ← Source Serif Pro Italic 12pt,
│    você saberá escolher e arquitetar    │    #2381b0, centralizado
│    soluções com UNIHIKER.              │
│                                         │
│                                         │
└─────────────────────────────────────────┘
```

### 6.2 Especificações da Divisória

| Elemento | Especificação |
|----------|---------------|
| Fundo | #f2f3f3 (cinza muito claro) |
| Margens | Simétricas (todas 80mm do conteúdo) |
| Sem cabeçalho | Divisória não tem header |
| Sem rodapé | Divisória não tem footer |
| Sem número de página | Página conta na numeração mas não exibe |
| "PARTE X" | Inter Black 14pt, #2381b0, tracking 6pt |
| Título da parte | Inter Light 48pt, #4a5f6a |
| Linha decorativa | 2pt, #2381b0, 40mm de largura, centralizada |
| Epígrafe | Source Serif Pro Italic 14pt, #72787b |
| Lista de capítulos | Inter Regular 11pt, #72787b |
| Promessa | Source Serif Pro Italic 12pt, #2381b0 |

### 6.3 Espaço Negativo

A divisória utiliza **60% de espaço negativo** acima do conteúdo principal. Isso cria impacto visual e pausa cognitiva: o leitor percebe que está entrando em uma nova seção da obra.

---

## ETAPA 7 — Elementos Gráficos Padronizados

### 7.1 Caixas Editoriais (45 tipos)

#### Estrutura Visual

```
    ┌───┬─────────────────────────────────────────────┐
    │   │ ■  ENGENHARIA EM FOCO                       │ ← Título: Inter Bold 10pt, cor da categoria
    │ B │                                             │
    │ o │ A DFRobot escolheu o ESP32-S3 como SoC do  │ ← Corpo: Source Serif Pro 10pt, #232527
    │ r │ K10 por três motivos técnicos: (1) o       │
    │ d │ ESP32-S3 oferece instruções vetoriais...   │
    │ a │                                             │
    │   │                                             │
    └───┴─────────────────────────────────────────────┘
     ↑
     Borda esquerda colorida, 5pt de largura
```

#### Especificações

| Parâmetro | Valor |
|-----------|-------|
| Largura total | Igual à área útil (166mm) |
| Borda esquerda | 5pt (ou 1.75mm), cor da categoria |
| Borda externa | 0.5pt, cor da categoria |
| Fundo | #e7e9ea (CARD_BG) |
| Padding interno | 16pt esquerda, 12pt direita, 8pt acima/abaixo |
| Título | Inter Bold 10pt, cor da categoria, tracking 0.5pt |
| Corpo | Source Serif Pro 10pt, #232527, justificado |
| Espaçamento antes | 10pt |
| Espaçamento depois | 10pt |
| Cantos arredondados | 2pt (externo), 0pt (borda esquerda) |

### 7.2 Tabelas

#### Estrutura

```
    ┌─────────────────────────────────────────────┐
    │  PARÂMETRO        │  VALOR        │  UNID.  │ ← Header: fundo #4a5f6a, texto branco
    ├───────────────────┼───────────────┼─────────┤
    │  Temperatura      │  25.5         │  °C     │ ← Linha ímpar: branco
    ├───────────────────┼───────────────┼─────────┤
    │  Pressão          │  101.3        │  kPa    │ ← Linha par: #eaecee
    └─────────────────────────────────────────────┘
    
    Tabela 10.1 — Parâmetros ambientais. Fonte: elaborado pelo autor.
    ↑ Legenda abaixo, Source Serif Pro Italic 9pt, #72787b, centralizado
```

#### Especificações

| Parâmetro | Valor |
|-----------|-------|
| Largura | 100% da área útil |
| Header | Fundo #4a5f6a, texto #FFFFFF, Inter Bold 9pt |
| Linha ímpar | Fundo branco (#FFFFFF) |
| Linha par | Fundo #eaecee (TABLE_STRIPE) |
| Borda | 0.4pt, #c2cfd6 (BORDER) |
| Padding célula | 5pt horizontal, 5pt vertical |
| Alinhamento 1ª coluna | Centralizado |
| Alinhamento demais colunas | Esquerda |
| Legenda | Source Serif Pro Italic 9pt, #72787b, centralizado |
| Espaçamento antes | 10pt |
| Espaçamento depois (legenda) | 10pt |
| hAlign | CENTER (tabela centralizada na página) |

### 7.3 Fluxogramas e Diagramas

Todos os fluxogramas e diagramas seguem o mesmo sistema visual:

| Elemento | Especificação |
|----------|---------------|
| Fundo | Branco (#FFFFFF) |
| Caixas (nós) | FancyBboxPatch, cantos arredondados 4pt |
| Cor de preenchimento | Cor da categoria (tier M ou XS) |
| Cor de borda | Branco (#FFFFFF), 1.5-2pt |
| Texto em caixa | Branco (#FFFFFF), Inter Bold 9-11pt |
| Setas | 1.5pt, cor BORDER (#c2cfd6) |
| Setas de feedback | 2pt, tracejada, cor ACCENT_2 |
| Linhas de grade | 0.5pt, #c2cfd6, 20% opacidade |
| Texto de annotation | Inter Regular 8pt, cor da categoria |
| Resolução | 180 DPI (matplotlib) ou 300 DPI (manual) |
| Fundo da figura | Branco (não transparente) |
| Largura máxima | 100% da área útil |

### 7.4 Ícones

A obra utiliza símbolos Unicode clássicos (não emoji) para identificar caixas editoriais:

| Símbolo | Unicode | Uso |
|---------|---------|-----|
| ■ | U+25A0 | Engenharia em Foco |
| ▲ | U+25B2 | Limitação / Alerta / Arquitetura |
| ◆ | U+25C6 | Insight |
| ● | U+25CF | Curiosidade |
| ◑ | U+25D1 | Laboratório |
| ▦ | U+25A6 | Benchmark |
| ★ | U+2605 | Aplicação Real |
| ⚖ | U+2696 | Trade-off |
| ✓ | U+2713 | Decisão / Sucesso |
| ☐ | U+2610 | Checkbox |

### 7.5 Checklists

Checklists usam checkboxes Unicode (☐) seguidos de texto:

```
☐ Precisão adequada à aplicação
☐ Alimentação compatível (3.3V/5V)
☐ Interface compatível com K10/M10
☐ Biblioteca testada e documentada
```

**Especificação:** Source Serif Pro 10pt, #232527, alinhamento esquerda, sem indentação, espaçamento entre itens 2pt.

### 7.6 Linhas do Tempo

Linhas do tempo são diagramas horizontais com:

- Linha principal: 3pt, cor HEADER_FILL
- Marcadores de evento: círculos 13pt diâmetro, cor ACCENT ou ACCENT_2
- Hastes: 1pt tracejada, cor BORDER
- Data: Inter Bold 9pt, cor do marcador
- Descrição: Source Serif Pro 8pt, #232527, em caixa branca com borda

---

## ETAPA 8 — Identidade Visual das Figuras Técnicas

### 8.1 Padrão de Figuras

Todas as figuras técnicas da obra seguem o mesmo sistema visual:

#### 8.1.1 Diagramas de Blocos

| Elemento | Especificação |
|----------|---------------|
| Caixas (blocos) | Cantos arredondados (radius 4pt), preenchimento sólido |
| Cor de preenchimento | Cor da categoria (paleta cascade tier M ou XS) |
| Cor de borda | Branco (#FFFFFF), 1.5-2.5pt |
| Sombra | Nenhuma (flat design) |
| Texto dentro de caixa | Branco (#FFFFFF), Inter Bold 9-12pt |
| Texto secundário | Branco, Inter Regular 8pt |
| Conectores | Linhas retas com setas, 1.5pt, cor BORDER |
| Conectores bidirecionais | Setas duplas, mesma espessura |
| Conectores de feedback | Tracejados, 2pt, cor ACCENT_2 |
| Fundo da figura | Branco (#FFFFFF) |
| Grid de fundo (opcional) | 0.05pt, #2381b0 a 5% opacidade, 40×40mm |

#### 8.1.2 Gráficos (bar, radar, linha)

| Elemento | Especificação |
|----------|---------------|
| Fundo | Branco (#FFFFFF) |
| Eixos | 1pt, #c2cfd6 |
| Grid | 0.8pt, #c2cfd6, 30% opacidade |
| Labels eixo X | Inter Regular 9pt, #232527 |
| Labels eixo Y | Inter Regular 8pt, #72787b |
| Título do gráfico | Inter Bold 12.5pt, #232527 |
| Legenda | Inter Regular 9pt, fundo branco com borda |
| Séries de dados | Cores: ACCENT, ACCENT_2, SEM_SUCCESS, SEM_WARNING, HEADER_FILL, ICON, COVER_BLOCK |
| Barras | Alpha 0.9, borda branca 1.5pt |
| Linhas | 2.5pt, marcadores 6pt |
| Área preenchida | Alpha 0.18 |

#### 8.1.3 Fotografias

| Elemento | Especificação |
|----------|---------------|
| Resolução mínima | 300 DPI |
| Formato | JPG (fotografias) ou PNG (diagramas com texto) |
| Cor | RGB (para digital), CMYK (para impressão) |
| Largura máxima | 100% da área útil (166mm) |
| Altura máxima | 40% da altura útil (~100mm) |
| Bordas | Sem borda (a legenda identifica a figura) |
| Créditos | Incluídos na legenda, não na imagem |

### 8.2 Numeração de Figuras

- Formato: "Figura X.Y" onde X = número do capítulo, Y = sequencial no capítulo
- Posição: na legenda, abaixo da figura
- Formato da legenda: "Figura X.Y — Descrição descritiva. Fonte: origem."
- Exemplo: "Figura 6.4 — Mapa de convergência tecnológica. Fonte: elaborado pelo autor."

### 8.3 Legenda Padrão

```
Figura 6.4 — Mapa de convergência tecnológica: oito forças
convergem para sistemas inteligentes. Fonte: elaborado pelo autor.
```

**Especificação:** Source Serif Pro Italic 9pt, #72787b, centralizado, entrelinha 12pt, espaçamento antes 4pt, espaçamento depois 10pt.

---

## ETAPA 9 — Capa: Briefing Técnico

### 9.1 Conceito

A capa deve comunicar **precisão técnica com elegância editorial**. O conceito visual é "engenharia como arquitetura": linhas retas, geometria pura, espaço negativo generoso, tipografia como elemento principal.

### 9.2 Hierarquia Visual

```
1. Título da coleção (topo, pequeno)
2. Número do volume (centralizado, grande)
3. Título do volume (centralizado, médio)
4. Subtítulo (abaixo do título, itálico)
5. Autor (rodapé)
6. Editora (rodapé)
```

### 9.3 Tipografia da Capa

| Elemento | Família | Peso | Tamanho | Cor |
|----------|---------|------|---------|-----|
| Coleção | Inter | 500 (Medium) | 13pt | #2381b0 |
| Volume | Inter | 200 (ExtraLight) | 96pt | #4a5f6a |
| Título | Source Serif Pro | 700 (Bold) | 42pt | #232527 |
| Subtítulo | Source Serif Pro | 400 Italic | 18pt | #72787b |
| Autor | Inter | 500 (Medium) | 14pt | #232527 |
| Editora | Inter | 400 (Regular) | 11pt | #72787b |

### 9.4 Composição

```
┌─────────────────────────────────────────┐
│ ┌─[Marca de canto TL]                   │
│ │                                       │
│ │  LIVRO TÉCNICO · ENGENHARIA EMBARCADA │ ← Kicker
│ │                          PLATAFORMAS  │ ← Book info (direita)
│ │                            UNIHIKER   │
│ │                                       │
│ │  [Barra de acento vertical]           │
│ │  │                                    │
│ │  │  01                                │ ← Número do capítulo/volume
│ │  │  Capítulo                          │
│ │  │                                    │
│ │  │  A DFRobot e a Origem              │ ← Título
│ │  │  da Plataforma UNIHIKER            │
│ │  │                                    │
│ │  │  [Subtítulo em itálico]            │
│ │  │                                    │
│ │  │  [Resumo em parágrafo]             │
│ │  │                                    │
│ │  │  [Tags em pills]                   │
│ │  │                                    │
│ │  │  Capítulo 1/12  Área  Edição       │ ← Meta
│ │  │                                    │
│ └─[Marca de canto BR]                   │
│           PLATAFORMAS UNIHIKER · DFR    │ ← Footer
└─────────────────────────────────────────┘
```

### 9.5 Elementos Gráficos da Capa

| Elemento | Especificação |
|----------|---------------|
| Grade de fundo | Quadriculado 40×40mm, 0.05pt, #2381b0 a 5% |
| Marca de canto TL | L invertido 120×120mm, 2pt, #2381b0 |
| Marca de canto BR | L invertido 120×120mm, 2pt, #2381b0 |
| Barra de acento | 4pt largura, 280pt altura, gradiente #2381b0 → #b73f53 |
| Linha superior | 1pt, #c2cfd6, margem 80mm |
| Linha inferior | 1pt, #c2cfd6, margem 80mm |
| Watermark | Inter Black 280pt, #4a5f6a a 4% opacidade |
| Tags (pills) | Borda 1pt #c2cfd6, radius 14pt, fundo branco 60% |
| Fundo | #f2f3f3 (cinza muito claro) |

### 9.6 Acabamentos

| Acabamento | Especificação |
|------------|---------------|
| Laminação | Fosca (matte) |
| Verniz | Localizado UV no título e na barra de acento |
| Hot stamping | Opcional: título em hot stamping prata fosca |
| Relevo | Opcional: marca de canto em relevo seco |

### 9.7 Lombada

| Elemento | Especificação |
|----------|---------------|
| Largura | 25mm (para ~370 páginas em Offset 90g/m²) |
| Texto | Rotacionado 90° (lê-se de cima para baixo) |
| Conteúdo | Título abreviado + "Volume I" + editora |
| Tipografia | Inter Bold 10pt, #232527 |
| Elemento gráfico | Barra de acento #2381b0 no topo |

### 9.8 Contracapa

| Elemento | Especificação |
|----------|---------------|
| Fundo | #f2f3f3 |
| Sinopse | Source Serif Pro 10pt, #232527, 8-10 linhas |
| ISBN | Inter Regular 10pt, #72787b, com código de barras |
| QR Code | 30×30mm, link para recursos online |
| Logo editora | 20×20mm, canto inferior direito |
| Preço | Opcional, canto inferior esquerdo |

### 9.9 Orelhas (se brochura com orelhas)

| Orelha | Conteúdo |
|--------|----------|
| Frente esquerda | Sobre o autor (foto + bio de 50 palavras) |
| Frente direita | "Outros volumes da coleção" (lista dos 3 volumes) |

---

## ETAPA 10 — Manual de Consistência Visual

### 10.1 Checklist de Consistência (50 itens)

#### Tipografia (10 itens)

| # | Verificação | ☐ |
|---|-------------|---|
| 1 | Source Serif Pro usada em todo corpo de texto | ☐ |
| 2 | Inter usada em todos os títulos e elementos funcionais | ☐ |
| 3 | DejaVu Sans Mono usada em todo código | ☐ |
| 4 | Escala tipográfica respeitada (sem tamanhos inventados) | ☐ |
| 5 | Pesos tipográficos corretos (Regular para corpo, Bold para títulos) | ☐ |
| 6 | Entrelinha de 16pt para corpo (4× baseline grid) | ☐ |
| 7 | Tracking de 2-4pt apenas em elementos uppercase (tags, kickers) | ☐ |
| 8 | Itálico usado apenas para legendas, citações e termos estrangeiros | ☐ |
| 9 | Negrito usado apenas para ênfase inline e títulos | ☐ |
| 10 | Não usar sublinhado (exceto em hyperlinks digitais) | ☐ |

#### Cor (10 itens)

| # | Verificação | ☐ |
|---|-------------|---|
| 11 | Paleta cascade respeitada (sem cores inventadas) | ☐ |
| 12 | Cor do corpo: #232527 (não #000000) | ☐ |
| 13 | Cor de títulos H1: #4a5f6a | ☐ |
| 14 | Cor de títulos H2: #2381b0 | ☐ |
| 15 | Cor de legendas: #72787b | ☐ |
| 16 | Header de tabela: fundo #4a5f6a, texto branco | ☐ |
| 17 | Linhas alternadas de tabela: branco e #eaecee | ☐ |
| 18 | Borda esquerda de caixas: 5pt na cor da categoria | ☐ |
| 19 | Fundo de caixas: #e7e9ea | ☐ |
| 20 | Cores semânticas corretas (verde=positivo, vermelho=alerta) | ☐ |

#### Grid e Espaçamento (10 itens)

| # | Verificação | ☐ |
|---|-------------|---|
| 21 | Margens: 24mm sup/inf, 22mm int/ext | ☐ |
| 22 | Coluna única como padrão | ☐ |
| 23 | Baseline grid de 4pt respeitado | ☐ |
| 24 | Espaçamento antes de H1: 18pt | ☐ |
| 25 | Espaçamento depois de H1: 10pt | ☐ |
| 26 | Espaçamento antes de figura: 8pt | ☐ |
| 27 | Espaçamento depois de legenda: 10pt | ☐ |
| 28 | Espaçamento antes de tabela: 10pt | ☐ |
| 29 | Espaçamento antes de caixa: 10pt | ☐ |
| 30 | Indentação de primeira linha: 14pt | ☐ |

#### Elementos Gráficos (10 itens)

| # | Verificação | ☐ |
|---|-------------|---|
| 31 | Caixas com borda esquerda 5pt e fundo #e7e9ea | ☐ |
| 32 | Tabelas centralizadas (hAlign=CENTER) | ☐ |
| 33 | Figuras centralizadas na página | ☐ |
| 34 | Diagramas com fundo branco | ☐ |
| 35 | Setas em diagramas: 1.5pt, cor BORDER | ☐ |
| 36 | Caixas em diagramas: cantos arredondados, flat design | ☐ |
| 37 | Cores de diagramas seguem paleta cascade | ☐ |
| 38 | Ícones Unicode (não emoji) | ☐ |
| 39 | Linhas de grade em diagramas: 0.05pt, 5% opacidade | ☐ |
| 40 | Watermark na capa: 4% opacidade | ☐ |

#### Cabeçalho e Rodapé (5 itens)

| # | Verificação | ☐ |
|---|-------------|---|
| 41 | Página par: "Plataformas UNIHIKER · Cap. N" à esquerda | ☐ |
| 42 | Página ímpar: "Título do capítulo" à direita | ☐ |
| 43 | Linha de cabeçalho: 0.6pt, #c2cfd6 | ☐ |
| 44 | Linha de rodapé: 0.4pt, #c2cfd6 | ☐ |
| 45 | Número de página à direita no rodapé | ☐ |

#### Numeração e Referência (5 itens)

| # | Verificação | ☐ |
|---|-------------|---|
| 46 | Figuras numeradas "Figura X.Y" (capítulo.sequencial) | ☐ |
| 47 | Tabelas numeradas "Tabela X.Y" | ☐ |
| 48 | Legendas incluem número, descrição e fonte | ☐ |
| 49 | Referências cruzadas em parênteses "(Cap. 3, Seção 3.5)" | ☐ |
| 50 | Paginação: romana no pré-texto, arábica no texto | ☐ |

---

## APÊNDICE A — Template de Estilos (CSS para diagramação digital)

```css
:root {
  --page-bg: #f2f3f3;
  --card-bg: #e7e9ea;
  --header-fill: #4a5f6a;
  --border: #c2cfd6;
  --accent: #2381b0;
  --accent-2: #b73f53;
  --text-primary: #232527;
  --text-muted: #72787b;
  --sem-success: #3e8656;
  --sem-warning: #9a7b3d;
}

body {
  font-family: 'Source Serif Pro', serif;
  font-size: 10.5pt;
  line-height: 16pt;
  color: var(--text-primary);
  text-align: justify;
}

h1 {
  font-family: 'Inter', sans-serif;
  font-weight: 700;
  font-size: 22pt;
  line-height: 28pt;
  color: var(--header-fill);
}

h2 {
  font-family: 'Inter', sans-serif;
  font-weight: 700;
  font-size: 15pt;
  line-height: 20pt;
  color: var(--accent);
}

h3 {
  font-family: 'Inter', sans-serif;
  font-weight: 700;
  font-size: 12pt;
  line-height: 16pt;
  color: var(--header-fill);
}

caption {
  font-family: 'Source Serif Pro', serif;
  font-style: italic;
  font-size: 9pt;
  line-height: 12pt;
  color: var(--text-muted);
  text-align: center;
}

table {
  width: 100%;
  border-collapse: collapse;
}

th {
  background: var(--header-fill);
  color: white;
  font-family: 'Inter', sans-serif;
  font-weight: 700;
  font-size: 9pt;
  padding: 5pt;
  text-align: center;
}

td {
  font-family: 'Source Serif Pro', serif;
  font-size: 9pt;
  padding: 5pt;
  border: 0.4pt solid var(--border);
}

tr:nth-child(even) td {
  background: #eaecee;
}

.highlight-box {
  background: var(--card-bg);
  border-left: 5pt solid var(--accent);
  border: 0.5pt solid var(--accent);
  padding: 8pt 12pt 8pt 16pt;
  margin: 10pt 0;
}

.highlight-box h4 {
  font-family: 'Inter', sans-serif;
  font-weight: 700;
  font-size: 10pt;
  color: var(--accent);
}

.highlight-box p {
  font-size: 10pt;
  line-height: 14pt;
}
```

---

## APÊNDICE B — Especificações para IA Generativa de Capa

### Prompt para geração de capa

```
CONCEITO: Capa de livro técnico profissional sobre engenharia de 
sistemas embarcados inteligentes. Estilo: minimalista, elegante, 
técnico. Referências visuais: Springer, IEEE Press, O'Reilly.

LAYOUT:
- Fundo cinza muito claro (#f2f3f3)
- Grade quadriculada sutil (5% opacidade, azul #2381b0)
- Marca em L nos cantos superior-esquerdo e inferior-direito (120mm, 2pt, azul)
- Barra vertical à esquerda (4pt largura, 280pt altura, gradiente azul→vermelho)
- Watermark no canto inferior direito ("UNIHIKER" a 4% opacidade, 280pt)

TIPOGRAFIA:
- "01" em extra-light 96pt (cinza azulado #4a5f6a)
- Título em serif bold 42pt (quase preto #232527)
- Subtítulo em itálico 18pt (cinza #72787b)
- Tags em pills com borda cinza

PALETA: #f2f3f3, #2381b0, #b73f53, #4a5f6a, #232527, #72787b

ESTILO: Flat design, sem sombras, sem gradientes (exceto barra de 
acento), sem fotografias, apenas tipografia e geometria pura.

PROPORÇÃO: A4 retrato (210×297mm) com margens de 80mm.
```

---

## APROVAÇÃO DO PROJETO GRÁFICO

| Papel | Nome | Data | Assinatura |
|-------|------|------|------------|
| Diretor de Arte | Z.ai Design Board | 18/07/2026 | Aprovado |
| Editor-Chefe | — | — | — |
| Diagramador | — | — | — |
| Autor | — | — | — |

---

**Fim do Documento Mestre do Projeto Gráfico.**

---
[↑ Voltar ao topo](#topo)
