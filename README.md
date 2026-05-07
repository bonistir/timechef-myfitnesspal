# TimeChef → MyFitnessPal

Sube capturas de pantalla del menú de TimeChef y obtén los macros del día listos para pegar en MyFitnessPal en segundos.

## El problema que resuelve

TimeChef no permite exportar los macros de forma directa. El proceso manual — mirar cada plato, sumar calorías, proteínas, carbohidratos y grasas, y crear un alimento en MFP — es lento y propenso a errores.

Esta app automatiza ese proceso: subes las capturas, la IA extrae los macros y te da el resultado listo para copiar.

## Cómo funciona

1. Introduce tu API key de OpenAI (se guarda solo en tu navegador, nunca sale de tu dispositivo)
2. Sube una o varias capturas del menú del día de TimeChef
3. La app analiza las imágenes con visión por IA y suma los macros totales
4. Copia el resultado al portapapeles y pégalo en MyFitnessPal

## Stack

- HTML + CSS + JavaScript vanilla — sin dependencias, sin build
- OpenAI API (GPT-4o con visión)
- Funciona 100% en el navegador

## Uso

No requiere instalación. Accede directamente en:

👉 **[https://bonistir.github.io/timechef-myfitnesspal](https://bonistir.github.io/timechef-myfitnesspal)**

O clona el repo y abre `index.html` en tu navegador.

## Privacidad

La API key se almacena únicamente en el `localStorage` de tu navegador. Las imágenes se envían directamente desde tu navegador a la API de OpenAI. Este servidor no almacena nada.

## Requisitos

- API key de OpenAI con acceso a `gpt-4o`
