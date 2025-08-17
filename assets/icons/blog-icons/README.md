# Iconos del Blog - Guía de Uso

Esta carpeta contiene las imágenes PNG que se utilizan como iconos en las tarjetas del blog.

## Archivos de Iconos Requeridos

Los siguientes archivos PNG deben estar presentes en esta carpeta:

- `ley.png` - Artículo 1: Restorative Justice (Justicia Restaurativa)
- `huella.png` - Artículo 2: Criminalization of Poverty (Criminalización de la Pobreza)
- `privacidad.png` - Artículo 3: Surveillance & Technology (Vigilancia y Tecnología)
- `penademuerte.png` - Artículo 4: Death Penalty (Pena de Muerte)
- `pena.png` - Artículo 5: Juvenile Justice (Justicia Juvenil)
- `critico.png` - Artículo 6: Critical Thinking (Pensamiento Crítico)
- `media.png` - Artículo 7: Media Literacy & AI (Alfabetización Mediática e IA)

## Especificaciones Técnicas

- **Formato**: PNG con transparencia
- **Tamaño recomendado**: 120x120 píxeles (mínimo 60x60)
- **Color**: Preferiblemente negro o gris oscuro (se aplicará filtro blanco automáticamente)
- **Fondo**: Transparente

## Cómo Reemplazar Iconos

1. **Coloca tus imágenes PNG** en esta carpeta con los nombres exactos especificados arriba
2. **Asegúrate de que el nombre del archivo coincida exactamente** con el especificado
3. **La imagen se mostrará automáticamente** en el fondo verde de las tarjetas
4. **El CSS aplicará automáticamente un filtro** para hacer la imagen blanca

## Personalización

Si quieres cambiar los nombres de los archivos, edita el archivo `index.html` y actualiza las rutas en:
- Las etiquetas `<img>` de las tarjetas del blog (líneas ~55-175)
- El objeto `articlesData` en el JavaScript (líneas ~270-450)
- La imagen por defecto del modal (línea ~258)

## Notas Importantes

- **Las imágenes se redimensionan automáticamente**: 60x60px en las tarjetas, 80x80px en el modal
- **Se aplica un efecto hover** que escala la imagen ligeramente
- **El filtro CSS** hace que todas las imágenes se vean blancas sobre el fondo verde
- **Si las imágenes no se muestran**, verifica que:
  - Los nombres de archivo coincidan exactamente
  - Los archivos sean PNG válidos
  - Las rutas en el HTML y JavaScript estén correctas

## Ejemplo de Estructura

```
assets/icons/blog-icons/
├── ley.png
├── huella.png
├── privacidad.png
├── penademuerte.png
├── pena.png
├── critico.png
├── media.png
└── README.md
```

## Solución de Problemas

Si los iconos aparecen rotos o no se muestran:
1. Verifica que todos los archivos PNG estén en la carpeta correcta
2. Confirma que los nombres de archivo coincidan exactamente
3. Asegúrate de que los archivos PNG sean válidos y no estén corruptos
4. Revisa la consola del navegador para errores de carga de imágenes
