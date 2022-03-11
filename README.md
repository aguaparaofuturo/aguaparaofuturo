#Site, Sistema e Webservice App

Repositório do site, sistema e webservice do aplicativo.

##Instalação
* git clone [git clone https://repositorio.cnmp.mp.br/mp/aguafuturo-mpmt.git](https://repositorio.cnmp.mp.br/mp/aguafuturo-mpmt.git)
* No terminal execute [npm](https://www.npmjs.com/get-npm): ***npm install***
* Criar a pasta **storage** na raiz do site com permissão de escrita (775)
* Entre na pasta do sistema
* Atribua permissão de escrita(775) na pasta **proxy/** dentro de sistema/ ***caso a pasta não exista, criei a pasta***
* Configure o arquivo **configs/dev.env** com os dados de acesso ao banco e url do sistema
* Restaure o banco de dados com o arquivo **aguaparaofuturo.sql**
* Acesse o sistema, usuário e senha padrão:
 - user:*ministerio*
 - pass:*ministerio*

###Configurações

As configurações de conexão de banco do sistema estão armmazenadas nos arquivos dentro da pasta *configs/* o arquivo *autoload.php* faz o carregamento das informações. 

Caso queira ter mais de uma configuração (ex.: desenvolvimento e produção) é só configurar os arquivos dentro da pasta *configs/* e alterar o arquivo *autoload.php*

* Configure o certificado de segurança (https), pois o aplicativo não se comunica sem isso.
* Configure o SMTP para envios de e-mail do sistema, no modulo Sistema->Configurações->Dados para envio de E-mails.

###Funcionalidades

. Adicionado ao sistema proteção nos formularios de login do sistema e de contato no site via reCAPTCHA v3.

###Dúvidas

Entrar em contato com: Wesley Ramalho - Consultor do Projeto Água para o Futuro 

(65)3611-0684 
wesley.ramalho@mpmt.mp.br

[Água para o Futuro](http://aguaparaofuturo.mpmt.mp.br)
