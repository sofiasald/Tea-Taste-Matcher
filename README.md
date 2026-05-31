#  Tea Taste Matcher

Un programa interactivo en Python que analiza tus preferencias de sabor, cafeína, dulzor y temperatura para recomendarte el **té más famoso del mundo** que mejor se adapta a tu paladar. Incluye datos culturales sobre su país de origen.

##  Características
- Cuestionario interactivo con validación de entradas
-  Sistema de puntuación ponderado por coincidencias
-  Base de datos estructurada con 6 tés icónicos
-  Bucle principal para múltiples consultas sin reiniciar
-  Código modular, comentado y fácil de extender

## 📊 Cómo Funciona
1. **Recolección de preferencias**: El usuario responde sobre nivel de cafeína, dulzor, temperatura y notas de sabor.
2. **Validación**: El programa asegura que las respuestas coincidan con opciones válidas.
3. **Algoritmo de match**: Asigna puntos por cada coincidencia exacta en categorías y suma puntos extra por notas de sabor compartidas.
4. **Recomendación**: Muestra el té con mayor puntuación, su país y un dato cultural relevante.
5. **Reutilización**: Permite repetir el proceso con nuevas preferencias.

##  Estructura del Código
| Función/Elemento | Descripción |
|------------------|-------------|
| `TEAS` | Diccionario con datos de tés (nombre, atributos, notas, cultura) |
| `obtener_input_valido()` | Garantiza que el usuario elija opciones permitidas |
| `obtener_notas_sabor()` | Parsea y valida selección múltiple de sabores |
| `calcular_puntuacion()` | Lógica de scoring: categorías (peso 2-3) + notas (peso 1) |
| `mostrar_resultado()` | Formatea y imprime la recomendación final |
| `main()` | Orquesta el flujo, maneja el bucle y coordina funciones |

## Requisitos
- Python 3.6+ (no requiere librerías externas)
- Terminal/Consola compatible con Unicode (emojis)

## Cómo Ejecutar
bash
### 1. Clona o descarga el archivo
git clone <tu-repositorio>
cd tea-taste-matcher

### 2. Ejecuta directamente
python tea_matcher.py


#  Tea Taste Matcher
An interactive Python program that analyzes your preferences for flavor, caffeine, sweetness, and brewing temperature to recommend the world's most famous tea that best matches your palate. It also includes cultural facts about its country of origin.

## Features
- Interactive questionnaire with robust input validation
- Weighted scoring system based on preference matches
- Structured database featuring 6 iconic teas from around the world
- Main loop allowing multiple queries without restarting the program
- Modular, well-commented, and easily extensible code

## How It Works
1. **Preference Collection**: The user answers questions about preferred caffeine level, sweetness, brewing temperature, and flavor notes.
2. **Input Validation**: The program ensures all responses match valid options before proceeding.
3. **Matching Algorithm**: Assigns points for each exact category match and adds extra points for shared flavor notes.
4. **Recommendation**: Displays the tea with the highest score, its country of origin, and a relevant cultural fact.
5. **Reusability**: Prompts the user to run a new query or exit gracefully.

## Code Structure
| Function / Element | Description |
|--------------------|-------------|
| `TEAS` | Dictionary containing tea data (name, attributes, flavor notes, cultural facts) |
| `obtener_input_valido()` | Ensures user input matches allowed options |
| `obtener_notas_sabor()` | Parses and validates comma-separated flavor selections |
| `calcular_puntuacion()` | Scoring logic: category matches (weight 2-3) + flavor notes (weight 1) |
| `mostrar_resultado()` | Formats and prints the final recommendation |
| `main()` | Orchestrates the workflow, manages the loop, and coordinates all functions |

## 🛠️ Requirements
- Python 3.6+ (no external libraries required)
- Terminal/Console with Unicode support (for emojis and formatting)

## How to Run
```bash
# 1. Clone or download the repository
git clone <your-repository-url>
cd tea-taste-matcher

# 2. Run the program
python tea_matcher.py
