# SEAViM-CORR

**SEAViM-CORR** (Sistema Experto para la Evaluación Visual de la Corrosión) es una herramienta basada en lógica difusa para diagnosticar diferentes tipos de corrosión en superficies metálicas a partir de imágenes. El sistema fue desarrollado con dos interfaces gráficas: una versión de escritorio y una versión móvil.

## Funcionalidades principales

- Diagnóstico automatizado de 5 tipos de corrosión comunes:
  - Corrosión puntual (CPP)
  - Corrosión filiforme (CFF)
  - Corrosión inducida por esfuerzo (CIE)
  - Corrosión galvánica (CGA)
  - Corrosión atmosférica (CAT)
- Análisis basado en imágenes con morfología estandarizada.
- Interfaz de escritorio para análisis detallado.
- Aplicación móvil para uso en campo.

## Requisitos de software

- Python 3.8+
- Tkinter
- OpenCV
- NumPy
- Kivy (solo para versión móvil)

## Instalación

Clona el repositorio:

```bash
git clone https://github.com/marbarc/SEAViM-CORR.git
```
Instala las dependencias:

```bash
pip install -r requirements.txt
```
## Ejecución

### Versión escritorio:
```bash
python desktop_app/main.py
```
La versión móvil está desarrollada con Kivy. Se requiere Buildozer para compilar el APK.
```bash
cd mobile_app
# Ejecutar Buildozer según las instrucciones del proyecto
```
## Licencia

Este software está licenciado bajo los términos de la licencia MIT. Consulta `LICENCE.txt` para más detalles.

## Cita sugerida

> Bárcenas-Castañeda, L. et al. (2025). SEAViM-CORR: A Fuzzy Logic-Based Expert System with Desktop and Mobile Interfaces for Corrosion Diagnosis. *SoftwareX*.
