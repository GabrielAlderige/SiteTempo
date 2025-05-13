# Previsão do Tempo - GabrielAlderige

Este é um aplicativo simples de previsão do tempo que permite ao usuário buscar a previsão do tempo para qualquer cidade usando a API do OpenWeather. O aplicativo exibe informações como temperatura, umidade, previsão do tempo e um ícone relacionado ao clima atual.

## Funcionalidades

- **Busca de cidade**: O usuário pode inserir o nome de uma cidade e clicar no botão para buscar a previsão do tempo dessa cidade.
- **Exibição de dados**: O aplicativo exibe informações sobre:
  - Nome da cidade
  - Temperatura em Celsius
  - Descrição do clima (ex: Nublado, Ensolarado)
  - Umidade do ar
  - Ícone representando o clima atual
- **Interação com a API OpenWeather**: Utiliza a API OpenWeather para buscar dados climáticos em tempo real.

## Tecnologias Utilizadas

- **HTML**: Estrutura da página web.
- **CSS**: Estilo e layout da página.
- **JavaScript**: Lógica de busca e manipulação dos dados de previsão do tempo.
- **API**: OpenWeather API para obter dados climáticos.

## Como Rodar o Projeto

1. Clone ou baixe este repositório em sua máquina local.
2. No diretório do projeto, abra o arquivo `index.html` em um navegador.
3. Insira o nome de uma cidade no campo de texto e clique no ícone de busca para visualizar a previsão do tempo dessa cidade.

### Requisitos

- **Chave de API do OpenWeather**: Você precisa de uma chave de API do OpenWeather para que o aplicativo funcione corretamente. Cadastre-se em [OpenWeather](https://openweathermap.org/) para obter a sua chave.
- **Configuração da chave da API**: No arquivo `script.js`, substitua a variável `key` com sua chave de API:

```javascript
const key = "sua-chave-aqui";


Depois de configurar sua chave de API, o aplicativo estará pronto para ser usado.