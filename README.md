<h1 align="center">Guilherme Fernandes</h1>

<p align="center">
  <strong>Analista de Sistemas Pleno · Back-end & Arquitetura de Dados · São Paulo, BR</strong><br>
  Construo sistemas internos, APIs e pipelines de dados que empresas usam de verdade — todo dia, em produção.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/guilherme-fernandes-564059215">LinkedIn</a> ·
  <a href="mailto:SEU@EMAIL.COM">E-mail</a> ·
  <em>Disponível para projetos freelance via GFA Systems</em>
</p>

---

## Sobre

Sou o time de TI inteiro de uma importadora com ~30 pessoas — da infraestrutura ao sistema que o comercial abre às 8h da manhã. Isso ensina uma coisa que curso nenhum ensina: quando o código quebra, o bug tem nome, sobrenome e ramal.

Trabalho principalmente com **back-end e dados**. Entendo o domínio antes de escrever a primeira linha, porque a maior parte dos bugs caros não é de código — é de regra de negócio mal interpretada. Front-end é meio; regra de negócio mora no servidor.

Em paralelo, curso Ciência da Computação na UNIP e desenvolvo produtos sob contrato através da **GFA Systems** (CNPJ próprio).

---

## Stack

| | |
|---|---|
| **Back-end** | Node.js · TypeScript · Fastify · Hono · Python · PHP |
| **Dados** | PostgreSQL / Supabase · MySQL · Prisma · modelagem e tuning de query |
| **Front** | Next.js · React · React Native / Capacitor |
| **Infra** | Docker · GitHub Actions · Vercel · Git |
| **Integrações** | Stripe · Mercado Pago · PIX · APIs de ERP · LLMs (Groq, OpenRouter) |

---

## Projetos

### Painel Web — Plataforma de Gestão e BI
Painel web proprietário de gestão operacional e BI interno, construído sozinho para substituir um fluxo de Power BI + Excel. Desenvolvido e mantido sob contrato de prestação de serviço, com titularidade de propriedade intelectual reconhecida em contrato.

`Node.js` `PostgreSQL` `React` `GitHub Actions`

- Pipeline de BI automatizado via GitHub Actions: processo manual de **~150 min → 3 min**
- Módulo de auditoria automatizada de estoque com verificação de integridade por **hash SHA-256**
- Arquitetura em camadas raw/core (ERP → data lake → BI)
- Usado diariamente pela operação comercial e de estoque

---

### New Database — Pipeline ETL
Pipeline de ETL que extrai dados do ERP, normaliza e centraliza em base única, servindo como camada de consumo para outros sistemas e APIs.

`Python` `Supabase / PostgreSQL`

- Separação explícita entre camada bruta e camada tratada
- Foco em consistência, integridade referencial e reuso das informações
- Base projetada para ser consumida por múltiplos sistemas sem duplicar regra

---

### PreciZou — SaaS de precificação
Plataforma SaaS multi-tenant de precificação e custeio para produtores artesanais de alimentos. Produto próprio, do zero ao billing.

`TypeScript` `Hono` `Next.js` `Prisma` `Supabase` `Stripe` `Mercado Pago`

- Multi-tenant com isolamento de dados por cliente
- Autenticação JWT com **rotação de refresh token**
- **Snapshots imutáveis de custo** — o preço histórico nunca muda quando o insumo muda
- Billing integrado com Stripe e Mercado Pago

> Aprendizado honesto: construí antes de validar o mercado. Produto tecnicamente sólido, tração baixa. Foi a lição mais cara e mais útil que tive.

---

### Prospec — Geração de leads com LLM
Ferramenta de prospecção white-label para agência de marketing imobiliário. Coleta, enriquece e gera briefings automáticos de leads.

`Next.js` `TypeScript` `Apify (Google Maps Scraper)` `Groq / LLaMA`

- Scraping estruturado com normalização e deduplicação de resultados
- Geração de briefing comercial por LLM, com camada de fallback entre provedores
- Em desenvolvimento ativo

---

### Conciliação Bancária — SaaS multi-cliente
Produto SaaS que concilia extrato bancário contra o sistema do cliente, com cada cliente operando em um banco diferente.

`Node.js` `TypeScript` `OFX`

- Parser de OFX com camada de adaptação por instituição bancária
- Arquitetura multi-cliente desde o primeiro commit
- Decisão de arquitetura documentada: Open Finance via agregador descartado por custo fixo mensal inviável no estágio atual

---

### Plataforma de Eventos e Inscrições
Sistema de inscrição e pagamento para múltiplos eventos, em produção.

`PHP` `MySQL` `React` `WooCommerce` `PIX`

- Back-end PHP com MySQL, front React entregue como build estático
- Integração de gateway de pagamento PIX/QR Code
- Manutenção e evolução contínuas em ambiente real de produção

---

### Fenagra — Kiosk game offline-first
Aplicação de captura de leads em formato de jogo, rodando offline em telas Android de 50" durante feira de negócios.

`React` `Capacitor` `Android`

- Arquitetura **offline-first**: zero dependência de rede durante o evento
- Persistência local com sincronização posterior dos leads capturados

---

## Também faço (e conta)

- Infraestrutura Microsoft 365 / Intune: Entra ID, Autopilot, Defender for Business, Conditional Access + MFA
- Especificação funcional de ERP e documentação técnica de decisão
- Auditoria técnica e financeira de contratos de fornecedores de TI
- Automação de processos que hoje rodam no braço em planilha

---

## Atividade

<div align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=Guife77&show_icons=true&count_private=true&include_all_commits=true&theme=tokyonight&hide_border=true&bg_color=0D1117" />
  <img height="165em" src="https://github-readme-streak-stats.herokuapp.com/?user=Guife77&theme=tokyonight&hide_border=true&background=0D1117" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Guife77&theme=tokyo-night&hide_border=true&bg_color=0D1117&area=true" width="98%" />
</div>

<div align="center">
  <img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Guife77&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117" />
</div>

---

## Contato

Curto trocar ideia sobre back-end, arquitetura de dados, performance e como evitar código que vira problema daqui a dois anos.

- **LinkedIn:** [guilherme-fernandes](https://www.linkedin.com/in/guilherme-fernandes-564059215)
- **E-mail:** guilhermefernandes995@gmail.com
- **Freelance / PJ:** GFA Systems — desenvolvimento sob contrato

<!--
PENDÊNCIAS SUAS (não dá pra eu resolver):

1. E-mail — aparece em 2 lugares. Troque pelo que você realmente lê.
2. Confirme se pode citar publicamente: Painel Web, New Database e a plataforma
   de eventos são ligados a cliente/empregador. Você tem o termo de titularidade
   do Painel, então nesse está coberto. Nos outros, confira antes.
3. Fixe 6 repos no perfil (Customize your pins). README vende, pinned repo prova.
4. Se algum projeto não puder ser aberto, escreva "código proprietário" no lugar
   do link — projeto sem link e sem explicação parece projeto que não existe.
-->
