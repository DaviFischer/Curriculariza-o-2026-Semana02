# 🎮 Quiz Brusque - Jogo Educativo Infantil

![Versão](https://img.shields.io/badge/versão-1.0-blue) ![Idade](https://img.shields.io/badge/idade-5%2B-brightgreen) ![Status](https://img.shields.io/badge/status-funcional-brightgreen)

---

## 📋 Descrição do Projeto

**Quiz Brusque** é um jogo educativo interativo desenvolvido para crianças a partir de 5 anos, com foco em ensinar sobre a história, cultura e pontos turísticos da cidade de **Brusque - Santa Catarina**.

O jogo combina elementos visuais atraentes, narração em áudio e um sistema de dificuldade progressivo para criar uma experiência educativa divertida e acessível para o público infantil.

---

## ✨ Principais Características

### 🎯 Funcionalidades Core

✅ **Perguntas Educativas**
- Perguntas sobre a história, cultura e patrimônio de Brusque
- Três níveis de dificuldade: **Fácil**, **Médio** e **Difícil**
- Conteúdo apropriado para crianças de 5 anos
- Questões didáticas e envolventes
- **Pool/Piscina de perguntas** separada por dificuldade (17 perguntas fáceis, 19 médias e 19 difíceis)
- **Sorteio aleatório** de 10 perguntas por partida
- **Embaralhamento das alternativas** a cada jogada

✅ **Sistema de Áudio Integrado**
- Leitura automática de perguntas em áudio (Web Speech API nativa)
- Narração das alternativas de resposta
- Feedback narrado para acertos e erros com mensagens de encorajamento
- Voz configurada em português (pt-BR), com velocidade e tom amigáveis para crianças
- Botão dedicado para repetir a leitura da pergunta

✅ **Interface Altamente Visual e Interativa**
- Design colorido e atrativo para crianças
- Animações suaves: personagens pulando, confetes ao acertar, tremor em erros
- Ícones e emojis representativos em cada pergunta
- Layout totalmente responsivo (mobile, tablet, desktop)
- Barra de progresso visual em tempo real
- Botões grandes e amigáveis para dedos pequenos

✅ **Diversidade de Personagens**
- Personagens (emojis) de diferentes etnias e tons de pele
- Representação de crianças, bebês e adultos variados
- Inclusão e diversidade como pilares do design
- Personagens animados nas telas inicial e final

✅ **Sistema de Login (Opcional)**
- Tela de boas-vindas com campo de nome opcional
- **Jogar sem cadastro é totalmente possível**
- Nome salvo localmente no navegador para próximas sessões
- Saudação personalizada com o nome da criança durante o jogo

✅ **Sistema de Dificuldade Progressivo**
- **Fácil** 🐣: Perguntas básicas sobre Brusque (cidade, estado, símbolos)
- **Médio** 🦁: Perguntas sobre cultura, festas e história
- **Difícil** 🚀: Questões avançadas sobre datas, nomes históricos e detalhes
- Todas as dificuldades usam 4 opções de resposta

✅ **Sistema de Encorajamento**
- 10 mensagens variadas de parabéns para acertos
- 10 mensagens motivacionais para erros (sem desanimar a criança)
- Mensagem final personalizada baseada na pontuação
- Confetes animados ao acertar e ao finalizar com boa pontuação

---

## 🎨 Aspectos de Design e Experiência

### Visual
- Paleta de cores vibrante: rosa, amarelo, verde, azul, roxo e laranja
- Fontes grandes e legíveis (Comic Sans MS / Trebuchet MS)
- Gradientes coloridos em cada alternativa de resposta
- Animações que não distraem o aprendizado
- Nuvens decorativas animadas ao fundo

### Acessibilidade
- Modo áudio completo (perguntas e respostas narradas automaticamente)
- Atributos `aria-label` e `role` em elementos interativos
- Navegação completa por teclado (Tab + Enter)
- Foco visível em todos os elementos interativos
- Contraste adequado de cores
- Tipografia responsiva com `clamp()`

### Interatividade
- Botões com feedback visual imediato (sombra 3D, animação ao clicar)
- Efeitos sonoros e narração gratificantes
- Barra de progresso visual animada
- Sistema de pontuação com estrelas (de 1 a 5)
- Confete animado com emojis ao acertar

---

## 🛠️ Tecnologias Utilizadas

### Frontend (100% Vanilla — sem frameworks ou bibliotecas externas)
- **HTML5** — Estrutura semântica e acessível
- **CSS3** — Estilização completa, utilizando:
  - CSS Variables (`:root`) para sistema de cores consistente
  - Flexbox e CSS Grid para layouts responsivos
  - Keyframes e Animations para todas as animações
  - Gradientes lineares e radiais
  - Media queries para responsividade
  - `clamp()` para tipografia responsiva
  - Pseudo-elementos (`::before`) para decorações de fundo
- **JavaScript (Vanilla / ES6+)** — Toda a lógica do jogo:
  - Arrow functions, `const`/`let`, template literals
  - Spread operator e manipulação de arrays
  - Algoritmo Fisher-Yates para embaralhamento aleatório
  - Manipulação dinâmica do DOM

### APIs Nativas do Navegador
- **Web Speech API (SpeechSynthesis)** — Síntese de fala em português, totalmente gratuita e offline
- **localStorage** — Armazenamento do nome do jogador no navegador

### Recursos Visuais
- **Emojis Unicode** — Ícones e personagens nativos do sistema (sem dependência de bibliotecas de ícones)
- **Fontes do Sistema** — Comic Sans MS / Trebuchet MS (sem carregamento externo)

### Outras Ferramentas
- **Git/GitHub** — Controle de versão
- **VS Code** — IDE de desenvolvimento

### ⚡ Diferenciais Técnicos
- ❌ **Zero dependências externas** — sem React, Vue, jQuery, ou qualquer biblioteca
- ❌ **Zero requisições de rede** — funciona 100% offline após o primeiro carregamento
- ✅ **Arquivo único** — todo o jogo está em um único `.html` autossuficiente
- ✅ **Sem backend** — não requer servidor para funcionar

---

## 📦 Instalação e Configuração

### Pré-requisitos
- Navegador moderno (Chrome, Firefox, Safari, Edge — versão recente)
- Nenhuma instalação adicional necessária!

### Como Executar
1. Baixe o arquivo `quiz-brusque.html`
2. Clique duas vezes no arquivo (ou abra com qualquer navegador)
3. Pronto! O jogo está rodando

### Hospedagem (opcional)
Para disponibilizar online, basta hospedar o arquivo HTML em qualquer serviço de hospedagem estática:
- GitHub Pages
- Netlify
- Vercel
- Servidor web simples (Apache, Nginx)

---

## 🎮 Como Jogar

### Tela Inicial
1. **Digite seu nome** (opcional) — ou pule essa etapa
2. Clique em **"Vamos Jogar!"** para começar

### Escolha de Dificuldade
1. Escolha entre:
   - 🐣 **Fácil** — 1 estrela
   - 🦁 **Médio** — 2 estrelas
   - 🚀 **Difícil** — 3 estrelas

### Durante o Jogo
1. A pergunta é lida **automaticamente** em voz alta
2. Clique no ícone 🔊 para **ouvir novamente**
3. Selecione uma das **4 alternativas**
4. Receba **feedback imediato** (visual + sonoro + narrado)
5. Acompanhe seu progresso pela **barra superior**

### Após Completar
- Visualize sua **pontuação final** (X de 10)
- Veja suas **estrelas conquistadas** (até 5 estrelas)
- Receba uma **mensagem personalizada** de encorajamento
- Escolha entre:
  - 🔄 **Jogar de Novo** (mesma dificuldade)
  - 🎯 **Trocar Nível** (nova dificuldade)
  - 🏠 **Voltar ao Início**

---

## 📚 Conteúdo Educativo

### Temas Abordados sobre Brusque
- 🏛️ **História**: Fundação (1860), Barão de Schneeburg, nome da cidade
- 🎭 **Cultura**: Fenarreco, tradições alemãs, italianas e portuguesas
- 🏞️ **Pontos Turísticos**: Pórtico, Santuário de Azambuja, Museu Histórico
- 🏭 **Desenvolvimento**: Indústria têxtil, fábrica Renaux, comércio de roupas
- 👥 **Diversidade**: Imigrantes alemães, italianos, poloneses e portugueses
- 🌳 **Meio Ambiente**: Vale do Itajaí, Rio Itajaí-Mirim, Mata Atlântica
- ⚽ **Esporte**: Brusque FC (Quadricolor do Vale), Estádio Augusto Bauer
- 🍞 **Gastronomia**: Cuca, marreco, comidas típicas alemãs

---

## 🔒 Privacidade e Segurança

- ✅ Conformidade com LGPD (Lei Geral de Proteção de Dados)
- ✅ **Nenhum dado é enviado para servidores externos**
- ✅ Nome salvo apenas no navegador local (localStorage)
- ✅ Sem coleta de informações pessoais
- ✅ Sem cookies de rastreamento
- ✅ Seguro para uso infantil

---

## 🎵 Integração de Áudio

### Recursos de Áudio
- **Narração Automática**: Cada pergunta é lida automaticamente ao aparecer
- **Narração de Alternativas**: As 4 opções são narradas em sequência (A, B, C, D)
- **Feedback Narrado**: 
  - Acerto: Mensagens variadas de parabéns ("Muito bem!", "Você é demais!", etc.)
  - Erro: Mensagens encorajadoras ("Tudo bem!", "Continue tentando!", etc.)
- **Botão de Repetir**: Permite ouvir a pergunta novamente a qualquer momento

### Configurações da Voz
- Idioma: Português Brasileiro (pt-BR)
- Velocidade: 0.85 (mais lenta, ideal para crianças)
- Tom: 1.2 (mais agudo, voz amigável)
- Volume: 100%

---

## 📱 Responsividade

O jogo funciona perfeitamente em:
- 🖥️ **Desktops**: Telas 1920x1080 e superiores
- 💻 **Tablets**: iPad, Android tablets
- 📱 **Smartphones**: Telas a partir de 320px de largura
- 🖱️ **Touch e Mouse**: Compatível com ambos os tipos de entrada

---

## 🐛 Resolução de Problemas

### Áudio não funciona
- Verifique se o navegador permite reprodução de áudio
- Certifique-se de que o volume do sistema está ativo
- Alguns navegadores exigem interação inicial do usuário antes de reproduzir áudio
- Teste em outro navegador (Chrome tem o melhor suporte para Web Speech API)

### Quiz não lembra o nome
- Verifique se o navegador permite localStorage
- Modo anônimo/privado pode bloquear o armazenamento
- Limpar dados do navegador apaga o nome salvo

### Página não carrega
- Verifique se o arquivo HTML está completo
- Tente abrir em outro navegador
- Use um navegador atualizado (versões recentes do Chrome, Firefox, Safari ou Edge)

### Voz robotizada ou em outro idioma
- O navegador escolhe a melhor voz disponível em pt-BR
- Em alguns sistemas, pode ser necessário instalar pacote de voz em português
- Windows: Configurações > Hora e Idioma > Fala
- Mac: Preferências do Sistema > Acessibilidade > Fala

---

## 📝 Licença

Este projeto está licenciado sob a **MIT License** - veja o arquivo `LICENSE` para detalhes.

---

## 🤝 Contribuições

Contribuições são bem-vindas! Por favor:

1. Faça um **Fork** do projeto
2. Crie uma **Branch** para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a Branch (`git push origin feature/MinhaFeature`)
5. Abra um **Pull Request**

### Como adicionar novas perguntas
As perguntas estão no objeto `PERGUNTAS` no JavaScript, divididas por dificuldade. Basta adicionar novos objetos seguindo o formato:
```javascript
{
  icone: "🏙️",
  pergunta: "Sua pergunta aqui?",
  opcoes: ["Opção 1", "Opção 2", "Opção 3", "Opção 4"],
  correta: 0  // índice da resposta correta (0 a 3)
}
```

---

## 🎓 Créditos Educacionais

**Disciplina**: Curricularização  
**Professor/Orientador**: Jonathan Nau  
**Universidade**: UNIFEBE - Centro Universitário de Brusque

---

## 🚀 Roadmap Futuro

- [ ] Expandir piscina de perguntas (mais de 50 por dificuldade)
- [ ] Sistema de selos e conquistas
- [ ] Modo multiplayer local (revezamento)
- [ ] Imagens reais dos pontos turísticos de Brusque
- [ ] Suporte a outros idiomas (alemão e italiano, devido à imigração)
- [ ] Versão PWA (Progressive Web App) para instalação no celular
- [ ] Modo "história" com narrativa contínua
- [ ] Categorias temáticas (apenas história, apenas cultura, etc.)
- [ ] Sistema de ranking entre amigos
- [ ] Versão para professores com relatórios de aprendizado

---

<div align="center">

### 🎉 Desenvolvido com ❤️ pela equipe de Sistemas da Informação - UNIFEBE 2026

**Quiz Brusque** - Aprendendo sobre nossa cidade de forma divertida! 🌟

</div>

---

## 📄 Notas Adicionais

- Este é um projeto educacional desenvolvido como parte do currículo de Sistemas da Informação da instituição UNIFEBE
- Todas as informações sobre Brusque foram cuidadosamente pesquisadas para garantir precisão educativa
- O jogo foi desenvolvido com foco em **acessibilidade e inclusão**
- **Arquivo HTML único e autossuficiente** — não requer instalação, servidor ou conexão com internet
- Feedback de pais e educadores é sempre bem-vindo para melhorias futuras

---

**Última atualização**: 2026  
**Versão**: 1.0.0
