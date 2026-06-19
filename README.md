# 🐝 Bee Fly – Canos Coloridos

Um jogo estilo *Flappy Bird* com uma abelha carismática, obstáculos coloridos, sistema de progressão de velocidade, conquistas e medalhas. Desenvolvido em HTML5, CSS e JavaScript puro, sem dependências externas.

![Prévia do jogo](https://via.placeholder.com/400x700/4A90E2/FFFFFF?text=Bee+Fly)

---

## 🎮 Funcionalidades

- **Controle simples** – toque ou clique na tela para fazer a abelha voar.
- **Dificuldade progressiva** – a velocidade dos obstáculos aumenta conforme sua pontuação, de 2.0 até 5.0.
- **Sistema de pontuação** – ganhe 1 ponto a cada cano que passar.
- **Recorde local** – sua melhor pontuação é salva automaticamente no navegador.
- **Conquistas** – desbloqueie 4 conquistas ao atingir marcos específicos.
- **Medalhas** – ao final da partida, receba uma medalha de acordo com sua pontuação.
- **Efeitos visuais** – partículas de comemoração, nuvens, flores e asas batendo.
- **Design responsivo** – adapta-se a diferentes tamanhos de tela (celular/desktop).

---

## 🕹️ Como Jogar

1. Acesse o jogo (ou abra o arquivo `index.html` no navegador).
2. Na tela inicial, clique em **Jogar**.
3. Toque ou clique na tela para fazer a abelha subir.
   - A gravidade a puxa para baixo – mantenha o ritmo para desviar dos canos.
4. Passe pelos canos para marcar pontos.
5. Se colidir com um cano ou com o chão, o jogo termina.
6. Veja sua pontuação final, recorde e medalha.
7. Clique em **Jogar Novamente** para tentar melhorar.

---

## 🏆 Conquistas

| Conquista             | Como desbloquear      | Ícone |
|-----------------------|-----------------------|-------|
| Primeiro Voo          | Iniciar a primeira partida | 🌱 |
| Polinizador Júnior    | Alcançar **10** pontos     | 🌸 |
| Mestre da Colmeia     | Alcançar **30** pontos     | 🍯 |
| Abelha Supersônica    | Alcançar **50** pontos     | ⚡ |

Todas as conquistas são salvas localmente e podem ser visualizadas no menu principal.

---

## 🥇 Medalhas

Ao final de cada partida, você recebe uma medalha com base na pontuação:

| Pontuação | Medalha       | Cor         |
|-----------|---------------|-------------|
| ≥ 50      | 💎 Diamante   | Azul        |
| ≥ 30      | 🥇 Ouro       | Dourado     |
| ≥ 15      | 🥈 Prata      | Cinza       |
| ≥ 5       | 🥉 Bronze     | Bronze      |
| < 5       | ❌ Sem medalha| Cinza claro |

---

## ⚙️ Mecânicas Técnicas

- **Velocidade progressiva**  
  A velocidade dos canos começa em **2.0** e aumenta **0.08** a cada ponto, até o limite de **5.0**. Isso garante um desafio crescente.

- **Gap dos canos**  
  O espaço entre os canos diminui gradualmente de **400px** até **120px** conforme a pontuação aumenta, tornando o jogo mais difícil.

- **Sistema de colisão**  
  A detecção usa colisão círculo-retângulo com uma pequena margem de segurança para uma experiência justa.

- **Salvamento local**  
  Utiliza `localStorage` para armazenar:
  - Melhor pontuação (`beefly_highscore`)
  - Progresso das conquistas (`beefly_achievements`)

---

## 🖥️ Execução Local

Como o jogo é um único arquivo HTML, você pode:

1. Baixar o arquivo `index.html`.
2. Abri-lo com qualquer navegador moderno (Chrome, Firefox, Edge, etc.).
3. Jogar imediatamente – nenhum servidor ou instalação necessária.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** – estrutura da página.
- **CSS3** – estilização, animações, layout responsivo.
- **JavaScript (ES6)** – lógica do jogo, renderização em canvas, gerenciamento de estado.
- **Canvas API** – renderização gráfica em tempo real.
- **LocalStorage** – persistência de dados do jogador.

---

## 📁 Estrutura do Projeto
