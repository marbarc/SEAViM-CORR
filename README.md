# SEAViM-CORR — Fuzzy Logic–Based Expert System for Corrosion Diagnosis

**SEAViM-CORR** is an expert system that performs **image-based corrosion diagnosis** on metallic surfaces using a **fuzzy inference engine**.  
The software is delivered through two graphical interfaces:  
- **Desktop version** for detailed analysis.  
- **Mobile version** for in situ assessments.  
## Key Features
- Identification of **primary** and **secondary** corrosion mechanisms (pitting, filiform, stress-induced, galvanic, atmospheric).  
- Image-based workflow with standardized morphological indicators.  
- Dual-interface design: **desktop GUI** for laboratory/office use, **mobile GUI** for real-time field use.  
- Reproducible outputs that reduce subjectivity in visual inspection.  
## Requirements
- **Python 3.8+**  
- Desktop: `Tkinter`, `OpenCV`, `Numpy`  
- Mobile (Android): **Kivy**
##  Example installation:  
Clone the repository:
```bash
git clone https://github.com/marbarc/SEAViM-CORR.git
```
Install the dependencies:
```bash
pip install -r requirements.txt
```
## Execution
### Desktop version:
```bash
python desktop_app/main.py
```
The mobile version is developed with Kivy. Buildozer is required to compile the APK.
```bash
cd mobile_app
# Run Buildozer according to the project instructions
```
## License

This software is licensed under the terms of the MIT License. See `LICENSE.txt` for details.

## Suggested citation
Bárcenas-Castañeda, M., Calatayud-Velázquez, L. E., Lazo Cortes, M. S., Orozco del Castillo, M. G., & Castellanos Escamilla, V. A. (2025). Advancing Corrosion Detection: A Fuzzy Expert System with Desktop and Mobile Interfaces. SoftwareX. (Under review)
