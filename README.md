# Commands

**A simple script to run programs and commands from python.**

It gets the exit code and standard and error outputs.

It is a base for other programs to use it.

**Usage:** `commands.py [-h] [-e ENCODING] command`

**Positional arguments:**      
  *command*               
    Command to execute and its parameters, between quotation marks .

**Optional arguments:**     
  *-h, --help*   
    Show the help message.    

  *-e ENCODING, --encoding ENCODING*   
    Character encoding. Default: utf8.

**Example:** 

    python3 commands.py 'ls -l'

**Ouput example:**   

    Command: ls -l
    Success (exit code=0)
    Output:
    000: total 8
    001: -rw-rw---- 1 test test 3243 abr 20 15:34 commands.py
    002: -rw-r--r-- 1 test test  408 abr 20 14:20 readme.md

---

**Un script sencillo para ejecutar programas y comandos desde python.**

Captura el código de retorno devuelto por el programa, asi como la salida estándar y la salida de error.

Es una base para ser usada en otros programas.

**Uso:** `commands.py [-h] [-e ENCODING] command`

**Argumentos posicionales:**      
  *command*               
    Command to execute and its parameters, between quotation marks .

**Argumentos opcionales:**     
  *-h, --help*   
    Show the help message.    

  *-e ENCODING, --encoding ENCODING*   
    Character encoding. Default: utf8.

**Ejemplo:** 

    python3 commands.py 'ls -l'

**Ejemplo de salida:**   

    Command: ls -l
    Success (exit code=0)
    Output:
    000: total 8
    001: -rw-rw---- 1 test test 3243 abr 20 15:34 commands.py
    002: -rw-r--r-- 1 test test  408 abr 20 14:20 readme.md

