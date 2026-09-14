# Markdown

Objetivos de aprendizaje

- Usar Markdown para agregar listas, imágenes y vínculos en un archivo de texto o comentario.
- Saber dónde y cómo usar Markdown en un repositorio de GitHub.
- Conocer las extensiones de sintaxis disponibles en GitHub (Markdown de tipo GitHub).

Usar la cursiva en el texto es tan fácil como poner el texto de destino entre asteriscos (*) o guiones bajos (_)
This is *italic* text.
This is also _italic_ text.

Cree texto en negrita usando dos asteriscos (**) o dos subrayados (__).
This is **bold** text.
This is also __bold__ text.

Para usar un asterisco literal, anteponga un carácter de escape; en GFM, es una barra diagonal inversa ( \ ). Esto muestra los caracteres de subrayado y los asteriscos como texto sin formato.

\_This is all \*\*plain\*\* text\_.

#### Declarar encabezados
HTML proporciona encabezados de contenido, como la etiqueta < h1 >. En Markdown, esto se realiza a través del símbolo #. Use una sola almohadilla (#) por cada nivel de encabezado del 1 al 6.

###### This is H6 text

#### Vínculo a imágenes y sitios
Los vínculos de imagen y sitio siguen una estructura similar.
```text
![Link an image.](/learn/azure-devops/shared/media/mara.png)
```
![Link an image.](/learn/azure-devops/shared/media/mara.png)

\[Link to Microsoft Training](/training)
[Link to Microsoft Training](/training)


Las tablas se pueden construir mediante una combinación de canalizaciones (|) para saltos de columna y guiones (-) para designar la fila anterior como encabezado.
First|Second
-|-
1|2
3|4

Puede crear citas en bloque con el carácter "mayor que" (>).
> This is quoted text.
