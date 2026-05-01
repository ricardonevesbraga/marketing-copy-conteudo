# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Propósito

Banco de **153 skills** para marketing, copy e conteúdo em Português Brasileiro.
Cada skill é um arquivo `SKILL.md` executável diretamente no Claude Code via `/nome-do-skill`.

## Estrutura do Repositório

```
.claude/
├── gerador-de-headlines-com-framework-aida/
│   └── SKILL.md
├── arquiteto-de-funil-de-vendas-completo/
│   └── SKILL.md
└── ... (153 skills no total)
```

Cada subdiretório em `.claude/` corresponde a um skill invocável pelo nome:

```
/gerador-de-headlines-com-framework-aida
/copy-completa-de-landing-page-acima-da-dobra
```

## Formato Obrigatório de SKILL.md

```markdown
---
name: nome-em-kebab-case-sem-acentos
description: Descrição objetiva do que o skill faz (1-2 frases).
---

# Título Legível do Skill

Descrição resumida (igual ao description).

## Quando usar
- Caso de uso A
- Caso de uso B

## Execução

Você é um especialista em... [persona do prompt]

[prompt completo com campos entre [colchetes] para o usuário preencher]

## Exemplo

### Input
[exemplo de entrada]

### Output esperado
[exemplo de saída]

---
**Tags:** Nível | Tipo | Categoria | Flowgrammers
```

## Convenções

**Nome do diretório e `name` no frontmatter:** kebab-case, sem acentos, sem números.
O `name` deve ser idêntico ao nome do diretório.

**Tags — valores válidos:**

| Campo | Opções |
|-------|--------|
| Nível | `Básico` \| `Intermediário` \| `Avançado` |
| Tipo | `Geração` \| `Auditoria` \| `Diagnóstico` \| `Adaptação` |
| Categoria | `Conteúdo & Copy` \| `Marketing, Vendas & Publicidade` |

A tag `Flowgrammers` é obrigatória em todos os skills.

## Criando um novo skill

1. Crie `.claude/nome-descritivo/SKILL.md` seguindo o formato acima
2. O `name` no frontmatter deve ser idêntico ao nome do diretório
3. Campos que o usuário preenche ficam entre `[colchetes]` no prompt
4. Inclua sempre um exemplo realista de Input e Output esperado
5. Adicione a entrada no `README.md` na categoria correta