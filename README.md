# Evidencia de Aprendizaje 1 - Analista de Datos I

## Información del Grupo
* **Nombre del Grupo:** ByteWise Tech Group
* **Institución:** Instituto Superior Politécnico Córdoba (ISPC)
* **Carrera:** Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial
* **Módulo:** Analista de Datos I
* **Docente:** Pratta, Nahuel

## Integrantes
A continuación se detallan los miembros del equipo y sus respectivos perfiles de GitHub:

* **Astudillo, Matías** - [matiasAstudillo89](https://github.com/matiasAstudillo89)
* **Corvalán, Marcelo** - [MarceloCorvalan](https://github.com/MarceloCorvalan)
* **Darwich, Javier Lucas** - [lucasdarwich](https://github.com/lucasdarwich)
* **Delosanto, Adriel** - [adriel1364](https://github.com/adriel1364)
* **Martin, Mauro Leonel** - [Mauro-Martin](https://github.com/Mauro-Martin)
* **Scaranno, Gabriel** - [GaboScarano](https://github.com/GaboScarano)

---

## Proyecto Integrador: Análisis de Conectividad en Escuelas de Cordoba
Este repositorio contiene la primera evidencia de aprendizaje vinculada al proyecto integrador. El objetivo inicial es la gestión y exploración de un dataset que permita realizar análisis estadísticos y predictivos sobre la conectividad de las ecuelas en la provincia.

### Dataset Seleccionado
Para este proyecto se utiliza el dataset **"Escuelas Starlink"**, el cual cumple con los requisitos académicos solicitados (más de 8 variables y más de 400 registros).

* **Origen:** Reporte Interno
* **Formato:** `.csv`
* **Ubicación en el repo:** `/Datos/escuelas_starlink_github.csv`

### Variables de Interés
El dataset incluye, entre otras, las siguientes variables clave para el análisis:
1. **cui:** Codigo Unico de Identificacion (Cualitativa).
2. **cue:** Codigo Unico de Establecimiento (Cualitativa).
3. **nombre_escuela:** Nombre de la escuela (Cualitativa).
4. **nombre_utm:** Nombre del equipo UTM instalado (Cualitativa).
5. **periodo:** Mes al que corresponde el registro de datos. Permite analizar la evolución del tráfico en el tiempo (Cualitativa).
6. **modelo:** Modelo del dispositivo UTM desplegado (Cualitativa).
7. **mac_address:** Dirección MAC del equipo (Cualitativa).
8. **ip_publica:** IP asignada a la escuela para salida a internet (Cualitativa).
9. **latitud / longitud:** Coordenadas geográficas de la escuela, utilizadas para georreferenciación y visualización en mapas (Cuantitativa).
10. **direccion:** Ubicación geográfica (Cualitativa).
11. **bw_gb:** Tráfico total mensual consumido por la escuela, expresado en gigabytes (Cuantitativa).
12. **clientes:** Cantidad estimada de usuarios o dispositivos conectados en la red de la escuela (Cuantitativa).
13. **wan_appliances:** Cantidad de dispositivos conectados al enlace WAN  (Cuantitativa).
14. **wan_carrier:** Proveedor del servicio de conectividad (Cualitativa).
15. **access_points:** Cantidad de puntos de acceso WiFi dentro de la escuela (Cuantitativa).
16. **bw_educacion:**  Tráfico asociado a plataformas educativas, aulas virtuales y contenido pedagógico (Cuantitativa).
17. **bw_web:** Navegación general en internet (búsquedas, páginas informativas, etc.) (Cuantitativa).
18. **bw_streaming:** Consumo de contenido multimedia, principalmente video (YouTube, plataformas educativas audiovisuales) (Cuantitativa).
19. **bw_calls:** Tráfico de videollamadas y comunicaciones en tiempo real (Zoom, Meet, etc.) (Cuantitativa).
20. **bw_socialmedia:** Uso de redes sociales (Cuantitativa).
21. **bw_updates**	Consumo en actualizaciones de sistema (Cuantitativa).
22. **bw_otros**	Tráfico no categorizado o misceláneo (Cuantitativa).
---

## Estructura del Repositorio
* `Datos/`: Carpeta que contiene el archivo `.csv` con los datos originales.
* `README.md`: Descripción del proyecto e información del grupo.
