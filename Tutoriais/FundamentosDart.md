# Tutorial 2 – Fundamentos do Dart

## Sumário:
- Variáveis e Tipos de Dados
- Controle de Fluxo (if, loops)
- Funções e Métodos
- Classes e Objetos

## 1. Variáveis e Tipos de Dados

**Int**: O tipo `int` representa números inteiros. Ele abrange valores positivos e negativos sem parte decimal.

```dart
int numero = 42;
```

**Double**: O tipo double é usado para números de ponto flutuante, ou seja, números que possuem parte decimal. Ele é útil para lidar com cálculos que envolvem precisão decimal.

```dart
double altura = 1.75;
```

**Bool**: O tipo bool representa valores booleanos, ou seja, true (verdadeiro) ou false (falso). Ele é essencial para a criação de estruturas de controle condicional.

```dart
bool estaChovendo = false;
```

**String**: O tipo String é usado para armazenar sequências de caracteres. Isso é fundamental para lidar com texto e dados baseados em caracteres.

```dart
String saudacao = 'Olá, mundo!';
```

**var**: Permite que o Dart infira o tipo da variável automaticamente. Uma vez atribuída, o tipo não pode ser alterado.

**final:** Declara uma variável que pode ser atribuída apenas uma vez, mas cujo valor é determinado em tempo de execução.

**const:** Declara uma variável que deve ser uma constante em tempo de compilação, ou seja, o valor é conhecido e atribuído no momento da compilação.


```dart
void main() {
  var idade = 25; // O Dart infere o tipo como int
  final nome = 'João'; // Valor atribuído uma única vez
  const pi = 3.1415; // Valor constante

  print('Idade: $idade, Nome: $nome, Pi: $pi');
}

```
