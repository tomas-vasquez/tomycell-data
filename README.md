# TomyCell Data

Este repositorio contiene los datos en formato JSON utilizados para el sitio web de **TomyCell**, un servicio técnico de reparación de celulares y equipos electrónicos en Santa Cruz, Bolivia.

## Estructura de Datos

Los datos están organizados en varios archivos JSON que son agregados mediante `index.ts`.

### Archivos JSON

- **`about.json`**: Información sobre la empresa, descripción y contadores de experiencia.
- **`business.json`**: Detalles de contacto, redes sociales, dirección física y estructura de sucursales (latitud/longitud).
- **`frequentQuestions.json`**: Preguntas frecuentes organizadas por categorías (servicio, precios, contacto).
- **`main.json`**: Datos principales de la página de inicio, estructurados por categorías de dispositivos (celulares, tablets, laptops, otros) y tipos de reparación.
- **`nav-links.json`**: Enlaces de navegación del menú.
- **`services.json`**: Descripción de los servicios ofrecidos (servicio técnico, venta de reacondicionados, compra de equipos averiados).
- **`testimonials.json`**: Testimonios de clientes.
- **`ubication.json`**: Información de ubicación para mapas y descripciones de los talleres.

## Uso

El archivo `index.ts` actúa como punto de entrada y exporta un objeto que contiene todos los datos:

```typescript
import data from './index';

// Ejemplo de acceso:
console.log(data.main.title);
```
