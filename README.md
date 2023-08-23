# 1) Explique qual a função da Máquina Virtual Java (JVM).
  A máquina virtual Java (JVM) é uma máquina imaginária que emula uma aplicação em uma máquina real. É a JVM que permite a portabilidade do código Java, sendo uma      importante ferramenta para interpretar o código em Java e rodá-lo em qualquer plataforma.

# 2) Qual a diferença entre JRE e JDK?
  O JRE (Java Runtime Environment) contém tudo aquilo que um usuário comum precisa para executar uma aplicação Java, já o JDK(Java Development Kit) é composto pelo JRE   e um conjunto de ferramentas úteis ao desenvolvedor Java.

# 4)  Compile o programa desenvolvido no exercício anterior. A seguir apague o arquivo .class gerado e tente executar o programa. O que aconteceu?
Sem o arquivo .class, o Java não consegue encontrar a classe para executá-la, causando um erro.

```
PS C:\Users\guilh\OneDrive\Documentos\ADS IFPB\POO> java BMQuest3       
Erro: Não foi possível localizar nem carregar a classe principal BMQuest3
Causada por: java.lang.ClassNotFoundException: BMQuest3
```
