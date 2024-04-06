# Infraestrutura-Como-C-digo-com-Serverless-Framework-na-AWS

**Criando um Projeto Serverless com o Serverless Framework e AWS**

Se você está pronto para dar seus primeiros passos na Nuvem da AWS, o **Serverless Framework** é uma excelente escolha. Ele permite criar e implantar aplicativos sem se preocupar com a infraestrutura subjacente. Vamos começar!

1. **Crie uma conta na AWS**:
   - Se você ainda não tem uma conta verificada na AWS, crie uma seguindo as instruções na [página de criação de conta da AWS](https://aws.amazon.com/pt/free/).
   - A conta precisa estar totalmente verificada para que possamos implantar nossos serviços Serverless.

2. **Instale o Serverless Framework**:
   - O Serverless Framework é um módulo NPM, portanto, você precisará ter o **Node.js** e o **NPM** instalados. Se ainda não os tem, siga as instruções para instalar o Node.js na [página oficial](https://nodejs.org/en/download/).
   - Após instalar o Node.js, execute o seguinte comando para instalar o Serverless Framework globalmente:
     ```
     npm install -g serverless
     ```

3. **Crie um novo serviço**:
   - O Serverless Framework facilita a criação de um novo serviço. No seu terminal, execute o seguinte comando:
     ```
     serverless
     ```
   - Isso iniciará um processo semelhante a um assistente para ajudá-lo a criar um novo serviço.
   - Escolha o tipo de template que deseja usar como base para o seu serviço. Para este tutorial, selecione a opção "AWS - Node.js - HTTP API".
   - Dê um nome ao seu novo serviço ou pressione "Enter" para manter o nome padrão (aws-node-http-api-project).
   - O Serverless Framework criará uma nova pasta com o mesmo nome do serviço e baixará o template relacionado à nossa escolha.

4. **Serverless Dashboard**:
   - O Serverless Dashboard é uma ferramenta fornecida pelo Serverless Framework para facilitar a gestão das conexões com a AWS.
   - Ele oferece recursos como gerenciamento de configurações, monitoramento e leitura de logs para suas funções Lambda.
   - Para este tutorial, usaremos o Dashboard para facilitar a conexão com nossa conta AWS durante a implantação.

https://github.com/cassianobrexbit/dio-live-serverless-2907
