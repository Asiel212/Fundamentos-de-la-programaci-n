# ¿Que es programar?  
 Set de instrucciones que le damos a una maquina pero mas especificos

# Ejemplo

" Entrar a la casa "
 Pasos
 1- Acercarse a la puerta
 2- levantar la mano
 3- tomar la manilla
 4- Girar la manilla hacia la izquierda
 5- Empujar la pueerta
 6- Soltar la manilla
 7- caminar hacia adelante
 8- Darse la vuelta en 180 grados 
 9- Levantar la mano# 10- tomar la manilla
 11- Empujar la puerta suavemente hasta que tope

# ¿Que puede hacer una computadora? 

 Puede multiplicar, dividir, sumar, restar
 RECORDAR (nombre, correo electronico, dirección, etc)

# Herramienta para comunicarnos con el computador 

 Los lenguajes de programación 

# ¿Que es? 

- lenguaje formal
- Tiene reglas gramaticales definidas
- Nos permite entregarle instrucciones a una máquina

# Datos:         si asociamos muchos datos se convertira en            información:
36                                                                     36 años
Chanchito                                                              Chanchito feliz
Feliz   

#      actualmente no nos dice nada pero si los asociamos mas obtendremos datos mas especificos
Información:

Usuario:
     36 años
     chanchito feliz


# Ejemplo  dato                  información
dato: Salchicha  >  Información: perro salchicha 


# creación de variables
   x = 10              dato
edad = 10              información
cantidad = 10           dato

x = "Chanchito"
animal = "Chanchito"
menu = "Chanchito"
holamundo = "Chanchito feliz"

# Tipos de datos

animal = "perro" -> String osea texto
edad = 36 ->  integer osea un numero entero
harina = 3.5 -> float osea valor flotante
caracter = "a" -> char
Dormido = False -> boolean osea valor boleano solo puede tener 2 valores True o False

# Ejemplo
nombre = "Sung jin woo" -> string
mascotas = 5 -> integer
medidas = 5.5 -> Float
vivo = true 

# Funciones
Sirven para no crear un codigo tan grande
para facilitar la modificación del codigo

ejemplo: 

function EntrarALaCasa():

 1- Acercarse a la puerta.
 2- levantar la mano.
 3- tomar la manilla.
 4- Girar la manilla hacia la izquierda.
 5- Empujar la pueerta.
 6- Soltar la manilla.
 7- caminar hacia adelante.
 8- Darse la vuelta en 180 grados.
 9- Levantar la mano# 10- tomar la manilla.
 11- Empujar la puerta suavemente hasta que tope.

como llamamos a la funcion?

facil solo escribiendo el nombre de la función con parentesis

EntrarALaCasa()

# Algoritmos

Function PasarALaCasa():
     1. Acercarse a la puerta.
     2. Patear muy fuerte. 
     3. Caminar hacia adelante


function EntrarALaHome():
     1. Correr en dirección a la ventana
     2. Saltar
     3. Hacerse bolita
     
Los algoritmos dependen del contexto del que nosotros queramos ejecutar


# Orientación a objetos

una forma de como poder resolver problemas

Class Personas {                                  CLASE            
      edad: integer
      nombre: string
      colorCabello: string
      Decirnombre():                            Esto es un metodo la cual todos los objetos de la misma clase 
          habla {tu nombre}                                seran afectados por el
}  
   
personaChanchito = New person(                              OBJETO        INSTANCIA DE LA CLASE PERSONA
    Edad: 36                       
    nombre: chanchito
    colorCabello: castaño
)

PersonaFelipe = Nwe person(
    Edad: 22
    Nombre: Felipe
    ColorCabello: rubio
)

SIRVE PARA ESCRIBIR MENOS CODIGO Osea duplicidad de codigo

Function PasarALaCasa(Personas):
        if persona.edad > 17:
               correr hacia la ventana
               saltar
               hacerse bolita
        else:
              vete de aqui

# Paradigma 


 Filosofia de como se debe resolver algo
  funcional himperativo estructurado y orientado a objetos
  Preferencia de como resolver algo


# BUGS
 Function entrarALaCasa(persona):
           Acercarse a la puerta 
           caminar hacia adelante
           
        ERROR: PUERTA CERRADA