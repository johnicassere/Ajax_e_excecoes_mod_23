# Ajax_e_excecoes_mod_23

**Explore a comunicação entre Front-End e Back-End**

**URL**

URL é a abreviação de Uniform Resource Locator. É um endereço único e padronizado que identifica um recurso na internet. Uma URL é usada para acessar diferentes tipos de recursos, como páginas da web, imagens, arquivos, vídeos, serviços web, entre outros.

___https://meusite.com.br___/produtos?***marca=nike&tamanho=39***

____Base URL____/          ___Recurso___/   ___Query parameters___

https://admin.meusite.com.br


**HTTP**

HTTP é a abreviação de Protocolo de comunicação utilizado para transferir dados na World Wide Web (WWW). É a base para a comunicação entre um cliente (geralmente um navegador web) e um servidor web. Permite que os clientes solicitem recursos, como páginas da web, imagens, arquivos, vídeos e serviços, por meio de URLs (Uniform Resource Locators). Ele define uma estrutura para a troca de mensagens entre o cliente e o servidor.

Uma chamada HTTP é composta por:

- método/verbo;
- headers/cabeçalhos;
- body (opcional).

Os principais verbos HTTP são:

**GET:** utilizado para solicitar um dado do servidor;
**POST:** quando desejamos enviar dados para o servidor;
**PUT:** utilizado para alterar todos os dados de uma informação;
**PATCH:** utilizado para alterar parcialmente os dados de uma informação;
**DELETE:** utilizado para deletar um recurso.

~~~
Uma resposta HTTP é composta por:
- status code;
- headers/cabeçalhos;
- body (opcional).

Quando fazemos uma requisição HTTP, obrigatoriamente teremos um código de status da requisição, informando se ela deu certo ou não. Também chamamos esses códigos de “status code”. Esses status codes respeitam um intervalo desta forma:

• 100 – 199: indica um status de informação; 
• 200 – 299: indica um status de sucesso; 
• 300 – 399: indica um status de redirecionamento; 
• 400 – 499: indica um status de erro por parte do cliente 
• 500 – 599: indica um erro por parte do servidor.

Os status codes mais comuns estão em 2XX, 4xx e 5XX. Exemplos:
Quando solicitamos um recursos que não existe ao servidor recebemos um status code 404, que indica um erro por parte do cliente, do solicitante.
~~~

**Json**

JSON é a abreviação para JavaScript Object Notation. 
Conjunto chave-valor 
```
   { 
    "nome": "Gian Souza" 
    }
```

**API Rest**

API é a abreviação para Application Programming Interface. REST é a abreviação para Representational State Transfer.

Máprática:

https://meusite.com/ produtos 
https://meusite.com/produtos/novo 
https://meusite.com/produtos/editar 
https://meusite.com/produtos/deletar


Boa prática:

**GET -** https://meusite.com/produtos

**POST -** https://meusite.com/produtos

**PUT -** https://meusite.com/produtos

**DELETE -** https://meusite.com/produtos