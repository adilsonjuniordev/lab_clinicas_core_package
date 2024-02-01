# Lab Clinicas (Flutter Experience)

[![forthebadge](https://forthebadge.com/images/badges/made-with-flutter.svg)](http://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-coffee.svg)](http://forthebadge.com)

[![MIT License](https://img.shields.io/badge/Flutter-3.16.9-blue)](https://docs.flutter.dev/release/release-notes)
[![MIT License](https://img.shields.io/badge/Dart-3.2.6-blue)](https://docs.flutter.dev/release/release-notes)

Projeto desenvolvido em 01/2024, utilizando o Flutter, com o intuito de aprimorar os conhecimentos no framework, utilizando arquitetura orientada à package, através de um core que será reaproveitado nas plataformas mobile, web e desktop.

## Stack utilizada

**Mobile:** Flutter (SDK versão inicial: 3.16.9)

## Packages utilizados no Core

| Package                    | Versão | Descrição                                         |
| :----------------          | :----- | :------------------------------------------------ |
| `flutter_getit`            | ^2.0.0 | Utilizado para injeção de dependências.           |
| `signals_flutter`          | ^3.0.0 | Utilizado para gerência de estado no projeto.     |
| `dio`                      | ^5.4.0 | Utilizado para requisições HTTP.                  |
| `shared_preferences`       | ^2.2.2 | Utilizado para persistência de dados local.       |
| `top_snackbar_flutter`     | ^3.1.0 | Utilizado para exibir snackbars customizadas.     |
| `loading_animation_widget` | ^1.2.0+4 | Utilizado para exibir loaders customizados.     |
| `asyncstate`               | ^2.1.1-dev.1 | Utilizado para exibir loader em todas as requisições assincronas automaticamente. |

## Como utilizar

Para utilizar o core, adicione-o como depêndencia de um projeto Flutter no arquivo pubspec.yaml, e adicione como path, o caminho deste package.

Sua depêndencia deve ser configurada de forma similar a esta abaixo:

```yaml
lab_clinicas_core:
    path: ../lab_clinicas_core
```

## Dica complementar

Depois de adicioná-lo como dependência no seu projeto, não se esqueça de obter o pacote:

```bash
flutter pub get
```

Qualquer dúvida, entre em contato que estarei disposto a auxiliá-lo!

## Desenvolvedor

### Adilson Junior

[![github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/adilsonjuniordev)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adilsonjuniordev/)
