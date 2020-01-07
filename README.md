# **Desafio Devops - OW Interactive**


## **Sobre a OW Interactive**

Fazemos parte do universo digital, focada em criar e desenvolver experiências interativas, integrando planejamento, criatividade e tecnologia. Conheça mais sobre nós em: [OW Interactive - Quem somos](http://www.owinteractive.com/quem-somos/).


## **Pré-requisitos**



*   Docker
*   Servidor NGINX
*   Codificação da disponibilização e consumo do JSON


## **Desafio**

 \
O objetivo do desafio é criar e desenvolver uma comunicação entre uma aplicação backend que irá disponibilizar um JSON através de uma URL que será consumido por uma outra aplicação frontend e a mesma deve mostrar esse resultado em um endereço acessível através de um browser.

Obs:



*   A aplicação backend obrigatoriamente deve utilizar PHP
*   A aplicação frontend obrigatoriamente deve utilizar Node
*   Deve ser disponibilizada uma documentação de como rodar o ambiente


### **Etapa 1 - Aplicação Backend**



*   Construir um docker com os seguintes requisitos obrigatórios:
    *   PHP >= 7.*
        *   Bibliotecas que devem ser instaladas no PHP: \
bz2, calendar, Core, ctype, curl, date, dom, exif, fileinfo, filter, ftp, gd, gettext, gmp, hash, iconv, imagick, intl, json, libxml, mbstring, mcrypt, mysqli, mysqlnd, openssl, pcntl, pcre, PDO, pdo_mysql, pdo_sqlite, Phar, posix, readline, Reflection, session, shmop, SimpleXML, soap, sockets, SPL, sqlite3, standard, sysvmsg, sysvsem, sysvshm, tokenizer, wddx, xml, xmlreader, xmlwriter, xsl, zip, zlib
    *   MariaDB >= 10.*
    *   Redis >= 5.*
    *   Nginx >= 1.13.*

**A aplicação deve ser acessado a partir do endereço [localhost:8000](http://localhost:8000)**

**Diferenciais:**



1. **Disponibilizar uma página com o resultado do comando phpinfo().**
2. **Criar a aplicação utilizando o framework Laravel.**
3. **O container da aplicação depender do container do banco de dados, então enquanto o container do banco de dados não estiver pronto ou ocorra algum erro na execução o container com a aplicação não poderá ser iniciado.**
4. **No desenvolvimento do JSON disponibilizado utilizar de alguma forma o MariaDB ou Redis.**


### **Etapa 2 - Aplicação Frontend**



*   Construir um docker com os seguintes requisitos obrigatórios:
    *   Node >= 8.*
    *   Redis >= 5.*

**A aplicação deve ser acessado a partir do endereço [localhost:3000](http://localhost:3000) \
**

**Diferenciais:**



1. **Criar a aplicação utilizando o framework Nuxt.JS.**
2. **Consumir o JSON que vem da aplicação backend utilizando a biblioteca Axios.**
3. **No desenvolvimento do consumo do JSON utilizar de alguma forma o Redis.**


### **Etapa 3 - Documentação**

Disponibilizar na raiz do projeto um arquivo README.md com as instruções de como rodar o projeto e mais alguma informação se necessário.

**Diferenciais:**



1. **Esperamos que o processo para rodar o projeto seja apenas o comando: \
docker-compose up -d**
2. **Adicionar ao documento README.md o por que usou X tecnologia para criar as aplicações frontend e backend.**

**	**


### **Finalização**

Crie um fork e submeta ao Github o seu desafio. Após isso envie um e-mail para [letsrock@owinteractive.com](mailto:letsrock@owinteractive.com), com o assunto [DESAFIO DEVOPS] com o link para o seu desafio. Obrigado por disponibilizar um tempo para participar e boa sorte =)


<!-- Docs to Markdown version 1.0β17 -->
