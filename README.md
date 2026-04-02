# Projeto Convert

Aplicação web simples para conversão de moedas estrangeiras para Real Brasileiro (BRL).

## Sobre o projeto

O projeto permite informar um valor, escolher uma moeda e visualizar:

- A cotação usada na conversão.
- O valor convertido para reais.

Atualmente, as cotações estão definidas diretamente no código JavaScript.

## Funcionalidades

- Conversão de:
  - Dólar Americano (USD)
  - Euro (EUR)
  - Libra Esterlina (GBP)
- Formatação de moeda no padrão brasileiro (`pt-BR`).
- Interface responsiva com feedback visual do resultado.
- Validação básica de entrada no campo de valor.

## Tecnologias

- HTML5
- CSS3
- JavaScript (Vanilla)

## Estrutura do projeto

```text
Projeto-Convert/
|-- index.html
|-- styles.css
|-- scripts.js
|-- img/
```

## Como executar localmente

1. Clone este repositório.
2. Acesse a pasta do projeto.
3. Abra o arquivo `index.html` no navegador.

Opcionalmente, você pode usar uma extensão como Live Server no VS Code para desenvolvimento local.

## Regras de conversão atuais

No arquivo `scripts.js`, as cotações fixas são:

- USD: 4.87
- EUR: 5.32
- GBP: 6.08

## Melhorias sugeridas

- Integrar API de câmbio para cotações em tempo real.
- Melhorar a validação do campo de valor (ex.: casas decimais e separadores).
- Adicionar testes de lógica para as funções de conversão.
- Incluir modo de acessibilidade com maior contraste e navegação por teclado aprimorada.

## Licença

Este projeto pode ser utilizado para fins de estudo e prática.
