# SemoC2 - Sistema de Eventos e Palestrantes

O SemoC2 é um aplicativo Android que permite aos usuários visualizar informações sobre eventos e palestrantes de um evento específico. O aplicativo é composto por vários fragmentos e atividades que exibem essas informações de forma clara e interativa.

## Capturas de Tela

![Tela Inicial](screenshots/screenshot1.png)
*Figura 1: Tela inicial exibindo eventos disponíveis*

![Tela de Palestrantes](screenshots/screenshot2.png)
*Figura 2: Tela de palestrantes*

## Recursos Principais

- **Visualização de Eventos:** O fragmento "Home" exibe uma lista de eventos disponíveis, incluindo seus títulos e descrições. Os usuários podem tocar em um evento para obter mais detalhes.

- **Visualização de Palestrantes:** O fragmento "Gallery" exibe uma lista de palestrantes que participarão do evento. Os usuários podem tocar em um palestrante para visualizar informações detalhadas.

- **Mapa de Localização:** O fragmento "Slideshow" exibe um mapa com uma localização específica.

## Tecnologias Usadas

- **Android:** O aplicativo é desenvolvido em Android e segue as melhores práticas de design de interface do usuário para dispositivos móveis.

- **Retrofit:** É usado para fazer chamadas de rede para buscar informações de eventos de uma fonte externa.

- **RecyclerView:** É utilizado para exibir listas de eventos e palestrantes de forma eficiente.

## Configuração e Execução

1. Clone o repositório para o seu ambiente de desenvolvimento.

2. Abra o projeto no Android Studio.

3. Certifique-se de que as dependências e bibliotecas estão configuradas corretamente.

4. Execute o aplicativo em um emulador Android ou dispositivo físico.

## API de Dados

O aplicativo consome uma API de dados para buscar informações sobre eventos. A interface `MyApiService` define os métodos de busca de dados, como a lista de eventos. Os dados são então exibidos nas atividades correspondentes.

## Contribuição

- Você é bem-vindo para contribuir para o projeto reportando problemas, enviando solicitações de pull ou melhorando a documentação.

- Certifique-se de seguir as diretrizes de contribuição do projeto ao enviar solicitações de pull.

## Autores

- [Seu Nome](https://github.com/seu-usuario) - Desenvolvedor Principal

## Licença

Este projeto é licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para obter detalhes.

## Agradecimentos

- Agradecemos a todos os colaboradores e à comunidade de código aberto por tornar este projeto possível.
