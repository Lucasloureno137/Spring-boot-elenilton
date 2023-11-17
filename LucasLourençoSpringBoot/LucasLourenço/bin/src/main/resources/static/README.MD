## Aplicação Java de Calculadora

### Classe `CalculatorApplication`

- Classe principal que inicia a aplicação Spring Boot.
- Anotada com `@SpringBootApplication`.

### Classe `CalculatorConfig`

- Classe de configuração vazia para a aplicação.

### Classe `CalculatorController`

#### Métodos

- `CalculatorController(CalculatorService calculatorService)`
  - Construtor da classe `CalculatorController`.
  - Recebe uma instância de `CalculatorService` e associa ao atributo `calculatorService`.

- `double add(double num1, double num2)`
  - Realiza a adição de dois números.

- `double subtract(double num1, double num2)`
  - Realiza a subtração de dois números.

- `double multiply(double num1, double num2)`
  - Realiza a multiplicação de dois números.

- `double divide(double num1, double num2)`
  - Realiza a divisão de dois números, verificando se o divisor é zero.

### Classe `CalculatorService`

#### Métodos

- `double add(double num1, double num2)`
  - Realiza a adição de dois números.

- `double subtract(double num1, double num2)`
  - Realiza a subtração de dois números.

- `double multiply(double num1, double num2)`
  - Realiza a multiplicação de dois números.

- `double divide(double num1, double num2)`
  - Realiza a divisão de dois números, verificando se o divisor é zero.

### Frontend - HTML

#### Arquivo `calculator.html`

- Arquivo HTML que cria uma interface de calculadora básica.

#### Estrutura e funcionalidade:

- Define um fundo degradê azul escuro e claro como plano de fundo.
- Utiliza elementos `<input>` para receber entrada do usuário e exibir o resultado.
- Fornece botões numéricos, botões de operações (+, -, *, /), botão de limpar (C) e botão de igualdade (=) para executar operações.
- Inclui scripts JavaScript para manipular as operações da calculadora.
- Usa estilos embutidos para definir a aparência dos elementos e botões.