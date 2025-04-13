# ingl-s-game
WordQuest – A fun and interactive vocabulary game to help users learn English through translation challenges, example sentences, and audio pronunciation. Built with HTML, CSS, JavaScript, and modern UI libraries.

# WordQuest Plus - English Vocabulary Game

## 📝 Description
WordQuest Plus is an interactive web-based game designed to help users learn English vocabulary in a fun and engaging way. The game features:

- 300+ words organized by themes and difficulty levels
- Multiple-choice questions with instant feedback
- Timer-based scoring system
- Pronunciation feature using browser's speech synthesis
- Progress tracking and review system

## 🎮 How to Play

1. **Select Options**:
   - Choose a difficulty level (Easy, Medium, Hard)
   - Select a vocabulary theme (Food, Animals, Technology, etc.) or "All" for mixed
   - Click "Confirm and Play"

2. **Gameplay**:
   - You'll see a Portuguese word and 4 English translation options
   - Select the correct translation before time runs out
   - Earn bonus points for quick answers
   - Use the speaker button to hear pronunciation

3. **Results**:
   - After completing all questions, see your score and performance
   - Review words you missed with examples
   - Play again to improve your score!

## ⚙️ Customization

### Adding More Words
To add more vocabulary, edit the `wordDatabase` object in the JavaScript code. Follow this structure:

```javascript
themeName: {
    difficultyLevel: [
        { pt: "portuguese word", en: "english translation", exemplo: "example sentence" },
        // more words...
    ],
    // more difficulty levels...
},
// more themes...
```

### Changing Game Settings
- **Number of questions**: Change the `20` in `shuffled.slice(0, 20)` to your preferred number
- **Timer duration**: Modify the `timeLeft = 60` value
- **Scoring system**: Adjust the `calculatePoints()` function

### Styling
- Modify the CSS variables at the top of the `<style>` section to change colors
- Add new theme colors by creating new CSS classes (like `.theme-yourtheme`)
- Adjust animations and responsive breakpoints as needed

## 🌐 Technologies Used
- HTML5, CSS3, JavaScript
- Web Speech API for pronunciation
- Font Awesome for icons
- Google Fonts (Poppins)

## 📜 License
Free to use and modify (MIT License)

---

# WordQuest Plus - Jogo de Vocabulário em Inglês

## 📝 Descrição
WordQuest Plus é um jogo interativo baseado na web projetado para ajudar usuários a aprender vocabulário em inglês de forma divertida e envolvente. O jogo inclui:

- 300+ palavras organizadas por temas e níveis de dificuldade
- Perguntas de múltipla escolha com feedback instantâneo
- Sistema de pontuação baseado em tempo
- Recurso de pronúncia usando a síntese de voz do navegador
- Acompanhamento de progresso e sistema de revisão

## 🎮 Como Jogar

1. **Seleção de Opções**:
   - Escolha um nível de dificuldade (Fácil, Médio, Difícil)
   - Selecione um tema de vocabulário (Comida, Animais, Tecnologia, etc.) ou "Todos" para misturado
   - Clique em "Confirmar e Jogar"

2. **Jogo**:
   - Você verá uma palavra em português e 4 opções de tradução em inglês
   - Selecione a tradução correta antes do tempo acabar
   - Ganhe pontos bônus por respostas rápidas
   - Use o botão de alto-falante para ouvir a pronúncia

3. **Resultados**:
   - Após completar todas as perguntas, veja sua pontuação e desempenho
   - Revise as palavras que errou com exemplos
   - Jogue novamente para melhorar sua pontuação!

## ⚙️ Personalização

### Adicionar Mais Palavras
Para adicionar mais vocabulário, edite o objeto `wordDatabase` no código JavaScript. Siga esta estrutura:

```javascript
nomeDoTema: {
    nivelDeDificuldade: [
        { pt: "palavra em português", en: "tradução em inglês", exemplo: "frase de exemplo" },
        // mais palavras...
    ],
    // mais níveis de dificuldade...
},
// mais temas...
```

### Alterar Configurações do Jogo
- **Número de perguntas**: Mude o `20` em `shuffled.slice(0, 20)` para seu número preferido
- **Duração do timer**: Modifique o valor `timeLeft = 60`
- **Sistema de pontuação**: Ajuste a função `calculatePoints()`

### Estilização
- Modifique as variáveis CSS no topo da seção `<style>` para mudar cores
- Adicione novas cores de tema criando novas classes CSS (como `.theme-seutema`)
- Ajuste animações e pontos de quebra responsivos conforme necessário

## 🌐 Tecnologias Utilizadas
- HTML5, CSS3, JavaScript
- Web Speech API para pronúncia
- Font Awesome para ícones
- Google Fonts (Poppins)

## 📜 Licença
Livre para uso e modificação (Licença MIT)
