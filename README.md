# Projeto exemplo de como utilizar Flutter Modular

Este projeto é um pequeno exemplo de como utilizar o poder do Flutter Modular para criar uma estrutura de aplicação escalável, fácil de manter e organizada. Seja você desenvolvendo um aplicativo pequeno ou um projeto complexo, o Flutter Modular ajuda a gerenciar dependências, rotas e módulos de maneira eficiente.

## Características

- **Arquitetura Modular**: Organize sua aplicação em módulos menores e reutilizáveis.
- **Injeção de Dependência**: Gerencie facilmente as dependências e seus ciclos de vida.
- **Gerenciamento de Rotas**: Simplifique a navegação com um poderoso sistema de rotas.
- **Escalabilidade**: Expanda sua aplicação adicionando novos módulos sem esforço.
- **Manutenção**: Mantenha seu código limpo e fácil de manter com limites de módulo bem definidos.

## Iniciando

Para começar com este projeto, siga estes passos:

1. **Clone o repositório**:
   ```sh
   git clone https://github.com/your-username/flutter-modular-project.git
   cd flutter-modular-project
  

2. **Install dependencies**:
  ```sh
   flutter pub get
  ```

3. **Project Structure**
O projeto segue uma arquitetura modular, com cada módulo encapsulando uma funcionalidade ou recurso específico. Aqui está uma visão geral da estrutura:

```sh
  lib/
  ├── app/
  │   ├── controllers/
  │   │   └── form_question_controller.dart
  │   ├── models/
  │   │   └── form_question_model.dart
  │   ├── pages/
  │   │   ├── dashboard_page.dart
  │   │   ├── form_question_page.dart
  │   │   ├── home_page.dart
  │   │   └── profile_page.dart
  ├── theme/
  │   └── theme_data.dart
  ├── widgets/
  │   └── chips_input_field.dart
  ├── main.dart
```

**Tecnologias Utilizadas**

- Flutter
- Flutter Modular
- Dart
