# Entrevista Zapay

Como usuário eu quero poder visualizar os débitos pendentes de pagamento do meu veículo.

https://www.figma.com/design/Ldo3CQbszUvDSVjABKcumm/Untitled?node-id=0-1&p=f&t=RNMQnrtmDOpMdino-0

## Critérios de aceite

- Usuário deve conseguir visualizar os débitos pendentes de pagamento
- Usuário deve conseguir selecionar e desselecionar os débitos
- Usuário deve conseguir visualizar o total dos débitos selecionados
- O botão Continuar deve exibir uma mensagem de alerta com o total dos débitos selecionados
- O botão Continuar deve ficar desabilitado quando não existirem débitos selecionados
- O usuário deve conseguir visualizar a tela exatamente como está no Figma (Pixel Perfect)

## Observações técnicas

### Os débitos do veículo devem ser obtidos através dessa API

```
GET https://681a03bd1ac115563507734a.mockapi.io/debs/v1/teste
```

### Bibliotecas já instaladas

```
"@tanstack/react-query": "^5.75.4",
"axios": "^1.9.0",
"lodash": "^4.17.21",
"styled-components": "^6.1.17",
"tailwindcss": "^4.1.5"
```
