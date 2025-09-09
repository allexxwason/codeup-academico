Sistema Académico CodeUp
📌 Requisitos

Java 17

Maven

Git

# Clonar el repositorio
git clone git@github.com:allexxwason/codeup-academico.git

cd codeup-academico

# Compilar el proyecto
mvn compile

# Ejecutar la clase principal
mvn exec:java -Dexec.mainClass="com.codeup.academico.App"

🚀 Ejemplo de uso

El sistema ya incluye una entidad Estudiante en com.codeup.academico.domain.
Puedes probarla modificando la clase App.java:

package com.codeup.academico;

import com.codeup.academico.domain.Estudiante;

public class App {
    public static void main(String[] args) {
        System.out.println("Sistema Académico CodeUp iniciado correctamente 🚀");

        Estudiante estudiante = new Estudiante("001", "Alex");
        System.out.println("Nuevo estudiante creado: " + estudiante.getId() + " - " + estudiante.getNombre());
    }
}

Al ejecutar, verás en consola:

Sistema Académico CodeUp iniciado correctamente 🚀
Nuevo estudiante creado: 001 - Alex

Estructura inicial

src/main/java/com/codeup/academico
 ├─ domain
 ├─ ui/console
 └─ App.java

 
