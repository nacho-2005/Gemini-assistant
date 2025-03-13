# Gemini Assistant

Un asistente personal digital desarrollado con Google Gemini AI que te ayuda a organizar tu vida diaria.

## Características

- **Gestión de tareas**: Añadir, listar y completar tareas con fechas y recordatorios.
- **Gestión financiera**: Registrar gastos e ingresos, establecer saldo y ver resúmenes.
- **Categorización automática**: Clasificación inteligente de gastos en categorías predefinidas.
- **Procesamiento de lenguaje natural**: Entiende expresiones de tiempo como "mañana", "en 2 horas", "hace una semana", etc.
- **Interfaz conversacional**: Interactúa con el asistente de forma natural en español.

## Requisitos

- Python 3.8+
- Google Generative AI API Key
- Bibliotecas Python: google-generativeai, sqlite3, datetime, re

## Configuración

1. Clona este repositorio
2. Instala las dependencias: `pip install google-generativeai`
3. Configura tu API Key de Google Gemini en el archivo `app.py`
4. Ejecuta el asistente: `python app.py`

## Uso

El asistente entiende comandos en lenguaje natural como:

- "Añade una tarea para mañana a las 3pm: reunión con el equipo"
- "Muéstrame mis tareas pendientes"
- "Registra un gasto de 20 USD en comida"
- "Hace una semana compré un mueble por 200 USD"
- "Mi saldo actual es de 500 USD"
- "Muéstrame un resumen de mis gastos"

## Categorías de gastos predefinidas

1. Comida
2. Entretenimiento
3. Transporte
4. Ropa
5. Gastos imprevistos
6. Vivienda
7. Otros

## Licencia

MIT