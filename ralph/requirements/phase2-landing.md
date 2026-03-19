# Phase 2 - Landing Page de Alta Conversão

## Objetivo
Criar landing page profissional para vender o produto Claude Code Agency Skills.

## Stack
- **Framework:** Next.js 14 (App Router)
- **Styling:** Tailwind CSS
- **Deploy:** Cloudflare Pages
- **Analytics:** Plausible (lightweight)
- **Formulários:** Supabase (captura de leads)

## Estrutura da Landing Page

### 1. Hero Section
**Headline:** "Entregue Projetos 10x Mais Rápido com Claude Code"
**Subheadline:** "Skills e templates prontos para agências de IA usarem Claude Code como copiloto técnico"
**CTA:** "Quero Acelerar Minha Agência" → Scroll para pricing
**Visual:** Interface do Claude Code + before/after

### 2. Problem Section
**Título:** "Sua Agência Está Presa em Tarefas Manuais?"
**Dores:**
- Demora semanas para entregar projetos
- Contratar devs custa caro
- Qualidade varia entre projetos
- Não consegue escalar

### 3. Solution Section
**Título:** "Claude Code como Seu Copiloto Técnico"
**Benefícios:**
- Entregue em dias, não semanas
- Padronize qualidade
- Escalone sem contratar
- Foque em estratégia, não código

### 4. What's Included
**Título:** "O Que Você Recebe"

**7 Skills Práticas:**
1. Next.js SaaS Starter
2. Landing Page Converter
3. Automation Workflow
4. Database Schema Designer
5. API Integration Master
6. AI Agent Builder (bônus)
7. Testing & QA (bônus)

**Templates de Projetos:**
- SaaS completo com auth
- Landing page otimizada
- Automação n8n/Make
- Integração de API

**Bônus:**
- Prompts otimizados
- Playbook de execução
- Acesso às atualizações

### 5. Social Proof (Placeholder)
**Título:** "Agências Já Estão Usando"
- Testimonial 1 (placeholder)
- Testimonial 2 (placeholder)
- Testimonial 3 (placeholder)

### 6. Pricing Section
**Título:** "Invista na Eficiência da Sua Agência"

**Preço de Lançamento:**
- ~~€79~~ **€39** (50% off)
- Acesso vitalício
- Atualizações gratuitas
- 7 skills + templates
- Bônus inclusos

**Garantia:** 7 dias de garantia

**CTA:** "Começar Agora - €39"

### 7. FAQ
- O que são "skills"?
- Preciso saber programar?
- Funciona com qualquer projeto?
- E as atualizações?
- Como acesso o conteúdo?

### 8. Final CTA
**Título:** "Pronto para Acelerar Sua Agência?"
**Sub:** "Junte-se a agências que entregam 10x mais rápido"
**CTA:** "Quero Acesso Imediato - €39"

### 9. Footer
- Links sociais
- Copyright
- Termos/Privacidade

## Design Decisions

### Cores (sugestão):
- **Primary:** Indigo/Blue (confiança, tecnologia)
- **Secondary:** Purple (inovação, IA)
- **Background:** White/Light gray
- **Text:** Dark gray/Black
- **Accent:** Green (sucesso, CTA)

### Tipografia:
- **Headings:** Inter ou Geist (moderna, tech)
- **Body:** Inter (legível)

### Estilo:
- Clean e minimalista
- Plenty of whitespace
- Gradientes sutis
- Cards com sombras suaves
- Ícones do Lucide React

## Technical Requirements

### Páginas:
- `/` - Landing page principal
- `/waitlist` - Captura de emails (opcional)
- `/success` - Página de sucesso pós-compra

### Componentes:
- Navbar (sticky)
- Hero
- Section (reusable)
- FeatureCard
- PricingCard
- TestimonialCard
- FAQItem
- Footer
- Button (CTA)

### Configuração:
- SEO completo (meta tags, OG image)
- Performance otimizada (images, fonts)
- Mobile-first responsive
- Analytics tracking

## Critérios de Conclusão

- [ ] Projeto Next.js criado
- [ ] Todas as sections implementadas
- [ ] Design responsivo
- [ ] SEO configurado
- [ ] Deploy no Cloudflare
- [ ] Analytics funcionando
- [ ] Formulário de captura (Supabase)
- [ ] Checkout integrado (Stripe)

## Entregáveis

- Pasta `landing/` ou repo separado
- README com instruções de deploy
- Variáveis de ambiente documentadas

## Próxima Fase
Phase 3: Criação das Skills

---

## Status

**2026-03-19:** Landing page criada em repo separado ✅
- Repo: https://github.com/gilluan/agency-skills-landing
- Código: Completo
- Deploy: Aguardando configuração Cloudflare

## Deploy

### Cloudflare Pages Setup:
1. Acesse: https://dash.cloudflare.com
2. Pages > Create a project
3. Connect to Git: gilluan/agency-skills-landing
4. Build settings:
   - Framework preset: Next.js
   - Build command: `npm run build`
   - Build output: `dist`
5. Deploy

### Variáveis de Ambiente (se necessário):
```
NEXT_PUBLIC_PLAUSIBLE_DOMAIN=agency-skills.io
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
```
