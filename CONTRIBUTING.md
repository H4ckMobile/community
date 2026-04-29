# Contributing to h4ckmobile/community

> 🇧🇷 Versão em português logo abaixo. / Portuguese version below.

Thanks for taking the time to contribute. This repo exists so readers of [h4ckmobile.com](https://h4ckmobile.com) can flag errors, suggest topics, and ask questions about the blog. Everything here is governed by the [Code of Conduct](./CODE_OF_CONDUCT.md) — please read it before opening anything.

## Quick decision tree

| Situation | Where it goes |
|---|---|
| Typo, broken link, or technical error in a post | Issue → `🐛 Post correction` template |
| Topic suggestion or post idea | Issue → `💡 Post suggestion` template |
| General question about a post (or about mobile security) | Discussion → Q&A |
| Brainstorming, feature ideas, "what if X" | Discussion → Ideas |
| Sharing a writeup, tool, or finding from authorized testing | Discussion → Show and tell |
| Vulnerability in the **h4ckmobile site itself** | Email → `contact@h4ckmobile.com` (do **not** open a public issue) |
| Vulnerability in third-party software discussed on the blog | Vendor first (responsible disclosure) — see [Code of Conduct § Security & Ethics](./CODE_OF_CONDUCT.md#security--ethics) |

## Reporting a typo or technical error

The path is exclusively via **issue** — no PRs needed for blog corrections.

1. Open a new issue and pick the **🐛 Post correction** template.
2. Include:
   - **URL of the post** (PT or EN version)
   - **Exact passage affected** (quote it directly so it's still findable if the post changes later)
   - **Suggested correction** (optional but very welcome)

That's it. The maintainer pushes the fix to the blog repo and closes the issue with a link to the commit.

## Suggesting a post topic

Open an issue with `[suggestion]` in the title (or use the `💡 Post suggestion` template). Minimum criteria so a suggestion is actionable:

- **Specific topic** — not "talk about Frida in general," but for example: "how to bypass SSL pinning on apps using a custom OkHttp factory with Frida."
- **Platform** — Android, iOS, or cross-platform.
- **Expected level** — beginner, intermediate, or advanced.
- **Why it would help the community** — one sentence is enough.

Suggestions that don't meet these criteria will be redirected back with a request for detail rather than closed silently.

## Issues vs. Discussions

Rule of thumb:

- **Question** ("how does X work?", "which tool should I use?", "anyone else seeing Y?") → **Discussion** (Q&A or General).
- **Concrete action needed** ("typo on post Y", "broken link", "site bug", "topic suggestion") → **Issue**.
- **In doubt?** → Discussion. It's easy to convert a Discussion to an Issue later; the reverse is awkward.

## Linking to a specific passage

When citing a post — in an issue, discussion, or anywhere — use this format: **URL with `#section` anchor + the quoted passage in a blockquote**.

Example:

> "Use frida-server version 16.0..."
>
> — https://h4ckmobile.com/en/studies/ssl-pinning-bypass#frida-setup

Why both:

- The `#section` anchor jumps the reader straight to the relevant header (every post on the blog has anchors on its `##` headings).
- The quoted text preserves the exact wording even if the post is later edited.

This removes ambiguity and makes the discussion thread useful even years later.

## Reporting a security vulnerability

If you find a vulnerability in the **h4ckmobile site itself** (not in third-party software the blog writes about):

- **Do not open a public issue.**
- Email **`contact@h4ckmobile.com`** with:
  - Affected URL
  - Steps to reproduce
  - Perceived severity (low / medium / high / critical)
  - Your handle / contact (optional, but useful for follow-up)
- Expect a first reply within **72h**. Coordinated disclosure timeline follows the principles in [Code of Conduct § Security & Ethics](./CODE_OF_CONDUCT.md#security--ethics).

For vulnerabilities in **third-party software** discussed on the blog, do **not** use this channel. Report directly to the vendor (responsible disclosure) per Security & Ethics clause 1 of the Code of Conduct.

## Code of Conduct

All interaction in this repository — issues, discussions, PRs, comments — is governed by the [Code of Conduct](./CODE_OF_CONDUCT.md), including the **Security & Ethics** addendum specific to this community. Read it once before contributing.

---

# 🇧🇷 Contribuindo para h4ckmobile/community

Obrigado por dedicar tempo a contribuir. Este repositório existe para que leitores do [h4ckmobile.com](https://h4ckmobile.com) reportem erros, sugiram temas e tirem dúvidas sobre o blog. Tudo aqui é regido pelo [Código de Conduta](./CODE_OF_CONDUCT.md) — leia antes de abrir qualquer coisa.

## Árvore de decisão rápida

| Situação | Para onde vai |
|---|---|
| Erro de digitação, link quebrado ou erro técnico num post | Issue → template `🐛 Post correction` |
| Sugestão de tema ou ideia de post | Issue → template `💡 Post suggestion` |
| Pergunta geral sobre um post (ou sobre mobile security) | Discussion → Q&A |
| Brainstorm, ideias de funcionalidade, "e se X" | Discussion → Ideas |
| Compartilhar writeup, ferramenta ou descoberta de teste autorizado | Discussion → Show and tell |
| Vulnerabilidade no **próprio site h4ckmobile** | Email → `contact@h4ckmobile.com` (**não** abrir issue pública) |
| Vulnerabilidade em software de terceiros discutido no blog | Vendor primeiro (disclosure responsável) — ver [Código de Conduta § Segurança & Ética](./CODE_OF_CONDUCT.md#segurança--ética) |

## Reportando um erro de digitação ou técnico

O caminho é exclusivamente via **issue** — não há fluxo de PR para correções do blog.

1. Abra uma nova issue e escolha o template **🐛 Post correction**.
2. Inclua:
   - **URL do post** (versão PT ou EN)
   - **Trecho exato afetado** (cite literalmente — assim permanece localizável mesmo se o post for editado depois)
   - **Correção sugerida** (opcional, mas muito bem-vinda)

Só isso. A manutenção empurra o fix no repositório do blog e fecha a issue com link pro commit.

## Sugerindo um tema de post

Abra uma issue com `[suggestion]` no título (ou use o template `💡 Post suggestion`). Critérios mínimos para que a sugestão seja acionável:

- **Tópico específico** — não "fala sobre Frida em geral", e sim, por exemplo: "como fazer bypass de SSL pinning em apps com OkHttp customizado usando Frida".
- **Plataforma** — Android, iOS ou cross-platform.
- **Nível esperado** — iniciante, intermediário ou avançado.
- **Por que isso ajudaria a comunidade** — uma frase basta.

Sugestões que não atendam a esses critérios são respondidas pedindo mais detalhe — não fechadas silenciosamente.

## Issues vs. Discussions

Regra de bolso:

- **Pergunta** ("como funciona X?", "qual ferramenta usar?", "alguém mais viu Y?") → **Discussion** (Q&A ou General).
- **Ação concreta necessária** ("typo no post Y", "link quebrado", "bug do site", "sugestão de tema") → **Issue**.
- **Em dúvida?** → Discussion. Converter Discussion em Issue depois é fácil; o contrário é desconfortável.

## Linkando um trecho específico

Quando for citar um post — em issue, discussion ou onde for — use este formato: **URL com âncora `#section` + o trecho em blockquote**.

Exemplo:

> "Use frida-server version 16.0..."
>
> — https://h4ckmobile.com/pt/studies/ssl-pinning-bypass#configuracao-frida

Por que os dois:

- A âncora `#section` leva direto pro header relevante (todos os posts do blog têm âncoras nos cabeçalhos `##`).
- O trecho citado preserva a redação exata mesmo se o post for editado depois.

Isso elimina ambiguidade e mantém a thread útil mesmo daqui a anos.

## Reportando uma vulnerabilidade de segurança

Se você encontrar uma vulnerabilidade no **próprio site h4ckmobile** (não em software de terceiros sobre os quais o blog escreve):

- **Não abra uma issue pública.**
- Envie email para **`contact@h4ckmobile.com`** com:
  - URL afetada
  - Passos para reproduzir
  - Severidade percebida (baixa / média / alta / crítica)
  - Seu handle / contato (opcional, mas útil para follow-up)
- Espere primeira resposta em até **72h**. O cronograma de disclosure coordenado segue os princípios do [Código de Conduta § Segurança & Ética](./CODE_OF_CONDUCT.md#segurança--ética).

Para vulnerabilidades em **software de terceiros** discutido no blog, **não** use este canal. Reporte diretamente ao vendor (disclosure responsável) conforme cláusula 1 de Segurança & Ética do Código de Conduta.

## Código de Conduta

Toda interação neste repositório — issues, discussions, PRs, comentários — é regida pelo [Código de Conduta](./CODE_OF_CONDUCT.md), incluindo o addendum **Segurança & Ética** específico desta comunidade. Leia uma vez antes de contribuir.
