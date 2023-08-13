# GymPredict

**Autores:** 
- Carlos Beytía
- Nicolás Nazar
- Vicente Olmos

## Descripción del Proyecto

GymPredict es un proyecto de Minería de Datos que tiene como objetivo analizar y predecir los mejores horarios para asistir al gimnasio. Utilizando datos de aforo recolectados durante un período determinado, esta herramienta proporciona recomendaciones sobre cuándo el gimnasio es menos concurrido, facilitando así la planificación de las visitas de los usuarios.

## Origen de los Datos

Los datos utilizados en GymPredict fueron obtenidos de la API del gimnasio Energy y corresponden al período de marzo a mayo de 2023. Si se desea obtener predicciones más actualizadas y precisas, es posible usar datos propios. Se recomienda que estén en el siguiente formato: 

```plaintext
aforo;Lunes;Martes;Miércoles;Jueves;Viernes;Sábado;Domingo;Hora
```

## Instalación y Uso

1. Es necesario contar con [Jupyter Notebook](https://jupyter.org/install) instalado. Si no se tiene, es posible instalarlo mediante pip:
```bash
pip install notebook
```
2. Se debe clonar el repositorio del proyecto o descargar los archivos.
3. Luego, abrir Jupyter Notebook en el equipo y navegar hasta el directorio donde se guardó el proyecto.
4. Finalmente, abrir el archivo `.ipynb` correspondiente para acceder al análisis y las recomendaciones.

## Conclusiones y Resultados

Se implementaron y evaluaron dos modelos: Regresión Polinomial y Máquinas de Vectores de Soporte (SVM). Aunque el modelo SVM demostró tener una precisión ligeramente superior, se consideró que la Regresión Polinomial es más adecuada para el proyecto por razones prácticas y operativas.

## Contribuciones

Si bien GymPredict fue desarrollado por el equipo mencionado, están abiertos a sugerencias y mejoras. Si tiene ideas o detecta áreas de mejora, se le invita a comunicarse o enviar una solicitud de pull.

## Contacto

Para consultas o comentarios relacionados con GymPredict, se puede contactar a cualquiera de los autores mencionados.

## Agradecimientos

Se agradece al gimnasio Energy por brindar acceso a su API, permitiendo realizar este análisis.

