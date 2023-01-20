# hands-on-t2-neo
Repositório do time Neo (turma 2) para o projeto do Hands On

# COMO INCIAR A APLICAÇÃO

## Banco de dados

É necessário adequar o banco de dados para iniciar a aplicação, no prompt de comandos digite:
```
mysql < database-create.sql -u root -p && echo Banco de dados modificado com sucesso
```

## Back-end

Para iniciar o back-end da aplicação, no prompt de comandos digite:
```
cd back-end
```
```
mvn spring-boot:run
```
O mesmo irá iniciar no endereço http://localhost:8080, com acesso local a base de dados MySQL, por meio da porta padrão 3306.


## Front-end

É necessário também instalar as dependências do projeto, no prompt de comandos digite:
```
cd front-end
```
```
npm install
```
Para iniciar o front-end da aplicação, no prompt de comandos digite:
```
ng serve
```
A aplicação vai iniciar no endereço http://localhost:4200.



# FERRAMENTAS

- *Railway*
  - Plataforma que será utilizada para deploy da aplicação back-end.
  - Criar uma conta: https://railway.app/
  - Outras alternativas: https://github.com/Engagespot/heroku-free-alternatives
- *Visual Studio Code*
  - https://code.visualstudio.com/Download
  - *Extensões*
    - *Extension Pack for Java (Extensão do VS Code)*
      - https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack
    - *Spring Boot Extension Pack (Extensão do VS Code)*
      - https://marketplace.visualstudio.com/items?itemName=pivotal.vscode-boot-dev-pack
    - *Thunder Client (Extensão do VS Code)*
      - https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client
    - *XML (Extensão do VS Code)*
      - https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml
    - *Angular Language Service (Extensão do VS Code)*
      - https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack
- *Git*
  - https://git-scm.com/downloads
- *JDK 17*
  - Para verificar se o JDK está corretamente instalado e configurado, digite no prompt de comandos:
    - javac -version
  - Se necessário, realizar a instalação e configuração:
    - Link para download: https://www.oracle.com/br/java/technologies/javase/jdk17-archive-downloads.html
    - Criar a variável de ambiente JAVA_HOME configurada para o diretório de instalação do JDK. Exemplo: “C:\Program Files\Java\jdk-17.0.6”.
    - Adicionar “%JAVA_HOME% bin” na variável de ambiente PATH.
    - Tutorial de configuração: https://mkyong.com/java/how-to-set-java_home-on-windows-10/
- *Maven*
  - Para verificar se o Maven está corretamente instalado e configurado, digite no prompt de comandos:
    - mvn -version
  - Se necessário, realizar a instalação e configuração:
    - Link para download: https://dlcdn.apache.org/maven/maven-3/3.8.6/binaries/apache-maven-3.8.6-bin.zip
    - Adicionar o diretório de instalação do Maven na variável de ambiente PATH. Exemplo: “C:\apache-maven\bin”.
    - Tutorial de instalação: https://mkyong.com/maven/how-to-install-maven-in-windows/
- *Node.js (e npm)*
  - Versão 14.15 ou superior.
  - Para verificar a versão do Node.js, no prompt de comandos digite:
    - node --version
  - Link para download (escolha a versão LTS): https://nodejs.org/en/download/
- *Angular CLI:*
  - Versão 14.0 ou superior.
  - Para verificar a versão do Angular CLI, no prompt de comandos digite:
    - ng --version ou ng version
  - Tutorial de instalação: https://angular.io/guide/setup-local
  - Para instalar o Angular CLI, no prompt de comandos digite:
    - npm install -g @angular/cli
- *SQL:*
  - Para conectar no MySQL, no prompt de comandos digite:
    - mysql -u root -p
  - Se necessário, realizar a instalação:
    - Link para download: https://dev.mysql.com/downloads/file/?id=512698
    - [Tutorial de instalação](https://github.com/webacademyufac/frameworks-back-end/blob/main/tutoriais/mysql/mysql.md)
  - Se necessário, resetar a senha de root:
    - Tutorial: https://dev.mysql.com/doc/mysql-windows-excerpt/8.0/en/resetting-permissions-windows.html
