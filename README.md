# ✝️ Doulos — Sistema de Gestão Social

**Versão atual: 2.0**

> *"O que fizestes a um destes meus pequeninos irmãos, a mim o fizestes."*
> — Mateus 25:40

O Doulos é um sistema **100% gratuito e completo** de gestão social para igrejas, projetos sociais, ONGs, associações comunitárias e qualquer entidade sem fins lucrativos.

---

## 💚 Gratuito para sempre — Licença Filantrópica Livre

O Doulos é distribuído gratuitamente e permanentemente para o terceiro setor. **Não há taxas, assinaturas, versão paga ou plano premium.** A gratuidade é princípio fundador registrado em cartório e no INPI.

> ✝ *Este princípio está registrado no código-fonte, em cartório, no INPI e nos Termos de Compromisso assinados por cada receptor.*

Uso comercial é **expressamente vedado** — qualquer cobrança viola a Lei nº 9.609/1998.

---

## 📋 Sobre o sistema

O Doulos funciona como um **arquivo único HTML** — sem instalação, sem servidor, sem internet obrigatória e sem mensalidade. Basta abrir o arquivo `Doulos_v2.0.html` no navegador para começar a usar.

Os dados ficam armazenados localmente no dispositivo, com **backup criptografado (AES-256-GCM)** em arquivo `.doulbkp` para segurança e portabilidade.

| Característica | Detalhe |
|---------------|---------|
| **Arquivo único** | HTML + CSS + JavaScript — sem dependências externas em tempo de execução |
| **Offline-first** | Funciona sem internet |
| **localStorage** | Dados ficam no dispositivo, privacidade total |
| **Backup AES-256-GCM** | Criptografia de nível bancário com derivação PBKDF2 |
| **Backup automático** | Configurável em intervalos de 10 a 60 minutos |
| **Log de auditoria** | Rastreabilidade completa de acessos e ações |

---

## 🧩 Módulos disponíveis — v2.0

| Módulo | Descrição |
|--------|-----------|
| 🏠 **Dashboard** | Painel com contadores em tempo real, próximos agendamentos e contas a vencer |
| 👧 **Atendidos** | Ficha completa com dados pessoais, situação escolar, responsável e mapeamento de 8 categorias de vulnerabilidade |
| 👨‍👩‍👧 **Responsáveis** | Cadastro de famílias e responsáveis legais com dados de contato |
| 🤝 **Vínculos** | Doadores, mantenedores, empresas parceiras e igrejas parceiras |
| 🙋 **Voluntários** | Cadastro com funções e disponibilidade semanal |
| 💛 **Doadores** | Módulo próprio para pessoas físicas, jurídicas, igrejas e doadores anônimos |
| 📌 **Mural de Avisos** | Comunicados para a equipe — Urgente, Informativo, Evento, Geral |
| 🗓️ **Agendamentos** | Agenda de atendimentos com controle de status e alertas no Dashboard |
| 📋 **Evolução do Atendido** | Prontuário individual com histórico longitudinal de acompanhamento |
| 📅 **Escalas de Serviço** | Escalas semanais e pontuais de voluntários, com impressão |
| 📚 **Atividades e Frequência** | Atividades configuráveis e controle de frequência com taxa de presença |
| 🎓 **Cursos e Turmas** | Cursos com vagas, carga horária, inscrições e chamada por sessão |
| 📦 **Estoque** | Controle de itens com alertas de estoque baixo (< 5 unidades) |
| 🎁 **Distribuição** | Entrega de itens com baixa automática no estoque |
| 💰 **Financeiro — Caixa** | Entradas e saídas com saldo em tempo real e gráfico mensal de barras |
| 📑 **Contas a Pagar/Receber** | Compromissos futuros com alertas automáticos de vencimento |
| 🧾 **Recibo de Doação** | Geração e impressão de recibos formais com pré-visualização |
| 🗒️ **Previsão de Gastos** | Planejamento de despesas com itens detalhados e total automático |
| 🚗 **Deslocamento** | Rotas de voluntários com odômetro e cálculo automático de km |
| 📊 **Relatórios** | 6 tipos: Financeiro, Estoque, Frequência, Atendidos, Deslocamento, Cursos |
| 👤 **Usuários** | Dois perfis (Coordenador e Voluntário) com senhas individuais |
| ⚙️ **Configurações** | Identificação institucional, saldo inicial, senha e backup automático |
| 🔍 **Auditoria** | Log completo de acessos e ações com usuário, data e hora |
| 💾 **Backup** | AES-256-GCM com PBKDF2 (arquivo .doulbkp) e backup automático configurável |

---

## 🚀 Como usar

1. Baixe o arquivo `Doulos_v2.0.html`
2. Abra no navegador (Google Chrome ou Microsoft Edge — recomendado)
3. Login inicial: usuário `admin` / senha `admin`
4. **Troque a senha imediatamente** nas Configurações
5. Configure a identidade da sua instituição em Configurações > Identificação

> 💡 Recomendamos uso em **PC, notebook ou tablet**. A interface foi otimizada para telas desktop.

---

## 🔐 Backup e portabilidade

Para usar em outro dispositivo ou ao trocar de computador:

1. Acesse **💾 Backup** → **Exportar Backup**
2. Defina uma senha e salve o arquivo `.doulbkp` gerado
3. No novo dispositivo, abra o Doulos → **Restaurar Backup** → selecione o arquivo → informe a senha

> ⚠️ **Guarde o arquivo de backup em local seguro** (HD externo, pendrive, Google Drive, OneDrive). Ele contém dados sensíveis criptografados com AES-256-GCM. Sem o arquivo e a senha, os dados não podem ser recuperados.

---

## 👥 Perfis de acesso

| Perfil | Acesso |
|--------|--------|
| **Coordenador** | Acesso completo a todos os módulos, incluindo Usuários, Configurações, Auditoria e Backup |
| **Voluntário** | Acesso aos módulos operacionais (Atendidos, Agendamentos, Estoque, Frequência etc.) sem acesso à administração |

---

## 📦 Como receber o sistema

O Doulos é distribuído **gratuitamente**, mas com responsabilidade social. Para receber o pacote completo:

1. O coordenador responsável assina o **Termo de Compromisso** (disponível neste repositório)
2. O termo assinado é enviado ao autor
3. O pacote completo (sistema + manual) é enviado gratuitamente

---

## 📁 Histórico de versões

| Versão | Principais adições |
|--------|---------------------|
| v1.0 | Versão inicial — módulos base: atendidos, atividades, frequência, estoque, distribuição, financeiro |
| v1.2 | Gráficos financeiros, previsão de gastos, backup AES-256-GCM |
| v1.5 | Voluntários, vínculos, relatórios ampliados |
| **v2.0** | **24 módulos, prontuário individual, cursos/turmas, mural de avisos, agendamentos, escalas, recibo de doação, contas a pagar/receber, backup automático, 6 tipos de relatório** |

---

## 👨‍💻 Autoria

**Idealizador e Desenvolvedor:** Kerson Kleber Espínola Pereira
**Cidade:** Itabuna, Bahia — Brasil
**Vínculo institucional:** UFSB — Universidade Federal do Sul da Bahia (SAI — Setor de Acessibilidade e Inclusão)

> *A concepção, arquitetura, design de interface, escolha de funcionalidades e toda a direção criativa são de autoria exclusiva de Kerson Kleber Espínola Pereira.*
> *O uso de IA (Claude / Anthropic) como ferramenta de produtividade durante o desenvolvimento não constitui coautoria.*

---

## 📜 Licença

Este software é protegido pela **Lei nº 9.609/1998** (Lei do Software) e **Lei nº 9.610/1998** (Lei de Direitos Autorais).

**Licença Filantrópica Livre:**
- ✅ Uso gratuito e irrestrito para organizações do terceiro setor
- ✅ Redistribuição permitida desde que mantidos licença e créditos originais
- ✅ Adaptações permitidas para uso social, mantidos os créditos
- ❌ Uso comercial expressamente vedado
- ❌ Comercialização ou cobrança de qualquer natureza proibida

---

*Doulos v2.0 · Desenvolvido por Kerson Kleber Espínola Pereira · Itabuna, BA · 2026*

*"O que fizestes a um destes meus pequeninos irmãos, a mim o fizestes." — Mateus 25:40*
