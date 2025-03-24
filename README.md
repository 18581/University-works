# Control PID para Motor Paso a Paso

## Descripción
Implementación de control PID usando Transformadas de Laplace para un motor NEMA 17.

## Requisitos
- Python 3.8+
- Paquetes: `control`, `numpy`, `matplotlib`
- LaTeX (opcional para el informe)

## Uso
```bash
# Generar gráficos
python scripts/motor_response.py
python scripts/nyquist_analysis.py

# Compilar informe LaTeX
cd tex && pdflatex informe.tex
