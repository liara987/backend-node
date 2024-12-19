# API em Node para upload Image com integração com Gemini para Geração de Descrição

Este projeto é um Backend desenvolvido em **Node.js** e permite o **upload de imagens** para um banco de dados **MongoDB**, além de integrar com a biblioteca **Gemini** para gerar descrições automáticas das imagens enviadas. O objetivo é fornecer uma solução completa que permita o armazenamento eficiente de imagens e a criação automática de descrições detalhadas para cada uma delas.

## Funcionalidades

- **Upload de Imagens**: Permite o envio de imagens para o banco de dados **MongoDB** para armazenamento seguro.
- **Geração de Descrição Automática**: Integração com o **Gemini** para analisar as imagens e gerar descrições precisas, ajudando na organização e catalogação das imagens.

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução JavaScript para servidores.
- **Express**: Framework web para criação de APIs.
- **MongoDB**: Banco de dados NoSQL utilizado para armazenar as imagens e suas informações associadas.
- **Gemini**: Biblioteca para gerar descrições automáticas das imagens carregadas.
- **Multer**: Middleware para lidar com upload de arquivos no servidor.

## Como Usar

1. Clone este repositório.
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Configure o MongoDB e crie uma instância no seu ambiente.
4. Preencha as variáveis de ambiente seguindo o modelo do **.env-example**
5. Execute o servidor:

```bash
npm run dev
```

6. Faça o post dos dados ou o upload de uma imagem através do Postman ou outra interface de API.

7. A imagem será armazenada no MongoDB e, em seguida, a integração com Gemini criará uma descrição detalhada da imagem.
