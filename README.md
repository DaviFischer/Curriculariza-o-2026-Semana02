# 🎮 Quiz Brusque - Jogo Educativo Infantil

![Versão](https://img.shields.io/badge/versão-1.0-blue) ![Idade](https://img.shields.io/badge/idade-5%2B-brightgreen) ![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)

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

✅ **Sistema de Áudio Integrado**
- Leitura automática de perguntas em áudio
- Narração das respostas para melhor compreensão
- Feedback sonoro para acertos e erros
- Controle de volume ajustável

✅ **Interface Altamente Visual e Interativa**
- Design colorido e atrativo para crianças
- Animações suaves e dinamismo na experiência
- Ícones e ilustrações representativas
- Layout responsivo e intuitivo

✅ **Diversidade de Personagens**
- Personagens de diferentes etnias
- Representação de diferentes tamanhos e aparências
- Inclusão e diversidade como pilares do design
- Personagens que acompanham o progresso do jogador

✅ **Sistema de Login/Cadastro (Opcional)**
- Tela de boas-vindas com opções
- Cadastro simples para salvar progresso
- Jogar sem cadastro é totalmente possível
- Perfil do jogador com histórico (se logado)

✅ **Sistema de Dificuldade Progressivo**
- **Fácil**: Perguntas básicas com múltipla escolha (3 opções)
- **Médio**: Perguntas mais desafiadoras (4 opções)
- **Difícil**: Questões avançadas para reforço de aprendizado (4 opções)

---

## 🎨 Aspectos de Design e Experiência

### Visual
- Paleta de cores vibrante e amigável às crianças
- Fontes grandes e legíveis
- Ilustrações do patrimônio cultural de Brusque
- Animações que não distraem o aprendizado

### Acessibilidade
- Modo áudio completo (perguntas e respostas narradas)
- Alt text em todas as imagens
- Contraste adequado de cores
- Navegação simplificada

### Interatividade
- Botões com feedback visual imediato
- Efeitos sonoros gratificantes
- Barra de progresso visual
- Sistema de pontuação/medalhas

---

## 🛠️ Tecnologias Utilizadas

### Frontend
- **HTML5** - Estrutura semântica
- **CSS3** - Estilização e animações
- **JavaScript** - Lógica interativa e áudio

### Backend
- **Node.js** - Ambiente de execução
- **Express.js** - Framework web
- **MongoDB** ou **Firebase** - Banco de dados (para histórico de usuários)

### Áudio
- **Web Audio API** - Controle de áudio
- **Text-to-Speech API** - Síntese de fala (Google Cloud ou semelhante)

### Outras Ferramentas
- **Git/GitHub** - Controle de versão
- **Figma** - Design de interface
- **VS Code** - IDE de desenvolvimento

---

## 📦 Instalação e Configuração

### Pré-requisitos
- Node.js v14.0 ou superior
- npm ou yarn
- Navegador moderno (Chrome, Firefox, Safari, Edge)

---

### Configuração de Áudio
1. Registre-se em uma API de Text-to-Speech (Google Cloud, Azure, etc.)
2. Adicione as credenciais ao arquivo `.env`
3. Configure a chave de API no código

---

## 🎮 Como Jogar

### Tela Inicial
1. **Jogar Sem Login**: Clique em "Jogar Agora" para começar imediatamente
2. **Criar Conta**: Preencha nome e escolha um personagem (opcional)
3. **Fazer Login**: Se já tiver conta, faça login para acessar seu histórico

### Durante o Jogo
1. Selecione o **nível de dificuldade** (Fácil, Médio ou Difícil)
2. Clique no **ícone de áudio** para ouvir a pergunta
3. Selecione uma das **respostas disponíveis**
4. Receba **feedback imediato** (áudio + visual)
5. Progresso é salvo automaticamente

### Após Completar
- Visualize sua **pontuação final**
- Veja **estatísticas da sessão**
- Escolha **jogar novamente** ou **voltar ao menu**

---

## 📚 Conteúdo Educativo

### Temas Abordados sobre Brusque
- 🏛️ **História**: Fundação, desenvolvimento, marcos históricos
- 🎭 **Cultura**: Tradições, festas, expressões culturais
- 🏞️ **Pontos Turísticos**: Museus, praças, monumentos
- 🏭 **Desenvolvimento**: Economia, indústria têxtil
- 👥 **Diversidade**: Comunidades, imigrantes
- 🌳 **Meio Ambiente**: Natureza local, preservação

---

## 🔒 Privacidade e Segurança

- ✅ Conformidade com LGPD (Lei Geral de Proteção de Dados)
- ✅ Dados de menores protegidos
- ✅ Sem coleta desnecessária de informações
- ✅ Senhas criptografadas (se aplicável)
- ✅ Sessões seguras

---

## 🎵 Integração de Áudio

### Recursos de Áudio
- **Narração de Perguntas**: Cada pergunta é lida em voz clara
- **Narração de Respostas**: Opções de resposta narradas (opcional)
- **Efeitos Sonoros**: 
  - Acerto: Som positivo e gratificante
  - Erro: Som neutro
  - Transições: Efeitos suaves entre telas

### Configurações de Áudio
- Ajuste de volume
- Opção de mutar completamente
- Velocidade de reprodução (lenta/normal/rápida)

---

## 📱 Responsividade

O jogo funciona perfeitamente em:
- 🖥️ **Desktops**: Telas 1920x1080 e superiores
- 💻 **Tablets**: iPad, Android tablets
- 📱 **Smartphones**: Telas de 375px a 768px de largura

---

## 🐛 Resolução de Problemas

### Áudio não funciona
- Verifique as permissões do navegador
- Certifique-se de que o volume do sistema está ativo
- Limpe o cache do navegador

### Quiz não salva o progresso (sem login)
- Dados locais são armazenados no navegador (localStorage)
- Limpar dados do navegador pode apagar o histórico

### Página não carrega
- Verifique a conexão com a internet
- Reinicie o servidor com `npm run dev`
- Limpe o cache do navegador

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

---

## 🎓 Créditos Educacionais

**Disciplina**: Curricularização
**Professor/Orientador**: Jonathan Nau
**Universidade**: UNIFEBE - Centro Universitário de Brusque

---

## 🚀 Roadmap Futuro

- [ ] Integração com redes sociais
- [ ] Mais temas (história geral, ciências, etc.)
- [ ] Suporte a outros idiomas
- [ ] Sistema de selos e conquistas expandido
- [ ] Minigames adicionais

---

<div align="center">

### 🎉 Desenvolvido com ❤️ pela equipe de Sistemas da Informação - UNIFEBE 2026

**Quiz Brusque** - Aprendendo sobre nossa cidade de forma divertida! 🌟

</div>

---

## 📄 Notas Adicionais

- Este é um projeto educacional desenvolvido como parte do currículo de Sistemas da Informação da instituição UNIFEBE
- Todas as informações sobre Brusque foram cuidadosamente pesquisadas para garantir precisão educativa
- O jogo foi desenvolvido com foco em acessibilidade e inclusão
- Feedback de pais e educadores é sempre bem-vindo para melhorias futuras

---

**Última atualização**: 2026  
**Versão**: 1.0.0-alpha
