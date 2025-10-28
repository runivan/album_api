# album_api

Resumo
------

`album_api` é um projeto Flutter de exemplo que demonstra como consumir uma API REST para listar e visualizar álbuns (ex.: endpoints JSON que retornam álbuns e fotos). O objetivo principal é servir como referência simples para chamadas HTTP, parsing de JSON e exibição de listas em uma aplicação Flutter multiplataforma (Android, iOS, Web, Windows, macOS e Linux).

Principais funcionalidades
- Busca e listagem de álbuns via requisições HTTP
- Exibição de detalhes de cada álbum (por exemplo: título, id, lista de fotos)
- Estrutura mínima pronta para rodar em múltiplas plataformas suportadas pelo Flutter

Tecnologias
- Flutter (Dart)
- Cliente HTTP (ex.: `http` package)

Como executar (rápido)
1. Tenha o Flutter instalado e configurado: https://flutter.dev/docs/get-started/install
2. Abra o diretório do projeto:

```powershell
cd c:\Projetos\Flutter\flutter_application_2\flutter_application_1\flutter_application_1\album_api
```

3. Instale dependências e rode o app:

```powershell
flutter pub get
flutter run
```

Observações
- Se o projeto consumir uma API externa (ex.: JSONPlaceholder), verifique se há necessidade de chave ou configuração de URL base.
- Ajuste os targets (emulador, dispositivo físico ou web) conforme sua plataforma de desenvolvimento.

Próximos passos sugeridos
- Adicionar instruções de testes automatizados
- Incluir badges de build/CI (ex.: GitHub Actions)
- Documentar endpoints usados e exemplos de resposta

Licença
-------
Coloque aqui a licença do projeto (por exemplo, `MIT`) ou remova esta seção se preferir outra política de licenciamento.

Contribuição
------------
Contribuições são bem-vindas. Abra issues para bugs ou feature requests e envie pull requests para revisão.

