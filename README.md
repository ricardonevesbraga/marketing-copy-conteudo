# Banco de Skills — Marketing, Copy & Conteúdo

> **153 prompts prontos** para marketing, copy e conteúdo em Português Brasileiro, prontos para uso no **Claude Code** e no **Claude** (web/app).

---

## Como instalar

### No Claude Code

Clone o repositório e copie os skills para o diretório `.claude` do seu projeto:

```bash
git clone https://github.com/flowgrammers/marketing-copy-conteudo
cp -r marketing-copy-conteudo/.claude/* .claude/
```

Pronto. Cada skill vira um comando disponível na sessão do Claude Code:

```
/gerador-de-headlines-com-framework-aida
/arquiteto-de-funil-de-vendas-completo
/copy-completa-de-landing-page-acima-da-dobra
```

---

## Como usar no Claude Code

1. Digite `/` seguido do nome do skill
2. O Claude pedirá as informações necessárias (produto, público, objetivo...)
3. Preencha os campos e receba o resultado

**Exemplo:**
```
/gerador-de-headlines-com-framework-aida

Produto: Curso de tráfego pago para e-commerce
Público-alvo: Donos de lojas que faturam R$10k–R$50k/mês
Principal dor: Gastar em ads sem retorno previsível
```

---

## Como usar no Claude (claude.ai)

### Opção 1 — Projects (recomendado)

1. Crie um **Project** no claude.ai
2. Em **Project knowledge**, adicione os arquivos `SKILL.md` dos skills que mais usa
3. Na conversa do projeto, peça ao Claude para executar o skill pelo nome:
   > *"Use o skill `gerador-de-headlines-com-framework-aida` para o meu produto X"*

### Opção 2 — Copy & paste direto

1. Abra o arquivo `.claude/nome-do-skill/SKILL.md`
2. Copie o conteúdo da seção **## Execução**
3. Cole no chat do Claude em claude.ai
4. Substitua os campos `[entre colchetes]` com suas informações

---

## Skills disponíveis

### Headlines & Hooks

_8 skills_

| Skill | Nível |
|-------|-------|
| [Conversor de Headline Fraca em Headline Forte](.claude/conversor-de-headline-fraca-em-headline-forte/SKILL.md) |  |
| [Criador de Hooks para Carrossel no Instagram](.claude/criador-de-hooks-para-carrossel-no-instagram/SKILL.md) |  |
| [Criador de Hooks para Reels e TikTok](.claude/criador-de-hooks-para-reels-e-tiktok/SKILL.md) |  |
| [Gerador de Headlines com Framework AIDA](.claude/gerador-de-headlines-com-framework-aida/SKILL.md) | Intermediário |
| [Gerador de Linhas de Assunto para Email](.claude/gerador-de-linhas-de-assunto-para-email/SKILL.md) | Intermediário |
| [Gerador de Títulos para YouTube (CTR Alto)](.claude/gerador-de-titulos-para-youtube-ctr-alto/SKILL.md) | Intermediário |
| [Headlines com Gatilhos Mentais Específicos](.claude/headlines-com-gatilhos-mentais-especificos/SKILL.md) | Intermediário |
| [Headlines de Alta Conversão para Landing Pages](.claude/headlines-de-alta-conversao-para-landing-pages/SKILL.md) | Avançado |

### Copy para Anúncios

_8 skills_

| Skill | Nível |
|-------|-------|
| [Adaptador de Copy para Múltiplas Plataformas](.claude/adaptador-de-copy-para-multiplas-plataformas/SKILL.md) | Avançado |
| [Auditor de Copy de Anúncio](.claude/auditor-de-copy-de-anuncio/SKILL.md) | Avançado |
| [Copy de Anúncio com Prova Social](.claude/copy-de-anuncio-com-prova-social/SKILL.md) |  |
| [Copy de Anúncio com Storytelling](.claude/copy-de-anuncio-com-storytelling/SKILL.md) | Intermediário |
| [Copy de Anúncio com Urgência e Escassez](.claude/copy-de-anuncio-com-urgencia-e-escassez/SKILL.md) | Intermediário |
| [Copy para Google Ads (Search)](.claude/copy-para-google-ads-search/SKILL.md) | Intermediário |
| [Copy para Remarketing (Carrinho Abandonado)](.claude/copy-para-remarketing-carrinho-abandonado/SKILL.md) | Avançado |
| [Copy para YouTube Ads (Pre-roll)](.claude/copy-para-youtube-ads-pre-roll/SKILL.md) | Avançado |

### Posts para Redes Sociais

_5 skills_

| Skill | Nível |
|-------|-------|
| [Adaptador de Post para Múltiplas Redes](.claude/adaptador-de-post-para-multiplas-redes/SKILL.md) | Intermediário |
| [Criador de Thread para Twitter/X](.claude/criador-de-thread-para-twitterx/SKILL.md) | Intermediário |
| [Gerador de Post Educativo para Instagram](.claude/gerador-de-post-educativo-para-instagram/SKILL.md) |  |
| [Post de Autoridade com Dados e Estatísticas](.claude/post-de-autoridade-com-dados-e-estatisticas/SKILL.md) | Intermediário |
| [Post de Bastidores (Behind the Scenes)](.claude/post-de-bastidores-behind-the-scenes/SKILL.md) |  |

### Scripts e Roteiros de Vídeo

_5 skills_

| Skill | Nível |
|-------|-------|
| [Roteiro de Vídeo Educativo (YouTube)](.claude/roteiro-de-video-educativo-youtube/SKILL.md) | Intermediário |
| [Roteiro de Vídeo Institucional](.claude/roteiro-de-video-institucional/SKILL.md) | Intermediário |
| [Script de Depoimento Guiado](.claude/script-de-depoimento-guiado/SKILL.md) |  |
| [Script de Stories com CTA](.claude/script-de-stories-com-cta/SKILL.md) |  |
| [Script para Vídeo de Vendas (VSL Curto)](.claude/script-para-video-de-vendas-vsl-curto/SKILL.md) | Avançado |

### Email Marketing

_5 skills_

| Skill | Nível |
|-------|-------|
| [Email de Boas-Vindas (Sequência de Onboarding)](.claude/email-de-boas-vindas-sequencia-de-onboarding/SKILL.md) | Intermediário |
| [Email de Lançamento (Pré > Abertura > Fechamento)](.claude/email-de-lancamento-pre-abertura-fechamento/SKILL.md) | Avançado |
| [Email de Recuperação de Carrinho](.claude/email-de-recuperacao-de-carrinho/SKILL.md) | Intermediário |
| [Email de Venda Direta (Oferta)](.claude/email-de-venda-direta-oferta/SKILL.md) | Intermediário |
| [Sequência de Nurturing (5 Emails)](.claude/sequencia-de-nurturing-5-emails/SKILL.md) | Avançado |

### Storytelling

_8 skills_

| Skill | Nível |
|-------|-------|
| [Construtor de História de Origem da Marca](.claude/construtor-de-historia-de-origem-da-marca/SKILL.md) | Intermediário |
| [Criador de Analogias e Metáforas para Produto](.claude/criador-de-analogias-e-metaforas-para-produto/SKILL.md) | Intermediário |
| [Criador de Caso de Sucesso (Case Study)](.claude/criador-de-caso-de-sucesso-case-study/SKILL.md) | Intermediário |
| [Framework Jornada do Herói para Vendas](.claude/framework-jornada-do-heroi-para-vendas/SKILL.md) | Avançado |
| [História de Problema-Solução para Copy](.claude/historia-de-problema-solucao-para-copy/SKILL.md) |  |
| [Narrativa de Transformação do Cliente](.claude/narrativa-de-transformacao-do-cliente/SKILL.md) | Intermediário |
| [Storytelling para Pitch de Investidor](.claude/storytelling-para-pitch-de-investidor/SKILL.md) | Avançado |
| [Storytelling para Página 'Sobre Nós'](.claude/storytelling-para-pagina-sobre-nos/SKILL.md) |  |

### Artigos de Blog

_8 skills_

| Skill | Nível |
|-------|-------|
| [Artigo Listicle (Top 10, 7 Dicas, etc.)](.claude/artigo-listicle-top-10-7-dicas-etc/SKILL.md) |  |
| [Artigo Pilar (Guia Completo 3000+ palavras)](.claude/artigo-pilar-guia-completo-3000-palavras/SKILL.md) | Avançado |
| [Artigo Tutorial Passo a Passo](.claude/artigo-tutorial-passo-a-passo/SKILL.md) |  |
| [Artigo de Blog Otimizado para SEO](.claude/artigo-de-blog-otimizado-para-seo/SKILL.md) | Intermediário |
| [Artigo de Comparação (Produto A vs Produto B)](.claude/artigo-de-comparacao-produto-a-vs-produto-b/SKILL.md) | Intermediário |
| [Artigo de Opinião / Thought Leadership](.claude/artigo-de-opiniao-thought-leadership/SKILL.md) | Avançado |
| [Gerador de Outline de Artigo com Pesquisa](.claude/gerador-de-outline-de-artigo-com-pesquisa/SKILL.md) |  |
| [Reescritor de Artigo (Melhorar Existente)](.claude/reescritor-de-artigo-melhorar-existente/SKILL.md) | Intermediário |

### Landing Pages & UX Copy

_15 skills_

| Skill | Nível |
|-------|-------|
| [Auditor de Landing Page (Análise de Conversão)](.claude/auditor-de-landing-page-analise-de-conversao/SKILL.md) | Avançado |
| [CTA (Call to Action) de Alta Conversão](.claude/cta-call-to-action-de-alta-conversao/SKILL.md) | Intermediário |
| [Copy Completa de Landing Page (Acima da Dobra)](.claude/copy-completa-de-landing-page-acima-da-dobra/SKILL.md) | Avançado |
| [Copy de Página de Captura (Lead Magnet)](.claude/copy-de-pagina-de-captura-lead-magnet/SKILL.md) | Intermediário |
| [Copy de Página de Obrigado com Upsell](.claude/copy-de-pagina-de-obrigado-com-upsell/SKILL.md) | Avançado |
| [Copy para Empty States (Telas Vazias)](.claude/copy-para-empty-states-telas-vazias/SKILL.md) | Intermediário |
| [Copy para Tela de Pricing](.claude/copy-para-tela-de-pricing/SKILL.md) | Avançado |
| [Mensagens de Confirmação e Sucesso](.claude/mensagens-de-confirmacao-e-sucesso/SKILL.md) |  |
| [Mensagens de Erro Amigáveis](.claude/mensagens-de-erro-amigaveis/SKILL.md) |  |
| [Microcopy para Botões e CTAs](.claude/microcopy-para-botoes-e-ctas/SKILL.md) |  |
| [Notificações Push Engajantes](.claude/notificacoes-push-engajantes/SKILL.md) | Intermediário |
| [Seção de Benefícios com Bullet Points](.claude/secao-de-beneficios-com-bullet-points/SKILL.md) |  |
| [Seção de FAQ Estratégica](.claude/secao-de-faq-estrategica/SKILL.md) |  |
| [Seção de Prova Social e Depoimentos](.claude/secao-de-prova-social-e-depoimentos/SKILL.md) | Intermediário |
| [Tooltips e Textos de Ajuda](.claude/tooltips-e-textos-de-ajuda/SKILL.md) |  |

### Funil & Estratégia de Vendas

_8 skills_

| Skill | Nível |
|-------|-------|
| [Arquiteto de Funil de Vendas Completo](.claude/arquiteto-de-funil-de-vendas-completo/SKILL.md) | Avançado |
| [Criador de Brand Voice (Tom de Voz)](.claude/criador-de-brand-voice-tom-de-voz/SKILL.md) | Intermediário |
| [Criador de Lead Magnet (Isca Digital)](.claude/criador-de-lead-magnet-isca-digital/SKILL.md) | Intermediário |
| [Diagnóstico de Funil (Identificar Gargalos)](.claude/diagnostico-de-funil-identificar-gargalos/SKILL.md) | Avançado |
| [Estratégia de Tripwire (Oferta de Entrada)](.claude/estrategia-de-tripwire-oferta-de-entrada/SKILL.md) | Avançado |
| [Mapeamento de Jornada do Cliente](.claude/mapeamento-de-jornada-do-cliente/SKILL.md) | Intermediário |
| [Proposta Comercial Completa (B2B)](.claude/proposta-comercial-completa-b2b/SKILL.md) | Avançado |
| [Script de Venda por WhatsApp](.claude/script-de-venda-por-whatsapp/SKILL.md) | Intermediário |

### E-commerce

_16 skills_

| Skill | Nível |
|-------|-------|
| [Análise de Concorrente e Posicionamento (E-commerce)](.claude/analise-de-concorrente-e-posicionamento-e-commerce/SKILL.md) | Avançado |
| [Calendário de Conteúdo para E-commerce (30 dias)](.claude/calendario-de-conteudo-para-e-commerce-30-dias/SKILL.md) |  |
| [Copy para Anúncio de Produto (Meta Ads)](.claude/copy-para-anuncio-de-produto-meta-ads/SKILL.md) | Intermediário |
| [Copy para Posts de Venda no Instagram (Feed)](.claude/copy-para-posts-de-venda-no-instagram-feed/SKILL.md) |  |
| [Copy para Remarketing (Meta Ads)](.claude/copy-para-remarketing-meta-ads/SKILL.md) | Avançado |
| [Copy para Stories de Vendas (Instagram)](.claude/copy-para-stories-de-vendas-instagram/SKILL.md) |  |
| [Copy para WhatsApp — Vendas e Follow-up](.claude/copy-para-whatsapp-vendas-e-follow-up/SKILL.md) |  |
| [Criação de Kits e Bundles de Produtos](.claude/criacao-de-kits-e-bundles-de-produtos/SKILL.md) | Intermediário |
| [Criação de Oferta Irresistível para E-commerce](.claude/criacao-de-oferta-irresistivel-para-e-commerce/SKILL.md) | Intermediário |
| [Descrição de Produto Persuasiva para E-commerce](.claude/descricao-de-produto-persuasiva-para-e-commerce/SKILL.md) |  |
| [Estratégia de Recompra e Fidelização de Clientes (E-commerce)](.claude/estrategia-de-recompra-e-fidelizacao-de-clientes-e-commerce/SKILL.md) | Intermediário |
| [Planejamento de Campanha de Produto (E-commerce)](.claude/planejamento-de-campanha-de-produto-e-commerce/SKILL.md) | Intermediário |
| [Reels e TikTok de Produto — Roteiro Rápido (10 ideias)](.claude/reels-e-tiktok-de-produto-roteiro-rapido-10-ideias/SKILL.md) |  |
| [Script de Vídeo para Produto (Reels / TikTok / Anúncio)](.claude/script-de-video-para-produto-reels-tiktok-anuncio/SKILL.md) |  |
| [Sequência de Emails para E-commerce](.claude/sequencia-de-emails-para-e-commerce/SKILL.md) | Intermediário |
| [Sequência de Recuperação de Carrinho Abandonado](.claude/sequencia-de-recuperacao-de-carrinho-abandonado/SKILL.md) | Intermediário |

### Consultoria & Serviços

_21 skills_

| Skill | Nível |
|-------|-------|
| [Copy com Voz Própria — Textos que Não Parecem IA](.claude/copy-com-voz-propria-textos-que-nao-parecem-ia/SKILL.md) | Avançado |
| [Copy de Autoridade para Especialista](.claude/copy-de-autoridade-para-especialista/SKILL.md) | Avançado |
| [Copy de Email de Vendas para Serviços de Consultoria](.claude/copy-de-email-de-vendas-para-servicos-de-consultoria/SKILL.md) | Avançado |
| [Copy de Lançamento de Serviço ou Programa](.claude/copy-de-lancamento-de-servico-ou-programa/SKILL.md) | Avançado |
| [Copy para DM — Abordagem Consultiva (Instagram e LinkedIn)](.claude/copy-para-dm-abordagem-consultiva-instagram-e-linkedin/SKILL.md) | Intermediário |
| [Copy para LinkedIn — Posicionamento e Geração de Leads](.claude/copy-para-linkedin-posicionamento-e-geracao-de-leads/SKILL.md) | Avançado |
| [Criação de Solução para Cliente (Serviços)](.claude/criacao-de-solucao-para-cliente-servicos/SKILL.md) | Intermediário |
| [Estratégia de Conteúdo Multicanal para Consultora](.claude/estrategia-de-conteudo-multicanal-para-consultora/SKILL.md) | Avançado |
| [Estrutura de Funil Simples para Serviços](.claude/estrutura-de-funil-simples-para-servicos/SKILL.md) |  |
| [Framework de Gestão de Objeções em Vendas de Serviço](.claude/framework-de-gestao-de-objecoes-em-vendas-de-servico/SKILL.md) | Avançado |
| [Framework de Posicionamento como Especialista](.claude/framework-de-posicionamento-como-especialista/SKILL.md) | Avançado |
| [Framework de Storytelling que Vende](.claude/framework-de-storytelling-que-vende/SKILL.md) | Avançado |
| [Framework de Upsell e Expansão de Clientes](.claude/framework-de-upsell-e-expansao-de-clientes/SKILL.md) | Avançado |
| [Gestão de Objeções em Vendas](.claude/gestao-de-objecoes-em-vendas/SKILL.md) |  |
| [Ideias de Conteúdo com Foco em Vendas](.claude/ideias-de-conteudo-com-foco-em-vendas/SKILL.md) |  |
| [Planejamento de Conteúdo Prático](.claude/planejamento-de-conteudo-pratico/SKILL.md) |  |
| [Posicionamento e Proposta de Valor Clara](.claude/posicionamento-e-proposta-de-valor-clara/SKILL.md) |  |
| [Proposta Comercial Profissional para Serviços](.claude/proposta-comercial-profissional-para-servicos/SKILL.md) |  |
| [Proposta Comercial de Alto Valor (Consultoria)](.claude/proposta-comercial-de-alto-valor-consultoria/SKILL.md) | Avançado |
| [Roteiro de Vendas para Conversas e DMs](.claude/roteiro-de-vendas-para-conversas-e-dms/SKILL.md) |  |
| [Script de Discovery Call Consultiva](.claude/script-de-discovery-call-consultiva/SKILL.md) | Avançado |

### Nichos Específicos

_46 skills_

| Skill | Nível |
|-------|-------|
| [Apresentação Executiva — Estrutura e Narrativa](.claude/apresentacao-executiva-estrutura-e-narrativa/SKILL.md) | Intermediário |
| [Bio e Posicionamento Profissional do Gestor](.claude/bio-e-posicionamento-profissional-do-gestor/SKILL.md) |  |
| [Bio e Posicionamento do Consultor Financeiro](.claude/bio-e-posicionamento-do-consultor-financeiro/SKILL.md) |  |
| [Bio e Posicionamento do Designer de Branding](.claude/bio-e-posicionamento-do-designer-de-branding/SKILL.md) |  |
| [Calendário Editorial Mensal para Designer de Branding](.claude/calendario-editorial-mensal-para-designer-de-branding/SKILL.md) |  |
| [Campanha de Marketing para Serviços B2B](.claude/campanha-de-marketing-para-servicos-b2b/SKILL.md) | Intermediário |
| [Conteúdo de Autoridade para Consultor Financeiro no LinkedIn](.claude/conteudo-de-autoridade-para-consultor-financeiro-no-linkedin/SKILL.md) | Intermediário |
| [Conteúdo de Autoridade para Designer no Instagram e LinkedIn](.claude/conteudo-de-autoridade-para-designer-no-instagram-e-linkedin/SKILL.md) |  |
| [Conteúdo de Autoridade para LinkedIn de Gestor](.claude/conteudo-de-autoridade-para-linkedin-de-gestor/SKILL.md) |  |
| [Copy de Captação para Designer de Branding](.claude/copy-de-captacao-para-designer-de-branding/SKILL.md) | Intermediário |
| [Copy de Captação para Serviços Jurídicos e de Gestão](.claude/copy-de-captacao-para-servicos-juridicos-e-de-gestao/SKILL.md) | Intermediário |
| [Copy para Facebook/Instagram Ads (Feed)](.claude/copy-para-facebookinstagram-ads-feed/SKILL.md) | Intermediário |
| [Copy para Onboarding de App/SaaS](.claude/copy-para-onboarding-de-appsaas/SKILL.md) | Intermediário |
| [E-mail e Comunicação Profissional de Alto Impacto](.claude/e-mail-e-comunicacao-profissional-de-alto-impacto/SKILL.md) |  |
| [Estrutura de Campanha Facebook/Instagram Ads](.claude/estrutura-de-campanha-facebookinstagram-ads/SKILL.md) | Avançado |
| [Follow-up Estratégico para Fechar Projetos em Negociação](.claude/follow-up-estrategico-para-fechar-projetos-em-negociacao/SKILL.md) |  |
| [Gerador de Enquete/Pergunta para Engajamento](.claude/gerador-de-enquetepergunta-para-engajamento/SKILL.md) |  |
| [Mapa de Objeções do Produto/Serviço](.claude/mapa-de-objecoes-do-produtoservico/SKILL.md) | Intermediário |
| [Playbook de Oferta de Investimento](.claude/playbook-de-oferta-de-investimento/SKILL.md) | Intermediário |
| [Post de Lançamento de Produto/Serviço](.claude/post-de-lancamento-de-produtoservico/SKILL.md) | Intermediário |
| [Primeiros Passos no Marketing Digital](.claude/primeiros-passos-no-marketing-digital/SKILL.md) | Intermediário |
| [Proposta Comercial de Alto Impacto](.claude/proposta-comercial-de-alto-impacto/SKILL.md) |  |
| [Roteiro de Webinar/Live de Vendas](.claude/roteiro-de-webinarlive-de-vendas/SKILL.md) | Avançado |
| [Rotina de Vendas Diária Simples](.claude/rotina-de-vendas-diaria-simples/SKILL.md) | Intermediário |
| [Script de Unboxing/Review de Produto](.claude/script-de-unboxingreview-de-produto/SKILL.md) |  |
| [Script para Reels/TikTok (até 60s)](.claude/script-para-reelstiktok-ate-60s/SKILL.md) |  |
| [Sistema de Apresentação para Investidores](.claude/sistema-de-apresentacao-para-investidores/SKILL.md) | Intermediário |
| [Sistema de Artigos de Autoridade](.claude/sistema-de-artigos-de-autoridade/SKILL.md) | Intermediário |
| [Sistema de Autoridade e Posicionamento](.claude/sistema-de-autoridade-e-posicionamento/SKILL.md) | Intermediário |
| [Sistema de Ações de Venda Simples](.claude/sistema-de-acoes-de-venda-simples/SKILL.md) | Intermediário |
| [Sistema de Criativos para Anúncios](.claude/sistema-de-criativos-para-anuncios/SKILL.md) | Intermediário |
| [Sistema de Email e WhatsApp para Vendas](.claude/sistema-de-email-e-whatsapp-para-vendas/SKILL.md) | Intermediário |
| [Sistema de Escala do Negócio com Previsibilidade](.claude/sistema-de-escala-do-negocio-com-previsibilidade/SKILL.md) | Intermediário |
| [Sistema de Experiência do Cliente Premium](.claude/sistema-de-experiencia-do-cliente-premium/SKILL.md) | Intermediário |
| [Sistema de Follow-up e Fechamento de Clientes](.claude/sistema-de-follow-up-e-fechamento-de-clientes/SKILL.md) | Intermediário |
| [Sistema de Funil de Conteúdo e Captação](.claude/sistema-de-funil-de-conteudo-e-captacao/SKILL.md) | Intermediário |
| [Sistema de Modelos Reutilizáveis de Copy](.claude/sistema-de-modelos-reutilizaveis-de-copy/SKILL.md) | Intermediário |
| [Sistema de Ofertas Irresistíveis](.claude/sistema-de-ofertas-irresistiveis/SKILL.md) | Intermediário |
| [Sistema de Parcerias e Influenciadores](.claude/sistema-de-parcerias-e-influenciadores/SKILL.md) | Intermediário |
| [Sistema de Precificação Premium](.claude/sistema-de-precificacao-premium/SKILL.md) | Intermediário |
| [Sistema de Primeiras Vendas com IA](.claude/sistema-de-primeiras-vendas-com-ia/SKILL.md) | Intermediário |
| [Sistema de Prova Social e Autoridade](.claude/sistema-de-prova-social-e-autoridade/SKILL.md) | Intermediário |
| [Sistema de Relatórios para Clientes](.claude/sistema-de-relatorios-para-clientes/SKILL.md) | Intermediário |
| [Sistema de Upsell e Cross-sell](.claude/sistema-de-upsell-e-cross-sell/SKILL.md) | Intermediário |
| [Teste A/B de Headlines (Gerador de Variações)](.claude/teste-ab-de-headlines-gerador-de-variacoes/SKILL.md) | Avançado |
| [Texto de Descrição de Branding para o Cliente Usar nas Redes](.claude/texto-de-descricao-de-branding-para-o-cliente-usar-nas-redes/SKILL.md) | Intermediário |

---

**Total: 153 skills** · **Flowgrammers**

## Contribuindo

Veja `CLAUDE.md` para o formato obrigatório antes de criar ou editar um skill.