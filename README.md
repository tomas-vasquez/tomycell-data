# TomyCell Data

Este repositorio contiene los datos en formato JSON utilizados para el sitio web de **TomyCell**, un servicio técnico de reparación de celulares y equipos electrónicos en Santa Cruz, Bolivia.

## Estructura de Datos

Los datos están organizados en el directorio `data/` y son agregados mediante `index.ts` o `index.js`.

### Archivos JSON

Se encuentran en `data/`:

- **`data/about.json`**: Información sobre la empresa, descripción y contadores de experiencia.
- **`data/business.json`**: Detalles de contacto, redes sociales, dirección física y estructura de sucursales (latitud/longitud).
- **`data/frequentQuestions.json`**: Preguntas frecuentes organizadas por categorías (servicio, precios, contacto).
- **`data/main.json`**: Datos principales de la página de inicio, estructurados por categorías de dispositivos (celulares, tablets, laptops, otros) y tipos de reparación.
- **`data/nav-links.json`**: Enlaces de navegación del menú.
- **`data/services.json`**: Descripción de los servicios ofrecidos (servicio técnico, venta de reacondicionados, compra de equipos averiados).
- **`data/testimonials.json`**: Testimonios de clientes.
- **`data/ubication.json`**: Información de ubicación para mapas y descripciones de los talleres.

## Uso

El archivo `index.ts` actúa como punto de entrada y exporta un objeto que contiene todos los datos:

```typescript
import data from './index';

// Ejemplo de acceso:
console.log(data.main.title);
```
