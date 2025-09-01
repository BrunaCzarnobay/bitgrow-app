# 🌱 BitGrow

**Liberdade financeira em família, desde cedo**

> Uma plataforma familiar que une educação bitcoinera gamificada com uma carteira Bitcoin não-custodial segura

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Bitcoin Only](https://img.shields.io/badge/Bitcoin-Only-orange.svg)](https://bitcoin.org/)
[![Lightning Network](https://img.shields.io/badge/Lightning-Network-blue.svg)](https://lightning.network/)
[![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow.svg)](https://github.com/BrunaCzarnobay/bitgrow-app)
[![Bitcoin Creative](https://img.shields.io/badge/Bitcoin-Creative-purple.svg)](https://bitcoincreative.org/)

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
![Dashboard Familiar](./design/screenshots/dashboard.png)
![Missões Kids](./design/screenshots/missions.png)
![Carteira Adult](./design/screenshots/wallet.png)

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
**⭐ Se este projeto te ajudou, deixe uma estrela no repositório!**
</div>
```
