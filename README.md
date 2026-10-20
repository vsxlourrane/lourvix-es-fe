# 🇦🇷 Lourvix ES · Fernando

Aula interativa de **espanhol profissional** voltada para um desenvolvedor backend brasileiro que atua com times argentinos em projetos de tecnologia, finanças e administração.

O material combina **flashcards de expressões argentinas**, um **cenário crítico de reunião** com quiz de compreensão e uma **tabela de verbos em voseo** aplicados ao contexto corporativo.

---

## 🎯 Objetivo pedagógico

- **Aprimorar a compreensão auditiva** do espanhol rioplatense (sotaque argentino), especialmente em reuniões de trabalho.
- **Praticar o voseo** (presente e imperativo) em contextos reais: deploy, análise de carga, fluxo administrativo, decisão financeira.
- **Ampliar o vocabulário técnico** de TI, finanças e administração em espanhol.
- **Reconhecer gírias e expressões** do dia a dia profissional portenho (*che, boludo, posta, tomar un mate, chamuyar* etc.).

---

## 🧩 Estrutura da página

O site é composto por três seções principais:

### 01 · Memoria Activa — Flashcards · Expresiones Argentinas
Cartas interativas que viram ao clique (ou `Enter` / `Espaço`). Cada carta traz:
- **Anverso**: a expressão em destaque + categoria (*Argentina · Informal*, *Java*, *Git*, *Reunião* etc.)
- **Reverso**: tradução em português, definição contextualizada e um exemplo real de uso.

Expressões incluídas:
`Che` · `Boludo` · `Posta` · `Tomar un mate` · `Tunar` · `Limar` · `Pincharse` · `Escupir` · `Stremear` · `Inyectar` · `Mergear/Pushear/Commitear` · `Ponerse las pilas` · `Colgarse` · `Chamuyar`

### 07 · Atención Crítica — Situación hipotética
Narrativa de uma reunião tensa entre Fernando (Brasil) e o time de Buenos Aires durante um incidente em produção no microserviço de transferências. O texto usa deliberadamente:
- Verbos da rotina técnica em voseo
- Marcadores argentinos de conversação
- Vocabulário financeiro e de arquitetura Java

Ao final, um **quiz de 10 perguntas** (10 pontos cada, total 100) com feedback imediato:
- Alternativa correta fica verde ✅
- Alternativa errada fica vermelha ❌
- Explicação contextual aparece abaixo da pergunta
- Barra de progresso e pontuação atualizam em tempo real

### 08 · Léxico verbal — 10 verbos de reunión en voseo
Tabela responsiva com:

| Coluna | Conteúdo |
|---|---|
| Verbo · significado | Infinitivo + tradução contextual (ex.: *Destrabar* → solucionar gargalo) |
| Presente · vos | Forma conjugada em voseo (ex.: *Vos destrabás*) |
| Imperativo · vos | Imperativo afirmativo (ex.: *Destrabá vos*) |
| Ejemplo en contexto | Frase real de reunião |

Verbos cobertos: `Destrabar` · `Analizar` · `Presupuestar` · `Implementar` · `Decidir` · `Mitigar` · `Liquidar` · `Relevar` · `Demorar` · `Rendir`

Em telas menores que 720px, a tabela vira cartões empilhados para melhor leitura no celular.

---

## 🛠️ Stack técnica

Projeto **100% estático**, sem frameworks, sem etapa de build:

| Camada | Tecnologia |
|---|---|
| Estrutura | HTML5 semântico |
| Estilo | CSS3 (variáveis, grid, flexbox, transições 3D) |
| Comportamento | JavaScript puro (Vanilla JS, IIFE) |

Sem dependências externas, sem `node_modules`, sem CDN. Tudo em um único arquivo `index.html`.

---

## 📁 Estrutura do repositório
lourvix-es-fe/
├── index.html ← todo o site (HTML + CSS + JS embutidos)
└── README.md ← este arquivo


---

## 🚀 Como rodar localmente

Como é um site estático, basta abrir o arquivo no navegador:

- **Windows**: duplo clique em `index.html`
- **Terminal (opcional, servidor local)**:
  ```bash
  python -m http.server 8000