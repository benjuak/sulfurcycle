Sulfur Cycle Mod - source
Autor: benjuak

Este ZIP contiene el código fuente del mod "Sulfur Cycle" (Fabric).
Para compilar necesitas:
- Java 17 instalado
- Gradle 7.6.x instalado y apuntado en IntelliJ
- Fabric Loom compatible (el proyecto ya usa fabric-loom 1.6-SNAPSHOT en build.gradle)

Pasos rápidos para compilar:
1) Abrir este proyecto en IntelliJ (File -> Open -> carpeta sulfurcycle_source)
2) Esperar a que Gradle importe el proyecto
3) Ejecutar en terminal: ./gradlew --refresh-dependencies
4) Ejecutar en terminal: ./gradlew build
5) El jar compilado estará en build/libs/sulfurcycle-1.0.0.jar

Notas:
- Este proyecto contiene implementaciones simplificadas (por ejemplo, ModWorldGen es un placeholder).
- Si al compilar hay errores de mappings (Yarn) o versiones, ajusta las versiones en build.gradle.
