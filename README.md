# Agendamento-Barber ✂️💈
Agendamento de serviços para barbearia com integração ao WhatsApp, desenvolvido em React com Material-UI.

## Funcionamento

Este projeto permite que os clientes agendem serviços em uma barbearia preenchendo um formulário com as seguintes informações:
- Nome
- Telefone
- Serviço desejado (opções: Cabelo, Barba, Sobrancelha, Cabelo + Barba, Cabelo + Sobrancelha, Cabelo + Barba + Sobrancelha)
- Data
- Horário (selecionado a partir de horários disponíveis)

Ao clicar em "Enviar para WhatsApp", a mensagem formatada com os detalhes do agendamento é aberta no WhatsApp para confirmação.

## Tecnologias Utilizadas

- React
- Material-UI

# Agendamento de Serviços para Barbearia

## Instalação

Para rodar este projeto localmente, siga os passos abaixo:

1. Clone o repositório:
   ```
   git clone https://github.com/seu-usuario/agendamento-barbearia.git
   ```

2. Navegue até o diretório do projeto:
   ```
   cd agendamento-barbearia
   ```


3. Instale as dependências:

   ```
   npm install react-router-dom

   npm install @mui/material @emotion/react @emotion/styled

   ``` 

4. Inicie o servidor de desenvolvimento:
   ```
   npm start
   ```

5. Abra o navegador e acesse `http://localhost:3000` para visualizar o projeto.

## Estrutura de Arquivos

A estrutura de arquivos do projeto é organizada da seguinte maneira:

```
agendamento-barbearia/
│
├── public/
│ ├── index.html
│ └── ...
│
├── src/
│ ├── components/
│ │ ├── BookingForm.js
│ │ └── ...
│ ├── App.js
│ ├── index.js
│ └── ...
│
├── package.json
└── ...
```


- **`public/`**: Contém o arquivo HTML principal e outros recursos estáticos.
- **`src/`**: Contém o código-fonte do projeto.
  - **`components/`**: Componentes React, incluindo `BookingForm.js` para o formulário de agendamento.
  - **`App.js`**: Componente principal que renderiza o aplicativo.
  - **`index.js`**: Ponto de entrada do React.

## Funcionamento

Este projeto permite que os clientes agendem serviços em uma barbearia preenchendo um formulário com as seguintes informações:
- Nome
- Telefone
- Serviço desejado (opções: Cabelo, Barba, Sobrancelha, Cabelo + Barba, Cabelo + Sobrancelha, Cabelo + Barba + Sobrancelha)
- Data
- Horário (selecionado a partir de horários disponíveis)

Ao clicar em "Enviar para WhatsApp", a mensagem formatada com os detalhes do agendamento é aberta no WhatsApp para confirmação.

## Tecnologias Utilizadas

- React 
- Material-UI


## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests com melhorias, correções de bugs, ou novos recursos.

## Licença

Este projeto está licenciado sob a [MIT License](https://opensource.org/licenses/MIT).
