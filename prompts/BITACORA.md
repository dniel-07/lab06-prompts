# Bitacora de prompts
 
Laboratorio 06: Fundamentos de Ingenieria de Prompts.
 
Herramienta de IA usada: (escribe aqui cual usaste)
 
## Ejercicio 2: Tokens y ventana de contexto

| Texto | Caracteres | Tokens |
|-------|------------|--------|
| Los estudiantes programan en Java. | 35 | 7 |
| The students program in Java. | 31 | 6 |
| desafortunadamente | 20 | 5 |

 
## Ejercicio 3: Temperatura

| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|-------------|----------------|---------------------------|
| 0 | 100% | BiblioTec |
| 0.5 | 35.3% | BiblioTec, LibroYa, PrestaLibro |
| 1 | 44.5% | BiblioTec, LibroYa, PrestaLibro, LectoGo, PaginaLibre, NubeDeTinta |
| 1.8 | 32.2% | BiblioTec, LibroYa, PrestaLibro, LectoGo, PaginaLibre, NubeDeTinta |

 
## Ejercicio 4: Prompt vago vs estructurado
 
| Criterio | Prompt vago | Prompt estructurado |
|----------|-------------|---------------------|
| Menciona el objetivo del sistema | Sí | Sí |
| Menciona a los usuarios principales | No | Sí |
| Tiene exactamente 3 funcionalidades | No | Sí |
| Esta en 3 parrafos | No | Sí |
| Lo usaria en un informe real | No | Sí |


## Ejercicio 5: Anatomia de un prompt
 
| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol | Crea un programa en Java. |
| Instruccion | Actua como desarrollador Java. Crea un programa en Java. |
| Contexto | Actua como desarrollador Java. Crea un programa en Java para gestionar los productos de una tienda. |
| Ejemplo | … usando una clase Producto con los atributos codigo, nombre, precio y stock. |
| Formato | … Explica primero la estructura de la clase y luego presenta el codigo Java. Usa este estilo para los metodos: getPrecio(), setPrecio(double precio). |


## Ejercicio 6: Del prompt basico al profesional

```text
Actua como desarrollador Java. Crea un ejemplo de login para una
aplicacion de escritorio utilizando Swing. El usuario debe ingresar
correo y contrasena. Explica brevemente el funcionamiento y presenta
el codigo organizado por clases.

Mejora el codigo anterior con estas restricciones: no uses librerias
externas, valida que el correo contenga @ y que la contrasena tenga
al menos 8 caracteres, y muestra los mensajes con JOptionPane.
```
