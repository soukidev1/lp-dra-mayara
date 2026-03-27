# LP — Dra. Mayara Sasaki | Harmonização Facial

## Visão geral do projeto

Landing page de alta conversão para campanhas de Google Ads.
Foco exclusivo em Harmonização Facial.
Objetivo único: fazer o visitante clicar no botão de WhatsApp e agendar uma consulta.

Não é um site institucional. Não tem menu de navegação externo.
Cada elemento da página existe para reduzir fricção e aumentar conversão.

---

## Objetivo de negócio

- **Produto:** Consulta de avaliação de harmonização facial (gratuita ou paga — confirmar com cliente)
- **CTA principal:** Abrir WhatsApp com mensagem pré-preenchida
- **Público:** Mulheres 25–45 anos, BH e região, pesquisando harmonização facial no Google
- **Canal de tráfego:** Google Ads (Search + Display)

---

## Sobre a médica

- **Nome:** Dra. Mayara Sasaki
- **Especialidade:** Medicina Estética — Harmonização Facial
- **CRM:** SP 234436
- **Instagram:** @dra.mayarasasaki
- **Posicionamento:** Resultados naturais, técnica refinada, atendimento humanizado
- **Diferenciais:** Médica (não esteticista), CRM ativo, naturalidade nos resultados

---

## Sobre a clínica

- **Nome:** Vibe Clinic — Clínica de Estética — Savassi
- **Endereço:** R. Fernandes Tourinho, 470 — Sala 701/702, Savassi, BH — MG, 30112-004
- **Telefone:** (31) 99764-5936
- **Horário:** Aberto — fecha às 20h
- **Google:** 5,0 estrelas · 160 avaliações
- **Observação importante:** A Dra. Mayara *atende na* Vibe Clinic, mas não é dona da clínica.
  Nunca escrever "sua clínica" ou "clínica da Dra. Mayara". Usar "clínica onde atendo".

---

## Procedimentos a destacar

1. Preenchimento Labial
2. Toxina Botulínica (Botox)
3. Rinomodelação
4. Bichectomia
5. Skinbooster

Cada procedimento deve ter: nome, descrição curta (1–2 linhas), benefício principal.
Nunca prometer resultado específico. Usar linguagem como "pode", "contribui para", "auxilia".

---

## Stack técnica

- **HTML5** semântico
- **CSS3** puro — sem framework (sem Tailwind, sem Bootstrap)
- **JavaScript** vanilla — sem jQuery, sem React
- **Fontes:** Google Fonts (Cormorant Garamond + Jost)
- **Sem dependências externas** além das fontes
- **Um único arquivo:** `index.html` com CSS e JS inline (facilita deploy)

---

## Identidade visual

### Paleta de cores
```
--rose:        #C4788A   /* CTA, destaques, estrelas */
--rose-light:  #E8A8B5   /* textos sobre fundo escuro */
--rose-dark:   #9B4F62   /* hover nos botões */
--gold:        #7A6B55   /* textos secundários, nav */
--cream:       #FAF7F4   /* fundo principal */
--off-white:   #F5F0EB   /* fundo seções alternadas */
--dark:        #2A2118   /* fundo hero direito, seção sobre */
--near-black:  #1A1614   /* footer, browser bar */
--text-main:   #4A3830   /* corpo de texto */
```

### Tipografia
```
Cormorant Garamond — titulações, depoimentos, números grandes
  peso 300 (light) para títulos grandes
  peso 400 para títulos médios
  itálico para palavras-chave em destaque

Jost — navegação, corpo, CTAs, labels
  peso 300 (light) para parágrafos
  peso 400 (regular) para texto de interface
  peso 500 (medium) para botões e labels uppercase
```

### Regras de estilo
- Títulos grandes: Cormorant Garamond 300, com palavra-chave em itálico rose
- Botões: Jost 500, uppercase, letter-spacing 2–3px, border-radius 2px
- Tags/labels: Jost 400, uppercase, letter-spacing 3–4px, font-size 9–10px
- Nunca usar sombras pesadas — máximo box-shadow sutil
- Bordas: 0.5px, sempre com opacidade (rgba)
- Espaçamento generoso — padding de seção mínimo 80px vertical

---

## Estrutura de seções

### 1. Navbar
- Logo (texto ou PNG) à esquerda
- Links âncora à direita: Procedimentos · Sobre · Clínica · Depoimentos
- Botão CTA "Agendar Consulta" em rose no canto direito
- `position: sticky; top: 0` com backdrop-filter blur leve
- Height: 64px

### 2. Hero
- Layout: grid 50/50
- **Esquerda (fundo cream):**
  - Tag de localização (Medicina Estética · Belo Horizonte)
  - H1 em Cormorant Garamond com palavra em itálico rose
  - Subtítulo Jost Light
  - Dois botões: CTA WhatsApp (rose filled) + "Ver Procedimentos" (rose outlined)
  - Trust bar: número de pacientes · avaliações 5★ · CRM
- **Direita (fundo escuro #2A2118):**
  - Foto profissional da Dra. Mayara em tamanho grande
  - Badge flutuante com credencial
- H1 sugerido: "Beleza natural que *transforma* com segurança"

### 3. Ribbon
- Fundo escuro, full-width
- Lista dos 5 procedimentos separados por dots rose
- Função: âncora visual de autoridade + SEO on-page

### 4. Procedimentos
- Fundo cream
- Grid 4 colunas
- Cada card: foto/imagem do procedimento, nome em serif, descrição, link "Saiba mais"
- Hover: elevação sutil + borda rose

### 5. Sobre a médica
- Layout 50/50, fundo escuro
- Esquerda: foto profissional (ensaio em poltrona bege — já disponível)
- Direita: tag, nome em serif itálico, bio humanizada, tags de especialidade, CRM
- Tom: pessoal, próximo, confiável

### 6. Clínica (Vibe Clinic)
- Fundo off-white
- Layout 50/50
- **Esquerda:** card estilizado no formato Google Meu Negócio
  - Fotos da clínica
  - Nome, 5,0 estrelas, "160 avaliações no Google"
  - Endereço, telefone, horário
- **Direita:** copy de acolhimento + box de destaque das 5 estrelas + endereço
- Nunca dizer que ela é dona — usar "clínica onde atendo" ou "espaço onde recebo minhas pacientes"

### 7. Depoimentos
- Fundo cream
- Grid 3 colunas
- 3 depoimentos reais (pegar do Google ou Instagram)
- Cada card: 5 estrelas, texto em Cormorant itálico, avatar + nome

### 8. CTA Final
- Bloco full-width na cor rose (#C4788A)
- Headline grande em serif
- Subtítulo com localização
- Botão branco com texto rose
- Micro-copy: "Resposta em até 1h · Sem compromisso"

### 9. Footer
- Fundo near-black
- Logo/nome à esquerda
- Instagram + cidade à direita
- Opcional: links de política de privacidade

---

## CTA — WhatsApp

O botão deve abrir o WhatsApp com mensagem pré-preenchida:

```
https://wa.me/5531XXXXXXXXX?text=Olá,%20Dra.%20Mayara!%20Vim%20pelo%20site%20e%20gostaria%20de%20agendar%20uma%20consulta%20de%20harmonização%20facial.
```

Substituir `XXXXXXXXX` pelo número real.
Usar `target="_blank"` e `rel="noopener"`.

---

## Regras de copy (tom de voz)

- Tom: sofisticado, humano, próximo — não clínico nem frio
- Nunca prometer resultado garantido
- Evitar palavras genéricas: "qualidade", "excelência", "melhor"
- Preferir: "naturalidade", "técnica", "segurança", "resultado discreto"
- Usar a primeira pessoa quando for texto da médica: "atendo", "realizo", "cuido"
- Falar com a paciente em segunda pessoa: "você", "sua versão", "o que você já tem"

---

## SEO on-page (básico para Google Ads)

```html
<title>Harmonização Facial em BH | Dra. Mayara Sasaki</title>
<meta name="description" content="Harmonização facial natural e segura com a Dra. Mayara Sasaki, especialista em Medicina Estética em Belo Horizonte. Agende sua consulta.">
```

H1 deve conter: harmonização facial
H2 das seções devem conter variações: procedimentos, médica, Belo Horizonte

---

## Arquivos esperados

```
lp-dra-mayara/
├── index.html          ← arquivo principal (tudo inline)
├── CLAUDE.md           ← este arquivo
└── assets/
    ├── logo.png         ← Logotipo_Principal_COR.png
    ├── simbolo.png      ← Simbolo.png
    ├── foto-dra.jpg     ← foto profissional da médica
    └── clinica/
        └── *.jpg        ← fotos da Vibe Clinic
```

---

## O que NÃO fazer

- Não criar múltiplas páginas — é uma LP de conversão, tudo em uma página
- Não adicionar blog, menu complexo ou links externos desnecessários
- Não usar imagens de banco de imagens genéricas — apenas fotos reais da médica e da clínica
- Não colocar preços (a menos que o cliente solicite)
- Não usar pop-ups agressivos
- Não deixar o fundo branco puro (#FFFFFF) — usar sempre #FAF7F4
- Não usar Inter, Roboto ou Arial — apenas Cormorant Garamond + Jost
