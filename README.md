# 🎵 Jukebox - Gerenciador de Playlists

Um sistema simples em Java para gerenciamento de playlists de música via terminal. Este projeto foi desenvolvido como prática de Orientação a Objetos, manipulação de Coleções e controle de fluxo.

## 📋 Sobre o Projeto

O **Jukebox** permite que o usuário crie uma playlist personalizada, cadastre músicas com seus respectivos anos de lançamento e, ao final, visualize a lista ordenada alfabeticamente. O foco principal foi a aplicação prática de conceitos fundamentais da linguagem Java.

## 🚀 Funcionalidades

- **Criação de Playlist:** Definição de nome personalizado para a lista.
- **Cadastro Dinâmico:** Loop de interação para adicionar quantas músicas o usuário desejar.
- **Ordenação Automática:** Implementação da interface `Comparable` para ordenar as músicas pelo título automaticamente.
- **Tratamento de Dados:** Uso de `Scanner` para entrada de dados via console.

## 🛠️ Tecnologias e Conceitos Utilizados

* **Java** (JDK)
* **POO:** Encapsulamento, Classes e Objetos (`Musica`, `Playlist`).
* **Java Collections:** Uso de `ArrayList` e `Collections.sort`.
* **Interfaces:** Implementação de `Comparable<Musica>`.
* **Entrada de Dados:** Classe `Scanner` e tratamento de buffer (`nextLine`).

## 📂 Estrutura do Projeto

O código está organizado em três classes principais:

1.  **`Principal.java`**: Ponto de entrada da aplicação, contendo a interação com o usuário e o loop principal `while`.
2.  **`Playlist.java`**: Responsável por armazenar a lista de músicas e o nome da coleção.
3.  **`Musica.java`**: Modelo que representa a música (título e ano) e define a regra de ordenação.

## ▶️ Como Executar

1.  Clone este repositório.
2.  Abra o projeto na sua IDE favorita (IntelliJ, Eclipse, VS Code).
3.  Execute a classe `Principal.java`.
4.  Siga as instruções no console para criar sua playlist!

---
Desenvolvido durante estudos de Java e Orientação a Objetos.
