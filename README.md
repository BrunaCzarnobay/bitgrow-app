# 🌱 BitGrow

**Liberdade financeira em família, desde cedo**

> Uma plataforma familiar que une educação bitcoinera gamificada com uma carteira Bitcoin não-custodial segura

[![Figma](https://img.shields.io/badge/Figma-Design%20do%20Projeto-orange?style=for-the-badge&logo=figma)](https://www.figma.com/design/Wlb7taeCnmIeljf8uZUV5j/BitGrow?m=auto&t=jkYFzdzmDaxqle1Y-6)

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Bitcoin Only](https://img.shields.io/badge/Bitcoin-Only-orange.svg)](https://bitcoin.org/)
[![Lightning Network](https://img.shields.io/badge/Lightning-Network-blue.svg)](https://lightning.network/)
[![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow.svg)](https://github.com/BrunaCzarnobay/bitgrow-app)
[![Bitcoin Creative](https://img.shields.io/badge/Bitcoin-Creative-purple.svg)](https://bitcoincreative.org/)

<img width="2037" height="1526" alt="Group 48095575" src="https://github.com/user-attachments/assets/6b03a7f7-0d03-4be1-b6a4-bb3f0ccf3d41" />

## 📋 Índice
- [✨ Visão Geral](#-visão-geral)
- [🎯 Objetivo](#-objetivo)
- [👥 Público-Alvo](#-público-alvo)
- [🚀 Funcionalidades](#-funcionalidades)
- [🛠️ Tecnologias](#️-tecnologias)
- [🎨 Design System](#-design-system)
- [📁 Estrutura do Projeto](#-estrutura-do-projeto)
- [📸 Screenshots](#-screenshots)
- [🌩️ Lightning Network](#️-lightning-network)
- [📊 Fluxo de Transações](#-fluxo-de-transações)
- [📅 Roadmap](#-roadmap)
- [📄 Licença](#-licença)
- [👨‍💻 Autoria](#-autoria)
- [🤝 Como Contribuir](#-como-contribuir)
- [❓ FAQ](#-faq)

## ✨ Visão Geral
O BitGrow nasce da necessidade de educar as novas gerações sobre soberania financeira de forma prática e segura. Mais que uma carteira, é uma **jornada educacional completa** que prepara toda a família para um futuro de liberdade financeira com Bitcoin.

> 💡 *"Com Bitcoin, você protege o fruto do seu trabalho. Com BitGrow, você ensina seus filhos a fazer o mesmo."*

## 🎯 Objetivo
| Meta | Descrição | Status |
|------|-----------|---------|
| **🧠 Educação** | Ensinar conceitos de dinheiro sólido, autocustódia e economia | ✅ |
| **🛡️ Segurança** | Oferecer ferramentas seguras com controles parentais e multisig | ✅ |
| **🚀 Adoção** | Facilitar a entrada no ecossistema Bitcoin para todas as idades | 🚧 |
| **👨‍👩‍👧‍👦 Família** | Criar uma experiência compartilhada de aprendizado financeiro | ✅ |

## 👥 Público-Alvo
| Grupo | Idade | Necessidades | Status |
|-------|-------|--------------|---------|
| **🧒 Crianças** | 7-10 anos | Aprendizado gamificado, recompensas visíveis, controles parentais | ✅ |
| **🧑 Adolescentes** | 11-16 anos | Conteúdo avançado, simulações, metas de poupança | 🚧 |
| **👨‍💼 Adultos** | 17+ anos | Carteira segura, multisig, herança digital, controle familiar | ✅ |
| **👨‍👩‍👧‍👦 Famílias** | Todas idades | Dashboard unificado, relatórios, metas compartilhadas | ✅ |

## 🚀 Funcionalidades
### 🧒 Modo Kids (7-10 anos)
- ✅ **Cofrinho Digital** com visualização de sats
- ✅ **Missões Gamificadas** e quizzes educativos
- ✅ **Recompensas via Lightning** com aprovação parental
- ✅ **Interface Lúdica** e ilustrações amigáveis
- ✅ **Controles Parentais** integrados

### 🧑 Modo Teen (11-16 anos)
- ✅ **Conteúdo Avançado** sobre inflação e segurança
- 🚧 **Simulações Lightning** com limites controlados
- ✅ **Metas de Poupança** de longo prazo
- ✅ **Badges de Conquista** e progressão
- 🚧 **Aulas sobre autocustódia**

### 👨‍💼 Modo Adult (17+ anos)
- ✅ **Carteira Lightning** não-custodial
- ✅ **Vault Multisig 2-de-3** para economias
- ✅ **Ferramentas de Herança** digital
- ✅ **Controle Parental** completo
- ✅ **Relatórios de Progresso** familiar

### 👨‍👩‍👧‍👦 Family Dashboard
- ✅ **Visão Unificada** do progresso familiar
- ✅ **Controle de Limites** e aprovações
- ✅ **Relatórios** de atividade e aprendizado
- ✅ **Metas Compartilhadas** familiares
- ✅ **Configurações de Segurança**

## 🛠️ Tecnologias
### 📱 Frontend
```yaml
framework: React Native
linguagem: TypeScript
estilização: Styled Components
testes: Jest + React Testing Library


### ⚡ Bitcoin & Lightning
```yaml
rede: Bitcoin Mainnet
layer2: Lightning Network
carteira: LDK (Lightning Development Kit)
multisig: Descriptores Miniscript
backup: Seed phrases BIP39
```

### 🔐 Segurança
```yaml
autenticação: Biometria + PIN
armazenamento: Secure Enclave + Async Storage
criptografia: AES-256 + SHA-256
backup: Cloud encrypted + local
```

### 🎨 Design & UX
```yaml
prototipagem: Figma
design system: Custom BitGrow
ícones: Custom SVG
animações: Lottie + Reanimated
```

### 📦 Infraestrutura
```yaml
build: GitHub Actions
deploy: TestFlight + Play Store
monitoring: Sentry
analytics: Plausible (privacy-friendly)
```

## 🎨 Design System
### 🎯 Paleta de Cores
```css
--bitcoin-orange: #F7931A;    /* Ações primárias e ênfase */
--black: #000000;              /* Títulos e texto principal */
--dark-gray: #333333;          /* Texto secundário */
--light-gray: #F5F5F5;         /* Fundos e superfícies */
--kids-blue: #2D7FF9;          /* Identidade visual Kids */
--teen-green: #00BFA5;         /* Identidade visual Teen */
--success: #22C55E;            /* Confirmações e sucesso */
--warning: #F59E0B;            /* Alertas e avisos */
--error: #DC2626;              /* Erros e perigos */
```

### ✒️ Tipografia
```css
--font-heading: 'Inter', -apple-system, sans-serif;
--font-body: 'Roboto', -apple-system, sans-serif;
--font-mono: 'Fira Code', monospace;
--text-xs: 12px;
--text-sm: 14px;
--text-base: 16px;
--text-lg: 18px;
--text-xl: 20px;
--text-2xl: 24px;
--text-3xl: 30px;
```

### 📐 Espaçamento
```css
--space-1: 4px;
--space-2: 8px;
--space-3: 12px;
--space-4: 16px;
--space-5: 20px;
--space-6: 24px;
--space-8: 32px;
--space-10: 40px;
```

### 🧩 Componentes
| Componente | Status | Documentação |
|------------|---------|--------------|
| Botão Primário | ✅ | [Ver especificações](./design/components/button.md) |
| Botão Secundário | ✅ | [Ver especificações](./design/components/button.md) |
| Card de Missão | ✅ | [Ver especificações](./design/components/card.md) |
| Input Text | 🚧 | [Ver especificações](./design/components/input.md) |
| Modal | 🚧 | [Ver especificações](./design/components/modal.md) |
| Navigation Bar | ✅ | [Ver especificações](./design/components/navbar.md) |

## 📁 Estrutura do Projeto
```
bitgrow-app/
├── 📱 src/
│   ├── components/          # Componentes reutilizáveis
│   │   ├── ui/             # Componentes de interface
│   │   ├── bitcoin/        # Componentes Bitcoin-specific
│   │   └── family/         # Componentes familiares
│   ├── screens/            # Telas do aplicativo
│   │   ├── kids/          # Telas modo Kids
│   │   ├── teen/          # Telas modo Teen
│   │   ├── adult/         # Telas modo Adult
│   │   └── family/        # Family Dashboard
│   ├── services/          # Serviços e APIs
│   │   ├── bitcoin/       # Serviços Bitcoin
│   │   ├── lightning/     # Serviços Lightning
│   │   └── storage/       # Gerenciamento de dados
│   ├── utils/             # Utilitários e helpers
│   │   ├── bitcoin/       # Utilitários Bitcoin
│   │   ├── family/        # Utilitários familiares
│   │   └── security/      # Utilitários de segurança
│   └── types/             # Definições TypeScript
├── 📚 documentation/
│   ├── BitGrow-Projeto-Detalhado.pdf
│   ├── presentation.pdf
│   ├── architecture.md    # Arquitetura do sistema
│   └── assets/           # Imagens e diagramas
├── 🎨 design/
│   ├── figma/            # Link para protótipo Figma
│   ├── components/       # Especificações de componentes
│   ├── screenshots/      # Capturas de tela
│   └── style-guide.md    # Guia de estilo completo
├── 📦 scripts/           # Scripts de desenvolvimento
├── 📄 LICENSE.md         # Licença CC BY-SA 4.0
└── 📖 README.md          # Este arquivo
```

## 📸 Screenshots
<img width="2580" height="1580" alt="Backup - Instruções da Frase de Recuperação" src="https://github.com/user-attachments/assets/cf1cef23-71cd-4310-944a-d83aad67d740" />
<img width="2580" height="1580" alt="Backup - Exibir Frase de Recuperação" src="https://github.com/user-attachments/assets/9649b743-014d-4520-ae51-94df624525fc" />
<img width="2580" height="1580" alt="Backup - Alerta de Segurança" src="https://github.com/user-attachments/assets/3e330f8b-3ab1-4181-b55d-6fe79bf6bc31" />
<img width="2580" height="1580" alt="Backup - Confirmar Frase de Recuperação" src="https://github.com/user-attachments/assets/fb532981-fd55-4b69-93ef-5a07412417a8" />
<img width="2580" height="1580" alt="Home" src="https://github.com/user-attachments/assets/b07ca586-2cd0-47cd-8343-db79e72e7372" />
<img width="2580" height="1580" alt="Ativos" src="https://github.com/user-attachments/assets/a730a5ca-1a73-44fb-a94e-27e93badbb35" />


## 🌩️ Lightning Network
### ⚡ Integração Lightning
O BitGrow utiliza Lightning Network para micro-recompensas instantâneas, transações com taxas insignificantes e experiência prática em tempo real.

**Parcerias com LSPs**
```yaml
parceiros:
  - name: Lightning Network+
    services: [channel management, liquidity]
  - name: Bitcoin Beach
    services: [education, community]
```

**Segurança em Camadas**
- ✅ Limites de valor por transação
- ✅ Approvação parental obrigatória
- ✅ Backup automático de canais
- ✅ Monitoramento 24/7

### 📊 Dashboard Lightning
- ✅ Visualização de saldo em sats
- ✅ Histórico de transações simplificado
- ✅ Metas de poupança em tempo real
- ✅ Estatísticas de aprendizado

## 📊 Fluxo de Transações
flowchart TD
    A[Criança completa missão] --> B[Gera invoice Lightning]
    B --> C[Servidor BitGrow + LSP Parceiro]
    C --> D[Pagamento é processado]
    D --> E[Pais aprovam e definem limites]
    E --> F[Sats vão para o cofrinho]
    F --> G[Excedentes para vault multisig]
    
## 📅 Roadmap
### 🎯 Fase 1 - MVP (Concluída ✅)
- [x] Design system completo
- [x] Protótipo Figma navegável
- [x] Arquitetura técnica definida
- [x] Documentação inicial

### 🚀 Fase 2 - Desenvolvimento (Em Andamento 🚧)
- [ ] Desenvolvimento frontend (React Native)
- [ ] Integração com Lightning Network
- [ ] Implementação multisig
- [ ] Sistema de recompensas
- [ ] Testes com usuários reais
- [ ] Polimento de UI/UX

### 🌟 Fase 3 - Lançamento (Planejada 📅)
- [ ] Lançamento na App Store
- [ ] Lançamento na Play Store
- [ ] Programa de beta testers
- [ ] Campanha educacional
- [ ] Onboarding de primeiras famílias

### 🔮 Fase 4 - Futuro (Ideias 💡)
- [ ] Integração com escolas
- [ ] Programas educacionais
- [ ] Versão web
- [ ] API pública
- [ ] Suporte a hardware wallets
- [ ] Recursos avançados de herança

## 📄 Licença
Este projeto está licenciado sob **Creative Commons Attribution-ShareAlike 4.0 International** (CC BY-SA 4.0). Veja o arquivo [LICENSE.md](./LICENSE.md) para detalhes completos.

## 👨‍💻 Autoria

### 🎓 Sobre o Projeto
Este projeto foi desenvolvido como parte da formação **Design Fundamentals** do **[Bitcoin Creative](https://bitcoincreative.org)** - o primeiro programa de formação em design e criatividade para Bitcoin no Brasil. Uma iniciativa educacional que une design thinking, estratégia criativa e os princípios fundamentais do Bitcoin.

### 👩‍💻 Desenvolvedora
Desenvolvido com ❤️ por **Bruna Czarnobay**  
*UX/UI Designer & Bitcoiner*  
**Participante do Programa Design Fundamentals - Bitcoin Creative**

📧 **Email:** [brunamaraf1@gmail.com](mailto:brunamaraf1@gmail.com)  
🌐 **LinkedIn:** [linkedin.com/in/bruna-czarnobay](https://www.linkedin.com/in/bruna-czarnobay/)  
🐦 **X (Twitter):** [x.com/czarnobaybruna](https://x.com/czarnobaybruna?s=21)  
📷 **Instagram:** [instagram.com/bruna.czarnobay](https://www.instagram.com/bruna.czarnobay?igsh=MzYxa2Qwb2FxaGJr&utm_source=qr)  
💼 **Portfólio:** [brunaczarnobay.framer.website](https://brunaczarnobay.framer.website/)  
💻 **GitHub:** [@BrunaCzarnobay](https://github.com/BrunaCzarnobay)

### 🌟 Agradecimentos Especiais
- **[Bitcoin Creative](https://bitcoincreative.org)** pela oportunidade incrível de aprendizado e mentoria
- **Equipe de professores** do programa Design Fundamentals pela orientação valiosa
- **Comunidade Bitcoin brasileira** pela inspiração constante e apoio
- **Todos os contribuidores** do ecossistema open source que tornam projetos como este possíveis

### 🎯 Contexto do Bitcoin Creative
O Bitcoin Creative é uma iniciativa pioneira que busca:
- 🔧 Capacitar designers e criativos no ecossistema Bitcoin
- 🎨 Desenvolver soluções centradas no usuário para problemas reais
- 🌱 Fomentar a educação bitcoinera através do design
- 🤝 Conectar profissionais e criar uma comunidade colaborativa

**Este projeto é um dos resultados dessa visão inovadora!**

## 🤝 Como Contribuir
1. **Fork o projeto** 🍴
2. **Clone seu fork** 
   ```bash
   git clone https://github.com/seu-usuario/bitgrow-app.git
   cd bitgrow-app
   ```
3. **Crie uma branch** 
   ```bash
   git checkout -b feature/nova-feature
   ```
4. **Commit suas mudanças** 
   ```bash
   git commit -m 'feat: adiciona nova funcionalidade'
   ```
5. **Push para a branch** 
   ```bash
   git push origin feature/nova-feature
   ```
6. **Abra um Pull Request** 🎉

## ❓ FAQ
### ❓ O BitGrow é custodial?
**✅ Não!** O BitGrow é **não-custodial**. Adultos têm controle total sobre suas chaves privadas.

### ❓ Como funciona a segurança para crianças?
**🛡️ Com controles parentais:** Todas as transações exigem aprovação dos pais, e limites podem ser configurados.

### ❓ Preciso pagar para usar?
**🎉 Não!** O BitGrow será gratuito e open source, seguindo os princípios do Bitcoin.

### ❓ Qual blockchain é suportada?
**₿ Bitcoin-only!** Suportamos apenas Bitcoin Mainnet e Lightning Network.

### ❓ Posso contribuir com código?
**🤝 Sim!** Este projeto é open source e aceitamos contribuições.

<div align="center">
⭐ Se este projeto te ajudou, deixe uma estrela no repositório!
</div>
-------------------------------------------------------------------------------------------------------------------------------------------

# English Version

# 🌱 BitGrow

**Financial freedom for the family, from an early age**

> A family platform that combines gamified Bitcoin education with a secure non-custodial Bitcoin wallet

[![Figma](https://img.shields.io/badge/Figma-Design%20do%20Projeto-orange?style=for-the-badge&logo=figma)](https://www.figma.com/design/Wlb7taeCnmIeljf8uZUV5j/BitGrow?m=auto&t=jkYFzdzmDaxqle1Y-6)

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Bitcoin Only](https://img.shields.io/badge/Bitcoin-Only-orange.svg)](https://bitcoin.org/)
[![Lightning Network](https://img.shields.io/badge/Lightning-Network-blue.svg)](https://lightning.network/)
[![Status](https://img.shields.io/badge/Status-In_Development-yellow.svg)](https://github.com/BrunaCzarnobay/bitgrow-app)
[![Bitcoin Creative](https://img.shields.io/badge/Bitcoin-Creative-purple.svg)](https://bitcoincreative.org/)

<img width="2037" height="1526" alt="Group 48095575" src="https://github.com/user-attachments/assets/6b03a7f7-0d03-4be1-b6a4-bb3f0ccf3d41" />


## 📋 Table of Contents
- [✨ Overview](#-overview)
- [🎯 Objective](#-objective)
- [👥 Target Audience](#-target-audience)
- [🚀 Features](#-features)
- [🛠️ Technologies](#️-technologies)
- [🎨 Design System](#-design-system)
- [📁 Project Structure](#-project-structure)
- [📸 Screenshots](#-screenshots)
- [🌩️ Lightning Network](#️-lightning-network)
- [📊 Transaction Flow](#-transaction-flow)
- [📅 Roadmap](#-roadmap)
- [📄 License](#-license)
- [👨‍💻 Authorship](#-authorship)
- [🤝 How to Contribute](#-how-to-contribute)
- [❓ FAQ](#-faq)

## ✨ Overview
BitGrow was born from the need to educate new generations about financial sovereignty in a practical and secure way. More than a wallet, it's a **complete educational journey** that prepares the entire family for a future of financial freedom with Bitcoin.

> 💡 *"With Bitcoin, you protect the fruits of your labor. With BitGrow, you teach your children to do the same."*

## 🎯 Objective
| Goal | Description | Status |
|------|-------------|---------|
| **🧠 Education** | Teach concepts of sound money, self-custody, and economics | ✅ |
| **🛡️ Security** | Offer secure tools with parental controls and multisig | ✅ |
| **🚀 Adoption** | Facilitate entry into the Bitcoin ecosystem for all ages | 🚧 |
| **👨‍👩‍👧‍👦 Family** | Create a shared financial learning experience | ✅ |

## 👥 Target Audience
| Group | Age | Needs | Status |
|-------|-----|-------|---------|
| **🧒 Children** | 7-10 years | Gamified learning, visible rewards, parental controls | ✅ |
| **🧑 Teens** | 11-16 years | Advanced content, simulations, savings goals | 🚧 |
| **👨‍💼 Adults** | 17+ years | Secure wallet, multisig, digital inheritance, family control | ✅ |
| **👨‍👩‍👧‍👦 Families** | All ages | Unified dashboard, reports, shared goals | ✅ |

## 🚀 Features
### 🧒 Kids Mode (7-10 years)
- ✅ **Digital Piggy Bank** with sats visualization
- ✅ **Gamified Missions** and educational quizzes
- ✅ **Lightning Rewards** with parental approval
- ✅ **Playful Interface** with friendly illustrations
- ✅ **Integrated Parental Controls**

### 🧑 Teen Mode (11-16 years)
- ✅ **Advanced Content** about inflation and security
- 🚧 **Lightning Simulations** with controlled limits
- ✅ **Long-term Savings Goals**
- ✅ **Achievement Badges** and progression
- 🚧 **Self-custody lessons**

### 👨‍💼 Adult Mode (17+ years)
- ✅ **Non-custodial Lightning Wallet**
- ✅ **2-of-3 Multisig Vault** for savings
- ✅ **Digital Inheritance Tools**
- ✅ **Complete Parental Control**
- ✅ **Family Progress Reports**

### 👨‍👩‍👧‍👦 Family Dashboard
- ✅ **Unified View** of family progress
- ✅ **Limit Control** and approvals
- ✅ **Activity** and learning reports
- ✅ **Shared Family Goals**
- ✅ **Security Settings**

## 🛠️ Technologies
### 📱 Frontend
```yaml
framework: React Native
language: TypeScript
styling: Styled Components
testing: Jest + React Testing Library


### ⚡ Bitcoin & Lightning
```yaml
network: Bitcoin Mainnet
layer2: Lightning Network
wallet: LDK (Lightning Development Kit)
multisig: Miniscript Descriptors
backup: BIP39 Seed Phrases
```

### 🔐 Security
```yaml
authentication: Biometrics + PIN
storage: Secure Enclave + Async Storage
encryption: AES-256 + SHA-256
backup: Encrypted cloud + local
```

### 🎨 Design & UX
```yaml
prototyping: Figma
design system: Custom BitGrow
icons: Custom SVG
animations: Lottie + Reanimated
```

### 📦 Infrastructure
```yaml
build: GitHub Actions
deploy: TestFlight + Play Store
monitoring: Sentry
analytics: Plausible (privacy-friendly)
```

## 🎨 Design System
### 🎯 Color Palette
```css
--bitcoin-orange: #F7931A;    /* Primary actions and emphasis */
--black: #000000;              /* Headlines and main text */
--dark-gray: #333333;          /* Secondary text */
--light-gray: #F5F5F5;         /* Backgrounds and surfaces */
--kids-blue: #2D7FF9;          /* Kids visual identity */
--teen-green: #00BFA5;         /* Teen visual identity */
--success: #22C55E;            /* Confirmations and success */
--warning: #F59E0B;            /* Alerts and warnings */
--error: #DC2626;              /* Errors and dangers */
```

### ✒️ Typography
```css
--font-heading: 'Inter', -apple-system, sans-serif;
--font-body: 'Roboto', -apple-system, sans-serif;
--font-mono: 'Fira Code', monospace;
--text-xs: 12px;
--text-sm: 14px;
--text-base: 16px;
--text-lg: 18px;
--text-xl: 20px;
--text-2xl: 24px;
--text-3xl: 30px;
```

### 📐 Spacing
```css
--space-1: 4px;
--space-2: 8px;
--space-3: 12px;
--space-4: 16px;
--space-5: 20px;
--space-6: 24px;
--space-8: 32px;
--space-10: 40px;
```

### 🧩 Components
| Component | Status | Documentation |
|-----------|--------|---------------|
| Primary Button | ✅ | [See specifications](./design/components/button.md) |
| Secondary Button | ✅ | [See specifications](./design/components/button.md) |
| Mission Card | ✅ | [See specifications](./design/components/card.md) |
| Text Input | 🚧 | [See specifications](./design/components/input.md) |
| Modal | 🚧 | [See specifications](./design/components/modal.md) |
| Navigation Bar | ✅ | [See specifications](./design/components/navbar.md) |

## 📁 Project Structure
```
bitgrow-app/
├── 📱 src/
│   ├── components/          # Reusable components
│   │   ├── ui/             # Interface components
│   │   ├── bitcoin/        # Bitcoin-specific components
│   │   └── family/         # Family components
│   ├── screens/            # App screens
│   │   ├── kids/          # Kids mode screens
│   │   ├── teen/          # Teen mode screens
│   │   ├── adult/         # Adult mode screens
│   │   └── family/        # Family Dashboard
│   ├── services/          # Services and APIs
│   │   ├── bitcoin/       # Bitcoin services
│   │   ├── lightning/     # Lightning services
│   │   └── storage/       # Data management
│   ├── utils/             # Utilities and helpers
│   │   ├── bitcoin/       # Bitcoin utilities
│   │   ├── family/        # Family utilities
│   │   └── security/      # Security utilities
│   └── types/             # TypeScript definitions
├── 📚 documentation/
│   ├── BitGrow-Detailed-Project.pdf
│   ├── presentation.pdf
│   ├── architecture.md    # System architecture
│   └── assets/           # Images and diagrams
├── 🎨 design/
│   ├── figma/            # Figma prototype link
│   ├── components/       # Component specifications
│   ├── screenshots/      # Screenshots
│   └── style-guide.md    # Complete style guide
├── 📦 scripts/           # Development scripts
├── 📄 LICENSE.md         # CC BY-SA 4.0 License
└── 📖 README.md          # This file
```

## 📸 Screenshots
<img width="2580" height="1580" alt="Backup - Instruções da Frase de Recuperação" src="https://github.com/user-attachments/assets/cf1cef23-71cd-4310-944a-d83aad67d740" />
<img width="2580" height="1580" alt="Backup - Exibir Frase de Recuperação" src="https://github.com/user-attachments/assets/9649b743-014d-4520-ae51-94df624525fc" />
<img width="2580" height="1580" alt="Backup - Alerta de Segurança" src="https://github.com/user-attachments/assets/3e330f8b-3ab1-4181-b55d-6fe79bf6bc31" />
<img width="2580" height="1580" alt="Backup - Confirmar Frase de Recuperação" src="https://github.com/user-attachments/assets/fb532981-fd55-4b69-93ef-5a07412417a8" />
<img width="2580" height="1580" alt="Home" src="https://github.com/user-attachments/assets/b07ca586-2cd0-47cd-8343-db79e72e7372" />
<img width="2580" height="1580" alt="Ativos" src="https://github.com/user-attachments/assets/a730a5ca-1a73-44fb-a94e-27e93badbb35" />


## 🌩️ Lightning Network
### ⚡ Lightning Integration
BitGrow uses Lightning Network for instant micro-rewards, negligible fee transactions, and real-time practical experience.

**LSP Partnerships**
```yaml
partners:
  - name: Lightning Network+
    services: [channel management, liquidity]
  - name: Bitcoin Beach
    services: [education, community]
```

**Layered Security**
- ✅ Value limits per transaction
- ✅ Mandatory parental approval
- ✅ Automatic channel backup
- ✅ 24/7 monitoring

### 📊 Lightning Dashboard
- ✅ Sats balance visualization
- ✅ Simplified transaction history
- ✅ Real-time savings goals
- ✅ Learning statistics

## 📊 Transaction Flow
flowchart TD
    A[Child completes mission] --> B[Generates Lightning invoice]
    B --> C[BitGrow Server + LSP Partner]
    C --> D[Payment is processed]
    D --> E[Parents approve and set limits]
    E --> F[Sats go to piggy bank]
    F --> G[Excess to multisig vault]

## 📅 Roadmap
### 🎯 Phase 1 - MVP (Completed ✅)
- [x] Complete design system
- [x] Navigable Figma prototype
- [x] Technical architecture defined
- [x] Initial documentation

### 🚀 Phase 2 - Development (In Progress 🚧)
- [ ] Frontend development (React Native)
- [ ] Lightning Network integration
- [ ] Multisig implementation
- [ ] Rewards system
- [ ] Testing with real users
- [ ] UI/UX polishing

### 🌟 Phase 3 - Launch (Planned 📅)
- [ ] App Store launch
- [ ] Play Store launch
- [ ] Beta tester program
- [ ] Educational campaign
- [ ] Onboarding of first families

### 🔮 Phase 4 - Future (Ideas 💡)
- [ ] School integrations
- [ ] Educational programs
- [ ] Web version
- [ ] Public API
- [ ] Hardware wallet support
- [ ] Advanced inheritance features

## 📄 License
This project is licensed under **Creative Commons Attribution-ShareAlike 4.0 International** (CC BY-SA 4.0). See the [LICENSE.md](./LICENSE.md) file for complete details.

## 👨‍💻 Authorship
### 🎓 About the Project
This project was developed as part of the **Design Fundamentals** program by **[Bitcoin Creative](https://bitcoincreative.org)** - the first design and creativity training program for Bitcoin in Brazil. An educational initiative that combines design thinking, creative strategy, and the fundamental principles of Bitcoin.

### 👩‍💻 Developer
Developed with ❤️ by **Bruna Czarnobay**  
*UX/UI Designer & Bitcoiner*  
**Participant in Design Fundamentals Program - Bitcoin Creative**

📧 **Email:** [brunamaraf1@gmail.com](mailto:brunamaraf1@gmail.com)  
🌐 **LinkedIn:** [linkedin.com/in/bruna-czarnobay](https://www.linkedin.com/in/bruna-czarnobay/)  
🐦 **X (Twitter):** [x.com/czarnobaybruna](https://x.com/czarnobaybruna?s=21)  
📷 **Instagram:** [instagram.com/bruna.czarnobay](https://www.instagram.com/bruna.czarnobay?igsh=MzYxa2Qwb2FxaGJr&utm_source=qr)  
💼 **Portfolio:** [brunaczarnobay.framer.website](https://brunaczarnobay.framer.website/)  
💻 **GitHub:** [@BrunaCzarnobay](https://github.com/BrunaCzarnobay)

### 🌟 Special Thanks
- **[Bitcoin Creative](https://bitcoincreative.org)** for the incredible learning opportunity and mentorship
- **Teaching team** of the Design Fundamentals program for valuable guidance
- **Brazilian Bitcoin community** for constant inspiration and support
- **All contributors** of the open source ecosystem that make projects like this possible

### 🎯 Bitcoin Creative Context
Bitcoin Creative is a pioneering initiative that aims to:
- 🔧 Empower designers and creatives in the Bitcoin ecosystem
- 🎨 Develop user-centered solutions for real problems
- 🌱 Foster Bitcoin education through design
- 🤝 Connect professionals and create a collaborative community

**This project is one of the results of this innovative vision!**

## 🤝 How to Contribute
1. **Fork the project** 🍴
2. **Clone your fork** 
   ```bash
   git clone https://github.com/your-username/bitgrow-app.git
   cd bitgrow-app
   ```
3. **Create a branch** 
   ```bash
   git checkout -b feature/new-feature
   ```
4. **Commit your changes** 
   ```bash
   git commit -m 'feat: add new feature'
   ```
5. **Push to the branch** 
   ```bash
   git push origin feature/new-feature
   ```
6. **Open a Pull Request** 🎉

## ❓ FAQ
### ❓ Is BitGrow custodial?
**✅ No!** BitGrow is **non-custodial**. Adults have full control over their private keys.

### ❓ How does security work for children?
**🛡️ With parental controls:** All transactions require parental approval, and limits can be configured.

### ❓ Do I need to pay to use it?
**🎉 No!** BitGrow will be free and open source, following Bitcoin's principles.

### ❓ Which blockchain is supported?
**₿ Bitcoin-only!** We only support Bitcoin Mainnet and Lightning Network.

### ❓ Can I contribute with code?
**🤝 Yes!** This project is open source and we accept contributions.


<div align="center">
**⭐ If this project helped you, leave a star on the repository!**
</div>

