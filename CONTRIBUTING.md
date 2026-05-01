# Como Contribuir

Obrigado pelo interesse em contribuir com o banco de skills! Toda contribuição é bem-vinda.

## O que você pode contribuir

- **Novo skill** — um prompt novo que ainda não existe no banco
- **Melhoria de skill existente** — ajuste de prompt, exemplo melhor, correção de texto
- **Correção de bug** — erro de formatação, frontmatter inválido, link quebrado

## Antes de começar

Verifique se já não existe um skill parecido no banco. Consulte o [README](README.md) para ver a lista completa organizada por categoria.

## Criando um novo skill

### 1. Estrutura obrigatória

Crie o diretório e arquivo seguindo o padrão:

```
.claude/nome-do-skill/SKILL.md
```

O nome do diretório deve ser em **kebab-case, sem acentos, sem números**.

### 2. Formato do SKILL.md

```markdown
---
name: nome-em-kebab-case
description: O que este skill faz em 1-2 frases objetivas.
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
[exemplo de entrada realista]

### Output esperado
[exemplo de saída realista]

---
**Tags:** Nível | Tipo | Categoria | Flowgrammers
```

### 3. Tags válidas

| Campo    | Valores aceitos                                          |
|----------|----------------------------------------------------------|
| Nível    | `Básico` \| `Intermediário` \| `Avançado`                |
| Tipo     | `Geração` \| `Auditoria` \| `Diagnóstico` \| `Adaptação` |
| Categoria | `Conteúdo & Copy` \| `Marketing, Vendas & Publicidade`  |

A tag `Flowgrammers` é obrigatória em todos os skills.

### 4. Atualize o README.md

Adicione seu skill na categoria correta do `README.md` seguindo o formato existente.

## Enviando sua contribuição

1. Faça um fork do repositório
2. Crie um branch descritivo: `git checkout -b skill/nome-do-skill`
3. Adicione seu skill e atualize o README
4. Abra um Pull Request com título claro: `feat: skill de [descrição breve]`

## Padrões de qualidade

- O prompt deve ser **testado** — use no Claude antes de enviar
- O exemplo de output deve ser **realista**, não genérico
- Campos que o usuário preenche ficam sempre entre `[colchetes]`
- Sem acentos no nome do diretório e no campo `name` do frontmatter
- O `name` no frontmatter deve ser **idêntico** ao nome do diretório

## Dúvidas

Abra uma [issue](https://github.com/ricardonevesbraga/marketing-copy-conteudo/issues) descrevendo sua dúvida ou sugestão.
