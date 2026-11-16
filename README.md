# ProyectoDatosAlgoritmos

Coursework repository for a data structures and algorithms project. It contains small Google Colab notebooks that load image data stored as CSV matrices and display them with NumPy and Matplotlib, plus the PowerPoint files for the course deliveries.

## Features

- Notebooks (`imagen_1`, `imagen_2`, `vaca3`, `vaca4`) that upload a CSV file in Colab, read it into a pandas DataFrame, convert it to a NumPy matrix and render it as a grayscale image with `plt.imshow`.
- Row selection on the matrix with `matrix.compress(...)` (shown in `vaca4.ipynb`).
- Presentation files for the team presentation, the second delivery (research) and the third delivery.

## Tech stack

- Python (Jupyter notebooks, designed for Google Colab)
- pandas, NumPy, Matplotlib
- `google.colab.files` for uploading the input CSV files

## Project structure

```
imagen_1.ipynb, imagen_2.ipynb   Image-as-matrix notebooks
vaca3.ipynb, vaca4.ipynb         Image-as-matrix notebooks
EntregableN3/                    Third delivery (pptx)
Investigación-Proyecto/          Second delivery, research (pptx)
Presentación-equipos/            Team presentation (pptx)
```

## Getting started

The notebooks use `google.colab.files.upload()`, so they are meant to run in Google Colab:

1. Open a notebook in Colab (for example from the badge at the top of the notebook).
2. Run the cells and upload the CSV file when prompted. The CSV files are not included in this repository; `vaca4.ipynb` expects a file named `imagen 4.csv` with no header row.

To run locally you would need `pandas`, `numpy`, `matplotlib` and Jupyter, and replace the `google.colab` upload with a local file path.

## Context

University project for a data structures and algorithms course (the presentation files use an EAFIT template). No license is specified.
