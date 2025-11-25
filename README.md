# Plano Tático: Operação Resgate INSS

**Cliente:** Dr. João Henrique Coutinho
**Desenvolvido por:** BF Labs
**Prazo:** 31/12/2025

## 📋 Sobre o Projeto

Este é um plano tático completo para operação de resgate de benefícios INSS, desenvolvido como uma "operação de guerra" para processar 6.000 leads em 35 dias com segurança e eficiência.

## 🚀 Funcionalidades Principais

### 1. Estratégia de Infraestrutura
- **Balanceamento de Carga Regional:** Distribuição inteligente de mensagens
- **Aquisição de Chips:** DDDs correspondentes aos estados com mais leads
- **Rotação Automática:** Sistema rotaciona entre números para evitar bloqueios
- **Segmentação Geográfica:** Clientes recebem mensagens de DDDs locais

### 2. Fluxos de Automação

#### Fluxo 01: O "Batedor" (Prospecção Ativa)
- Tecnologia: Automação com IA geradora de textos personalizados
- Cadência: 3 semanas de acompanhamento (6 mensagens)
- Gatilho: Resposta imediata cai no atendimento

#### Fluxo 02: O Agente Especialista (Atendimento)
- Tecnologia: Agente de IA treinado com linguagem do Dr. João
- Funções: Tira dúvidas, envia provas sociais, valida dados
- Notificação: Alerta imediato para supervisor humano

### 3. Projeções de Tráfego
- **Cenário 1:** 500 leads/chip (~12 chips) - Finaliza 18/12
- **Cenário 2:** 800 leads/chip (~7 chips) - Finaliza 22/12

## 🛠️ Tecnologias Utilizadas

- **Frontend:** HTML5, TailwindCSS, Font Awesome
- **Tipografia:** Google Fonts (Playfair Display, Inter)
- **Deploy:** Vercel
- **Versionamento:** Git
- **Hospedagem:** GitHub

## 📦 Como Rodar o Projeto

### Pré-requisitos
- Node.js 14.0.0 ou superior
- Git

### Instalação
```bash
# Clone o repositório
git clone https://github.com/BFLabsAI/planejamento-dr-joao-henrique.git

# Entre na pasta do projeto
cd planejamento-dr-joao-henrique

# Instale as dependências
npm install
```

### Executando Localmente
```bash
# Para desenvolvimento (abre o navegador automaticamente)
npm run dev

# Para produção
npm start
```

O projeto estará disponível em `http://localhost:3000`

## 🌐 Deployment

### GitHub Actions
O projeto está configurado para deploy automático na Vercel quando há push para a branch main.

### Deploy Manual na Vercel
1. Conecte sua conta Vercel ao GitHub
2. Importe o repositório: `BFLabsAI/planejamento-dr-joao-henrique`
3. Configure as variáveis de ambiente (se necessário)
4. Deploy!

## 📁 Estrutura do Projeto

```
dr-joao-henrique/
├── index.html          # Página principal com plano tático
├── package.json        # Dependências e scripts do projeto
├── vercel.json        # Configuração de deployment na Vercel
├── README.md          # Este arquivo
└── .gitignore         # Arquivos ignorados pelo Git
```

## 🎯 Entregáveis Necessários

Para iniciar a operação, o escritório precisa fornecer:

1. **Base de Dados:** Planilha com 6.000 contatos
2. **Chips:** Compra baseada na projeção escolhida
3. **Material de Treino:** Textos e provas sociais
4. **Vídeos:** 3 vídeos curtos e verticais do Dr. João

## 📊 Métricas e KPIs

- **Meta:** Processar 6.000 leads em 35 dias
- **Conversão Esperada:** [Definir com cliente]
- **Limite Seguro:** 300 envios/dia por chip
- **Período:** Dezembro/2025

## 🔐 Segurança

- Headers de segurança configurados
- Cache otimizado para assets estáticos
- Preconnect para external resources
- HTTPS via Vercel

## 📞 Contato

- **Desenvolvedor:** Bruno Falcao
- **Empresa:** BF Labs
- **GitHub:** https://github.com/BFLabsAI

## 📄 Licença

MIT License - BF Labs 2025

---

## 🚀 Próximos Passos

1. ✅ Aprovação deste plano
2. ✅ Definição da projeção (500 ou 800 leads/chip)
3. ⏳ Gravação dos vídeos
4. ⏳ Setup técnico da operação

---

*Desenvolvido com inteligência e estratégia pela BF Labs.*