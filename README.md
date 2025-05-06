# OndaHertz.es - Contenido Autogenerado por Inteligencia Artificial

Bienvenido al repositorio de OndaHertz.es, un blog dedicado al fascinante mundo de la radioafición. Este proyecto utiliza tecnologías de inteligencia artificial para generar contenido y mejorar la experiencia del usuario. Con un enfoque principal en España, pero cubriendo temas de todo el mundo, OndaHertz.es es una ventana al mundo de las comunicaciones por radio.  

## Descripción General

OndaHertz.es utiliza el generador de sitios estáticos Jekyll con el tema 'YAT' (Yet Another Theme) para ofrecer una experiencia atractiva y enriquecedora. Este proyecto es un ejemplo de cómo la tecnología y la creatividad pueden unirse para ofrecer contenido de calidad, completamente autogenerado por inteligencia artificial.  

## Tecnologías Utilizadas

- **Jekyll**: Un generador de sitios estáticos simple pero poderoso, ideal para sitios personales, proyectos o blogs especializados. [Más información sobre Jekyll](https://jekyllrb.com/)  
- **Tema**: Tema YAT (Yet Another Theme) de Jekyll, creado por [jeffreytse/jekyll-theme-yat](https://github.com/jeffreytse/jekyll-theme-yat).  
- **Generación de Contenido por IA**: Los textos son generados dinámicamente mediante la API de OpenAI.  
- **Generación de Imágenes**: Cada entrada de contenido incluye una imagen relacionada creada con DALL-E.  
- **Hosting**: El sitio está alojado en GitHub Pages.  

## Flujo de Trabajo

1. **Gestión de Temas**:
   - Los temas principales se extraen de `AI_content/list_of_NEW_topics.csv`.
   - Si no hay temas disponibles, el sistema genera automáticamente 10 nuevos temas relacionados con la radioafición.

2. **Generación de Contenido e Imágenes**:
   - Cada tema activa la API de OpenAI para generar contenido textual, mientras que DALL-E crea imágenes adecuadas al tema.

3. **Composición de las Páginas**:
   - Las páginas se generan de forma periódica, incorporando contenido textual y visual, y luego se actualizan en el sitio web.

## Contribuciones

¡Tus contribuciones son bienvenidas! Si tienes ideas para mejoras o detectas algún problema, no dudes en hacer un fork del repositorio y enviar un pull request.  

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Los detalles completos se encuentran en el archivo [LICENSE](LICENSE.txt).  

## Contacto

Si tienes alguna pregunta o sugerencia, puedes contactar con Andrea Gigante a través de [LinkedIn](https://www.linkedin.com/in/agigante/).  
