### 1) Explique qual a função da Máquina Virtual Java (JVM).
  A máquina virtual Java (JVM) é uma máquina imaginária que emula uma aplicação em uma máquina real. É a JVM que permite a portabilidade do código Java, sendo uma      importante ferramenta para interpretar o código em Java e rodá-lo em qualquer plataforma.

### 2) Qual a diferença entre JRE e JDK?
  O JRE (Java Runtime Environment) contém tudo aquilo que um usuário comum precisa para executar uma aplicação Java, já o JDK (Java Development Kit) é composto pelo JRE   e um conjunto de ferramentas úteis ao desenvolvedor Java.

### 4) Compile o programa desenvolvido no exercício anterior. A seguir apague o arquivo .class gerado e tente executar o programa. O que aconteceu?
Sem o arquivo .class, o Java não consegue encontrar a classe para executá-la, causando um erro.

```
Erro: Não foi possível localizar nem carregar a classe principal BMQuest3
Causada por: java.lang.ClassNotFoundException: BMQuest3
```

### 5) Mude o nome do método “main” para “start”, compile e execute. O que aconteceu?
Ocorre um erro, pois A JVM não consegue identificar a presença do "main" o que torna incapaz a execução.

```
error: can't find main(String[]) method in class: BMAtividade3
```

### 7) Experimente escrever todo o programa anterior em maiúsculo, compile e execute. O que aconteceu?
Erro no de @GuiiAbreu:
```
.\BMQUEST7.java:1: error: class, interface, enum, or record expected
PUBLIC CLASS BMQUEST8{
^
.\BMQUEST7.java:4: error: class, interface, enum, or record expected
        SYSTEM.OUT.PRINTLN("S├âO PAULO");
        ^
.\BMQUEST8.java:5: error: class, interface, enum, or record expected
    }
    ^
3 errors
```

Erro no de @KarlosMessyas:
```
error: file not found: BMAtividade6.java
Usage: javac <options> <source files>
use --help for a list of possible options
```

### 8) Experimente salvar o arquivo com um nome diferente do nome da classe, compile e execute. O que aconteceu?
Erro no de @GuiiAbreu:
```
.\BMQUEST8.java:1: error: class BMQuest8 is public, should be declared in a file named BMQuest8.java
public class BMQuest8{
       ^
1 error
```
Erro no de @KarlosMessyas:
```
Error: Could not find or load main class MeuPrograma
Caused by: java.lang.ClassNotFoundException: MeuPrograma
```
