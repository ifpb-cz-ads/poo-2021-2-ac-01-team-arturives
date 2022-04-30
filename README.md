1 - O JVM (Java Virtual Machine) é uma máquina virtual, um software que
simula uma máquina física, que gerencia processos, memórias e arquivos,
compreendendo o ByteCode, gerado pelo JAVAC, traduzindo esse código para
cada máquina, proporcionando ao DEV portabilidade do código em qualquer 
sistema operacional, dando origem aquele ditado que o DEV que trabalha em
Java só precisa escrever seu código uma única vez e pode executá-lo em 
qualquer máquina.

2 -	O JRE é uma implementação do JVM responsável por executar os
programas em Java, sendo assim, um plugin necessário para a sua execução.
	O JDK é um pacote de softwares que são utilizados para desenvolver
aplicações em Java, por isso é tratado como um kit de desenvolvimento, como
dito na própria sigla que deriva do nome Java Development Kit.

3 - public class program {

    public static void main(String[] args){
        System.out.println("Terminei a primeira aula com um programa Java!");
    }
}

4 - O terminal retornou a seguinte mensagem:
 Erro: Não foi possível localizar nem carregar a classe principal program
 Causada por: java.lang.ClassNotFoundException: program 

A medida que eu apago o arquivo, a JVM nao consegue mais localiza-lo 
para executar o programa ou classe em questao, tendo em mente que para
cada Classe declarada dentro do arquivo com extensao .java, sera gerado 
um bytecode com extensao .class diferente
