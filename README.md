# AI_Project – Sistema de recomendación con GitHub Copilot

Actividad formativa INACAP: *Tendencias emergentes en IA* (GitHub Copilot).

## Objetivo
Explorar GitHub Copilot como herramienta práctica para generar el código de un sistema de recomendación simple.

## Pasos realizados

1. **Cuenta GitHub:** ingresé a https://github.com/, inicié sesión y validé mi correo. Usé el plan gratuito y el acceso a Copilot.
   > 📸 *Captura: GitHub con la sesión iniciada*
2. **Repositorio:** con el botón *New* creé el repositorio público `AI_Project`, con archivo README.
   > 📸 *Captura: pantalla Create a new repository*
3. **Clonado local:** en el terminal integrado de VS Code:
   ```bash
   git clone https://github.com/moyarzunsalas-cmd/AI_Project.git
   cd AI_Project
   ```
   > 📸 *Captura: terminal con el clon*
4. **Archivo de código:** creé `recommendation_system.py` en VS Code.
   > 📸 *Captura: explorador con el archivo*
5. **Código con Copilot:** Copilot generó el modelo KNN con scikit-learn: carga de datos, división en entrenamiento y prueba, entrenamiento, evaluación y función `recommend()`.
   > 📸 *Captura: Copilot generando el código*
6. **Dataset de ejemplo:** `products.csv` con columnas `feature1`, `feature2`, `feature3` y `label`.
7. **Ejecución:** `python recommendation_system.py` muestra la precisión del modelo y un producto recomendado.
   > 📸 *Captura: salida en el terminal*
8. **Commit y Push:**
   ```bash
   git add .
   git commit -m "Add recommendation system example"
   git remote add origin https://github.com/moyarzunsalas-cmd/AI_Project.git
   git push -u origin main
   ```
   > 📸 *Captura: push exitoso*

## Requisitos

```bash
pip install numpy pandas scikit-learn
```

## Autor
Matías Oyarzún – INACAP
