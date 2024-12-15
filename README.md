
# Projeto: Busca Países

## Descrição

Este é um site simples que permite ao usuário pesquisar informações sobre um país, digitando seu nome em inglês. O site utiliza a API **RestCountries** para obter dados do país e exibe informações como:

- Nome do país
- Bandeira
- Capital
- Continente
- População

## Funcionalidades

- **Pesquisa de país**: O usuário pode digitar o nome de um país em inglês e, ao clicar em "Pesquisar", o site irá buscar as informações sobre o país na API.
- **Exibição de informações**: Após a pesquisa, o site exibe os detalhes sobre o país, incluindo a bandeira, a capital, o continente e a população.
- **Conversão de números**: A população do país é convertida em formato extenso (exemplo: "1,000,000" para "1 Milhão").

## Tecnologias Utilizadas

- **HTML5**: Estrutura do site.
- **CSS (Bootstrap 5)**: Estilização da página e layout responsivo.
- **JavaScript**: Manipulação do DOM e chamada da API.
- **API RestCountries**: Para buscar informações sobre os países.

## Como Usar

1. Abra o arquivo `index.html` no seu navegador.
2. Digite o nome de um país em inglês na caixa de pesquisa.
3. Clique em "Pesquisar" para exibir as informações do país.
4. O site irá buscar e exibir informações sobre o país, como bandeira, capital, continente e população.

## Exemplo de uso

- **Pesquisa**: "Brazil"
- **Resultado**:
    - Nome do país: Brazil
    - Bandeira: [imagem da bandeira do Brasil]
    - Capital: Brasília
    - Continente: América do Sul
    - População: 211,000,000 (ou "211 Milhões", dependendo da conversão)

## Estrutura de Diretórios

```
/assets
    /logoSenac.svg        # Logo da Senac
/index.html              # Arquivo principal HTML
```

## Considerações

Este projeto é uma ótima base para aprender sobre o consumo de APIs e a exibição de dados dinâmicos em uma página web. O uso do Bootstrap facilita o design responsivo, e o JavaScript permite a interação com a API para buscar e exibir as informações.

---

**Autor**: Seu Nome  
**Data de Criação**: 2024  
**Licença**: MIT
