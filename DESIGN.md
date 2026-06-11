---
name: Grupo SETEC Marine Service
colors:
  background: '#121315'
  primary: '#b4c9df'
  primary-container: '#0e2334'
  on-primary: '#1e3244'
  on-primary-container: '#778ba0'
  secondary: '#a0cafc'
  secondary-container: '#184974'
  on-secondary: '#003257'
  on-secondary-container: '#8eb8ea'
  tertiary: '#e5c09a'
  tertiary-container: '#311d04'
  on-tertiary: '#422c11'
  on-tertiary-container: '#a38361'
  copper: '#B46E3C'
  cream-bg: '#ECE6D6'
  surface: '#121315'
  surface-dim: '#121315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0d0e10'
  surface-container-low: '#1b1c1d'
  surface-container: '#1f2021'
  surface-container-high: '#292a2b'
  surface-container-highest: '#343536'
  on-surface: '#e4e2e3'
  on-surface-variant: '#c3c7cc'
  outline: '#8d9196'
  outline-variant: '#43474c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
typography:
  display-xl:
    fontFamily: Outfit
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Outfit
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Outfit
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Outfit
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Outfit
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Outfit
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Outfit
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
  highlight-italic:
    fontFamily: Playfair Display
    fontSize: 1.1em
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  DEFAULT: 0.25rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max-width: 1280px
  section-padding-y: 120px
  stack-md: 24px
  stack-sm: 8px
  gutter: 32px
  stack-lg: 48px
---

# Design System: Grupo SETEC — Marine Service

Este documento define a linguagem de design, a paleta de cores, as regras tipográficas e os padrões de componentes da landing page do **Grupo SETEC — Marine Service**.

## 1. Visual Theme & Atmosphere

A identidade visual do Grupo SETEC transmite **alta confiabilidade técnica, robustez industrial e prestígio marítimo**. O design utiliza uma combinação sofisticada de tons escuros e profundos da engenharia oceânica (Navy e Slate) contrastados com a elegância do **Cobre Industrial** e a leveza de um fundo de areia/creme para seções explicativas.

O contraste de elementos de vidro e cartões semitransparentes escuros com o calor das seções de cor creme cria um ritmo visual dinâmico, moderno e de alta qualidade. O espaçamento é generoso, enfatizando um design "respirável", limpo e profissional, ideal para operações corporativas e de engenharia crítica.

## 2. Color Palette & Roles

### Primary Foundation
*   **Deep Oceanic Slate** (`#121315`): Cor de fundo principal escura que fornece uma base sóbria e tecnológica.
*   **Deep Container Blue** (`#0e2334`): Tom azul-marinho fechado usado para destacar contêineres e o cabeçalho.
*   **Warm Sand Cream** (`#ECE6D6`): Fundo claro e quente usado para seções institucionais que exigem alta legibilidade e sofisticação.

### Accent & Interactive
*   **Industrial Copper** (`#B46E3C`): A cor de destaque primária que simboliza aço, engrenagens e engenharia marítima. Utilizado para CTAs principais, ícones de diferenciais e realces importantes.
*   **Interactive Blue** (`#a0cafc`): Utilizado para sinalizar links, hovers e interações leves.

### Typography & Text Hierarchy
*   **Frost White** (`#e4e2e3` / `white`): Texto primário sobre fundos escuros para máxima legibilidade.
*   **Deep Charcoal** (`#1e3244`): Texto primário e de títulos sobre a seção clara Sand Cream.
*   **Muted Blue Gray** (`#778ba0`): Subtítulos e descrições secundárias sobre fundos escuros.

### Functional States
*   **Error / Warning**: Coral suave (`#ffb4ab`) para mensagens de erro, contrastado por um tom escuro (`#93000a`).

## 3. Typography Rules

A tipografia do projeto é refinada, combinando a legibilidade limpa e técnica de uma fonte geométrica sem-serifa com a expressividade de uma serifa clássica.

*   **Outfit**: Fonte principal sem-serifa, limpa, moderna e ideal para displays de grandes dimensões e textos técnicos.
*   **Playfair Display**: Fonte serifada italiana aplicada em itálico para dar ênfase a palavras de impacto (ex: *inegociável*), evocando prestígio e autoridade.

### Hierarchy & Weights
*   **Display XL (72px, Bold)**: Títulos principais de impacto (Hero).
*   **Headline LG (48px, Semi-Bold)**: Títulos das seções principais.
*   **Headline MD (32px, Medium)**: Subtítulos de seções e cartões bento.
*   **Body LG (18px, Regular)**: Descrições principais e parágrafos introdutórios.
*   **Body MD (16px, Regular)**: Texto corrido e descrições de cartões.
*   **Label Caps (12px, Bold, Uppercase)**: Tags, botões e pequenos rótulos de navegação.

## 4. Component Stylings

### Buttons
*   **Primary CTA**: Fundo Industrial Copper (`#B46E3C`), cantos arredondados (`lg`), texto em caixa alta (`label-caps`) branco. Efeitos de hover aumentam o brilho (`hover:brightness-110`) e efeito ativo aplica uma leve redução de escala (`active:scale-95`).
*   **Secondary CTA**: Fundo transparente, borda fina branca (`border-white/20`), backdrop blur de vidro, com transição de hover para maior opacidade.

### Cards & Containers
*   **Bento Grid Cards**: Bordas finas de contorno (`border-outline-variant/10`), fundo branco opaco com sombra suave em seções claras, ou `glass-card` (fundo com opacidade de 5% e desfoque de 10px) em seções escuras.

### Navigation
*   **Sticky Header**: Transparente na abertura e encolhe com fundo escuro (`#1b1c1d`) e borda inferior sutil após scroll de 100px. Links devem manter o contraste legível o tempo todo.

### Inputs & Forms
*   **Formulários**: Estilo minimalista com borda inferior fina de 2px, fundo transparente e transição de foco para a cor Industrial Copper com remoção do outline padrão.

## 5. Layout Principles

### Grid & Structure
*   **Max Content Width**: Limitado a `1280px` (`max-w-container-max-width`) para evitar estiramento visual em monitores ultrawide.
*   **Section Padding**: Espaçamento vertical generoso de `120px` (`py-section-padding-y`) para separar de forma limpa as áreas do site.
*   **Layout Responsivo**: Grid colapsável de 3 colunas para 1 coluna no celular.

---

## 6. Design System Notes for Stitch Generation

### Language to Use
"Sophisticated industrial maritime aesthetic", "deep navy oceanic blue tone", "high-end copper metal accents", "clean minimal modern tech dashboard", "crisp high-contrast typography", "tactile pebbling buttons".

### Color References
*   Background: `#121315`
*   Copper: `#B46E3C`
*   Cream: `#ECE6D6`
*   Container: `#0e2334`

### Component Prompts
*   `Modern sticky navbar with transparent background that turns solid dark navy and shrinks on scroll.`
*   `Responsive infinite marquee logo carousel with smooth sliding motion and blurred edges.`
*   `Tactile copper action button with sharp uppercase typography and smooth scale active state.`
