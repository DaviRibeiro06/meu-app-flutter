
# Repositório de Exemplos em Dart

Bem-vindo ao repositório de exemplos em Dart! Este repositório foi criado com o objetivo de fornecer uma referência clara e organizada para quem deseja aprender ou revisar conceitos fundamentais da linguagem Dart.

## Conteúdo do Repositório

Aqui você encontrará exemplos práticos de códigos Dart abordando os seguintes tópicos:

### 1. Funções (Functions)

Exemplos de declaração e uso de funções, incluindo:

- Funções com e sem retorno.
- Parâmetros obrigatórios e opcionais.
- Funções anônimas (lambda).

**Exemplo:**

```dart
void saudar(String nome) {
  print('Olá, $nome!');
}

int soma(int a, int b) => a + b;
```

### 2. Estruturas Condicionais

Demonstrações de como usar condicionais para controle de fluxo, como:

- `if`, `else` e `else if`.
- Operador ternário.
- Switch case.

**Exemplo:**

```dart
void verificarIdade(int idade) {
  if (idade >= 18) {
    print('Você é maior de idade.');
  } else {
    print('Você é menor de idade.');
  }
}
```

### 3. Loops

Exemplos de diferentes tipos de loops em Dart, como:

- `for`
- `while`
- `do-while`
- Iteração com listas usando `for-in` e `forEach`.

**Exemplo:**

```dart
void listarNumeros(int n) {
  for (int i = 0; i <= n; i++) {
    print('Número: $i');
  }
}
```

### 4. Modelos (Models)

Como criar e usar classes para representar modelos de dados, incluindo:

- Declaração de classes.
- Construtores nomeados e padrão.
- Uso de getters e setters.

**Exemplo:**

```dart
class Pessoa {
  String nome;
  int idade;

  Pessoa(this.nome, this.idade);

  void apresentar() {
    print('Olá, meu nome é $nome e eu tenho $idade anos.');
  }
}
```

### 5. Tipos de Dados

Exemplos abrangentes de tipos nativos e personalizados, como:

- Tipos primitivos: `int`, `double`, `String`, `bool`.
- Coleções: `List`, `Set`, `Map`.
- Enumerações (Enums).

**Exemplo:**

```dart
void trabalharComTipos() {
  int idade = 25;
  double altura = 1.75;
  String nome = 'Ana';
  bool ativo = true;

  List<String> habilidades = ['Dart', 'Flutter', 'Git'];
  print('Habilidades: $habilidades');
}
```

## Como Usar Este Repositório

1. Clone o repositório:
   ```bash
   git clone https://github.com/DaviRibeiro06/meu-app-flutter.git
   ```
2. Navegue para a pasta do projeto:
   ```bash
   cd meu-app-flutter/app
   ```
3. Abra os arquivos de exemplo no editor de código de sua preferência.
    ```bash
   cd lib
   ```
   
## Contribuições

Contribuições são bem-vindas! Se você tem ideias de melhorias ou novos exemplos para incluir, fique à vontade para abrir uma *issue* ou enviar um *pull request*.

## Licença

Este repositório é licenciado sob a [MIT License](LICENSE).

---

Aproveite os exemplos e bons estudos com Dart!


