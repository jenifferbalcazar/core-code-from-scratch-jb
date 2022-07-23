## core-code-from-scratch-jb

### Software Development Fundamentals Bootcamp :rocket:

**Estudiante:** Jeniffer Balcazar Justiniano :arrow_up:

> SEMANA 1 - TAREAS

**N°1 - Lenguajes de programación compilados e interpretados**

**Compilado:** Es cuando se escribe un código y se necesita de un compilador para que así se cree un archivo (código de máquina) y se convierta en un ejecutable para poder verlo, lo bueno es que, no se envía el código fuente, se puede enviar el ejecutable y lo pueden ver. Lo malo es que, interesa mucho el tipo de máquina que tenga la otra persona o el SO, y que bueno, la compilación es un paso extra cada que se quiera hacer pruebas del programa. **Ej:** C, C++, Rust, Go, etc.

**Interpretado:** Es cuando se escribe un código y se ejecuta directamente. Lo bueno aquí, es que no importa mucho el tipo de máquina que tenga la persona que lo ejecutará, si se requiere probar el programa solo se corre y ya. Lo malo es que la otra máquina necesita de un intérprete y que se comparta la fuente de código completa. **Ej:** PHP, JavaScrip, TypeScript.

**N° 2 - ¿Java es un lenguaje interpretado, compilado o ambos?**

**Java es ambos:** Es compilado a un lenguaje intermedio llamado "bytecode" que luego es interpretado/compilado por el JVM(Java Virtual Machine). Los creadores querían crear un lenguaje compilado pero que éste se pudiera ejecutar en cualquier SO. Al momento de programar ya las líneas de código, es necesario instalar el JRE(Java Runtime Environment), que es el que se encarga de interpretar el bytecpde, e incluso el JDK(Java Development Kit) que incluye el compilador.

**N° 3 - Pseudocode Currency Converter EJERCICIO**

  1. START
  2. BTC                <-- 0,000044
  3. DOLLAR             <-- GET
  4. TOTAL_CONVERTER    <-- BTC * DOLLAR
  5. PRINT DOLLAR + "dollars are equal to" + TOTAL_CONVERTER + "BITCOINS."
  6. END
