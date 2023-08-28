# Librería Generadora de Contraseñas Aleatorias

Genera contraseñas aleatorias seguras en Java con esta librería. Incluye métodos para crear contraseñas de letras, números y combinaciones aleatorias. Fácil de integrar en tus proyectos.

## Características

- `LetrasAleatorias`: Genera letras aleatorias para contraseñas únicas.
- `NumerosAleatorios`: Crea contraseñas numéricas aleatorias en un rango especificado.
- `CombinacionAleatoria`: Combina letras, números y caracteres especiales para contraseñas fuertes.

## Requisitos

Necesitas tener instalado el JDK (Kit de Desarrollo de Java) en tu sistema para usar esta librería.

## Uso Rápido

```java
import LibreriaContraseñas.LetrasAleatorias;
import LibreriaContraseñas.NumerosAleatorios;
import LibreriaContraseñas.CombinacionAleatoria;

public class Main {

    public static void main(String[] args) {
        // Generar contraseña de letras aleatorias
        String letras = LetrasAleatorias.generarLetrasAleatorias(10);
        System.out.println("Contraseña de letras aleatorias: " + letras);

        // Generar contraseña de números aleatorios
        String numeros = NumerosAleatorios.generarNumerosAleatorios(8, 0, 9);
        System.out.println("Contraseña de números aleatorios: " + numeros);

        // Generar combinación aleatoria de caracteres
        String combinacion = CombinacionAleatoria.generarCombinacionAleatoria(12);
        System.out.println("Contraseña de combinación aleatoria: " + combinacion);
    }
}

## Información Legal

Esta librería está reservada con todos los derechos de autor. Es una tarea calificable para la clase de Desarrollo de Software de la Universidad del Sinú. El archivo puede ser modificado en el futuro como parte de los requisitos académicos. 

## Contacto

Si tienes preguntas o sugerencias, puedes contactarme en valentinasalgadoblandon16gmail.com
