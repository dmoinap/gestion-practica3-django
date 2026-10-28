# Notas del despliegue simulado

## Objetivo
Verificar la ejecución de la aplicación Django y PostgreSQL
desde una carpeta externa al repositorio original.

## Procedimiento
1. Se creó la carpeta despliegue-practica3.
2. Se copiaron los archivos de configuración necesarios.
3. Se inició la aplicación mediante Docker Compose.
4. Se verificó el estado de los contenedores.
5. Se comprobó que PostgreSQL estuviera saludable y Django
   publicara el puerto 8000.

## Resultado
Los dos servicios se iniciaron correctamente desde la carpeta
de despliegue simulado. PostgreSQL presentó el estado healthy
y Django quedó disponible en el puerto 8000.

## Observaciones
Este procedimiento representa una simulación local de despliegue.
No corresponde a una publicación en un servidor externo.
