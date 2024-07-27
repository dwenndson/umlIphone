"# umlIphone" 

# Projeto iPhone

## Diagrama UML

![Diagrama UML do iPhone](diagrama_UML_iphone.svg)

Este é o diagrama UML do iPhone baseado na apresentação de 2007.

## Classes e Interfaces

### iPhone.java

```java
public class iPhone {
   
    private String versao;

    public iPhone(String versao) {
        this.versao = versao;
    }

    public void ligar() {
        System.out.println("iPhone ligado");
    }

    public void desligar() {
        System.out.println("iPhone desligado");
    }

    public void reiniciar() {
        System.out.println("iPhone reiniciado");
    }
}
