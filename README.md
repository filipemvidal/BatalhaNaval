# BatalhaNaval 🚢

Um joguinho simples de batalha naval no terminal desenvolvido em C++. 

## 📋 Descrição do Projeto

Este é um jogo de Batalha Naval para terminal com uma mecânica única. Diferentemente do jogo clássico onde cada jogador tem seu próprio tabuleiro, nesta versão ambos os jogadores jogam no mesmo tabuleiro gerado aleatoriamente pelo computador.

**Objetivo:** Destruir o maior número de navios possível e acumular mais pontos que o adversário.

### Mecânicas Especiais

- **Sistema de pontuação diferenciado**: O primeiro jogador a acertar um navio e o jogador que acertar a última posição livre do navio recebem pontos extras
- **Opções de personalização**:
  - **Opção 1**: Determina se ao destruir completamente um navio, os pontos ao redor dele serão automaticamente preenchidos com asteriscos vermelhos
  - **Opção 2**: Determina se ao acertar um navio, o jogador pode jogar novamente logo em seguida

> 💡 **Nota**: Este foi o meu primeiro projeto da faculdade! 

## 🚀 Como Instalar/Usar

### Pré-requisitos

- Compilador C++ (g++, clang++ ou similar)
- Terminal/Console

### Compilação

```bash
g++ batalhaNaval.cpp -o ./output/batalhaNaval
```

### Execução

```bash
./output/batalhaNaval
```

### Como Jogar

1. Execute o programa
2. Configure as opções de personalização do jogo
3. Para jogar, escolha a posição onde deseja lançar uma bomba
4. Use o formato de entrada: `<número><letra>` (exemplo: `2f`, `5a`, `10c`)
5. Alterne os turnos entre os jogadores
6. O jogo termina quando todos os navios forem destruídos
7. O jogador com mais pontos vence! 

**DIVIRTA-SE!** 🎮

## 🛠️ Tecnologias Utilizadas

- **C++**: Linguagem de programação principal
- **Terminal/Console**: Interface do usuário

## 📁 Estrutura do Projeto

```
BatalhaNaval/
├── batalhaNaval.cpp    # Código fonte principal
├── README.md           # Documentação do projeto
└── output/             # Diretório de saída
```

---

⭐ Desenvolvido por [filipemvidal](https://github.com/filipemvidal)
