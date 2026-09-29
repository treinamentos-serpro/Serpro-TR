# 📘 Tarefa: Jogo da Forca

## 🎯 Objective

Pratique o uso de strings, listas, condicionais e loops em Python criando um jogo clássico de adivinhação de palavras.

## 📝 Tasks

### 🛠️ Preparar o Estado Inicial do Jogo

#### Descrição
Defina a lista de palavras disponíveis, escolha uma palavra aleatória e inicialize as variáveis que controlarão o progresso do jogo.

#### Requisitos
O programa completo deve:

- Armazenar uma lista de palavras possíveis
- Selecionar uma palavra aleatória da lista
- Criar uma estrutura para guardar as letras já descobertas
- Definir o número máximo de tentativas incorretas

### 🛠️ Implementar a Lógica Principal do Jogo

#### Descrição
Crie o loop do jogo para receber os palpites do usuário, atualizar o estado da palavra e decidir quando o jogo termina.

#### Requisitos
O programa completo deve:

- Solicitar uma letra por vez ao usuário
- Verificar se a letra está presente na palavra secreta
- Atualizar a visualização da palavra com letras descobertas
- Contar e exibir as tentativas incorretas restantes
- Encerrar o jogo quando a palavra for completamente adivinhada ou as tentativas acabarem
- Exibir mensagens de vitória e derrota ao final do jogo