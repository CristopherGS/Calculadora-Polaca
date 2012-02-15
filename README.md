#Calculadora Polaca
========
   Pr&aacutectica 1.3 realizada para la materia Organizaci�n de computadores.

  **Por:**
   *    Esteban Arango Medina
   *    Daniel Duque Tirado
   *     Daniel Zuluaga Suarez

Esta pr�ctica fue realizada en el lenguaje *assembler* de procesadores Intel para Linux, usando el compilador NASM ([The net wide assembler](http://repo.or.cz/w/nasm.git "NASM git")).

###Instalaci�n NASM
 Para la instalaci�n de NASM en las distribuciones Debian y Ubuntu basta con abrir la 'terminal' y escribir:
    
	$ sudo apt-get install nasm

###__Ejecuci�n__
 Para correr la Calculadora simplemente 'compilamos' *Calculadora.asm* y creamos el paquete ejecutable.
    
	nasm -f elf Calculadora.asm 
    ld Calculadora.o -o Calculadora
    ./Calculadora`
