# ⏰ VitalClock - Gerenciador Inteligente de Tempo de Vida

![VitalClock Banner](https://img.shields.io/badge/VitalClock-Inova%C3%A7%C3%A3o%20Paulista-7c3aed?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

## 🌟 Sobre o Projeto

O **VitalClock** é uma plataforma web inovadora que utiliza inteligência artificial para calcular e visualizar a expectativa de vida baseada em hábitos diários. Desenvolvido como parte da iniciativa **"Inovações Paulistas: Criando o Futuro Sustentável e Inclusivo da Nossa Região"**, o projeto visa promover saúde pública, conscientização sobre qualidade de vida e bem-estar acessível para todos os brasileiros.

### 🎯 Objetivos

- **Conscientização**: Mostrar de forma tangível como hábitos diários impactam a longevidade
- **Sustentabilidade**: Promover escolhas saudáveis que beneficiam tanto o indivíduo quanto o meio ambiente
- **Inclusão**: Oferecer acesso gratuito a informações de saúde baseadas em dados científicos
- **Inovação**: Utilizar tecnologia e IA para democratizar o acesso à análise de saúde personalizada

### 🔗 Conexão com o Tema

O VitalClock conecta-se ao tema "Inovações Paulistas" ao:

1. **Tecnologia Acessível**: Plataforma 100% web, sem necessidade de instalação
2. **Dados Locais**: Utiliza estatísticas de saúde pública brasileira
3. **Impacto Social**: Promove mudanças de hábitos que reduzem pressão no sistema de saúde
4. **Sustentabilidade**: Incentiva hábitos que reduzem pegada de carbono (menos uso de carro, alimentação natural)
5. **Inclusão Digital**: Interface acessível (WCAG 2.1 AA) com navegação por teclado e leitores de tela

---

## 🚀 Acesse o Projeto

**🌐 Site ao vivo:** [https://joaoestevam700.github.io/vitalclock/](https://joaoestevam700.github.io/vitalclock/)

---

## ✨ Funcionalidades

### 🔐 Sistema de Autenticação
- ✅ Cadastro e login de usuários
- ✅ Armazenamento seguro (criptografado) de dados locais
- ✅ Persistência de sessão

### 📊 Análise de Expectativa de Vida
- ✅ Questionário interativo de 4 etapas
- ✅ Algoritmo baseado em estudos científicos
- ✅ Análise de 8 fatores de saúde:
  - Sono
  - Exercício físico
  - Alimentação
  - Tabagismo
  - Consumo de álcool
  - Nível de estresse
  - Tempo de tela
  - Idade e sexo biológico

### ⏰ Relógio de Vida em Tempo Real
- ✅ Contador regressivo animado (anos, dias, horas, minutos, segundos)
- ✅ Visualização impactante do tempo restante
- ✅ Atualização em tempo real

### 🔄 Simulador de Mudanças
- ✅ Simule alterações de hábitos
- ✅ Veja o impacto em anos ganhos/perdidos
- ✅ Comparação lado a lado (atual vs. simulado)
- ✅ Recomendações personalizadas

### 💬 Chatbot com IA
- ✅ Assistente virtual inteligente
- ✅ Respostas sobre saúde e hábitos
- ✅ Sugestões contextualizadas
- ✅ Disponível 24/7

### 📈 Dados de Saúde Pública
- ✅ Integração com estatísticas brasileiras
- ✅ Comparação com médias nacionais
- ✅ Contextualização dos resultados

### ♿ Acessibilidade Total
- ✅ Navegação completa via teclado
- ✅ Suporte para leitores de tela
- ✅ Atributos ARIA completos
- ✅ Conformidade WCAG 2.1 AA
- ✅ Alto contraste
- ✅ Skip links

Mais em breve, verificar nosso Roadmap...

---

## 🛠️ Tecnologias Utilizadas

### Frontend
- **HTML5**: Estrutura semântica completa
- **CSS3**: Design system customizado, Flexbox, CSS Grid
- **JavaScript ES6+**: Lógica moderna e otimizada
- **React 18**: Componentes reutilizáveis e gerenciamento de estado
- **Babel**: Transpilação JSX

### Design & UX
- **Design System Proprietário**: Paleta de cores coesa, tipografia escalável
- **Animações CSS**: Transições fluidas e microinterações
- **Responsividade**: Mobile-first, adaptável a todos os dispositivos
- **Iconografia**: Emojis para comunicação universal

### APIs & Dados
- **LocalStorage API**: Persistência local de dados
- **Crypto API**: Criptografia de senhas (Base64)
- **Simulação de Health API**: Dados de saúde pública

### Acessibilidade
- **ARIA Labels**: Navegação assistiva completa
- **Keyboard Navigation**: Suporte total via teclado
- **Focus Management**: Indicadores visuais claros
- **Semantic HTML**: Tags apropriadas para cada conteúdo

---

## 📦 Estrutura do Projeto
```
vitalclock/
│
├── index.html          # Arquivo único com toda a aplicação
├── README.md          # Este arquivo
```

### 🏗️ Arquitetura do Código
```javascript
// Design System (CSS Variables)
:root {
    --primary-purple: #7c3aed;
    --primary-blue: #3b82f6;
    --primary-green: #10b981;
    // ... mais variáveis
}

// Componentes React
- VitalClock (Container Principal)
  ├── LandingPage (Página inicial)
  ├── LoginPage (Autenticação)
  ├── QuestionarioPage (Questionário)
  ├── DashboardPage (Painel principal)
  └── SimuladorModal (Modal de simulação)

// Utilitários
- DB: Gerenciamento de dados locais
- HealthAPI: Integração com dados de saúde
- calculateLifeExpectancy: Algoritmo de IA
- showToast: Sistema de notificações
```

---

## 🎨 Design System

### Paleta de Cores

| Cor | Hex | Uso |
|-----|-----|-----|
| ![#7c3aed](https://via.placeholder.com/15/7c3aed/7c3aed.png) Purple | `#7c3aed` | Primária |
| ![#3b82f6](https://via.placeholder.com/15/3b82f6/3b82f6.png) Blue | `#3b82f6` | Secundária |
| ![#10b981](https://via.placeholder.com/15/10b981/10b981.png) Green | `#10b981` | Sucesso |
| ![#f59e0b](https://via.placeholder.com/15/f59e0b/f59e0b.png) Orange | `#f59e0b` | Atenção |
| ![#ef4444](https://via.placeholder.com/15/ef4444/ef4444.png) Red | `#ef4444` | Erro |

### Tipografia
- **Fonte**: Inter (Google Fonts)
- **Escalas**: 0.75rem até 3.75rem
- **Pesos**: 300, 400, 500, 600, 700, 800, 900

---

## 🎮 Como Usar o VitalClock

1. **Acesse a página inicial** e clique em "Começar Análise Gratuita"
2. **Crie uma conta** com nome, email e senha
3. **Responda o questionário** de 4 etapas sobre seus hábitos
4. **Visualize seu Dashboard**:
   - Veja seu "Relógio de Vida" em tempo real
   - Analise o impacto de cada hábito
   - Receba recomendações personalizadas
5. **Use o Simulador** para ver como mudanças de hábitos afetam sua expectativa
6. **Converse com o Chatbot IA** para dúvidas sobre saúde

### 🎹 Navegação por Teclado
- `Tab`: Navegar entre elementos
- `Enter/Space`: Ativar botões
- `Esc`: Fechar modais
- `Setas`: Ajustar sliders

---

## 🤖 Como Funciona o Cálculo e Estimativa

O algoritmo de cálculo considera:
```javascript
Base: 76 anos (homens) | 81 anos (mulheres)

Fatores analisados:
+ Sono (7-8h): +3 anos
+ Exercício (4+ dias): +4 anos
+ Dieta saudável: +3 anos
+ Não fumar: baseline
+ Baixo estresse: +2 anos

- Sono (<6h): -5 anos
- Sedentarismo: -3 anos
- Tabagismo: -10 anos
- Estresse alto: -4 anos
- Tela excessiva (8h+): -2 anos
```

---

## 📊 Dados e Fontes

### Estatísticas de Saúde
- **IBGE**: Expectativa de vida no Brasil
- **OMS**: Dados de saúde global
- **Ministério da Saúde**: Causas de morte no Brasil

### Base Científica
O algoritmo é baseado em estudos científicos sobre:
- Privação de sono e mortalidade
- Exercício físico e longevidade
- Impacto do tabagismo
- Nutrição e expectativa de vida
- Estresse crônico e saúde

---

## 🌐 Compatibilidade

### Navegadores Suportados
- ✅ Chrome 90+ (Recomendado)
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

### Dispositivos
- ✅ Desktop (1920x1080+)
- ✅ Laptop (1366x768+)
- ✅ Tablet (768x1024)
- ✅ Mobile (375x667+)

### Requisitos
- JavaScript habilitado
- LocalStorage habilitado
- Conexão com internet (para fontes externas)

---

## 📚 Créditos e Atribuições

### Bibliotecas de Terceiros
- **React 18.2.0** - [MIT License](https://github.com/facebook/react/blob/main/LICENSE)
  - Framework JavaScript para UI
  - Uso: Gerenciamento de componentes e estado
  
- **Babel Standalone 7.x** - [MIT License](https://github.com/babel/babel/blob/main/LICENSE)
  - Transpilador JavaScript
  - Uso: Transpilação JSX em tempo real

### Fontes
- **Inter** by Rasmus Andersson - [SIL Open Font License](https://github.com/rsms/inter/blob/master/LICENSE.txt)
  - Fonte tipográfica
  - Uso: Tipografia principal do sistema

### APIs e Dados
- **IBGE** - Dados públicos de expectativa de vida
- **OMS** - Estatísticas de saúde global
- Dados simulados para demonstração (ambiente de desenvolvimento)

### Inspiração de Design
- Tailwind CSS (paleta de cores)
- Material Design (princípios de acessibilidade)
- Stripe (design system)

### Ícones
- Emojis Unicode (domínio público)
- Sem necessidade de biblioteca externa

---

## 👨‍💻 Desenvolvimento

### Autor
**Equipe Vital (João Estevam Fernandes Barbosa & Kauã Henrique Lima da Cruz**
- GitHub: [joaoestevam700](https://github.com/joaoestevam700) & [kauahl](https://github.com/kauahl)
- LinkedIn: [João Estevam](https://www.linkedin.com/in/jo%C3%A3o-estevam-b05b2b309/) & [Kauã Henrique](https://www.linkedin.com/in/kau%C3%A3-henrique-lima-da-cruz-02ba7a309/)
- Email: joaoestevan8@email.com & kauahlcruz@gmail.com

### Licença
Este projeto está sob a licença **MIT**.
```
MIT License

Copyright (c) 2024 [João Estevam Fernandes Barbosa & Kauã Henrique Lima da Cruz]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```


---

## 🐛 Reportar Bugs

Encontrou um bug? Abra uma [issue](https://github.com/joaoestevam700/vitalclock/issues) com:
- Descrição detalhada do problema
- Passos para reproduzir
- Navegador e versão
- Screenshots (se aplicável)

---

## 🔮 Roadmap Futuro

### Versão 2.0
- [ ] Backend real com Node.js + PostgreSQL
- [ ] Autenticação OAuth (Google, Facebook)
- [ ] Integração Google Fit / Apple Health
- [ ] Gráficos de evolução temporal
- [ ] Sistema de metas e conquistas
- [ ] Notificações push
- [ ] Modo offline (PWA)
- [ ] Aplicativo mobile (React Native)

### Versão 3.0
- [ ] IA generativa para recomendações
- [ ] Telemedicina integrada
- [ ] Marketplace de produtos saudáveis
- [ ] Comunidade de usuários
- [ ] Versão corporativa (empresas)

---

## 📞 Contato e Suporte

- **Email**: Em Breve
- **Discord**: [Comunidade VitalClock](#) Em Breve
- **Twitter**: [@vitalclock](#) Em Breve

---

## ⭐ Se Gostou do Projeto

Se o VitalClock foi útil para você:
- ⭐ Dê uma estrela no GitHub
- 🐦 Compartilhe no Twitter
- 💼 Compartilhe no LinkedIn
- 👥 Indique para amigos e família

---

## 📖 Documentação Técnica Adicional

### Variáveis CSS Customizáveis
```css
:root {
    --primary-purple: #7c3aed;
    --primary-blue: #3b82f6;
    /* Customize suas cores aqui */
}
```

### Algoritmo de Cálculo
```javascript
const calculateLifeExpectancy = (data) => {
    let base = data.gender === 'male' ? 76 : 81;
    // Aplicar modificadores baseados em hábitos
    // Retorna expectativa e fatores
};
```

### LocalStorage Schema
```javascript
{
    "vitalclock_user": {
        "name": "Nome do Usuário",
        "email": "email@example.com",
        "password": "base64_hash",
        "createdAt": "2024-01-01T00:00:00.000Z"
    },
    "vitalclock_data_email@example.com": {
        "age": "30",
        "gender": "male",
        "sleep": "7",
        // ... outros dados
    }
}
```

---

## 🎓 Contexto Educacional

Este projeto foi desenvolvido para:
- Demonstrar boas práticas de desenvolvimento web
- Aplicar conceitos de UX/UI e acessibilidade
- Implementar IA de forma prática e útil
- Contribuir para saúde pública e bem-estar

---

## 🌍 Impacto Social

### Objetivos de Desenvolvimento Sustentável (ODS)
O VitalClock contribui para:
- **ODS 3**: Saúde e Bem-estar
- **ODS 9**: Indústria, Inovação e Infraestrutura
- **ODS 10**: Redução das Desigualdades
- **ODS 11**: Cidades e Comunidades Sustentáveis

---

## 📄 Changelog

### v1.0.0 (2025-22-10)
- ✅ Lançamento inicial
- ✅ Sistema de login/cadastro
- ✅ Questionário completo
- ✅ Dashboard com relógio de vida
- ✅ Simulador de mudanças
- ✅ Chatbot IA
- ✅ Acessibilidade completa (WCAG 2.1 AA)
- ✅ Design responsivo
- ✅ Documentação completa

---

<div align="center">

**🌟 Feito com ❤️ para um futuro mais saudável e sustentável 🌟**

[⬆ Voltar ao topo](#-vitalclock---gerenciador-inteligente-de-tempo-de-vida)

</div>
