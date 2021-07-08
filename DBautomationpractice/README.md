﻿Softwares necessários:
IDE: [Eclipse](http://www.eclipse.org/)
Java: [Java](http://www.oracle.com/technetwork/pt/java/index.html)
Mozilla Firefox: [Mozilla](https://www.mozilla.org/pt-BR/firefox/new/)

**Preparação do ambiente - Passo a Passo:**
 1. Baixe e instale o Eclipse;
 2. Baixe e instale o Java: JRE e JDK;
 3. Baixe e instale o Mozilla Firefox;
 4. Configure o Java no Windows 10: vá até o Painel de Controle > Sistema e Segurança > Sistema;
 5. Clique em "Configurações avançadas do sistema";
 6. Clique em "Variáveis de Ambiente...";
 7. Clique no botão “Nova” em “Variáveis do sistema”;
 8. Digite no nome da variável: "JAVA_HOME";
 9. No valor da variável: coloque o endereço onde foi instalado. Exempo: “C:\Program Files\Java\jdk1.8.0_251”;
 10. Clique em "OK";
 11. Progure por "Path" e selecione depois clique em "Editar...";
 12. Clique em "Novo" e digite "%JAVA_HOME%\bin" depois clique em "OK";
 13. Clique em "OK" novamente para salvar as configurações;
 14. Para confirmar se foi configurado certo e a verificar a versão, vá ao CMD(Prompt de comando) e digite "java -version"

**Executando o script - Passo a Passo:**
 1. Baixe o projeto e descompacte-o;
 2. Acesse o Eclipse;
 3. Dentro do eclipse clique em "File" e depois em "Open Projects from File System...";
 4. Em Import source, digite o endereço do projeto. Exemplo: "C:\Projects\DBautomationpractice". Ou clique em "Directory" e selecione a pasta do projeto "DBautomationpractice" e clique em "OK";
 5. Clique em "Finish" e espere o projeto carregar;
 6. É possível que as classes do JUnit não sejam encontradas. Caso isso aconteça, clicar com o botão direito no projeto (item mais acima na árvore na esquerda) e "Build Path" depois em "Add Libraries" escolha "JUnit" depois clique em "Next" e depois em "Finish";
 7. Após, clique em "src/test/java";
 8. Clique no pacote "testcase" e no codigo mude o nome no email linha "newUser.newAccount("nikolasbbbbbs@dbteste.com");" para um nome qualquer;
 9. Após, clique no pacote "testsuites" e com o botão direito sobre o regressionTestSuite.java e selecione "Run As" e após "JUnit Test";
 10. Na primeira vez de excução o teste poderá falhar pois precisa atualizar o navegador para o teste, aguarde a atualização;
 11. Após terminada execute novamente o teste;
 12. Espere o caso de teste ser executado no navegador web;
 13. Ao terminar e a barra de status do JUnit ficar verde, acesse a pasta do projeto e clique em "reports" e clique para abrir o report.html no navegador web, você poderá verificar o resultado gerado.
 
