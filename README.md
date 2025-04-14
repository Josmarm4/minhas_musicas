# 🎵 Projeto Minhas Músicas

Este é um projeto desenvolvido durante o curso da **Alura** sobre Orientação a Objetos em Java. Nele, criamos uma pequena aplicação para gerenciar músicas e podcasts, utilizando todos os quatro pilares da programação orientada a objetos: **abstração**, **encapsulamento**, **herança** e **polimorfismo**.

## 📚 Conceitos Aplicados

- **Abstração**: representamos elementos do mundo real como `Musica`, `Podcast` e `Audio`, focando apenas nos atributos e comportamentos essenciais.
- **Encapsulamento**: protegemos os atributos com `private` e criamos métodos públicos de acesso (`get` e `set`), controlando o que pode ser acessado ou alterado.
- **Herança**: as classes `Musica` e `Podcast` herdam da superclasse `Audio`, aproveitando e estendendo seus comportamentos.
- **Polimorfismo**: o método `inclui()` da classe `MinhasPreferidas` aceita um `Audio`, mas se comporta de maneira diferente conforme o tipo real do objeto (`Musica` ou `Podcast`), graças à sobrescrita do método `getClassificacao()`.

Além disso:
- Organizamos o código em pacotes (`modelos` e `principal`);
- Utilizamos boas práticas de projeto, como reutilização de código e separação de responsabilidades.

## 💻 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Josmarm4/minhas-musicas.git
   ```

2. Abra o projeto em uma IDE como **IntelliJ IDEA** ou **VS Code com suporte a Java**.

3. Execute a classe `Principal.java` para simular o uso do sistema.

## 📦 Estrutura de Diretórios

```
minhas-musicas/
├── minhasmusicas/
│   ├── modelos/
│   │   ├── Audio.java
│   │   ├── Musica.java
│   │   ├── Podcast.java
│   │   └── MinhasPreferidas.java
│   └── principal/
│       └── Principal.java
```

## 🧪 Exemplo de Saída

```text
BolhaDevé é considerado sucesso absoluto e preferido por todos.
Forever também é um dos que todo mundo está curtindo.
```

## 🚀 Tecnologias Utilizadas

- Java 17+
- Orientação a Objetos
- IntelliJ IDEA
- Git e GitHub

## 🧠 Aprendizados

Durante esse projeto, foi possível:

- Praticar os 4 pilares da OOP;
- Estruturar um código reutilizável e organizado;
- Simular regras de negócio com lógica personalizada;
- Trabalhar com sobrescrita de métodos e referências polimórficas;
- Entender como criar e consumir classes de maneira eficiente em Java.

---

### ✍️ Autor

Desenvolvido por Josmar Miguel durante o curso da Alura.
