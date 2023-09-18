# Diagrama UML do iPhone

Este é um diagrama UML que representa as classes e interfaces para o componente iPhone, com os comportamentos esperados de Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.

## Classes e Interfaces

### `ReprodutorMusical` (Interface)
- `tocar()`: Método para reproduzir música.
- `pausar()`: Método para pausar a reprodução.
- `selecionarMusica(musica: String)`: Método para selecionar uma música.

### `AparelhoTelefonico` (Interface)
- `ligar(numero: String)`: Método para fazer uma ligação.
- `atender()`: Método para atender uma chamada.
- `iniciarConversaVoz()`: Método para iniciar uma conversa por voz.

### `NavegadorInternet` (Interface)
- `exibirPagina(url: String)`: Método para exibir uma página da internet.
- `adicionarNovaAba()`: Método para adicionar uma nova aba do navegador.
- `atualizarPagina()`: Método para atualizar a página do navegador.

### `IPhone` (Classe)
- Implementa todas as interfaces acima.
- Fornece a implementação real para todos os métodos das interfaces.
- Representa o iPhone, que desempenha os papéis de Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.

## Como Usar

Este diagrama UML pode ser usado como referência ao desenvolver software que envolva um componente de iPhone. Ele descreve os comportamentos esperados do iPhone em relação à reprodução de música, chamadas telefônicas e navegação na internet.

![Diagrama UML do iPhone](https://app.diagrams.net/#G1H2BIArmecVHF9C-3AiXeznpFLXJooMUT)

